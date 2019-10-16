# VSCode extensions for Ruby On Rails developer
Good extensions i have installed in VSCode for ROR development. Please read the document from the extension link to see how to use it.

## Main extensions

* [Ruby](https://marketplace.visualstudio.com/items?itemName=rebornix.Ruby)
* [Rails](https://marketplace.visualstudio.com/items?itemName=bung87.rails)
* [Ruby on Rails](https://marketplace.visualstudio.com/items?itemName=hridoy.rails-snippets)
* [ruby-rubocop](https://marketplace.visualstudio.com/items?itemName=misogi.ruby-rubocop)
* [Rails Go to Spec](https://marketplace.visualstudio.com/items?itemName=sporto.rails-go-to-spec)
* [Rails i18n](https://marketplace.visualstudio.com/items?itemName=shanehofstetter.rails-i18n)
* [Rails Partial](https://marketplace.visualstudio.com/items?itemName=aki77.rails-partial)
* [Rails Routes](https://marketplace.visualstudio.com/items?itemName=aki77.rails-routes)
* [Simple Ruby ERB](https://marketplace.visualstudio.com/items?itemName=vortizhe.simple-ruby-erb)
* [rails-latest-migration](https://marketplace.visualstudio.com/items?itemName=tmikoss.rails-latest-migration)
* [Slim](https://marketplace.visualstudio.com/items?itemName=sianglim.slim)
* [Better Haml](https://marketplace.visualstudio.com/items?itemName=karunamurti.haml)
* [HTML Snippets](https://marketplace.visualstudio.com/items?itemName=abusaidm.html-snippets)
* [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)
* [IntelliSense for CSS, SCSS class names in HTML, Slim and SCSS](https://marketplace.visualstudio.com/items?itemName=gencer.html-slim-scss-css-class-completion)
* [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
* [Babel ES6/ES7](https://marketplace.visualstudio.com/items?itemName=dzannotti.vscode-babel-coloring)
* [advanced-new-file](https://marketplace.visualstudio.com/items?itemName=patbenatar.advanced-new-file)
* [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
* [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)
* [indent-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)
* [Rainbow Brackets](https://marketplace.visualstudio.com/items?itemName=2gua.rainbow-brackets)
* [Auto Add Brackets in String Interpolation](https://marketplace.visualstudio.com/items?itemName=aliariff.auto-add-brackets)
* [Guides](https://marketplace.visualstudio.com/items?itemName=spywhere.guides)

## Theme and icons (Optional)

* [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
* [One Dark Pro](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme)

## Settings

```
  {
    "editor.tabSize": 2,
    "editor.insertSpaces": true,
    "editor.detectIndentation": false,
    "editor.renderIndentGuides": true,
    "extensions.ignoreRecommendations": true,
    "files.trimTrailingWhitespace": true,
    "files.insertFinalNewline": true,
    "files.trimFinalNewlines": true,
    "files.exclude": {
      "**/.git": true,
      "**/.svn": true,
      "**/.DS_Store": true,
      "**/node_modules": true,
      "**/.idea": true,
      "**/.vscode": false,
      "**/tmp": true
    },
    "files.watcherExclude": {
      "**/.git/objects/**": true,
      "**/node_modules/**": true,
      "**/tmp": true
    },
    "guides.enabled": false,
    "html.suggest.html5": true,
    "javascript.implicitProjectConfig.experimentalDecorators": true,
    "javascript.updateImportsOnFileMove.enabled": "always",
    "javascript.validate.enable": false,
    "material-icon-theme.folders.theme": "specific",
    "material-icon-theme.folders.color": "#90a4ae",
    "material-icon-theme.hidesExplorerArrows": false,
    "material-icon-theme.files.associations": {},
    "material-icon-theme.folders.associations": {},
    "material-icon-theme.languages.associations": {},
    "railsI18n.loadAllTranslations": true,
    "search.exclude": {
      "**/node_modules": true,
      "**/bower_components": true,
      "**/.git": true,
      "**/.DS_Store": true,
      "**/tmp": true,
      "**/coverage": true,
      "**/ios": true,
      "**/android": true
    },
    "workbench.startupEditor": "none",
    "workbench.colorTheme": "One Dark Pro",
    "workbench.iconTheme": "material-icon-theme",
  }
```
