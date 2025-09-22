# Contributing to Eclipse Themes

Thank you for your interest in contributing to Eclipse Themes! This guide will help you create and submit themes for various applications.

## 🎨 Creating a New Theme

### 1. Create a New Repository
```bash
# Repository Naming
Eclipse-Theme-{app-name}

# Examples:
Eclipse-Theme-vscode
Eclipse-Theme-winterm
Eclipse-Theme-intellij
```

### 2. Required Files
```
Eclipse-Theme-{app-name}/
├── README.md          # Installation and usage instructions
├── theme.json         # Theme configuration
└── screenshots/       # Screenshots of your theme
    ├── light.png      # Light variant (if applicable)
    └── dark.png       # Dark variant
```

### 3. Theme Guidelines
- Follow our official color palette
- Maintain accessibility (minimum 4.5:1 contrast ratio)
- Include both light and dark variants if the application supports it
- Test your theme thoroughly before submission
- Document any special requirements or customizations

## 🎨 Color Palette

<div style="display: flex; flex-wrap: wrap; gap: 2rem; margin: 2rem 0;">

### 🌙 Eclipse Dark

#### Core Colors
| Role | Hex | Usage |
|------|-----|-------|
| Background | `#1e1e2e` | Main background |
| Foreground | `#cdd6f4` | Primary text |
| Accent | `#cba6f7` | Primary UI elements |
| Highlight | `#89b4fa` | Secondary UI elements |
| Muted | `#6c7086` | Comments, line numbers |
| Selection | `#45475a` | Selected text |

#### Syntax
| Element | Hex |
|---------|-----|
| Keywords | `#cba6f7` |
| Functions | `#89b4fa` |
| Strings | `#a6e3a1` |
| Numbers | `#fab387` |
| Types | `#f9e2af` |
| Variables | `#cdd6f4` |
| Tags | `#f38ba8` |
| Attributes | `#f9e2af` |

</div>

<div style="display: flex; flex-wrap: wrap; gap: 2rem; margin: 2rem 0;">

### ☀️ Eclipse Dawn

#### Core Colors
| Role | Hex | Usage |
|------|-----|-------|
| Background | `#eff1f5` | Main background |
| Foreground | `#4c4f69` | Primary text |
| Accent | `#8839ef` | Primary UI elements |
| Highlight | `#1e66f5` | Secondary UI elements |
| Muted | `#9ca0b0` | Comments, line numbers |
| Selection | `#ccd0da` | Selected text |

#### Syntax
| Element | Hex |
|---------|-----|
| Keywords | `#8839ef` |
| Functions | `#1e66f5` |
| Strings | `#40a02b` |
| Numbers | `#fe640b` |
| Types | `#df8e1d` |
| Variables | `#4c4f69` |
| Tags | `#d20f39` |
| Attributes | `#df8e1d` |

</div>

### Terminal Colors

#### Eclipse Dark Terminal
| Color | Hex |
|-------|-----|
| Black | `#45475a` |
| Red | `#f38ba8` |
| Green | `#a6e3a1` |
| Yellow | `#f9e2af` |
| Blue | `#89b4fa` |
| Magenta | `#f5c2e7` |
| Cyan | `#94e2d5` |
| White | `#bac2de` |
| Bright Black | `#585b70` |
| Bright Red | `#f38ba8` |
| Bright Green | `#a6e3a1` |
| Bright Yellow | `#f9e2af` |
| Bright Blue | `#89b4fa` |
| Bright Magenta | `#f5c2e7` |
| Bright Cyan | `#94e2d5` |
| Bright White | `#a6adc8` |

#### Eclipse Dawn Terminal
| Color | Hex |
|-------|-----|
| Black | `#dce0e8` |
| Red | `#d20f39` |
| Green | `#40a02b` |
| Yellow | `#df8e1d` |
| Blue | `#1e66f5` |
| Magenta | `#ea76cb` |
| Cyan | `#179299` |
| White | `#4c4f69` |
| Bright Black | `#9ca0b0` |
| Bright Red | `#d20f39` |
| Bright Green | `#40a02b` |
| Bright Yellow | `#df8e1d` |
| Bright Blue | `#1e66f5` |
| Bright Magenta | `#ea76cb` |
| Bright Cyan | `#179299` |
| Bright White | `#4c4f69` |

## 📝 README Requirements
Your theme's README.md should include:

