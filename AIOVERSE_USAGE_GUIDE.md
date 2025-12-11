# Aioverse Brand Assets - Complete Usage Guide

## Table of Contents
1. [Overview](#overview)
2. [Getting Started](#getting-started)
3. [Asset Categories](#asset-categories)
4. [Design Tokens](#design-tokens)
5. [Typography Guidelines](#typography-guidelines)
6. [Logo Usage](#logo-usage)
7. [Icons & Illustrations](#icons--illustrations)
8. [Color Palette](#color-palette)
9. [Best Practices](#best-practices)
10. [File Naming Conventions](#file-naming-conventions)

## Overview

Aioverse is the universal naming component and organizational framework for Aiotize Inc.'s brand ecosystem. This comprehensive guide helps designers, developers, and stakeholders understand how to properly utilize all brand assets.

**Repository Code:** aio3-brand-assets
**Aioverse Code:** AIO-BRAND
**Purpose:** Centralized hub for all Aiotize Inc. brand assets, design tokens, and visual systems
**Maintained By:** Aiotize Design Systems Team
**Last Updated:** December 11, 2025

## Getting Started

### Quick Access
- **Repository:** https://github.com/Shivansh9000/Aioverse-BrandNew
- **Website:** https://aio3.ai
- **Domain:** aio3.ai

### Repository Structure
```
Aioverse-BrandNew/
├── fonts/              [AIO-FONT]       - Typography assets
├── logos/              [AIO-LOGO]       - Logo variations
├── icons/              [AIO-ICON]       - Icon library
├── illustrations/      [AIO-ILLUS]      - Custom illustrations
├── photos/             [AIO-PHOTO]      - Photography assets
├── guidelines/         [AIO-GUIDE]      - Brand guidelines
├── tokens/             [AIO-TOKEN]      - Design tokens
├── AIOVERSE_ECOSYSTEM.md                - Ecosystem documentation
├── AIOVERSE_NAMING.md                   - Naming conventions
├── FOLDER_STRUCTURE.md                  - Folder descriptions
└── README.md                            - Project overview
```

## Asset Categories

### 1. Fonts [AIO-FONT]
All typography assets for the Aioverse brand.

**Location:** `/fonts/`

**Contents:**
- Primary font families
- Web font formats (WOFF, WOFF2, TTF)
- Font weight variations
- License documentation

**Usage:**
- Web: Include font files in CSS stylesheets
- Design: Install fonts locally for Adobe Creative Suite
- Development: Implement via @font-face or CDN

### 2. Logos [AIO-LOGO]
All logo variations and brand mark assets.

**Location:** `/logos/`

**Variations:**
- Full logo with wordmark
- Symbol/mark only
- Horizontal/vertical layouts
- Color and monochrome versions
- Minimum size specifications

**File Formats:**
- Vector: SVG, AI, EPS
- Raster: PNG (with transparency), PDF

### 3. Icons [AIO-ICON]
Comprehensive icon library for UI/UX implementation.

**Location:** `/icons/`

**Organization:**
- 24px icons (UI)
- 32px icons (larger displays)
- 48px icons (touch targets)
- SVG format for scalability
- Consistent stroke weight (2px)

**Categories:**
- Navigation icons
- Action icons
- Status indicators
- Social media icons
- Utility icons

### 4. Illustrations [AIO-ILLUS]
Custom illustrations and artwork.

**Location:** `/illustrations/`

**Contents:**
- Brand character illustrations
- Scene compositions
- Thematic graphics
- Landing page illustrations

**Formats:**
- SVG (preferred for web)
- PNG with transparency
- Sketch/Figma source files

### 5. Photography [AIO-PHOTO]
Curated photography and stock imagery.

**Location:** `/photos/`

**Categories:**
- Product photography
- Team/culture photos
- Hero images
- Background textures

**Guidelines:**
- Consistent color grading
- High resolution (300 DPI for print)
- Web optimization (72 DPI)
- Licensed for commercial use

### 6. Brand Guidelines [AIO-GUIDE]
Comprehensive documentation for brand implementation.

**Location:** `/guidelines/`

**Contents:**
- Brand voice and tone
- Logo usage rules
- Color specifications
- Typography guidelines
- Spacing and grids
- Photography style guide
- Animation principles

### 7. Design Tokens [AIO-TOKEN]
Design system tokens for consistent implementation.

**Location:** `/tokens/`

**Token Types:**
- Color tokens (brand colors, semantic colors)
- Typography tokens (font families, sizes, weights)
- Spacing tokens (padding, margins, gaps)
- Border tokens (radius, width, style)
- Shadow tokens (elevation levels)
- Motion tokens (transition duration, easing)

## Design Tokens

### Token Structure
```json
{
  "aio": {
    "color": {
      "primary": { "value": "#007AFF", "type": "color" },
      "secondary": { "value": "#5AC8FA", "type": "color" },
      "success": { "value": "#34C759", "type": "color" },
      "error": { "value": "#FF3B30", "type": "color" }
    },
    "spacing": {
      "xs": { "value": "4px", "type": "spacing" },
      "sm": { "value": "8px", "type": "spacing" },
      "md": { "value": "16px", "type": "spacing" },
      "lg": { "value": "24px", "type": "spacing" },
      "xl": { "value": "32px", "type": "spacing" }
    }
  }
}
```

### Implementation
- **CSS:** Import as CSS variables
- **Figma:** Connect via design tokens plugin
- **Web:** Use as SCSS/CSS variables
- **Mobile:** Convert to platform-specific formats

## Typography Guidelines

### Font Families

**Primary:** [Font Name]
- Use for: Headlines, UI elements
- Weight: 600-700 (Bold)
- Size range: 24px - 48px

**Secondary:** [Font Name]
- Use for: Body text, descriptions
- Weight: 400-500 (Regular, Medium)
- Size range: 12px - 18px

**Mono:** [Font Name]
- Use for: Code, technical content
- Weight: 400 (Regular)
- Size: 12px - 14px

### Size Scale
```
H1: 48px / 1.5 line-height
H2: 36px / 1.4 line-height
H3: 28px / 1.4 line-height
H4: 24px / 1.3 line-height
Body: 16px / 1.5 line-height
Small: 14px / 1.4 line-height
Caption: 12px / 1.3 line-height
```

## Logo Usage

### Minimum Sizes
- **Digital:** 120px (width)
- **Print:** 1 inch (width)
- **Favicon:** 32x32px

### Clear Space
Maintain clear space of at least the height of the secondary mark around the logo.

### Color Usage
- **Primary:** Full color (on white/light backgrounds)
- **Monochrome:** Black on light, white on dark
- **Reversed:** Always ensure sufficient contrast

### Do's & Don'ts

**Do:**
- Use provided logo files
- Maintain aspect ratio
- Ensure adequate surrounding space
- Use on contrasting backgrounds

**Don't:**
- Stretch or distort
- Change colors without approval
- Add effects or shadows
- Use old/obsolete versions

## Icons & Illustrations

### Icon Usage

**Grid System:**
- 24px grid for all sizes
- 2px stroke weight (for line icons)
- Consistent corner radius (2px)

**Implementation:**
```html
<svg class="icon icon-24" viewBox="0 0 24 24">
  <!-- icon content -->
</svg>
```

**CSS:**
```css
.icon {
  width: 24px;
  height: 24px;
  stroke-width: 2;
  fill: currentColor;
}
```

### Illustration Guidelines

- **Color:** Use brand color palette
- **Style:** Consistent illustration style
- **Format:** SVG for scalability
- **Complexity:** Balanced visual hierarchy

## Color Palette

### Primary Colors

| Color | Hex | RGB | Usage |
|-------|-----|-----|-------|
| Primary Blue | #007AFF | rgb(0, 122, 255) | CTA, Active states |
| Primary Green | #34C759 | rgb(52, 199, 89) | Success, Positive |
| Primary Red | #FF3B30 | rgb(255, 59, 48) | Error, Alert |
| Primary Gray | #8E8E93 | rgb(142, 142, 147) | Disabled, Secondary |

### Gradients
- **Brand Gradient:** Primary Blue → Primary Cyan
- **Success Gradient:** Primary Green → Teal
- **Error Gradient:** Primary Red → Orange

## Best Practices

### For Designers

1. **Always use latest assets**
   - Check repository regularly for updates
   - Use version control
   - Document custom modifications

2. **Maintain consistency**
   - Follow guidelines strictly
   - Use design tokens
   - Create design system libraries

3. **Quality assurance**
   - Export with correct settings
   - Test across devices
   - Validate color accessibility (WCAG AA)

### For Developers

1. **Asset optimization**
   - Compress images
   - Optimize SVGs
   - Use modern formats (WebP, WOFF2)

2. **Implementation**
   - Use CSS variables for colors
   - Implement responsive images
   - Lazy load non-critical assets

3. **Accessibility**
   - Add alt text to images
   - Ensure color contrast
   - Test with screen readers

### For Product Managers

1. **Brand consistency**
   - Review designs against guidelines
   - Maintain visual identity
   - Track brand usage

2. **Asset management**
   - Keep inventory updated
   - Document usage rights
   - Review licensing

## File Naming Conventions

### Format: `[CATEGORY]-[TYPE]-[VARIANT].[FORMAT]`

**Examples:**
```
AIO-LOGO-PRIMARY-COLOR.svg
AIO-ICON-ARROW-24.svg
AIO-ILLUS-HERO-LANDING.png
AIO-PHOTO-TEAM-01.jpg
AIO-FONT-PRIMARY-BOLD.woff2
```

### Category Codes
- `AIO-FONT` → Fonts
- `AIO-LOGO` → Logos
- `AIO-ICON` → Icons
- `AIO-ILLUS` → Illustrations
- `AIO-PHOTO` → Photography
- `AIO-GUIDE` → Guidelines
- `AIO-TOKEN` → Design Tokens

### Version Control
- Include version numbers for major revisions
- Use semantic versioning (v1.0, v1.1, v2.0)
- Document changelog

## Troubleshooting

### Common Issues

**Q: Font not loading on website?**
A: Check CORS headers, file paths, and browser compatibility. Verify font format is supported.

**Q: Icon appears blurry?**
A: Ensure you're using correct size for your use case (24px, 32px, or 48px). Use SVG for best results.

**Q: Colors don't match on print?**
A: Request CMYK color values. RGB displays differently in print. Use Pantone references when available.

**Q: License questions?**
A: All assets are proprietary to Aiotize Inc. Internal use only. Contact legal for external licensing.

## Support & Feedback

- **Issues:** Report via GitHub Issues
- **Questions:** Contact design-systems@aiotize.com
- **Suggestions:** Pull requests welcome
- **Updates:** Follow repository for latest changes

## Version History

- **v1.0** (December 11, 2025) - Initial release
- All previous versions - Legacy (deprecated)

---

**© 2025 Aiotize Inc. All rights reserved.**
**Last Updated:** December 11, 2025
**Maintained By:** Aiotize Design Systems Team
