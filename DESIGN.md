---
name: Lumina Carta Digital
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#45474c'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#75777d'
  outline-variant: '#c5c6cd'
  surface-tint: '#545f73'
  primary: '#091426'
  on-primary: '#ffffff'
  primary-container: '#1e293b'
  on-primary-container: '#8590a6'
  inverse-primary: '#bcc7de'
  secondary: '#536347'
  on-secondary: '#ffffff'
  secondary-container: '#d4e6c2'
  on-secondary-container: '#58674b'
  tertiary: '#2d0600'
  on-tertiary: '#ffffff'
  tertiary-container: '#501301'
  on-tertiary-container: '#d4765a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e3fb'
  primary-fixed-dim: '#bcc7de'
  on-primary-fixed: '#111c2d'
  on-primary-fixed-variant: '#3c475a'
  secondary-fixed: '#d6e8c5'
  secondary-fixed-dim: '#bbccaa'
  on-secondary-fixed: '#121f09'
  on-secondary-fixed-variant: '#3c4b31'
  tertiary-fixed: '#ffdbd0'
  tertiary-fixed-dim: '#ffb59f'
  on-tertiary-fixed: '#3a0a00'
  on-tertiary-fixed-variant: '#793019'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display:
    fontFamily: Plus Jakarta Sans
    fontSize: 2.25rem
    fontWeight: '700'
    lineHeight: 2.75rem
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.75rem
    fontWeight: '600'
    lineHeight: 2.25rem
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.375rem
    fontWeight: '600'
    lineHeight: 1.75rem
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.625rem
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.125rem
    fontWeight: '600'
    lineHeight: 1.5rem
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.6rem
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.45rem
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '600'
    lineHeight: 1.25rem
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: 1rem
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.6875rem
    fontWeight: '500'
    lineHeight: 0.875rem
    letterSpacing: 0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-desktop: 2.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.875rem
  space-lg: 1.25rem
  space-xl: 2rem
---

## Brand & Style
The design system embodies contemporary hospitality: airy, architectural, and effortlessly legible under any ambient dining light. Built specifically for mobile QR-code scanning, it rejects dark, ornate, or faux-luxurious tavern tropes in favor of editorial Scandinavian minimalism. 

Key attributes:
- **Atmosphere:** Sunlit, pristine, unhurried, and refined.
- **Audience:** Contemporary diners seeking instant, friction-free readability, clear allergen indicators, and curated dish storytelling directly on mobile browsers.
- **Design Philosophy:** Organic modern minimalism. Surfaces leverage pure white and whisper-light slate washes, paired with generous breathing room, high-contrast charcoal typography, and subdued botanical accents (soft olive and muted terracotta) for state changes and dietary callouts.

## Colors
The palette evokes clean porcelain and organic ingredients, completely free of muddy tones, high-gloss gradients, or synthetic neon.

- **Primary (`#1E293B` - Deep Charcoal Slate):** Anchors typographic hierarchy, titles, prices, and high-priority actionable triggers. Replaces pure black to eliminate harsh optical contrast on bright mobile screens.
- **Secondary (`#5F6F52` - Muted Olive Sage):** Applied to active navigation pills, vegetarian/vegan labels, and positive interactive selections. Evokes fresh herbs and culinary craft.
- **Tertiary (`#C86D51` - Soft Terracotta):** Used selectively for chef’s recommendations, spice notes, wine pairings, and subtle notification badges without creating alarming urgency.
- **Neutral (`#F8FAFC` - Porcelain Wash) & Neutral Subtle (`#F1F5F9` - Pale Slate):** Provides surface tinting for dish cards, section dividers, and search bars against the `#FFFFFF` canvas.

## Typography
Plus Jakarta Sans provides geometric warmth and open apertures, guaranteeing effortless scanning under dim candlelight or direct sunlight. 

- **Prices:** Displayed using `headline-md` or `headline-sm` with a semi-bold weight (`600`), set in charcoal `#1E293B`, aligned directly with or beside the dish name for instantaneous comprehension.
- **Dish Descriptions:** Rendered in `body-md` using a muted text tone (`#64748B`), balancing editorial character with scanning comfort.
- **Dietary & Allergen Markers:** Capitalized or title-cased using `label-sm` with slight positive tracking to preserve legibility at micro dimensions.

