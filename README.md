# 📦 Monorepo Fullstack Template

This is a **Turborepo** template designed for full-stack web development, featuring a modular monorepo structure. It includes:

- **Next.js** - React framework for server-side rendering and static site generation.
- **TypeScript** - Strongly typed JavaScript for better development experience.
- **Tailwind CSS** - Utility-first CSS framework for rapid UI development.
- **shadcn/ui** - Pre-built UI components for a consistent design system.
- **Husky** - Pre-commit hooks for enforcing code quality.
- **Biome.js** - Tool for linter and formatter.

## 🚀 Getting Started

### Prerequisites
Make sure you have the following installed:
- [Node.js](https://nodejs.org/) (LTS >= 20)
- [pnpm](https://pnpm.io/) (>=9)

### Installation

1. Clone this repository:
   ```sh
   git clone https://github.com/VLyned/turborepo-fullstack-template.git
   ```

2. Install dependencies:
   ```sh
   cd turborepo-fullstack-template
   pnpm install
   ```

3. Run the development server:
   ```sh
   pnpm run dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) to view the app.

## 📂 Project Structure

```
📦monorepo-fullstack-template
 ┣ 📂.husky/               # Git hooks for pre-commit checks
 ┣ 📂.vscode/              # VSCode workspace settings
 ┣ 📂apps/                 # Application layer
 ┃ ┗ 📂web/                # Main Next.js web app
 ┃ ┃ ┣ 📂public/           # Static assets
 ┃ ┃ ┣ 📂src/              # Source files
 ┃ ┃ ┃ ┣ 📂app/            # Next.js app directory
 ┃ ┃ ┃ ┣ 📂components/     # Shared components
 ┃ ┃ ┃ ┣ 📂hooks/          # Custom React hooks
 ┃ ┃ ┃ ┗ 📂lib/            # Utility functions
 ┃ ┃ ┣ 📜next.config.ts    # Next.js configuration
 ┃ ┃ ┗ 📜package.json      # Web app dependencies
 ┣ 📂packages/             # Shared packages across the monorepo
 ┃ ┣ 📂config-tailwind/    # Tailwind CSS configuration package
 ┃ ┣ 📂config-typescript/  # TypeScript configuration presets
 ┃ ┗ 📂ui/                 # Reusable UI components package
 ┃ ┃ ┣ 📂src/components/   # UI components (button, card, etc.)
 ┃ ┃ ┣ 📂src/styles/       # Global styles
 ┃ ┃ ┗ 📜package.json      # UI library dependencies
 ┣ 📜.editorconfig         # Code formatting rules
 ┣ 📜.gitignore            # Git ignore file
 ┣ 📜.npmrc                # npm configuration
 ┣ 📜biome.json            # Biome configuration
 ┣ 📜package.json          # Root package dependencies
 ┣ 📜pnpm-workspace.yaml   # pnpm workspace configuration
 ┣ 📜turbo.json            # Turborepo configuration
 ┗ 📜README.md             # This file
```

## ✨ Features
- **Monorepo architecture** powered by [Turborepo](https://turbo.build/repo)
- **Optimized builds** and caching
- **Pre-configured Tailwind CSS** with dark mode support
- **Component-based UI with shadcn/ui**
- **Type-safe development** with TypeScript
- **Husky pre-commit hooks** for enforcing code quality
- **Biome formatting and linting** for coding standards

---

Configured by [VLyned - Diego Veramendi](https://github.com/VLyned)

