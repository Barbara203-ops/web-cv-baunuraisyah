---
name: Nusantara Executive
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
  secondary: '#006a61'
  on-secondary: '#ffffff'
  secondary-container: '#86f2e4'
  on-secondary-container: '#006f66'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#00174b'
  on-tertiary-container: '#497cff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#89f5e7'
  secondary-fixed-dim: '#6bd8cb'
  on-secondary-fixed: '#00201d'
  on-secondary-fixed-variant: '#005049'
  tertiary-fixed: '#dbe1ff'
  tertiary-fixed-dim: '#b4c5ff'
  on-tertiary-fixed: '#00174b'
  on-tertiary-fixed-variant: '#003ea8'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display:
    fontFamily: Newsreader
    fontSize: 4rem
    fontWeight: '500'
    lineHeight: 4.5rem
    letterSpacing: -0.02em
  display-mobile:
    fontFamily: Newsreader
    fontSize: 2.5rem
    fontWeight: '500'
    lineHeight: 3rem
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Newsreader
    fontSize: 2.5rem
    fontWeight: '600'
    lineHeight: 3rem
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Newsreader
    fontSize: 1.875rem
    fontWeight: '600'
    lineHeight: 2.25rem
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Newsreader
    fontSize: 1.75rem
    fontWeight: '600'
    lineHeight: 2.25rem
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
  title-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.125rem
    fontWeight: '600'
    lineHeight: 1.5rem
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1rem
    fontWeight: '600'
    lineHeight: 1.5rem
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.75rem
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.625rem
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.375rem
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '600'
    lineHeight: 1.25rem
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: 1rem
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system expresses modern Indonesian executive leadership, institutional credibility, and refined intellectual clarity. Designed specifically for professional portfolios spanning finance, Islamic banking, economic consultancy, and executive leadership, the visual tone balances contemporary minimalism with warm, dignified presence.

The aesthetic fuses Corporate Modern precision with warm editorial prestige. It rejects sterile enterprise uniformity in favor of humanized authority—characterized by generous whitespace, deliberate structural alignment, grounded slate neutrals, and luminous emerald accents that evoke stability, ethical growth, and trust. Interactions should feel deliberate, effortless, and poised.

## Colors

The palette leverages a deep navy foundation paired with an ethical emerald signature, supported by tactical slate blues and clean cream-slate surfaces.

- **Primary (`#0F172A` / `#1E293B`)**: Deep Slate Navy. Conveys institutional permanence, academic rigor, and executive gravitas. Used for primary headlines, structural containers, and high-emphasis states.
- **Secondary (`#0D9488` / `#10B981`)**: Ethical Emerald & Teal. Grounded in Islamic economic values of vitality, balance, and growth. Serves as key accents, achievement markers, active verification badges, and positive metrics.
- **Tertiary (`#2563EB`)**: Royal Slate Blue. Applied selectively for interactive hyperlinks, active filter states, and analytical chart highlights.
- **Neutral & Canvas (`#F8FAFC`, `#FFFFFF`, `#E2E8F0`, `#64748B`)**: Surface foundation. `#F8FAFC` forms the muted canvas, layered over by `#FFFFFF` card containers and demarcated with `#E2E8F0` micro-borders for crisp visual separation. Body text relies on `#334155` for high legibility without pure black harshness.

## Typography

The pairing reflects intellectual stature and contemporary readability:

- **Display & Section Headers (Newsreader)**: Delivers an authoritative editorial cadence suitable for executive biographies, thought leadership, and academic citations. Slightly tightened tracking balances the natural expansion of serif letterforms.
- **Body & Functional UI (Plus Jakarta Sans)**: Originating from an Indonesian geometric design perspective, it provides superb rhythm, native support for Indonesian honorifics, formal titles (e.g., *S.E., M.Ec., Ph.D.*), and technical finance terms.
- Use uppercase styling exclusively for micro-labels (`label-sm`), category pills, and verification tags, accompanied by slight letter-spacing (`0.04em`).

## Layout & Spacing

The layout is built on a structured 12-column fluid grid system for desktop and tablet, collapsing to a single-column rhythm on mobile:

