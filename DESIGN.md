---
name: Nocturne Guard
colors:
  surface: '#0f131c'
  surface-dim: '#0f131c'
  surface-bright: '#353943'
  surface-container-lowest: '#0a0e17'
  surface-container-low: '#181b25'
  surface-container: '#1c1f29'
  surface-container-high: '#262a34'
  surface-container-highest: '#31353f'
  on-surface: '#dfe2ef'
  on-surface-variant: '#c7c4d7'
  inverse-surface: '#dfe2ef'
  inverse-on-surface: '#2c303a'
  outline: '#908fa0'
  outline-variant: '#464554'
  surface-tint: '#c0c1ff'
  primary: '#c0c1ff'
  on-primary: '#1000a9'
  primary-container: '#8083ff'
  on-primary-container: '#0d0096'
  inverse-primary: '#494bd6'
  secondary: '#d0bcff'
  on-secondary: '#3c0091'
  secondary-container: '#571bc1'
  on-secondary-container: '#c4abff'
  tertiary: '#7bd0ff'
  on-tertiary: '#00354a'
  tertiary-container: '#009bd1'
  on-tertiary-container: '#002d40'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e1e0ff'
  primary-fixed-dim: '#c0c1ff'
  on-primary-fixed: '#07006c'
  on-primary-fixed-variant: '#2f2ebe'
  secondary-fixed: '#e9ddff'
  secondary-fixed-dim: '#d0bcff'
  on-secondary-fixed: '#23005c'
  on-secondary-fixed-variant: '#5516be'
  tertiary-fixed: '#c4e7ff'
  tertiary-fixed-dim: '#7bd0ff'
  on-tertiary-fixed: '#001e2c'
  on-tertiary-fixed-variant: '#004c69'
  background: '#0f131c'
  on-background: '#dfe2ef'
  surface-variant: '#31353f'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
  code-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 2rem
  gutter-desktop: 3rem
  margin: 1.5rem
  margin-desktop: 4rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system crafts an uncompromising, executive-tier authentication gateway for mission-critical enterprise platforms. It projects authoritative security, calm operational command, and refined digital craftsmanship. The target audience comprises enterprise leaders, engineers, and data custodians who treat software access with intentionality and discretion.

The aesthetic fuses **Minimalism** with restrained **Glassmorphism** and high-precision technical cues:
- **Atmosphere:** Deep midnight environments paired with layered luminescence. Luminous indigo and electric violet optical flares sit softly behind deep obsidian glass planes.
- **Tone:** Unflappable, sophisticated, and technologically pristine.
- **Security Posture:** Polished perimeter lines, cryptographic token micro-details, crisp hardware-key signifiers, and deliberate kinetic feedback instill immediate institutional confidence.

## Colors

The palette operates in a calibrated low-light visual spectrum built on absolute dark foundation tones, elevated by vibrant indigo and violet spectral accents.

- **Primary (`#6366F1` - Electric Indigo):** The focal anchor for primary interactions, active input outlines, and system state confirmation.
- **Secondary (`#8B5CF6` - Luminescent Violet):** Reserved for progressive disclosure, secondary brand signatures, contextual badges, and high-tier biometric/hardware auth prompts.
- **Tertiary (`#38BDF8` - Cyan Stream):** Applied sparingly for high-trust security cues, encrypted tunnel indicators, and passkey activity badges.
- **Neutral Foundation (`#090D16` - Deep Midnight Obsidian):** The foundational abyss canvas tone. Derived shades structure surface glass planes:
  - Surface Underlay: `#060910`
  - Frosted Card Base: `rgba(15, 23, 42, 0.65)`
  - Elevated Popovers & Dialogs: `rgba(20, 30, 55, 0.85)`
  - Border Rings / Ghost Strokes: `rgba(255, 255, 255, 0.08)` to `rgba(99, 102, 241, 0.25)`
  - Text Neutral Primary: `#F8FAFC`
  - Text Neutral Muted: `#94A3B8`

## Typography

The typography pairings contrast geometric warmth with neutral engineering legibility.

- **Display & Headings:** `Plus Jakarta Sans` provides structural elegance and contemporary authority without feeling overly playful. Tight negative letter spacing (`-0.025em` to `-0.01em`) maintains dense, editorial cohesion.
- **Body & Controls:** `Inter` is chosen for input fields, data streams, helper states, and validation strings due to its tall x-height and optical legibility at micro scales.
- **Micro-Labels & Monospace Accents:** Micro-caps and audit strings rely on `label-sm` with wider letter spacing (`0.04em`) to establish crisp hierarchy against deep obsidian backgrounds.

## Layout & Spacing

The architecture operates on an asymmetric **two-column desktop layout** contained within a strict 8px harmonic spacing system.

- **Desktop (min-width: 1024px):**
  - **Left Showcase Canvas (55% width):** Ambient interactive portal featuring generative particle mesh, live node health, enterprise tenant verification, and subtle background glow fields.
  - **Right Authentication Pane (45% width):** Centered floating glass panel hosting the interaction flow. Maximum container width is constrained to `440px` for optimal eye tracking.
  - **Gutter:** `3rem` separation between spatial bounds, ensuring breathing room between dynamic brand graphics and security controls.
