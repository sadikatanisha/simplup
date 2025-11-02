# Simplup

A monorepo project with Next.js web app, NestJS API, and worker services.

## Structure

- `apps/web`: Next.js app (App Router)
- `services/api`: Backend service (NestJS/Fastify or Express)
- `services/worker`: Worker service (BullMQ + FFmpeg hooks)
- `packages/shared`: Shared types, constants, utils
- `infra`: Terraform skeleton (optional)

## Getting Started

1. Install dependencies: `npm install`
2. Start development: `npm run dev`
