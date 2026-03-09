# FurniCo — Furniture Store Landing Page

A clean, minimal furniture store landing page built with HTML, CSS, and Tailwind CSS.

---

## Why Tailwind CSS

Tailwind was chosen for its utility-first approach, making it easy to style
directly in the HTML without switching between files. It keeps the design
consistent through a built-in spacing and color scale, and handles responsive
design with simple prefixes like `md:` and `sm:` — making it a great fit for
a project like this.

---

## Why Media Queries

Tailwind alone doesn't cover every responsive case, so custom media queries
were added in an external stylesheet to handle layout shifts at two breakpoints:

- **1024px (Tablet)** — grids collapse from 4 columns to 2
- **768px (Mobile)** — everything stacks to 1 column, the navbar becomes a hamburger menu

---

## Why a Furniture Store

Furniture as a theme naturally calls for a clean, minimal aesthetic — lots of
whitespace, neutral colors, and subtle interactions. This made it a great
use case for practicing layout, grid systems, hover effects, and responsive
design without needing loud colors or complex UI patterns.

---

## Sections

- Header with responsive hamburger menu
- Hero banner with product image
- Featured products grid
- Customer testimonials
- Contact form
- Footer

---

## Tools Used

- HTML5
- CSS3 + Media Queries
- Tailwind CSS (via CDN)
- Google Fonts — Montserrat
