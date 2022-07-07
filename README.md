# Visual Studio Code Extensions
This is my vs's most used extensions

# My Favorites Extensions

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
