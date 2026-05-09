---
name: Studio Aura
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#20201f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353535'
  on-surface: '#e5e2e1'
  on-surface-variant: '#c4c7c7'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#8e9192'
  outline-variant: '#444748'
  surface-tint: '#c8c6c5'
  primary: '#c8c6c5'
  on-primary: '#313030'
  primary-container: '#0f0f0f'
  on-primary-container: '#7d7b7b'
  inverse-primary: '#5f5e5e'
  secondary: '#e9c176'
  on-secondary: '#412d00'
  secondary-container: '#604403'
  on-secondary-container: '#dab36a'
  tertiary: '#dac587'
  on-tertiary: '#3c2f00'
  tertiary-container: '#140e00'
  on-tertiary-container: '#8c7a44'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#ffdea5'
  secondary-fixed-dim: '#e9c176'
  on-secondary-fixed: '#261900'
  on-secondary-fixed-variant: '#5d4201'
  tertiary-fixed: '#f8e1a1'
  tertiary-fixed-dim: '#dac587'
  on-tertiary-fixed: '#231b00'
  on-tertiary-fixed-variant: '#544514'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353535'
typography:
  display-lg:
    fontFamily: Bodoni Moda
    fontSize: 80px
    fontWeight: '400'
    lineHeight: 96px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Bodoni Moda
    fontSize: 48px
    fontWeight: '400'
    lineHeight: 56px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Bodoni Moda
    fontSize: 42px
    fontWeight: '400'
    lineHeight: 52px
  headline-sm:
    fontFamily: Bodoni Moda
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: 0.01em
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.15em
spacing:
  unit: 8px
  margin-desktop: 80px
  margin-mobile: 24px
  gutter: 32px
  section-gap: 160px
---

## Brand & Style

The design system is rooted in the philosophy of "discreet luxury"—an aesthetic that prioritizes quiet confidence, architectural precision, and the curated atmosphere of an elite art gallery. It targets high-net-worth individuals and connoisseurs who value intentionality over ostentation. 

The visual style is **Minimalist**, characterized by vast "blackspace" that allows high-end interior photography to breathe. It leverages fine lines and structural alignment to evoke the feel of a premium architectural editorial. Every element should feel curated, permanent, and impeccably crafted, moving away from transient digital trends toward a timeless, physical presence.

## Colors

The palette is strictly nocturnal, utilizing a "Dark" default mode to simulate the intimate lighting of a boutique hotel lounge. 

- **Primary Backgrounds:** Use 'Obsidian' for the deepest immersion. Layer 'Charcoal' and 'Slate Black' to create subtle structural depth and section containers.
- **Accents:** 'Brushed Gold' is reserved for interactive elements, call-to-actions, and fine structural highlights. 'Champagne' serves as a secondary metallic for softer highlights or hover states.
- **Typography:** 'Pearl' is the standard for high-readability body text, while 'Ivory' is used for headings to provide a softer, more organic contrast than pure white.

## Typography

This design system employs a high-contrast typographic pairing to mirror architectural blueprints and fashion journals.

- **Headings:** Use **Bodoni Moda**. Its extreme stroke contrast and vertical stress embody traditional luxury. Maintain generous leading to ensure a sense of airiness.
- **Body & Interface:** Use **Hanken Grotesk**. This sans-serif provides a contemporary, sharp counterpoint to the serif headings. Its wide apertures ensure legibility on dark backgrounds.
- **Labels:** Use uppercase Hanken Grotesk with increased letter spacing (tracking) for navigational elements and small captions to evoke a sense of professional labeling.

## Layout & Spacing

The design system utilizes a **Fixed Grid** model on desktop to maintain a curated, gallery-like composition. 

- **Desktop:** 12-column grid with a max-width of 1440px. Gutters are wide (32px) to prevent visual clutter.
- **Blackspace:** Use extreme vertical padding (160px+) between major sections to enforce a slow, rhythmic scrolling experience.
- **Margins:** Generous outer margins (80px) act as a digital "mat" for the content, similar to a framed photograph.
- **Mobile:** Reflows to a 4-column grid with 24px margins. Typography scales down significantly to maintain the architectural ratio.

## Elevation & Depth

Depth in this design system is conveyed through **Tonal Layers** and **Low-Contrast Outlines** rather than traditional shadows.

1.  **Surfaces:** Elements sit on the 'Obsidian' base. Higher-level components (like cards or modals) use the 'Charcoal' or 'Slate Black' tones to appear physically closer to the viewer.
2.  **Borders:** Use 1px "Fine Lines" in 'Brushed Gold' at 30-50% opacity to define boundaries. These lines should feel like gold leaf inlay on dark wood.
3.  **Glassmorphism:** For overlays and menus, use a subtle backdrop blur (20px) with a 10% 'Ivory' tint to simulate frosted glass, maintaining the high-end boutique aesthetic.
4.  **Shadows:** Avoid heavy dropshadows. If needed for critical separation, use a large-radius (40px) ambient glow tinted with the background color to maintain a soft, integrated look.

## Shapes

The shape language of the design system is **Sharp (0px)**. 

Rectilinear forms mirror the precision of high-end interior architecture and structural beams. Buttons, image containers, and input fields must maintain 90-degree corners. This sharpness reinforces the "stately" and "monumental" feel of the brand. Rounded corners should be avoided entirely, as they introduce a softness that conflicts with the intended architectural rigors.

## Components

- **Buttons:** Primary buttons are ghost-style with a 1px 'Brushed Gold' border and 'Ivory' text. On hover, the background fills with a subtle 'Bronze' gradient.
- **Dividers:** Horizontal rules must be 0.5px or 1px thick, utilizing the 'Brushed Gold' accent at low opacity. They should never span the full width of the container, often starting or ending 10% from the edge to create an asymmetric, modern look.
- **Inputs:** Minimalist bottom-border only fields. The label uses the `label-caps` style and floats above the field.
- **Cards:** Cards do not have background colors; they are defined by their content alignment and separated by the fine-line dividers. Images within cards should have a subtle desaturation that returns to full color on hover.
- **Imagery:** All images should be treated with a high-contrast, slightly warm tint to harmonize with the gold accents. Use large-scale "hero" photography that spans at least 8 columns of the grid.
- **Navigation:** A persistent, minimal top bar with 'Ivory' text. Use a 'Brushed Gold' dot or 1px underline for active states.