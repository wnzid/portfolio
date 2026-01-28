# Portfolio (Next.js)

A concise, responsive portfolio built with Next.js and TypeScript. Includes a minimal layout, theme toggle (light/dark), and a typography-first design using Inter for body text and Geist Mono for micro labels.

## Quick Start

Install dependencies and run locally:

```bash
npm install
npm run dev
```

Open http://localhost:3000 in your browser.

## What’s Included

* Next.js (App Router)
* TypeScript-ready pages in `app/`
* Global styles and typography in `app/globals.css`
* Icons from MUI (`@mui/icons-material`)
* Profile/avatar image served from `public/`

## Typography & Theme

This project follows a simple font system:

* Body / headings: Inter (16px base)
* Micro labels & metadata: Geist Mono (12px)

Colors are theme-aware:

* Light theme text color: `#5A6B94`
* Dark theme text color: `#8A99C2`

Edit the font and color rules in `app/globals.css` to tune the look.

## Key Files

* `app/page.tsx` — main layout and content
* `app/globals.css` — global typography, spacing and theme vars
* `public/` — static assets (put your profile image here as `public/avatar.jpg` or update the Image `src` in `page.tsx`)

## Customization

* Avatar: replace `public/avatar.jpg` (or the referenced path `/img/heee.jpg`) with your image.
* Theme: the theme toggle sets `.dark` on the root element. Change colors in `:root` / `html.dark` in `app/globals.css`.
* Typography: modify `profile-title`, `.desc`, `.micro-label`, `.date-range`, `.footer-micro`, and related rules in `app/globals.css`.

## Scripts

* `npm run dev` — start dev server
* `npm run build` — build for production
* `npm run start` — start production server

## License

Feel free to reuse or adapt this template for your portfolio.

---
If you want, I can add a CONTRIBUTING section, CI config, or a production-ready `package.json` snippet — tell me which you'd prefer next.
