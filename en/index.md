---
layout: default
title: "Roman Kudashov — Backend Engineer (Node.js/TS)"
lang: en
permalink: /en/
description: "Node.js/TS, Fastify/Express, PostgreSQL+Prisma, OpenAPI/Swagger, Docker. Almaty/Remote."
og_image: /assets/img/og-en.png
---

# Roman Kudashov — Backend Engineer (Node.js/TypeScript)

- GitHub: <https://github.com/NIMARS> · LinkedIn: <https://www.linkedin.com/in/nimars/> · Email: <mailto:mars7010ry@gmail.com>

## Summary {#summary}

> I build backend APIs with Node.js/TS using Zod, Pino and OpenAPI/Swagger.
> PostgreSQL+Prisma: schema/migrations/indexes, JSONB/GIN, cursor pagination. JWT with refresh rotation (HttpOnly).

## Skills {#skills}

**Backend:** Node.js, TypeScript, Fastify/Express, REST, Middleware, Zod, Pino, centralized error handler, AsyncLocalStorage  
**Auth/Sec:** JWT (access/refresh, rotation, jti, HttpOnly), CORS (credentials), Helmet, rate-limit (token bucket)  
**DB/ORM:** PostgreSQL, Prisma (schema/migrate/seed), SQL (JOIN/indexes, JSONB, GIN), cursor pagination  
**Testing:** Jest, Supertest  
**DevOps:** Docker, docker-compose, Nginx, Linux, `.env` + Zod validation, GitHub Actions (lint/test/build)  
**Tools:** Git, Postman/Insomnia, psql, Swagger/OpenAPI  
**Additionally:** Web3 (Solidity/ethers.js, IPFS — basics), C++ (STL — basics), React/Vite/Axios — basics

## Projects {#projects}

### 🐾 AllAboutPet — Express→Fastify, TypeScript, Prisma, PostgreSQL

CRUD for pets/events/docs; JWT: access (header) + refresh (HttpOnly, rotation, DB sessions); **Zod → OpenAPI**; uploads (Multer, **SHA-256**, local → **MinIO/S3**); **cursor pagination**; **GIN** for JSONB tags; centralized error handler + **Pino**; `/health`, `/ready`.  
**DevOps/QA:** Dockerfile (multi-stage), docker-compose (api+pg[+redis+minio]), `.env.example` (+validation), Nginx, Jest/Supertest (20+), ESLint/Prettier, GitHub Actions (lint+test+build)  
**Repo:** <https://github.com/NIMARS/all-about-pet>

### 📝 Notes API — Fastify, TypeScript, Prisma, PostgreSQL

CRUD + tag filter; **Zod → JSON Schema**, **Pino**; PostgreSQL: **GIN** on `tags` (JSONB), cursor `(created_at,id)`.  
**Docs/DevOps/QA:** Swagger (/docs), docker-compose (api+pg), Jest/Supertest (20+)  
**Repo:** <https://github.com/NIMARS/notes-api>

### ✅ TodoApp — PERN, TypeScript

Backend: Node.js + Express (REST), Frontend: React + Vite; PostgreSQL; Swagger; integration tests (Jest + Supertest).  
**Repo:** <https://github.com/NIMARS/todo-pern-ts>

### 🧪 Engineering Data dApp — Fastify, TS, ethers.js, Solidity

**EIP-712** signatures, `Transfer` event subscription, ACL (admin/user), IPFS; Solidity contracts (Hardhat, tests, OZ), deploy scripts; backend: ethers.js (RPC retries, rate-limit).  

## Experience {#experience}

**Lead Specialist** · Institute of Information Technologies (03.2022–10.2024) — PostgreSQL, server-side scripts/integrations, documentation.
**Assistant** · St. Petersburg State Marine Technical University (10.2020–10.2024) — teaching materials and practice in C++/Python/Computer Science, projects (Git, code review).
**Engineer** · Radio Control Technologies and Gamma (04.2018–02.2022) — C++/Java utilities and libraries.

## Education {#education}

**SPbSMTU** — B.Sc. in Applied Mathematics, M.Sc. in Computer Science and Engineering, Ph.D. studies (postgraduate study) in Mathematical Modeling, Numerical Methods, and Software Systems (Teacher Researcher).

## Contacts {#contacts}

- GitHub: <https://github.com/NIMARS>  
- LinkedIn: <https://www.linkedin.com/in/nimars/>  
- Email: <mars7010ry@gmail.com>

### PDF

- [Download CV (PDF)](/assets/CV.pdf)
