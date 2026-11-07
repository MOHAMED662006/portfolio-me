---
name: Obsidian Crimson
colors:
  surface: '#131315'
  surface-dim: '#131315'
  surface-bright: '#39393b'
  surface-container-lowest: '#0e0e10'
  surface-container-low: '#1c1b1d'
  surface-container: '#201f21'
  surface-container-high: '#2a2a2c'
  surface-container-highest: '#353437'
  on-surface: '#e5e1e4'
  on-surface-variant: '#e6bdb8'
  inverse-surface: '#e5e1e4'
  inverse-on-surface: '#313032'
  outline: '#ac8884'
  outline-variant: '#5c403c'
  surface-tint: '#ffb4ab'
  primary: '#ffb4ab'
  on-primary: '#690005'
  primary-container: '#dc2626'
  on-primary-container: '#fff6f5'
  inverse-primary: '#bf0715'
  secondary: '#ffb4aa'
  on-secondary: '#690003'
  secondary-container: '#e10111'
  on-secondary-container: '#fff1ef'
  tertiary: '#ffb4ac'
  on-tertiary: '#690007'
  tertiary-container: '#cb403a'
  on-tertiary-container: '#fff6f4'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb4ab'
  on-primary-fixed: '#410002'
  on-primary-fixed-variant: '#93000b'
  secondary-fixed: '#ffdad5'
  secondary-fixed-dim: '#ffb4aa'
  on-secondary-fixed: '#410001'
  on-secondary-fixed-variant: '#930007'
  tertiary-fixed: '#ffdad6'
  tertiary-fixed-dim: '#ffb4ac'
  on-tertiary-fixed: '#410002'
  on-tertiary-fixed-variant: '#8e1214'
  background: '#131315'
  on-background: '#e5e1e4'
  surface-variant: '#353437'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 64px
    fontWeight: '800'
    lineHeight: 72px
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
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
  code-lg:
    fontFamily: JetBrains Mono
    fontSize: 15px
    fontWeight: '500'
    lineHeight: 24px
  code-md:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  gutter-lg: 2rem
  margin: 2rem
  margin-mobile: 1.25rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system targets an ultra-modern, high-impact technical portfolio tailored for an elite Front-end Engineer and Creative Developer. The aesthetic marries high-octane engineering discipline with cinematic creative execution. It projects deep technical mastery, architectural rigor, and taste for cutting-edge interaction design.

### Visual Style
- **Dark Glassmorphism & Raymarching Aesthetics:** Multi-layered translucent panels resting over an obsidian void, punctuated by diffuse crimson luminous backlights and subtle light leaks.
- **Precision Engineering Meets Cybernetic Elegance:** Clean mathematical grids, hairline dividers with selective glow hotspots, and terminal-inspired diagnostic elements.
- **Interactive Depth:** Surfaces react dynamically to cursor movement with localized spotlight gradients, glass refractions, and sub-pixel edge highlights.

## Colors

The palette relies on a disciplined dark balance: pure deep obsidian foundations accented by high-energy crimson and laser-focused ruby red emitters.

### Palette Architecture
- **Canvas & Void (`neutral`):** `#0A0A0C` (Base Canvas), `#121216` (Elevated Surface), `#181820` (Interactive / Overlay Surface).
- **Crimson Spectrum (`primary`, `secondary`, `tertiary`):** 
  - `#E50914` (Luminous Red / Active Glow Emissives)
  - `#DC2626` (Primary Action & Brand Anchor)
  - `#991B1B` (Deep Crimson Accent & Active Borders)
  - `#7F1D1D` (Subdued Glow Falloff & Ambient Backing)
- **Text & Accents:**
  - `#F8FAFC` (Primary Text / High-Contrast Headings)
  - `#94A3B8` (Secondary Slate / Body & Metadata)
  - `#475569` (Muted Code / Borders / Non-focus Elements)

### Glow & Gradient Rules
- Never use solid red backdrops for large containers. Crimson is treated as a light source: use radial glow gradients (`radial-gradient(circle at center, rgba(220, 38, 38, 0.15) 0%, transparent 70%)`) and 1px gradient hairline borders (`linear-gradient(135deg, rgba(229, 9, 20, 0.4) 0%, rgba(255, 255, 255, 0.05) 50%, rgba(220, 38, 38, 0.1) 100%)`).

## Typography

The type system creates an intentional juxtaposition between high-precision sans-serif geometry and structured, technical monospace data.

- **Primary Voice (Plus Jakarta Sans):** Handles headlines, titles, narrative storytelling, and human-facing UI controls. Generous tracking on large headers adds air and cinematic presence.
- **Technical Sub-Voice (JetBrains Mono):** Reserved for technical metadata, tags, stack indicators, inline syntax, file paths, and terminal prompts.
- **Label Caps:** Formatted with `text-transform: uppercase` and `letter-spacing: 0.08em` for section markers, status indicators, and terminal breadcrumbs.

## Layout & Spacing

A 12-column responsive fluid grid anchored by strict vertical rhythm based on an 8pt step system.

### Grid & Breakpoints
- **Mobile (< 768px):** 4 columns, `margin-mobile` (1.25rem), `gutter-sm` (1rem). Single column stacking for project showcases and tech matrices.
- **Tablet (768px - 1024px):** 8 columns, `margin` (2rem), `gutter` (1.5rem). Multi-column technical tables and split code/preview views.
- **Desktop (> 1024px):** 12 columns, max-width container capped at `1440px`, `margin-desktop` (3rem), `gutter-lg` (2rem). Complex asymmetric showpieces and split showcase grids.

