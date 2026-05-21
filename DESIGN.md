---
name: Lagosian Elegance
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f4'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#44474e'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#75777f'
  outline-variant: '#c5c6cf'
  surface-tint: '#4d5e83'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#061a3c'
  on-primary-container: '#7384ab'
  inverse-primary: '#b5c6f1'
  secondary: '#745a3a'
  on-secondary: '#ffffff'
  secondary-container: '#fedab1'
  on-secondary-container: '#785e3e'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#191c1d'
  on-tertiary-container: '#828485'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#b5c6f1'
  on-primary-fixed: '#061a3c'
  on-primary-fixed-variant: '#36466a'
  secondary-fixed: '#ffddb7'
  secondary-fixed-dim: '#e3c19a'
  on-secondary-fixed: '#2a1801'
  on-secondary-fixed-variant: '#5a4225'
  tertiary-fixed: '#e1e3e4'
  tertiary-fixed-dim: '#c5c7c8'
  on-tertiary-fixed: '#191c1d'
  on-tertiary-fixed-variant: '#454748'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  section-padding-desktop: 120px
  section-padding-mobile: 64px
  gutter: 24px
  margin-desktop: 80px
  container-max: 1280px
---

## Brand & Style

The design system is rooted in the "Lagosian Elegance" philosophy—a blend of classic hospitality and contemporary luxury. It targets a sophisticated clientele, evoking feelings of exclusivity, refined taste, and serenity.

The visual style is **High-Contrast Minimalism**. It relies on expansive white space to denote premium quality, paired with authoritative navy and metallic bronze accents. The interface uses high-quality editorial typography and subtle depth to guide the user through a curated digital experience that mirrors a high-end physical lounge.

## Colors

The palette is anchored by **Pure White (#FFFFFF)** to ensure a clean, airy aesthetic. **Deep Navy (#05193B)** provides structural weight, used for primary headings, navigation bars, and high-impact section backgrounds. 

**Refined Bronze (#A38562)** serves as the primary action color, used for secondary buttons, icons, and focus states, adding a layer of warmth and luxury. Neutral grays are used sparingly for secondary body text to maintain high legibility without distracting from the brand colors.

## Typography

This design system utilizes a high-contrast typographic pairing. **Playfair Display** is used for all headlines and display text, providing an editorial, "Storybook" feel that aligns with the brand's name.

**Plus Jakarta Sans** is used for all functional text, including body copy, labels, and navigation items. Its modern, rounded geometry balances the traditional feel of the serif headings. Letter spacing is increased for labels and small caps to enhance the "luxury boutique" aesthetic.

## Layout & Spacing

The layout follows a **Fixed Grid** model for desktop, centering content within a 1280px container to maintain focus. We utilize an 8px base unit for all internal component spacing (padding, gaps).

Generous vertical "breathing room" is mandatory; section padding should never drop below 120px on desktop to maintain the premium feel. On mobile, the system transitions to a fluid single-column layout with 20px side margins. Alternating background colors (White to Navy) are used to visually separate content narratives rather than using divider lines.

## Elevation & Depth

To maintain the clean, light-themed aesthetic, this design system avoids heavy drop shadows. Instead, it utilizes:

1.  **Tonal Layering:** Deep Navy sections sit "behind" White cards to create natural depth.
2.  **Soft Ambient Glows:** For interactive elements like "Book a Table" or featured cards, use a very faint, highly diffused bronze-tinted shadow (0px 10px 30px rgba(163, 133, 98, 0.08)).
3.  **Refined Outlines:** Secondary UI elements use 1px solid Bronze or light Navy borders to define boundaries without adding visual weight.

## Shapes

The design system adopts a **Rounded** shape language, specifically utilizing an 8px (0.5rem) corner radius for most containers, buttons, and input fields. This radius strikes a balance between the sharp precision of luxury and the approachability of modern service.

Large image containers and feature cards may use `rounded-lg` (16px) to emphasize their role as focal points within the layout.

## Components

### Buttons
- **Primary:** Deep Navy background with White text. Bold, uppercase labels.
- **Secondary:** Transparent background with Bronze 1px border and Bronze text.
- **Tertiary/Ghost:** Pure text with a 1px Bronze underline on hover.

### Cards
Cards should have a White background, the 8px corner radius, and a very subtle 1px border (#E2E8F0) rather than a shadow. Use generous internal padding (32px).

### Input Fields
Fields use a subtle off-white background (#F8F9FA) with an 8px radius. The focus state replaces the border with a 1px Bronze stroke.

### Chips & Tags
Used for "Chef's Selection" or "VIP Enclave." These should be small, uppercase, using the Bronze color for text with a 10% opacity Bronze background.

### Navigation
The header is sticky with a blurred backdrop. Links use Plus Jakarta Sans in Navy, with a subtle Bronze dot appearing below the active page link.