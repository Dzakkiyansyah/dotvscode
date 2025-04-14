# My VS Code Settings Configuration 🚀

## 📋 Introduction
This repository contains my personal VS Code settings configuration that works across:
- Windows
- Linux 
- WSL (Windows Subsystem for Linux)

## ⚙️ Configuration

```json
{
  // ================= Editor Settings =================
  "editor.fontSize": 16,
  "editor.fontFamily": "'Monospace Nerd Font', 'Fira Code', 'JetBrainsMono Nerd Font', monospace",
  "editor.fontLigatures": true,
  "editor.tabSize": 2,
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.codeActionsOnSave": {
    "source.fixAll": "explicit",
    "source.fixAll.eslint": "always",
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

  // ================= Workbench / UI Settings =================
  "workbench.colorTheme": "Andromeda",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.sideBar.location": "right",
  "workbench.startupEditor": "none",
  "workbench.tips.enabled": false,
  "workbench.tree.renderIndentGuides": "none",
  "breadcrumbs.enabled": false,
  "material-icon-theme.hidesExplorerArrows": true,

  // ================= Terminal Settings =================
  "terminal.integrated.fontFamily": "'Monospace Nerd Font', 'Fira Code', 'JetBrainsMono Nerd Font'",
  "terminal.integrated.fontSize": 14,
  "terminal.integrated.defaultProfile.windows": "Git Bash",
  // "terminal.integrated.defaultProfile.linux": "zsh", // Aktifkan kalau pakai Linux & zsh

  // ================= File / Explorer Settings =================
  "files.autoSave": "afterDelay",
  "explorer.confirmDragAndDrop": false,
  "explorer.confirmDelete": false,
  "explorer.compactFolders": false,

  // ================= Language Specific Settings =================
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[markdown]": {
    "editor.formatOnSave": true,
    "editor.formatOnPaste": true
  },

  // ================= Extension Settings =================

  // ESLint
  "eslint.validate": [
    "javascript",
    "typescript",
    "javascriptreact",
    "typescriptreact"
  ],

  // Prettier
  "prettier.singleQuote": true,
  "prettier.semi": true,

  // Path Intellisense
  "path-intellisense.autoSlashAfterDirectory": true,

  // Tailwind CSS (aktifkan jika kamu pakai Tailwind)
  "tailwindCSS.includeLanguages": {
    "html": "html",
    "javascript": "javascript",
    "typescriptreact": "typescript"
  },

  // Emmet
  "emmet.triggerExpansionOnTab": true,

  // Live Server
  "liveServer.settings.donotShowInfoMsg": true,

  // Code Spell Checker
  "cSpell.language": "en, id",
  "cSpell.enabled": false,
  "cSpell.allowCompoundWords": true
}

