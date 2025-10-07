# nimars.github.io
<!-- Language switcher: две секции, русская по умолчанию открыта -->
<h3 align="right">
  <a href="#english-version">EN</a> | <a href="#русская-версия">RU</a>
</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-20.x-339933?logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-5.x-3178C6?logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-JSONB%2FGIN-4169E1?logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Express-Middleware-000000?logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/Prisma-ORM-2D3748?logo=prisma" />
  <img src="https://img.shields.io/badge/OpenAPI-Swagger-85EA2D?logo=swagger&logoColor=black" />
  <img src="https://img.shields.io/badge/Fastify-JSON_Schema-000000?logo=fastify" />
  <img src="https://img.shields.io/badge/Jest%2FSupertest-Tests-99425B?logo=jest&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-compose-2496ED?logo=docker&logoColor=white" />
</p>

---

## 🇷🇺 Русская версия

**Кудашов Роман** — Junior Backend Engineer (Node.js/TypeScript)  
Алматы / Remote · [GitHub](https://github.com/NIMARS) · [LinkedIn](https://www.linkedin.com/in/nimars/) · [Email](mailto:mars7010ry@gmail.com)

### Summary
Делаю бэкенд-API на **Node.js/TS** с валидацией (**Zod**), логированием (**Pino**) и документацией (**OpenAPI/Swagger**).  
**PostgreSQL + Prisma**: схема/миграции/индексы, **JSONB/GIN**, курсорная пагинация.  
**JWT** с refresh-ротацией (**HttpOnly cookie**), prod-штрихи: `/health` и `/ready`, **docker-compose**, **Nginx**.  
Английский C1 (IELTS).
Открыт к Junior/стажировке, remote/Алматы.

### Навыки
**Backend:**       Node.js, TypeScript, Fastify/Express, REST, Middleware, Zod, Pino, централизованный error-handler, AsyncLocalStorage  
**Auth/Sec:**      JWT (access/refresh, ротация, jti, HttpOnly), CORS (credentials), Helmet, rate-limit (token bucket)  
**DB/ORM:**        PostgreSQL, Prisma (schema/migrate/seed), SQL (JOIN/индексы, JSONB, GIN), курсорная пагинация  
**Testing:**       Jest, Supertest  
**DevOps:**        Docker, docker-compose, Nginx, Linux, `.env` + Zod-валидация, GitHub Actions (lint/test/build)  
**Инструменты:**   Git, Postman/Insomnia, psql, Swagger/OpenAPI  
**Дополнительно:** Web3 (Solidity/ethers.js, IPFS — базово), C++ (STL — базово), React/Vite/Axios — базово

---

### Проекты

#### 🐾 AllAboutPet — Express→Fastify, TypeScript, Prisma, PostgreSQL
CRUD питомцев/событий/документов; JWT: access (header) + refresh (HttpOnly, ротация, сессии в БД); **Zod → OpenAPI**; загрузка файлов (Multer, **SHA-256**, локально → **MinIO/S3**); **курсорная пагинация**; **GIN** по JSONB-тегам; централизованный error-handler + **Pino**; `/health`, `/ready`.  
**DevOps/QA:** Dockerfile (multi-stage), docker-compose (api+pg[+redis+minio]), `.env.example` (+валидация), Nginx, Jest/Supertest (20+), ESLint/Prettier, GitHub Actions (lint+test+build)  
**Repo:** https://github.com/NIMARS/all-about-pet

#### 📝 Notes API — Fastify, TypeScript, Prisma, PostgreSQL
CRUD заметок, фильтр по тегам; **Zod → JSON Schema**, **Pino**; PostgreSQL: **GIN** по `tags` (JSONB), курсор `(created_at,id)`.  
**Docs/DevOps/QA:** Swagger (/docs), docker-compose (api+pg), Jest/Supertest (20+)  
**Repo:** https://github.com/NIMARS/notes-api 

#### ✅ TodoApp — PERN, TypeScript
Back: Node.js + Express (REST), Front: React + Vite; БД: PostgreSQL; Swagger; интеграционные тесты (Jest + Supertest).  
**Repo:** https://github.com/NIMARS/todo-pern-ts

#### 🧪 Engineering Data dApp — ethers.js, Solidity
Подписание **EIP-712**, подписка на события `Transfer`, ACL (admin/user), IPFS; контракты Solidity (Hardhat, тесты, OZ), скрипты деплоя; backend: ethers.js (ретраи RPC, rate-limit).  

---

### Опыт и образование (коротко)
**Ведущий специалист** · Институт информационных технологий (03.2022–10.2024) — PostgreSQL (индексы/EXPLAIN), серверные скрипты/интеграции, документация.  
**Ассистент** · СПбГМТУ (10.2020–10.2024) — материалы/практики по C++/Python/CS, проекты (Git, code review).  
**Инженер** · Технологии радиоконтроля и Гамма (04.2018–02.2022) — утилиты/библиотеки C++/Java.  
**СПбГМТУ** — Прикладная математика (Бакалавр), Информатика и вычислительная техника (Магистр), Аспирантура (матмоделирование).

---

### Roadmap (что сейчас допиливаю)
Redis rate-limit/блок-листы · Testcontainers (Postgres) · OpenTelemetry/Prometheus · GH Actions (deploy) · MinIO pre-signed URL

---

## 🇬🇧 English version

**Roman Kudashov** — Junior Backend Engineer (Node.js/TypeScript)  
Almaty / Remote · [GitHub](https://github.com/NIMARS) · [LinkedIn](https://www.linkedin.com/in/nimars/) · [Email](mailto:mars7010ry@gmail.com)

### Summary
I build backend APIs with **Node.js/TypeScript**, using **Zod** for validation, **Pino** for structured logs, and **OpenAPI/Swagger** for docs.  
**PostgreSQL + Prisma**: schema/migrations/indexes, **JSONB/GIN**, **cursor pagination**.  
**JWT** with refresh rotation (**HttpOnly cookie**). Production bits: `/health`, `/ready`, **docker-compose**, **Nginx**.  
English C1 (IELTS). Open to Junior/Intern roles, remote/Almaty.

### Skills
**Backend:** Node.js, TypeScript, Fastify/Express, REST, Middleware, Zod, Pino, centralized error handler, AsyncLocalStorage  
**Auth/Sec:** JWT (access/refresh, rotation, jti, HttpOnly), CORS (credentials), Helmet, rate-limit (token bucket)  
**DB/ORM:** PostgreSQL, Prisma (schema/migrate/seed), SQL (JOIN/indexes, JSONB, GIN), cursor pagination  
**Testing:** Jest, Supertest  
**DevOps:** Docker, docker-compose, Nginx, Linux, `.env` + Zod validation, GitHub Actions (lint/test/build)  
**Tools:** Git, Postman/Insomnia, psql, Swagger/OpenAPI  
**Additionally:** Web3 (Solidity/ethers.js, IPFS — basics), C++ (STL — basics), React/Vite/Axios — basics

---

### Projects

#### 🐾 AllAboutPet — Express→Fastify, TypeScript, Prisma, PostgreSQL
CRUD for pets/events/docs; JWT: access (header) + refresh (HttpOnly, rotation, DB sessions); **Zod → OpenAPI**; uploads (Multer, **SHA-256**, local → **MinIO/S3**); **cursor pagination**; **GIN** for JSONB tags; centralized error handler + **Pino**; `/health`, `/ready`.  
**DevOps/QA:** Dockerfile (multi-stage), docker-compose (api+pg[+redis+minio]), `.env.example` (+validation), Nginx, Jest/Supertest (20+), ESLint/Prettier, GitHub Actions (lint+test+build)  
**Repo:** https://github.com/NIMARS/all-about-pet · **Swagger:** _add link_ · **Demo:** _optional_

#### 📝 Notes API — Fastify, TypeScript, Prisma, PostgreSQL
CRUD + tag filter; **Zod → JSON Schema**, **Pino**; PostgreSQL: **GIN** on `tags` (JSONB), cursor `(created_at,id)`.  
**Docs/DevOps/QA:** Swagger (/docs), docker-compose (api+pg), Jest/Supertest (20+)  
**Repo:** https://github.com/NIMARS/notes-api · **Swagger:** _add link_

#### ✅ TodoApp — PERN, TypeScript
Backend: Node.js + Express (REST), Frontend: React + Vite; PostgreSQL; Swagger; integration tests (Jest + Supertest).  
**Repo:** https://github.com/NIMARS/todo-pern-ts

#### 🧪 Engineering Data dApp — Fastify, TS, ethers.js, Solidity
**EIP-712** signatures, `Transfer` event subscription, ACL (admin/user), IPFS; Solidity contracts (Hardhat, tests, OZ), deploy scripts; backend: ethers.js (RPC retries, rate-limit).  
**Repo:** _add link_

---

## Contacts
- GitHub: https://github.com/NIMARS  
- LinkedIn: https://www.linkedin.com/in/nimars/  
- Email: mars7010ry@gmail.com

---

### PDF
- [Скачать резюме (PDF)](./CV.pdf)

