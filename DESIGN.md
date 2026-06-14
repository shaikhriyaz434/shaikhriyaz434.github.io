---
name: RiyazPortfolioTheme
colors:
  background: "#fafafa"       # Default: Aurora Light Glass base
  surface: "rgba(255, 255, 255, 0.65)"
  card: "rgba(255, 255, 255, 0.65)"
  primary: "#ec4899"          # Pink/Magenta accent
  secondary: "#a855f7"        # Purple secondary
  accent: "#3b82f6"           # Blue highlight
  border: "rgba(0, 0, 0, 0.08)"
  text-primary: "#0f172a"     # Slate 900
  text-secondary: "#334155"   # Slate 800
  text-muted: "#94a3b8"       # Slate 400
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

## Aesthetic Concept: "Aurora & Solar"
An interface focused on clean, light-mode glassmorphism as the default experience (Aurora), paired with a premium high-contrast dark-mode alternative (Solar).

## Visual Pillars
1. **Glassmorphic Depth**: Subtle backdrop blurring (`backdrop-filter: blur(12px)`) and semi-translucent background fills (`rgba(255, 255, 255, 0.65)` for Aurora, `rgba(28, 25, 23, 0.6)` for Solar).
2. **Radial Lighting**: Ambient glowing background orbs that shift based on mouse movements to establish organic interaction depth.
3. **Typography Contrast**: Plus Jakarta Sans geometric headers matched with Inter body copy, plus JetBrains Mono for interactive console output.
4. **Focused Color Palettes**: Soft pink, purple, and blue gradients in Aurora; high-energy warm orange, rose, and gold in Solar.


## Component Specifications
- **Interactive Console**: Built to resemble a code IDE/terminal. Font family must be `JetBrains Mono`. Input line has active caret animation. Outputs must be clearly categorized with color codes.
- **Filterable Timeline**: Work experience cards are connected by a vertical axis. Hover states dynamically expand/highlight individual cards while scaling the axis node.
- **Skills Matrix**: Organized in a modular grid. Categories are labeled with custom icons. Individual skill tags have hover-glow states.
