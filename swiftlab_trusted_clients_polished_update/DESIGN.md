---
name: Swiftlab
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1b1b1b'
  surface-container: '#1f1f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353535'
  on-surface: '#e2e2e2'
  on-surface-variant: '#e3beb8'
  inverse-surface: '#e2e2e2'
  inverse-on-surface: '#303030'
  outline: '#aa8983'
  outline-variant: '#5a403c'
  surface-tint: '#ffb4a6'
  primary: '#ffb4a6'
  on-primary: '#660700'
  primary-container: '#fb593f'
  on-primary-container: '#5a0500'
  inverse-primary: '#b52613'
  secondary: '#c6c6c7'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b4b5b5'
  tertiary: '#68d5f1'
  on-tertiary: '#003641'
  tertiary-container: '#1d9eb9'
  on-tertiary-container: '#002e38'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad4'
  primary-fixed-dim: '#ffb4a6'
  on-primary-fixed: '#3f0300'
  on-primary-fixed-variant: '#900d00'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#afecff'
  tertiary-fixed-dim: '#68d5f1'
  on-tertiary-fixed: '#001f26'
  on-tertiary-fixed-variant: '#004e5d'
  background: '#131313'
  on-background: '#e2e2e2'
  surface-variant: '#353535'
typography:
  headline-xl:
    fontFamily: Geist
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.03em
  headline-lg-mobile:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Geist
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-md:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Geist
    fontSize: 11px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
  container-max-width: 1200px
---

## Brand & Style
The design system embodies a high-performance, developer-centric aesthetic inspired by the "dark mode" pioneers of modern enterprise SaaS. It projects an image of precision, speed, and technical sophistication. The target audience includes engineers, designers, and power users who value information density presented with clarity and refined elegance.

The style is a hybrid of **Minimalism** and **Glassmorphism**. It utilizes deep obsidian backgrounds, high-contrast typography, and surgically precise borders. Subtle gradients and translucent layers provide a sense of depth without compromising the "lean" feel required for complex workflows. The overall emotional response should be one of empowerment—user interfaces that feel like professional-grade tools.

## Colors
The palette is rooted in a "Void" philosophy. The base background is absolute black (#000000) to ensure perfect contrast on OLED displays and a premium "endless" depth. Secondary surfaces use a slightly lighter dark gray (#0a0a0a) to create structural hierarchy.

The primary accent is **Swift Orange** (#f05138), a high-energy hue used exclusively for high-impact actions and critical status indicators. Typography primarily utilizes pure white for headings and a muted zinc/gray for secondary information to reduce eye strain while maintaining a crisp hierarchy. Borders are consistently dark (#1f1f1f), acting as the primary tool for structural definition.

## Typography
The design system utilizes **Geist** for its entire type scale, capitalizing on its technical, minimal character and exceptional legibility at small sizes. The typographic hierarchy is aggressive; large headlines use tight tracking and heavy weights to create a sense of authority, while body text is spaced for optimal reading flow in data-heavy environments.

Labels and metadata should be rendered in smaller, medium-weight styles with slight letter-spacing increases to maintain clarity against the dark background. Monospaced numerals should be favored for data tables and metrics to ensure alignment.

## Layout & Spacing
A 12-column fluid grid system is the foundation for all views. The layout relies on a strict 4px/8px baseline grid to ensure mathematical harmony between elements. 

- **Desktop:** Elements are organized into modular cards or distinct sections separated by 24px gutters. Content is typically centered in a maximum 1200px container to prevent excessive line lengths.
- **Tablet:** Gutters remain at 24px, but side margins reduce to 24px.
- **Mobile:** The layout reflows to a single column with 16px margins. 

The philosophy is "density with air"—packing information tightly within components but providing generous margins between major sections to prevent visual clutter.

## Elevation & Depth
Depth is achieved through a combination of **Tonal Layering** and **Glassmorphism**. Unlike light-themed systems that use heavy shadows, this design system uses luminosity and borders to signify elevation:

1.  **Level 0 (Base):** Pure Black (#000000).
2.  **Level 1 (Cards/Containers):** Deep Gray (#0a0a0a) with a 1px solid border (#1f1f1f).
3.  **Level 2 (Modals/Popovers):** Translucent background (80% opacity) with a `backdrop-filter: blur(12px)` and a slightly brighter border (#2e2e2e).

Soft, low-opacity glows (using the accent color at 5-10% opacity) may be used behind primary CTAs to create a "halo" effect, suggesting the element is emitting light rather than casting a shadow.

## Shapes
The design system uses a "Soft" (0.25rem / 4px) corner radius as its default state. This subtle rounding maintains the professional, architectural feel of the UI while removing the harshness of 0px corners.

- **Standard Elements:** 4px (Buttons, Inputs, Small Cards).
- **Large Containers:** 8px (Main Content Areas, Dashboard Sections).
- **Interactive States:** On hover, certain elements may transition from 4px to 6px to provide tactile visual feedback.

## Components
- **Buttons:** Primary buttons use the Swift Orange background with white text. Secondary buttons are ghost-style with a 1px #1f1f1f border and a subtle hover state that brightens the border to #white.
- **Input Fields:** Dark backgrounds (#050505) with 1px borders. On focus, the border transitions to Swift Orange or white with a 2px outer glow.
- **Cards:** Defined by their #1f1f1f borders. For premium "featured" cards, use a subtle linear gradient border (top-left to bottom-right) that transitions from #333 to #111.
- **Chips/Badges:** Small, high-contrast capsules with subtle background tints derived from their status color (e.g., Success = Emerald text on 10% opacity Emerald background).
- **Lists:** Rows are separated by 1px horizontal lines (#1f1f1f). Hover states use a subtle gray shift (#0f0f0f) to indicate interactivity.
- **Navigation:** Sidebars and headers should use backdrop blurs when scrolling over content, maintaining the glassmorphic aesthetic.