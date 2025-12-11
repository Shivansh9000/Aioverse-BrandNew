# Aioverse Ecosystem Map

> **Aioverse** is Aiotize Inc.'s unified naming and organizational system spanning all brand, design, and technical repositories.

## Ecosystem Overview

The Aioverse ecosystem comprises interconnected repositories that follow consistent naming, structure, and governance patterns.

### Core Principles
- **Universal Naming**: All repositories follow Aioverse naming conventions
- **Semantic Codes**: Each repository type has a unique identifier (AIO-*)
- **Hierarchical Organization**: Folders follow consistent categorization patterns
- **Version Control**: Semantic versioning applied consistently
- **Discoverability**: Clear descriptions at all levels

---

## Primary Repositories

### 1. aio3-brand-assets [AIO-BRAND]
**Code**: `aio3-brand-assets`  
**Aioverse Code**: `AIO-BRAND`  
**Repository URL**: `github.com/aio3-ai/Brand-ssets`  
**Purpose**: Centralized brand assets, typography, logos, icons, photos, guidelines  
**Key Folders**:
- `fonts/` [AIO-FONT] - Typography system
- `logos/` [AIO-LOGO] - Brand marks
- `icons/` [AIO-ICON] - UI icons
- `illustrations/` [AIO-ILLUS] - Custom artwork
- `photos/` [AIO-PHOTO] - Brand photography
- `guidelines/` [AIO-GUIDE] - Brand standards
- `tokens/` [AIO-TOKEN] - Design tokens

**Status**: Active  
**Maintained By**: Aiotize Design Systems Team  

---

### 2. aio3-design-system [AIO-DESIGN]
**Code**: `aio3-design-system`  
**Aioverse Code**: `AIO-DESIGN`  
**Purpose**: Component library, design patterns, and system documentation  
**Key Contents**:
- Component specifications [AIO-COMP]
- Design patterns [AIO-PATTERN]
- Usage documentation [AIO-DOC]
- Accessibility guidelines [AIO-A11Y]

**Status**: Active  
**Maintained By**: Aiotize Design Systems Team  

---

### 3. aio3-icon-system [AIO-ICON-SYSTEM]
**Code**: `aio3-icon-system`  
**Aioverse Code**: `AIO-ICON-SYSTEM`  
**Purpose**: Extended icon sets beyond brand-assets repository  
**Key Contents**:
- UI icon library [AIO-ICON-UI]
- Social media icons [AIO-ICON-SOCIAL]
- System icons [AIO-ICON-SYSTEM]
- Custom icon creation guides [AIO-ICON-GUIDE]

**Status**: Active  
**Maintained By**: Aiotize Design Systems Team  

---

### 4. aio3-component-library [AIO-COMPONENT-LIB]
**Code**: `aio3-component-library`  
**Aioverse Code**: `AIO-COMPONENT-LIB`  
**Purpose**: Reusable UI component implementations  
**Key Contents**:
- React/Vue components [AIO-COMP-REACT, AIO-COMP-VUE]
- Web components [AIO-COMP-WEB]
- Component documentation [AIO-COMP-DOC]
- Usage examples [AIO-COMP-EXAMPLE]

**Status**: Active  
**Maintained By**: Aiotize Engineering Team  

---

### 5. aio3-design-tokens [AIO-TOKEN-SYSTEM]
**Code**: `aio3-design-tokens`  
**Aioverse Code**: `AIO-TOKEN-SYSTEM`  
**Purpose**: Centralized design token management and distribution  
**Key Contents**:
- Color tokens [AIO-TOKEN-COLOR]
- Typography tokens [AIO-TOKEN-TYPO]
- Spacing tokens [AIO-TOKEN-SPACE]
- Animation tokens [AIO-TOKEN-ANIM]

**Status**: Active  
**Maintained By**: Aiotize Design Systems Team  

---

## Repository Naming Convention

### Format
```
aio3-[category]-[descriptor]
```

### Examples
```
aio3-brand-assets          → Brand and asset repository
aio3-design-system         → Design system
aio3-icon-system           → Extended icon collection
aio3-component-library     → Component implementations
aio3-design-tokens         → Token management
```

### Aioverse Code System

| Repository | Aioverse Code | Examples |
|------------|---------------|----------|
| Brand Assets | `AIO-BRAND` | AIO-BRAND-ASSETS |
| Design System | `AIO-DESIGN` | AIO-DESIGN-v1 |
| Icon System | `AIO-ICON-SYSTEM` | AIO-ICON-SYSTEM-001 |
| Component Library | `AIO-COMPONENT-LIB` | AIO-COMPONENT-LIB-REACT |
| Design Tokens | `AIO-TOKEN-SYSTEM` | AIO-TOKEN-SYSTEM-v1 |

---

## Organizational Structure

### Directory Hierarchy
```
aio3-*-repository/
├── README.md                      → Repository purpose
├── AIOVERSE_NAMING.md            → Naming conventions
├── [category]/                   → Asset or component folders
│   ├── [subcategory]/           → Organized items
│   └── [specific-asset]/        → Individual files
├── docs/                         → Documentation
│   ├── getting-started.md       → Quick start guide
│   ├── usage-guide.md           → Detailed usage
│   └── faq.md                   → Frequently asked questions
└── CHANGELOG.md                  → Version history
```

