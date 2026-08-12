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

## Round (12 Aug)

- Afterpay added to the payment options row (official landscape logo)
- Header logo enlarged ~3x and set to overhang below the header onto the hero image
- New "We accept all Australian health funds" section added between the payment steps and Visiting Us, with the main funds (Bupa, HCF, Medibank, nib, HBF, Australian Unity, CBHS, Teachers Health)
  - NOTE: fund logos are styled text wordmarks as placeholders — health fund logos are trademarked; swap official artwork at build (client said "just main health funds logos only")

## Colour theme toggle (11 Aug)

- The feature sections (Orthodontics band + Contact) now read from a `--feature-bg` CSS variable
- Default is the light blue (#E2F0F3); a footer toggle beside the copyright switches them to a warm sand (#EBDDC9)
- Toggle adds/removes `body.theme-sand`, remembers the choice via localStorage (works when hosted / opened directly; harmless no-op elsewhere)
- For the build: pick one palette and hard-code it, or keep the toggle as an internal preview and remove before launch

## Latest round (23 Jul — pre-meeting)

- Real practice photography added: new "Inside the Practice" gallery + real reception/exterior in Welcome and Visit
- Real dentist portraits swapped in for Dr Kamini Titus and Clin. A/Prof Anthony Au (team, arch image, mega menus) — portraits are low-res (319px source); request hi-res versions for production
- All "Orthodontist" titles now read "Specialist Orthodontist"
- Two services added: Teeth Whitening, Custom Mouthguards
- Zip Pay + Medipay added to the payment logo row and text references (styled text badges — swap official brand artwork at build)
- More playful graphics: floating tooth outlines + twinkling sparkles in hero and orthodontics band

## Earlier round (23 Jul)

- New family hero banner; header, buttons and footer switched to logo blue (orange accent removed)
- "Orthodontics for Every Age" moved directly after "Why families choose us"
- Age cards rebuilt as Kids / Teens / Adults with photography; Dr Kamini now in the arch image
- Invisalign Platinum Provider callout added inside the orthodontics section
- Full-width Google Map added above the footer
- New page needed: /turramurra/teens-orthodontist/ (linked from cards, mega menu and footer)

## Before go-live

- Confirm hero stats (25+ years / 10,000+ procedures are placeholders)
- Confirm Dr Jinjing Mao removal (assumed general dentist)
- Confirm hours: header says Mon–Fri 8–5, appointments copy says Mon–Sat 9–5
- Swap in official Invisalign Platinum Provider badge from the Invisalign Doctor Site + verify current tier
- Mobile menu needs an accordion version of the mega-menu structure
