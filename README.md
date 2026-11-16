# Razab USA — Thanksgiving 2026 Email Campaign (The Harvest Table Showcase)
### Responsive HTML Email & Asset Suite

This repository contains the email template for **Razab USA's Thanksgiving 2026 Campaign ("The Harvest Table")**, matching the reference showcase specification.

---

## 1. Design Direction: The Harvest Table Showcase
- **Layout:** Unified 600px email container (`.rz-wrap`) framed on a warm linen background (`#EFE6D6`), finished with soft shadow and rounded corners.
- **Palette:** 
  - Deep Forest Greens: `#26392B`, `#2F4A35`, `#385A40`
  - Harvest Gold & Amber Accents: `#F7CC83`, `#C87F4E`, `#C9A25A`
  - Warm Parchment & Cream Surfaces: `#FAF7F2`, `#EFE3CC`, `#FBEFD2`, `#FFFFFF`
  - Typography Colors: Terracotta `#8F544A` (headings), Deep Chestnut `#5A3D36` (body)
- **Typography:**
  - Headings: Playfair Display (Georgia fallback for Outlook)
  - Body & UI: Inter (Arial/sans-serif fallback)

---

## 2. Template Structure & Sections
1. **Preheader:** Hidden preview text with zwnj padding (`Pull up a chair at The Harvest Table: 20% off every Razab glass container with code HARVEST...`).
2. **Top Strip:** Deep forest banner (`Thanksgiving Sale · 20% Off · Code HARVEST`).
3. **Masthead:** Header with Razab logo (`assets/razab-logo.png`), tagline, and navigation links.
4. **Hero Banner:** Full-bleed Thanksgiving Sale banner (`assets/hero-thanks2.jpg`, 600×804) featuring the Thanksgiving container casserole feast, autumn harvest pumpkins and foliage, 20% discount offer, and promo code `HARVEST`.
5. **Gilded Accent Dividers:** 4px gradient separators (`#C87F4E` to `#F7CC83`).
6. **The Feature Video:** Full-bleed interactive video (`assets/hero sec video 2.mp4` / `assets/hero-sec-video-2.mp4`, 600×338) with autoplay, loop, muted, playsinline, featuring the container opening with glowing "HURRY UP! THANKSGIVING SALE IS LIVE" rising smoke text, and high-res poster fallback (`assets/hero-video-poster.jpg`).
7. **Brand Story:** "Feast Today. Fresh All Week." story block with three core value badges (*Freezer to oven*, *Airtight seal*, *See every leftover*).
8. **Product Mosaic:** 2×2 edge-to-edge product grid:
   - **The Host's Set** (30 Pc Glass Food Storage Set — `assets/p-host.jpg`)
   - **The Potluck Carrier** (6500ML Extra Large Container — `assets/p-carry.jpg`)
   - **The Pastry & Pie Keeper** (3900ML Airtight Container — `assets/p-keeper.jpg`)
   - **The Holiday Baker** (Glass Loaf Pans with Lids — `assets/p-loaf.jpg`)
9. **Honey Promo Band:** Inline promo reminder code banner.
10. **Spotlight Section:** Split feature on The Thanksgiving Loaf Pans (`assets/pantry-thanksgiving.jpg`) with deep forest CTA button (`Bake for the feast`).
11. **Footer:** Full-bleed autumn landscape painting (`assets/harvest-footer.jpg`), warm holiday greeting, light logo (`assets/razab-logo-light.png`), social links, coupon terms, and compliant footer links (Unsubscribe, Preferences, View in Browser).

---

## 3. Campaign & Offer Specs
- **Brand:** Razab USA (Borosilicate Glass Food Storage & Bakeware)
- **Campaign Title:** Thanksgiving Sale — The Harvest Table
- **Offer:** **20% OFF** with code **`HARVEST`**
- **Validity:** November 20 to November 27, 2026 (Ends 11:59 PM EST)

---

## 4. File Structure
```text
razab-thanksgiving-2/
├── index.html                     # Primary production HTML email template
├── email.html                     # Mirror copy for ESP testing & Klaviyo/Mailchimp import
├── thanksgiving-2026-email.html   # Standalone campaign showcase file
├── README.md                      # Campaign documentation
├── .gitignore                     # Git configuration
└── assets/                        # High-resolution product photography, logos, and GIFs
```

---

## 5. ESP Deployment & Compatibility
- **Tested & Optimized for:** Gmail (Web, iOS, Android), Apple Mail (macOS, iOS), Outlook (2016-2021, M365 with VML fallback buttons and MSO conditionals), Yahoo Mail.
- **Klaviyo Merge Tags:**
  - Unsubscribe: `{{ unsubscribe_url }}`
  - Preferences: `{{ preferences_url }}`
  - View in browser: `{{ view_in_browser_url }}`
  - Company Address: `{{ company_address }}`