---

## Inter-Repository Dependencies

### Relationship Map
```
aio3-brand-assets
    ├─ provides tokens to → aio3-design-tokens
    ├─ provides icons to → aio3-icon-system
    └─ provides guidelines to → aio3-design-system

aio3-design-tokens
    └─ consumed by → aio3-component-library
                   → aio3-design-system

aio3-component-library
    ├─ uses → aio3-design-tokens
    ├─ uses → aio3-design-system
    └─ uses → aio3-brand-assets (fonts, colors)
```

---

## Naming Standards Across Repositories

### File Naming Pattern (Universal)
```
[AssetType]-[Descriptor]-[Variant]-[Version].[Format]
```

### Folder Naming Pattern (Universal)
```
[category]/[subcategory]/[specific-item]/
```

### Version Control (Universal)
- **Semantic Versioning**: v1.2.3 (MAJOR.MINOR.PATCH)
- **Date-Based**: YYYYMMDD-revision
- **Archive Naming**: [Name]-v[X]-ARCHIVED.[ext]

---

## Documentation Standards

### Every Repository Must Include

**Root Level**:
- [ ] `README.md` - Repository overview and quick start
- [ ] `AIOVERSE_NAMING.md` - Naming conventions specific to repository
- [ ] `CHANGELOG.md` - Version history
- [ ] `CONTRIBUTING.md` - Contribution guidelines

**In docs/ Folder**:
- [ ] `getting-started.md` - Beginner guide
- [ ] `usage-examples.md` - Code examples
- [ ] `best-practices.md` - Do's and don'ts
- [ ] `faq.md` - Common questions

**Folder Level**:
- [ ] Descriptive `.md` file for complex folders
- [ ] `.aioverse` config files for automation

---

## Description Templates

### For Repositories
```markdown
# [Repository Name] [AIO-CODE]

**Aioverse Code**: `AIO-CODE`  
**Purpose**: [Clear description of repository purpose]  
**Maintained By**: [Team name]  
**Last Updated**: [Date]  

## Quick Start
[Essential setup and usage steps]

## Documentation
- [AIOVERSE_NAMING.md](./AIOVERSE_NAMING.md) - Naming conventions
- [docs/](./docs/) - Detailed documentation
```

### For Folders
```markdown
### `folder-name/` [AIO-CODE]

**Aioverse Code**: `AIO-CODE`  
**Category**: [Category name]  
**Purpose**: [What this folder contains and why]  
**Usage**: [How to use items in this folder]  
**Naming Convention**: `[pattern]`  
```

---

## Governance & Maintenance

### Naming System Ownership
**Owner**: Aiotize Design Systems Team  
**Contact**: design-systems@aiotize.inc  
**Review Cycle**: Quarterly  

### Repository Ownership
| Repository | Owner | Contact |
|------------|-------|----------|
| aio3-brand-assets | Design Systems | design@aiotize.inc |
| aio3-design-system | Design Systems | design@aiotize.inc |
| aio3-icon-system | Design Systems | design@aiotize.inc |
| aio3-component-library | Engineering | engineering@aiotize.inc |
| aio3-design-tokens | Design Systems | design@aiotize.inc |

---

## Discovery & Navigation

### Finding Assets Across Ecosystem

1. **By Type** (Aioverse Code):
   - `AIO-FONT` → fonts/
   - `AIO-LOGO` → logos/
   - `AIO-ICON` → icons/ & aio3-icon-system
   - `AIO-TOKEN` → tokens/ & aio3-design-tokens

2. **By Purpose**:
   - **Branding** → aio3-brand-assets
   - **Components** → aio3-component-library
   - **Guidelines** → aio3-design-system
   - **Tokens** → aio3-design-tokens

3. **By Team**:
   - **Design Systems** → All design repositories
   - **Engineering** → component-library

---

## Future Extensions

### Planned Repositories
- `aio3-web-components` - Web standard components
- `aio3-animation-library` - Animation patterns
- `aio3-accessibility-guide` - A11y documentation
- `aio3-localization-assets` - Multi-language content

### Upcoming Features
- Automated asset discovery API
- Version conflict detection
- Cross-repository linking
- Automated changelog generation

---

## Quick Links

### Documentation
- [AIOVERSE_NAMING.md](./AIOVERSE_NAMING.md) - Comprehensive naming guide
- [FOLDER_STRUCTURE.md](./FOLDER_STRUCTURE.md) - Folder organization
- [README.md](./README.md) - Brand assets overview

### Related Repositories
- [aio3-design-system](https://github.com/aio3-ai/aio3-design-system)
- [aio3-component-library](https://github.com/aio3-ai/aio3-component-library)
- [aio3-design-tokens](https://github.com/aio3-ai/aio3-design-tokens)
- [aio3-icon-system](https://github.com/aio3-ai/aio3-icon-system)

---

**Aioverse v1.0** - December 2025  
**Made by the Aiotize Design Systems Team**  
Part of Aiotize Inc.'s universal naming and organizational framework
