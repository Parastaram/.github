# Parastaram Project

The **Parastaram Project** is a modular system consisting of a **backend service** and a **frontend service**, built with clean architecture principles to ensure maintainability and scalability.

Developed by: [Ali Moradi](https://github.com/AliDeWeb)

---

## 📦 Repositories

### 1. Backend Service – [parastaram-backend-service](https://github.com/Parastaram/Main_Backend_Service)

The core backend service built with layered architecture and Onion Architecture. It is structured into **Domain**, **Application**, **Infrastructure**, and **Client** layers.

**Tech Stack:**

- Node.js
- NestJS
- TypeORM
- PostgreSQL
- Docker & Docker Compose
- Swagger

**Development Notes:**

- Follow strict separation of concerns with inward dependencies
- Naming conventions: camelCase (variables/functions), kebab-case (folders/files), snake_case (entity fields)
- All DTOs must be validated with `class-validator` and documented using Swagger's `@ApiProperty()`

---

### 2. Frontend Service – [parastaram-frontend-service](https://github.com/Parastaram/Main_Frontend_Service)

The frontend interface built with **Next.js (App Router)** and **React Query**, organized for scalable and modular development.

**Tech Stack:**

- Next.js
- React.js
- TypeScript
- Tailwind CSS
- React Query

**Project Structure:**

- `app/`: App Router structure and routes
- `components/`: Reusable UI components
- `services/`: API interactions using React Query
- `lib/`: Shared utility functions
- `types/`: Global TypeScript types and interfaces

---

## 📋 Contribution Guidelines

All contributors must:

1. Follow the existing structure and naming conventions.
2. Run lint and test commands before submitting a pull request.
3. Use [Conventional Commits](https://www.conventionalcommits.org) for commit messages.
4. Respect the layered architecture and dependency direction.

---

## 📜 License

This project is licensed under the [Custom](./LICENSE) License.
