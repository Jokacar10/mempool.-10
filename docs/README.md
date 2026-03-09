# Documentation

This directory contains the VitePress documentation for the Mempool project.

## Getting Started

### Development

To start the development server:

```bash
npm run docs:dev
```

This will start a local server at `http://localhost:5173` with hot module replacement.

### Building

To build the documentation:

```bash
npm run docs:build
```

The built files will be in `docs/.vitepress/dist`.

### Preview

To preview the built documentation:

```bash
npm run docs:preview
```

## Structure

- `docs/` - Documentation content
  - `.vitepress/` - VitePress configuration
    - `config.js` - Site configuration
  - `guides/` - User guides
    - `vercel-web-analytics.md` - Guide for Vercel Web Analytics
  - `index.md` - Documentation homepage

## Adding New Documentation

To add new documentation pages:

1. Create a new `.md` file in the appropriate directory under `docs/`
2. Add the page to the sidebar in `docs/.vitepress/config.js`
3. Write your content using Markdown and VitePress features

## VitePress Features

This documentation uses VitePress, which supports:

- Markdown extensions
- Code groups for multiple examples
- Custom containers (tips, warnings, etc.)
- Syntax highlighting
- And much more

See the [VitePress documentation](https://vitepress.dev/) for more information.
