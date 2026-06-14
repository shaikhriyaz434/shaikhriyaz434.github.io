---
name: RiyazPortfolioTheme
colors:
  background: "#030712"       # Deep outer-space grey
  surface: "#0f172a"          # Rich dark slate
  card: "rgba(15, 23, 42, 0.6)" # Glassmorphic slate with alpha
  primary: "#6366f1"          # Vivid Indigo
  secondary: "#14b8a6"        # Cool Teal
  accent: "#a855f7"           # Bright Purple
  border: "rgba(255, 255, 255, 0.08)"
  text-primary: "#f9fafb"     # High contrast grey-white
  text-secondary: "#cbd5e1"   # Mid contrast slate-grey
  text-muted: "#64748b"       # Low contrast slate-grey
typography:
  fontFamilyHeader: "'Plus Jakarta Sans', sans-serif"
  fontFamilyBody: "'Inter', sans-serif"
  fontFamilyCode: "'JetBrains Mono', monospace"
  h1:
    fontSize: "3.5rem"
    fontWeight: "800"
    letterSpacing: "-0.04em"
  h2:
    fontSize: "2.25rem"
    fontWeight: "700"
    letterSpacing: "-0.03em"
  body:
    fontSize: "1rem"
    lineHeight: "1.6"
spacing:
  xs: "4px"
  sm: "8px"
  md: "16px"
  lg: "24px"
  xl: "48px"
  xxl: "80px"
shadows:
  glow-primary: "0 0 30px rgba(99, 102, 241, 0.15)"
  glow-secondary: "0 0 30px rgba(20, 184, 166, 0.15)"
  card-hover: "0 20px 40px rgba(0, 0, 0, 0.3)"
border-radius:
  sm: "6px"
  md: "12px"
  lg: "20px"
---

# Design System & Creative Direction

## Aesthetic Concept: "Cyber-Minimalist Glass"
An interface that blends high-tech AI engineering with clean, premium design. The interface relies on dark-mode depth, glassmorphism, glowing radial gradients, and subtle vector mesh patterns to feel alive and advanced without compromising readability.

## Visual Pillars
1. **Glassmorphic Cards**: Depth created through `backdrop-filter: blur(16px)`, translucent background alphas, and ultra-thin, light borders (`rgba(255, 255, 255, 0.08)`).
2. **Radial Lighting**: Ambient glowing orbs positioned in the background that animate slowly, creating organic depth.
3. **Typography Contrast**: Pairing the bold, geometry of `Plus Jakarta Sans` for headers with the clean, neutral readability of `Inter` for body copy. Code and interactive widgets utilize `JetBrains Mono`.
4. **Interactive Accents**: Hover states that trigger scale shifts, border color transitions, and glowing drop shadows.

## Component Specifications
- **Interactive Console**: Built to resemble a code IDE/terminal. Font family must be `JetBrains Mono`. Input line has active caret animation. Outputs must be clearly categorized with color codes.
- **Filterable Timeline**: Work experience cards are connected by a vertical axis. Hover states dynamically expand/highlight individual cards while scaling the axis node.
- **Skills Matrix**: Organized in a modular grid. Categories are labeled with custom icons. Individual skill tags have hover-glow states.
