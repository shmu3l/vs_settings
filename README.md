# vs_settings
{
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnSave": true,
  "editor.detectIndentation": true,
  "editor.fontSize": 14,
  "editor.tabSize": 4,
  "editor.insertSpaces": true,
  "terminal.integrated.fontSize": 14,
  "terminal.integrated.fontFamily": "'Dank Mono', Menlo, Monaco, 'Courier New', monospace",
  "terminal.integrated.lineHeight": 1,
  "editor.fontFamily": "'Dank Mono', Menlo, Monaco, 'Courier New', monospace",
  "editor.fontLigatures": false,
  "editor.rulers": [80],
  "editor.snippetSuggestions": "top",
  "editor.wordBasedSuggestions": false,
  "editor.suggest.localityBonus": true,
  "editor.acceptSuggestionOnCommitCharacter": false,
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.suggestSelection": "recentlyUsed",
    "editor.suggest.showKeywords": false
  },
  "editor.renderWhitespace": "boundary",
  "files.exclude": {
    "USE_GITIGNORE": true
  },
  "files.defaultLanguage": "{activeEditorLanguage}",
  "javascript.validate.enable": false,
  "search.exclude": {
    "**/node_modules": true,
    "**/bower_components": true,
    "**/coverage": true,
    "**/dist": true,
    "**/build": true,
    "**/.build": true,
    "**/.gh-pages": true
  },
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": false
  },
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    "typescript",
    "typescriptreact"
  ],
  "eslint.options": {
    "env": {
      "browser": true,
      "jest/globals": true,
      "es6": true
    },
    "parserOptions": {
      "ecmaVersion": 2019,
      "sourceType": "module",
      "ecmaFeatures": {
        "jsx": true
      }
    },
    "rules": {
      "no-debugger": "off"
    }
  },
  "workbench.colorTheme": "One Dark Pro",
  "workbench.iconTheme": "material-icon-theme",
  "breadcrumbs.enabled": true,
  "grunt.autoDetect": "off",
  "gulp.autoDetect": "off",
  "npm.runSilent": true,
  "explorer.confirmDragAndDrop": false,
  "editor.formatOnPaste": false,
  "editor.cursorSmoothCaretAnimation": true,
  "editor.smoothScrolling": true,
  "editor.suggestSelection": "first",
  "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
  "window.zoomLevel": 0,
  "typescript.updateImportsOnFileMove.enabled": "always",
  "editor.accessibilitySupport": "on",
  "python.languageServer": "Pylance",
  "workbench.editorAssociations": [
    {
      "viewType": "jupyter-notebook",
      "filenamePattern": "*.ipynb"
    }
  ]
}
