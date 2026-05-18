---
name: Ghibli-Inspired Narrative
colors:
  surface: '#f9faf0'
  surface-dim: '#d9dbd1'
  surface-bright: '#f9faf0'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f5ea'
  surface-container: '#edefe5'
  surface-container-high: '#e7e9df'
  surface-container-highest: '#e2e3d9'
  on-surface: '#1a1c16'
  on-surface-variant: '#43493c'
  inverse-surface: '#2e312b'
  inverse-on-surface: '#f0f2e7'
  outline: '#73796b'
  outline-variant: '#c3c9b8'
  surface-tint: '#3e6922'
  primary: '#3c661f'
  on-primary: '#ffffff'
  primary-container: '#548036'
  on-primary-container: '#f9ffed'
  inverse-primary: '#a3d480'
  secondary: '#0c6780'
  on-secondary: '#ffffff'
  secondary-container: '#9ae1ff'
  on-secondary-container: '#09657f'
  tertiary: '#5f5f04'
  on-tertiary: '#ffffff'
  tertiary-container: '#787820'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#bef199'
  primary-fixed-dim: '#a3d480'
  on-primary-fixed: '#0a2100'
  on-primary-fixed-variant: '#27500a'
  secondary-fixed: '#baeaff'
  secondary-fixed-dim: '#89d0ed'
  on-secondary-fixed: '#001f29'
  on-secondary-fixed-variant: '#004d62'
  tertiary-fixed: '#e8e883'
  tertiary-fixed-dim: '#cbcb6a'
  on-tertiary-fixed: '#1d1d00'
  on-tertiary-fixed-variant: '#494900'
  background: '#f9faf0'
  on-background: '#1a1c16'
  surface-variant: '#e2e3d9'
typography:
  display:
    fontFamily: EB Garamond
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: EB Garamond
    fontSize: 28px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-md:
    fontFamily: EB Garamond
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.7'
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.2'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: '8'
  gutter: '24'
  margin-mobile: '16'
  margin-desktop: '64'
  container-max: '1200'
---

## Brand & Style
The design system is rooted in the philosophy of "Ma" (the empty space) and the warmth of hand-painted animation. It evokes a sense of nostalgia, wonder, and environmental harmony, targeting users who value slow-living, storytelling, and craftsmanship. 

The visual style is a hybrid of **Tactile/Skeuomorphic** and **Minimalism**. It avoids the sterile coldness of modern tech in favor of "lived-in" interfaces. Elements should feel like physical artifacts—parchment paper, painted wood, or ceramic tiles—resting on a soft, airy canvas. The emotional response is one of safety, curiosity, and quiet joy.

## Colors
The palette is derived from natural landscapes—meadows, summer skies, and rustic villages. 

- **Primary (Meadow Green):** A soft, desaturated green used for growth-oriented actions and success states. It feels lighter and more organic than a traditional corporate green.
- **Secondary (Sky Blue):** Used for information, links, and calm interactions.
- **Tertiary (Sunflower Yellow):** Used for highlights, warnings, and playful accents.
- **Accent (Terracotta Red):** Reserved for high-priority calls to action or critical alerts.
- **Surface (Cream):** The primary background color, providing a soft, non-fatiguing alternative to pure white.
- **Ink (Deep Charcoal):** Used for all primary text to maintain high legibility with a soft, organic feel.

## Typography
The typography balances the literary elegance of classic European storybooks with the clarity of modern interfaces. 

- **Headlines:** Use EB Garamond for all headings. It should feel authoritative yet organic. For large display text, use medium weights to allow the character of the serifs to shine.
- **Body:** Montserrat provides a clean, open counter-form that ensures readability against textured backgrounds. Generous line-height (1.6+) is mandatory to evoke a sense of "airiness."
- **Captions & Labels:** Use Montserrat in uppercase with slight letter spacing for a refined, organized feel.

## Layout & Spacing
The layout follows a **Fixed Grid** approach for desktop to create a centered, book-like composition, transitioning to a fluid model for mobile devices. 

- **Rhythm:** An 8px base unit drives all padding and margins. 
- **White Space:** Implementation should prioritize "Ma"—intentional empty space. Avoid crowding elements; allow each card or block of text to "breathe" as if it were an illustration on a wide page.
- **Breakpoints:** 
  - Mobile: < 600px (1 column, 16px margins)
  - Tablet: 600px - 1024px (6 columns, 24px margins)
  - Desktop: > 1024px (12 columns, 64px margins)

## Elevation & Depth
Depth in this design system is achieved through **Tonal Layers** and **Soft Ambient Shadows** rather than sharp technical shadows.

- **Surface Tiers:** Use subtle shifts in cream and pale parchment to define hierarchy. Lower surfaces are slightly more saturated; higher surfaces are lighter.
- **Shadows:** Shadows should be extremely diffused (32px+ blur), low opacity (10%), and tinted with a hint of the Earthy Brown color rather than pure black. This mimics the soft falloff of light in a watercolor painting.
- **Texture Overlays:** Apply a very low-opacity grain or paper texture across the entire UI to kill the "digital" flatness of the screen.

## Shapes
Shapes are soft and asymmetrical where possible. 

- **Radius:** Standard components use a 0.5rem (8px) radius. Larger cards and containers should use 1.5rem (24px) to emphasize the approachable nature of the brand.
- **Organic Borders:** For featured elements (like hero images or profile cards), use a CSS `mask-image` or `border-image` that mimics a hand-drawn watercolor stroke or a slightly deckled paper edge. 
- **Icons:** Icons must be monoline or soft-filled, featuring natural motifs (leaves for "success", clouds for "storage", stars for "favorites"). Avoid sharp 90-degree angles in iconography.

## Components
- **Buttons:** Use a pill-shape for primary actions. The hover state should not be a color change, but a "soft glow"—an outer shadow that matches the button's hue (e.g., a soft green glow for primary buttons).
- **Cards:** Cards should have a thin (1px) border in a slightly darker shade of the background color (e.g., Dark Cream) rather than a harsh grey. 
- **Inputs:** Input fields are rectangular with soft rounded corners (8px) and a subtle inner shadow to feel "pressed" into the paper surface.
- **Chips:** Small, highly rounded elements used for tagging, utilizing the secondary Sky Blue and Tertiary Yellow palettes.
- **Modals:** Centered overlays that use a heavy backdrop blur (15px+) to make the background appear like a soft-focus forest or sky, keeping the focus on the content.
- **Lists:** Use custom bullet points, such as small painted leaves or dots, to maintain the whimsical theme.