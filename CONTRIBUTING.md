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
