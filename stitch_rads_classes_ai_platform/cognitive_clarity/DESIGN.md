---
name: Cognitive Clarity
colors:
  surface: '#f9f9ff'
  surface-dim: '#cfdaf2'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eeff'
  surface-container-high: '#dee8ff'
  surface-container-highest: '#d8e3fb'
  on-surface: '#111c2d'
  on-surface-variant: '#434653'
  inverse-surface: '#263143'
  inverse-on-surface: '#ecf1ff'
  outline: '#737784'
  outline-variant: '#c3c6d5'
  surface-tint: '#2559bd'
  primary: '#00327d'
  on-primary: '#ffffff'
  primary-container: '#0047ab'
  on-primary-container: '#a5bdff'
  inverse-primary: '#b1c5ff'
  secondary: '#006875'
  on-secondary: '#ffffff'
  secondary-container: '#00e3fd'
  on-secondary-container: '#00616d'
  tertiary: '#343739'
  on-tertiary: '#ffffff'
  tertiary-container: '#4b4e50'
  on-tertiary-container: '#bcbfc1'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2ff'
  primary-fixed-dim: '#b1c5ff'
  on-primary-fixed: '#001946'
  on-primary-fixed-variant: '#00419e'
  secondary-fixed: '#9cf0ff'
  secondary-fixed-dim: '#00daf3'
  on-secondary-fixed: '#001f24'
  on-secondary-fixed-variant: '#004f58'
  tertiary-fixed: '#e0e3e5'
  tertiary-fixed-dim: '#c4c7c9'
  on-tertiary-fixed: '#191c1e'
  on-tertiary-fixed-variant: '#444749'
  background: '#f9f9ff'
  on-background: '#111c2d'
  surface-variant: '#d8e3fb'
typography:
  headline-xl:
    fontFamily: Hanken Grotesk
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
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
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-margin-mobile: 16px
  container-margin-desktop: 40px
  gutter: 24px
  stack-sm: 12px
  stack-md: 24px
  stack-lg: 48px
---

## Brand & Style

The design system is engineered for an AI-powered educational environment where focus and trust are paramount. The brand personality is **intelligent, organized, and encouraging**, acting as a silent partner in the student's learning journey. 

The aesthetic follows a **Modern Minimalist** approach with a high-contrast focus. It leverages generous whitespace to reduce cognitive load, ensuring that educational content remains the hero. The interface utilizes a "Digital Laboratory" feel—precise and clinical yet welcoming—achieved through sharp typography and a systematic use of vibrant accents to denote AI-driven insights and interactive elements.

## Colors

The palette is anchored by **Deep Cobalt (#0047AB)**, providing a foundation of institutional trust and authority. This is contrasted against a "Spacious White" background strategy using **#F8FAFC** for surface areas to maintain a clean, airy feel.

**Vibrant Cyan (#00E5FF)** serves as the high-energy accent reserved specifically for AI interactions, progress indicators, and primary calls-to-action. This creates a clear mental model for the user: Cyan represents intelligence and forward momentum. Neutrals are cool-toned grays, ensuring a cohesive professional atmosphere without the starkness of pure black.

## Typography

This design system employs a multi-font strategy to balance character with utility. **Hanken Grotesk** is used for headlines to provide a modern, sharp edge that feels contemporary and "tech-forward." **Inter** handles the heavy lifting for educational content, chosen for its exceptional legibility at various sizes and its neutral, professional tone.

For technical data, AI-generated snippets, and UI labels, **Geist** provides a precise, mono-inspired feel that distinguishes system-level information from learning content. Line heights are kept generous (1.5x for body) to facilitate long-form reading sessions without fatigue.

## Layout & Spacing

The design system utilizes a **Mobile-First Fluid Grid**. On mobile devices, a 4-column layout with 16px side margins is standard. As the viewport scales to desktop, the system transitions to a 12-column centered fixed grid (max-width 1280px).

The spacing rhythm is based on a **linear 8px scale**. Vertical stack spacing should be used aggressively to create "focus zones." Critical learning modules should be separated by `stack-lg` to prevent visual clutter. Gutters remain consistent at 24px to ensure distinct separation between cards and content blocks.

## Elevation & Depth

This design system uses **Tonal Layering** combined with **Ambient Shadows** to create a focused hierarchy. 
- **Level 0 (Background):** Solid #F8FAFC.
- **Level 1 (Cards/Modules):** White surface with a 1px border (#E2E8F0) and a very soft, diffused shadow (Offset: 0, 4px; Blur: 20px; Opacity: 4% Black).
- **Level 2 (Interactive/Floating):** White surface with a more pronounced shadow (Offset: 0, 10px; Blur: 30px; Opacity: 8% Cobalt) to suggest interactability.

AI-driven components utilize a subtle **Cyan Inner Glow** (2px, 15% opacity) instead of traditional shadows to signify their unique, "active" status within the platform.

## Shapes

The shape language is defined by "Approachable Precision." The standard `rounded-md` (8px) is applied to all primary containers and input fields, striking a balance between the friendliness of a learning app and the professionalism of a coaching platform. 

Buttons and "AI Insight" chips use `rounded-xl` (24px) to create a softer, more inviting touchpoint for the most frequent interactions. Image containers and video players must strictly adhere to the `rounded-lg` (16px) standard to maintain visual harmony.

## Components

### Buttons
- **Primary:** Deep Cobalt background, white text. Bold, 8px roundedness.
- **AI Action:** Cyan background, Cobalt text. 24px roundedness (pill-shaped) to distinguish from standard actions.
- **Ghost:** Transparent background, Cobalt border and text.

### Input Fields
- **Default State:** White background, 1px Gray-200 border, 8px roundedness.
- **Focus State:** 2px Cobalt border with a soft blue outer glow.
- **AI-Enhanced:** Subtle Cyan left-border (4px) to indicate the AI is assisting with the input.

### Cards
Cards are the primary vessel for educational modules. They feature a clean white background, the Level 1 shadow profile, and 16px internal padding. Headers within cards should use Hanken Grotesk Semi-Bold.

### Progress Indicators
Progress bars use a "Dual-Track" system: a light gray track with a Cyan fill. For AI-recommended pace, a secondary ghost-track in light Cyan is used.

### Chips & Tags
Used for categorization (e.g., "Math", "AI-Generated"). Tags are small, uppercase Geist labels with a light tinted background (e.g., 10% Cobalt for standard, 10% Cyan for AI).