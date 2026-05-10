---
name: Obsidian & Gold Minimalist
colors:
  surface: '#121414'
  surface-dim: '#121414'
  surface-bright: '#38393a'
  surface-container-lowest: '#0d0f0f'
  surface-container-low: '#1a1c1c'
  surface-container: '#1e2020'
  surface-container-high: '#282a2b'
  surface-container-highest: '#333535'
  on-surface: '#e2e2e2'
  on-surface-variant: '#c4c7c7'
  inverse-surface: '#e2e2e2'
  inverse-on-surface: '#2f3131'
  outline: '#8e9192'
  outline-variant: '#444748'
  surface-tint: '#c9c6c5'
  primary: '#c9c6c5'
  on-primary: '#313030'
  primary-container: '#0a0a0a'
  on-primary-container: '#7b7979'
  inverse-primary: '#5f5e5e'
  secondary: '#e9c176'
  on-secondary: '#412d00'
  secondary-container: '#604403'
  on-secondary-container: '#dab36a'
  tertiary: '#c8c6c5'
  on-tertiary: '#303030'
  tertiary-container: '#0a0a0a'
  on-tertiary-container: '#7a7979'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c9c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#ffdea5'
  secondary-fixed-dim: '#e9c176'
  on-secondary-fixed: '#261900'
  on-secondary-fixed-variant: '#5d4201'
  tertiary-fixed: '#e4e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1b1c1c'
  on-tertiary-fixed-variant: '#474746'
  background: '#121414'
  on-background: '#e2e2e2'
  surface-variant: '#333535'
typography:
  display-xl:
    fontFamily: Noto Serif
    fontSize: 72px
    fontWeight: '400'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.1em
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
  gutter: 32px
  section-padding: 120px
---

## Brand & Style

The design system is rooted in the concept of "Quiet Luxury," prioritizing restraint, precision, and an atmosphere of clinical excellence. It targets a discerning clientele seeking transformation through subtle, natural-looking artistry. The emotional response is one of immediate relief and deep-seated trust, achieved through a "less is more" approach.

The visual style is a blend of **Minimalism** and **Modern Corporate**, utilizing expansive dark space to create an aura of exclusivity. It avoids the clutter of traditional medical sites, instead opting for a gallery-like experience where the work speaks for itself. Every element is intentional, reflecting the meticulous nature of scalp micropigmentation.

## Colors

The palette is anchored in **Deep Obsidian Black** (#0A0A0A) to establish a premium, high-contrast foundation that mimics the depth of natural hair follicles. **Charcoal Gray** (#262626) is used for secondary surfaces to provide subtle depth without breaking the dark mode immersion.

**Muted Gold** (#C5A059) serves as the primary accent color, used sparingly for calls to action, borders, and iconography to signify "Gold Standard" quality. Typography primarily uses **Silvered White** (#E5E5E5) to ensure high legibility while maintaining a softer, more sophisticated look than pure white.

## Typography

This design system employs a sophisticated typographic hierarchy. **Noto Serif** is utilized for headlines to evoke a sense of heritage, medical authority, and artisanal craft. Its classic proportions suggest a "bespoke" service rather than a generic procedure.

**Manrope** provides the functional counterpart for body text and labels. Its geometric yet warm construction maintains a clinical clarity that is easy to digest. Large "Display" headings should be used for impact in hero sections, while small, tracked-out uppercase labels are used for category markers and overlines to reinforce the high-end editorial feel.

## Layout & Spacing

The layout follows a **Fixed Grid** model with a generous 12-column structure. To convey "Quiet Luxury," the design system utilizes extreme whitespace (or negative space). Sections are separated by significant vertical padding (120px+) to allow the content to breathe and to prevent the user from feeling rushed.

Content is centered within a 1280px container, with wide 32px gutters that ensure a relaxed, uncrowded reading experience. For mobile viewports, margins are maintained at 24px to ensure the clinical precision of the grid remains intact across all devices.

## Elevation & Depth

In a dark-mode, high-end environment, depth is created through **Tonal Layers** rather than heavy shadows. 
- **Base Level:** Deep Obsidian (#0A0A0A) for the main background.
- **Surface Level:** Charcoal (#1A1A1A) for cards and containers, creating a subtle lift.
- **Accents:** 1px "Hairline" borders in Muted Gold or low-opacity Silver are used to define boundaries without adding visual weight.

Where shadows are necessary (e.g., floating booking buttons), use a long, diffused, 30% opacity black shadow to create a soft "ambient" lift that feels natural and integrated.

## Shapes

The shape language is "Softly Architectural." A **Soft** roundedness level (4px to 8px) is applied to buttons and cards. This slight rounding takes the edge off the "clinical" feel, making the interface feel more welcoming and human-centric, while still appearing sharp and professional.

Photography should use sharp, 0px corners when used in full-width hero sections, but should adopt the 8px (rounded-lg) radius when presented as "Before & After" gallery cards to make them feel like curated portraits.

## Components

### Buttons
Primary buttons are solid Muted Gold with black text, using the `label-sm` typographic style for a compact, intentional look. Secondary buttons are "Ghost" style—transparent with a 1px Gold or Silver border.

### Before & After Slider
A custom component featuring a vertical "lens" divider. This allows users to interact with the high-quality imagery, emphasizing the precision of the SMP results.

### Cards
Feature cards use a Charcoal (#1A1A1A) background with no shadows and a very subtle 1px border. They should have generous internal padding (40px) to maintain the minimalist aesthetic.

### Input Fields
Inputs for consultation forms are minimalist: a single 1px Silver bottom border that turns Gold on focus. Label text should float above the line in a small, tracked-out font.

### Progress Indicators
Used for "The Process" section, these should be thin, elegant lines with small dot markers, reflecting the "dot-by-dot" precision of the scalp micropigmentation treatment itself.