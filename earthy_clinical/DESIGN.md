---
name: Earthy Clinical
colors:
  surface: '#f9f9fa'
  surface-dim: '#dadadb'
  surface-bright: '#f9f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f4'
  surface-container: '#eeeeef'
  surface-container-high: '#e8e8e9'
  surface-container-highest: '#e2e2e3'
  on-surface: '#1a1c1d'
  on-surface-variant: '#434843'
  inverse-surface: '#2f3132'
  inverse-on-surface: '#f0f1f1'
  outline: '#737872'
  outline-variant: '#c3c8c1'
  surface-tint: '#4f6353'
  primary: '#425646'
  on-primary: '#ffffff'
  primary-container: '#5a6e5d'
  on-primary-container: '#d9f0da'
  inverse-primary: '#b6ccb8'
  secondary: '#5e5e5b'
  on-secondary: '#ffffff'
  secondary-container: '#e1dfdb'
  on-secondary-container: '#63635f'
  tertiary: '#4d534a'
  on-tertiary: '#ffffff'
  tertiary-container: '#656b61'
  on-tertiary-container: '#e7ecdf'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d2e8d3'
  primary-fixed-dim: '#b6ccb8'
  on-primary-fixed: '#0d1f12'
  on-primary-fixed-variant: '#384b3c'
  secondary-fixed: '#e4e2dd'
  secondary-fixed-dim: '#c8c6c2'
  on-secondary-fixed: '#1b1c19'
  on-secondary-fixed-variant: '#474744'
  tertiary-fixed: '#dfe4d8'
  tertiary-fixed-dim: '#c3c8bd'
  on-tertiary-fixed: '#181d16'
  on-tertiary-fixed-variant: '#43483f'
  background: '#f9f9fa'
  on-background: '#1a1c1d'
  surface-variant: '#e2e2e3'
  clinical-sage: '#7A8C7E'
  warm-cream: '#FDFBF7'
  deep-charcoal: '#1A1C1D'
  soft-linen: '#ECE9E4'
  success-green: '#4A6B53'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Open Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Open Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Open Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  caption:
    fontFamily: Open Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: '1.4'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 24px
  margin-x: 32px
  section-gap: 120px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

This design system establishes a sophisticated, "earthy yet clinical" aesthetic for a premium naturopathic practice. It avoids the typical clichés of alternative medicine by prioritizing high-end professionalism and evidence-based authority, while maintaining an empathetic, approachable heart.

The style is a blend of **Minimalism** and **Modern Corporate**, utilizing generous whitespace and a structured grid to convey medical precision. This is softened by a organic color palette and high-quality, bright photography that bridges the gap between the laboratory and the natural world. The emotional response should be one of immediate relief, clarity, and trust.

## Colors

The palette is grounded in "Clinical Sage" and "Warm Cream" to evoke a sense of calm and organic growth without sacrificing the cleanliness expected of a medical professional.

- **Primary (Sage):** Used for primary actions, iconography, and subtle background sections. It represents health and vitality.
- **Secondary (Cream):** The foundational background color. It provides a warmer, more inviting alternative to pure white, reducing eye strain and feeling more "human."
- **Tertiary (Muted Olive):** Used for decorative elements, borders, and secondary surfaces.
- **Neutral (Charcoal):** Used strictly for high-readability typography and deep structural elements. Never use pure black (#000000) to keep the look sophisticated and soft.

## Typography

The typographic strategy pairs the authoritative, timeless elegance of a serif with the functional clarity of a humanist sans-serif.

- **Headlines:** Playfair Display conveys the doctor’s expertise and traditional medical heritage. Use high-contrast weights for section headers to create a rhythmic flow.
- **Body:** Open Sans is selected for its exceptional legibility in long-form medical explanations. It remains neutral and professional, allowing the content to lead.
- **Labels:** Uppercase styling with slight tracking (letter-spacing) is used for small navigation items and "Areas of Focus" badges to provide a modern, organized feel.

## Layout & Spacing

The design system utilizes a **Fixed Grid** model for desktop to ensure content remains readable and elegantly framed. 

- **Grid:** A 12-column grid with 24px gutters.
- **Vertical Rhythm:** A "Section-Gap" of 120px is used between major content blocks to provide the "breathing room" necessary for a calming user experience.
- **Mobile Adaptivity:** On mobile devices, margins reduce to 20px, and the 120px gaps scale down to 64px. Content reflows into a single column, with carousels utilized for "Services" to maintain a compact vertical footprint.

## Elevation & Depth

This system avoids heavy drop shadows in favor of **Tonal Layering** and **Low-Contrast Outlines**.

- **Surfaces:** Depth is created by placing "Warm Cream" cards on "Soft Linen" backgrounds. 
- **Outlines:** Use 1px solid borders in a color slightly darker than the surface (e.g., Clinical Sage at 20% opacity) to define boundaries without adding visual weight.
- **Glassmorphism:** Reserved exclusively for the header navigation bar—a subtle backdrop blur (8px) with a semi-transparent Cream fill allows the photography to peek through as the user scrolls, maintaining a sense of light and air.

## Shapes

The shape language is **Soft**. Sharp 90-degree corners are avoided to ensure the UI feels approachable and organic, while large "pill" shapes are avoided to maintain professional clinical rigor. 

Standard components (Cards, Inputs) use a 0.25rem radius. Buttons and decorative "Focus Area" icons use a slightly more pronounced 0.5rem radius to stand out as interactive or highlighted elements.

## Components

- **Buttons:** Primary buttons are solid "Clinical Sage" with white "Open Sans" bold text. Secondary buttons use a "Deep Charcoal" outline with no fill.
- **Cards:** Cards should have no shadow; instead, use a 1px "Soft Linen" border and a "Warm Cream" background. Padding should be generous (32px) to reinforce the premium feel.
- **Input Fields:** Minimalist design. A bottom-border only approach (1px Charcoal) with labels that sit above the field in "Label-MD" typography.
- **Chips/Badges:** Used for medical tags or categories. Small, "Soft Linen" backgrounds with "Deep Charcoal" text, utilizing the 0.5rem roundedness.
- **Accordions (FAQs):** Simple text-based dividers. The "plus" and "minus" icons should be thin (1px) and rendered in Sage.
- **Service Carousel:** Use a progress indicator (e.g., "1/6") in "Caption" styling below the component, with simple arrow icons for navigation.