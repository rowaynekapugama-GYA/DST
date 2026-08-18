# Dental Specialists Turramurra — Website (Batch 1)

Static site, ready for Vercel drag-and-drop. No build step.

## Pages
- `index.html` — approved homepage
- `about-us.html` — About Us + Our Team (full specialist bios + support team)
- `prosthodontics.html` — Prosthodontist
- `orthodontics.html` — Orthodontist
- `general-services.html` — General Dental Services
- `patient-info.html` — Patient Info + resources
- `vercel.json` — cleanUrls, no trailing slash

## Built so far

**Batch 1 — main pages:** index, about-us, prosthodontics, orthodontics,
general-services, patient-info

**Batch 2 — Prosthodontics children (5):**
- comprehensive-assessment.html
- cosmetic-dental-care.html
- anti-ageing-restorative.html  (incl. crowns & bridges, full mouth rejuvenation,
  dental implants, removable + complete dentures, 3 case studies)
- tmd-treatment.html
- sleep-apnoea.html

These are wired into the mega menu, the Prosthodontics service cards and the footer.

## Batch 6 (built)
- `contact.html` — practice details, hours, directions, referral/enquiry cards.
  All nav + footer "Contact" links now point here (the enquiry form remains on index.html#contact).
- `emergency-dental.html` — first of the General Services children.

## Still to build

- **Orthodontics children (8):** Orthodontics for Children / Adults, Two-Phase
  Treatment, Orthodontic Options, Invisalign, Clarity Ceramic Braces,
  EMS Airflow Guided Biofilm Therapy, Orthodontic FAQ's
- **General Services children (5):** Preventative Care, Cosmetics Dentistry,
  Emergency Dental, Restorative Treatments, Oral Health Maintenance
- **Patient Info children (9):** Appointments, Fees & Payment, Afterpay,
  Lifestyle Damage, Diagnostic Information, Jaw Pain Information, Follow Up Care,
  Your Welcome Pack & Registration, Links
- **Other:** Contact Us, Blog, DST Academy, Doctor Referrals, Recruitment

Links to any not-yet-built page still point at the relevant parent section, so
nothing dead-ends.

## Notes
- Child/service pages are not built yet. Mega-menu and card links for them currently
  point at the relevant parent page section (`#services` / `#resources`).
- Practice photography, team photos and hero images are hotlinked from
  `dentalspecialists.com.au/wp-content/uploads/...` — migrate into the new media
  library at final build.
- Placeholder/theme dummy copy from the old WordPress site (Vokalia/Consonantia,
  "A small river named Duden", info@example.com, US phone numbers, "Mark Mcguire",
  "25 Years of Experience in Interior Design") was deliberately excluded.

## Outstanding client questions
- Homepage hero stats (25+ years / 10,000+ procedures) are still placeholders.
- Opening hours conflict: header says Mon–Fri 08:00–17:00; the General Services page
  says Mon/Wed/Fri 8:00am–6:00pm. Needs confirming.
- General Services + Dr Jinjing Mao are included here per this brief, which reverses
  the earlier instruction to remove general dentistry. Confirm which is current.
