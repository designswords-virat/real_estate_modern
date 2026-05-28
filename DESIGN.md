---
name: Aethel
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1b1b1c'
  surface-container: '#202020'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353535'
  on-surface: '#e5e2e1'
  on-surface-variant: '#c4c7c7'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#303030'
  outline: '#8e9192'
  outline-variant: '#444748'
  surface-tint: '#c9c6c5'
  primary: '#c9c6c5'
  on-primary: '#313030'
  primary-container: '#0d0d0d'
  on-primary-container: '#7c7a7a'
  inverse-primary: '#5f5e5e'
  secondary: '#c6c6c7'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b4b5b5'
  tertiary: '#e2c195'
  on-tertiary: '#402d0c'
  tertiary-container: '#150b00'
  on-tertiary-container: '#91764f'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c9c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#ffddb0'
  tertiary-fixed-dim: '#e2c195'
  on-tertiary-fixed: '#281800'
  on-tertiary-fixed-variant: '#594320'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353535'
typography:
  display-xl:
    fontFamily: Clash Display
    fontSize: 80px
    fontWeight: '600'
    lineHeight: 88px
    letterSpacing: -0.02em
  display-lg:
    fontFamily: Clash Display
    fontSize: 64px
    fontWeight: '600'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Clash Display
    fontSize: 48px
    fontWeight: '500'
    lineHeight: 56px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Clash Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  headline-sm:
    fontFamily: Clash Display
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  headline-lg-mobile:
    fontFamily: Clash Display
    fontSize: 36px
    fontWeight: '500'
    lineHeight: 44px
  display-lg-mobile:
    fontFamily: Clash Display
    fontSize: 42px
    fontWeight: '600'
    lineHeight: 48px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  gutter-desktop: 32px
  margin-desktop: 80px
  gutter-mobile: 16px
  margin-mobile: 20px
  max-width: 1440px
---

## Brand & Style
The design system is engineered for a premium architectural and real estate audience. It bridges the gap between high-end editorial print and futuristic digital interfaces. The visual narrative centers on **Minimalism** with a **Glassmorphic** overlay, evoking a sense of structural integrity and transparency.

The UI should feel like a physical space—airy, intentional, and high-fidelity. By utilizing a "Dark-First" luxury aesthetic, the system emphasizes property photography and architectural renders as the primary focal points. The emotional response is one of quiet confidence, technological sophistication, and timeless luxury.

## Colors
This design system utilizes a high-contrast palette to establish depth and hierarchy.
- **Matte Black (#0D0D0D):** The foundational canvas, providing a deep, infinite background that makes imagery pop.
- **Soft White (#F5F5F5):** Reserved for primary typography and essential UI elements to ensure peak legibility.
- **Graphite Gray (#1E1E1E):** Used for structural containers, secondary surfaces, and subtle separation.
- **Warm Beige Accent (#C8A97E):** A sophisticated metallic-inspired tone used sparingly for calls-to-action, highlights, and premium signifiers.

## Typography
The typography strategy is editorial and authoritative. **Clash Display** provides a distinctive, geometric character for headings, utilizing tight letter-spacing for a modern architectural feel. **Manrope** serves as the functional workhorse, providing exceptional clarity for data-rich real estate listings and long-form architectural descriptions. 

Uppercase labels with slight tracking are used for metadata and categorization to maintain a structured, organized appearance.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy on desktop to mimic the structured columns of an architectural blueprint. 
- **Desktop:** 12-column grid with generous 80px margins to allow the content to breathe. 
- **Tablet:** 8-column grid with 40px margins.
- **Mobile:** 4-column fluid grid.

Spacing follows an 8px linear scale. Large whitespace "voids" are encouraged to separate distinct sections, reflecting the open-plan nature of modern architecture. Elements should be aligned to the grid but can occasionally break the margin for "Full-Bleed" hero imagery.

## Elevation & Depth
Depth is created through **Glassmorphism** and **Tonal Layering** rather than traditional heavy shadows.
- **Level 1 (Base):** Matte Black (#0D0D0D).
- **Level 2 (Cards/Surface):** Graphite Gray (#1E1E1E) with a subtle 1px border at 10% opacity Soft White.
- **Level 3 (Overlays/Modals):** A semi-transparent blur (Backdrop Filter: blur(20px)) using the Soft White at 5% opacity.

Shadows are "Ambient"—extremely diffused (0px 20px 40px), low-opacity black, creating a subtle lift that suggests the UI is floating over a dark void.

## Shapes
Shapes are geometric but softened. A `rounded-md` (0.5rem) base is used for most interactive elements to balance the "harshness" of the dark theme. Larger containers like property cards or hero sections use `rounded-xl` (1.5rem) to evoke a premium, custom-molded feel. 

Interactive indicators, such as status chips or page pagination, may use pill shapes to contrast against the predominantly rectangular grid.

## Components
- **Buttons:** Primary buttons are Solid Soft White with Matte Black text. Secondary buttons are outlined with a 1px Soft White border. The hover state for all buttons includes a subtle scale-up (1.02x) and a soft glow.
- **Input Fields:** Minimalist design—bottom border only in default state, transitioning to a full Graphite Gray container with a Warm Beige focus ring.
- **Cards:** Property cards use a "Floating Info" layout. The image occupies the full card area, with text details housed in a glassmorphic footer overlaying the bottom 30% of the image.
- **Lists:** Clean, horizontal dividers (1px Graphite Gray). Hovering over a list item triggers a subtle background color shift to #1E1E1E.
- **Architectural Specs:** A custom component for property data (sq ft, beds, baths) using the `label-md` typography style paired with thin, custom SVG icons in Warm Beige.
- **Navigation:** A persistent, frosted-glass header with minimal links and a high-contrast CTA for "Book a Tour" or "Contact Studio."