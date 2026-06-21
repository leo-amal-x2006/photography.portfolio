---
name: Lumina & Earth
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0edec'
  surface-container-high: '#ebe7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#424843'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#737973'
  outline-variant: '#c2c8c2'
  surface-tint: '#4d6355'
  primary: '#051a0f'
  on-primary: '#ffffff'
  primary-container: '#1a2f23'
  on-primary-container: '#809787'
  inverse-primary: '#b4ccbb'
  secondary: '#904d03'
  on-secondary: '#ffffff'
  secondary-container: '#ffa85c'
  on-secondary-container: '#743d00'
  tertiary: '#171713'
  on-tertiary: '#ffffff'
  tertiary-container: '#2b2b27'
  on-tertiary-container: '#94928c'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d0e9d6'
  primary-fixed-dim: '#b4ccbb'
  on-primary-fixed: '#0a2014'
  on-primary-fixed-variant: '#364c3e'
  secondary-fixed: '#ffdcc3'
  secondary-fixed-dim: '#ffb77d'
  on-secondary-fixed: '#2f1500'
  on-secondary-fixed-variant: '#6e3900'
  tertiary-fixed: '#e5e2db'
  tertiary-fixed-dim: '#c9c6c0'
  on-tertiary-fixed: '#1c1c18'
  on-tertiary-fixed-variant: '#474742'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '600'
    lineHeight: '1.2'
  body-lg:
    fontFamily: DM Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: DM Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: DM Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.1em
spacing:
  container-max: 1440px
  gutter: 32px
  margin-desktop: 80px
  margin-tablet: 40px
  margin-mobile: 20px
  section-gap: 120px
---

## Brand & Style

The brand personality is artistic, contemplative, and premium. It targets high-end editorial clients, art collectors, and lifestyle brands who value storytelling and a refined aesthetic. The UI should evoke a sense of calm and "slow living," acting as a silent gallery frame for the photography.

The design style is a blend of **Minimalism** and **Tactile Modernism**. It prioritizes heavy whitespace to let images breathe, while using sophisticated typography and a nature-inspired palette to create an immersive, high-end editorial experience. Decorative elements are used sparingly, appearing as thin hair lines or subtle organic textures that mimic the grain of fine-art paper.

## Colors

The palette is rooted in the "Golden Hour" and the natural world. 

- **Primary (Deep Forest):** Used for primary headings and significant UI accents to provide a grounded, organic feel.
- **Secondary (Golden Ember):** Reserved for interactive highlights, call-to-actions, and subtle decorative rules. It represents the warmth of the setting sun.
- **Tertiary (Parchment):** A warm, off-white background color that reduces the harshness of pure white and evokes a physical gallery wall.
- **Neutral (Obsidian):** Used for body text and critical UI elements to ensure high legibility and a professional finish.

Avoid pure blacks or pure whites to maintain the "filmic" and organic quality of the design system.

## Typography

The typography strategy relies on the contrast between a sophisticated Serif and a functional, modern Sans-Serif.

**Playfair Display** is used for headlines to convey luxury and editorial authority. It should be typeset with tight letter-spacing in larger sizes to maximize its dramatic, high-contrast strokes.

**DM Sans** provides a neutral, highly readable counterpoint for body copy and metadata. Its low-contrast, geometric forms ensure the UI feels contemporary and does not compete with the ornate details of the serif headings. 

For labels and technical metadata (ISO, Shutter speed), use small-caps with generous letter spacing to evoke the look of a printed photography book.

## Layout & Spacing

The layout follows a **Fluid Grid** model with generous margins to create an "immersive gallery" feel. On desktop, the 12-column grid uses wide 32px gutters to separate imagery and text cleanly.

**Horizontal Spacing:** Margins are intentionally wide (80px on desktop) to push content toward the center, creating a focal point.
**Vertical Spacing:** Use large section gaps (120px+) to separate different photographic series or chapters. This forced "pause" encourages the user to linger on individual images.

**Adaptability:**
- **Desktop:** Multi-column masonry or asymmetrical layouts for photo grids.
- **Tablet:** Shift to 8-column grid; reduce section gaps to 80px.
- **Mobile:** Single column stack; margins reduced to 20px. Images should transition to edge-to-edge (bleed) to maximize impact on small screens.

## Elevation & Depth

This design system avoids traditional drop shadows to maintain a flat, editorial aesthetic. Depth is instead achieved through:

1.  **Tonal Layering:** Using slightly different shades of the Tertiary (Parchment) color to define "Container" vs "Surface" areas.
2.  **Low-Contrast Outlines:** Subtle 1px borders in a darkened version of the background color (e.g., #E8E4D8) are used to define image frames or input fields without adding visual weight.
3.  **Overlapping Elements:** Floating a small caption or label slightly over the edge of a photograph to create a physical, layered paper effect.
4.  **Backdrop Blurs:** When overlays or menus appear, a very light blur (4px) is applied to the background to maintain focus while keeping the presence of the photography underneath.

## Shapes

The shape language is strictly **Sharp (0)**. 

All image containers, buttons, and UI modules use 90-degree corners. This evokes the precision of a camera sensor and the classic edges of a printed photograph or a traditional mat board. Sharp corners reinforce the professional, serious, and architectural nature of the portfolio. Avoid any rounded corners, even in small UI elements like chips or checkboxes.

## Components

- **Buttons:** Primary buttons are solid Obsidian with Parchment text. They are wide with ample internal padding. Secondary buttons are Ghost-style with a thin 1px primary border and no fill.
- **Image Cards:** No borders or shadows. Titles and metadata appear on hover or are positioned asymmetrically below the image using the `label-sm` style.
- **Navigation:** Minimalist top bar. Links use the `label-sm` style. Active states are indicated by a subtle Golden Ember underline.
- **Input Fields:** Bottom-border only (underlined style) to mimic signature lines on a print. Labels use the `label-sm` style and sit above the line.
- **Chips/Tags:** Sharp rectangular boxes with a very light tint of the Primary color as a background and Primary color text.
- **Image Viewer (Lightbox):** Full-screen Obsidian background with 90% opacity. Navigation arrows are thin 1px icons.
- **Lists:** Clean, hair-line separators (#E8E4D8) between items. Use Serif for list item titles to maintain the editorial feel.