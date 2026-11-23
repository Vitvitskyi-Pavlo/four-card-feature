# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK).

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size (`375px` mobile and `1440px` desktop)

### Screenshot

![Four card feature section preview](./images/screenshot.png)

### Links

- Solution URL: [Frontend Mentor Solution](https://www.frontendmentor.io/solutions/your-solution-link)
- Live Site URL: [Live Demo](https://your-live-site-url.netlify.app)

## My process

### Built with

- Semantic HTML5 markup (`<main>`, `<header>`, `<section>`, `<article>`)
- CSS custom properties (`:root` variables)
- CSS Grid (asymmetric 3-column desktop layout)
- Flexbox (card internal alignment and header structure)
- Mobile-first workflow using relative `rem` units
- [Google Fonts](https://fonts.google.com/) – Poppins (`200`, `400`, `600`)

### What I learned

- **Asymmetric CSS Grid placement:** Used `grid-template-columns: repeat(3, 1fr)` paired with `align-items: center` and explicit `grid-column` / `grid-row: 1 / 3` rules so the outer cards (`Supervisor` and `Calculator`) center vertically alongside the stacked middle column without extra wrapper `<div>` elements.
- **Heading hierarchy and styling:** Combined both lines of the main title inside a single `<h1>` using a `<span>` with `display: block` and `font-weight: 600` to preserve proper document outline for screen readers while matching the two-weight visual design.
- **Card styling with Flexbox:** Structured each `<article>` as a column flex container using `align-self: flex-end` on the decorative icons (`alt=""`) and `border-top` with `overflow: hidden` for clean rounded top accents.
