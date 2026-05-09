# Replit Agent Task: RoyalKims

## Goal
Build a polished combined website for Royal Kims covering both jewelry sales and professional cleaning services, with compelling copy, client testimonials, and clear service/product sections.

## Tasks
1. Build a hero section: elegant dark/gold aesthetic, tagline combining "Fine Jewelry" and "Premium Cleaning Services", and two CTA buttons: "Shop Jewelry" and "Book Cleaning"
2. Create a Jewelry section: product grid with 6+ placeholder items (rings, necklaces, bracelets, earrings) with names, materials, and prices — link each to a simple product detail modal
3. Build a Cleaning Services section: cards for each service type (residential cleaning, deep cleaning, move-in/move-out, office cleaning) with pricing tiers and a "Get a Quote" CTA
4. Add a Testimonials section: 5 realistic client testimonials alternating between jewelry buyers and cleaning service clients — include star ratings and client first names
5. Build a Contact/Booking section: contact form (name, email, phone, service type, message) that submits to Supabase `inquiries` table; include business phone and email
6. Add an About section: family-owned business story, years of experience, commitment to quality — warm, personal tone
7. Implement a simple cart system for jewelry (localStorage) with checkout form
8. Add Open Graph meta tags (og:title, og:description, og:image) and JSON-LD for LocalBusiness schema
9. Ensure mobile-first responsive design throughout
10. Deploy to Cloudflare Pages (static build)

## Tech Stack
- React 18 + TypeScript
- Vite
- Tailwind CSS
- Supabase (contact form / inquiry storage)
- Cloudflare Pages (static deploy)

## Deploy Target
Cloudflare Pages — connect `Kaoz625/RoyalKims`. Build command: `npm run build`, output: `dist/`. Never Vercel.

## Done When
- [ ] Jewelry grid and cleaning services cards both render with placeholder content
- [ ] 5 testimonials are displayed with star ratings
- [ ] Contact form submits to Supabase
- [ ] Site has gold/dark elegant aesthetic throughout
- [ ] Fully mobile-responsive at 375px
- [ ] Open Graph and JSON-LD tags present
- [ ] All changes pushed to `Kaoz625/RoyalKims` main branch