- **Tablet (768px – 1023px):** Collapses into a centered single column with a compacted vertical banner header showcasing ambient brand art.
- **Mobile (<768px):** The ambient pane is suppressed entirely in favor of an uninterrupted, high-efficiency vertical stack with `1.5rem` outer canvas padding.

## Elevation & Depth

Visual hierarchy uses physical glass layering over volumetric ambient light rather than traditional drop shadows.

- **Level 0 (Abyss Foundation):** `#090D16` solid dark tone integrated with subtle SVG grid lines (opacity 0.03) and radial color gradients (`#6366F1` at 8% opacity and `#8B5CF6` at 5% opacity).
- **Level 1 (Frosted Glass Container):**
  - Background: `rgba(15, 23, 42, 0.65)`
  - Backdrop Filter: `blur(20px) saturate(180%)`
  - Border Ring: `1px solid rgba(255, 255, 255, 0.08)`
  - Shadow: `0 24px 48px -12px rgba(0, 0, 0, 0.65), 0 0 0 1px rgba(255, 255, 255, 0.05) inset`
- **Level 2 (Active Elements & Focus Glass):**
  - Background: `rgba(30, 41, 69, 0.75)`
  - Border Ring: `1px solid rgba(99, 102, 241, 0.45)`
  - Glow: `0 0 20px rgba(99, 102, 241, 0.2)`
- **Level 3 (Modal / Biometric Hardware Overlays):**
  - Background: `rgba(10, 15, 28, 0.92)`
  - Backdrop Filter: `blur(32px)`
  - Border Ring: `1px solid rgba(139, 92, 246, 0.35)`
  - Shadow: `0 32px 64px -16px rgba(0, 0, 0, 0.8), 0 0 32px rgba(139, 92, 246, 0.15)`

## Shapes

The system standardizes on **Rounded (Level 2)** geometry:
- Standard elements (inputs, interactive buttons, list rows) maintain an outer curvature of `0.5rem` (8px).
- Intermediate cards, segmented controls, and internal sub-panels use `rounded-lg` (`1rem` / 16px).
- Main authentication viewport containers employ `rounded-xl` (`1.5rem` / 24px) to softly frame the frosted surface against the backdrop.
- Avatars, status pips, and standalone cryptographic key indicators maintain a full circle (`rounded-full`).

## Components

### Buttons
- **Primary Action (Log In / Authorize):** Gradient fill from `#6366F1` to `#4F46E5` with an internal top-highlight ring (`1px solid rgba(255, 255, 255, 0.2) inset`). Hover state triggers a subtle scale transform (`1.01`) and increases ambient violet glow (`0 0 24px rgba(99, 102, 241, 0.4)`).
- **Secondary (SSO / SAML Identity):** Frosted glass base (`rgba(255, 255, 255, 0.04)`), low-contrast perimeter border (`rgba(255, 255, 255, 0.1)`), crisp 14px typography. Hover elevates surface to `rgba(255, 255, 255, 0.08)` and border to `rgba(255, 255, 255, 0.2)`.
- **Tertiary / Ghost (Forgot Password / Magic Link):** Clean text button with zero background. Shifts from `#94A3B8` to `#F8FAFC` on hover with an underline animation anchored from center.

### Input Fields
- **Container:** Dark recess surface (`rgba(7, 11, 20, 0.6)`), 44px height, `0.5rem` radius.
- **Border Treatment:** Baseline border of `1px solid rgba(255, 255, 255, 0.1)`.
- **Focus Transition:** Border shifts immediately to `#6366F1` accompanied by a dual-ring focus glow (`0 0 0 3px rgba(99, 102, 241, 0.25)`).
- **Accessory Slots:** Right-aligned credential reveal controls, passkey shortcuts, and CAPS-lock indicators styled in `#94A3B8`.

### Checkboxes & Selection Controls
- **Remember Session Checkbox:** 18px square with a `4px` corner radius. Unchecked state features an obsidian fill with a 1px white border at 15% opacity. Checked state fills with `#6366F1`, displaying a sharp, centered white vector checkmark.

### Security Badges & Chips
- **TLS / Compliance Chips:** Pill-shaped status indicators with 11px uppercase typography, a pulsing emerald or cyan status dot (`#10B981` / `#38BDF8`), and a faint perimeter glow indicating SOC2 / ISO-27001 session shielding.

### Authentication Cards
- Structural framing built via `rounded-xl`, combining the frosted glass formula with a gradient border mask (`linear-gradient(180deg, rgba(255, 255, 255, 0.12), rgba(255, 255, 255, 0.02))`).

### MFA Verification Code Blocks
- Six discrete square input tiles (`48px x 56px`), centered tabular figures in `Plus Jakarta Sans`, active index indicated via pulsing bottom indicator line in Luminescent Violet (`#8B5CF6`).