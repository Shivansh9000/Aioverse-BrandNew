# Brand Assets Folder Structure

This repository follows a clear, scalable organizational system for brand assets and design tokens.

## Top-Level Folders

### `fonts/`
Contains all typeface files organized by usage category.
- `primary/Nohemi/` - Primary brand typeface
- `secondary/TokyoTrailMono/` - Secondary/accent typeface

### `logos/`
Brand logo files in various formats and sizes.

### `illustrations/`
Brand illustrations and custom artwork.

### `icons/`
Icon sets and UI icons (SVG, PNG, etc.).

### `photos/`
Brand photography and image assets.

### `guidelines/`
Brand guidelines documentation and reference materials.

### `tokens/`
Design tokens source of truth.
- Contains the Asset Tokens file (design system variables)
- Can be extended with subfolders:
  - `json/` - JSON export format
  - `css/` - CSS variable exports
  - `figma/` - Figma token files

## Usage

1. **Designers**: Use `guidelines/` and `logos/` for brand reference
2. **Developers**: Reference `tokens/` for color scales, spacing, typography
3. **Asset Management**: Add new files to appropriate type-based folders

## Naming Conventions

- Use descriptive folder names (lowercase, hyphens for spaces)
- Keep file names consistent and version-numbered when needed
- Use subfolders within main categories for further organization
