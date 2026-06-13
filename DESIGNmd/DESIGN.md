---
name: Precision Utility
colors:
  surface: '#0b1326'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#dae2fd'
  on-surface-variant: '#c2c6d6'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#8c909f'
  outline-variant: '#424754'
  surface-tint: '#adc6ff'
  primary: '#adc6ff'
  on-primary: '#002e6a'
  primary-container: '#4d8eff'
  on-primary-container: '#00285d'
  inverse-primary: '#005ac2'
  secondary: '#4edea3'
  on-secondary: '#003824'
  secondary-container: '#00a572'
  on-secondary-container: '#00311f'
  tertiary: '#ffb786'
  on-tertiary: '#502400'
  tertiary-container: '#df7412'
  on-tertiary-container: '#461f00'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a42'
  on-primary-fixed-variant: '#004395'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#ffdcc6'
  tertiary-fixed-dim: '#ffb786'
  on-tertiary-fixed: '#311400'
  on-tertiary-fixed-variant: '#723600'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: -0.01em
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
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
  mono-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: '1.4'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  container-padding: 24px
  gutter: 16px
  section-gap: 48px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

This design system is built upon a foundation of **Utility Minimalism**. It prioritizes extreme clarity, structural integrity, and functional density, drawing direct inspiration from high-performance developer tools and modern operating system interfaces. The aesthetic is "Official Software"—avoiding decorative trends in favor of a focused, distraction-free environment tailored for student productivity.

The brand personality is professional, reliable, and systematic. It communicates a sense of order and "zero friction," ensuring that the interface never competes with the student's task at hand. Visual interest is generated through precise alignment, generous whitespace, and sharp typographic hierarchy rather than ornamentation.

## Colors

The palette is anchored in a **Dark Mode** primary experience. It utilizes a deep slate and charcoal scale to provide a low-strain, high-focus canvas.

- **Primary:** A professional "Action Blue" (#3B82F6) used for primary interactions, progress indicators, and focus states.
- **Secondary/Success:** A crisp "Forest Green" (#10B981) for completion states and positive feedback.
- **Neutral Scale:** The background is near-black (#0B0E14) to maximize contrast with the content. Surface layers use slightly lighter slate tones (#161B22) to establish depth without relying on shadows.
- **Typography:** Pure white or off-white (#F8FAFC) for maximum legibility of primary content, with muted grays (#94A3B8) for secondary metadata.

## Typography

This design system utilizes **Inter** as a systematic font stack. The typography is treated as a functional tool: sizes are strictly categorized to create a clear scan-path for information-heavy student workflows.

Headlines use tighter tracking and heavier weights to anchor sections, while body text maintains a generous line height (1.6) to ensure long-form reading comfort. A specialized mono-style label (using Inter's medium weight) is used for metadata and status indicators, mimicking the look of a terminal or IDE.

## Layout & Spacing

The layout philosophy follows a **Fixed-Fluid Hybrid** model. Content is organized within a structured 12-column grid on desktop, while spacing between elements follows a strict 4px/8px base-unit system to maintain mathematical harmony.

- **Desktop:** 12 columns, 1120px max-width, 16px gutters, 24px margins.
- **Tablet:** 8 columns, fluid width, 16px gutters, 24px margins.
- **Mobile:** 4 columns, fluid width, 12px gutters, 16px margins.

Spacing is "generous" to avoid visual clutter. Elements are grouped using tight stacks (8px-16px) and separated into logical sections with larger gaps (48px+) to prevent cognitive overload.

## Elevation & Depth

To maintain the "software utility" feel, this design system avoids heavy shadows. Depth is communicated via **Tonal Layering** and **Ghost Borders**:

1.  **Level 0 (Background):** The darkest slate (#0B0E14). Used for the main application canvas.
2.  **Level 1 (Sidebars/Navigation):** Slightly lighter (#12161D). Creates a subtle vertical split.
3.  **Level 2 (Cards/Content Blocks):** Lighter surface (#1C2128) with a 1px solid border (#30363D).
4.  **Level 3 (Modals/Popovers):** The highest surface (#2D333B). These are the only elements that utilize a subtle, 15% opacity black shadow to lift them above the content.

Interactive elements use a "flat-yet-tactile" approach, where buttons change their background shade on hover rather than their elevation.

## Shapes

The design system uses a **Soft (Roundedness 1)** configuration. This translates to a base corner radius of **4px** for small components (buttons, inputs, chips) and **8px** for larger containers (cards, modals). 

This range (4-8px) is the "sweet spot" for professional software—it is softer than a brutalist sharp edge but far more serious than the highly rounded, "bubbly" shapes seen in consumer-grade social apps. It conveys precision and intent.

## Components

### Buttons & Actions
- **Primary:** Solid Blue background (#3B82F6) with white text. 4px radius. No gradient. High-contrast focus ring (2px offset).
- **Ghost:** Transparent background with a 1px border. Used for secondary actions to reduce visual weight.
- **Iconography:** Use 20px stroked icons for clarity. Icons should match the text color exactly.

### Form Inputs
- **Fields:** Dark charcoal background (#0B0E14) with a subtle 1px border. On focus, the border changes to the Primary Blue with a subtle outer glow.
- **Labels:** Always positioned above the input in `label-md` style for maximum accessibility.

### Cards & Surfaces
- **Containers:** Solid background (#161B22) with 8px radius. Use horizontal separators (1px line) to divide header, body, and footer instead of whitespace alone.

### Feedback Elements
- **Chips:** Small, high-contrast badges with a subtle background tint (e.g., 10% opacity Green background with 100% opacity Green text) for status-at-a-glance.
- **Progress Bars:** Thin 4px tracks with solid color fills. No rounded caps; use squared or slightly rounded ends to maintain the technical look.