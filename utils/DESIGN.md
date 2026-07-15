---
name: Lumina Industrial
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#c3c5d9'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#8d90a2'
  outline-variant: '#434656'
  surface-tint: '#b7c4ff'
  primary: '#b7c4ff'
  on-primary: '#002682'
  primary-container: '#0052ff'
  on-primary-container: '#dfe3ff'
  inverse-primary: '#004ced'
  secondary: '#ffc482'
  on-secondary: '#482900'
  secondary-container: '#fd9e00'
  on-secondary-container: '#653c00'
  tertiary: '#ffb4a1'
  on-tertiary: '#611300'
  tertiary-container: '#bf3003'
  on-tertiary-container: '#ffddd5'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dde1ff'
  primary-fixed-dim: '#b7c4ff'
  on-primary-fixed: '#001452'
  on-primary-fixed-variant: '#0038b6'
  secondary-fixed: '#ffddba'
  secondary-fixed-dim: '#ffb866'
  on-secondary-fixed: '#2b1700'
  on-secondary-fixed-variant: '#673d00'
  tertiary-fixed: '#ffdbd2'
  tertiary-fixed-dim: '#ffb4a1'
  on-tertiary-fixed: '#3c0800'
  on-tertiary-fixed-variant: '#891e00'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 72px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-xl:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-italic:
    fontFamily: Newsreader
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.3'
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
  label-mono:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-padding: 64px
  gutter: 24px
  section-gap: 120px
  grid-pattern-size: 40px
---

## Brand & Style

This design system is engineered for the high-end industrial renewable energy sector. It targets institutional investors, utility-scale partners, and government stakeholders who value precision, reliability, and technical prowess.

The aesthetic is a fusion of **Dark Industrial Tech** and **Swiss Minimalism**. It utilizes a deep charcoal foundation to evoke the strength of heavy infrastructure, contrasted with high-fidelity glassmorphism to represent the cutting-edge intelligence of smart grids. 

### Visual Pillars
- **Technical Precision:** Use of subtle background blueprint grids (opacity 5-10%) and monospaced accents.
- **Cleantech Luminescence:** Elements appear to glow or emit light against the dark substrate, utilizing the Electric Blue and Solar Orange as functional "signals."
- **Organic Engineering:** A strict 24px radius is applied to primary containers, balancing industrial rigidity with the fluidity of renewable energy flows.
- **Glassmorphism:** Surfaces use high background blur (20px-40px) with thin, translucent borders to create a layered, multi-dimensional workspace.

## Colors

The palette is anchored in a monochromatic dark range to ensure maximum contrast for technical data and accented highlights.

- **Deep Charcoal (#0D0D0D):** The primary background color. It should be matte and deep, providing a non-reflective "chassis" for the UI.
- **Electric Blue (#0052FF):** Representing energy flow, connectivity, and digital intelligence. Used for primary actions and "active" system states.
- **Solar Orange (#FF9F00):** Representing power generation, heat, and physical hardware. Used sparingly for critical alerts, high-level KPIs, and secondary focal points.
- **Glass Surfaces:** Containers use a semi-transparent white stroke (1px, 10-15% opacity) and a dark translucent fill to maintain legibility over the technical grid pattern.

## Typography

Typography follows a rigorous hierarchy inspired by Swiss editorial design.

- **Headlines:** Montserrat provides a geometric, authoritative presence. Large titles should use tight tracking and bold weights to feel like architectural elements.
- **Body:** Inter is used for high legibility in technical descriptions. The muted grey color ensures the hierarchy remains focused on headlines and data.
- **Serif Contrast:** Occasional use of `Newsreader` in italic adds a sophisticated, humanistic touch to editorial pull-quotes or mission statements, breaking the industrial rigidity.
- **Technical Labels:** Space Grotesk is used for data labels, telemetry readings, and small UI metadata to emphasize the "tech-stack" nature of the product.

## Layout & Spacing

The layout is built on a **12-column fluid grid** with generous safe areas to maintain a "high-end" airy feel despite the dark theme.

- **Grid Pattern:** A persistent technical background grid with 40px squares is visible at low opacity (3-5%). Elements should align strictly to this grid.
- **Rhythm:** An 8px base unit governs all padding and margins.
- **Desktop:** 64px outer margins. Content is often center-aligned or asymmetric to create visual interest.
- **Mobile:** Transition to a single-column layout with 24px margins. Headlines scale down to 32px-40px to ensure readability.

## Elevation & Depth

Depth is conveyed through **translucency and blur** rather than traditional drop shadows.

- **Surface Tiers:**
    - **Base:** #0D0D0D with the blueprint grid pattern.
    - **Level 1 (Cards/Panels):** Glassmorphic fill (rgba 255, 255, 255, 0.03) with a 40px backdrop blur.
    - **Level 2 (Modals/Overlays):** Slightly higher opacity fill (rgba 255, 255, 255, 0.07) with a subtle inner glow on the top edge.
- **Borders:** Surfaces are defined by 1px "razor" borders using `rgba(255, 255, 255, 0.1)`. This creates a clean, schematic look reminiscent of high-end hardware interfaces.

## Shapes

The design uses a distinctive **24px (1.5rem)** radius for all primary containers and large cards. This "organic industrial" curve contrasts the sharp grid lines of the background.

- **Primary Containers:** 24px corner radius.
- **Buttons & Inputs:** 12px corner radius for a more compact, tactile feel.
- **Data Tags:** Fully rounded (pill) to distinguish them from structural components.
- **Iconography:** Use 2pt stroke weight with slightly rounded joins to match the typeface characteristics.

## Components

### Buttons
- **Primary:** Electric Blue background, white text. No shadow, but a subtle outer glow on hover. 12px radius.
- **Secondary:** Transparent with a 1px white border (30% opacity). Blur effect applied to the button area.
- **Tertiary:** Solar Orange text link with a monospaced "arrow" (e.g., →) for technical calls to action.

### Cards
- Always glassmorphic. Content should have 32px internal padding. 
- Headers within cards should use the technical label style (Space Grotesk) to denote the "module" name.

### Input Fields
- Dark, inset appearance with a 1px border that glows Electric Blue when focused. 
- Placeholder text in muted grey.

### Chips & Tags
- Used for system status (e.g., "ONLINE", "GENERATING"). 
- Small, uppercase Space Grotesk text. Use the accent colors (Blue/Orange) for the text only, against a dark semi-transparent background.

### Technical Elements
- **Telemetry Readouts:** Use monospaced numbers for changing values (e.g., Wattage, Voltage) to prevent layout shift.
- **Dividers:** 1px lines with a gradient fade at both ends to integrate seamlessly into the blueprint background.