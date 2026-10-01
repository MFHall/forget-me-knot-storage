# Forget Me Knot Boat & RV Storage — Website

Static website for **Forget Me Knot Boat & RV Storage**, Kingston, WA.
Domain: `forgetmeknotboatandrvstorage.com`

## Contents
- `index.html` — Home page
- `rates.html` — Rates & space sizes
- `rules.html` — Facility info & hours
- `contact.html` — Contact form, map, and details
- `css/style.css` — Shared styling (navy/gold theme, mobile-responsive)
- `robots.txt`, `sitemap.xml` — SEO basics

## Business details used
- Address: 7810 NE Ecology Rd, Kingston, WA 98346
- Phone: (360) 865-2751
- Email: ForgetMeKnotBoatRV@gmail.com
- Hours: Mon–Fri 8am–4pm (after-hours access/appointments by call)
- Rates: $120/mo up to 20 ft, $240/mo for 46–50 ft, "call for rates" 21–45 ft
- Storage: boats, RVs, passenger vehicles, semi trucks, trailers — uncovered, locked gate, security cameras

## No artwork yet
The coworker's artwork wasn't available, so the logo is a styled text wordmark.
Swap in real artwork later by adding an image to `css/style.css`'s `.brand`
or an `<img>` in the header — no rebuild needed.

## To publish ASAP
1. **Hosting**: Any static host works (Netlify, GitHub Pages, Vercel, or
   traditional hosting via your domain registrar/host). Netlify or Vercel:
   drag-and-drop this folder or connect a repo — live in minutes.
2. **Domain**: Point `forgetmeknotboatandrvstorage.com` DNS at the host
   (the host's dashboard gives exact A/CNAME records).
3. **Google Business Profile**: Create/claim a listing with this address
   and phone number — this is the biggest early driver of local search traffic.
4. **Contact form**: The form currently submits via `mailto:`. For automatic
   lead capture, connect a service like Formspree or Netlify Forms and update
   the `<form>` tag in `contact.html`.

## Local preview
Open `index.html` directly in a browser, or serve the folder with any static
file server, e.g.:

```
npx serve forget-me-knot-storage
```
