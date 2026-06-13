# Project 3 - The Visual Identity
### DecodeLabs UI/UX Design Internship · Batch 2026

---

## Overview

This is the third milestone of the DecodeLabs Industrial Training Kit. After researching the user (Project 1) and building the wireframe skeleton (Project 2), Project 3 is where everything finally comes to life visually.

The client is a premium organic food delivery service. The goal is to design a high fidelity mobile UI that feels trustworthy, fresh, and premium not loud, not fast food, not generic. Every color, font, and spacing decision needs to mean something.

**Scenario:** The brand needs a visual identity that communicates trust, health, and speed through colors and typography alone before a single word is read.

---

## Deliverables

| Deliverable | Description |
|---|---|
| Style Tile | Color palette, typography, button styles, and a sample product card — all in one Figma frame |
| Splash Screen | The first thing users see when they open the app — brand feel, logo, tagline |
| Product List | A scrollable screen showing food items in a clean grid with images, names, and prices |
| Product Detail | A full product page with hero image, name, price, certifications, and Add to Cart button |

---

## Color Palette

| Color | Name | Hex | When to Use |
|---|---|---|---|
| 🟢 | Leaf Green | `##3D6B35` | Primary brand color — buttons, icons, accents |
| 🟤 | Earthy Brown | `#4A2E1A` | Body text, secondary elements |
| 🟡 | Harvest Gold | `#C4973A` | Loading states and delight moments only — use sparingly |
| 🟫 | Off-White / Cream | `#F5F0E8` | Background color throughout the app |

> **Avoid red entirely.** No urgency signals, no fast-food energy.

---

## Typography

| Role | Font | Style | Used For |
|---|---|---|---|
| Headlines | Playfair Display | Serif | Product names, screen titles, brand statements |
| Body | Montserrat | Sans-Serif | Prices, descriptions, labels, everything else |
---

## Spacing System — 8-Point Grid

Every margin, padding, and spacing value must be a **multiple of 8**.

| Value | Use |
|---|---|
| `8px` | Tight internal spacing (between text lines, icon gaps) |
| `16px` | Standard screen margins |
| `24px` | Section padding, card inner spacing |
| `48px` | Button height (minimum tap target) |

This keeps the layout consistent across all screen sizes and densities (@1x, @2x, @3x).

---

## Screen-by-Screen Notes

**Splash Screen**
- Background: Off-White `#F5F0E8`
- Brand logo centered
- Tagline in Playfair Display
- Keep it minimal — one image, one message

**Product List**
- 2-column product card grid
- Each card: food image (natural light), product name in Playfair, price + calories in Montserrat
- Search bar at top with 16px side margins
- Category pills below the search bar

**Product Detail**
- Full-width hero food image at top
- Product name (Playfair, large), then price and calorie info (Montserrat)
- USDA Organic / Non-GMO certification badges visible
- Add to Cart button: full width, 48px height, Leaf Green `#3D6B35`, white text

---

## Accessibility

- Minimum text contrast ratio: **4.5:1** (WCAG AA standard)
- The brief's heading example achieves **15.8:1** — aim for this on key text
- Never use color alone to show errors — always combine shape + icon + text
- Error state example: red border + warning icon + "Invalid email address" label

---

## Tools Used

- Figma / Adobe XD

---
