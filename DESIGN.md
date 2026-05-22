---
name: Alpenglow
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
  on-surface-variant: '#414755'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#717786'
  outline-variant: '#c1c6d7'
  surface-tint: '#005bc1'
  primary: '#0058bc'
  on-primary: '#ffffff'
  primary-container: '#0070eb'
  on-primary-container: '#fefcff'
  inverse-primary: '#adc6ff'
  secondary: '#845400'
  on-secondary: '#ffffff'
  secondary-container: '#feb246'
  on-secondary-container: '#6f4600'
  tertiary: '#585d60'
  on-tertiary: '#ffffff'
  tertiary-container: '#707579'
  on-tertiary-container: '#fbfcff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a41'
  on-primary-fixed-variant: '#004493'
  secondary-fixed: '#ffddb6'
  secondary-fixed-dim: '#ffb95a'
  on-secondary-fixed: '#2a1800'
  on-secondary-fixed-variant: '#643f00'
  tertiary-fixed: '#dfe3e7'
  tertiary-fixed-dim: '#c3c7cb'
  on-tertiary-fixed: '#171c1f'
  on-tertiary-fixed-variant: '#43474b'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '300'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 36px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style

The design system is inspired by the ethereal clarity of high-altitude landscapes. It targets a professional audience that values precision, serenity, and high-performance aesthetics. The brand personality is "Elevated Clarity"—balancing the cold, sharp focus of alpine peaks with the inviting warmth of a sunset horizon.

The visual style is **Aesthetic Minimalism** with subtle **Glassmorphic** accents. It utilizes generous whitespace to evoke the vastness of the sky, paired with razor-sharp typography and soft, translucent layers that mimic the interplay of light on ice and clouds. The emotional response should be one of calm confidence and effortless scale.

## Colors

The palette is derived directly from the mountain horizon at dusk.
- **Primary (Sky Blue):** A bright, clear blue used for primary actions and highlights, representing the endless sky.
- **Secondary (Sunset Gold):** A warm, glowing orange used sparingly for attention-grabbing elements, notifications, or "Farooq" brand signatures.
- **Neutral (Snow & Ice):** A range of crisp whites and extremely light cool-greys form the backbone of the UI, ensuring the interface feels airy and lightweight.
- **Tonal Accents:** Use soft blue-tinted greys for borders and backgrounds to maintain the "cool" alpine atmosphere without reverting to pure black-and-white.

## Typography

This design system uses a pairing of **Hanken Grotesk** for headlines and **Inter** for body text. 
- **Headlines:** Set with light weights and tight letter-spacing to appear sophisticated and modern. The "Display" style should feel as thin and sharp as a ridge line.
- **Body:** Inter provides the professional utility required for SaaS and high-information environments, ensuring legibility even at small scales.
- **Labels:** Small labels use Hanken Grotesk with increased tracking and a semi-bold weight for a technical, precise feel.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** on desktop (1200px max-width) and a **Fluid Grid** on mobile. 
- **Rhythm:** An 8px base unit drives all spacing decisions.
- **Density:** The system prioritizes "Low Density" to maintain the aesthetic of vastness. Large sections should be separated by `xl` (80px) spacing to allow the content to breathe.
- **Margins:** Desktop margins are generous (64px) to center the focus, while mobile margins compress to 16px to maximize screen real estate.
- **Columns:** Use a 12-column grid for desktop, a 6-column grid for tablet, and a 2-column grid for mobile.

## Elevation & Depth

Hierarchy is established through **Backdrop Blurs** and **Ambient Shadows** rather than heavy borders.
- **Surfaces:** Use semi-transparent white (rgba 255, 255, 255, 0.7) with a `20px` backdrop blur for floating menus and navigation bars.
- **Shadows:** Shadows are highly diffused and tinted with the primary blue (e.g., `0 10px 30px rgba(0, 122, 255, 0.08)`). This keeps the "elevation" feeling light and airy rather than heavy or muddy.
- **Dividers:** Use thin `1px` lines in a very light grey-blue (`#E2E8F0`) only when absolutely necessary for content separation.

## Shapes

The shape language is **Rounded**, reflecting the soft curves of snowdrifts while maintaining the professional structure of the grid. 
- **Standard UI Elements:** Use a `0.5rem` (8px) radius for buttons and input fields.
- **Containers:** Cards and large modal containers use `1rem` (16px) for a softer, more modern presence.
- **Icons:** Icons should feature rounded terminals and a consistent 2px stroke weight to match the "light but professional" aesthetic.

## Components

### Buttons
- **Primary:** Solid Sky Blue with white text. High-contrast, 0.5rem corner radius.
- **Secondary:** Sky Blue ghost button with a 1px border.
- **Tertiary:** Sunset Gold text-only button for critical calls to action that need to pop against the blue/white landscape.

### Input Fields
- Backgrounds should be slightly off-white (`#F8FAFC`) to distinguish them from the pure white page background. Use a subtle 1px border that turns Sky Blue on focus.

### Cards
- Cards use the `rounded-lg` (16px) radius and a very soft ambient shadow. They should feel like sheets of light resting on the background.

### Navigation
- Top navigation should always use the Glassmorphic effect (blur) to allow the "mountain" colors of the background content to peak through as the user scrolls.

### Status Chips
- Chips use a "Light Tonal" style: a pale background of the status color with high-contrast text (e.g., pale orange background with dark orange text for warnings).