---
name: Institutional Emerald
colors:
  surface: '#f8f9ff'
  surface-dim: '#c4dcfd'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eef4ff'
  surface-container: '#e4efff'
  surface-container-high: '#dbe9ff'
  surface-container-highest: '#d1e4ff'
  on-surface: '#011d35'
  on-surface-variant: '#3e4941'
  inverse-surface: '#19324b'
  inverse-on-surface: '#e9f1ff'
  outline: '#6e7a71'
  outline-variant: '#bdcabf'
  surface-tint: '#006d44'
  primary: '#006a42'
  on-primary: '#ffffff'
  primary-container: '#168556'
  on-primary-container: '#f6fff6'
  inverse-primary: '#77daa4'
  secondary: '#2060a3'
  on-secondary: '#ffffff'
  secondary-container: '#80b6fe'
  on-secondary-container: '#004681'
  tertiary: '#795600'
  on-tertiary: '#ffffff'
  tertiary-container: '#956e19'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#93f7be'
  primary-fixed-dim: '#77daa4'
  on-primary-fixed: '#002111'
  on-primary-fixed-variant: '#005232'
  secondary-fixed: '#d4e3ff'
  secondary-fixed-dim: '#a4c9ff'
  on-secondary-fixed: '#001c39'
  on-secondary-fixed-variant: '#004883'
  tertiary-fixed: '#ffdea6'
  tertiary-fixed-dim: '#f0bf64'
  on-tertiary-fixed: '#271900'
  on-tertiary-fixed-variant: '#5e4200'
  background: '#f8f9ff'
  on-background: '#011d35'
  surface-variant: '#d1e4ff'
typography:
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Libre Franklin
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Libre Franklin
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Libre Franklin
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Libre Franklin
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
  unit: 8px
  container-max-width: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style
The design system is engineered for the Lúa Hóa financial workshop, targeting a sophisticated audience that values academic rigor and professional heritage. The brand personality is authoritative yet approachable, blending the gravitas of institutional finance with a modern, clean-lined aesthetic. 

The visual style is **Corporate / Modern** with an **Editorial** edge. It leverages high-quality typography and a restricted color palette to evoke an emotional response of stability, wisdom, and premium exclusivity. The interface prioritizes clarity and generous whitespace to ensure complex financial concepts remain legible and digestible, reflecting the precision of a high-end educational environment.

## Colors
The palette is rooted in traditional institutional colors, updated for digital clarity.

- **Primary Emerald (#1F8A5B):** Used for growth-oriented accents and primary calls to action. It signifies prosperity and stability.
- **Secondary Corporate Blue (#2563A6):** Applied to secondary interactive elements and information highlights to provide a professional counterpoint to the Emerald.
- **Tertiary Soft Gold (#D6A84F):** Reserved for subtle highlights, accents, and high-value status indicators.
- **Deep Navy (#102A43):** The primary color for text and heavy structural elements, providing deep contrast against the ivory background.
- **Surface Ivory (#FAFAF6):** A warm, off-white foundation that reduces eye strain and distinguishes the product from generic "pure white" corporate tools.

## Typography
The typographic hierarchy establishes an academic and trustworthy tone. 

**Playfair Display** is used for headlines to provide a literary and prestigious feel. It should be used with tight letter-spacing for large titles. **Libre Franklin** provides a neutral, highly legible contrast for body text and functional UI labels, ensuring that data-heavy financial content is easy to read. 

Use **Body-lg** for introductory paragraphs and **Label-md** (with uppercase styling) for category headers or section titles above headlines to reinforce the structured, institutional layout.

## Layout & Spacing
This design system utilizes a **Fixed Grid** model for desktop to maintain the feel of a structured publication, transitioning to a fluid model for mobile.

- **Grid:** A 12-column grid with 24px gutters.
- **Margins:** Generous 64px outer margins on desktop to create a centered, focused reading experience. Mobile margins are reduced to 20px.
- **Rhythm:** An 8px linear scale governs all padding and margins. Vertical rhythm is critical; maintain 48px to 64px between major sections to emphasize the premium use of whitespace.

## Elevation & Depth
Depth is achieved through **Tonal Layers** and **Low-Contrast Outlines** rather than aggressive shadows.

- **Surfaces:** Secondary containers use a slightly darker ivory or a very faint tint of the secondary blue to distinguish sections.
- **Outlines:** Use 1px borders in Deep Navy at 10% opacity for cards and input fields.
- **Shadows:** When necessary (e.g., for elevated cards or menus), use an "Ambient Shadow"—a very soft, diffused shadow with a 15% opacity of Deep Navy, offset primarily on the Y-axis.

## Shapes
The shape language is **Soft** and restrained. Elements feature a 0.25rem (4px) corner radius to soften the clinical nature of finance while maintaining a sharp, professional precision. Larger components like cards may use 0.5rem (8px) for a subtle modern touch. Interactive elements like buttons should never be fully rounded (pill-shaped) to preserve the institutional aesthetic.

## Components
- **Buttons:** Primary CTA buttons use Emerald (#1F8A5B) with white text. Secondary actions use Navy (#102A43) with white text. Tertiary buttons are ghost-style with a Navy outline or text-only.
- **Input Fields:** Use the Ivory surface with a subtle 1px border. Focus states transition the border to Emerald. Labels should always be visible above the field using the `label-sm` style.
- **Cards:** White or Ivory backgrounds with a 1px Navy (10% opacity) border. Use for workshop modules or financial data points.
- **Lists:** Use custom bullet points in Soft Gold (#D6A84F) for an editorial touch.
- **Chips:** Small, rectangular tags with 2px radius. Use Corporate Blue backgrounds at 10% opacity with Blue text for category tags.
- **Progress Indicators:** Financial tracking should use a thin 4px bar in Emerald to represent completion or growth.