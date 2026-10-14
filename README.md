# Dianne Moodley Attorneys Inc. — Independent website concept

A fully functional nine-page static HTML + CSS + vanilla JS website based on the established Wakili wa Tech South African law-firm style. **No React, npm, Vite or build step**.

## Deliverables
- Home, About, Practice Areas, Our Attorney, Insights, Contact, Privacy, Terms and 404.
- Black-and-gold client logo with a transparent footer/header version; authentic supplied attorney portrait intentionally appears in three page locations (Home, About and Our Attorney), as explicitly requested by the user; separate branded 1200×630 Open Graph/WhatsApp card.
- Emails: primary diannemoodley.associates@gmail.com (user-supplied banner), additional professional dianne@diannemoodleyinc.co.za (firm website).
- Telephone 071 331 1044 / 082 576 0094; office 598 Westcliff Drive, Westcliff, Chatsworth, 4092, Durban.
- Working `mailto:` email-draft form (visitor must press Send — **no server submission**).
- One WhatsApp contact button pointing to first phone number; **WhatsApp registration not verified**.
- Correct page-level Open Graph/Twitter metadata and factual LegalService structured data. Canonicals currently assume https://dianne-moodley-attorneys.vercel.app.
- **noindex** until client approval, while robots.txt allows social preview bots to retrieve metadata.
- Verified facts and release notes: `RESEARCH-NOTES.md`; image provenance: `PHOTO-SOURCES.md`.

## Preview and deployment
`python3 -m http.server 8000` in site root; browse http://localhost:8000/. Vercel framework Other, project root `.`, output `.`. Use `npx vercel --yes` for preview. Before publishing to official domain, confirm authorisation and actual host, then update metadata throughout project. Do not create a duplicate GitHub repo or Vercel project for future updates.

## V2 client-requested adjustments
- Brand colours are **black and gold**; former navy backgrounds, gradients and text accents are converted to black and neutral shades, and the WhatsApp sharing preview matches.
- The *same* supplied portrait intentionally appears in the Home introduction, the About introduction and the Our Attorney profile. This explicitly overrides the usual no-repeat content-photo rule for this one portrait.
- All external stock photos retain their site-wide unique-source rule; no new repeated stock photos introduced.
- Fixed inaccurate legacy practice descriptions in the footer copied from an unrelated law firm.
