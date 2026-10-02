# My CV Website

A personal CV / portfolio website built with **Astro**, **TypeScript**, and **Tailwind CSS**. The site presents my education, work experience, skills, and projects in a fast, responsive, single-page layout.

## Purpose

This project serves as my online curriculum vitae (CV). It is meant to:

- Present my professional background, skills, and projects in a clean, accessible format
- Be easily shareable via a link (e.g., in job applications or on LinkedIn)
- Serve as a lightweight, fast-loading alternative to a PDF resume
- Be easy for me to update and redeploy as my experience grows

## Tech Stack

- [![Astro][Astro-badge]][Astro-url] — static site framework used to build and bundle the site
- [![TypeScript][TypeScript-badge]][TypeScript-url] — typed superset of JavaScript used for the site's components and scripts
- [![Tailwind CSS][Tailwind-badge]][Tailwind-url] — utility-first CSS framework used for styling

## Prerequisites

Before installing, make sure you have the following installed on your machine:

- [Node.js](https://nodejs.org/) (v18 or later recommended)
- npm (comes bundled with Node.js) — or an alternative package manager such as `pnpm` or `yarn`

You can check your installed versions with:

```bash
node -v
npm -v
```

## Dependencies

This project relies on the following external dependencies (managed via `package.json`):

| Dependency | Purpose |
|---|---|
| `astro` | Core framework for building and serving the site |
| `typescript` | Type-checking and TypeScript support |
| `tailwindcss` | Utility classes for styling |
| `@astrojs/tailwind` | Integration that connects Tailwind CSS with Astro |

All dependencies are installed automatically in the installation step below — you do not need to install them individually.

## Installation

1. Clone or copy the project files onto your machine:

   ```bash
   git clone https://github.com/Rolands-Prohorovs/CV.git
   cd CV
   ```

2. Install the project dependencies:

   ```bash
   npm install
   ```

## Usage

**Run the development server** (with hot-reload, for local editing):

```bash
npm run dev
```

The site will be available at `http://localhost:4321` by default.

**Build the site for production:**

```bash
npm run build
```

This generates a static, optimized version of the site in the `dist/` folder, ready to be deployed to any static hosting service (e.g., Netlify, Vercel, GitHub Pages).

**Preview the production build locally:**

```bash
npm run preview
```

## Project Structure

```
/
├── public/              # Static assets (logos, images, favicon)
├── src/
│   ├── pages/           # Site pages (index.astro)
│   └── styles/          # Global Tailwind/CSS styles
├── astro.config.mjs     # Astro configuration
├── tsconfig.json        # TypeScript configuration
└── package.json         # Project metadata and dependencies
```

<!-- ROADMAP -->
## Roadmap
- ✅ landing page
- ✅ About Me page
- ✅ Company cooloboration project page
   - ⬜ style and layout of this page
- ⬜ Work experience page 
## Maintainer

This project is maintained by **Rolands Prohorovs**.

- Email: roland.prohorov@inbox.lv

## License

This project is for personal use.


[Astro-badge]: https://img.shields.io/badge/Astro-BC52EE?style=for-the-badge&logo=astro&logoColor=white
[Astro-url]: https://astro.build/
[TypeScript-badge]: https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white
[TypeScript-url]: https://www.typescriptlang.org/
[Tailwind-badge]: https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white
[Tailwind-url]: https://tailwindcss.com/