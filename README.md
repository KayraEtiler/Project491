# Project 491

![NestJS](https://img.shields.io/badge/NestJS-v7.0.0-red?logo=nestjs)
![TypeScript](https://img.shields.io/badge/TypeScript-v4.0-blue?logo=typescript)

![Status](https://img.shields.io/badge/status-development-yellowgreen)
![Version](https://img.shields.io/badge/version-0.0.1-blue)

[![renovate](https://img.shields.io/badge/renovate-enabled-%231A1F6C?logo=renovatebot)](https://app.renovatebot.com/dashboard)

## Project Description

UNIQUE ~ AI-POWERED ONLINE MOVIE STREAMING AND RECOMMENDING PLATFORM

This project, [Project 491], It is a graduation project developed using + NestJS REST API.

[Detailed documention](/docs/readme.md)

Demo: [Demo eklenecek]

## Table of Contents

- [Features](#özellikler)
- [Quick Start](#hızlı-başlangıç)
- [Easy Development](#rahat-geliştirme)
- [Links](#bağlantılar)
- [Automatic Update of Dependencies](#bağımlılıkların-otomatik-güncellenmesi)
- [Database Tools](#veritabanı-araçları)
- [Tests](#testler)
- [Tests in Docker](#docker-içinde-testler)
- [Test Benchmarking](#test-benchmarking)

## Features

- [x] Database ([typeorm](https://www.npmjs.com/package/typeorm)).
- [x] Seeding.
- [x] Config Service ([@nestjs/config](https://www.npmjs.com/package/@nestjs/config)).
- [x] Mailing ([nodemailer](https://www.npmjs.com/package/nodemailer)).
- [x] Sign up and log in with email.
- [x] Log in with social media (Apple, Facebook, Google, Twitter).
- [x] Admin and User roles.
- [x] I18N ([nestjs-i18n](https://www.npmjs.com/package/nestjs-i18n)).
- [x] File upload. Local and Amazon S3 supported.
- [x] Swagger.
- [x] E2E and unit testing.
- [x] Docker.
- [x] CI (Github Actions).

## Quick Start

```bash
git clone --depth 1 https://github.com/[kullanıcı_adınız]/[repo_adınız].git my-app
cd my-app/
cp env-example .env
docker compose up -d
docker compose up -d postgres adminer maildev

npm install
npm run migration:run
npm run seed:run
npm run start:dev
```

Durum kontrolü için

```bash
docker compose logs
```
