# Razab USA — Thanksgiving 2026 Email Campaign (Design Concept 2: High-Energy Retail)
### High-Impact, Conversion-Focused Responsive HTML Email & Asset Suite

This repository contains the second email design variation for **Razab USA's Thanksgiving 2026 Campaign ("The Thanksgiving Harvest Mega Sale")**.

---

## 1. Concept Direction: Bold Holiday Sale & High-Energy Retail
Unlike Concept 1's muted heirloom/parchment aesthetic, **Concept 2** is engineered for high conversion, commercial urgency, and retail impact:
- **Palette:** Rich Spiced Cranberry (`#9E1A1A`), Vibrant Warm Amber/Pumpkin (`#D96B27`), Harvest Gold (`#F5A623`), Crisp White & Cream contrast surfaces (`#FFFFFF`, `#FAF7F2`), and Deep Charcoal Espresso foundations (`#1B120E`).
- **Visual Hooks:**
  - Dynamic sale highlight badges (`SAVE 20%`, `LIMITED STOCK`, `BESTSELLER`).
  - Eye-catching discount announcement bar with code **`HARVEST`**.
  - High-urgency countdown timer block and Thanksgiving feast prep timeline.
  - Value-proposition icon ribbons (Oven Safe to 1040°F, 100% Airtight & Leakproof, BPA-Free Borosilicate Glass).
  - Clear, prominent dual CTAs optimized for click-through rate.

---

## 2. Campaign & Offer Specs
- **Brand:** Razab USA (Borosilicate Glass Food Storage & Bakeware)
- **Campaign Title:** Thanksgiving Harvest Mega Sale — *Cook, Serve, Store & Savor*
- **Offer:** **20% OFF Everything** with code **`HARVEST`**
- **Free Shipping:** Free US shipping on qualifying orders
- **Key Products Featured:**
  1. **The Ultimate Host's Set (30-Piece Glass Food Storage)**
  2. **The Jumbo Potluck Carrier (6500ML Glass Roaster with Locking Lid)**
  3. **The Pastry, Pie & Casserole Keeper (3900ML)**
  4. **The Holiday Baker (Borosilicate Glass Loaf Pan Set)**

---

## 3. Email File Structure
```text
razab-thanksgiving 2/
├── index.html                     # Primary high-energy production HTML email template
├── email.html                     # Mirror copy for multi-client testing & Klaviyo/Mailchimp import
├── README.md                      # Campaign documentation and deployment guide
├── .gitignore                     # Git configuration
└── assets/                        # High-resolution product photography, logos, and badges
```

---

## 4. ESP Deployment & Compatibility
- **Tested & Optimized for:** Gmail (Web, iOS, Android), Apple Mail (macOS, iOS), Outlook (2016-2021, M365, Web), Yahoo Mail.
- **Klaviyo Merge Tags:**
  - Unsubscribe: `{{ unsubscribe_url }}`
  - Preferences: `{{ preferences_url }}`
  - View in browser: `{{ view_in_browser_url }}`
- **Mailchimp Merge Tags:**
  - Unsubscribe: `*|UNSUB|*`
  - Web version: `*|ARCHIVE|*`
