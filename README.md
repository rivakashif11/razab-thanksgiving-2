# Razab USA — Thanksgiving 2026 Email Campaign (The Harvest Table Showcase)
### Responsive HTML Email & Asset Suite

This repository contains the email template for **Razab USA's Thanksgiving 2026 Campaign ("The Harvest Table")**, matching the reference showcase specification.

---

## 1. Design Direction: The Harvest Table Showcase
- **Layout:** Unified 600px email container (`.rz-wrap`) framed on a warm linen background (`#EFE6D6`), finished with soft shadow and rounded corners.
- **Palette:** 
  - Deep Forest Greens: `#26392B`, `#2F4A35`, `#385A40`
  - Harvest Gold & Amber Accents: `#F7CC83`, `#C87F4E`, `#C9A25A`
  - Warm Parchment & Cream Surfaces: `#FDEBCB` (matching the Hero Section parchment tone), `#EFE6D6` (outer canvas), `#F7CC83`
  - Typography Colors: Terracotta `#8F544A` (headings), Deep Chestnut `#5A3D36` (body)
- **Typography:**
  - Headings: Playfair Display (Georgia fallback for Outlook)
  - Body & UI: Inter (Arial/sans-serif fallback)

---

## 2. Template Structure & Sections
0. **Seamless Integrated Thanksgiving Background:** Unified 600px container (`.rz-wrap`) rendered as a single-column layout with a high-resolution feathered background image (`assets/thanksgiving-page-bg.jpg`, 1200×1040 Retina). The Thanksgiving aesthetic borders (dark wood, pumpkins, autumn foliage) blend continuously into the solid warm cream/beige center (`#FDEBCB` from the hero section) via a smooth 32px cosine feathering gradient. This completely eliminates any vertical gaps, seams, or dividing lines between the page content and the side borders while keeping the total width strictly at **600px**. Product cards and inner sections are styled with `#FDEBCB` to create a harmonious, unified aesthetic.
1. **Preheader:** Hidden preview text with zwnj padding (`Pull up a chair at The Harvest Table: 20% off every Razab glass container with code HARVEST...`).
2. **Top Strip:** Deep forest banner (`Thanksgiving Sale · 20% Off · Code HARVEST`).
3. **Masthead (Dark Wood & Autumn Foliage Canvas):** Header set against a continuous rustic dark wood and autumn leaves background (`assets/thanksgiving-header-bg.jpg`, `#3E2417`), seamlessly extending the wood and foliage textures all the way up to the top green strip with zero cream box overlay. Features the crisp light Razab logo (`assets/razab-logo-light.png`), light cream navigation links (`#FAF7F2`), and harvest gold separator dots (`#F7CC83`) for clean contrast.
4. **The Feature Video (6500ML Container):** Full-bleed showcase video (`assets/hero sec 6500ml.mp4` / `assets/hero-sec-6500ml.mp4`, 600×338) positioned directly below the Masthead in the primary hero spot, featuring autoplay, loop, muted, playsinline, and high-res poster fallback (`assets/hero-6500ml-poster.jpg`).
5. **Gilded Accent Dividers:** 4px gradient separators (`#C87F4E` to `#F7CC83`).
6. **Thanksgiving Sale Animated Banner:** Full-bleed animated banner (`assets/thanks-hero-3.gif`, 600×804, 327 KB) positioned right below the video, featuring animated rising steam from the hot roast turkey inside the clear glass container and subtle candlelight blink/glow on the autumn pumpkins. Outlook desktop displays the clean static frame 0.
7. **Brand Story:** "Feast Today. Fresh All Week." story block with three core value badges (*Freezer to oven*, *Airtight seal*, *See every leftover*).
8. **The Harvest Collection Cards:** 2×2 spacious, elevated product card grid with dedicated margins, rounded corners, soft drop shadow, discount pills, and distinct terracotta "Shop Now →" CTA buttons:
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
