# Cutroom

Cutroom is an AI-assisted video production platform built to turn a topic into a publishable short-form video through a structured, multi-stage workflow. I designed it as a full-stack product that combines orchestration, APIs, database-backed state, and React-based video rendering in one system.

## Why this project stands out

- Built a **7-stage production pipeline** that coordinates research, scripting, voice, music, visuals, editing, and publishing
- Developed with **TypeScript, Next.js, Prisma, PostgreSQL, and Remotion**
- Shipped a product with **tested API routes, pipeline logic, and stage handlers** (300+ tests currently passing locally)
- Designed for **real workflow visibility**, including pipeline progress, stage ownership, and template-driven output
- Extended the platform with **15+ reusable video templates** for different content formats

## Skills demonstrated

- Full-stack application architecture
- API design and backend workflow orchestration
- Type-safe data modeling with Prisma
- Automated testing with Vitest
- Frontend development with React and Next.js
- Programmatic video generation with Remotion
- Product thinking for creator tools and internal platforms

## Tech stack

| Area | Tools |
| --- | --- |
| Frontend | Next.js 14, React 18, Tailwind CSS |
| Backend | Next.js API Routes, TypeScript |
| Data | Prisma, PostgreSQL |
| Video | Remotion |
| Testing | Vitest, Testing Library |

## Selected highlights

- Created a dashboard and API surface for managing pipelines end to end
- Modeled stage-by-stage ownership, handoffs, and status tracking for multi-agent workflows
- Built reusable rendering templates so one pipeline can support multiple video styles
- Documented supporting systems including the [API](docs/API.md), [deployment flow](docs/DEPLOYMENT.md), and [template system](docs/TEMPLATE_SYSTEM.md)

## Run locally

```bash
pnpm install
cp .env.example .env.local
pnpm db:push
pnpm dev
```

Open `http://localhost:3000` to view the app.

## Additional documentation

- [API Reference](docs/API.md)
- [Deployment Guide](docs/DEPLOYMENT.md)
- [Template System](docs/TEMPLATE_SYSTEM.md)
- [Contributing](CONTRIBUTING.md)

## License

[MIT](LICENSE)
