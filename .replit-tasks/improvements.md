# Replit Agent Task: RoyalKims

## Goal
Redesign the RoyalKims site from its current basic split-screen prototype into a polished dual-service storefront for "Royalty Creations & Cleaning" — a luxury jewelry showcase and professional cleaning services hub — with real product/service listings, testimonials, and a working contact form.

## Tasks
1. Keep the split-gateway concept (Jewelry side / Cleaning side) but redesign it: use a full-screen hero with animated background, gold gradient for jewelry and deep navy/silver for cleaning, modern card-flip or slide transition when selecting a side
2. **Jewelry section**: product gallery grid (8–12 items: rings, necklaces, bracelets, earrings) with placeholder images, product name, price, and a "Inquire" button that opens a mailto or modal contact form; include a "Custom Orders" CTA section; gold (#C9A84C) and blush accent palette
3. **Cleaning services section**: service list cards (Residential Deep Clean, Move-In/Move-Out, Office/Commercial, Carpet & Upholstery, Window Cleaning) with icon, description, and "Get a Quote" CTA; navy (#0A1628) and silver accent palette
4. **Testimonials section** (shared footer): 4 customer quotes with star rating, customer first name + neighborhood (e.g., "Maria T. — Crown Heights"), carousel or card layout
5. **Contact / Quote form**: single unified form with a dropdown to select Jewelry Inquiry or Cleaning Quote, fields for name/email/phone/message, and a submit button — use Formspree or Netlify Forms (since this is static HTML); add honeypot field for spam prevention
6. Add a sticky nav bar on both sub-pages with the Royal Kims logo, links to Jewelry / Cleaning / Testimonials / Contact, and a phone number click-to-call
7. Typography: use Google Fonts — Playfair Display for headings, Lato for body — to convey luxury
8. Ensure full mobile responsiveness (375px min), large touch targets for CTAs
9. Keep it as a single HTML file with embedded CSS and JS, or split into index.html + style.css + script.js — no build tool required
10. Add basic SEO meta tags: title, description, OG tags for both service categories

## Tech Stack
- Vanilla HTML5 / CSS3 / JavaScript
- Google Fonts (Playfair Display + Lato)
- Formspree for contact form (free tier, no backend needed)
- CSS Grid and Flexbox for layout

## Deploy Target
Cloudflare Pages (static site). Never Vercel.

## Done When
- [ ] Split gateway renders with polished animations on click
- [ ] Jewelry gallery shows at least 8 product cards with images, name, price, and Inquire button
- [ ] Cleaning section shows at least 5 service cards with icon, description, and CTA
- [ ] Testimonials carousel/grid shows at least 4 reviews with star ratings
- [ ] Contact form submits via Formspree without page reload (AJAX or fetch)
- [ ] Site is fully responsive on mobile (375px)
- [ ] SEO meta tags present in <head>
- [ ] No broken links or console errors
