# Crypto & Developing

A responsive, multi-page blog about crypto trading and my path into fintech development. Built with HTML and CSS only, as a solo project in the Scrimba Frontend Developer Path.

**Live demo:** https://crypto-exp.netlify.app/

## Pages

- **Home**: hero with the featured post and a grid of six articles
- **Featured post**: the full story behind the blog
- **About**: who I am and why I'm moving from trading into development

## Features

- Mobile-first responsive layout (one column on phones, three on wider screens)
- CSS Grid with `grid-template-areas`
- Flexbox for the navbar and card layouts
- CSS custom properties for a dark, trading-terminal style theme
- Hero image overlay with a `::before` pseudo-element for readable text
- Semantic HTML: `header`, `nav`, `main`, `article`, `section`, `footer`

## Tech

- HTML5
- CSS3
- No frameworks, no JavaScript

## What I learned

- Mobile-first design with `min-width` media queries
- Relative units (`rem`, `%`, `fr`) instead of fixed pixels
- Why `minmax(0, 1fr)` prevents horizontal overflow on small screens
- How `box-sizing` affects width once padding is added
- CSS Grid only lays out direct children of the grid container
- Positioning text over images with `position: relative` and `absolute`

## Run locally

Clone the repo and open `index.html` in your browser, or use the Live Server extension in VS Code.

## Author

Alex Emeretlis: trader turned aspiring fintech developer.
