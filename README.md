# Enterprise Catalog & Membership RESTful API

A scalable backend service built with TypeScript and NestJS designed to manage digital inventory assets, user authorization, and personalized user engagement pipelines.

## Architecture & Core Capabilities
- **Modular Backend Framework:** Structured around NestJS controllers, services, and dependency injection following strict enterprise separation of concerns.
- **Relational Persistence Layer:** Entity-driven data modeling utilizing MySQL and TypeORM for high-integrity asset catalogs, account profiles, and customized user interaction matrices.
- **Security & Authorization:** Role-based access control (RBAC) and stateless authentication powered by JWT (JSON Web Tokens), complemented by global validation pipes and exception filters.
- **API Documentation & Contracts:** Automated OpenAPI specification generation via Swagger for streamlined client integration and contract verification.
- **Quality Assurance:** Comprehensive unit and end-to-end (E2E) test automation suites powered by Jest.

## Tech Stack
- **Runtime & Language:** Node.js, TypeScript
- **Framework:** NestJS
- **Database & ORM:** MySQL, TypeORM
- **Security:** JWT Authentication
- **Documentation:** Swagger / OpenAPI
- **Testing & Linting:** Jest, ESLint, Prettier

## Project Roadmap & Active Development
- [x] Core NestJS project scaffolding, TypeScript configuration, and testing infrastructure setup
- [ ] Relational entity schema integration (`AssetRegistry`, `AccountProfiles`, `UserInteractions`)
- [ ] JWT authentication guards and DTO validation middleware
- [ ] Swagger UI interactive endpoint documentation

## Getting Started

### Installation
```bash
npm install
