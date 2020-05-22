# Visual Studio Code Settings
Install extensions
```
code --install-extension dbaeumer.vscode-eslint
code --install-extension esbenp.prettier-vscode
code --install-extension felixfbecker.php-intellisense
code --install-extension Gruntfuggly.todo-tree
code --install-extension k--kato.intellij-idea-keybindings
code --install-extension MehediDracula.php-namespace-resolver
code --install-extension monokai.theme-monokai-pro-vscode
code --install-extension octref.vetur
code --install-extension onecentlin.laravel-blade
code --install-extension onecentlin.laravel5-snippets
code --install-extension PKief.material-icon-theme
```

and paste the settings to settings.json

```
{
    "workbench.colorTheme": "Monokai Pro (Filter Octagon)",
    "workbench.iconTheme": "material-icon-theme",
    "editor.fontFamily": "'Operator Mono', Menlo, Monaco, 'Courier New', monospace",
    "editor.tabSize": 2,
    "files.exclude": {
        ".idea": true,
        ".vscode": true,
        "composer.lock": true,
        "node_modules": true,
        "package-lock.json": true,
        "yarn.lock": true
    },
    "explorer.openEditors.visible": 0,
    "editor.fontWeight": "500",
    "editor.fontSize": 14,
    "editor.renderWhitespace": "none",
    "editor.lineHeight": 24,
    "editor.letterSpacing": 0.25,
    "explorer.decorations.colors": false,
    "editor.suggestLineHeight": null,
    "workbench.editor.focusRecentEditorAfterClose": false,
    "explorer.autoReveal": false,
    "todo-tree.tree.showScanModeButton": false,
    "emmet.includeLanguages": {
        "vue": "html"
    },
    "emmet.triggerExpansionOnTab": true,
    "eslint.format.enable": true,
    "eslint.run": "onSave",
    "files.autoSave": "onWindowChange",
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true
    }
}
```
