---
name: Kinetic Amber Studio
colors:
  surface: '#0b1326'
  surface-dim: '#0b1326'
  surface-bright: '#31394d'
  surface-container-lowest: '#060e20'
  surface-container-low: '#131b2e'
  surface-container: '#171f33'
  surface-container-high: '#222a3d'
  surface-container-highest: '#2d3449'
  on-surface: '#dae2fd'
  on-surface-variant: '#d8c3ad'
  inverse-surface: '#dae2fd'
  inverse-on-surface: '#283044'
  outline: '#a08e7a'
  outline-variant: '#534434'
  surface-tint: '#ffb95f'
  primary: '#ffc174'
  on-primary: '#472a00'
  primary-container: '#f59e0b'
  on-primary-container: '#613b00'
  inverse-primary: '#855300'
  secondary: '#ffc640'
  on-secondary: '#402d00'
  secondary-container: '#e3aa00'
  on-secondary-container: '#5a4100'
  tertiary: '#56e5a9'
  on-tertiary: '#003824'
  tertiary-container: '#30c88f'
  on-tertiary-container: '#004e34'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffddb8'
  primary-fixed-dim: '#ffb95f'
  on-primary-fixed: '#2a1700'
  on-primary-fixed-variant: '#653e00'
  secondary-fixed: '#ffdf9f'
  secondary-fixed-dim: '#f9bd22'
  on-secondary-fixed: '#261a00'
  on-secondary-fixed-variant: '#5c4300'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#0b1326'
  on-background: '#dae2fd'
  surface-variant: '#2d3449'
typography:
  display-hero:
    fontFamily: Syne
    fontSize: 64px
    fontWeight: '800'
    lineHeight: 72px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Syne
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Syne
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Syne
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Syne
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-tag:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
  caption:
    fontFamily: Plus Jakarta Sans
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

This design system expresses the personality of a senior creative engineer: technically meticulous, design-led, and unapologetically forward-looking. The visual language bridges elite software engineering with boutique digital agency aesthetics, balancing structural discipline with expressive electricity.

The design movement combines **Neo-Brutalist structural clarity** (crisp hairline borders, monospaced data metadata, architectural modularity) with **high-end dark-mode Glassmorphism and micro-grid precision**. It avoids chaotic clutter in favor of intentional hierarchy, razor-sharp alignment, and focused explosions of high-voltage amber against deep slate substrates.

Target audience: Design engineering leads, startup founders, tech recruiters, and engineering executives who value both system-level craftsmanship and refined visual polish.

## Colors

The system is calibrated natively for dark surfaces with extreme clarity and vibrant thermal energy:

- **Primary Accent (`#F59E0B`)**: Electric warm amber. Used selectively for primary call-to-actions, active links, focused states, and key navigational landmarks.
- **Secondary Accent (`#FBBF24`)**: Luminous gold. Applied to interactive hover states, energetic badges, and terminal highlight tokens.
- **Tertiary Accent (`#10B981`)**: Emerald signal. Dedicated to deployment statuses, live production indicators, and success logs.
- **Surface Foundations**:
  - `surface-base`: `#0B0F19` (Obsidian canvas)
  - `surface-raised`: `#111827` (Card backdrop and panel foundation)
  - `surface-overlay`: `#1E293B` (Dropdowns, modals, and elevated utility layers)
- **Borders & Outlines**: `#334155` at default; `#F59E0B` at 40% opacity on interactive hover.
- **Text & Foreground**:
  - `text-primary`: `#F8FAFC` (Pure crisp off-white for effortless legibility)
  - `text-secondary`: `#94A3B8` (Cool slate for supporting context and descriptions)
  - `text-muted`: `#64748B` (Subtle technical markers and line counts)

## Typography

The typographic architecture balances expressive, forward-leaning geometry with technical utility:

- **Headlines (`Syne`)**: Provides structural drama, artistic authority, and unmistakable attitude for project case study titles and banner statements. Set tight with negative tracking.
- **Body (`Plus Jakarta Sans`)**: Delivers geometric warmth, generous x-height, and superior sustained legibility across long-form architecture writeups and technical case studies.
- **Metadata & Code (`JetBrains Mono`)**: Signals developer pedigree. Applied strictly to commit hashes, tech stack indicators, numeric project indices (e.g., `[01/08]`), file paths, and terminal interfaces.

