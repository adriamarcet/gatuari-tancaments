**Gatuari Tancaments**

Site files for Gatuar Tancaments landing page.

**Purpose:** This repo contains the site source (pages, components and layouts) used to present information for the Gatuari Tancaments project. It's an Astro site that uses Tailwind for styling and a small component set under `src/components` and `src/layouts`.

**Quick Start**

- **Prerequisites:** Node.js 18+ installed and `npm` available.
- **Install dependencies:**

```bash
npm install
```

- **Run development server:**

```bash
npm run dev
```

The dev server runs on `http://localhost:4321` by default.

- **Build for production:**

```bash
npm run build
```

- **Preview the production build locally:**

```bash
npm run preview
```

**Project Structure**

- **`public/`**: Static assets (images, favicon, webmanifest). Files here are served as-is.
- **`src/pages/`**: Top-level routes. Edit `src/pages/index.astro` to change the homepage content.
- **`src/layouts/`**: Page layout components used across pages (e.g. `BaseLayout.astro`, `Contact.astro`).
- **`src/components/`**: Reusable UI components (header, footer, accordion, carousel, KPI block).
- **`src/styles/`**: Global CSS and design variables (`globals.css`, `variables.css`).

Notable files and folders:

- `src/components/Header/header.astro` and `src/components/Footer/footer.astro`: Global header and footer markup.
- `src/layouts/BaseLayout.astro`: Main site layout wrapping pages.
- `src/layouts/IndexHeader.astro`, `IndexCarousel.astro`, `IndexFAQ.astro`, `IndexKPI.astro`: Homepage sections.

**How to edit content**

- Homepage: edit `src/pages/index.astro` and the index-specific layout/sections in `src/layouts/`.
- Reusable content: update or add components in `src/components/` and include them in layouts or pages.
- Styles: change color variables in `src/styles/variables.css` or add utility classes in `src/styles/globals.css`.

**Tailwind**

Tailwind is configured in `tailwind.config.cjs`. Customize utilities and theme values there.
