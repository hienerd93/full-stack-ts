# Turborepo kitchen sink starter

This Turborepo starter is maintained by hienerd93.

## What's inside?

This Turborepo includes the following packages and apps:

### Apps and Packages

- `backend`: an [Express](https://expressjs.com/) server
- `frontend`: a [Vite](https://vitejs.dev/) single page app
- `@repo/eslint-config`: ESLint configurations used throughout the monorepo
- `@repo/jest-presets`: Jest configurations
- `@repo/logger`: isomorphic logger (a small wrapper around console.log)
- `@repo/ui`: a dummy React UI library (which contains `<CounterButton>` and `<Link>` components)
- `@repo/typescript-config`: tsconfig.json's used throughout the monorepo

Each package and app is 100% [TypeScript](https://www.typescriptlang.org/).

### Utilities

This Turborepo has some additional tools already setup for you:

- [TypeScript](https://www.typescriptlang.org/) for static type checking
- [ESLint](https://eslint.org/) for code linting
- [Jest](https://jestjs.io) test runner for all things JavaScript
- [Prettier](https://prettier.io) for code formatting
