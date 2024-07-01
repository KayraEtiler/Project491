# Project 491

![NestJS](https://img.shields.io/badge/NestJS-v7.0.0-red?logo=nestjs)
![TypeScript](https://img.shields.io/badge/TypeScript-v4.0-blue?logo=typescript)

![Status](https://img.shields.io/badge/status-development-yellowgreen)
![Version](https://img.shields.io/badge/version-0.0.1-blue)

[![renovate](https://img.shields.io/badge/renovate-enabled-%231A1F6C?logo=renovatebot)](https://app.renovatebot.com/dashboard)

## Proje Açıklaması

Bu proje, [Project 491], NestJS REST API +  kullanılarak geliştirilen bir bitirme projesidir. Temel amacı, [Projemizin kısaca amacı].

[Detaylı dokümantasyon](/docs/readme.md)

Demo: [Demo eklenecek]

## İçindekiler Tablosu

- [Özellikler](#özellikler)
- [Hızlı Başlangıç](#hızlı-başlangıç)
- [Rahat Geliştirme](#rahat-geliştirme)
- [Bağlantılar](#bağlantılar)
- [Bağımlılıkların Otomatik Güncellenmesi](#bağımlılıkların-otomatik-güncellenmesi)
- [Veritabanı Araçları](#veritabanı-araçları)
- [Testler](#testler)
- [Docker İçinde Testler](#docker-içinde-testler)
- [Test Benchmarking](#test-benchmarking)

## Özellikler

- [x] Veritabanı ([typeorm](https://www.npmjs.com/package/typeorm)).
- [x] Seeding.
- [x] Config Servisi ([@nestjs/config](https://www.npmjs.com/package/@nestjs/config)).
- [x] Mailing ([nodemailer](https://www.npmjs.com/package/nodemailer)).
- [x] Email ile kayıt olma ve giriş yapma.
- [x] Sosyal medya ile giriş yapma (Apple, Facebook, Google, Twitter).
- [x] Admin ve Kullanıcı rolleri.
- [x] I18N ([nestjs-i18n](https://www.npmjs.com/package/nestjs-i18n)).
- [x] Dosya yükleme. Yerel ve Amazon S3 destekli.
- [x] Swagger.
- [x] E2E ve birim testleri.
- [x] Docker.
- [x] CI (Github Actions).

## Hızlı Başlangıç

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
