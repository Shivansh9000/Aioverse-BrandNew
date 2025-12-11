# Aioverse Naming System & Asset Taxonomy

> **Aioverse™** is the universal naming component and organizational framework for Aiotize Inc.'s brand assets, design systems, and digital ecosystem.

## 1. Aioverse Core Principles

### Philosophy
- **Universal**: One consistent naming convention across all Aiotize ecosystems
- **Semantic**: Names convey purpose, category, and hierarchy
- **Scalable**: Grows with organizational complexity without losing clarity
- **Accessible**: Easy to read, remember, and search for all team members

### Core Tenets
1. **Asset-First Naming** - Assets define their category and purpose
2. **Hierarchical Clarity** - Folder depth reflects conceptual hierarchy
3. **Consistency Over Creativity** - Predictable naming beats unique names
4. **Localization-Ready** - Framework supports multi-language teams

---

## 2. Aioverse Asset Classification

All assets fall into one of these primary categories:

### Category: `fonts/`
- **Aioverse Code**: `AIO-FONT`
- **Purpose**: Typography system for all brand communications
- **Structure**: `fonts/[weight]/[family-name]/`
- **Example**: `fonts/primary/Nohemi/` (primary typeface)
- **Example**: `fonts/secondary/TokyoTrailMono/` (accent typeface)
- **Naming Pattern**: `[FontName]-[Weight]-[Style].[format]`
  - `Nohemi-Regular.woff2`
  - `Nohemi-Bold-Italic.ttf`

### Category: `logos/`
- **Aioverse Code**: `AIO-LOGO`
- **Purpose**: Primary and secondary brand marks
- **Structure**: `logos/[variation]/[format]/`
- **Naming Pattern**: `Aioverse-[Type]-[Version]-[ColorMode].[format]`
  - `Aioverse-Primary-v1-Dark.svg`
  - `Aioverse-Wordmark-v1-Light.png`
  - `Aioverse-Symbol-v1-Mono.pdf`

### Category: `icons/`
- **Aioverse Code**: `AIO-ICON`
- **Purpose**: UI icons and symbol sets
- **Structure**: `icons/[set-name]/[variant]/`
- **Naming Pattern**: `[IconName]-[Size]-[State].[format]`
  - `menu-24-default.svg`
  - `close-32-hover.png`
  - `aio-logo-16-active.svg`

### Category: `illustrations/`
- **Aioverse Code**: `AIO-ILLUS`
- **Purpose**: Custom illustrations and visual narratives
- **Structure**: `illustrations/[style]/[use-case]/`
- **Naming Pattern**: `[Concept]-[Scene]-[Version].[format]`
  - `Workflow-Dashboard-v1.svg`
  - `Team-Collaboration-v2.png`
  - `Growth-Analytics-v1.ai`

### Category: `photos/`
- **Aioverse Code**: `AIO-PHOTO`
- **Purpose**: Branded photography and imagery
- **Structure**: `photos/[subject]/[collection]/`
- **Naming Pattern**: `Aioverse-[Subject]-[DateTaken]-[Reference].[format]`
  - `Aioverse-Team-20250101-Meeting001.jpg`
  - `Aioverse-Office-20250110-Workspace.png`
  - `Aioverse-Product-20250115-Launch.jpg`

### Category: `guidelines/`
- **Aioverse Code**: `AIO-GUIDE`
- **Purpose**: Brand standards, usage rules, and documentation
- **Structure**: `guidelines/[aspect]/`
- **Naming Pattern**: `Aioverse-[Aspect]-Guidelines-[Version].[format]`
  - `Aioverse-Logo-Guidelines-v2.pdf`
  - `Aioverse-Color-Guidelines-v1.md`
  - `Aioverse-Typography-Guidelines-v1.pdf`

### Category: `tokens/`
- **Aioverse Code**: `AIO-TOKEN`
- **Purpose**: Design system variables and tokens
- **Structure**: `tokens/[format]/[domain]/`
- **Naming Pattern**: `aioverse-[domain]-[version].[format]`
  - `aioverse-colors-v1.json`
  - `aioverse-typography-v1.yaml`
  - `aioverse-spacing-v1.css`

