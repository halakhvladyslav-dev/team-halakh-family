# Team Halakh Family

Initial project setup with Next.js, TypeScript, Tailwind CSS,
and shadcn/ui (Base UI, Nova preset).

The application is located in the repository root.

## Requirements

- Node.js 22 or 24 LTS
- pnpm 10.34.6

## Getting started

Install dependencies:

```bash
pnpm install --frozen-lockfile
```

Start the development server:

```bash
pnpm dev
```

Open http://localhost:3000 in your browser.

## Checks

```bash
pnpm lint
pnpm build
```

## Production preview

After building the application:

```bash
pnpm start
```

## Project structure

- app/ - pages, root layout, and global styles
- components/ui/ - shadcn/ui components
- lib/ - shared utilities

The home page includes a shadcn/ui button as a setup example.
