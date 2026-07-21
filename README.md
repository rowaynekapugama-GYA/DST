# Dental Specialists Turramurra — Homepage Redesign

Design concept for the dentalspecialists.com.au rebuild, by Generate Your Audience.

**Direction:** modern, elegant, family-oriented. Palette drawn from the DST logo teal, with Fraunces italic display type echoing the cursive logo script. Specialist positioning only (orthodontics + prosthodontics) — general dentistry removed per client.

## Structure

- `index.html` — self-contained homepage mockup (all CSS/JS inline)
- `assets/` — logo variants and imagery
  - `logo.png` / `logo-white.png` — original + white-wordmark variant (transparent header & footer)
  - `kids-braces.jpg`, `adult-clear-aligner.jpg`, `aligner-smile-bg.jpg` — compressed Shutterstock comps; replace with licensed originals at build

Practice photos and the hero banner are hotlinked from the current live site / S3 and should be re-uploaded to the new media library at build time.

## Preview

Open `index.html` directly, or enable GitHub Pages (Settings → Pages → deploy from branch) to share a live link.

## Before go-live

- Confirm hero stats (25+ years / 10,000+ procedures are placeholders)
- Confirm Dr Jinjing Mao removal (assumed general dentist)
- Confirm hours: header says Mon–Fri 8–5, appointments copy says Mon–Sat 9–5
- Swap in official Invisalign Platinum Provider badge from the Invisalign Doctor Site + verify current tier
- Mobile menu needs an accordion version of the mega-menu structure
