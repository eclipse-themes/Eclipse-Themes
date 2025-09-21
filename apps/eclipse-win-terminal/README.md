# Eclipse Midnight Terminal Theme

Bring the Eclipse Midnight theme to your Windows Terminal, Command Prompt, and PowerShell!

## 📁 Folder & File Structure

- **Folder:** `eclipse-win-terminal`   
- **File:** `eclipse-midnight.json` → contains the full theme JSON

## 🚀 Quick & Easy Installation

### 1. Open Windows Terminal Settings
- Press `Ctrl + ,` **or** click the down arrow → **Settings**.

### 2. Add the Theme
1. Open your `settings.json` by clicking **Open JSON file** in Settings.
2. Copy the contents of the `eclipse-win-terminal.json` file from this folder.
3. Paste it **inside your JSON root**, replacing or adding under `"schemes"`.

### 3. Apply to Profiles
Inside the `"profiles"` → `"list"` section, add the following to every profile you want to use the theme with (PowerShell, CMD, WSL, etc.):

```json
"colorScheme": "Eclipse Midnight"
```

### 4. Save & Enjoy
Save `settings.json` and open a new tab in Terminal — your Eclipse Dawn theme should be active!

## ℹ️ Notes
- Works in Windows Terminal, PowerShell, Command Prompt, and WSL.
- Cursor, selection, and ANSI colors match the Eclipse Midnight theme.
- For best results, use with a font that supports ligatures and powerline symbols.

## 🔄 Troubleshooting
If the theme doesn't appear:
1. Ensure the JSON is properly formatted in your `settings.json`
2. Check for any syntax errors in the JSON
3. Restart Windows Terminal if changes don't take effect immediately