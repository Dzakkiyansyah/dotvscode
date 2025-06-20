# My VS Code Settings Configuration 🚀

## 📋 Introduction

This repository contains my personal VS Code settings configuration that works across:

- Windows

- Linux
- WSL (Windows Subsystem for Linux)

## ⚙️ Configuration

```json
{
  // =================================================================
  // ==                CORE EDITOR & FONT SETTINGS                  ==
  // =================================================================
  "editor.fontFamily": "'Fira Code', 'JetBrains Mono', 'Cascadia Code', monospace",
  "editor.fontSize": 15,
  "editor.fontLigatures": true,
  "editor.lineHeight": 1.6,
  "editor.letterSpacing": 0.2,
  "editor.wordWrap": "on",
  "editor.smoothScrolling": true,
  "editor.stickyScroll.enabled": false,
  "editor.minimap.enabled": true,
  "editor.renderWhitespace": "selection",

  // --- Upgrade Detail Editor ---
  "editor.cursorStyle": "line",
  "editor.cursorWidth": 2,
  "editor.cursorBlinking": "expand",
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.renderLineHighlight": "gutter",
  "editor.guides.bracketPairs": "active",
  "editor.guides.bracketPairsHorizontal": false,
  "editor.guides.highlightActiveIndentation": true,

  // =================================================================
  // ==               UI, THEME & AESTHETICS                        ==
  // =================================================================
  "workbench.colorTheme": "Bearded Theme Arc",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.productIconTheme": "fluent-icons",
  "window.commandCenter": false,
  "window.titleBarStyle": "custom",
  "window.zoomLevel": 0,
  "workbench.startupEditor": "none",
  "workbench.layoutControl.enabled": false,
  "breadcrumbs.enabled": true,

  // =================================================================
  // ==             FILE, EXPLORER & WINDOW BEHAVIOR                ==
  // =================================================================
  "files.autoSave": "onFocusChange",
  "files.trimTrailingWhitespace": true,
  "files.insertFinalNewline": true,
  "explorer.compactFolders": false,
  "explorer.confirmDelete": false,
  "explorer.confirmDragAndDrop": false,

  // =================================================================
  // ==              AUTOMATION & CODE QUALITY                      ==
  // =================================================================
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnSave": true,
  "editor.formatOnPaste": true,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": "explicit",
    "source.organizeImports": "explicit"
  },

  // =================================================================
  // ==                 INTEGRATED TERMINAL                         ==
  // =================================================================
  "terminal.integrated.fontSize": 14,
  "terminal.integrated.fontFamily": "'FiraCode Nerd Font', 'JetBrainsMono Nerd Font', monospace",
  "terminal.integrated.lineHeight": 1.2,
  "terminal.integrated.cursorStyle": "line",
  "terminal.integrated.smoothScrolling": true,
  "terminal.integrated.shellIntegration.enabled": true,

  // =================================================================
  // ==              LANGUAGE-SPECIFIC SETTINGS                     ==
  // =================================================================
  "[javascript]": { "editor.defaultFormatter": "esbenp.prettier-vscode" },
  "[javascriptreact]": { "editor.defaultFormatter": "esbenp.prettier-vscode" },
  "[typescript]": { "editor.defaultFormatter": "esbenp.prettier-vscode" },
  "[typescriptreact]": { "editor.defaultFormatter": "esbenp.prettier-vscode" },
  "[json]": { "editor.defaultFormatter": "esbenp.prettier-vscode" },
  "[markdown]": {
    "editor.formatOnSave": false,
    "editor.wordWrap": "bounded",
    "editor.wordWrapColumn": 80
  },

  // =================================================================
  // ==                 KEY EXTENSION SETTINGS                      ==
  // =================================================================

  // --- Prettier ---
  "prettier.enable": true,
  "prettier.singleQuote": false,
  "prettier.semi": true,
  "prettier.trailingComma": "es5",
  "prettier.arrowParens": "always",

  // --- ESLint ---
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    "typescript",
    "typescriptreact"
  ],

  // --- Tailwind CSS IntelliSense ---
  "tailwindCSS.includeLanguages": { "plaintext": "html" },
  "tailwindCSS.experimental.classRegex": [
    ["cva\\(([^)]*)\\)", "[\"'`]([^\"'`]*).*?[\"'`]"],
    ["cx\\(([^)]*)\\)", "(?:'|\"|`)([^']*)(?:'|\"|`)"]
  ],

  // --- GitLens ---
  "gitlens.currentLine.enabled": false,
  "gitlens.hovers.currentLine.over": "line",
  "gitlens.codeLens.enabled": false,

  // --- Better Comments ---
  "better-comments.tags": [
    {
      "tag": "!",
      "color": "#FF2D00",
      "strikethrough": false,
      "backgroundColor": "transparent"
    },
    {
      "tag": "?",
      "color": "#3498DB",
      "strikethrough": false,
      "backgroundColor": "transparent"
    },
    {
      "tag": "//",
      "color": "#474747",
      "strikethrough": true,
      "backgroundColor": "transparent"
    },
    {
      "tag": "todo",
      "color": "#FF8C00",
      "strikethrough": false,
      "backgroundColor": "transparent"
    },
    {
      "tag": "*",
      "color": "#98C379",
      "strikethrough": false,
      "backgroundColor": "transparent"
    }
  ],

  // --- Other Extensions ---
  "emmet.includeLanguages": { "javascript": "javascriptreact" },
  "emmet.triggerExpansionOnTab": true,
  "path-intellisense.autoSlashAfterDirectory": true,

  // =================================================================
  // ==         UPGRADE: APC CUSTOMIZE UI++ (EFEK KACA)             ==
  // =================================================================
  "apc.electron": {
    "opacity": 0.85,
    "vibrancy": "dark"
  },
  "apc.header": {
    "height": 36
  },
  "apc.listRow": {
    "height": 24
  },
  "apc.stylesheet": {
    ".monaco-workbench .part.sidebar": "background-color: transparent!important;",
    ".monaco-workbench .part.panel": "background-color: transparent!important;",
    ".monaco-workbench .part.editor": "background-color: transparent!important;"
  },

  // Code Spell Checker
  "cSpell.enabled": false,
  "cSpell.allowCompoundWords": true,
  "cSpell.words": ["id", "en", "ID", "EN"]
}

```
