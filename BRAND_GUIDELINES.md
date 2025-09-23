# Eclipse Theme Brand Guidelines

## Table of Contents
- [🎨 Color Palette](#-color-palette)
  - [Core Colors](#core-colors)
  - [Text & UI](#text--ui)
  - [Accent Colors](#accent-colors)
- [Terminal Colors](#terminal-colors)
  - [Standard Colors](#standard-colors)
  - [Bright Colors](#bright-colors)
- [UI Component Colors](#ui-component-colors)
  - [Buttons](#buttons)
  - [Input Fields](#input-fields)
  - [Selection](#selection)
- [Syntax Highlighting](#syntax-highlighting)
- [Usage Guidelines](#usage-guidelines)
- [Accessibility](#accessibility)
- [Implementation Notes](#implementation-notes)

---

## 🎨 Color Palette

### Core Colors

| Color | Name | Hex | Usage |
|-------|------|-----|-------|
| ![](https://placehold.co/24x24/1a1825/1a1825.png) | Midnight Base | `#1a1825` | Primary background |
| ![](https://placehold.co/24x24/151320/151320.png) | Deep Space | `#151320` | Secondary background |
| ![](https://placehold.co/24x24/212030/212030.png) | Cosmic Void | `#212030` | Input backgrounds |
| ![](https://placehold.co/24x24/2d2b40/2d2b40.png) | Nebula | `#2d2b40` | Hover states |
| ![](https://placehold.co/24x24/3a384a/3a384a.png) | Eclipse Shadow | `#3a384a` | Active/Selected states |

### Text & UI

| Color | Name | Hex | Usage |
|-------|------|-----|-------|
| ![](https://placehold.co/24x24/f0f0f7/f0f0f7.png) | Starlight | `#f0f0f7` | Primary text |
| ![](https://placehold.co/24x24/c0c0d0/c0c0d0.png) | Moonlight | `#c0c0d0` | Secondary text |
| ![](https://placehold.co/24x24/7d7b95/7d7b95.png) | Cosmic Dust | `#7d7b95` | Muted/Disabled text |
| ![](https://placehold.co/24x24/252337/252337.png) | Event Horizon | `#252337` | Borders and dividers |
| ![](https://placehold.co/24x24/353447/353447.png) | Lunar Surface | `#353447` | Input borders |

### Accent Colors

| Color | Name | Hex | Usage |
|-------|------|-----|-------|
| ![](https://placehold.co/24x24/9a86fd/9a86fd.png) | Cosmic Violet | `#9a86fd` | Primary brand color, main actions |
| ![](https://placehold.co/24x24/8ab2ff/8ab2ff.png) | Stellar Blue | `#8ab2ff` | Secondary actions, links |
| ![](https://placehold.co/24x24/c5a7ff/c5a7ff.png) | Nebula Purple | `#c5a7ff` | Tertiary actions, highlights |
| ![](https://placehold.co/24x24/8effd9/8effd9.png) | Quantum Mint | `#8effd9` | Success states, positive actions |
| ![](https://placehold.co/24x24/ffa874/ffa874.png) | Solar Flare | `#ffa874` | Warnings, attention needed |
| ![](https://placehold.co/24x24/ff7d95/ff7d95.png) | Nova Red | `#ff7d95` | Errors, destructive actions |
| ![](https://placehold.co/24x24/e2c792/e2c792.png) | Lunar Gold | `#e2c792` | Highlights, special text |

<details>
<summary>## Terminal Colors</summary>

### Standard Colors

| Color | Hex | Usage |
|-------|-----|-------|
| ![](https://placehold.co/24x24/1a1825/1a1825.png) Black | `#1a1825` | Background, standard black |
| ![](https://placehold.co/24x24/ff7d95/ff7d95.png) Red | `#ff7d95` | Errors, deletions |
| ![](https://placehold.co/24x24/8effd9/8effd9.png) Green | `#8effd9` | Success, additions |
| ![](https://placehold.co/24x24/ffa874/ffa874.png) Yellow | `#ffa874` | Warnings, changes |
| ![](https://placehold.co/24x24/8ab2ff/8ab2ff.png) Blue | `#8ab2ff` | Links, information |
| ![](https://placehold.co/24x24/c5a7ff/c5a7ff.png) Magenta | `#c5a7ff` | Special elements |
| ![](https://placehold.co/24x24/8dd9ff/8dd9ff.png) Cyan | `#8dd9ff` | Secondary information |
| ![](https://placehold.co/24x24/f0f0f7/f0f0f7.png) White | `#f0f0f7` | Standard text |

### Bright Colors

| Color | Hex | Usage |
|-------|-----|-------|
| ![](https://placehold.co/24x24/7d7b95/7d7b95.png) Bright Black | `#7d7b95` | Muted text |
| ![](https://placehold.co/24x24/ff95a9/ff95a9.png) Bright Red | `#ff95a9` | Light errors |
| ![](https://placehold.co/24x24/a1ffe4/a1ffe4.png) Bright Green | `#a1ffe4` | Light success |
| ![](https://placehold.co/24x24/ffb88f/ffb88f.png) Bright Yellow | `#ffb88f` | Light warnings |
| ![](https://placehold.co/24x24/a5b8ff/a5b8ff.png) Bright Blue | `#a5b8ff` | Light information |
| ![](https://placehold.co/24x24/d2bfff/d2bfff.png) Bright Magenta | `#d2bfff` | Light special |
| ![](https://placehold.co/24x24/a5dfff/a5dfff.png) Bright Cyan | `#a5dfff` | Light secondary |
| ![](https://placehold.co/24x24/ffffff/ffffff.png) Bright White | `#ffffff` | Intense text |

</details>

<details>
<summary>## UI Component Colors</summary>

### Buttons

| Element | Color | Hex |
|---------|-------|-----|
| ![](https://placehold.co/24x24/3a3550/3a3550.png) Normal | Button Normal | `#3a3550` |
| ![](https://placehold.co/24x24/4a4560/4a4560.png) Hover | Button Hover | `#4a4560` |
| ![](https://placehold.co/24x24/f0f0f7/f0f0f7.png) Text | Button Text | `#f0f0f7` |

### Input Fields

| Element | Color | Hex |
|---------|-------|-----|
| ![](https://placehold.co/24x24/212030/212030.png) Background | Input Background | `#212030` |
| ![](https://placehold.co/24x24/353447/353447.png) Border | Input Border | `#353447` |
| ![](https://placehold.co/24x24/f0f0f7/f0f0f7.png) Text | Input Text | `#f0f0f7` |
| ![](https://placehold.co/24x24/7d7b95/7d7b95.png) Placeholder | Input Placeholder | `#7d7b95` |

### Selection

| Element | Color | Hex |
|---------|-------|-----|
| ![](https://placehold.co/24x24/3a384a/3a384a.png) Background | Selection Background | `#3a384a` |
| ![](https://placehold.co/24x24/2d2b40/2d2b40.png) Inactive | Inactive Selection | `#2d2b40` |

</details>

<details>
<summary>## Syntax Highlighting</summary>

| Element | Color | Hex |
|---------|-------|-----|
| ![](https://placehold.co/24x24/c5a7ff/c5a7ff.png) Keywords | Nebula Purple | `#c5a7ff` |
| ![](https://placehold.co/24x24/8ab2ff/8ab2ff.png) Functions | Stellar Blue | `#8ab2ff` |
| ![](https://placehold.co/24x24/e2c792/e2c792.png) Strings | Lunar Gold | `#e2c792` |
| ![](https://placehold.co/24x24/ffa874/ffa874.png) Numbers | Solar Flare | `#ffa874` |
| ![](https://placehold.co/24x24/8effd9/8effd9.png) Types | Quantum Mint | `#8effd9` |
| ![](https://placehold.co/24x24/f0f0f7/f0f0f7.png) Variables | Starlight | `#f0f0f7` |
| ![](https://placehold.co/24x24/ff7d95/ff7d95.png) Tags | Nova Red | `#ff7d95` |
| ![](https://placehold.co/24x24/8effd9/8effd9.png) Attributes | Quantum Mint | `#8effd9` |
| ![](https://placehold.co/24x24/7d7b95/7d7b95.png) Comments | Cosmic Dust | `#7d7b95` |

</details>

## Usage Guidelines

1. **Primary Accent**: Use Cosmic Violet (`#9a86fd`) for primary actions and important UI elements.
2. **Secondary Actions**: Use Stellar Blue (`#8ab2ff`) for secondary actions and links.
3. **Success States**: Use Quantum Mint (`#8effd9`) to indicate successful operations.
4. **Warnings**: Use Solar Flare (`#ffa874`) for warning messages and non-critical alerts.
5. **Errors**: Use Nova Red (`#ff7d95`) for error messages and destructive actions.
6. **Text**: Use Starlight (`#f0f0f7`) for primary text and Moonlight (`#c0c0d0`) for secondary text.
7. **Backgrounds**: Use Midnight Base (`#1a1825`) for main backgrounds and Deep Space (`#151320`) for secondary panels.

## Accessibility
- Ensure text has sufficient contrast (minimum 4.5:1 for normal text, 3:1 for large text)
- Use semantic colors consistently (e.g., red for errors, green for success)
- Provide alternative text for color-coded information
- Test with color blindness simulators for accessibility

## Implementation Notes
- When implementing in CSS/SCSS, use CSS variables for theming
- For terminal themes, follow the color mapping provided in the Terminal Colors section
- For syntax highlighting, use the specified colors for each token type
- Always test the theme in both light and dark environments

