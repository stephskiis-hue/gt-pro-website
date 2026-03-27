# GT PRO — Project Memory

## Business Info
- **Company:** GT PRO Enterprises
- **Owner contact:** tavaracci@gmail.com | (204) 990-4426
- **Location:** Winnipeg, Manitoba, Canada
- **Founded:** 2011
- **Service area:** Winnipeg & all of Manitoba
- **Website domain (planned):** gtproenterprises.ca

## Design System
- **Primary navy:** #03192e
- **Secondary gold:** #735a3a
- **Surface:** #f9f9f9
- **Font headlines:** Noto Serif (italic for emphasis)
- **Font body/labels:** Manrope
- **Icons:** Material Symbols Outlined (SVG fallbacks in nav logo)
- **No 1px borders rule** — use ambient shadows instead
- **Glassmorphism nav:** `backdrop-blur`, semi-transparent bg

## Site Structure (Static HTML — no build step)
- `index.html` — Homepage
- `services.html` — 4 service sections (Kitchens, Bathrooms, Basements, Full Remodels)
- `gallery.html` — Filterable bento grid (All / Kitchens / Bathrooms / Basements)
- `quote.html` — 4-step quote form (Formspree backend)
- `about.html` — Company story, philosophy, credentials
- `images/` — 25 enhanced real project photos from GT PRO album
- All files in: `/sessions/exciting-zen-hopper/mnt/outputs/`

## Form Backend
- Provider: **Formspree** (free tier, 50 submissions/month)
- Setup: Replace `YOUR_FORM_ID` in quote.html with ID from formspree.io
- Instructions comment at top of quote.html

## Key Decisions Made
- Removed price ranges from services page (client preference)
- Removed Full Remodel filter tab from gallery
- Removed before/after slider from homepage
- Budget slider: min $0, max $200k, default $25k
- Year shown: 2011 (founding year)
- Brand: "GT PRO" / "GT PRO Enterprises" (was "Stitch Renovations")
- Logo: SVG house icon (replaced Material Symbol "architecture" which showed as text before font load)
- Mobile nav: closes on outside click
- Real contact: (204) 990-4426 / tavaracci@gmail.com

## Hosting Notes
- Pure static site — works on Netlify, GitHub Pages, any static host
- Netlify has built-in form handling as alternative to Formspree
- Images are local (images/ folder), no CDN needed

## Photos
- Source: GT PRO ENTERPRISES Google Photos album (downloaded by client)
- 25 processed images at max 1800px, JPEG quality 88
- Enhanced with auto-contrast, brightness +8%, saturation +15%, unsharp mask

## Agent Strategy (for future sessions)
- Use **haiku** for: find/replace edits, year changes, simple text swaps, CSS additions
- Use **sonnet** for: multi-file coordinated edits, layout changes, new sections
- Use **opus** for: architecture decisions, new page planning, SEO strategy
