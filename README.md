# ⚡ My VS Code Setup

## 📝 Why I use VS Code  
I’ve been using Visual Studio Code since 2018 and it has become my go-to code editor. It’s fast, customizable, and works smoothly across all platforms.  
Over the years, I’ve tweaked its settings, themes, extensions, and shortcuts to match my workflow.  
Every time I set up a new environment, it’s a hassle to redo everything, so I decided to keep all my settings here.  
👉 Feel free to use them if they help you!  

---

## ⚙️ VS Code Settings  
```json
{
  // ===== Editor =====
  "editor.fontSize": 18,
  "editor.tabSize": 2,
  "editor.wordWrap": "on",
  "editor.cursorSmoothCaretAnimation": true,
  "editor.cursorBlinking": "expand",
  "editor.formatOnSave": true,
  "editor.formatOnPaste": true,
  "editor.formatOnType": true,
  "editor.linkedEditing": true,
  "editor.bracketPairColorization.enabled": true,
  "editor.guides.bracketPairs": true,
  "editor.guides.bracketPairsHorizontal": true,
  "editor.hover.enabled": false,
  "editor.defaultFormatter": "esbenp.prettier-vscode",

  // ===== Prettier Config =====
  "prettier.proseWrap": "always",
  "prettier.singleQuote": true,
  "prettier.arrowParens": "avoid",

  // ===== ESLint Integration =====
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true,
    "source.organizeImports": true
  },
  "eslint.alwaysShowStatus": true,

  // ===== Language Specific =====
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features"
  },

  // ===== UI Customization =====
  "workbench.iconTheme": "material-icon-theme",
  "workbench.colorTheme": "Andromeda",
  "workbench.editor.enablePreview": false,
  "window.zoomLevel": 1,
  "workbench.colorCustomizations": {
    "editorGroupHeader.tabsBackground": "#2c2c54",
    "activityBar.background": "#2c2c54",
    "sideBar.background": "#141422",
    "minimap.background": "#141422",
    "tab.activeBackground": "#706fd3",
    "tab.inactiveBackground": "#191846",
    "terminal.border": "#2c2c54",
    "terminal.background": "#2c2c54",
    "statusBar.background": "#474787",
    "scrollbarSlider.background": "#474787",
    "scrollbarSlider.hoverBackground": "#706fd3"
  },

  // ===== Terminal =====
  "terminal.integrated.defaultProfile.windows": "Git Bash",
  "terminal.integrated.fontSize": 18,

  // ===== Diff Editor =====
  "diffEditor.wordWrap": "on",

  // ===== Security =====
  "security.workspace.trust.untrustedFiles": "open",

  // ===== Live Server =====
  "liveServer.settings.CustomBrowser": "chrome:PrivateMode",
  "liveServer.settings.donotShowInfoMsg": true,
  "liveServer.settings.donotVerifyTags": true,

  // ===== Live SASS Compiler =====
  "liveSassCompile.settings.formats": [
    {
      "format": "compressed",
      "extensionName": ".min.css",
      "savePath": "/css"
    }
  ],
  "liveSassCompile.settings.generateMap": false,

  // ===== Screencast Mode =====
  "screencastMode.onlyKeyboardShortcuts": true,
  "screencastMode.mouseIndicatorColor": "#f1c40f",
  "screencastMode.verticalOffset": 0,

  // ===== Emmet Support =====
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  }
}
```

Got you! Here's a polished, professional, and GitHub-friendly version of your README content:

---

# 💻 My VS Code Setup

A curated collection of my favorite **VS Code extensions, themes, keyboard shortcuts, fonts, and more** to supercharge productivity and improve workflow.

---

## ⚙️ Extensions I Use

