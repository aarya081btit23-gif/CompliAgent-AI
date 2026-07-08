---
name: CompliAgent AI System
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#45464d'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#006c49'
  on-secondary: '#ffffff'
  secondary-container: '#6cf8bb'
  on-secondary-container: '#00714d'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#2a1700'
  on-tertiary-container: '#b87500'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
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
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
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
  xl: 32px
  2xl: 48px
  3xl: 64px
  container-max: 1440px
  gutter: 24px
---

## Brand & Style

The design system is engineered for high-stakes regulatory environments, specifically tailored for SEBI-regulated stock brokers. The brand personality is **precise, efficient, and reliable**, serving as a "digital auditor" that remains unobtrusive until action is required.

The visual style follows a **Corporate / Modern** aesthetic. It prioritizes data density without sacrificing clarity, utilizing a systematic approach to whitespace and structural alignment. The UI evokes a sense of "technological authority"—combining the traditional stability of financial institutions with the speed and intelligence of AI-driven compliance. 

Key visual principles include:
- **Clarity over Decoration:** Every element serves a functional purpose in the compliance workflow.
- **Instant Recognition:** Color and iconography are used strategically to communicate risk levels and system status at a glance.
- **Architectural Integrity:** Strong vertical and horizontal alignment to reflect the structured nature of regulatory frameworks.

## Colors

The palette is anchored in **Deep Navy (#0F172A)** to establish a foundation of trust and regulatory authority. **Emerald Green (#10B981)** is utilized for success states and "Compliant" statuses, providing a clear visual "go" signal. **Amber (#F59E0B)** serves as the primary alert color for risk and attention-required items.

The system employs a specific semantic tier for risk management:
- **Critical/Overdue:** High-intensity reds to signal immediate regulatory danger.
- **High Risk:** Vibrant orange for significant anomalies.
- **Medium Risk/Attention:** Amber for cautionary monitoring.
- **Low Risk/Completed:** Blues and Greens for stable, healthy environments.

Backgrounds should remain primarily white or very light gray (#F8FAFC) to ensure the semantic colors carry maximum cognitive weight.

## Typography

The typography strategy focuses on legibility and data-heavy scanning. **Inter** is the primary typeface for its exceptional clarity and professional tone. 

For technical data, regulatory codes, and timestamps, **JetBrains Mono** is introduced as a secondary label font. This monospaced choice reinforces the "AI-driven" and "precise" nature of the compliance platform, making alphanumeric strings easier to audit and compare.

**Hierarchy Rules:**
- Use `headline-lg` for dashboard section headers.
- Use `label-sm` (uppercase) for table headers and metadata categories.
- Ensure a minimum contrast ratio of 4.5:1 for all body text against backgrounds.

## Layout & Spacing

This design system utilizes a **12-column fluid grid** for desktop, transitioning to a **4-column grid** for mobile devices. The layout philosophy centers on "Modular Information Blocks"—grouping related compliance data into distinct containers.

**Spacing Rhythm:**
- A base unit of **4px** is used to derive all spacing.
- **16px (md)** is the standard padding for components and internal card spacing.
- **24px (lg)** is the default gutter between major layout sections.
- **Mobile Adjustments:** Margins reduce from 32px on desktop to 16px on mobile to maximize screen real estate for data tables.

## Elevation & Depth

To maintain a clean, corporate feel, depth is communicated through **Tonal Layers** and **Low-Contrast Outlines** rather than heavy shadows.

- **Level 0 (Surface):** The main background color (#F8FAFC).
- **Level 1 (Cards/Containers):** Pure white background with a 1px border (#E2E8F0).
- **Level 2 (Active/Hover):** A subtle, extra-diffused shadow (0px 4px 6px -1px rgba(15, 23, 42, 0.05)) to indicate interactivity.
- **Level 3 (Modals/Popovers):** Higher contrast border and a more defined shadow to pull the element forward from the data grid.

Avoid using gradients. Depth should feel physical but restrained, like a stack of high-quality paper documents.

## Shapes

The design system uses a **Soft (Level 1)** roundedness profile. This 4px (0.25rem) base radius provides a modern touch without appearing overly "bubbly" or consumer-oriented. It maintains the professional rigor required for financial software.

- **Standard Components:** 4px (Buttons, Input Fields, Checkboxes).
- **Large Components:** 8px (Cards, Modals).
- **Badges/Chips:** Full Pill-shape (999px) to distinguish status indicators from clickable buttons.

## Components

### Buttons
- **Primary:** Solid Navy (#0F172A) with white text. 4px radius.
- **Secondary:** White background with Navy border and text.
- **Success/Action:** Solid Emerald Green for "Finalize" or "Approve" actions.

### Status Indicators (Pills)
Status badges must use the full-pill radius. They should use a "Soft Fill" approach: a 10-15% opacity background of the status color with high-contrast text of the same hue (e.g., Critical = Light Red background, Dark Red text).

### Input Fields
Clean, 1px bordered boxes. On focus, the border should shift to the Primary Navy with a subtle 2px outer "glow" in a transparent version of the primary color. Label text should always be visible above the field.

### Data Tables
The core of the platform. Use `body-sm` for row data. Row backgrounds should alternate (Zebra striping) using #F1F5F9. The "Risk Level" column should always feature the semantic status pill for instant scanning.

### Cards
Cards are the primary container for compliance modules. They should have a 1px #E2E8F0 border, no shadow (unless hovered), and a clear title section using `headline-md`.

### Risk Alerts
Specialized banners that appear at the top of the dashboard. They use the status color as a left-side border accent (4px width) to denote the severity of the alert.