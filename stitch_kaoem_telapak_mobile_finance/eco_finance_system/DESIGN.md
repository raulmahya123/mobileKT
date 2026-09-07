---
name: Eco Finance System
colors:
  surface: '#f3faff'
  surface-dim: '#cddce4'
  surface-bright: '#f3faff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#e7f6fe'
  surface-container: '#e1f0f8'
  surface-container-high: '#dbebf2'
  surface-container-highest: '#d6e5ed'
  on-surface: '#0f1d23'
  on-surface-variant: '#3e4949'
  inverse-surface: '#243238'
  inverse-on-surface: '#e4f3fb'
  outline: '#6e7979'
  outline-variant: '#bdc9c9'
  surface-tint: '#00696d'
  primary: '#006467'
  on-primary: '#ffffff'
  primary-container: '#007f83'
  on-primary-container: '#e1feff'
  inverse-primary: '#77d5d9'
  secondary: '#8e4e00'
  on-secondary: '#ffffff'
  secondary-container: '#ffa44c'
  on-secondary-container: '#6f3c00'
  tertiary: '#316348'
  on-tertiary: '#ffffff'
  tertiary-container: '#4a7c5f'
  on-tertiary-container: '#e2ffea'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#94f2f6'
  primary-fixed-dim: '#77d5d9'
  on-primary-fixed: '#002021'
  on-primary-fixed-variant: '#004f52'
  secondary-fixed: '#ffdcc1'
  secondary-fixed-dim: '#ffb778'
  on-secondary-fixed: '#2e1500'
  on-secondary-fixed-variant: '#6c3a00'
  tertiary-fixed: '#b8efcc'
  tertiary-fixed-dim: '#9dd3b1'
  on-tertiary-fixed: '#002111'
  on-tertiary-fixed-variant: '#1d5036'
  background: '#f3faff'
  on-background: '#0f1d23'
  surface-variant: '#d6e5ed'
typography:
  page-title:
    fontFamily: Poppins
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  page-title-mobile:
    fontFamily: Poppins
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
  section-heading:
    fontFamily: Poppins
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  card-value:
    fontFamily: Poppins
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-main:
    fontFamily: Poppins
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  input-text:
    fontFamily: Poppins
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  button-text:
    fontFamily: Poppins
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
  label-md:
    fontFamily: Poppins
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
  label-sm:
    fontFamily: Poppins
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  metadata:
    fontFamily: Poppins
    fontSize: 11px
    fontWeight: '400'
    lineHeight: 14px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max-width: 1440px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 32px
  component-gap: 16px
  stack-gap: 8px
---

## Brand & Style

The design system is engineered for a professional enterprise finance environment that balances environmental stewardship with fiscal precision. The brand personality is **trustworthy, analytical, and grounded**, designed to evoke a sense of stability and institutional reliability.

The visual style is **Corporate / Modern**, characterized by:
- **Clarity & Precision:** High legibility and systematic alignment to handle complex financial data.
- **Eco-Conscious Professionalism:** Utilizing a palette of teals and earth-toned accents that reflect the "Eco Finance" mission without sacrificing enterprise authority.
- **Flat UI Architecture:** Eschewing gradients and glassmorphism in favor of solid fills, crisp borders, and meaningful whitespace. This ensures the interface remains fast, functional, and accessible.

## Colors

This design system utilizes a structured palette to differentiate financial categories and status indicators clearly.

- **Primary Teal:** Represents the core brand. Use the dark variant (#006467) for interactions and the light variants (#DFF1F1, #F0F8F8) for subtle background highlights or active states in navigation.
- **Accents:** Orange (#F69D46) is used sparingly for highlighting specific financial insights or call-to-actions, while Supporting Green (#5C8F71) reinforces the ecological aspect of the system.
- **Neutrals:** A slate-toned neutral scale is used to maintain professional gravitas. Text Primary (#28363C) ensures high contrast for financial figures.
- **Semantic Logic:** Statuses must use a "Pale-Background + Dark-Text" formula. For example, a "Success" tag should use a light green background with #3D8B62 text to ensure legibility and a soft but professional appearance.

## Typography

The typography system relies exclusively on **Poppins** to provide a clean, geometric feel that is highly readable in data-dense environments.

- **Financial Data:** Card values and numeric outputs should use the `card-value` style to ensure they are the primary focal point of dashboard views.
- **Hierarchy:** Clear distinction is made between `page-title` (for context) and `section-heading` (for grouping content).
- **Functional Text:** Labels and metadata are slightly tighter in line-height to allow for compact data tables and complex forms without feeling cluttered.

## Layout & Spacing

The design system employs a **Fluid Grid** model with fixed-width sidebars for desktop enterprise views. 

- **Desktop (1440px+):** 12-column grid, 24px gutters, 32px outer margins.
- **Tablet (768px - 1439px):** 8-column grid, 16px gutters, 24px outer margins.
- **Mobile (<767px):** 4-column grid, 16px gutters, 16px outer margins.

The spacing rhythm follows a 4px/8px baseline. Use 16px for standard grouping of elements and 8px for internal component relationships (e.g., label to input field).

## Elevation & Depth

This design system uses a **Low-Contrast Outline** approach to convey hierarchy, avoiding shadows to maintain a clean, "eco-modern" aesthetic.

- **Flat Surface Tiering:** Depth is created through tonal layering. The global background is `#F7F9F9`, while actionable surfaces (Cards, Modals) use `#FFFFFF`.
- **Borders as Dividers:** Surfaces are defined by `#E1E7E8` borders. This provides a clear "container" feel without the visual weight of shadows.
- **Interaction Depth:** On hover or active states, surfaces do not lift; instead, they may transition in border color (to Primary Teal) or use subtle inner-background shifts (to `#F0F8F8`).

## Shapes

The shape language is consistently **Rounded**, providing a approachable feel to the rigorous financial data.

- **Standard Elements:** Buttons and Input fields use an 8px radius.
- **Container Elements:** Cards use a 10px radius to subtly distinguish them from smaller UI components.
- **Mobile Overlays:** Bottom sheets use a 16px radius on top corners to emphasize their role as temporary, high-level surface layers.

## Components

### Buttons
- **Primary:** #007F83 background, White text, 48px height, 8px radius.
- **Secondary:** #F0F8F8 background, #007F83 text, no border.
- **Outlined:** White background, #007F83 border, #007F83 text.

### Input Fields
- **Default:** 48px height, 8px radius, #CDD5D8 border.
- **Focus State:** #007F83 border with 1px thickness.
- **Labels:** Positioned above the field using `label-md`.

### Cards
- **Structure:** White background, #E1E7E8 border, 10px radius. 
- **Header:** Optional 1px divider (#E9EDEE) separating the title area from the content area.

### Chips/Tags
- **Status Tags:** Use the semantic palette. (e.g., Success: #E9F3ED background, #3D8B62 text). 
- **Geometry:** Fully rounded (pill-shaped) for tags to differentiate them from square-cornered buttons.

### Bottom Sheets
- **Mobile Only:** Use a 16px top-left and top-right radius. Include a 4px thick "handle" indicator at the top center in `#E1E7E8`.

### Lists & Tables
- **Row Height:** 56px for standard data rows.
- **Dividers:** 1px solid #E9EDEE between rows.