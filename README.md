# Hi, I'm Nikita 👋

**Java Backend Developer** from Klaipėda, Lithuania. Self-taught, learning Java independently since age 13. I work across the full lifecycle of a backend system: architecture, implementation, testing, deployment, and maintenance.

- 🎓 Studying Java software development at **TECHIN** (Vilnius)
- 🔭 Building **[auto3.lt](https://auto3.lt)**, an automotive marketplace
- 💼 Open to **Junior / Java Backend Developer** roles: on-site, relocation, or remote in the EU
- 🧠 Interested in distributed systems, networking, performance, and application security

## 🚀 Projects

### auto3.lt · automotive marketplace · 2026–present

[auto3.lt](https://auto3.lt) is a marketplace for private sellers and dealerships: vehicle search, listing management, payments, and moderation. Full stack.

- **Java 25 + Spring Boot 4** REST API for listings, dealer profiles, favorites, saved searches, and admin workflows
- Advanced vehicle filtering with **JPA Criteria queries and PostgreSQL**, plus **Redis** caching and Hibernate query optimization
- Listing lifecycle: drafts, moderation, rejection and resubmission, paid plans, renewals, promotional placements
- Online payment gateway integration with account balances, transaction history, and automatic plan activation
- Asynchronous image pipeline: WebP conversion, watermarking, multiple variants, S3-compatible storage
- **Spring Security** with OAuth2, persistent sessions, role-based permissions, email/SMS verification, reCAPTCHA
- **Next.js + TypeScript** frontend using API types generated from OpenAPI
- Deployed with **GitLab CI/CD, Docker Compose, Nginx, and Cloudflare**

### MineComplex · multiplayer gaming platform · 2024–2026

Backend connecting game servers, a website, and a native launcher through shared services and APIs. Around **150 daily players**.

- Modular core on **gRPC + Protocol Buffers**: accounts, player presence, permissions, social features, statistics, and in-game economy across servers
- **Distributed player-state synchronization** with versioned snapshots and event updates, handling race conditions during server transfers and restoring state after connection failures
- Unified **Spring Boot REST API** for the website and launcher, with **MongoDB** and **PostgreSQL** (Spring Data JPA, Flyway)
- Authentication with **Spring Security, OAuth2, and RS256 JWT**: refresh-token rotation, token-reuse detection, session revocation, secure cookies
- Content distribution via S3-compatible storage and a CDN: content-addressed files, SHA-256 integrity checks, Ed25519-signed manifests, release publishing and rollback
- Automated tests with **JUnit 5** covering authentication, data consistency, storage, and API integration

## 🛠 Tech stack

![Java](https://img.shields.io/badge/Java_25-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat&logo=springsecurity&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=flat&logo=hibernate&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=flat)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat&logo=gitlab&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)

- **Backend:** Java 25, Spring Boot, Spring MVC, Spring Security, Spring Data JPA, Hibernate, gRPC, Protocol Buffers, REST, OpenAPI
- **Data:** PostgreSQL, MongoDB, Redis, Caffeine, Flyway
- **Infrastructure:** Docker, Docker Compose, Nginx, Linux, Cloudflare, AWS S3, GitLab CI/CD
- **Testing & build:** JUnit 5, Maven, Git
- **Frontend:** Next.js, React, TypeScript, Tailwind CSS

## 🌍 Languages

Russian (native) · English (fluent) · Lithuanian (conversational)

## 📫 Contact

✉️ sigamatute@gmail.com
