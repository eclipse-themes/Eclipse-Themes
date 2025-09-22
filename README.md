<div align="center">
  <h1>
    <img src="Assets/Eclipse.png" alt="Eclipse Midnight Logo" height="40" style="vertical-align: middle; margin-right: 15px;"/>
    Eclipse Midnight
  </h1>
</div>

A beautiful dark theme inspired by lunar eclipses, designed for people who appreciate a sleek, modern interface with excellent contrast and readability.

## 🌟 Theme Previews

<details>
<summary>💻 Editor Preview</summary>

<div align="center">
  <img src="Assets/EclipseEditor.png" alt="Eclipse Midnight Editor View" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.2); max-width: 100%;"/>
  <p><em>Eclipse Midnight in Action</em></p>
</div>
</details>

<details>
<summary>📦 Extension Page</summary>

<div align="center">
  <img src="Assets/EclipseExtensionPage.jpg" alt="Eclipse Midnight Extension Page" style="border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.2); max-width: 100%;"/>
  <p><em>Eclipse Midnight Extension Page</em></p>
</div>
</details>


## 🎨 Brand & Color Guidelines

For detailed color specifications, naming conventions, and usage guidelines, please refer to our comprehensive [Brand Guidelines](BRAND_GUIDELINES.md). This includes the complete color palette, terminal colors, and implementation details for maintaining visual consistency across all Eclipse Midnight themes.

## 🚀 Installation

1. Open the **Extensions** view in VS Code (`Ctrl+Shift+X` or `Cmd+Shift+X`)
2. Search for "Eclipse Theme - Midnight"
3. Click **Install**
4. Open the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P`)
5. Select **Preferences: Color Theme** and choose "Eclipse Midnight"

## 🛠️ Customization

You can customize the theme by adding these settings to your `settings.json`:

```json
{
  "workbench.colorCustomizations": {
    "[Eclipse Midnight]": {
      "editor.background": "#1a1825",
      "sideBar.background": "#151320"
    }
  },
  "editor.tokenColorCustomizations": {
    "[Eclipse Midnight]": {
      "textMateRules": [
        {
          "scope": "comment",
          "settings": {
            "fontStyle": "italic"
          }
        }
      ]
    }
  },
  "editor.tokenColorCustomizations": {
    "[Eclipse Midnight]": {
      "textMateRules": [
        {
          "scope": "keyword",
          "settings": {
            "foreground": "#c5a7ff"
          }
        },
        {
          "scope": "variable",
          "settings": {
            "foreground": "#8effd9"
          }
        }
      ]
    }
  }
}
```

## 📦 Applications

### VS Code Theme
- [Install from Marketplace](https://marketplace.visualstudio.com/items?itemName=Eclipse-Theme.eclipse-theme-midnight)
- [GitHub Repository](https://github.com/eclipse-themes/Eclipse-Themes/tree/main/apps/vscode)

## 📝 License

Eclipse Midnight is licensed under the MIT License. See [LICENSE](LICENSE) for more information.


## 📄 License

This project is licensed under the [MIT License](LICENSE).
