# Visual Studio Code Settings
Install extensions
```
code --install-extension andersonmfjr.vue-extension-pack
code --install-extension andersonmfjr.vue-jumptotag
code --install-extension andersonmfjr.vue-snippets-standardjs
code --install-extension christian-kohler.npm-intellisense
code --install-extension dbaeumer.vscode-eslint
code --install-extension EditorConfig.EditorConfig
code --install-extension esbenp.prettier-vscode
code --install-extension felixfbecker.php-intellisense
code --install-extension felixfbecker.php-pack
code --install-extension killalau.vscode-liquid-snippets
code --install-extension ms-vscode.Go
code --install-extension neilding.language-liquid
code --install-extension octref.vetur
code --install-extension PKief.material-icon-theme
```

and paste the settings to settings.json

```
{
  "editor.fontFamily": "Operator Mono, Menlo, Monaco, 'Courier New', monospace",
  "editor.fontSize": 14,
  "explorer.autoReveal": false,
  "files.exclude": {
    ".idea": true,
    "node_modules": true,
    "vendor": true
  },
  "explorer.openEditors.visible": 0, 
  "editor.fontWeight": "500",
  "editor.formatOnType": true,
  "emmet.includeLanguages": {
    "blade": "html",
    "edge": "html",
    "vue-html": "html",
    "vue": "html"
  },
  "workbench.iconTheme": "material-icon-theme",
  "breadcrumbs.enabled": false,
  "files.autoSave": "onWindowChange"
}
```
