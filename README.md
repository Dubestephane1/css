# OdinCSS

A lightweight, dependency-free CSS utility framework with **2,700+ classes** to build modern, responsive websites faster — no installation, no build step, no JavaScript.

Live demo: <https://odin.fr.to>

## Quick Start

Add one line to the `<head>` of your HTML file:

```html
<link rel="stylesheet" href="https://odin.fr.to/odin.min.css">
```

That's it. Start using the classes right away.

## Why OdinCSS?

- **Over 2,700 utility classes** — colors, spacing, typography, grids, borders, gradients, transitions and more.
- **No installation required** — a single CDN link, nothing else to configure.
- **Intuitive, readable class names** inspired by Bootstrap and Tailwind, but lighter and simpler.
- **1rem = 10px** base sizing, so `font-size-20` = 20px, `pad-10` = 10px, etc.
- **Completely free** — released by a solo developer, with new colors, fonts and classes added regularly.

## How the classes work

The naming convention is simple and predictable:

1. **Color first** — `azure-txt`, `blue-bg`, `red-border`, `green-txt-hover`, `yellow-bg-hover`, ...
2. **Numbers last** — `font-size-20`, `pad-10`, `margin-r-10`, `gap-10`, `w-100-pc`, `h-50`, `grid-col-3`, ...
3. **Shorteners everywhere** — `bg` = background, `pad` = padding, `w` = width, `l/r/t/b` = left/right/top/bottom, `pc` = %.

### Examples

```html
<p class="azure-txt font-size-20">Hello, world!</p>

<div class="black-gray-bg pad-20 border-rad-12">A rounded card</div>

<div class="grad-peachy pad-20 border-rad-12">Gradient box</div>

<button class="azure-bg yellow-bg-hover">Hover me</button>

<div class="display-grid grid-col-3 gap-10">
  <div>Column 1</div>
  <div>Column 2</div>
  <div>Column 3</div>
</div>
```

## Resources

- **Site & live demo:** <https://odin.fr.to>
- **Shades, fonts & gradients gallery:** included on the site's *Resources* section
- **Fonts:** 25+ Google Fonts available as `font-*` classes (e.g. `font-lobster`, `font-oxanium`, `font-poppins`)
- **Email:** <contact@stephanedube.dev>

## Repository layout

| File | Purpose |
|------|---------|
| `odin.min.css` | Main OdinCSS framework (minified, ~2,700 classes) |
| `odinstyle.min.css` | Extended framework variant with additional styles |
| `odinstyle1.css` | Source-breakdown version of the framework |
| `index7.css` | Page-level styles for the OdinCSS landing page |
| `index.html` | The OdinCSS landing page / documentation site |
| `odinicon.ico` / `odinicon.png` | OdinCSS logo |

## Status

OdinCSS is an ongoing, honest solo project. It is small and early-stage but fully usable for experiments, prototypes and production utility styling. New colors, fonts and classes are added over time.