## Layout & Spacing
A mobile-first fluid layout optimized for single-handed thumb interaction on mobile browsers, scaling up to an elegant centered multi-column editorial grid on tablets and desktop management views.

- **Mobile Viewport (up to 640px):** Single-column stack with `margin: 1rem`. Sticky horizontal navigation pill bar for categories (Starters, Mains, Desserts, Wines) with subtle fade masks on screen edges.
- **Tablet / Large Mobile (641px - 1024px):** 2-column dish card arrangement with `gutter: 1.25rem` and max-width container set to 720px.
- **Desktop / Kiosk (1025px+):** Centered card layout constrained to a maximum width of 960px with `margin-desktop: 2.5rem`.
- **Rhythm Rules:** Generous vertical element separation prevents touch errors. Cards enforce internal padding of `space-lg` to create an uncluttered, high-end dining presentation.

## Elevation & Depth
Depth is created primarily through tonal planar layering and crisp low-contrast borders rather than traditional dark drop shadows.

- **Base Canvas:** Pure `#FFFFFF`.
- **Surface Tier (Dish Cards & Search):** `#F8FAFC` base fill, bordered by a single crisp outline: `1px solid #E2E8F0`.
- **Subtle Ambient Lift:** Cards use an ultra-diffused, barely perceptible shadow: `box-shadow: 0 2px 8px -2px rgba(30, 41, 59, 0.04)`.
- **Active / Floating Overlays (Filter Chips & Sticky Category Nav):** Pure white `#FFFFFF` backdrop with `backdrop-filter: blur(12px)` and `box-shadow: 0 4px 16px -4px rgba(30, 41, 59, 0.06)`, framed by `1px solid rgba(226, 232, 240, 0.8)`.

## Shapes
A balanced medium curve structure (`0.5rem` base, scaling to `1rem` on container elements) ensures dish cards feel contemporary, gentle, and tactile without drifting into juvenile or overly bubble-like aesthetics.

- **Dish Card Containers:** `1rem` (`rounded-lg`) corners provide a soft, framed enclosure for imagery and text.
- **Images:** Scaled with matching internal corner radius (`0.75rem`) to maintain parallel rhythm within card containers.
- **Chips, Badges & Filters:** Pill-style or slightly rounded (`0.5rem` to full round) to clearly signal interactive tactile status.

## Components

### Dish Cards (Core Menu Item)
- **Structure:** Either horizontal split (text on left, square food thumbnail on right) for compact scanning, or stacked vertical banner for featured plates.
- **Background & Border:** Background `#F8FAFC`, border `1px solid #E2E8F0`, corner radius `1rem`.
- **Spacing:** Inner padding of `1.25rem`. 
- **Typography:** Dish title in `headline-sm` (`#1E293B`), price in `headline-sm` (`#1E293B`), description in `body-md` (`#64748B`).

### Category Navigation (Sticky Chips & Tabs)
- **Idle State:** Surface `#F1F5F9`, text `#64748B`, border `1px solid transparent`.
- **Active State:** Background `#5F6F52` (Olive) or `#1E293B` (Charcoal Slate), text `#FFFFFF`, soft shadow `0 2px 6px rgba(95, 111, 82, 0.2)`.
- **Layout:** Horizontal overflow scroll without scrollbars; items maintain touch targets of at least 44px height.

### Dietary & Allergen Badges
- **Style:** Compact, micro-capsule tags (`label-sm`).
- **Variants:**
  - *Vegan / Vegetarian:* Tinted olive wash (`#F0F4EE`), text `#5F6F52`.
  - *Chef Highlight / Seasonal:* Tinted terracotta wash (`#FAF0ED`), text `#C86D51`.
  - *Allergen Warning (Gluten, Nuts):* Tinted neutral wash (`#F1F5F9`), text `#475569`.

### Interactive Buttons & Triggers
- **Primary (View Order / Call Waiter):** Background `#1E293B`, text `#FFFFFF`, height `48px`, border radius `0.75rem`, active pressed scale down to `0.98`.
- **Secondary / Filter Action:** Background `#FFFFFF`, border `1px solid #E2E8F0`, text `#1E293B`.

### Search & Preference Input
- **Container:** Height `44px`, background `#F8FAFC`, border `1px solid #E2E8F0`, inner padding `0 1rem`.
- **Focus State:** Border transitions cleanly to `#1E293B` with zero outer ring glow.