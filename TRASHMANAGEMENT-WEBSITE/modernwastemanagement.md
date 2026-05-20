---
name: Eco-Modern Waste Management
colors:
  surface: '#f8f9fb'
  surface-dim: '#d9dadc'
  surface-bright: '#f8f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f6'
  surface-container: '#edeef0'
  surface-container-high: '#e7e8ea'
  surface-container-highest: '#e1e2e4'
  on-surface: '#191c1e'
  on-surface-variant: '#3d4a3d'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f3'
  outline: '#6d7b6c'
  outline-variant: '#bccbb9'
  surface-tint: '#006e2f'
  primary: '#006e2f'
  on-primary: '#ffffff'
  primary-container: '#22c55e'
  on-primary-container: '#004b1e'
  inverse-primary: '#4ae176'
  secondary: '#486554'
  on-secondary: '#ffffff'
  secondary-container: '#caead6'
  on-secondary-container: '#4e6b5a'
  tertiary: '#9e4036'
  on-tertiary: '#ffffff'
  tertiary-container: '#ff8b7c'
  on-tertiary-container: '#76231b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#6bff8f'
  primary-fixed-dim: '#4ae176'
  on-primary-fixed: '#002109'
  on-primary-fixed-variant: '#005321'
  secondary-fixed: '#caead6'
  secondary-fixed-dim: '#afceba'
  on-secondary-fixed: '#042014'
  on-secondary-fixed-variant: '#314d3e'
  tertiary-fixed: '#ffdad5'
  tertiary-fixed-dim: '#ffb4a9'
  on-tertiary-fixed: '#410001'
  on-tertiary-fixed-variant: '#7f2a21'
  background: '#f8f9fb'
  on-background: '#191c1e'
  surface-variant: '#e1e2e4'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
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
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
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
  lg: 40px
  xl: 64px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
---

## Brand & Style
The design system is anchored in the principles of environmental stewardship, efficiency, and modern utility. It aims to transform the perception of waste collection from a gritty necessity into a streamlined, high-tech service. The visual language is clean and optimistic, evoking a sense of renewal and civic pride.

The aesthetic follows a **Corporate Modern** approach with hints of **Minimalism**. It prioritizes high legibility, generous whitespace to suggest "cleanliness," and a card-based architecture that keeps complex booking data organized and approachable. The UI should feel as lightweight and frictionless as the sustainable future it promotes.

## Colors
The palette is dominated by "Vital Green," symbolizing growth and ecological health. 

- **Primary**: Used for call-to-action buttons, active states, and primary branding elements.
- **Secondary (Soft Green)**: Used for subtle highlights, background tints for chips, and success states.
- **Neutral**: A range of cool grays provides the structural scaffolding, ensuring the green accents remain impactful.

**Dark Mode Strategy:**
In dark mode, the surface shifts to a deep midnight gray (#111827). Borders should use a low-opacity white (10%) to maintain structure without creating harsh contrast. Green accents should maintain their hue but may require slight luminance adjustments for AAA accessibility against dark backgrounds.

## Typography
This design system utilizes **Inter** for all levels of the hierarchy. Its systematic nature and high x-height make it ideal for data-heavy interfaces like booking schedules and waste manifests.

- **Headlines**: Use bold weights with slight negative letter-spacing to create a confident, modern look.
- **Body**: Standard weight with generous line-height to ensure readability during quick scans of service details.
- **Labels/Numbers**: Used for status badges and table headers, employing medium to semi-bold weights for clear distinction from body text.

## Layout & Spacing
The layout follows a **Fluid Grid** system based on an 8px square rhythm. 

- **Desktop**: A 12-column grid with 24px gutters. Content is typically housed in cards that span 4, 6, or 12 columns.
- **Tablet**: An 8-column grid with 16px gutters.
- **Mobile**: A 4-column grid with 16px margins. 

Elements should use "md" (24px) spacing for internal card padding to maintain the airy, clean eco-friendly aesthetic. Section vertical spacing should scale to "xl" (64px) on desktop to provide visual breathing room between distinct booking categories.

## Elevation & Depth
Depth is created using **Ambient Shadows** and **Tonal Layers**. This avoids a flat, clinical look while remaining professional.

1.  **Level 0 (Floor)**: The main background.
2.  **Level 1 (Cards)**: White surfaces (or #1F2937 in dark mode) with a soft, diffused shadow: `0 4px 6px -1px rgb(0 0 0 / 0.1)`.
3.  **Level 2 (Overlays/Modals)**: Higher elevation with a larger blur radius to indicate temporary focus: `0 20px 25px -5px rgb(0 0 0 / 0.1)`.

In Dark Mode, shadows are minimized in favor of subtle border-strokes (1px) using a lighter gray than the background to define edges.

## Shapes
The design system uses a consistent **Rounded (1rem / 16px)** corner radius for all primary containers and cards. This approach softens the professional interface, making the service feel more approachable and modern.

- **Small elements** (Inputs, Buttons): Use 0.5rem (8px).
- **Standard Cards**: Use 1rem (16px).
- **Status Badges**: Use 9999px (Pill-shaped) to distinguish them from interactive buttons.

## Components

### Buttons
- **Primary**: Solid #22C55E background with white text. High-contrast, 0.5rem rounded corners.
- **Secondary**: #DCFCE7 background with #166534 text. Used for less urgent actions.
- **Ghost**: Transparent background with green outline or text for tertiary actions.

### Input Fields
- White background with a 1px #E5E7EB border. On focus, the border shifts to #22C55E with a subtle green outer glow (2px).

### Status Badges (Pills)
- **Pending**: Amber background, dark amber text.
- **Accepted**: Blue background, dark blue text.
- **In Progress**: Purple background, dark purple text.
- **Completed**: Green background, dark green text.
*All badges should use a low-opacity version of their color for the background to keep text legible.*

### Cards
- The primary container for booking info. Feature 1rem rounded corners, white/dark-gray background, and the Level 1 shadow. Cards should have a consistent 24px internal padding.

### Tables
- Clean, borderless design. Headers in `label-sm` style with #6B7280 color. Rows separated by a light gray horizontal rule (1px). The "Active" row can have a very subtle green tint to guide the eye.

### Service Indicators
- Custom icons for waste types (Recyclable, Organic, Hazardous) should be enclosed in circular containers with Soft Green highlights.