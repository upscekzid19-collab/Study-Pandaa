---
name: Institutional Excellence Dark
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
  secondary: '#ffb95f'
  on-secondary: '#472a00'
  secondary-container: '#ee9800'
  on-secondary-container: '#5b3800'
  tertiary: '#b7c8e1'
  on-tertiary: '#213145'
  tertiary-container: '#8292aa'
  on-tertiary-container: '#1a2b3e'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a42'
  on-primary-fixed-variant: '#004395'
  secondary-fixed: '#ffddb8'
  secondary-fixed-dim: '#ffb95f'
  on-secondary-fixed: '#2a1700'
  on-secondary-fixed-variant: '#653e00'
  tertiary-fixed: '#d3e4fe'
  tertiary-fixed-dim: '#b7c8e1'
  on-tertiary-fixed: '#0b1c30'
  on-tertiary-fixed-variant: '#38485d'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  headline-xl:
    fontFamily: Public Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Public Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Public Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-md:
    fontFamily: Public Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Public Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Public Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Source Sans 3
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  caption:
    fontFamily: Public Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 40px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
---

## Brand & Style
The design system evolves into a high-authority, dark-mode environment tailored for prestige, government, and finance sectors. The aesthetic is "Sovereign Modernism"—combining the weight of established institutions with the sleekness of modern technology. 

The personality is intellectual, secure, and commanding. By utilizing a deep midnight foundation, the interface reduces visual noise and emphasizes high-value data and achievement markers. The style leans into **Corporate Modernism** with a focus on precision, utilizing subtle tonal layering rather than aggressive shadows to define hierarchy.

## Colors
The palette is anchored by a **Deep Charcoal/Midnight Navy (#0f172a)** base, providing a stable and serious environment. 

- **Primary:** A recalibrated Professional Navy Blue, shifted toward a more vibrant blue (#3b82f6) to maintain legibility and "glow" against dark backgrounds.
- **Accent:** Institutional Amber (#f59e0b) is reserved strictly for achievements, warnings, and high-level status markers, ensuring it retains its symbolic value.
- **Surfaces:** Containers use a lighter muted tone (#1e293b) to create a clear sense of containment and physical structure.
- **Typography:** Primary information uses an off-white (#f8fafc) for maximum readability without the harshness of pure white, while metadata uses a muted slate grey.

## Typography
This design system utilizes **Public Sans** for its institutional clarity and neutral, authoritative tone. It is a typeface that suggests stability and accessibility. 

For functional interface elements and data labels, **Source Sans 3** is employed to provide a distinct visual hierarchy between content and navigation. Headlines utilize tighter letter-spacing and heavier weights to command attention, while body text maintains generous line heights to ensure long-form readability against the dark background.

## Layout & Spacing
The system follows a **Fixed Grid** philosophy for desktop to maintain an organized, "document-like" structure, transitioning to a fluid model for mobile.

- **Desktop:** 12-column grid with a 1280px max-width, 24px gutters, and 40px side margins.
- **Tablet:** 8-column grid with 24px gutters and 24px margins.
- **Mobile:** 4-column grid with 16px gutters and 16px margins.

Spacing is strictly derived from a 4px base unit, ensuring a rhythmic vertical flow. White space (or "dark space") is used intentionally to separate different functional zones rather than relying on heavy borders.

## Elevation & Depth
In this dark-themed system, depth is communicated through **Tonal Layers** rather than shadows. 

- **Level 0 (Background):** Deepest navy (#0f172a).
- **Level 1 (Cards/Sections):** Muted slate (#1e293b).
- **Level 2 (Popovers/Modals):** A slightly lighter slate (#334155) to simulate physical proximity to the user.

A **Low-contrast outline** approach is used for interactive elements. Instead of traditional shadows, buttons and inputs feature a subtle 1px border (#334155) to define their edges against the dark surfaces. Interactive states (hover/active) are indicated by a subtle increase in brightness of the surface color or a primary-colored border.

## Shapes
The shape language is **Soft** (0.25rem), reflecting a professional and structured environment. This slight rounding takes the "edge" off the brutalist tendencies of dark mode while maintaining a serious, institutional character.

- **Standard Buttons & Inputs:** 4px (0.25rem) radius.
- **Cards & Modals:** 8px (0.5rem) radius.
- **Status Tags/Chips:** 12px (0.75rem) radius for distinct visual separation from functional buttons.

## Components

### Buttons
Primary buttons use the adjusted Primary Blue (#3b82f6) with white text. Secondary buttons are ghost-styled with a Slate border and Off-White text. High-importance achievement buttons use the Amber/Gold accent.

### Input Fields
Fields use the Level 1 surface color (#1e293b) with a 1px border. Focus states are indicated by a Primary Blue 2px border and a subtle outer glow. Labels sit above the field in Secondary Text color.

### Cards
Cards are defined by the Level 1 surface. They do not use shadows; instead, they are separated from the background by their tonal difference and a subtle 1px border.

### Chips & Badges
Used for status markers. Success states use a dark green tint, while "Achievement" markers use the Amber/Gold palette with high contrast black text for maximum impact.

### Lists & Tables
Rows are separated by thin Slate-800 lines. Table headers use the Label-MD typography style with a subtle background tint to distinguish the header row from the data.