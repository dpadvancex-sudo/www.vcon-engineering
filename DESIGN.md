---
name: Structural Precision
colors:
  surface: '#f9f9fe'
  surface-dim: '#dad9de'
  surface-bright: '#f9f9fe'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f8'
  surface-container: '#eeedf2'
  surface-container-high: '#e8e8ed'
  surface-container-highest: '#e2e2e7'
  on-surface: '#1a1c1f'
  on-surface-variant: '#43474f'
  inverse-surface: '#2f3034'
  inverse-on-surface: '#f1f0f5'
  outline: '#737780'
  outline-variant: '#c3c6d1'
  surface-tint: '#3a5f94'
  primary: '#001e40'
  on-primary: '#ffffff'
  primary-container: '#003366'
  on-primary-container: '#799dd6'
  inverse-primary: '#a7c8ff'
  secondary: '#904d00'
  on-secondary: '#ffffff'
  secondary-container: '#fd8b00'
  on-secondary-container: '#603100'
  tertiary: '#381300'
  on-tertiary: '#ffffff'
  tertiary-container: '#592300'
  on-tertiary-container: '#d8885c'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d5e3ff'
  primary-fixed-dim: '#a7c8ff'
  on-primary-fixed: '#001b3c'
  on-primary-fixed-variant: '#1f477b'
  secondary-fixed: '#ffdcc3'
  secondary-fixed-dim: '#ffb77d'
  on-secondary-fixed: '#2f1500'
  on-secondary-fixed-variant: '#6e3900'
  tertiary-fixed: '#ffdbca'
  tertiary-fixed-dim: '#ffb690'
  on-tertiary-fixed: '#341100'
  on-tertiary-fixed-variant: '#723610'
  background: '#f9f9fe'
  on-background: '#1a1c1f'
  surface-variant: '#e2e2e7'
typography:
  headline-lg:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.25'
  headline-sm:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
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
    lineHeight: '1.5'
  label-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.02em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin: 32px
  stack-xs: 4px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
  stack-xl: 64px
---

## Brand & Style

The design system is built upon the pillars of structural integrity, engineering precision, and industrial momentum. It is designed to serve a professional B2B audience in the engineering and construction sectors, where clarity and reliability are paramount. The visual language evokes a sense of "Blue-Collar Sophistication"—combining the grit of the construction site with the digital precision of a modern architectural firm.

The chosen style is **Corporate / Modern**. It utilizes a systematic approach to density and information hierarchy, ensuring that complex data sets and project timelines remain legible and actionable. The aesthetic is clean and rhythmic, mirroring the organized chaos of a successful construction project through structured grids and high-contrast focal points.

## Colors

The color palette is anchored by **Deep Blue (#003366)**, symbolizing the foundation, stability, and institutional trust of the engineering profession. This color should be used for headers, primary navigation, and structural UI elements.

**Vibrant Orange (#FF8C00)** serves as the secondary "Energy" color. Drawing inspiration from high-visibility safety gear and heavy machinery, it is reserved strictly for high-priority Call-to-Action (CTA) elements, status indicators for active projects, and interactive highlights.

The neutral palette consists of cool grays and crisp whites. Use whites for primary surfaces and light grays for background containment to maintain a "B2B clean" look that prevents eye fatigue during long sessions of data entry or project review.

## Typography

This design system utilizes **Manrope** for headlines to provide a modern, technical, and refined appearance. Its geometric qualities reflect architectural drafting and precision. **Inter** is utilized for body text and UI labels due to its exceptional legibility in technical contexts and its seamless fallback to high-quality Thai system fonts like Sarabun or Kanit, ensuring a localized experience for Thai engineering teams.

Maintain a strict vertical rhythm by adhering to the defined line heights. Use heavier weights (600+) for headlines to establish a clear information hierarchy. Body text should remain at a 400 weight for maximum readability in dense reports.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** model for desktop environments to mirror the stability of engineering blueprints. A 12-column grid system with a 24px gutter provides the necessary structure for complex dashboards and equipment catalogs.

Spacing is governed by an 8px base unit. All margins, padding, and gaps between elements must be multiples of this unit (8, 16, 24, 32, etc.). This mathematical consistency reinforces the brand's commitment to precision and order. Large "Stack" values should be used to separate distinct project phases or sections within a page, while smaller units manage the internal relationships of component groups.

## Elevation & Depth

To maintain a professional and "industrial" feel, this design system avoids excessive shadows or decorative blurs. Instead, it utilizes **Tonal Layers** and **Low-Contrast Outlines**.

Depth is communicated through subtle surface shifts. Use a light gray background for the page body, and "lift" content areas by placing them on white cards with a fine 1px border (#E2E8F0). When shadows are absolutely necessary (e.g., on floating action buttons or modal overlays), use a "hardened" shadow: low-blur, low-opacity, and shifted slightly downward to mimic the direct overhead lighting found in a workshop or site office.

## Shapes

The shape language is "Soft-Industrial." By using a **Level 1 (Soft)** roundedness (4px), the UI feels engineered rather than organic. This subtle rounding removes the aggressive sharpness of pure 0px corners—making the interface feel modern and approachable—while maintaining the rigid, rectangular nature of construction materials and structural beams.

Apply this 4px radius consistently to all buttons, input fields, and cards. Use "pill" shapes (Level 3) only for status badges or tags to make them stand out as distinct, non-structural metadata.

## Components

### Buttons
Primary buttons use the Deep Blue background with white text. The "Action" CTA (e.g., "Request Quote" or "Submit Bid") uses the Vibrant Orange background with a high-contrast label. All buttons feature a 4px corner radius and a subtle hover state that darkens the background color by 10%.

### Input Fields
Inputs are framed by a 1px solid gray border. Upon focus, the border transitions to Deep Blue with a subtle 2px outer glow in a semi-transparent blue. This reinforces the focus on data accuracy.

### Cards
Cards are the primary container for project information. They must have a white background, a 1px light gray border, and no shadow in their default state. On hover, a card may lift slightly with a soft, short shadow to indicate interactivity.

### Chips & Lists
Lists should prioritize high density for technical specifications. Chips used for status (e.g., "In Progress," "Completed") should use muted background tints of the status color with a darker text version of that same color for maximum legibility.

### Progress Indicators
Given the construction context, progress bars are critical. Use a Deep Blue track with a Vibrant Orange fill to denote completion, ensuring the user's eye is immediately drawn to the "Energy" of the work being done.