- **Desktop (≥ 1024px)**: 12-column layout with a 1200px max content container, 24px (`1.5rem`) gutters, and dynamic outer margins starting at 48px (`3rem`).
- **Tablet (768px – 1023px)**: 8-column layout, 24px gutters, and 32px margins.
- **Mobile (< 768px)**: 4-column layout, 16px (`1rem`) gutters, and 20px (`1.25rem`) lateral padding to maximize reading comfort.

Content reflow prioritizes executive clarity: sidebars (such as bio summaries and download actions) collapse to prominent stacked headers or anchored footers on mobile. Spacing between major content sections must adhere to an 8px modular baseline, maintaining open, unhurried negative space.

## Elevation & Depth

Visual hierarchy is established using soft ambient light tinted with the deep navy palette, combined with hairline borders (`1px solid #F1F5F9` to `#E2E8F0`).

- **Surface 0 (Base)**: `#F8FAFC`. Clean, un-elevated canvas.
- **Surface 1 (Cards, Standard Blocks)**: `#FFFFFF` resting on `#F8FAFC`. Elevated by a subtle ambient drop shadow: `box-shadow: 0 1px 3px 0 rgba(15, 23, 42, 0.04), 0 1px 2px -1px rgba(15, 23, 42, 0.03)` with a hairline outline `border: 1px solid #E2E8F0`.
- **Surface 2 (Interactive Hover & Flyouts)**: `box-shadow: 0 10px 25px -5px rgba(15, 23, 42, 0.06), 0 8px 10px -6px rgba(15, 23, 42, 0.04)`. Imparts a gentle physical lift without aggressive float.
- **Surface 3 (Modals & Overlays)**: `box-shadow: 0 20px 30px -10px rgba(15, 23, 42, 0.12)`, supported by a tinted backdrop blur (`rgba(15, 23, 42, 0.4)` with `backdrop-filter: blur(8px)`).

## Shapes

The design uses balanced, rounded geometry (`roundedness: 2` base) calibrated to convey modernity while retaining institutional seriousness:

- Standard structural cards, project showcases, and credential tiles utilize `rounded-2xl` (`1rem` / `16px`).
- Form elements, buttons, and callout blocks use `rounded-xl` (`0.75rem` / `12px`).
- Badges, status markers, tags, and avatars use fully rounded pill geometry (`rounded-full` / `9999px`) to contrast against the architectural cards.

## Components

### Buttons
- **Primary**: Deep Slate Navy background (`#0F172A`), white text, subtle shadow, and `rounded-xl`. On hover: `#1E293B` with a `translate-y-[-1px]` micro-lift.
- **Secondary / Sharia Accent**: Muted emerald tint (`#F0FDF4`), text `#0D9488`, border `1px solid rgba(13, 148, 136, 0.2)`. On hover: `#DCFCE7`.
- **Ghost / Tertiary**: Neutral transparent background, text `#334155`. On hover: `#F1F5F9`.

### Chips & Tags
- Used for financial competencies, sharia compliance badges, and advisory roles.
- Styling: `rounded-full`, padding `4px 12px`, typography `label-sm`. Emerald chips use `background: #ECFDF5`, `color: #065F46`, and a border of `1px solid #A7F3D0`.

### Cards
- Base: White background, `rounded-2xl`, border `1px solid #E2E8F0`, padding `24px` (`space-lg`).
- Hoverable portfolio cards smoothly transition to Surface 2 depth with border brightening to `#CBD5E1`.

### Timeline & Experience Elements
- Vertical line in `#E2E8F0` (`2px` width).
- Node indicators: 12px circular dots with a 4px inner dot of `#0D9488` encircled by an outer `#ECFDF5` halo.
- Indonesian date localization format (e.g., *Januari 2021 – Sekarang*), styled in `label-sm` with slate `#64748B`.

### Input Fields & Search
- Surface: `#FFFFFF`, `rounded-xl`, border `1px solid #CBD5E1`, padding `12px 16px`.
- Focus state: Border transitions to `#0D9488` with a ring of `3px rgba(13, 148, 136, 0.15)`. No default black focus outline.

### Verification & Trust Badges
- Compact pill containing a verified icon checkmark, label (e.g., *Tersertifikasi OJK / DSN-MUI*), set in `#065F46` on `#F0FDF4` with `#10B981` accents.