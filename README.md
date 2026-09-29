# Scott Decorative Concrete, LLC — Homepage

A premium, redesigned homepage for **Scott Decorative Concrete, LLC**, a stamped &
decorative concrete specialist serving Washington, DC and Maryland since 1983. Rebuilt
from the existing site at
[washingtonstampedconcrete.com](https://www.washingtonstampedconcrete.com/).

Built as a fast, dependency-free static site, using the company's **real logo, brand
colors, and project photos**.

**Live site:** _(GitHub Pages — see repo Settings → Pages)_

---

## Business details
- **Company:** Scott Decorative Concrete, LLC
- **Phone:** (202) 301-4680
- **Address:** 138 Adams St NW, Washington, DC 20001
- **Established:** 1983 (40+ years)
- **Credentials:** Licensed, Bonded & Insured *(per the company's own project signage)*
- **Hours:** Monday–Sunday, 6 AM – 10 PM
- **Tagline:** "Concrete Beauty, Built to Last."
- **Service area:** Washington, DC · Bethesda · Silver Spring · Annapolis · Waldorf, MD & surrounding
- **Social:** [Pinterest](https://www.pinterest.com/ScottDecorativeConcreteLLC/pins) · [Yelp](https://yelp.com/biz/scott-decorative-concrete-washington)

## Services
Stamped concrete · Concrete staining · Driveways · Patios & pool decks · Retaining walls ·
Concrete repair · Retaining wall repair · Decks · Fencing · Stone work.

## Tech
- Static **HTML + CSS + vanilla JS** — no build step, no framework, no dependencies.
- Google Fonts (Archivo + Inter). Everything else is local.
- Accessible: semantic landmarks, single `<h1>`, keyboard nav, visible focus,
  `prefers-reduced-motion`, descriptive alt text.
- SEO: descriptive title/meta, Open Graph, and `GeneralContractor` JSON-LD with full NAP,
  founding date, opening hours, and social profiles.

## Structure
```
index.html            # full homepage
css/styles.css        # design system + all sections + responsive
js/main.js            # sticky header, mobile menu, scroll reveals, form shell
assets/img/           # real logo + project photos + favicon
```

## Design
**Scott brand palette** pulled from the logo and site: **teal-blue `#1B9DC5`** (deep
`#12718F`) accent, **slate `#556D74`**, and **cream `#F3ECDB`**, on a rugged charcoal
dark header so the silver "SCOTT" logo pops. Archivo + Inter typography.

---

## Notes for the client
- **Logo & photos are real** — the header/footer use the actual Scott logo, and every
  project image is a real Scott job pulled from the current site. Swap or add photos by
  dropping files into `assets/img/`.
- **Estimate form** — front-end only; it does not submit anywhere yet. Wire it to email or
  a CRM (Formspree, Netlify Forms, GHL, etc.) to start capturing leads.
- **"Licensed, Bonded & Insured"** is taken from the company's own yard sign shown in a
  project photo. Confirm the current license details before adding a license number.
- Only substantiated facts are used — no invented reviews, project counts, awards, or
  guarantees.

## Deploy (GitHub Pages)
Settings → Pages → Source: `main` / root. The site publishes at the Pages URL.
Local preview: open `index.html`, or run `python3 -m http.server` in the repo root.
