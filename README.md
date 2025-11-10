# Starter Project Monorepo

This is a modern monorepo setup for web projects, powered by [Turborepo](https://turborepo.com/) and [pnpm](https://pnpm.io/). It provides a scalable foundation for building, testing, and sharing code across multiple apps and packages.

## Monorepo Structure

```
├── apps/
│   ├── docs/   # Next.js documentation site
│   └── web/    # Next.js main web app
├── packages/
│   ├── ui/     # Shared React component library
│   ├── eslint-config/      # Shared ESLint config
│   └── typescript-config/  # Shared TypeScript config
├── package.json
├── pnpm-workspace.yaml
├── turbo.json
└── README.md
```

## Key Features

- **Next.js** apps for web and docs
- **Shared UI library** for React components
- **Centralized ESLint and TypeScript configs**
- **TypeScript** everywhere
- **Jest** for unit testing in packages
- **Prettier** for code formatting
- **Turborepo** for fast builds, caching, and task orchestration
- **pnpm** for efficient monorepo dependency management

## Getting Started

1. **Install dependencies:**
   ```sh
   pnpm install
   ```
2. **Run development servers:**

   ```sh
   pnpm dev
   ```

   - Visit `apps/web` at [http://localhost:3000](http://localhost:3000)
   - Visit `apps/docs` at [http://localhost:3001](http://localhost:3001)

3. **Build all apps and packages:**
   ```sh
   pnpm build
   ```
4. **Run tests:**
   ```sh
   pnpm test
   ```
5. **Lint and format code:**
   ```sh
   pnpm lint
   pnpm format
   ```

## Apps & Packages

- **apps/web**: Main Next.js web application
- **apps/docs**: Documentation site (Next.js)
- **packages/ui**: Shared React component library (with Jest tests)
- **packages/eslint-config**: Shared ESLint config for all projects
- **packages/typescript-config**: Shared TypeScript config for all projects

## Tooling & Developer Experience

- **Prettier**: Auto-formats code on save
- **ESLint**: Lints code for quality and consistency
- **Jest**: Unit tests for UI components
- **Turbo**: Fast builds, caching, and filtering

## Scripts

Common scripts (run from repo root):

- `pnpm dev` — Start all dev servers
- `pnpm build` — Build all apps and packages
- `pnpm lint` — Lint all code
- `pnpm format` — Format code with Prettier
- `pnpm test` — Run all tests

## Useful Links

- [Turborepo Docs](https://turborepo.com/docs)
- [Next.js Docs](https://nextjs.org/docs)
- [pnpm Docs](https://pnpm.io/)
- [Jest Docs](https://jestjs.io/)
- [ESLint Docs](https://eslint.org/)
- [Prettier Docs](https://prettier.io/)
