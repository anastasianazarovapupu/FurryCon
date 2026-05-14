---
name: Kawaii-Core Fest
colors:
  surface: '#fff8f7'
  surface-dim: '#f3d2d2'
  surface-bright: '#fff8f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff0ef'
  surface-container: '#ffe9e8'
  surface-container-high: '#ffe1e0'
  surface-container-highest: '#fcdbda'
  on-surface: '#281717'
  on-surface-variant: '#5d3f3d'
  inverse-surface: '#3f2b2b'
  inverse-on-surface: '#ffedec'
  outline: '#926e6c'
  outline-variant: '#e7bdb9'
  surface-tint: '#c0001e'
  primary: '#bb001d'
  on-primary: '#ffffff'
  primary-container: '#e51c2d'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb3ae'
  secondary: '#92407e'
  on-secondary: '#ffffff'
  secondary-container: '#fd9ce0'
  on-secondary-container: '#7b2c69'
  tertiary: '#006672'
  on-tertiary: '#ffffff'
  tertiary-container: '#008190'
  on-tertiary-container: '#f7feff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad7'
  primary-fixed-dim: '#ffb3ae'
  on-primary-fixed: '#410004'
  on-primary-fixed-variant: '#930014'
  secondary-fixed: '#ffd7ef'
  secondary-fixed-dim: '#ffade5'
  on-secondary-fixed: '#3a0031'
  on-secondary-fixed-variant: '#752864'
  tertiary-fixed: '#9defff'
  tertiary-fixed-dim: '#4fd8ed'
  on-tertiary-fixed: '#001f24'
  on-tertiary-fixed-variant: '#004f59'
  background: '#fff8f7'
  on-background: '#281717'
  surface-variant: '#fcdbda'
  neon-lime: '#C4FF4D'
  soft-lilac: '#E6D5FF'
  peach-fuzz: '#FFD6C2'
  surface-white: '#FFFFFF'
typography:
  display-lg:
    fontFamily: Bricolage Grotesque
    fontSize: 72px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Bricolage Grotesque
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Bricolage Grotesque
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Bricolage Grotesque
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '500'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-bold:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1'
  caption:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.4'
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  base: 8px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  container-max: 1280px
---

## Brand & Style

The design system is built to evoke the high-energy, inclusive, and vibrant atmosphere of an Asian subculture festival. The brand personality is unapologetically enthusiastic, welcoming, and "hyper-cute." It targets a youth-centric demographic that values self-expression, safety, and community.

The visual style is a blend of **Glassmorphism** and **Tactile** design. It utilizes "squishy" UI elements—large radii, soft shadows, and semi-translucent layers—to mimic a physical, plush-like quality. The aesthetic is "Fuzzy-Digital," where modern tech interfaces meet the soft, tactile nature of the furry community. High-energy motion, bouncing transitions, and overlapping organic shapes define the interactive experience.

## Colors

The palette transforms the aggressive red of the reference material into a primary "Pulse Red" used for calls to action, balanced by a secondary "Cotton Candy Pink" and tertiary "Cyber Sky Blue." The system relies on a high-contrast relationship between deep chocolate-brown neutrals (replacing pure blacks) and vibrant neon accents.

The background strategy utilizes "Pastel Rainbow" gradients—extremely soft, low-opacity transitions between lilac, peach, and blue—to ensure the interface feels airy and safe. Use the `neon-lime` sparingly for status indicators or high-priority "New" tags to maintain the energetic subculture vibe.

## Typography

This design system uses **Bricolage Grotesque** for headlines to leverage its quirky, expressive letterforms which echo the "organic" and "fuzzy" theme. Its variable nature allows for tight, impactful display text that feels custom-made for a festival. 

For readability and a contemporary feel, **Plus Jakarta Sans** is used for all functional text. Its soft, rounded terminals complement the headline font while maintaining high legibility for schedules and informational content. Headlines should occasionally use "Squish-Stretch" animations on hover to emphasize the playful nature of the brand.

## Layout & Spacing

The layout follows a **Fluid Grid** model with a heavy emphasis on "Organic Overlap." Elements should not always be strictly confined to their columns; floating decorative elements (like "furry" badges or mascot paws) can break the grid to create depth.

Spacing follows an 8px rhythmic scale. Use generous internal padding in containers (minimum 32px) to give the UI a "breathable" and spacious feel. Mobile layouts should utilize a single-column stack with full-width cards, while desktop layouts use a 12-column grid with asymmetric offsets to mimic the chaotic energy of a street festival.

## Elevation & Depth

Depth is achieved through **Tonal Volumetric Layers** and **Faux-Fur Textures**. 
- **Surface Level:** The base background is a soft, semi-opaque pastel gradient.
- **Mid Level (Cards):** Use `surface-white` with a 0.05 opacity "grain/fur" SVG pattern overlay. Borders are thick (2px) but low-contrast (using a darker shade of the background color).
- **High Level (Pop-ups/Buttons):** These use **Ambient Shadows**. Shadows are not black; they are tinted with the `secondary` or `tertiary` color (e.g., a soft pink shadow) with a high blur radius (20px+) and low opacity (15%) to make elements appear as if they are floating on a cloud.

Avoid sharp dropshadows. Use backdrop blurs (10px - 20px) on navigation bars and floating chips to maintain the glassmorphic aesthetic.

## Shapes

The shape language is strictly **Pill-shaped** and hyper-rounded. There are no sharp corners in this design system. 

Beyond standard containers, use "Blob" shapes for background decorations and image masks. These blobs should have slightly irregular, hand-drawn qualities. Buttons and input fields must use maximum rounding (stadium shape) to reinforce the "soft and safe" tactile feel.

## Components

### Buttons
Primary buttons are "Chunky." They feature a 2px solid border of a darker shade of the button color and a "press" effect where the button physically shifts 2px down and right, simulating a mechanical squish.

### Chips & Tags
Used for subculture categories (e.g., "Cosplay," "Art-Track"). Chips should use the `named_colors` palette with high-saturation backgrounds and dark brown text. Use a "fuzzy" icon prefix (like a small paw print or tail) where appropriate.

### Cards
Cards are the primary content container. They must feature `rounded-xl` corners and the subtle faux-fur background pattern. Interaction with a card (hover) should cause it to scale up slightly (1.02x) and increase the intensity of its tinted ambient shadow.

### Input Fields
Fields should be oversized with a 2px border that changes from neutral to `secondary_color` on focus. Use "Plus Jakarta Sans" for placeholders to keep the interface friendly.

### Furry Accents
Include "Ear" or "Tail" decorative components that can be programmatically attached to the corners of cards or modal windows to lean into the theme without obstructing content.