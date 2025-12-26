# GoNex Innovations — Digital Marketing Agency (Landing)

Modern dark-themed landing page with neon green accents, built with Tailwind CDN, HTML, and vanilla JS.

## Getting Started

Open `index.html` in your browser (no build step required).

To connect a backend for the contact form, replace the client-side mailto handler in `assets/js/main.js` with an API POST request.

## Files

- `index.html` — main page with hero, services, contact form
- `assets/css/style.css` — minimal custom styles & utilities
- `assets/js/main.js` — interactions (nav toggle, form, smooth scroll)

## Features

- Mobile-first responsive design
- Neon green (#00FF66) accent color with dark theme
- Service cards with hover effects
- Smooth anchor link scrolling
- Contact form (client-side mailto handler)
- Accessible HTML structure

## Customization

### Colors
- Primary accent: `#00FF66` (neon green)
- Dark background: `#071013` to `#0b0b0b`

Update `index.html` Tailwind config and `assets/css/style.css` `:root` variables to change colors globally.

### Content
Edit sections in `index.html` to update company info, services, contact details.

## Production Notes

- Tailwind is loaded via CDN. For production, use Tailwind CLI or compile to purge unused styles.
- The contact form uses `mailto:` as fallback; implement a server endpoint for robust lead capture.
- Add actual social media links in footer section.