---

## 3. Aioverse File Naming Convention

### Universal File Format
```
[AssetType]-[Descriptor]-[Variant]-[Version].[Format]
```

### Component Breakdown

#### AssetType (Required)
- `Aioverse` - Master brand asset
- `Component` - UI or design component
- `Icon` - Icon asset
- `Illustration` - Illustration asset
- `Photo` - Photography
- `Font` - Typography file

#### Descriptor (Optional but Recommended)
- Clear, single-concept identifier
- Examples: `Logo`, `Button`, `Menu`, `Card`, `Header`
- Use hyphens for multi-word: `call-to-action`

#### Variant (Optional)
- Specific state or modification
- Examples: `Dark`, `Light`, `Hover`, `Active`, `Disabled`, `Mobile`
- Can be stacked: `Dark-Mobile`

#### Version (Optional)
- Version number: `v1`, `v2`, `v3`
- Or date-based: `20250101`
- Semantic versioning: `1-0-0` (major-minor-patch)

#### Format (Required)
- File extension: `svg`, `png`, `jpg`, `pdf`, `ai`, `woff2`, `ttf`, `json`, `yaml`, `css`

### Examples
```
Aioverse-Logo-Dark-v1.svg
Aioverse-Button-Hover-20250115.png
Component-Card-Light-Mobile-v2.ai
Icon-Menu-24-Active.svg
Photo-Team-20250110-v1.jpg
Font-Nohemi-Bold-Italic.woff2
```

---

## 4. Folder Hierarchy & Organization

### Root Level (Asset Categories)
```
Brand-ssets/
├── fonts/              [AIO-FONT] Typography system
├── logos/              [AIO-LOGO] Brand marks
├── icons/              [AIO-ICON] UI symbols
├── illustrations/      [AIO-ILLUS] Custom artwork
├── photos/             [AIO-PHOTO] Imagery
├── guidelines/         [AIO-GUIDE] Documentation
└── tokens/             [AIO-TOKEN] Design system
```

### Second Level (Context/Classification)
```
fonts/
├── primary/            [AIO-FONT-PRIMARY] Main typefaces
├── secondary/          [AIO-FONT-SECONDARY] Accent typefaces
└── system/             [AIO-FONT-SYSTEM] UI system fonts

logos/
├── primary/            [AIO-LOGO-PRIMARY] Main brand mark
├── secondary/          [AIO-LOGO-SECONDARY] Alternate mark
├── wordmark/           [AIO-LOGO-WORDMARK] Text-only logo
└── symbol/             [AIO-LOGO-SYMBOL] Icon-only mark

icons/
├── ui/                 [AIO-ICON-UI] Interface icons
├── social/             [AIO-ICON-SOCIAL] Social media icons
├── custom/             [AIO-ICON-CUSTOM] Brand-specific icons
└── system/             [AIO-ICON-SYSTEM] System-wide icons
```

---

## 5. Aioverse Code System

Each asset category has a unique code for referencing and tracking:

| Category | Code | Usage |
|----------|------|-------|
| Fonts | `AIO-FONT` | `AIO-FONT-01`, `AIO-FONT-02` |
| Logos | `AIO-LOGO` | `AIO-LOGO-PRIMARY-01` |
| Icons | `AIO-ICON` | `AIO-ICON-UI-001` |
| Illustrations | `AIO-ILLUS` | `AIO-ILLUS-WEB-001` |
| Photos | `AIO-PHOTO` | `AIO-PHOTO-BRANDED-001` |
| Guidelines | `AIO-GUIDE` | `AIO-GUIDE-LOGO-v1` |
| Tokens | `AIO-TOKEN` | `AIO-TOKEN-COLOR-v1` |

### Usage in Documentation
```markdown
**Asset**: [AIO-LOGO-PRIMARY-01]
Name: Aioverse-Primary-Mark-v1.svg
Category: Logo - Primary Brand Mark
Location: logos/primary/
```

