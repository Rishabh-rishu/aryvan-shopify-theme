# Aryvan Botanical Wellness — Temporary Photography Replacement Guide

> **Note for Merchant / Production Launch:**
> All photographic assets prefixed with `temp-` in the `assets/` folder are licensed temporary stock photographs intended strictly for design presentation and layout validation during development.
> **Before publishing the theme or launching the live store**, replace these files with your proprietary Aryvan product and brand photography.

---

## 1. Inventory of Temporary Image Assets

### A. Confirmed Products (Launch 3.0)
| File Name | Purpose / Placement | Recommended Dimensions | Format | Source / License |
|---|---|---|---|---|
| `temp-product-spirulina.webp` | Product 01: Spirulina Powder | 800 × 1000 px (4:5) | WebP or JPG | Unsplash (Free Commercial Use) |
| `temp-product-moringa.webp` | Product 02: Moringa Powder | 800 × 1000 px (4:5) | WebP or JPG | Unsplash (Free Commercial Use) |
| `temp-product-sea-buckthorn.webp` | Product 03: Sea Buckthorn Powder | 800 × 1000 px (4:5) | WebP or JPG | Unsplash (Free Commercial Use) |

### B. Coming Soon Product Slots (4 Future Slots)
| File Name | Purpose / Placement | Recommended Dimensions | Format | Source / License |
|---|---|---|---|---|
| `temp-coming-soon-1.webp` | Coming Soon Slot 1 (Organic Seed / Macro) | 800 × 1000 px (4:5) | WebP or JPG | Unsplash (Free Commercial Use) |
| `temp-coming-soon-2.webp` | Coming Soon Slot 2 (Sunlit Foliage Contour) | 800 × 1000 px (4:5) | WebP or JPG | Unsplash (Free Commercial Use) |
| `temp-coming-soon-3.webp` | Coming Soon Slot 3 (Artisanal Apothecary Studio) | 800 × 1000 px (4:5) | WebP or JPG | Unsplash (Free Commercial Use) |
| `temp-coming-soon-4.webp` | Coming Soon Slot 4 (Amber Glass / Natural Drops) | 800 × 1000 px (4:5) | WebP or JPG | Unsplash (Free Commercial Use) |

### C. Homepage Editorial & Brand Story Assets
| File Name | Purpose / Placement | Recommended Dimensions | Format | Source / License |
|---|---|---|---|---|
| `temp-hero-botanical.webp` | Homepage Hero Banner background | 1920 × 1080 px (16:9) | WebP or JPG | Photo by Chris Lee on Unsplash (Free Commercial Use) |
| `temp-collection-elixirs.webp` | Featured Collection 1 (Restorative Elixirs) | 800 × 1000 px (4:5) | WebP or JPG | Photo by Sarah Chai on Unsplash (Free Commercial Use) |
| `temp-collection-skincare.webp` | Featured Collection 2 (Botanical Skincare) | 800 × 1000 px (4:5) | WebP or JPG | Photo by Content Pixie on Unsplash (Free Commercial Use) |
| `temp-collection-teas.webp` | Featured Collection 3 (Herbal Teas & Infusions) | 800 × 1000 px (4:5) | WebP or JPG | Photo by Tea Creative on Unsplash (Free Commercial Use) |
| `temp-brand-story.webp` | Brand Story editorial narrative section | 1200 × 1500 px (4:5) | WebP or JPG | Photo by Nourish on Unsplash (Free Commercial Use) |
| `temp-botanical-ingredients.webp` | Botanical Ingredients & Natural Principles section | 1200 × 900 px (4:3) | WebP or JPG | Photo by Luca Bravo on Unsplash (Free Commercial Use) |
| `temp-wellness-ritual.webp` | Best Sellers & Ritual showcase fallback | 1000 × 1200 px (4:5) | WebP or JPG | Photo by Mathilde Langevin on Unsplash (Free Commercial Use) |

---

## 2. How to Replace with Official Aryvan Photography

### Option A: Via Shopify Theme Editor (Recommended)
Each section in the theme includes an intuitive **Image Picker** setting:
1. From Shopify Admin, go to **Online Store > Themes**.
2. Click **Customize** next to the Aryvan draft theme.
3. Select any section (e.g. **Product showcase**, **Coming soon products**, **Hero banner**, **Brand story**, or **Botanical ingredients**).
4. In the settings sidebar, click **Select image** to upload your brand's official photography.
5. The uploaded image overrides the default temporary asset automatically.

### Option B: Replace Direct Files in `assets/`
If you wish to update the default fallback assets directly in code:
1. Prepare your optimized images in `.webp` format using the recommended dimensions above.
2. Overwrite the files in the `assets/` directory maintaining the same filename (or update references).
3. Commit and push the changes to GitHub.

---

## 3. Image Optimization Best Practices for Luxury Storefronts

- **File Formats**: Use `.webp` for maximum compression and fidelity. For transparent backgrounds, use WebP or PNG.
- **Target File Sizes**: Keep hero images under 250KB and card/editorial images under 100KB to ensure fast LCP (Largest Contentful Paint).
- **Aspect Ratios**:
  - Hero banners: 16:9 or 21:9 wide landscape.
  - Product & collection cards: 4:5 vertical portrait.
  - Ingredients & feature grids: 4:3 or 1:1 square.
- **Color Temperature**: Maintain warm, natural, earthy tones (warm ivory highlights, deep forest greens, soft natural sunlight) for visual consistency across all imagery.
