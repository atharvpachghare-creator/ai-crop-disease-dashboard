---
name: AgroScan AI
colors:
  surface: '#fbf9f9'
  surface-dim: '#dbdad9'
  surface-bright: '#fbf9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f3'
  surface-container: '#efeded'
  surface-container-high: '#e9e8e7'
  surface-container-highest: '#e3e2e2'
  on-surface: '#1b1c1c'
  on-surface-variant: '#40493d'
  inverse-surface: '#303031'
  inverse-on-surface: '#f2f0f0'
  outline: '#707a6c'
  outline-variant: '#bfcaba'
  surface-tint: '#1b6d24'
  primary: '#0d631b'
  on-primary: '#ffffff'
  primary-container: '#2e7d32'
  on-primary-container: '#cbffc2'
  inverse-primary: '#88d982'
  secondary: '#126d27'
  on-secondary: '#ffffff'
  secondary-container: '#9cf49c'
  on-secondary-container: '#19722b'
  tertiary: '#335f3a'
  on-tertiary: '#ffffff'
  tertiary-container: '#4b7850'
  on-tertiary-container: '#ccfecd'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#a3f69c'
  primary-fixed-dim: '#88d982'
  on-primary-fixed: '#002204'
  on-primary-fixed-variant: '#005312'
  secondary-fixed: '#9ff79f'
  secondary-fixed-dim: '#83da85'
  on-secondary-fixed: '#002105'
  on-secondary-fixed-variant: '#005318'
  tertiary-fixed: '#bdefbe'
  tertiary-fixed-dim: '#a2d3a4'
  on-tertiary-fixed: '#002109'
  on-tertiary-fixed-variant: '#24502c'
  background: '#fbf9f9'
  on-background: '#1b1c1c'
  surface-variant: '#e3e2e2'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Plus Jakarta Sans
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
  sm: 12px
  md: 16px
  lg: 24px
  xl: 32px
  gutter: 16px
  margin-mobile: 20px
  margin-desktop: 48px
---

## Brand & Style

The brand identity is rooted in the intersection of agricultural heritage and cutting-edge artificial intelligence. It must evoke a sense of "Scientific Vitality"—combining the organic reliability of nature with the precision of advanced technology. The design system targets a diverse demographic, from field-based farmers requiring high legibility to researchers demanding data density.

The visual style is a hybrid of **Modern Corporate** and **Glassmorphism**. It leverages the structured hierarchy of Material Design 3 and the refined translucency found in Apple’s Human Interface Guidelines. The interface prioritizes high accessibility, utilizing generous white space to reduce cognitive load during critical crop diagnostic tasks. The emotional response should be one of immediate trust, professional competence, and optimism.

## Colors

The palette is monochromatic-adjacent, utilizing varying depths of green to establish a strong thematic connection to agriculture. 

- **Primary Green (#2E7D32):** Used for key actions and structural elements to convey stability.
- **Secondary & Accent Greens:** Employed for illustrative accents, progress indicators, and subtle highlights.
- **Background (#F8FFF5):** A tinted off-white that reduces eye strain in bright outdoor sunlight compared to pure white.
- **Semantic Colors:** Strictly reserved for status feedback—Red for disease detection (Danger), Amber for nutrient deficiencies (Warning), and Emerald for healthy crops (Success).

## Typography

The typography system balances character with utility. **Plus Jakarta Sans** (substituted for Google Sans for its contemporary geometric terminals) provides an approachable but authoritative voice for headings. **Inter** is utilized for all functional text, chosen for its exceptional legibility in data-heavy agricultural reports and its ability to remain clear at small scales.

For mobile layouts, headline sizes scale down to prevent excessive line-breaking, while body text remains large (minimum 16px) to ensure accessibility for users in varying field conditions.

## Layout & Spacing

This design system employs a **Fluid Grid** model based on an 8px square baseline, with 4px half-steps for fine-tuning. 

- **Mobile:** A 4-column grid with 20px outside margins and 16px gutters.
- **Tablet/Desktop:** A 12-column centered grid with a maximum content width of 1140px.
- **Vertical Rhythm:** Spacing between sections should be generous (24px or 32px) to maintain the premium, airy feel. Stacked elements within cards use 8px or 12px increments to keep related information tightly grouped.

## Elevation & Depth

Hierarchy is established through a combination of **Tonal Layering** and **Ambient Shadows**.

1.  **Base Layer:** The off-white green background (#F8FFF5).
2.  **Card Layer:** White surfaces (#FFFFFF) with a soft, ultra-diffused shadow (0px 8px 24px rgba(46, 125, 50, 0.08)) to create a gentle lift without looking heavy.
3.  **Glassmorphism:** Overlays, navigation bars, and bottom sheets use a backdrop blur (20px) with 85% opacity white fills. This maintains context of the field imagery behind the UI.
4.  **Floating Action Buttons (FAB):** Higher elevation with a slightly more saturated shadow to signify primary interaction (scanning).

## Shapes

The shape language is organic and soft, reflecting the natural subject matter. 

- **Primary Cards:** Use a 24px corner radius (`rounded-xl` equivalent) to feel friendly and modern.
- **Buttons:** Use fully rounded (pill-shaped) corners to provide a clear tactile target for thumb-driven mobile interaction.
- **Input Fields:** Use 12px corner radius to balance the softness of cards with the structured nature of data entry.
- **Media:** Photography of leaves and crops should always be clipped to the container's 24px radius to maintain system harmony.

## Components

- **Buttons:** Primary buttons are pill-shaped, filled with Primary Green, and use White Label-MD text. Secondary buttons use an outline of Primary Green with a subtle tint fill.
- **Diagnostic Cards:** Large 24px rounded containers. They should include a "Glass" header area if overlaid on crop images.
- **Chips:** Used for "Crop Type" or "Severity" tags. Use Primary-Light (#A5D6A7) backgrounds with Primary-Dark text for high contrast.
- **Input Fields:** Filled style (Material 3 inspired) with a subtle bottom stroke and 12px top-corner rounding.
- **The Scanner (FAB):** A large, circular button in the bottom center containing a camera icon. It uses a slight glow effect in Primary Green to draw the eye.
- **Progress Indicators:** Use the Secondary Green (#66BB6A) with rounded caps for a softer, more organic feel during AI processing.