```markdown
# Eclipse Theme for [App Name]

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A beautiful Eclipse theme for [App Name].

## ✨ Features
- Light and dark variants
- Optimized for [specific use cases]
- [Other notable features]

## 🚀 Installation

### Method 1: [Recommended Method]
1. [Step-by-step instructions]
2. [Any configuration needed]
3. [How to activate/select the theme]

### Method 2: [Alternative Method]
[Alternative installation steps]

## 🎨 Customization
[Any customization options available]

## 📸 Screenshots
[Add screenshots with captions]

## 🤝 Contributing
Contributions are welcome! Please read our [contributing guidelines](CONTRIBUTING.md).

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

## 📤 Submitting Your Theme
1. Fork this repository
2. Create a new branch: `git checkout -b my-theme`
3. Add your theme files
4. Commit your changes: `git commit -m 'feat: add Eclipse Theme for [App Name]'`
5. Push to the branch: `git push origin my-theme`
6. Open a Pull Request
7. Create a new [Theme Submission](https://github.com/eclipse-themes/Eclipse-Themes/issues/new?template=theme-submission.yml) issue

## 🔍 Review Process
- Initial review within 1-2 weeks
- May request adjustments for consistency
- Once approved, your theme will be:
  - Added to our official list
  - Featured in our showcase
  - Included in future updates

## 💡 Tips for Great Themes
- Test with real code in different languages
- Ensure good contrast in all UI elements
- Document any special requirements
- Include helpful screenshots
- Keep the README updated

# Contributing to Eclipse Themes

Thank you for your interest in contributing to Eclipse Themes! This document provides guidelines for contributing to the Eclipse Midnight theme.

## 🎨 Color Palette Reference

### Core Colors
- **Midnight Base**: `#1a1825` (Primary background)
- **Deep Space**: `#151320` (Secondary background)
- **Cosmic Void**: `#212030` (Tertiary background)
- **Nebula**: `#2d2b40` (Hover/Inactive states)
- **Eclipse Shadow**: `#3a384a` (Active/Selected states)

### Text Colors
- **Starlight**: `#f0f0f7` (Primary text)
- **Moonlight**: `#c0c0d0` (Secondary text)
- **Cosmic Dust**: `#7d7b95` (Muted/Disabled text)
- **Event Horizon**: `#252337` (Borders and dividers)
- **Lunar Surface**: `#353447` (Input borders)

### Accent Colors
- **Cosmic Violet**: `#9a86fd` (Primary brand color)
- **Stellar Blue**: `#8ab2ff` (Secondary accent)
- **Nebula Purple**: `#c5a7ff` (Tertiary accent)
- **Quantum Mint**: `#8effd9` (Success/Positive actions)
- **Solar Flare**: `#ffa874` (Warning/Attention)
- **Nova Red**: `#ff7d95` (Error/Destructive actions)
- **Lunar Gold**: `#e2c792` (Highlight/Important info)

## 🚀 Getting Started

1. **Fork** the repository on GitHub
2. **Clone** your fork locally
   ```bash
   git clone https://github.com/your-username/Eclipse-Themes.git
   cd Eclipse-Themes
   ```
3. **Install** dependencies
   ```bash
   npm install
   ```
4. **Create a branch** for your changes
   ```bash
   git checkout -b fix/your-fix-name
   # or
   git checkout -b feature/your-feature-name
   ```

## 🔧 Development Workflow

1. Make your changes in your feature branch
2. Test your changes in VS Code's Extension Development Host
3. Run the linter
   ```bash
   npm run lint
   ```
4. Commit your changes with a descriptive message following [Conventional Commits](https://www.conventionalcommits.org/):
   ```bash
   git commit -m "feat: add new syntax highlighting for TypeScript"
   # or
   git commit -m "fix: correct contrast in sidebar"
   ```
5. Push your changes to your fork
   ```bash
   git push origin your-branch-name
   ```

## 📝 Submitting Changes

1. Open a **Pull Request** against the `main` branch
2. Fill out the PR template with details about your changes
3. Include before/after screenshots for visual changes
4. Ensure all tests pass and there are no merge conflicts
5. Request a review from one of the maintainers

## 🐛 Reporting Issues

When reporting issues, please include:

- **Description**: Clear explanation of the issue
- **Steps to Reproduce**: Step-by-step instructions to reproduce
- **Expected vs Actual**: What you expected to happen vs what actually happened
- **Screenshots**: Visual examples if applicable
- **Environment**:
  - OS: [e.g., Windows 11, macOS 14, Ubuntu 22.04]
  - VS Code Version: [e.g., 1.85.0]
  - Theme Version: [e.g., 0.3.1]

## 💡 Feature Requests

We welcome feature requests! Please include:
- A clear description of the feature
- The problem it solves
- Any relevant examples or references
- Screenshots or mockups if applicable

## 🎨 Design Guidelines

- Maintain a minimum contrast ratio of 4.5:1 for text
- Use the defined color palette consistently
- Follow VS Code's theming guidelines
- Keep the theme feeling cohesive and professional
- Test changes in both light and dark UIs

## 📜 Code Style

- Use 2 spaces for indentation in JSON files
- Sort color keys alphabetically in theme files
- Keep lines under 100 characters
- Add comments for non-obvious color usage
- Follow existing naming conventions

## 📝 Commit Message Format

We follow [Conventional Commits](https://www.conventionalcommits.org/):

```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

**Types**:
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Code style changes (formatting, etc.)
- `refactor`: Code changes that neither fix bugs nor add features
- `perf`: Performance improvements
- `test`: Adding or modifying tests
- `chore`: Changes to the build process or auxiliary tools

## 📄 License

By contributing to Eclipse Themes, you agree that your contributions will be licensed under the [MIT License](LICENSE).