### Spacing Principles
- Technical elements and compact badges use micro intervals (`space-xs`, `space-sm`).
- Content blocks, terminal headers, and card internals rely on `space-md` and `space-lg`.
- Major section transitions leverage `space-xl` multiplied by 2 or 3 to emphasize portfolio scope and focus.

## Elevation & Depth

Visual hierarchy uses atmospheric optical layering: surfaces are frosted, translucent shields elevated through backdrop filtration, dual-tone edge lights, and localized red luminescence rather than conventional muddy black dropshadows.

### Layer Hierarchy
- **Level 0 (Canvas):** Pure `#0A0A0C` background, textured with a subtle 3% SVG film noise grain and interactive radial red glow emitters (`rgba(220, 38, 38, 0.08)`) that follow cursor coordinates.
- **Level 1 (Sub-surface / Grid Tiles):** Background `#121216` with `80%` opacity, `backdrop-filter: blur(12px)`, bordered by `1px solid rgba(255, 255, 255, 0.06)`.
- **Level 2 (Showcase Cards & Dialogs):** Background `#181820` with `60%` opacity, `backdrop-filter: blur(24px)`, bordered by `1px solid rgba(220, 38, 38, 0.2)`.
  - Edge light: `box-shadow: inset 0 1px 0 0 rgba(255, 255, 255, 0.1)`.
  - Ambient shadow: `0 20px 40px -15px rgba(0, 0, 0, 0.7), 0 0 30px -10px rgba(220, 38, 38, 0.2)`.
- **Level 3 (Focused State / Active Glow):** Border elevated to `#E50914` at `50%` opacity, accompanied by an external aura: `box-shadow: 0 0 35px 2px rgba(229, 9, 20, 0.35), inset 0 0 15px rgba(229, 9, 20, 0.1)`.

## Shapes

The design system adopts a balanced, surgical corner radius (`roundedness: 2`). This provides ergonomic, modern polish while retaining the technical precision demanded by developer UI.

- **Micro Controls & Badges (`rounded-sm`):** 0.375rem (6px) for terminal tabs, code badges, and inline status chips.
- **Interactive Elements & Inputs (`rounded`):** 0.5rem (8px) for buttons, inputs, dropdown menus, and standard cards.
- **Primary Showcase Containers (`rounded-lg`):** 1rem (16px) for major case study viewports, terminal window wrappers, and interactive sandbox environments.
- **Highlight Embellishments:** Structural corners on showcase cards occasionally feature 45-degree micro chamfers or faux registration brackets to echo high-end tooling.

## Components

### Buttons & Interactive Controls
- **Primary Action (Crimson Core):** Background `linear-gradient(135deg, #DC2626, #991B1B)`. Crisp white text (`#F8FAFC`). Shadow: `0 0 20px rgba(220, 38, 38, 0.4)`. On hover, scale 1.02x with light sweep animation across the border and intensify glow to `#E50914`.
- **Secondary Action (Glass Ghost):** Background `rgba(24, 24, 32, 0.6)` with `backdrop-filter: blur(12px)`. Border `1px solid rgba(255, 255, 255, 0.1)`. Slate text transitioning to white and crimson border highlight on hover.
- **Icon / Terminal Trigger:** Square profile, centered monospace icon or SVG, border `1px solid rgba(255, 255, 255, 0.08)`, active state flashes crimson.

### Project Showcase Cards
- Translucent dark container (`#121216` at 70% opacity, 16px blur). Hairline perimeter border with a linear gradient passing through crimson.
- **Internal Structure:** Top browser/terminal chrome header (traffic light dots styled in grayscale `#475569`, turning crimson on hover), preview viewport for dynamic webGL/canvas embeds, followed by title, descriptive copy, and a bottom tech-stack tray.

### Tech Stack Grid & Badges
- **Badges:** Pill-shaped or micro-radius tags with `code-md` typography. Background `rgba(220, 38, 38, 0.08)`, border `1px solid rgba(220, 38, 38, 0.25)`, text `#F8FAFC`. A pulsing `#E50914` 4px indicator dot precedes active/core proficiencies.
- **Tech Stack Tiles:** Square or 4:3 glassmorphism blocks featuring SVG brand icons with subtle crimson drop-shadows on active hover.

### Interactive Terminal Emulator
- Window frame with title bar displaying current working directory (`~/projects/creative-dev`).
- Monospace output with highlighted green/crimson command status, syntax coloring, and an active blinking red cursor (`#E50914`, 1s infinite alternate fade).

### Form Inputs & Text Fields
- Surface: `#0A0A0C` inset. Border: `1px solid rgba(255, 255, 255, 0.1)`.
- Focus state: Border transitions to `#DC2626` accompanied by an inner and outer crimson ambient halo (`box-shadow: 0 0 12px rgba(220, 38, 38, 0.25)`). Placeholder in muted slate (`#475569`).

### Selection Controls (Checkboxes & Radios)
- Base: Custom square/circular obsidian wells (`#121216`) with hairline border.
- Checked state: Filled with `#DC2626` accompanied by a micro crimson glow dot and sharp white icon indicator.