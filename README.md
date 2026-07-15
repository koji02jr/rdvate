# RDVate

Marketing website for **RDVate** — a digital marketing studio that helps brands rise above the noise.

A single, self-contained static page (`index.html`) — fonts, styles, and scripts are all inlined, so there's no build step and no external dependencies.

## Features

- Responsive, light/dark themed, accessible (keyboard focus, reduced-motion support)
- Embedded typography (Bricolage Grotesque + Hanken Grotesk)
- Interactive touches: cursor-tracking hero glow, liquid-glass CTA, peeling "Noise" sticker, bento capability grid, "Selected Work" hover previews, custom glass cursor, and a frosted-glass dropdown menu

## Develop

Just open `index.html` in a browser, or serve it locally:

```bash
python3 -m http.server 4599
# then visit http://localhost:4599
```

## Deploy

It's a static site — deploy anywhere (Vercel, Netlify, GitHub Pages, Cloudflare Pages) with no configuration. The whole site is one file.

## To do

- Replace placeholder contact email (`hello@rdvate.com`) with the real address
- Add real social links and project images
- Swap in the official logo asset