* **Auto Close Tag** – Jun Han
* **Auto Import (ES6, TS, JSX, TSX)** – Sergey Korenuk
* **Auto Rename Tag** – Jun Han
* **Debugger for Chrome**
* **ESLint** – Microsoft
* **Indent Rainbow** – oderwat
* **HTML CSS Support** – ecmel
* **JavaScript (ES6) Code Snippets** – charalampos karypidis
* **Live Server** – Ritwick Dey
* **Live Sass Compiler** – Glenn Marks
* **Material Icon Theme** – Philipp Kief
* **npm Intellisense** – Christian Kohler
* **Path Intellisense** – Christian Kohler
* **Postman** – Postman
* **Prettier – Code Formatter** – Prettier
* **ReactJS Code Snippets** – charalampos karypidis
* **Simple React Snippets** – Burke Holland
* **Snipped** – Jefferson Licet
* **Stylelint** – Stylelint
* **WordPress Snippets** – wpprotools.io
* **VSCode React Refactor** – planbcoding
* **Tailwind CSS IntelliSense** – Tailwind Labs

---

## 🎨 Themes I Use

* Andromeda
* Dracula Official
* Night Owl
* Shades of Purple
* SynthWave '84
* Ayu

---

## ⌨ Keyboard Shortcuts

| Action                     | Windows / Linux       | Mac                    |
| -------------------------- | --------------------- | ---------------------- |
| HTML Boilerplate           | `! + TAB`             | `! + TAB`              |
| Open Palette / Search File | `Ctrl + P`            | `Cmd + P`              |
| Add Cursors to All Matches | `Ctrl + Shift + L`    | `Cmd + Shift + L`      |
| Undo                       | `Ctrl + U`            | `Cmd + U`              |
| Select Current Line        | `Ctrl + L`            | `Cmd + L`              |
| Zen Mode                   | `Ctrl + K Z`          | `Cmd + K Z`            |
| Toggle Sidebar             | `Ctrl + B`            | `Cmd + B`              |
| Search Global Files        | `Ctrl + Shift + F`    | `Cmd + Shift + F`      |
| Search in File             | `Ctrl + F`            | `Cmd + F`              |
| Find and Replace           | `Ctrl + H`            | `Cmd + H`              |
| Delete Previous Word       | `Ctrl + Backspace`    | `Cmd + Backspace`      |
| Move Line Up/Down          | `Alt + ↑/↓`           | `Option + ↑/↓`         |
| Add Multiple Cursors       | `Ctrl + Alt + ↑/↓`    | `Cmd + Option + ↑/↓`   |
| Comment Line               | `Ctrl + /`            | `Cmd + /`              |
| Block Comment              | `Ctrl + K + Ctrl + C` | `Cmd + K + Cmd + C`    |
| Split View                 | `Ctrl + \`            | `Cmd + \`              |
| Switch Between Views       | `Ctrl + 1, 2…`        | `Cmd + 1, 2…`          |
| Duplicate Line             | `Alt + Shift + ↑/↓`   | `Option + Shift + ↑/↓` |
| Navigate to Specific Line  | `Ctrl + G`            | `Cmd + G`              |
| Open Terminal              | \`Ctrl + \`\`         | \`Cmd + \`\`           |
| Show Suggestions           | `Ctrl + Space`        | `Cmd + Space`          |
| Close Tab                  | `Ctrl + W`            | `Cmd + W`              |
| Close All Tabs             | `Ctrl + Shift + W`    | `Cmd + Shift + W`      |

---

## ✒ Fonts I Use

* [Fira Code](https://fonts.google.com/specimen/Fira+Code)
* [Operator Mono](https://www.typography.com/fonts/operator/styles)

---

## 🧑‍💻 Contributors

* [Miraz Hossain](https://github.com/miraz-rio/)

---

## 🥰 Follow Me

* [GitHub](https://github.com/miraz-rio/)
* [Facebook](https://www.facebook.com/miraz.rio/)
* [Twitter/X](https://x.com/mirazrio)
* [Instagram](https://www.instagram.com/miraz.rio/)
* [LinkedIn](https://www.linkedin.com/in/mirazrio/)