---

## 6. Version Control & Evolution

### Versioning Strategy

#### Semantic Versioning (Recommended)
```
v[MAJOR].[MINOR].[PATCH]
Example: v1.2.3

MAJOR: Breaking changes (complete redesign)
MINOR: Non-breaking changes (refinements)
PATCH: Fixes (corrections)
```

#### Date-Based Versioning
```
[YYYYMMDD]-[revision]
Example: 20250115-01 (January 15, 2025, revision 1)
```

#### Archive Strategy
```
[AssetName]-[Version]-ARCHIVED.[format]
Example: Aioverse-Logo-v1-ARCHIVED.svg
```

---

## 7. Color & State Naming

### Predefined Variants
```
Light       → Light theme variant
Dark        → Dark theme variant
Monochrome  → Black and white only
Brand       → Full brand colors
Neutral     → Grayscale variant

Default     → Standard state
Hover       → Mouse over state
Active      → Currently selected/active
Focus       → Keyboard focus state
Disabled    → Inactive/disabled state
Loading     → Loading/in-progress state
Error       → Error/alert state
Success     → Success/confirmation state
```

### Combination Examples
```
Aioverse-Button-Dark-Hover.svg
Aioverse-Icon-Light-Disabled.png
Aioverse-Card-Monochrome-Active.ai
```

---

## 8. Repository & Location Naming

### Repository Naming Pattern
```
aio3-[AioCategory]-[Descriptor]
Examples:
aio3-design-system
aio3-brand-assets
aio3-component-library
aio3-icon-system
```

### Asset Repository Structure
```
[org]/aio3-[category]-[descriptor]
├── README.md                 → Repository purpose
├── AIOVERSE_NAMING.md       → This document
├── [category]/              → Asset files
│   └── [subcategory]/       → Organized assets
└── docs/                    → Additional documentation
    ├── guidelines.md
    ├── usage-examples.md
    └── faq.md
```

---

## 9. Implementation Checklist

When adding new assets to Aioverse, follow this checklist:

- [ ] Determine primary asset category (fonts, logos, icons, etc.)
- [ ] Choose appropriate subcategory
- [ ] Assign Aioverse code
- [ ] Follow naming convention: `[Type]-[Descriptor]-[Variant]-[Version].[format]`
- [ ] Include version number (v1, v2, or YYYYMMDD-01)
- [ ] Add descriptive comments in code/metadata
- [ ] Update this documentation if new pattern emerges
- [ ] Create entry in asset registry (if applicable)

---

## 10. Quick Reference Guide

### When Naming Assets, Ask:
1. **What is it?** (AssetType: Logo, Icon, Font, etc.)
2. **What is its purpose?** (Descriptor: Primary, UI, Accent, etc.)
3. **What state/variant is it?** (Variant: Dark, Hover, Mobile, etc.)
4. **What version is it?** (Version: v1, v2, 20250115, etc.)

### Common Naming Errors to Avoid
❌ `logo.svg` → Too generic
❌ `Logo-Updated-Final-FINAL.svg` → Too vague
❌ `LOGO_V1_DARK_FINAL_2025.svg` → Inconsistent casing

✅ `Aioverse-Logo-Primary-Dark-v1.svg` → Clear and consistent
✅ `Aioverse-Icon-Menu-24-Active.svg` → Descriptive
✅ `aioverse-colors-v1.json` → Lowercase tokens convention

---

## 11. Future Extensions

This naming system supports future expansion:
- **Locale codes**: `Aioverse-Guide-Logo-EN-v1.pdf` (English)
- **Device targets**: `Aioverse-Icon-Menu-iOS-24.svg`
- **Accessibility variants**: `Aioverse-Icon-Menu-A11y-24.svg`
- **Animated versions**: `Aioverse-Illustration-Loading-Animated.lottie`

---

## Contact & Updates

**Aioverse Naming System** is maintained by the Aiotize Design System team.

For questions or suggestions, please contact: [contact-info]

Last Updated: December 2025
Aioverse Version: 1.0
