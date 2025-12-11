# Aioverse Visual Systems & Color Palettes

## Overview

Based on GitHub's design system principles, the Aioverse visual system defines the core visual language that brings Aiotize's brand persona to life. These systems ensure consistency across all brand applications.

## Color System Architecture

Inspired by GitHub's tiered palette approach, Aioverse uses three primary color systems:

### Primary Color Palette (Innovative + Reliable)

The primary palette anchors around Aiotize's core brand color, complemented with neutrals for a clean, professional appearance.

**Aiotize Core Brand Color**: Teal/Cyan
- Primary: #00D4FF (Bright, energetic, forward-thinking)
- Secondary: #00A8CC (Professional, trustworthy)
- Deep: #003F5C (Grounded, stable)

**Neutrals**:
- Light: #F5F7FA (Clean backgrounds)
- Medium: #9BA4B5 (Secondary text)
- Dark: #1E293B (Primary text)
- Black: #000000 (Maximum contrast)

### Secondary Color Palette (Pragmatic + Collaborative)

Supporting colors that express practical solutions and partnership.

**Green** (#10B981 - Growth, progress, positive action)
**Blue** (#3B82F6 - Trust, reliability, technology)
**Purple** (#A855F7 - Innovation, future-forward)
**Orange** (#F97316 - Energy, action, attention)
**Red** (#EF4444 - Alerts, errors, caution)

### Accent Color Palette (Visionary)

Bold accents for key moments and aspirational content.

**Gold** (#F59E0B - Premium, achievement)
**Emerald** (#059669 - Growth, nature, sustainability)
**Violet** (#7C3AED - Transformation, potential)

## Typography System

### Typeface Selection

**Headlines**: Modern, geometric sans-serif
- Family: Inter or similar (forward-looking, contemporary)
- Weight: Bold (700) for primary headers, Semibold (600) for secondary

**Body Text**: Clean, highly legible sans-serif
- Family: Inter or similar
- Weight: Regular (400) for body, Medium (500) for emphasis

**Code/Technical**: Monospace
- Family: Jetbrains Mono or similar
- Weight: Regular for standard code

### Type Scale

- **Display**: 48px, Bold, 1.2x line-height
- **H1**: 36px, Bold, 1.25x line-height
- **H2**: 28px, Semibold, 1.3x line-height
- **H3**: 22px, Semibold, 1.35x line-height
- **Body Large**: 18px, Regular, 1.5x line-height
- **Body**: 16px, Regular, 1.5x line-height
- **Body Small**: 14px, Regular, 1.5x line-height
- **Caption**: 12px, Regular, 1.4x line-height

## Design Tokens

### Spacing Scale (8px base unit)

- xs: 4px
- sm: 8px
- md: 16px
- lg: 24px
- xl: 32px
- 2xl: 48px
- 3xl: 64px
- 4xl: 96px

### Border Radius

- none: 0px
- sm: 4px
- md: 8px
- lg: 12px
- xl: 16px
- full: 9999px

### Shadows

- Light: 0 1px 2px rgba(0,0,0,0.05)
- Medium: 0 4px 6px rgba(0,0,0,0.1)
- Large: 0 10px 15px rgba(0,0,0,0.15)
- Extra Large: 0 20px 25px rgba(0,0,0,0.2)

### Opacity Scale

- 10%: used for subtle overlays
- 20%: hover states
- 50%: disabled states
- 75%: active states
- 100%: full opacity

## Component System

### Button Styles

**Primary Buttons**: Teal background, white text (action-oriented)
**Secondary Buttons**: Gray background, dark text (alternative actions)
**Tertiary Buttons**: No background, text only (low-priority actions)
**Danger Buttons**: Red background, white text (destructive actions)

### Icon System

- **Size**: 16px, 24px, 32px
- **Weight**: Consistent 2px strokes
- **Style**: Modern, geometric, recognizable at small sizes
- **Color**: Inherit text color or use accent colors

### Form Elements

- **Input Height**: 40px
- **Border**: 1px solid #00D4FF or gray
- **Focus State**: Teal border with shadow
- **Padding**: 8px horizontal, centered text

## Responsive Breakpoints

- Mobile: 320px - 640px
- Tablet: 641px - 1024px
- Desktop: 1025px+

## Dark Mode Considerations

When implementing dark mode:

- **Swap**: Light backgrounds become dark
- **Tint**: Colors shift slightly (primary becomes slightly brighter)
- **Text**: Inversed for contrast

Primary brand color (#00D4FF) maintains high contrast in both light and dark modes.

## Accessibility Specifications

### Color Contrast Ratios

- Text on background: Minimum 4.5:1 (WCAG AA)
- Large text (18px+): Minimum 3:1 (WCAG AA)
- Interactive elements: Minimum 3:1 (WCAG AA)

### Motion & Animation

- Standard transition: 200ms ease-out
- Hover transition: 150ms ease-out
- Respect prefers-reduced-motion

## Usage Guidelines

### Do's

- Use primary brand color for key actions
- Maintain consistent spacing using the token scale
- Follow the typographic hierarchy
- Use secondary colors for supporting information
- Apply shadows for depth and hierarchy

### Don'ts

- Mix multiple primary brand colors in one component
- Use sans-serif and serif fonts together
- Ignore contrast ratios for accessibility
- Create custom colors that don't fit the palette
- Ignore responsive breakpoints

---

Version: 1.0
Last Updated: December 11, 2025
Maintained By: Aiotize Design Systems Team
