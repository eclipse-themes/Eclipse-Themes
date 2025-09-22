# Contributing to Eclipse Midnight

Thank you for your interest in contributing to Eclipse Midnight! This guide will help you create and submit themes for various applications.

## 📋 Table of Contents
- [Brand Guidelines](#-brand--color-guidelines)
- [Creating a New Theme](#-creating-a-new-theme)
- [Theme Structure](#-theme-structure)
- [Submitting Your Theme](#-submitting-your-theme)
- [Review Process](#-review-process)
- [Testing](#-testing)
- [Feature Requests & Bug Reports](#-feature-requests--bug-reports)
- [Design Guidelines](#-design--code-style)

## 🎨 Brand & Color Guidelines

Before you start, please review our comprehensive [Brand Guidelines](BRAND_GUIDELINES.md) for detailed information about:
- Color palette and naming conventions
- Dark theme specifications
- Terminal color schemes
- UI component styling
- Syntax highlighting guidelines
- Accessibility standards

All themes should follow these guidelines to maintain visual consistency across the Eclipse Midnight ecosystem.

## 🎨 Creating a New Theme

### 1. Repository Setup
```bash
# Create a new repository with the naming convention:
eclipse-midnight-{app-name}

# Examples:
# eclipse-midnight-vscode
# eclipse-midnight-winterm
# eclipse-midnight-intellij
```

### 2. Required Files Structure
```
Eclipse-Theme-{app-name}/
├── README.md          # Installation and usage instructions
├── theme.json         # Theme configuration
└── screenshots/       # Screenshots of your theme
    └── dark.png       # Dark variant
```

### 3. Theme Guidelines
- Follow our official color palette from the Brand Guidelines
- Maintain accessibility (minimum 4.5:1 contrast ratio)
- Include both light and dark variants if the application supports it
- Test your theme thoroughly before submission
- Document any special requirements or customizations

## 🏗️ Theme Structure

### Core Components
1. **Color Scheme**: Use the colors defined in [Brand Guidelines](BRAND_GUIDELINES.md)
2. **Syntax Highlighting**: Follow the token color guidelines
3. **UI Components**: Style according to the application's theming system
4. **Terminal**: Implement the terminal color scheme from the guidelines

### README Requirements
Your theme's README.md should include:
- Installation instructions
- Screenshots
- Customization options
- Contribution guidelines
- License information

## 📤 Submitting Your Theme
1. Create a new repository for your theme (e.g., `eclipse-midnight-yourthemename`)
2. Push your theme code to your repository
   ```bash
   git remote add origin https://github.com/your-username/eclipse-midnight-yourthemename.git
   git branch -M main
   git push -u origin main
   ```
3. Create a new [Theme Submission](https://github.com/eclipse-themes/Eclipse-Themes/issues/new?template=theme-submission.yml) issue with:
   - A link to your repository
   - A brief description of your theme
   - Screenshots of the theme in action

## 🔍 Review Process
- Initial review within 1-2 weeks
- May request adjustments for consistency
- Once approved, your theme will be:
  - Added to our official list
  - Featured in our showcase
  - Included in future updates

## ✅ Testing

Please ensure your changes work in:
- [ ] Dark theme
- [ ] High contrast mode (if applicable)
- [ ] Different operating systems (Windows, macOS, Linux)

## 💡 Feature Requests & Bug Reports

We welcome contributions! When submitting:
- Clearly describe the feature or bug
- Include steps to reproduce (for bugs)
- Add screenshots or mockups if applicable
- Specify the environment (OS, application version, etc.)

## 🎨 Design & Code Style

### Design Guidelines
- Maintain a minimum contrast ratio of 4.5:1 for text
- Use the defined color palette consistently
- Follow the application's theming guidelines
- Keep the theme cohesive and professional
