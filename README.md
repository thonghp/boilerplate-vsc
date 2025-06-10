{
  "workbench.iconTheme": "material-icon-theme",
  "editor.fontFamily": "'Cascadia Code', Consolas, 'Courier New', monospace",
  "editor.fontSize": 18,
  "editor.fontLigatures": true,
  "workbench.sideBar.location": "right",
  "javascript.updateImportsOnFileMove.enabled": "always",
  "workbench.colorTheme": "Solarized Light",
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "json.schemas": [],
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "terminal.integrated.env.windows": {},
  "[javascriptreact]": {
    "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.formatOnSave": true,
  "explorer.compactFolders": false,
  "[markdown]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "codeium.enableConfig": {
    "*": true
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "diffEditor.ignoreTrimWhitespace": false,
  "chat.commandCenter.enabled": false,
  "editor.wordWrap": "on",
  // Cấu hình tự động fix ESLint và Prettier khi lưu
  "editor.codeActionsOnSave": {
    "source.fixAll": "explicit",
    "source.fixAll.eslint": "explicit"
  },
  "eslint.validate": [
    "javascript",
    "javascriptreact"
  ],
  // cấu hình màu cho solarized light đối với code js
  "editor.tokenColorCustomizations": {
    "[Solarized Light]": {
      "textMateRules": [
        // === CODE CUSTOM ===
        {
          "name": "Từ khoá như const let var,...",
          "scope": "storage",
          "settings": {
            "foreground": "#a626a4"
          }
        },
        {
          "name": "Từ khoá như function, class",
          "scope": "storage.type.function.js",
          "settings": {
            "foreground": "#a626a4"
          }
        },
        {
          "name": "Tên của hàm",
          "scope": "entity.name.function.js",
          "settings": {
            "foreground": "#b58900"
          }
        },
        {
          "name": "Tên biến hoặc thuộc tính",
          "scope": "variable.other",
          "settings": {
            "foreground": "#073642"
          }
        },
        {
          "name": "Từ khoá như this",
          "scope": "variable.language",
          "settings": {
            "foreground": "#be0027"
          }
        },
        {
          "name": "Tham số trong hàm",
          "scope": "variable.parameter",
          "settings": {
            "foreground": "#6c71c4"
          }
        },
        {
          "name": "Property key trong object như name",
          "scope": "variable.other.property.js",
          "settings": {
            "foreground": "#be0027"
          }
        },
        // === MARKDOWN CUSTOM ===
        {
          "name": "Màu của các heading (#, ##, etc.)",
          "scope": [
            "markup.heading.markdown",
            "markup.heading.setext.1.markdown",
            "markup.heading.setext.2.markdown"
          ],
          "settings": {
            "foreground": "#be0027",
            "fontStyle": "bold"
          }
        },
        {
          "name": "Link ở mục lục hoặc link trích dẫn",
          "scope": [
            "markup.underline.link.markdown",
            "string.other.link.title.markdown"
          ],
          "settings": {
            "foreground": "#00a98f", 
            "fontStyle": "underline"
          }
        },
        {
          "name": "Là các từ nằm trong **_**",
          "scope": [
            "markup.bold.markdown",
            "markup.bold.markdown punctuation.definition.bold"
          ],
          "settings": {
            "foreground": "#371777", 
            "fontStyle": "bold"
          }
        },
        {
          "name": "Màu mặc định của chữ",
          "scope": [
            "markup.list"
          ],
          "settings": {
            "foreground": "#371777",
            "fontStyle": ""
          }
        },
      ]
    }
  },
}
