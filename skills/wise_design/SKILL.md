---
name: wise_design
description: "Guidelines and reference documentation for the Wise Design System (Neptune Design System), including its typography, color palettes, core grid spacing, border radii, and 50+ UI components and patterns."
---

# Wise Design System (Neptune CSS) Skill

You are equipped with the knowledge of the **Wise Design System** (also known as the **Neptune Design System**), which is used to build consistent, premium, and accessible products for Wise.

---

## 1. Design System Core Principles

### Core Aesthetics & Brand Colours
*   **Vibrant & Energetic:** The Wise brand uses high-contrast, curated color combinations.
*   **The Green Identity:** Wise is primary green.
    *   `Bright Green`: `#9FE870` (used for key interactive accent surfaces, e.g., Primary Buttons).
    *   `Forest Green`: `#163300` (used for text/icons on Bright Green, dark backgrounds, and core interactivity).
*   **Secondary Palette:** Inspired by global cultures. Used to add warmth and metaphors deep in flows or marketing screens.
    *   `Bright Orange`: `#FFC091`
    *   `Bright Yellow`: `#FFEB69`
    *   `Bright Blue`: `#A0E1E1`
    *   `Bright Pink`: `#FFD7EF`
    *   `Dark Purple`: `#260A2F`
    *   `Dark Gold`: `#3A341C`
    *   `Dark Charcoal`: `#21231D`
    *   `Dark Maroon`: `#320707`

### Semantic Product Tokens
*   `Content Primary`: Light mode `#0E0F0C` / Dark mode `#f3f5f1` (`--color-content-primary`)
*   `Content Secondary`: Light mode `#454745` / Dark mode `#e8ebe6` (`--color-content-secondary`)
*   `Content Tertiary`: Light mode `#6A6C6A` / Dark mode `#cacfc7` (`--color-content-tertiary`)
*   `Content Link`: Light mode `#163300` / Dark mode `#9fe870` (`--color-content-link`)
*   `Interactive Primary`: Light mode `#163300` / Dark mode `#9fe870` (`--color-interactive-primary`)
*   `Interactive Accent`: Light mode `#9FE870` / Dark mode `#9fe870` (`--color-interactive-accent`)
*   `Background Screen`: Light mode `#FFFFFF` / Dark mode `#121511` (`--color-background-screen`)
*   `Background Elevated`: Light mode `#FFFFFF` / Dark mode `#1e211d` (`--color-background-elevated`)
*   `Border Neutral`: Light mode `#0E0F0C` (12% opacity) / Dark mode `#FFFFFF` (20% opacity) (`--color-border-neutral`)

---

## 2. Typography
*   **Wise Sans:** Custom display font, heavy and uppercase. Used only for display headings and key success/celebration moments (e.g., Success screen).
*   **Inter:** Standard functional sans-serif typeface. Used for all form inputs, body text, UI actions, and links to maximize readability and accessibility.
*   **Text Hierarchy:**
    *   Display 1 (Heavy 56px to 128px, Line height 85%)
    *   Heading 1 (Semi Bold 42px to 78px, Line height 46px to 82px)
    *   Heading 2 (Semi Bold 37px to 53px)
    *   Body 2 (Regular/Semi Bold 16px to 18px)
    *   Body 3 (Regular/Semi Bold 14px to 16px)

---

## 3. Spacing Grid & Border Radii
*   **Grid:** 8px base grid (`size-4` = 4px, `size-8` = 8px, `size-12` = 12px, `size-16` = 16px, `size-24` = 24px, `size-32` = 32px).
*   **Horizontal Semantic Spacing:**
    *   `between-cards`: `size-12` (12px)
    *   `between-chips`: `size-8` (8px)
    *   `screen-mobile`: `size-24` (24px)
    *   `component-default`: `size-16` (16px)
*   **Vertical Semantic Spacing:**
    *   `between-text`: `size-8` (8px)
    *   `display-text-bottom`: `size-16` (16px)
    *   `text-to-component`: `size-16` (16px)
    *   `content-to-button`: `size-24` (24px)
    *   `between-sections`: `size-32` (32px)
*   **Radii (Mobile):**
    *   `radius-small`: 10px
    *   `radius-medium`: 16px
    *   `radius-large`: 24px
    *   `radius-x-large`: 32px
    *   `radius-2x-large`: 48px

---

## 4. Neptune CSS Reference Code

When building web applications using the Neptune design system, implement layouts by referencing the styling class hooks:
```html
<!-- Primary Button Example -->
<button class="wds-Button wds-Button--large wds-Button--primary">
  <span class="wds-Button-content">
    <span class="wds-Button-label">
      <span class="wds-Button-labelText">Send Money</span>
    </span>
  </span>
</button>

<!-- Section Header Example -->
<div class="np-section-header">
  <h2 class="np-text-heading-2">Send Money</h2>
</div>
```

Refer to the detailed reference documents inside the `references/` folder:
*   [Foundations Guide](file:///references/foundations.md) - Exact hex values, typographic scales, spacing tokens, accessibility tables.
*   [Components Guide](file:///references/components.md) - Rules, props, and variants for 50+ components (Buttons, Cards, Inputs, Modals, etc.).
*   [Patterns Guide](file:///references/patterns.md) - Rules and design guidelines for layouts, screens (success, error), and notification grids.
