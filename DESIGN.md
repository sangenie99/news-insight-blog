---
name: Modern Editorial
colors:
  surface: '#f8f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f8f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#454652'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#767683'
  outline-variant: '#c6c5d4'
  surface-tint: '#4c56af'
  primary: '#000666'
  on-primary: '#ffffff'
  primary-container: '#1a237e'
  on-primary-container: '#8690ee'
  inverse-primary: '#bdc2ff'
  secondary: '#0061a4'
  on-secondary: '#ffffff'
  secondary-container: '#33a0fd'
  on-secondary-container: '#00355c'
  tertiary: '#380b00'
  on-tertiary: '#ffffff'
  tertiary-container: '#5c1800'
  on-tertiary-container: '#e17c5a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e0e0ff'
  primary-fixed-dim: '#bdc2ff'
  on-primary-fixed: '#000767'
  on-primary-fixed-variant: '#343d96'
  secondary-fixed: '#d1e4ff'
  secondary-fixed-dim: '#9ecaff'
  on-secondary-fixed: '#001d36'
  on-secondary-fixed-variant: '#00497d'
  tertiary-fixed: '#ffdbd0'
  tertiary-fixed-dim: '#ffb59d'
  on-tertiary-fixed: '#390c00'
  on-tertiary-fixed-variant: '#7b2e12'
  background: '#f8f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-lg:
    fontFamily: Newsreader
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Newsreader
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 36px
  headline-lg-mobile:
    fontFamily: Newsreader
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 30px
  headline-md:
    fontFamily: Newsreader
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Public Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Public Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-lg:
    fontFamily: Public Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-md:
    fontFamily: Public Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  baseline: 8px
  container-margin: 20px
  gutter: 16px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
  section-padding: 40px
---

## Brand & Style
The design system is anchored in the principles of **Minimalism** and **Corporate Modernism**, tailored specifically for the high-density information environment of a news blog. The objective is to establish immediate authority and trust through intentional restraint. 

The aesthetic evokes the feeling of a premium physical newspaper translated into a digital-first experience. By utilizing generous whitespace and a limited color palette, the system ensures that the editorial content remains the focal point. The emotional response should be one of calm focus, reliability, and intellectual clarity, avoiding the "clutter" typically associated with ad-heavy news platforms.

## Colors
This design system utilizes a high-contrast palette to maintain professional gravity. 

- **Primary (Deep Navy):** Used exclusively for headings, primary branding, and high-level navigation to provide a "weighted" feel to the information hierarchy.
- **Secondary (Accent Blue):** Reserved for interactive elements, such as text links, active states, and primary Call-to-Action (CTA) buttons.
- **Neutral/Surface:** A very light gray (#F5F7F9) is used for card backgrounds and section dividers to subtly separate content without breaking the minimalist flow.
- **Background:** Pure white is used for the main reading canvas to maximize legibility and ensure a fast-loading, clean appearance.

## Typography
Typography is the cornerstone of the design system. It uses a "Hybrid Editorial" approach:

- **Headlines (Newsreader):** A sophisticated Serif that provides the authoritative "voice" of the publication. It features slightly condensed proportions and high legibility at various sizes.
- **Body & UI (Public Sans):** An institutional Sans-Serif designed for clarity. It is used for long-form reading and interface elements to ensure the app feels modern and functional.
- **Scale:** On mobile, article titles (Headline-LG) are reduced to 24px to prevent excessive line breaks while maintaining visual impact. Label styles use increased letter spacing and uppercase styling for category tags to distinguish them from editorial copy.

## Layout & Spacing
The layout follows a **Fluid Grid** model optimized for a single-column mobile view. 

The spacing rhythm is generous, utilizing a base-8 unit. A standard container margin of 20px ensures that text does not feel cramped against the edges of the device screen. 
- **Vertical Rhythm:** Use `stack-lg` (32px) between major news sections and `stack-md` (16px) between individual news cards.
- **Reading Comfort:** Article pages utilize a narrower text container or wider horizontal margins (24px) to keep line lengths optimal for reading.

## Elevation & Depth
To maintain a fast-loading and "flat" journalistic aesthetic, depth is conveyed through **Tonal Layers** rather than heavy shadows.

- **Level 0 (Background):** Pure White (#FFFFFF).
- **Level 1 (Cards):** Use a subtle 1px border (#E0E4E8) or a light neutral fill (#F5F7F9) to define news items.
- **Level 2 (Navigation/Floating):** Use a very soft, ambient shadow (0px 4px 12px, 5% opacity Deep Navy) for the bottom navigation bar or floating action buttons to signify they sit above the scrollable content.
- **Dividers:** Use hairline 1px dividers for list items to maintain a structured, grid-like feel without adding visual weight.

## Shapes
The design system uses a **Soft** shape language. 

A corner radius of 4px (`rounded`) is applied to cards and input fields to soften the professional tone without appearing too casual or "bubbly." 
- **Buttons:** Use 4px rounded corners to maintain consistency.
- **Category Chips:** May use a higher roundedness (up to 16px) to distinguish them as interactive metadata tags rather than structural content.

## Components
Consistent component execution ensures the design system remains cohesive:

- **News Cards:** Minimalist containers. Image at the top or left-aligned thumbnail, followed by a category label (Accent Blue), Headline (Deep Navy), and a "Time ago" timestamp in a muted neutral.
- **Category Chips:** Small, low-contrast pills. Light gray background with Deep Navy text for inactive states; Accent Blue background with white text for active/selected states.
- **Buttons:**
    - *Primary:* Solid Deep Navy background, white text, 4px radius.
    - *Secondary/Text:* Accent Blue text, no background, used for "Read More" or "View All" links.
- **Input Fields:** Clean, bottom-border only or light-bordered boxes. Focus state uses a 2px Accent Blue bottom border.
- **Lists:** Clean rows separated by hairline dividers, with Newsreader used for the list item titles.
- **Progress Indicators:** A thin Accent Blue line at the top of the article view to indicate reading progress, reinforcing the "fast-loading" and technical precision of the app.