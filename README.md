# Modern CSS Reset Monorepo

This is the monorepo for managing multiple JavaScript/TypeScript projects under one repository. The monorepo is organized using [Turborepo](https://turbo.build/repo) for task orchestration.

## Packages

### 1. **@smashweaver/resetcss**

This is a TypeScript package providing a modern CSS reset based on Josh Comeau's guide.

- **Package location**: `packages/reset-css`
- **CSS reset file**: [`reset.css`](https://github.com/smashweaver/resetcss/blob/main/packages/reset-css/reset.css)
- **License**: MIT

### 2. **Next.js Demo App (dummy)**

This is a demo Next.js project that demonstrates how to consume the reset-css package.

- **App location**: apps/dummy
- **Description**: This project serves as a demonstration of integrating the @smashweaver/resetcss package into a Next.js application.

#### How to Install:

You can install it in your Next.js (or any other project) by adding the following dependency:

```bash
npm install @smashweaver/resetcss
```
