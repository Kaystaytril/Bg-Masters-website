# BG Masters Accounting and Tax Services — Website

A four-page static website (Home, About, Services, Contact) for BG Masters
Accounting and Tax Services, East London. Built with plain HTML, CSS and a
small amount of JavaScript — no build step, no dependencies. Just upload the
folder to any web host.

## Files
- `index.html` — Home
- `about.html` — About
- `services.html` — Services
- `contact.html` — Contact
- `assets/style.css` — all styling and the design system
- `assets/script.js` — mobile menu, scroll animations, contact form handling
- `assets/logo.svg` / `assets/favicon.svg` — brand mark (recreated from your logo)

## Before going live — replace these placeholders
The real details I didn't have are clearly marked on-page (look for the small
italic notes). Search-and-replace these across all files:

| Placeholder | Where | Replace with |
|---|---|---|
| `043 000 0000` / `+27430000000` | header, footer, contact | Real phone number |
| `info@bgmasters.co.za` | footer, contact | Real email address |
| `1 Oxford Street, Vincent, East London, 5247` | footer, contact | Real street address |
| `27000000000` (wa.me link) | WhatsApp button, contact | Real WhatsApp number, intl format |
| `[Founder Name]` + bio | about.html | Founder's name, photo and biography |
| `PR–000000` / "SAIT" | about.html | Real registration body & practice number |
| Map embed | contact.html | Google Maps embed for the exact office |
| Social links (`href="#"`) | all footers | Facebook / Instagram / LinkedIn URLs |

## Contact form
The form currently shows a confirmation message but does not send email yet.
To make it live, connect it to a form service (e.g. Formspree, Web3Forms) or your
host's mail handler — see the comment in `assets/script.js`.

## Brand colours (from your logo)
- Navy `#1A2E4A` · Blue `#15689B` · Green `#2FA877` · Gold `#E9A23B` · Orange `#DD8133`

## Notes
- Fully responsive (desktop, tablet, mobile) with a mobile menu.
- Keyboard-accessible, respects reduced-motion, and content stays visible even
  if JavaScript is disabled.
- The logo is an SVG recreation of your supplied logo so it stays crisp at any
  size. If you have the original vector (AI/SVG/EPS) file, swap it in for an
  exact match.
