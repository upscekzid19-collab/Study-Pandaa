---
name: Institutional Excellence
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#44474e'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#75777f'
  outline-variant: '#c5c6cf'
  surface-tint: '#4e5e82'
  primary: '#031636'
  on-primary: '#ffffff'
  primary-container: '#1a2b4c'
  on-primary-container: '#8293ba'
  inverse-primary: '#b6c6f0'
  secondary: '#795900'
  on-secondary: '#ffffff'
  secondary-container: '#ffbf00'
  on-secondary-container: '#6d5000'
  tertiary: '#241300'
  on-tertiary: '#ffffff'
  tertiary-container: '#3f2600'
  on-tertiary-container: '#b28c5b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#b6c6f0'
  on-primary-fixed: '#071b3b'
  on-primary-fixed-variant: '#364669'
  secondary-fixed: '#ffdfa0'
  secondary-fixed-dim: '#fbbc00'
  on-secondary-fixed: '#261a00'
  on-secondary-fixed-variant: '#5c4300'
  tertiary-fixed: '#ffddb5'
  tertiary-fixed-dim: '#eabf8a'
  on-tertiary-fixed: '#2a1800'
  on-tertiary-fixed-variant: '#5e4117'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display-lg:
    fontFamily: Public Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Public Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Public Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
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
    fontFamily: Public Sans
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Public Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 32px
  xl: 48px
  gutter: 16px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style

The design system is engineered for high-stakes academic achievement. It prioritizes **Institutional Authority** and **Cognitive Clarity**, ensuring that students preparing for UPSC and JKPSC exams feel a sense of stability and focus. 

The visual style is **Modern Corporate**, utilizing a card-based architecture that breaks complex syllabi into digestible modules. By leveraging a "Content-First" philosophy, the UI minimizes distractions, using whitespace as a functional tool to reduce eye strain during long study sessions. The emotional response is one of disciplined progress—shifting the user's mindset from overwhelming preparation to structured mastery.

## Colors

The palette is anchored by **Deep Navy Blue**, representing the gravity and prestige of civil services. This is contrasted against a **Crisp White** background to maintain a high-legibility environment.

- **Primary (Deep Navy):** Used for headers, primary actions, and brand-heavy components to establish authority.
- **Secondary (Amber):** Reserved strictly for motivational cues—streaks, achievement badges, and premium features. It acts as a visual reward.
- **Neutral (Slate/White):** A scale of cool grays is used for borders and secondary text to maintain a calm, professional hierarchy.
- **Surface:** The primary background is white, while secondary surfaces (cards) use a subtle light-gray tint to define boundaries without harsh lines.

## Typography

This design system utilizes **Public Sans**, an institutional-grade typeface designed for clarity and accessibility. It is a neutral, low-contrast sans-serif that remains highly legible across different device pixel densities.

- **Headlines:** Set in Bold or Semi-Bold weights to create a clear entry point for each section.
- **Body Text:** Uses a generous 1.5x line height for the `body-md` and `body-lg` tiers to facilitate "active reading" and better information retention.
- **Labels:** Small caps or medium-weight labels are used for meta-data (e.g., "Time Remaining," "Subject Category") to differentiate them from core study content.

## Layout & Spacing

The layout follows a **Strict 8px Grid System**, ensuring mathematical harmony between elements. 

- **Grid:** A 12-column grid is used for desktop dashboards, while a 4-column grid is standard for mobile devices.
- **Card-Based Hierarchy:** Content is encapsulated in cards with `md` (24px) padding to provide focus. 
- **Reflow:** On mobile, margins reduce to 16px to maximize the reading area. Lists and content blocks stack vertically, while progress trackers and quick-actions remain anchored for easy access.

## Elevation & Depth

To maintain a minimal and professional aesthetic, depth is communicated through **Tonal Layers** and **Low-Contrast Outlines** rather than heavy shadows.

- **Level 0 (Background):** Crisp White (#FFFFFF).
- **Level 1 (Cards/Surface):** White background with a 1px border in a soft Slate-200.
- **Level 2 (Active/Hover):** A very soft ambient shadow (0px 4px 12px rgba(26, 43, 76, 0.05)) to suggest interactivity.
- **Overlays:** Modals and dropdowns use a more defined shadow to separate them from the primary reading plane.

## Shapes

The design system employs **Rounded** geometry to balance the "serious" nature of the content with an approachable, modern user experience.

- **Standard Elements:** Buttons, inputs, and cards use a 0.5rem (8px) radius.
- **Containers:** Large dashboard sections or "Study Hub" containers use a 1rem (16px) radius to create a soft, nested feel.
- **Full-Round:** Used exclusively for tags and badges (e.g., "New," "Attempted") to distinguish them from interactive buttons.

## Components

### Buttons & Chips
- **Primary Button:** Solid Deep Navy with white text; used for "Start Test" or "Join Live Class."
- **Secondary Button:** Outlined Deep Navy; used for "View Solution."
- **Category Chips:** Light blue background with Deep Navy text; used for subjects like "Modern History" or "Geography."

### Progress & Motivation
- **Progress Bars:** Use a dual-tone approach—a light gray track with a Deep Navy fill for syllabus completion. For "Success" milestones, the fill transitions to Amber.
- **Streak Badges:** Circular or hexagonal containers using Amber (#FFBF00) with white iconography to represent consecutive study days.

### List Items (Documents & Videos)
- **Document Items:** Feature a file-type icon (PDF) on the left, the document title in `body-md` (bold), and meta-data (size, date) in `label-sm`.
- **Video Items:** Include a small 16:9 thumbnail with a play icon overlay and a duration timestamp in the bottom-right corner.

### Form Fields
- Inputs are clean with a 1px border. On focus, the border transitions to Deep Navy with a subtle 2px outer glow in a translucent primary color. Labels are always persistent above the field.