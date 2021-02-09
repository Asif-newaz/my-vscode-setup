# VSCode setup

### Theme

I use the `Oceanic Next` theme with the dimmed bg option. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=naumovs.theme-oceanicnext)

### Icon theme

I use the `vscode-icons` icon theme. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)

### Extensions used in course videos

For each of the extensions, read the overview page in order to learn how to use it.

`Auto Close Tag` to automatically close HTML tags. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)

`Auto Rename Tag` to automatically change matching HTML tags. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)

`Code Spell Checker` to automatically underlines words that it doesn't recognize in its dictionary files. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)

`Color Highlight` to, as the name says, highlight colors in CSS. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)

`Paste and Indent` to automatically indent pasted code. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=Rubymaniac.vscode-paste-and-indent)

`Path Intellisense` to autocomplete filenames. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)

`Prettier` to automatically format code. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

`Icon Fonts` Snippets for popular icon fonts such as Font Awesome, Ionicons, Glyphicons, Octicons, Material Design Icons and many more! [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=idleberg.icon-fonts)

`Bracket Pair Colorizer` A customizable extension for colorizing matching brackets. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)

`Better Align` Align code without selecting them first. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=wwm.better-align)

`GitLens` GitLens simply helps you better understand code. Quickly glimpse into whom, why, and when a line or code block was changed. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)

`Babel JavaScript` JavaScript syntax highlighting for ES201x, React JSX, Flow and GraphQL. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=mgmcdermott.vscode-language-babel)

`vscode-styled-components` Syntax highlighting for styled-components. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=jpoissonnier.vscode-styled-components)

`JavaScript (ES6) code snippets` This extension contains code snippets for JavaScript in ES6 syntax for Vs Code editor (supports both JavaScript and TypeScript). [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets)

`ESLint` Using this, it is very easy to find out the error of the code. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)

`ES7 React/Redux/GraphQL/React-Native snippets` Simple extensions for React, Redux and Graphql in JS/TS with ES7 syntax. It works just like Emmet. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)

### Other extensions I use (will keep it updated) 

`Project Manager` to easily switch between projects. One of the most useful extensions. [Link &rarr;](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager)

### Settings

If you want your editor to work and look exactly the same way as mine, you can copy these settings to your own settings file. Just go to settings in VSCode, and on the right side, you can paste this code.

```
{
    "workbench.colorTheme": "Oceanic Next (dimmed bg)",
    "files.autoSave": "onFocusChange",
    "editor.minimap.enabled": true,
    "workbench.statusBar.visible": true,
    "workbench.activityBar.visible": true,
    "editor.formatOnSave": false,
  
    "workbench.colorCustomizations": {
      "statusBar.background": "#333333",
      "statusBar.noFolderBackground": "#333333",
      "statusBar.debuggingBackground": "#263238"
    },
    "editor.fontSize": 16,
  
    "css.validate": false,
    "scss.validate": false,
    "less.validate": false,
    "editor.wordWrap": "on",
    "[html]": {
      "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "prettier.tabWidth": 4,
    "workbench.iconTheme": "vscode-icons",
    "cSpell.userWords": [
      "booy"
    ],
    "editor.renderWhitespace": "all",
    "breadcrumbs.enabled": true,
    "files.associations": {
    
    },
    "editor.fontFamily": "Fira Code", 
    "editor.fontLigatures": true,
    "editor.fontWeight": "500",
  }

```
