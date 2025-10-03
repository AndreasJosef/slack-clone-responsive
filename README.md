# Modern CSS Starter

A minimal **content-first landing page starter** built with modern CSS.  

This project gives you a professional baseline for learning, prototyping, or shipping lightweight pages without relying on heavy frameworks.

---

## Quick start

You can start a new project in two ways:

### Option A: GitHub template  
1. Click **Use this template** at the top of this repo on GitHub.  
2. Create a new repository from it.  
3. Clone your new repo locally and run:

```bash
npm install
npm run dev
````

### Option B: Degit (one-liner)

If you prefer working directly from the terminal:

```bash
npx degit AndreasJosef/modern-css-starter my-new-project
cd my-new-project
npm install
npm run dev
```

This copies the latest version of Modern CSS Starter into `my-new-project` without including the Git history.


## Features

* **Content-first workflow** — start with semantic HTML, let design emerge from content
* **Cascade layers** — predictable overrides (`tokens`, `base`, `blocks`, `utilities`)
* **Design tokens** — surfaces, ink, brand colors, type scale, spacing, layout knobs
* **Modern CSS** — custom properties, `clamp()`, Grid, Flexbox, container queries ready
* **No frameworks** — artisanal CSS, fully under your control
* **Vite dev server** — fast hot reload, easy to extend if needed


## Philosophy

This starter is designed to help you **learn CSS deeply** while always having a professional baseline.
Instead of fighting a framework or copying utility classes, you work directly with:

* **Tokens** for colors, type, spacing, and layout — your design “knobs”
* **Cascade layers** for clarity and control
* **Blocks (BEM)** so each section owns its layout and styling

Design emerges naturally from the content. You don’t need a design tool to begin — the page grows from semantic HTML and small, deliberate CSS decisions.


## Project structure

```
modern-css-starter/
├── index.html         # semantic content structure
├── vite.config.js     # dev server setup
├── package.json
└── src/
    ├── img/           # images and assets
    └── styles/
        ├── app.css      # entry point with @layer order + imports
        ├── tokens.css   # design tokens (colors, type, spacing, layout)
        ├── base.css     # resets + accessibility baseline
        └── blocks.css   # block/component styles (BEM)
```

## Usage

Once you’ve cloned the repo or created a new project from it:

Install dependencies:

```bash
npm install
```

Run the dev server (auto reloads on save):

```bash
npm run dev
```

Build for production (outputs to `/dist`):

```bash
npm run build
```

Preview the production build locally:

```bash
npm run preview
```

## Example workflow

1. Write semantic HTML in `index.html`
2. Add or tweak tokens in `src/styles/tokens.css`
3. Style blocks in `src/styles/blocks.css` (BEM naming)
4. Adjust spacing, type, and colors via tokens
5. Fine-tune with modifiers and container queries


## Why this instead of a framework?

This starter is intentionally lightweight. It doesn’t include Bootstrap, Tailwind, or any other framework — so you can:

* **Learn CSS fundamentals** instead of memorizing utility classes
* Build a **design system from scratch** with tokens and layers
* Understand **how modern CSS really works** (cascade, fluid type, grid, container queries)
* Move faster later when you do use a framework, because you know what’s happening underneath


## License

MIT — free to use and adapt.

