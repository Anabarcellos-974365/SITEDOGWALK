---
name: Canine Trust
colors:
  surface: '#fbf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fbf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae8e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#414750'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0f0'
  outline: '#717881'
  outline-variant: '#c1c7d1'
  surface-tint: '#0a629e'
  primary: '#06619c'
  on-primary: '#ffffff'
  primary-container: '#337ab7'
  on-primary-container: '#ffffff'
  inverse-primary: '#9bcbff'
  secondary: '#835400'
  on-secondary: '#ffffff'
  secondary-container: '#feb959'
  on-secondary-container: '#734a00'
  tertiary: '#006d1b'
  on-tertiary: '#ffffff'
  tertiary-container: '#298732'
  on-tertiary-container: '#fffeff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d0e4ff'
  primary-fixed-dim: '#9bcbff'
  on-primary-fixed: '#001d34'
  on-primary-fixed-variant: '#004a79'
  secondary-fixed: '#ffddb5'
  secondary-fixed-dim: '#feb959'
  on-secondary-fixed: '#2a1800'
  on-secondary-fixed-variant: '#643f00'
  tertiary-fixed: '#99f894'
  tertiary-fixed-dim: '#7edb7b'
  on-tertiary-fixed: '#002204'
  on-tertiary-fixed-variant: '#005312'
  background: '#fbf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
typography:
  display-lg:
    fontFamily: Work Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Work Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Work Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Work Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Work Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Work Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Work Sans
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Work Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 40px
  xl: 64px
  gutter: 24px
  margin-mobile: 16px
  container-max: 1200px
---

## Brand & Style

The design system is built on a foundation of reliability, warmth, and straightforward utility. It targets pet owners and caregivers who value transparency and professional standards. The visual style follows a **Corporate Modern** approach—striking a balance between the clinical efficiency of a service platform and the approachability of a local community hub.

The aesthetic utilizes clean lines, generous white space, and a systematic card-based architecture. To maintain a sense of friendliness, we move away from sharp edges toward soft, approachable corners. The brand identity is anchored by its silhouette assets, which should always be used as high-contrast anchors in headers or footers to reinforce the "pet-first" nature of the product.

## Colors

This design system uses a logic-driven color palette to guide users through the service funnel:

*   **Primary (Pet-Care Blue):** Used for structural elements, headers, and navigation anchors. It evokes stability and professionalism.
*   **Secondary (Highlight Orange):** Reserved for information badges, warning states, and high-interest highlights that require user attention without being a "success" state.
*   **Tertiary (Success Green):** Strictly for final conversion actions, confirmation messages, and positive status indicators (e.g., "Payment Completed").
*   **Neutral (Foundation):** A range of greys from #333333 for text to #F9F9F9 for background surfaces, ensuring high legibility and a clean canvas.

## Typography

The design system utilizes **Work Sans** across all levels to ensure a grounded, professional, and highly legible experience. 

*   **Headlines:** Use Bold and Semi-Bold weights to create a strong visual hierarchy. Large headers in Blue or Black define the start of new sections.
*   **Body Text:** Standardized at 16px for optimal readability in long-form content like contracts or service descriptions.
*   **Labels:** Small, uppercase labels are used for "overlines" (e.g., "CONTRATANTE") to categorize sections without adding visual weight.

## Layout & Spacing

This design system follows a **Fixed Grid** model for desktop to ensure content remains centered and scannable, transitioning to a **Fluid Grid** for mobile devices.

*   **Desktop:** A 12-column grid with a 1200px max-width. Margins are flexible, but gutters are fixed at 24px.
*   **Tablet:** An 8-column grid with 24px margins.
*   **Mobile:** A 4-column grid with 16px side margins. 

The vertical rhythm is based on an 8px base unit. Component padding should lean towards "spacious" to facilitate easy touch targets on mobile for pet owners on the move.

## Elevation & Depth

We utilize **Tonal Layers** and **Low-Contrast Outlines** rather than heavy shadows to maintain a "clean paper" feel.

*   **Surface Level 0 (Background):** Pure white or ultra-light grey (#F5F7FA).
*   **Surface Level 1 (Cards/Containers):** Pure white with a 1px border (#E1E4E8).
*   **Interactive Elevation:** Only primary buttons and active candidate cards receive a soft, ambient shadow (10% opacity black, 8px blur) to indicate "lift" and interactivity.
*   **Section Headers:** Use solid color blocks (Primary Blue) to anchor the top of pages, creating depth through color blocking rather than physical shadows.

## Shapes

The shape language is **Soft**. This choice maintains professional rigor while feeling more contemporary than the original sharp-edged source images.

*   **Standard (0.25rem):** Used for input fields and small buttons.
*   **Large (0.5rem):** Used for candidate listing cards and main container sections.
*   **Extra Large (0.75rem):** Used for modal dialogs and "Pet Profile" images to emphasize the friendly nature of the brand.

## Components

### Buttons
*   **Primary Action:** Solid Primary Blue with white text. Rounded (0.25rem).
*   **Success Action:** Solid Tertiary Green. Used for "Select Candidate" or "Confirm Payment."
*   **Outline/Cancel:** Ghost buttons with a Primary Blue border or simple text links for secondary navigation like "Voltar."

### Cards
*   **Candidate Cards:** White background, 1px grey border, 0.5rem corner radius. Include a small circular avatar placeholder and left-aligned text for professional details.
*   **Feature Cards:** Used in landing pages; include a Secondary Orange icon or header to differentiate services.

### Form Fields
*   **Inputs:** Full-width by default in mobile, stacked vertically. Use 16px padding and a light grey border that turns Primary Blue on focus. Labels should be placed above the input field, never inside as placeholders.

### Progress Indicators
*   **Steps:** A horizontal line with numbered circles, using Primary Blue for completed steps and light grey for pending ones.

### Brand Integration
*   **Silhouette Icons:** The dog silhouette must be placed in the top right of main containers or centered in empty states to maintain brand consistency.