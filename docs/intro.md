---
sidebar_position: 1
---

# Tutorial Intro

This is my rogh work!

### My VS Code settings

```json title='settings.json'
{
  "workbench.iconTheme": "material-icon-theme",
  "editor.detectIndentation": false,
  "editor.tabSize": 2,
  "editor.bracketPairColorization.enabled": true,
  "editor.guides.bracketPairs":"active",
  "editor.fontFamily": "Dank Mono",
  // "editor.fontFamily": "Fira Code",
  // "editor.fontFamily": "Fira Code iScript",
  "editor.fontLigatures":  true,
  "editor.fontSize": 14,
  // "workbench.colorTheme": "Dark++ Italic",
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": [
          //following will be in italic (=FlottFlott)
          "comment",
          "entity.name.type.class", //class names
          "keyword", //import, export, return…
          "storage.modifier", //static keyword
          "storage.type", //class keyword
          "support.class.builtin",
          "keyword.control",
          "constant.language",
          "entity.other.attribute-name",
          "string.quoted.single",
          "entity.name.method",
          "entity.name.tag"
        ],
        "settings": {
          "fontStyle": "italic",
        }
      }
    ]
  },
  
  "diffEditor.ignoreTrimWhitespace": false,
  "git.ignoreWindowsGit27Warning": true,
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[markdown]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[python]": {
    "editor.formatOnType": true
  },
  "[scss]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "terminal.integrated.env.linux": {}
}
```
