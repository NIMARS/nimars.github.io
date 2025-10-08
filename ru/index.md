---
layout: default
title: "Кудашов Роман — Backend Engineer (Node.js/TS)"
lang: ru
permalink: /ru/
description: "Node.js/TS, Fastify/Express, PostgreSQL+Prisma, OpenAPI/Swagger, Docker. Алматы/Remote."
og_image: /assets/img/og-ru.png
---

# Кудашов Роман — Backend Engineer (Node.js/TypeScript)

- GitHub: <https://github.com/NIMARS> · LinkedIn: <https://www.linkedin.com/in/nimars/> · Email: <mailto:mars7010ry@gmail.com>

## Summary {#summary}

> Делаю бэкенд-API на Node.js/TS с валидацией (Zod), логированием (Pino) и документацией (OpenAPI/Swagger).
> PostgreSQL+Prisma: схема/миграции/индексы, JSONB/GIN, курсорная пагинация. JWT с refresh-ротацией (HttpOnly).

## Навыки {#skills}

**Backend:**       Node.js, TypeScript, Fastify/Express, REST, Middleware, Zod, Pino, централизованный error-handler, AsyncLocalStorage  
**Auth/Sec:**      JWT (access/refresh, ротация, jti, HttpOnly), CORS (credentials), Helmet, rate-limit (token bucket)  
**DB/ORM:**        PostgreSQL, Prisma (schema/migrate/seed), SQL (JOIN/индексы, JSONB, GIN), курсорная пагинация  
**Testing:**       Jest, Supertest  
**DevOps:**        Docker, docker-compose, Nginx, Linux, `.env` + Zod-валидация, GitHub Actions (lint/test/build)  
**Инструменты:**   Git, Postman/Insomnia, psql, Swagger/OpenAPI  
**Дополнительно:** Web3 (Solidity/ethers.js, IPFS — базово), C++ (STL — базово), React/Vite/Axios — базово

## Проекты {#projects}

### 🐾 AllAboutPet — Express→Fastify, TypeScript, Prisma, PostgreSQL

CRUD питомцев/событий/документов; JWT: access (header) + refresh (HttpOnly, ротация, сессии в БД); **Zod → OpenAPI**; загрузка файлов (Multer, **SHA-256**, локально → **MinIO/S3**); **курсорная пагинация**; **GIN** по JSONB-тегам; централизованный error-handler + **Pino**; `/health`, `/ready`.  
**DevOps/QA:** Dockerfile (multi-stage), docker-compose (api+pg[+redis+minio]), `.env.example` (+валидация), Nginx, Jest/Supertest (20+), ESLint/Prettier, GitHub Actions (lint+test+build)  
**Repo:** <https://github.com/NIMARS/all-about-pet>

### 📝 Notes API — Fastify, TypeScript, Prisma, PostgreSQL

CRUD заметок, фильтр по тегам; **Zod → JSON Schema**, **Pino**; PostgreSQL: **GIN** по `tags` (JSONB), курсор `(created_at,id)`.  
**Docs/DevOps/QA:** Swagger (/docs), docker-compose (api+pg), Jest/Supertest (20+)  
**Repo:** <https://github.com/NIMARS/notes-api>

### ✅ TodoApp — PERN, TypeScript

Back: Node.js + Express (REST), Front: React + Vite; БД: PostgreSQL; Swagger; интеграционные тесты (Jest + Supertest).  
**Repo:** <https://github.com/NIMARS/todo-pern-ts>

### 🧪 Engineering Data dApp — ethers.js, Solidity

Подписание **EIP-712**, подписка на события `Transfer`, ACL (admin/user), IPFS; контракты Solidity (Hardhat, тесты, OZ), скрипты деплоя; backend: ethers.js (ретраи RPC, rate-limit).

## Опыт {#experience}

**Ведущий специалист** · Институт информационных технологий (03.2022–10.2024) — PostgreSQL, серверные скрипты/интеграции, документация.  
**Ассистент** · СПбГМТУ (10.2020–10.2024) — материалы/практики по C++/Python/CS, проекты (Git, code review).  
**Инженер** · Технологии радиоконтроля и Гамма (04.2018–02.2022) — утилиты/библиотеки C++/Java.  

## Образование {#education}

**СПбГМТУ** — Прикладная математика (Бакалавр), Информатика и вычислительная техника (Магистр), Математическое моделирование, численные методы и комплексы программ (Педагог исследователь, аспирантура).

## Контакты {#contacts}

- GitHub: <https://github.com/NIMARS>  
- LinkedIn: <https://www.linkedin.com/in/nimars/>  
- Email: <mars7010ry@gmail.com>

### PDF

- [Скачать резюме (PDF)](/assets/CV.pdf)
