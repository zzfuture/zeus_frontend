# ⚡ URL Shortener

This is a simple URL shortener project that allows users to enter a really long URL, generate a shorter version and quickly redirect to the original destination. The web page is developed using Astro and JavaScript.

## Features

- Quickly shortens long URLs.
- Automatically redirects to the original URL.
- Simple and fast to use.

## Technologies Used

- Astro**: Framework for building fast and efficient web sites.
- JavaScript**: URL shortener logic.

## Installation and Execution

Follow the steps below to install and run the project locally.

### Prerequisites

- A modern JavaScript interpreter (e.g. Node.js v16 or higher).
- A compatible package manager such as `pnpm`, `npm` or `yarn`.

### Commands

The following commands are available for project management, regardless of the package manager you use:

| Command | Action |
| :------------------------- | :------------------------------------------------ |
| `pnpm install` | Installs the necessary dependencies.              |
| | `pnpm run dev` | Start the development server on `localhost:4321`. |
| `pnpm run build` | Generates the production version in the `./dist/` folder. |
| `pnpm run preview` | Preview the production site locally.    |
| `pnpm run astro ...` | Execute CLI commands such as `astro add` or `astro check`. |
| `pnpm run astro -- --help` | Displays help for Astro CLI commands.     |

> **Note**: You can replace `pnpm` with the package manager of your choice (`npm` or `yarn`).

## 🚀 Project Structure

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
│       └── login.astro #WIP
└── package.json
└── astro.config.mjs
└── tsconfig.json
```