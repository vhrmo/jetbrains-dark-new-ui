# JetBrains Dark
Extension of `https://github.com/kotikotprojects/jetbrains-dark-new-ui` with added colors for python.

# Development

Open the project in VSCode and edit `themes/JetBrains Dark (New UI)-color-theme.json`

Press `F5` to debug the extension - this will provide you live updates.

Use the scope inspector from the `Command Palette` with the `Developer: Inspect Editor Tokens and Scopes` to identify the scopes for which you want to define color.

## Build the extension

Install Visual Studio Code Extension Manager 
```shell
npm i -g @vscode/vsce
```

Package the extension
```shell
vsce package
```

Load the resulting `vsix` file to VSCode.
