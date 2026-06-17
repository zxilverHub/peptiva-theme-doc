# Peptiva — Theme Setup Guide

A clean, premium skincare theme for Shopify (Online Store 2.0). This guide walks you
through setting up the theme after install. Copy this into your public docs page
(e.g. Notion → Share → Publish).

---

## 1. Getting started
1. In Shopify admin go to **Online Store → Themes**.
2. Your theme appears in the theme library. Click **Customize** to open the editor.
3. Everything is edited visually in the **theme editor** (sections, blocks, settings).

## 2. Theme settings (global)
Open the editor → **Theme settings** (gear icon, bottom-left):
- **Colors** — set your palette: Accent, Accent text, Body text, Background, Muted surface,
  Dark surface, Text on dark, Borders. *Most sections pull from this palette via a
  "Color scheme" dropdown, so changing a color here updates the whole theme.*
- **Typography** — Heading font + Body font (from Shopify's font library), with size scales.
- **Layout** — page width, section spacing, corner radius, favicon.
- **Buttons** — button corner radius.
- **Cart** — drawer or page.
- **Social media** — your social links (used in the footer).

## 3. Header
Edit **Header group → Header**:
- **Sticky behavior** — Never / Fixed / Show on scroll up (magic) / Stays + compact on scroll.
- **Logo** — upload a logo or use the store name; position (left/center); size.
- **Menu** — choose your menu; link style (underline / pill / color); gap; active color.
- **Icons** — show/hide search, account, cart; search as icon or input box.
The **Announcement bar** (Header group) supports multiple rotating messages.

## 4. Homepage sections
Add/reorder via **Add section**. Most sections include a **Color scheme** dropdown,
**Section padding**, and an optional **Decorative shapes** group (toggle + up to 3 shapes).

| Section | What it's for |
|---|---|
| **Hero** | Headline + image. Layouts: 3-column, image left/right, centered. Height, title size, media shape. Blocks: buttons, stat, heading, text, badge. |
| **Value badges** | Trust row (Cruelty-Free, Vegan, Dermatologist-Tested…). |
| **Logo list** | "As seen in" press/cert strip (image or text). |
| **Product marquee** | Scrolling product-name ticker from a collection. |
| **Shop by concern** | Image tiles linking to concern collections; grid/flex + alignment options. |
| **Featured collection** | Product grid from a chosen collection. |
| **Feature banner** | Bold statement banner with arrow/button CTA and decorative circle. |
| **Ingredient teaser** | Active-ingredient cards (icon/image, benefit, link). |
| **Product values** | Brand values with image + value list (3-column / image-left/right / grid). |
| **Routine finder CTA** | Quiz/routine call-to-action banner. |
| **Before & after** | Draggable before/after comparison slider. |
| **Guarantee** | Promise icons (shipping, returns, secure, support). |
| **Testimonials** | Reviews (grid / scroll / masonry), star ratings, color scheme. |
| **Social gallery** | UGC grid/scroll with captions/links. |
| **Blog posts** | Latest posts from a blog. |
| **CTA banner** | Closing call-to-action; full-width option, background image + overlay. |
| **Image with text** | Story block (image + text), aspect-ratio & fit options. |
| **Rich text** | Simple heading + text + button. |
| **Newsletter** | Email signup band; background image + overlay options. |
| **FAQ** | Accordion Q&A (centered or split layout). |

## 5. Pages & templates
Create pages in **Online Store → Pages → Add page**, then set the **Theme template**
(right sidebar) and **Save**:

| Page | Template to choose |
|---|---|
| About | `page.about` |
| Ingredients (Science) | `page.ingredients` (searchable ingredient library) |
| Routines | `page.routines` (quiz + AM/PM routines) |
| Contact | `page.contact` (form + live-chat notice) |
| COA / Transparency (optional) | `page.coa` |

## 6. Navigation menus
**Online Store → Navigation → Main menu**. Suggested links:
Home (`/`), Shop (a collection), Ingredients (`/pages/ingredients`),
Routines (`/pages/routines`), Journal (`/blogs/news`), About (`/pages/about`),
Contact (`/pages/contact`). Build a **Footer** menu too.
Fill **Settings → Policies** (Refund, Privacy, Terms, Shipping) — the footer Policies
column lists them automatically.

## 7. Collections & Shop-page filters
- Create **Collections** (Products → Collections). Automated collections by tag/type work
  great (e.g. type = Serum, or tag = "Dark Spots").
- Point the **Shop** menu link and the homepage **Shop by Concern** tiles at these.
- For the filter sidebar on the Shop page, install the free **Shopify Search & Discovery**
  app → **Filters** → add Price, Product type, and tag/metafield filters
  (Skin Concern, Skin Type, Key Ingredient).

## 8. Products
- Import products (Products → Import). Add **tags** for type / concern / ingredient / skin
  type so the Shop filters work.
- On the **product template** you can add blocks: At-a-glance summary, Best-for skin types,
  Key actives, How to use, Clinical results, Full ingredient list, Lab report, Collapsible row.
- Add product **images** for the gallery.

## 9. Blog
Shopify's default **News** blog (`/blogs/news`) works out of the box. Add posts in
**Online Store → Blog posts** with a featured image. The blog page supports a featured
post, tag filter, and column options.

## 10. Footer
**Footer group → Footer** is built from blocks across 3 layers:
- **Layer 1:** Brand (logo + description), Menu columns, a Contact block, and/or Newsletter.
- **Layer 2:** Notice (e.g. usage/safety note) with alignment & UI style.
- **Layer 3:** Credit line + Social icons (from Theme settings → Social media).

## 11. Recommended image sizes
- Hero / CTA product image: ~1000–1400px wide (transparent PNG looks best).
- Section/lifestyle images: ~1600px wide.
- Shop-by-concern tiles: ~600×800 (3:4).
- Before/after: matching dimensions per pair.
- Logos: transparent PNG/SVG, ~200px.

## 12. Color schemes & decorative shapes
- **Color scheme** dropdowns (on most sections) pull from Theme settings → Colors, so the
  whole theme stays consistent — change a palette color once and it updates everywhere.
- **Decorative shapes** (on many sections): toggle on, then add up to 3 shapes
  (circle / ring / blob / square / dots) with position, color, size and opacity.

## 13. Support
Need help? Contact **silverdaveramos021503@gmail.com**.
