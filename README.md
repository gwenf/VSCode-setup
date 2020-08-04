# VSCode-setup

[**Complete List of Synced Settings**](https://gist.github.com/gwenf/a9e3a9859f55b1fed72ca7137a87c8ba)

## Plugins

* html
* npm intellisense
* vue
	* Vetur
* JavaScript
	* ESLint
* golang
* python
	* autopep8
	* django
* Solodity
* Themes
	* Palenight
	* Seti Monokai
	* Bracket Pair Colorizer
* VSCode Liveshare
* Autoformatting
	* Beautify

### Plugins I want to try:

* VSCode-icons
* Gitlens
* Code Spell Check
* Indent Rainbow
* asciidocs and asciidoctor
* AI Autocompleters
	* Kite
	* TabNine

## Settings

* Scroll past end of file
* Debugging
	* Python
	* JavaScript
* Keybindings
	* Vim
* Tab sizes
* Autoformatting
	* Format on save
	
	
	
```json	
{
    "window.zoomLevel": 3,
    "javascript.updateImportsOnFileMove.enabled": "always",
    "latex-workshop.view.pdf.viewer": "tab",
    "editor.suggest.snippetsPreventQuickSuggestions": false,
    "editor.wordBasedSuggestions": false,
    "editor.parameterHints.enabled": false,
    "editor.quickSuggestions": false,
    "python.linting.pycodestylePath": "/Users/gwen/anaconda3/bin/pep8",
    "python.linting.enabled": true,
    "files.exclude": {
        "**/*.js.map": false,
        "**/*.js": false
    },
    "workbench.startupEditor": "newUntitledFile",
    "editor.tabSize": 2,
    "python.terminal.activateEnvironment": false,
    "search.useGlobalIgnoreFiles": true,
    "emmet.showSuggestionsAsSnippets": true,
    "workbench.editor.enablePreview": false,
    "workbench.editor.enablePreviewFromQuickOpen": false,
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "workbench.colorTheme": "Seti Monokai",
    "emmet.excludeLanguages": [
        "markdown"
    ],
    "emmet.includeLanguages": {
        "vue-html": "html",
        "javascript": "javascriptreact",
        "vue": "html"
    },
    "vetur.format.defaultFormatter.js": "prettier-eslint"
}
```
