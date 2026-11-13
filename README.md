# Pillars Realm Real Estate LLC — Landing Page

Official landing page for **Pillars Realm Real Estate LLC**, a RERA-licensed real estate agency based in Dubai, UAE.

---

## 🏢 Company Info

| Field       | Details                                                    |
|-------------|------------------------------------------------------------|
| Company     | Pillars Realm Real Estate LLC                              |
| Office      | No. 1410, Grosvenor Business Tower, Barsha Heights, Dubai  |
| Phone       | +971 04 584 1700                                           |
| Email       | admin@pillarsre.ae                                         |
| Website     | [pillarsre.ae](https://pillarsre.ae)                       |
| Instagram   | [@pillarsrealm](https://www.instagram.com/pillarsrealm)    |

---

## 🗂 Project Structure

```
pillarsre/
├── index.html          # Main landing page
├── robots.txt          # Search engine crawler rules
├── sitemap.xml         # XML sitemap for SEO
├── README.md           # This file
└── assets/
    ├── logo_golden.png                              # Gold transparent logo (header, footer, about)
    ├── futuristic-landscape-dubai.jpg               # Hero background image
    └── WhatsApp Image 2026-10-19 at 6.04.37 PM (1).jpeg  # OG / social share image
```

---

## 🧱 Tech Stack

- **HTML5** — semantic markup
- **Tailwind CSS** (CDN) — utility-first styling
- **Font Awesome 6.5** (CDN) — icons
- **Google Fonts** — Cormorant Garamond (serif) + Montserrat (sans)
- **Vanilla JS** — scroll effects, mobile menu, animations, marquee control

No build tools or frameworks required. Open `index.html` directly in a browser.

---

## 📄 Sections

| Section           | Description                                              |
|-------------------|----------------------------------------------------------|
| Header            | Sticky navbar with logo, nav links, mobile menu          |
| Hero              | Full-screen Dubai skyline with headline and CTA          |
| Channel Partners  | Auto-scrolling marquee — DAMAC, Emaar, Nakheel, Azizi, Binghatti, Danube, Sobha |
| Services          | 6 service cards with hover effects                       |
| About / Stats     | Animated counters + why choose us                        |
| Contact           | Office info, phone, email, Instagram, Google Maps embed  |
| Footer            | Logo, quick links, services, contact details, social     |

---

## 🔍 SEO

- Full meta tags (title, description, keywords, canonical)
- Open Graph tags (og:title, og:description, og:image, og:url, og:type, og:locale)
- Twitter Card (summary_large_image)
- JSON-LD structured data (`RealEstateAgent` schema)
- Geo meta tags for local SEO (Dubai, AE-DU)
- `robots.txt` — allows all crawlers
- `sitemap.xml` — single URL pointing to `https://pillarsre.ae/`

---

## 🚀 Deployment

1. Upload all files to the root of `pillarsre.ae`
2. Ensure `assets/` folder is uploaded with all 3 files
3. Verify `https://pillarsre.ae/robots.txt` and `https://pillarsre.ae/sitemap.xml` are accessible
4. Submit sitemap to [Google Search Console](https://search.google.com/search-console)

> **Note:** The hero background image (`futuristic-landscape-dubai.jpg`) is 18MB. Compress it to under 500KB before going live using [Squoosh](https://squoosh.app) for faster load times.

---

## 🔮 Pending / Future

- [ ] Contact / enquiry form backend integration (form is commented out in HTML, ready to wire up)
- [ ] Property listings page (dynamic, requires backend)
- [ ] Compress hero image for production
- [ ] Create a branded 1200×630px OG cover image
- [ ] Add Google Analytics / Meta Pixel

---

## 🎨 Brand Colors

| Name       | Hex       | Usage                        |
|------------|-----------|------------------------------|
| Navy       | `#0a1628` | Primary dark background      |
| Deep Black | `#03070e` | Hero, footer background      |
| Gold       | `#c9a84c` | Accents, borders, highlights |
| Gold Light | `#e8c97a` | Gradient highlights          |
| Gold Dark  | `#a07c2a` | Gradient shadows             |

---

*Built with Kiro — November 2026*
