# Key West Family Dentistry — Redesign

A static multi-page redesign of [caribbeandentist.com](https://www.caribbeandentist.com/) with a warm, healing boutique aesthetic. Built without frameworks — pure HTML, CSS, and a small `script.js`.

## Run locally

```bash
python3 -m http.server 5174
# open http://localhost:5174/index.html
```

## Pages

- `index.html` — Home
- `services.html` — Services
- `doctor.html` — Dr. Andrew Arnouk
- `reviews.html` — Reviews (with source filter tabs)
- `contact.html` — Contact + map card
- `login.html` / `register.html` — Patient portal auth
- `dashboard.html` — Patient portal landing

## Design

- Style direction: warm cream / terracotta / seafoam serif-led boutique
- Generated via the `design-first-product` skill (see `design/` for phase 1–3 references and the product spec)
- Type: Fraunces (display) + Inter (UI), served via Google Fonts with preconnect

## QA

Verified at 375 / 768 / 1440 viewports with Playwright:
- 0 contrast issues (WCAG AA)
- All forms validate empty submit and show feedback
- Mobile menu closes on outside click, Esc, and second toggle
- Brand-colored `:focus-visible` ring on all interactive elements
- All local links resolve