## Layout & Spacing

The canvas is constructed on an adaptable 12-column responsive grid underpinned by an 8pt architectural rhythm:

- **Desktop (1024px+)**: 12-column grid, `margin: 3rem`, `gutter: 1.5rem`, maximum container constraint of 1280px.
- **Tablet (768px - 1023px)**: 8-column layout, `margin: 2rem`, `gutter: 1.25rem`.
- **Mobile (< 768px)**: 4-column layout, `margin-mobile: 1.25rem`, `gutter-mobile: 1rem`.

To reinforce the creative technologist aesthetic, major module borders align directly to the grid lines. Micro-dot matrices or subtle grid intersections (`+` glyphs rendered in `text-muted` at low opacity) may anchor outer structural boundaries.

## Elevation & Depth

Visual hierarchy uses crisp boundary delineation and tonal luminance rather than traditional heavy drop shadows:

- **Layer 0 (Canvas Base)**: Pure `#0B0F19` with a persistent faint 32px CSS background dot grid (`radial-gradient(#1E293B 1px, transparent 1px)`).
- **Layer 1 (Card & Module Surfaces)**: Semi-translucent `#111827` blended with `backdrop-filter: blur(12px)`. Enclosed within a 1px structural hairline border of `rgba(255, 255, 255, 0.08)`.
- **Layer 2 (Overlays & Dialogs)**: `#1E293B` featuring a diffused amber accent aura: `box-shadow: 0 16px 40px -10px rgba(0, 0, 0, 0.6), 0 0 24px -4px rgba(245, 158, 11, 0.15)`.
- **Interactive State**: Hovered elements brighten their inner surface fill by 4% and shift their border to `rgba(245, 158, 11, 0.45)`, producing a dynamic, backlit kinetic response.

## Shapes

The shape system adopts a tight, engineered **Soft** geometry (`roundedness: 1`):

- **Structural Cards and Panels**: `0.5rem` (`rounded-lg`) to balance precision and modern softness.
- **Inputs, Nested Containers, and Code Blocks**: `0.25rem` base curvature.
- **Tech Badges & Status Chips**: Pill-shaped overrides (`9999px`) provide high-contrast visual rhythm against angular cards.

## Components

### Buttons
- **Primary**: Solid Electric Amber (`#F59E0B`) fill, Obsidian (`#0B0F19`) text set in bold `Plus Jakarta Sans`. Interactive hover elevates luminance to Secondary Gold (`#FBBF24`) with an outward displacement: `transform: translate(-1px, -1px)` paired with an amber glow.
- **Secondary / Ghost**: Semi-opaque background (`rgba(255, 255, 255, 0.04)`), 1px border (`#334155`), and crisp off-white text. Hover switches the border to full amber with an inner tint.
- **Terminal Action**: Monospaced text framed by square brackets (e.g., `[ view_demo() ]`) with a cursor blink transition on hover.

### Chips & Tech Stack Pills
- Pill-shaped (`rounded-full`), padded with `0.25rem` vertical and `0.75rem` horizontal spacing.
- Styled using `label-tag` (`JetBrains Mono`, uppercase).
- Slate base background (`#1E293B`), 1px hairline border (`#334155`), with text rendered in `#F8FAFC`. Active skill tags swap to Amber tint with a leading glowing dot indicator.

### Cards (Project & Experience)
- Backed by dark slate glassmorphism with 1px hairline borders.
- Top navigation row of each card displays an index notation in JetBrains Mono (e.g., `CASE_STUDY // 01`) and live status lights.
- Subtle micro-glow transitions track the mouse cursor across the card perimeter.

### Form Inputs & Code Playgrounds
- Inputs feature dark slate fill (`#0B0F19`), subtle inset hairline borders, and `label-code` typography for placeholder prompts (e.g., `guest@portfolio:~$`).
- Focus states invoke a 1px border ring in Amber (`#F59E0B`) without thick default browser outlines.

### Lists & Activity Logs
- Border-separated modular rows rather than plain bullet points.
- Timestamps and git branch metadata styled in `label-code` set to Slate (`#64748B`).