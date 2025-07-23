# 🚀 My Visual Studio Code Setup

A curated collection of extensions and settings that optimize my development workflow and boost productivity.

## 📦 Extensions

### 🎨 **Theme & UI**
| Extension | Description | Link |
|-----------|-------------|------|
| **GitHub Theme** | Official GitHub themes for VS Code | [Install](https://marketplace.visualstudio.com/items?itemName=GitHub.github-vscode-theme) |
| **Palenight Theme** | Elegant dark theme | [Install](https://marketplace.visualstudio.com/items?itemName=whizkydee.material-palenight-theme) |
| **Material Icon Theme** | Modern icons for better file recognition | [Install](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) |

### 💻 **Development Tools**
| Extension | Description | Link |
|-----------|-------------|------|
| **Prettier** | Automatic code formatting | [Install](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) |
| **Error Lens** | Inline display of errors and warnings | [Install](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens) |
| **Code Runner** | Execute code directly in VS Code | [Install](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner) |
| **Auto Rename Tag** | Automatically rename HTML/XML tags | [Install](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag) |

### 🌐 **Web Development**
| Extension | Description | Link |
|-----------|-------------|------|
| **Live Server** | Local development server with live reload | [Install](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) |
| **Angular Language Service** | IntelliSense for Angular templates | [Install](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template) |
| **Angular Schematics** | Ultimate Angular code generation in Visual Studio Code | [Install](https://marketplace.visualstudio.com/items?itemName=cyrilletuzi.angular-schematics) |
| **JavaScript (ES6) Snippets** | ES6 code snippets | [Install](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets) |
| **es6string-html** | Syntax highlighting for HTML in ES6 template strings | [Install](https://marketplace.visualstudio.com/items?itemName=Tobermory.es6-string-html) |

### 🔧 **Git & Version Control**
| Extension | Description | Link |
|-----------|-------------|------|
| **GitLens** | Enhanced Git integration and visualization | [Install](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) |

### 📊 **Productivity & Organization**
| Extension | Description | Link |
|-----------|-------------|------|
| **Todo Tree** | Find and organize TODO comments in code | [Install](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree) |
| **Rainbow CSV** | Colorful highlighting of CSV columns | [Install](https://marketplace.visualstudio.com/items?itemName=mechatroner.rainbow-csv) |
| **Restore Terminals** | Automatically restore terminal sessions | [Install](https://marketplace.visualstudio.com/items?itemName=EthanSK.restore-terminals) |

### 📄 **File Handling**
| Extension | Description | Link |
|-----------|-------------|------|
| **Draw.io Integration** | Create diagrams directly in VS Code | [Install](https://marketplace.visualstudio.com/items?itemName=hediet.vscode-drawio) |
| **vscode-pdf** | View PDF files in VS Code | [Install](https://marketplace.visualstudio.com/items?itemName=tomoki1207.pdf) |

## ⚙️ **Custom Settings**

### 🎯 **Editor Behavior**
```json
{
  "editor.wordWrap": "on",
  "editor.cursorBlinking": "expand",
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.bracketPairColorization.enabled": true
}
```

### 📁 **File Handling**
```json
{
  "explorer.copyRelativePathSeparator": "/"
}
```

---

## 🚀 **Quick Setup**

### Installation per Command Line:
```bash
# Theme & UI
code --install-extension GitHub.github-vscode-theme
code --install-extension whizkydee.material-palenight-theme
code --install-extension PKief.material-icon-theme

# Development Tools
code --install-extension esbenp.prettier-vscode
code --install-extension usernamehw.errorlens
code --install-extension formulahendry.code-runner
code --install-extension formulahendry.auto-rename-tag

# Web Development
code --install-extension ritwickdey.LiveServer
code --install-extension Angular.ng-template
code --install-extension xabikos.JavaScriptSnippets
code --install-extension Tobermory.es6-string-html

# Git & Productivity
code --install-extension eamodio.gitlens
code --install-extension Gruntfuggly.todo-tree
code --install-extension mechatroner.rainbow-csv
code --install-extension EthanSK.restore-terminals

# File Handling
code --install-extension hediet.vscode-drawio
code --install-extension tomoki1207.pdf
```

### Add settings:
1. `Ctrl+Shift+P` → "Preferences: Open Settings (JSON)"
2. Add the above settings to your `settings.json` file

---

*💡 **Tip:** These extensions and settings are regularly updated. Check for updates occasionally to benefit from new features!*
