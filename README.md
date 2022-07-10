# Visual Studio Code Extensions & Scripts
This is my vs's most used extensions

# Extensions Visual Studio Code

* [Bookmarks](https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks)

* [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2)

* [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)

* [Liveserver](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

* [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)

* [Material Theme](https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-material-theme)

* [Paste JSON as Code](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype)

* [TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)

* [TODO Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)

* [Snipped](https://marketplace.visualstudio.com/items?itemName=JeffersonLicet.snipped)

* [Polacode](https://marketplace.visualstudio.com/items?itemName=pnp.polacode)

* [Css Peak](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek)

* [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)

* [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)

* [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)

* [IntelliSense for CSS class names in HTML](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion)

* [JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets)

* [SQl Server Client(mssql)](https://marketplace.visualstudio.com/items?itemName=cweijan.vscode-myssql-client2)

* [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

* [Tailwind CSS IntelliSensePreview](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)

* [Sass](https://marketplace.visualstudio.com/items?itemName=Syler.sass-indented)

* [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)

* [Settings Sync](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync)

* [Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)

* [indent-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)

* [SVG](https://marketplace.visualstudio.com/items?itemName=jock.svg)


# Keybindings.json Shortcut Visual Studio Code
To Open Keybindings menu just use ```Ctrl + K then Ctrl + S```

```

// Place your key bindings in this file to override the defaultsauto[]
[
    {
        "key": "alt+s",
        "command": "editor.emmet.action.wrapWithAbbreviation"
    },
    {
        "key": "ctrl+d",
        "command": "editor.action.copyLinesDownAction",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "shift+alt+down",
        "command": "-editor.action.copyLinesDownAction",
        "when": "editorTextFocus && !editorReadonly"
    },
    {
        "key": "ctrl+shift+u",
        "command": "editor.action.transformToUppercase"
    },
    {
        "key": "ctrl+shift+i",
        "command": "editor.action.transformToLowercase"
    }
]
```


# My Visual Studio Snippets for Javascript
To Open Snippets for Javascript menu just use ```File -> Preferences -> Configure User Snippets```
```
	"Print console": {
		"prefix": "clg",
		"body": [
			"console.log(${1:object});",
			"$2"
		],
		"description": "Log output to console"
	},
	"My Custom Funtion": {
		"prefix": "func",
		"body": [
			"function ${1:SuperHeroe}(${2:parameter})",
			"{",
			"    // code to be executed",
			"}"
		]
	}
```
