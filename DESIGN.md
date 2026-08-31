---
name: Serene Empathy
colors:
  surface: '#fbf9f7'
  surface-dim: '#dbdad8'
  surface-bright: '#fbf9f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f1'
  surface-container: '#efedec'
  surface-container-high: '#eae8e6'
  surface-container-highest: '#e4e2e0'
  on-surface: '#1b1c1b'
  on-surface-variant: '#4d4449'
  inverse-surface: '#30302f'
  inverse-on-surface: '#f2f0ee'
  outline: '#7f7479'
  outline-variant: '#d0c3c8'
  surface-tint: '#715766'
  primary: '#715766'
  on-primary: '#ffffff'
  primary-container: '#b496a7'
  on-primary-container: '#452f3d'
  inverse-primary: '#debecf'
  secondary: '#546257'
  on-secondary: '#ffffff'
  secondary-container: '#d5e3d6'
  on-secondary-container: '#58665b'
  tertiary: '#815342'
  on-tertiary: '#ffffff'
  tertiary-container: '#c9927d'
  on-tertiary-container: '#522c1d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#fbd9ec'
  primary-fixed-dim: '#debecf'
  on-primary-fixed: '#291522'
  on-primary-fixed-variant: '#57404e'
  secondary-fixed: '#d8e6d9'
  secondary-fixed-dim: '#bccabd'
  on-secondary-fixed: '#121e16'
  on-secondary-fixed-variant: '#3d4a40'
  tertiary-fixed: '#ffdbce'
  tertiary-fixed-dim: '#f5b9a3'
  on-tertiary-fixed: '#321206'
  on-tertiary-fixed-variant: '#663c2c'
  background: '#fbf9f7'
  on-background: '#1b1c1b'
  surface-variant: '#e4e2e0'
  deep-onyx: '#191919'
  sage-muted: '#8C9A8E'
  warm-terracotta: '#D9A08B'
  dusty-mauve: '#B496A7'
typography:
  display-lg:
    fontFamily: Libre Caslon Text
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 36px
    fontWeight: '400'
    lineHeight: 44px
  headline-md:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  headline-sm:
    fontFamily: Libre Caslon Text
    fontSize: 24px
    fontWeight: '400'
    lineHeight: 32px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style
The brand personality is rooted in professional empathy, offering a safe harbor for mental wellness. It balances the clinical authority of a psychological practice with the warmth of a restorative retreat. The target audience seeks a high-end, trustworthy, and non-judgmental environment.

The design style is **Modern Organic Minimalism**. It utilizes expansive white space, a refined color palette, and a focus on "soft" digital architecture. By blending the structure of a professional clinic with organic, fluid visual elements, the interface feels both organized and human. Transitions should be slow and easing, avoiding jarring movements to maintain a sense of calm.

## Colors
The palette is a curated selection of earthy, muted tones designed to lower cortisol and invite reflection. 
- **Primary (Dusty Mauve):** Used for key brand moments and soft call-to-actions.
- **Secondary (Sage Green):** Provides a calming grounding effect, ideal for success states or restorative content blocks.
- **Tertiary (Warm Terracotta):** Used sparingly as an accent for highlights and active interactions.
- **Neutral (Warm Bone):** The foundation of the design system, replacing pure white to reduce eye strain and feel more "physical."
- **Deep Onyx:** Reserved for high-legibility typography and thin-stroke iconography.

## Typography
The typography strategy pairings high-authority serifs with accessible sans-serifs. 

**Libre Caslon Text** is used for all headlines to project a sense of history, wisdom, and literary sophistication. It should be typeset with slightly tighter letter spacing in larger sizes.

**Hanken Grotesk** is chosen for its exceptional legibility and modern, open apertures. It handles the heavy lifting of clinical descriptions and functional labels. Body text should maintain generous line heights to ensure a comfortable reading experience for users who may be in a stressed emotional state.

## Layout & Spacing
This design system utilizes a **Fixed-Fluid Hybrid Grid**. Content is centered within a 1200px max-width container for desktop to maintain focus, while margins expand fluidly beyond that.

The rhythm is based on an 8px square grid. Vertical spacing between sections should be aggressive (80px to 120px) to allow the "breathable" nature of the brand to manifest. Group related items with 24px or 32px gaps, but keep thematic sections distinct with significant white space. 

On mobile, the 12-column grid collapses to a 4-column layout with 20px side margins, ensuring that text does not feel cramped.

## Elevation & Depth
Depth is conveyed through **Tonal Layering** and **Soft Ambient Shadows** rather than stark borders.

1.  **Surfaces:** Use subtle shifts in background color (e.g., from Neutral to a very light Sage) to define different content areas.
2.  **Shadows:** Shadows are highly diffused (Blur: 30px-50px) with very low opacity (5-8%) and a slight tint of the Primary color to avoid "dirty" grays.
3.  **Glassmorphism:** Use sparingly for navigation bars or floating action overlays with a high backdrop blur (20px) to maintain the sense of lightness.
4.  **Organic Overlays:** Images should occasionally break the grid with soft, rounded masks or overlap onto adjacent sections to create a sense of natural flow.

## Shapes
The shape language is primarily **Organic and Rounded**. While standard UI elements use a 0.5rem (8px) radius, high-impact containers and image masks should utilize asymmetrical "blob" shapes or very large radii (2rem+) to mimic stones, petals, or other natural forms. 

Avoid sharp 90-degree corners wherever possible, as they can feel aggressive or overly clinical. Circles are used for profile images and secondary decorative elements.

## Components
- **Buttons:** Primary buttons use a solid Dusty Mauve background with white text and a 0.5rem radius. Secondary buttons should be ghost-style with a 1px border in Sage-Muted and a subtle hover fill.
- **Inputs:** Form fields feature a soft bone-colored background with a bottom-only border in Deep Onyx (1px) to feel more like a personal journal than a corporate form.
- **Cards:** Cards should have no border, utilizing a very soft ambient shadow and a 1rem corner radius. Padding inside cards must be generous (min 32px).
- **Chips/Tags:** Use for therapeutic specialties. These should be pill-shaped with a low-saturation background color and dark text (e.g., light terracotta background with deep onyx text).
- **List Items:** Separated by thin, low-opacity lines (10% Onyx). Use iconography that is thin-stroke (1.5px) and illustrative rather than blocky.
- **Specialty Component - Reflection Box:** A large, soft-colored container with an organic shape mask used for testimonials or mindful quotes, typeset in centered Libre Caslon Text.