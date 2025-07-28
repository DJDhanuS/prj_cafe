# prj_cafe

A fullstack web application starter using Node.js, PostgreSQL, ReactJS (Next.js), TailwindCSS, following microfrontend and microservice architectures.

## Structure

- `apps/frontend`: Next.js frontend with Tailwind (microfrontend)
- `apps/backend`: Node.js microservices (API gateway, shared logic)
- `services/*`: Individual microservices (auth, orders, products)
- `packages/ui`: Shared UI components (for microfrontends)
- `packages/db`: Database utilities (e.g., Prisma or Sequelize for PostgreSQL)

## Getting Started

1. Clone the repo
2. Install dependencies in each app/service/package
3. Use `docker-compose up` to start local development environment
