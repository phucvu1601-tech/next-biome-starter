# Next Biome Starter

A minimal **Next.js starter** with essential development tooling preconfigured for a clean and consistent workflow.

## Stack

- Next.js
- TypeScript
- Biome
- Commitlint
- Lefthook
- shadcn/ui

## Setup

### 1. Init Next.js

Project initialized with **Next.js + TypeScript** using the `src` directory structure.

### 2. Biome

Linting and formatting are handled by **Biome** — a fast, all-in-one toolchain that replaces both ESLint and Prettier:

- `biome.json`

Ensures consistent code style and catches issues across the project with a single tool.

### 3. Commitlint + Lefthook

Commit messages follow **Conventional Commits**.

- `commitlint.config.mjs`
- `lefthook.yml`

Git hooks run checks before committing.

Example:

```
feat: add login page
fix: resolve navbar bug
chore: update dependencies
```

### 4. shadcn/ui

UI components powered by **shadcn/ui**.
Components are added directly to the project and can be customized as needed.

## Project Structure

```
.
├── public/
├── src/
│   ├── app/
│   ├── components/
│   │   └── ui/
│   └── lib/
├── biome.json
├── commitlint.config.mjs
├── lefthook.yml
├── next.config.ts
├── tsconfig.json
└── package.json
```

## Usage

Clone or download the source code, then initialize a new repository:

```bash
git init
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```