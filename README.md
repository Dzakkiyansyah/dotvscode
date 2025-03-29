# My VS Code Settings Configuration 🚀

## 📋 Introduction
This repository contains my personal VS Code settings configuration that works across:
- Windows
- Linux 
- WSL (Windows Subsystem for Linux)

## ⚙️ Configuration

```json
{
  // ============== Editor Settings ==============
  "editor.fontSize": 16,
  "editor.fontFamily": "'Monospace Nerd Font', 'Fira Code', 'JetBrainsMono Nerd Font', monospace",
  "editor.fontLigatures": true,
  "editor.tabSize": 2,
  "editor.formatOnSave": true,
  "editor.codeActionsOnSave": {
    "source.fixAll": "explicit",
    "source.sortImports": "explicit"
  },
  "editor.mouseWheelZoom": true,
  "editor.wordWrap": "on",
  "editor.minimap.enabled": true,
  
  // Editor Visuals
  "editor.renderWhitespace": "none",
  "editor.renderLineHighlight": "none",
  "editor.matchBrackets": "never",
  "editor.showFoldingControls": "never",
  "editor.overviewRulerBorder": false,
  "editor.cursorBlinking": "phase",
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.stickyScroll.enabled": false,
  "editor.hover.enabled": false,
  "editor.lightbulb.enabled": "on",

  // ============== Workbench/UI Settings ==============
  "workbench.colorTheme": "poimandres",
  "workbench.iconTheme": "symbols",
  "workbench.sideBar.location": "right",
  "workbench.startupEditor": "none",
  "workbench.tips.enabled": false,
  "workbench.tree.renderIndentGuides": "none",
  "breadcrumbs.enabled": false,
  "material-icon-theme.hidesExplorerArrows": true,

  // ============== Terminal Settings ==============
  "terminal.integrated.fontFamily": "'Monospace Nerd Font', 'Fira Code', 'JetBrainsMono Nerd Font'",
  "terminal.integrated.fontSize": 14,
  "terminal.integrated.defaultProfile.windows": "PowerShell",
  "terminal.integrated.defaultProfile.linux": "zsh",

  // ============== File/Explorer Settings ==============
  "files.autoSave": "afterDelay",
  "explorer.confirmDragAndDrop": false,
  "explorer.confirmDelete": false,
  "explorer.compactFolders": false,

  // ============== WSL Settings ==============
  "remote.WSL.defaultBehaviour": "openNewWindow",
  "remote.WSL.autoReconnect": false,

  // ============== Language Specific ==============
  "[markdown]": {
    "editor.formatOnSave": true,
    "editor.formatOnPaste": true
  },
  "blade.format.enable": true,

  // ============== Extensions Settings ==============
  // Spell Checker
  "cSpell.language": "en, id",
  "cSpell.enabled": false,
  "cSpell.allowCompoundWords": true,

  // Prettier
  "editor.defaultFormatter": "esbenp.prettier-vscode",

  // Emmet
  "emmet.triggerExpansionOnTab": true,

  // Live Server
  "liveServer.settings.donotShowInfoMsg": true,
}
