# Contributing to Eclipse Midnight

Thank you for your interest in contributing to Eclipse Midnight! This guide will help you create and submit themes for various applications.

## 🎨 Brand & Color Guidelines

Before you start, please review our comprehensive [Brand Guidelines](BRAND_GUIDELINES.md) for detailed information about:
- Color palette and naming conventions
- Light and dark theme specifications
- Terminal color schemes
- UI component styling
- Syntax highlighting guidelines
- Accessibility standards

All themes should follow these guidelines to maintain visual consistency across the Eclipse Midnight ecosystem.

## 🎨 Creating a New Theme

### 1. Create a New Repository
```bash
# Repository Naming
eclipse-midnight-{app-name}

# Examples:
eclipse-midnight-vscode
eclipse-midnight-winterm
eclipse-midnight-intellij
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

## Color Scheme Reference

For a complete reference to the Eclipse Midnight color scheme, including both dark and light variants, please see the [Brand Guidelines](BRAND_GUIDELINES.md). The guidelines provide detailed information about:

- Core color palette for both dark and light themes
- Syntax highlighting colors
- Terminal color schemes
- UI component styling
- Accessibility considerations

All new themes should follow these guidelines to maintain consistency with the Eclipse Midnight design system.

### Terminal Colors

For terminal color schemes and specifications, please refer to the [Terminal Colors](BRAND_GUIDELINES.md#terminal-colors) section in our Brand Guidelines.

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
4. Commit your changes: `git commit -m 'feat: add Eclipse Midnight theme for [App Name]'`
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

# Contributing to Eclipse Midnight

Thank you for your interest in contributing to Eclipse Midnight! This document provides guidelines for contributing to the theme.

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

By contributing to Eclipse Midnight, you agree that your contributions will be licensed under the [MIT License](LICENSE).
