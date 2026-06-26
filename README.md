# Peace of Mind — Peptide Weight Loss Landing Page

Sophisticated, bilingual (English / Spanish) marketing landing page for Peace of Mind Rehab Center's medical peptide weight loss program.

## What it does
- Educates leads on physician-supervised peptide weight loss
- Shows the four-peptide formulary (Retatrutide · Tirzepatide · Tesamorelin · MOTS-c) with branded photos
- Embedded Calendly widget for free discovery call booking
- Real before/after patient transformation
- EN ⇄ ES language toggle (top-right) — defaults to visitor's browser language
- Mobile-optimized

## Stack
- Single-file `index.html` — no build step
- Vanilla HTML + CSS + JS
- Embedded Calendly widget
- Hosted on Firebase (`pom-patient-tracker.web.app/peptide-weightloss-landing.html`)

## Files
| File | Purpose |
|---|---|
| `index.html` | The landing page |
| `pom-logo.png` | Brand logo (used in nav + image overlays) |
| `pep-*.png` | Branded peptide vial photos |
| `wl-doctor-care.png` | Hero photo |
| `wl-patient-1-before.jpg` · `wl-patient-1-after.jpg` | Real patient transformation (signed release on file) |
| `wl-vials.png` · `wl-injection.png` · `wl-scale.png` | Editorial image accents |

## Local preview
Just open `index.html` in any browser — no server needed.

## Deploy
The live page is hosted on Firebase Hosting via the `pom-patient-tracker` project. To redeploy:
1. Copy `index.html` (as `peptide-weightloss-landing.html`) and all images to the Firebase workspace folder
2. `firebase deploy --only hosting`

## Editing copy
All translatable text uses `data-i18n="key"` attributes (or `data-i18n-html="key"` for text containing HTML).
The translation dictionary is in the `<script>` block at the bottom of `index.html`, in the `I18N` constant.

## Brand
- Teal `#3DBDB0` · Pink `#F4A5BE`
- Playfair Display (serif headlines) + Inter (body)
- Calendly: `https://calendly.com/pomconnect2140/weight-loss-discovery-call`

---

© Peace of Mind Rehab Inc · 2140 W Flagler St, Suite 211 · Miami, FL 33135
