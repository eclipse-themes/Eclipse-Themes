# Eclipse Theme Brand Guidelines

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

## Terminal Colors

### Standard Colors

| Color | Hex | Usage |
|-------|-----|-------|
| Black | `#1a1825` | Background, standard black |
| Red | `#ff7d95` | Errors, deletions |
| Green | `#8effd9` | Success, additions |
| Yellow | `#ffa874` | Warnings, changes |
| Blue | `#8ab2ff` | Links, information |
| Magenta | `#c5a7ff` | Special elements |
| Cyan | `#8dd9ff` | Secondary information |
| White | `#f0f0f7` | Standard text |

### Bright Colors

| Color | Hex | Usage |
|-------|-----|-------|
| Bright Black | `#7d7b95` | Muted text |
| Bright Red | `#ff95a9` | Light errors |
| Bright Green | `#a1ffe4` | Light success |
| Bright Yellow | `#ffb88f` | Light warnings |
| Bright Blue | `#a5b8ff` | Light information |
| Bright Magenta | `#d2bfff` | Light special |
| Bright Cyan | `#a5dfff` | Light secondary |
| Bright White | `#ffffff` | Intense text |

## UI Component Colors

### Buttons
- Normal: `#3a3550`
- Hover: `#4a4560`
- Text: `#f0f0f7`

### Input Fields
- Background: `#212030`
- Border: `#353447`
- Text: `#f0f0f7`
- Placeholder: `#7d7b95`

### Selection
- Background: `#3a384a`
- Inactive: `#2d2b40`

## Syntax Highlighting

| Element | Color | Hex |
|---------|-------|-----|
| Keywords | Nebula Purple | `#c5a7ff` |
| Functions | Stellar Blue | `#8ab2ff` |
| Strings | Lunar Gold | `#e2c792` |
| Numbers | Solar Flare | `#ffa874` |
| Types | Quantum Mint | `#8effd9` |
| Variables | Starlight | `#f0f0f7` |
| Tags | Nova Red | `#ff7d95` |
| Attributes | Quantum Mint | `#8effd9` |
| Comments | Cosmic Dust | `#7d7b95` |

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

## License
These brand guidelines are part of the Eclipse Theme project and are available under the MIT License.
