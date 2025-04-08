# React PWA Boot: Vite + React 19 + TS + Tailwind 4

This project serves as a starter template for building Progressive Web Applications (PWAs) using a modern tech stack. It's bootstrapped with Vite and pre-configured with React 19, TypeScript, Tailwind CSS 4, and `vite-plugin-pwa`.

## Tech Stack

* **Build Tool:** [Vite](https://vitejs.dev/)
* **Framework:** [React 19](https://react.dev/)
* **Language:** [TypeScript](https://www.typescriptlang.org/)
* **Styling:** [Tailwind CSS 4](https://tailwindcss.com/) (`@tailwindcss/vite`)
  * Dark Mode: Enabled via `class` strategy (`darkMode: 'class'`)
* **PWA:** [vite-plugin-pwa](https://vite-pwa-org.netlify.app/)
  * Manifest Generation
  * Service Worker (Workbox) with 'prompt' update strategy
  * PWA Asset Generation (`@vite-pwa/assets-generator`)
  * Includes a `PWABadge` component for handling update notifications.
* **Linting:** [ESLint](https://eslint.org/) with TypeScript support (`typescript-eslint`), React Hooks plugin.
* **Formatting:** [Prettier](https://prettier.io/)
* **Icons:** [Lucide React](https://lucide.dev/)

## Features

* ⚡️ Fast development and builds powered by Vite.
* ⚛️ Latest React 19 features.
* 🔒 Type safety with TypeScript.
* 🎨 Utility-first styling with Tailwind CSS 4 (including class-based dark mode).
* 📱 Progressive Web App ready:
  * Service Worker for offline capabilities (via Workbox).
  * Web App Manifest configured.
  * Automatic PWA asset generation from `public/favicon.svg`.
  * User prompt for app updates when new content is available.
* ✨ Code quality checks using ESLint and Prettier.
* ✅ Strict TypeScript configuration enabled.
* 🔍 Pre-configured with Lucide Icons for easy icon integration.

## Getting Started

### Prerequisites

* Node.js (LTS version recommended)
* npm, yarn, or pnpm

### Installation

1. Clone the repository:

    ```bash
    git clone <your-repo-url>
    cd netlooker-react-pwa-boot # Or your project directory name
    ```

2. Install dependencies:

    ```bash
    npm install
    # or
    yarn install
    # or
    pnpm install
    ```

### Development

Run the development server:

```bash
npm run dev
