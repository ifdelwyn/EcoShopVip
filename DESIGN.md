---
name: Lumina Eco
colors:
  surface: '#eaffea'
  surface-dim: '#a9e9b6'
  surface-bright: '#eaffea'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#d1ffd8'
  surface-container: '#bcfdc9'
  surface-container-high: '#b7f7c3'
  surface-container-highest: '#b1f2be'
  on-surface: '#00210d'
  on-surface-variant: '#3e4a3d'
  inverse-surface: '#00391a'
  inverse-on-surface: '#c3ffce'
  outline: '#6e7b6c'
  outline-variant: '#bdcaba'
  surface-tint: '#006e2d'
  primary: '#006b2c'
  on-primary: '#ffffff'
  primary-container: '#00873a'
  on-primary-container: '#f7fff2'
  inverse-primary: '#62df7d'
  secondary: '#006d30'
  on-secondary: '#ffffff'
  secondary-container: '#92f5a4'
  on-secondary-container: '#007233'
  tertiary: '#006b2d'
  on-tertiary: '#ffffff'
  tertiary-container: '#00873b'
  on-tertiary-container: '#f7fff3'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#7ffc97'
  primary-fixed-dim: '#62df7d'
  on-primary-fixed: '#002109'
  on-primary-fixed-variant: '#005320'
  secondary-fixed: '#95f8a7'
  secondary-fixed-dim: '#79db8d'
  on-secondary-fixed: '#00210a'
  on-secondary-fixed-variant: '#005323'
  tertiary-fixed: '#6bff8f'
  tertiary-fixed-dim: '#4ae176'
  on-tertiary-fixed: '#002109'
  on-tertiary-fixed-variant: '#005321'
  background: '#eaffea'
  on-background: '#00210d'
  surface-variant: '#b1f2be'
typography:
  display:
    fontFamily: Inter
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: '1.3'
  title-lg:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '500'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.2'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
---

## Brand & Style
The design system embodies a premium, high-end organic commerce experience that fuses the precision of modern technology with the vitality of the natural world. It targets an affluent, eco-conscious demographic that values sustainability without compromising on aesthetic sophistication or digital performance.

The visual style is a hybrid of **Minimalism** and **Glassmorphism**. It utilizes expansive white space, precise typography, and sophisticated "frosted" surfaces to create a sense of airy transparency and trust. The emotional response should be one of "Refined Vitality"—feeling fresh, innovative, and impeccably clean. This is achieved through high-quality photography, smooth motion curves, and a light-drenched interface that mirrors the clarity of a high-end wellness boutique.

## Colors
The palette is rooted in a spectrum of verdant greens, designed to evoke growth and environmental stewardship while maintaining a "tech-forward" brightness. 

- **Primary (#16A34A):** Used for main actions and brand signifiers. It represents the "Success Green" of a flourishing ecosystem.
- **Secondary (#15803D):** A deeper "Forest Green" used for depth, hover states of primary elements, and structural accents.
- **Accent (#22C55E):** A "Vibrant Lime" reserved for high-visibility highlights, active indicators, and promotional callouts.
- **Surface & Background:** The background uses an ultra-light mint (#F0FDF4) to reduce eye strain and differentiate from pure white glass surfaces (#FFFFFF).
- **Text:** The deep dark green (#14532D) replaces traditional grays to ensure high legibility while maintaining the organic thematic consistency.

## Typography
This design system utilizes **Inter** for its exceptional clarity and systematic versatility across multiple languages. The typographic hierarchy is structured to support high-end editorial commerce.

**Internationalization:**
- **CJK (ZH, JP):** Adjust line heights to 1.7x for body text to maintain readability.
- **Arabic (AR):** Ensure `dir="rtl"` is globally applied; Inter provides a neutral companion to standard Arabic system fonts.
- **Sizing:** Large display headers use tight tracking and heavy weights for impact, while body text uses generous line height for a premium, effortless reading experience.

## Layout & Spacing
The layout follows a **fluid grid** philosophy with fixed maximum widths to preserve the "Stripe-like" organized aesthetic on ultra-wide monitors.

- **Desktop:** 12-column grid with 24px gutters. Use wide 48px margins to frame the content like a luxury magazine.
- **Tablet:** 8-column grid with 20px gutters.
- **Mobile:** 4-column grid with 16px margins. 
- **Rhythm:** All spacing is derived from a base-8 unit. Padding within cards and glass containers should be generous (typically 32px or 40px) to enhance the feeling of premium "breathability."

## Elevation & Depth
The system uses **Glassmorphism** and **Ambient Shadows** to create a multi-layered interface that feels light and futuristic.

1.  **Base Layer:** The Ultra-light Mint background (#F0FDF4).
2.  **Glass Layer:** Surfaces use a semi-transparent white (#FFFFFF) with a 20px - 40px backdrop blur and a subtle 1px inner border (white, 20% opacity) to catch the light.
3.  **Shadows:** Shadows are highly diffused, low-opacity, and slightly tinted with the Primary color (e.g., `rgba(22, 163, 74, 0.08)`) to avoid a "dirty" gray look.
4.  **Floating Nav:** The main navigation bar should always be a floating glass element with a high z-index, separated from the background by a premium "extra-large" ambient shadow.

## Shapes
The shape language is sophisticated and modern, avoiding both sharp aggressive corners and overly childish "bubbly" curves. 

- **Primary Elements:** Buttons and Input fields use a standard 0.5rem (8px) radius.
- **Containers:** Product cards and glass panels use `rounded-lg` (16px) or `rounded-xl` (24px) to create a softer, more inviting architectural feel.
- **Interactive States:** On hover, certain elements may subtly increase their corner radius or expand slightly (magnetic effect) to indicate interactivity.

## Components
- **Magnetic Buttons:** Primary buttons feature a solid green fill with a white label. Implement a "magnetic" hover effect where the button subtly pulls toward the cursor within a 20px radius.
- **Glass Navbars:** Fixed-position containers with `backdrop-filter: blur(20px)` and a thin, light-catching top border.
- **Glow Hover Effects:** Interactive cards should exhibit a soft, radial green glow that follows the mouse movement, highlighting the card's boundary.
- **Shimmer States:** Use a custom "Eco Shimmer" for loading—a gradient moving from #F0FDF4 to #DCFCE7 and back, creating a pulse of life.
- **Inputs:** Ultra-minimalist fields with a light mint background and a 2px Primary green bottom border that expands on focus.
- **Product Cards:** Images should be hosted on a slightly off-white background with no border, using a subtle drop shadow to separate them from the glass container.