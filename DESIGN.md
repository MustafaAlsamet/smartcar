---
name: Majestic Heritage Gold
colors:
  surface: '#fbf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fbf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae8e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#4e453a'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0f0'
  outline: '#807569'
  outline-variant: '#d1c5b6'
  surface-tint: '#775928'
  primary: '#775928'
  on-primary: '#ffffff'
  primary-container: '#b08d57'
  on-primary-container: '#3d2700'
  inverse-primary: '#e8c086'
  secondary: '#5f5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e2dfde'
  on-secondary-container: '#636262'
  tertiary: '#605e58'
  on-tertiary: '#ffffff'
  tertiary-container: '#95928b'
  on-tertiary-container: '#2c2b26'
  error: '#721C24'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdeae'
  primary-fixed-dim: '#e8c086'
  on-primary-fixed: '#281800'
  on-primary-fixed-variant: '#5d4213'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1b1b1b'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#e6e2da'
  tertiary-fixed-dim: '#c9c6bf'
  on-tertiary-fixed: '#1c1c17'
  on-tertiary-fixed-variant: '#484741'
  background: '#fbf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
  gold-hover: '#8C6D41'
  surface-dark: '#2A2A2A'
  surface-white: '#FFFFFF'
  border-light: '#E0E0E0'
  success: '#155724'
typography:
  headline-lg:
    fontFamily: Cairo
    fontSize: 44px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Cairo
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Cairo
    fontSize: 28px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Cairo
    fontSize: 22px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Cairo
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.7'
  body-md:
    fontFamily: Cairo
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  body-sm:
    fontFamily: Cairo
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.6'
  label-lg:
    fontFamily: Cairo
    fontSize: 20px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: 0.02em
  label-md:
    fontFamily: Cairo
    fontSize: 16px
    fontWeight: '600'
    lineHeight: '1.2'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1200px
  gutter: 25px
  margin-mobile: 20px
  section-gap: 40px
  form-gap: 20px
  unit-xs: 4px
  unit-sm: 8px
  unit-md: 16px
  unit-lg: 24px
  unit-xl: 32px
---

## Brand & Style

The design system is crafted to evoke a sense of **Premium Arabic Luxury**, blending high-end automotive aesthetics with cultural sophistication. The target audience includes high-net-worth residents, corporate professionals, and international tourists seeking prestige and reliability in the Sultanate of Oman.

The visual style is **Corporate / Modern** with a **Minimalist** foundation, utilizing heavy whitespace and a refined color palette to allow high-definition vehicle imagery to take center stage. The interface should feel expensive yet accessible, utilizing clean lines and subtle, purposeful animations that mimic the smooth acceleration of a luxury vehicle. The emotional response is one of absolute trust, exclusivity, and effortless service.

## Colors

The palette is anchored by **Gold 600**, representing excellence and the premium nature of the fleet. This is paired with **Rich Dark Grays** to provide a grounded, formal structure, and **Warm Beige** to move away from clinical whites toward a more "heritage luxury" feel.

- **Primary Gold:** Reserved for key actions, brand marks, and high-hierarchy headings.
- **Secondary Dark Gray:** Used for high-contrast surfaces like headers and footers to frame the content.
- **Tertiary Warm Beige:** The global background color, providing a soft, sophisticated canvas.
- **Neutral Dark:** The primary color for body text to ensure maximum readability against the light background.

## Typography

The design system exclusively uses **Cairo**, a typeface specifically designed for harmonizing Arabic and Latin scripts. Its geometric yet humanist qualities align perfectly with a modern luxury brand.

- **Headlines:** Use Bold weights for H1 and Semibold for H2/H3. The Gold color should be applied to primary section headers to establish hierarchy.
- **Body Text:** Maintained at a comfortable 16px (1.0em) for standard copy, increasing to 18px for detailed car descriptions to enhance the premium reading experience.
- **RTL Optimization:** Ensure line heights are generous (minimum 1.6) to accommodate the ascenders and descenders of Arabic script without crowding.

## Layout & Spacing

This design system employs a **Fixed Grid** layout for desktop (1200px max-width) to maintain a curated, editorial feel. The spacing follows a mathematical rhythm based on 8px increments, though specific "Luxury Gaps" of 25px and 30px are used to break the standard grid for a more custom appearance.

- **Grid:** 12-column grid with 25px gutters. 
- **Margins:** Desktop margins are flexible, while mobile margins are fixed at 20px to ensure content is safely inset.
- **Reflow:** On tablet, the 3-column car listings should reflow to 2-columns; on mobile, they transition to a single-column stack with horizontal image carousels.

## Elevation & Depth

Hierarchy is established through **Tonal Layers** and **Ambient Shadows**. Surfaces should feel physically present but understated.

- **Base Surfaces:** The page background is the lowest level. White containers (`#FFFFFF`) sit directly on top.
- **Shadow Profile:** Use a soft, diffused shadow for cards: `0 5px 15px rgba(0,0,0,0.08)`. This creates a subtle lift without the "heaviness" of traditional drop shadows.
- **Interactive Depth:** Upon hover, elements like Car Cards should increase their shadow spread and transition 5px upwards (`translateY`) to provide immediate tactile feedback.
- **Overlays:** Modals and booking summaries use a 20% dark backdrop blur to maintain focus on the transaction while keeping the car fleet visible in the background.

## Shapes

The shape language is **Rounded**, striking a balance between the precision of luxury machinery and the approachability of high-end hospitality.

- **Standard Radius (8px):** Applied to primary containers, car cards, and feature images.
- **Action Radius (5px):** Slightly sharper corners for buttons and input fields to imply functional precision and "tight" engineering.
- **Accents:** Use 3px solid Gold borders as top or bottom strokes on major sections (Header/Footer) to "bookend" the content with luxury markers.

## Components

### Buttons
- **Primary:** Solid Gold (`#B08D57`) with White text. Bold weight. 5px radius. On hover, darken to `#8C6D41` and lift 2px.
- **Secondary:** Transparent with a 2px Gold border. Used for "View Details" or secondary actions.

### Input Fields
- **Default:** White background with a `#CCC` border. 12px padding.
- **Focus State:** Transition to a Gold border with a 5px outer glow (`rgba(176, 141, 87, 0.5)`).

### Car Cards
- **Structure:** White container, 8px radius, subtle shadow.
- **Imagery:** Aspect ratio 16:9 for car photos.
- **Pricing:** Displayed in Bold Gold text at the bottom right (for RTL) to emphasize value.

### Lists & Chips
- **Vehicle Features:** Use small icons (AC, Transmission, Passengers) paired with `body-sm` text.
- **Status Chips:** Small 4px rounded labels for "Available" (Success Green) or "Special Offer" (Primary Gold).

### Navigation
- **Header:** Dark gray (`#1C1C1C`) background. Links in White, transitioning to Gold on hover.
- **Search Bar:** A high-visibility "floating" component on the Hero section with a White background and 8px radius.