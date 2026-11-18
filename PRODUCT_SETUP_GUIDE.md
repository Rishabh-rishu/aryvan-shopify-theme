# Aryvan Botanical Wellness — Merchant Product Setup Guide (Launch 3.0)

This comprehensive guide assists the store merchant in importing, pricing, and connecting the **3 Confirmed Botanical Products** and managing the **4 Coming Soon Slots** in Shopify Admin.

---

## 1. Product Strategy Overview

Aryvan launches with a focused 7-product strategy:

| Product Name | Category | Status | Default Temporary Asset |
|---|---|---|---|
| **Spirulina Powder** | Botanical Powder | Confirmed Harvest | `assets/temp-product-spirulina.webp` |
| **Moringa Powder** | Botanical Powder | Confirmed Harvest | `assets/temp-product-moringa.webp` |
| **Sea Buckthorn Powder** | Botanical Powder | Confirmed Harvest | `assets/temp-product-sea-buckthorn.webp` |
| **Future Harvest Slot 1** | Botanical Formulation | Coming Soon | `assets/temp-coming-soon-1.webp` |
| **Future Harvest Slot 2** | Botanical Formulation | Coming Soon | `assets/temp-coming-soon-2.webp` |
| **Future Harvest Slot 3** | Botanical Formulation | Coming Soon | `assets/temp-coming-soon-3.webp` |
| **Future Harvest Slot 4** | Botanical Formulation | Coming Soon | `assets/temp-coming-soon-4.webp` |

> **Ethical Commerce Rule:** The theme intentionally avoids fake prices or fictitious reviews. If a product does not yet have a price in Shopify, the theme elegantly displays **"Harvest In Progress — Direct inquiry or allocation upon release"** and directs patrons to connect directly.

---

## 2. Importing Products via CSV

A pre-formatted, Shopify-compliant CSV is included in the root of your project:
📁 `aryvan-products-template.csv`

### Steps to Import:
1. Open your **Shopify Admin** (`https://admin.shopify.com/store/<your-store-name>`).
2. Navigate to **Products**.
3. Click the **Import** button in the top right corner.
4. Click **Add file** and select `aryvan-products-template.csv`.
5. Check **"Import products as drafts"** (recommended until your final pricing and weights are confirmed).
6. Click **Upload and preview**, then click **Import products**.

---

## 3. Configuring Pricing, Inventory & Imagery

Once imported into Shopify Admin:

1. **Set Commercial Price:**
   - Click into each product (e.g., *Spirulina Powder*).
   - Under **Pricing**, enter your retail `Price` (and optional `Compare-at price`).
   - Under **Cost per item**, input your COGS for internal profit margin calculation.

2. **Set Inventory & SKU:**
   - Under **Inventory**, assign a unique SKU (e.g., `ARY-SPI-100G`).
   - Specify your available stock quantity at your primary warehouse location.
   - Choose whether to track inventory and stop selling when out of stock.

3. **Upload High-Resolution Product Photography:**
   - Under **Media**, click **Add media**.
   - Upload high-resolution packshots (recommended square ratio: 2000 × 2000 px, or portrait 4:5 ratio).
   - *Note: If no media is uploaded, the theme automatically falls back to the licensed high-res temporary photography in `assets/`.*

4. **Publish the Products:**
   - Under **Product status** (top right), change from **Draft** to **Active**.
   - Under **Publishing**, ensure **Online Store** is selected.

---

## 4. Connecting Products to the Homepage Showcase

The theme features a dynamic product picker for each card:

1. In Shopify Admin, navigate to **Online Store > Themes**.
2. Next to your **Aryvan Botanical Wellness (Draft)** theme, click **Customize**.
3. In the sidebar section tree, click **"Product showcase"** (located directly below Brand Introduction).
4. Expand the blocks:
   - Click on **Confirmed Product — Spirulina Powder**.
   - Under the **"Shopify product link (optional)"** setting, click **Select product**.
   - Choose your newly created **Spirulina Powder** from the picker.
   - Repeat for **Moringa Powder** and **Sea Buckthorn Powder**.
5. Once selected:
   - The card will dynamically display your exact Shopify price (`product.price | money`).
   - The card will automatically link to the high-end Product Detail Page (PDP).
   - The card's title and primary photo will synchronize with your Shopify product catalog while respecting any custom overrides you configure in the theme editor.
6. Click **Save** in the top right corner.

---

## 5. Managing the 4 "Coming Soon" Slots

As your product pipeline matures and new formulations are ready to launch:

1. Open **Shopify Theme Customizer**.
2. Click on the **"Coming soon formulations"** section.
3. You can:
   - Reorder or toggle individual Coming Soon slots.
   - Update the badge label (e.g., `"COMING SOON"`, `"HARVESTING"`, or `"AUTUMN RELEASE"`).
   - Update the botanical teaser notes.
   - Change the temporary botanical mood imagery from the curated dropdown.
4. When a 4th or 5th product is finalized:
   - Add it as an active product in Shopify Admin.
   - Add a new block under **"Product showcase"** and link the new product.
   - Remove or replace the corresponding slot in **"Coming soon formulations"**.

---

## 6. Updating Contact & Representative Details

The homepage and product pages feature direct access to the brand representative:

- **Representative:** Arpit Tripathi
- **Direct Email:** `atripathi7874@gmail.com`

To update these details in the future:
1. In the Theme Customizer, select **"Contact section"** (right above the footer).
2. Edit **Heading**, **Subtext**, **Contact name**, or **Contact email**.
3. All `mailto:` links across the storefront will update automatically.

---

## 7. Recommended Image Specifications

Refer to `TEMPORARY_PHOTOGRAPHY_GUIDE.md` for full attribution and replacements:

- **Product Showcase Packshots:** 1600 × 2000 px (4:5 ratio) or 1600 × 1600 px (1:1), WebP or JPG, `< 250 KB`.
- **Hero & Story Banners:** 2880 × 1620 px (16:9 ratio), WebP or JPG, `< 350 KB`.
- **Apothecary Collection Tiles:** 1200 × 1500 px (4:5 ratio), WebP or JPG, `< 200 KB`.
