---
name: Lucky Exam Charm
colors:
  surface: '#fff8f5'
  surface-dim: '#e1d8d3'
  surface-bright: '#fff8f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fcf2ed'
  surface-container: '#f6ece7'
  surface-container-high: '#f0e6e1'
  surface-container-highest: '#eae1dc'
  on-surface: '#1f1b18'
  on-surface-variant: '#5b403f'
  inverse-surface: '#342f2c'
  inverse-on-surface: '#f9efea'
  outline: '#8f6f6e'
  outline-variant: '#e4bebc'
  surface-tint: '#bb152c'
  primary: '#b7102a'
  on-primary: '#ffffff'
  primary-container: '#db313f'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb3b1'
  secondary: '#864e5a'
  on-secondary: '#ffffff'
  secondary-container: '#feb6c4'
  on-secondary-container: '#7a4450'
  tertiary: '#705d00'
  on-tertiary: '#ffffff'
  tertiary-container: '#c9a900'
  on-tertiary-container: '#4c3f00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad8'
  primary-fixed-dim: '#ffb3b1'
  on-primary-fixed: '#410007'
  on-primary-fixed-variant: '#92001c'
  secondary-fixed: '#ffd9df'
  secondary-fixed-dim: '#fbb3c1'
  on-secondary-fixed: '#360c19'
  on-secondary-fixed-variant: '#6b3743'
  tertiary-fixed: '#ffe16d'
  tertiary-fixed-dim: '#e9c400'
  on-tertiary-fixed: '#221b00'
  on-tertiary-fixed-variant: '#544600'
  background: '#fff8f5'
  on-background: '#1f1b18'
  surface-variant: '#eae1dc'
typography:
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '800'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '500'
    lineHeight: '1.6'
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 40px
  container-padding: 20px
  card-gap: 16px
---

## Brand & Style

This design system is built to provide emotional support, warmth, and a sense of "good luck" to students and learners. The brand personality is encouraging, gentle, and whimsical, aiming to reduce exam-related anxiety through a "healing" aesthetic.

The visual style is a blend of **Tactile Softness** and **Illustrative Minimalism**. It avoids the coldness of traditional academic software in favor of a playful, friendly environment. Key stylistic hallmarks include generous whitespace, organic decorative motifs (like cat paws and stars), and a layering strategy that makes elements feel like physical charms or paper cards. The presence of character-driven elements—specifically the cats Pudding and Cheetah—adds a relatable, companionable layer to the user experience.

## Colors

The palette is rooted in traditional symbols of luck and celebration, softened for a contemporary digital feel.

- **Primary (Festive Red):** Used for high-emphasis actions, critical headings, and the iconic "Red Envelope" element. It conveys energy and success.
- **Secondary (Soft Petal Pink):** The primary background and accent color. It creates a calming, "healing" environment that reduces stress.
- **Tertiary (Sparkle Gold):** Reserved for decorative highlights, stars, and "winning" moments. It adds a premium, "lucky" feel without being overwhelming.
- **Neutral (Warm Cream):** Replaces harsh whites to maintain a soft, paper-like texture for cards and backgrounds.

Surface colors should prioritize low-contrast transitions between cream and pink to maintain the "soft" visual hierarchy.

## Typography

This design system utilizes **Plus Jakarta Sans** for headings and labels to take advantage of its modern, rounded terminals which reinforce the friendly tone. For longer passages of encouraging text, **Be Vietnam Pro** provides excellent readability with a warm, contemporary character.

Typography should be treated with generous line-heights to ensure the interface feels breezy and unhurried. Use "headline-lg" primarily for the "Charm" results and "body-lg" for the personalized messages from Pudding and Cheetah.

## Layout & Spacing

The layout philosophy follows a **Fixed-Width Centered** model, mimicking the proportions of a physical charm or a mobile handset. This focuses the user's attention on the "lucky" content.

A 4px baseline rhythm is used to maintain consistency. Spacing is intentionally generous—especially around illustrative elements—to prevent the UI from feeling "cluttered" or "stressful." Use `xl` spacing for major section breaks and `md` for internal card padding.

## Elevation & Depth

Hierarchy is achieved through **Ambient Shadows** and **Tonal Layering**. 

- **Level 1 (Base):** The warm neutral background.
- **Level 2 (Cards):** Soft, diffused shadows with a slight red/pink tint (e.g., `rgba(230, 57, 70, 0.08)`) to make cards appear as if they are floating gently above the surface.
- **Level 3 (Interactive):** Elements like the Red Envelope or Primary Buttons use slightly deeper shadows to invite interaction.

Avoid harsh black shadows; all shadows must be "tinted" with the primary or secondary brand colors to maintain the warm, cohesive atmosphere.

## Shapes

The shape language is defined by **High Circularity**. There are no sharp corners in this design system.

- **Standard Elements:** Use `rounded-lg` (1rem) for most cards and containers.
- **Interactive Elements:** Use `rounded-xl` or full pill-shapes for buttons and chips to make them feel "squishy" and tactile.
- **Decorative Motifs:** Illustrations of hearts, stars, and cat paws should follow organic, hand-drawn curves rather than geometric precision.

## Components

### Buttons
Buttons are pill-shaped and utilize a subtle "lift" effect on hover. The primary action button (e.g., "Open Envelope") should use the Festive Red background with white or gold text.

### Lucky Cards
The central component of the design system. Cards feature a thick "rounded-xl" corner, a soft secondary-color border, and are often adorned with cat paw prints in the corners. They should transition in with a soft "fade and float" animation.

### Decorative Embellishments
Include small, lightweight SVG illustrations of stars and hearts that can be scattered around the main container. These should use the Tertiary Gold and Secondary Pink colors.

### Character Avatars
Pudding and Cheetah are presented in circular or soft-square frames. In result states, their avatars should be paired with speech bubbles using the "body-md" typography to deliver personalized encouragement.

### Red Envelope (Specialty Component)
A skeuomorphic-lite element with a visible "seal" (using the Tertiary Gold). It serves as the primary gateway to the "Charm" experience.