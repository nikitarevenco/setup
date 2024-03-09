# vscode
```
F1: Rename File
F2: New File

CTRL + Q: Go to symbol
CTRL + SHIFT + F: Find in all files
CTRL + D: Delete lines
CTRL + R: Go to references
CTRL + T: Quick Fix
CTRL + L: Go to line
CTRL + 2: Add selection to next find match
CTRL + SHIFT + 2: Add all selections to next find match
CTRL + B: Open and focus breadcrumbs
CTRL + S: Show call hierarchy
CTRL + £: Open command palette

CAPS + V: Toggle view
CAPS + T: Toggle terminal
CAPS + S: Save file
CAPS + Up: Move line up
CAPS + Down: Move line down

ALT + Right: Expand selection
ALT + Left: Shrink selection
```



# extensions
transparent shell
just perfection
tiling assistant
dash to dock
blur my shell
applications menu

# user settings

{
  "security.workspace.trust.untrustedFiles": "open",
  "files.autoSave": "onFocusChange",
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.autoClosingBrackets": "always",
  "editor.formatOnSave": true,
  "editor.wordWrap": "on",
  "editor.tabSize": 2,
  "editor.fontSize": 22,
  "hediet.vscode-drawio.resizeImages": null,
  "cSpell.userWords": [
    "avgtemp",
    "Btns",
    "divs",
    "forecastday",
    "todos",
    "Xdifference"
  ],
  "workbench.iconTheme": "material-icon-theme",
  "terminal.integrated.env.linux": {},
  "liveServer.settings.donotShowInfoMsg": true,
  "editor.inlayHints.enabled": "off",
  "workbench.colorCustomizations": {
    "editor.lineHighlightBackground": "#1073cf2d",
    "editor.lineHighlightBorder": "#9fced11f",
    "editorError.foreground": "#ff555500",
    "editorWarning.foreground": "#fbff0000",
    "editorInfo.foreground": "#0022ff00"
  },
  "diffEditor.wordWrap": "off",
  "editor.guides.indentation": false,
  "editor.guides.bracketPairs": true,
  "glassit.alpha": 255,
  "git.enableSmartCommit": true,
  "editor.minimap.enabled": false,
  "git.confirmSync": false,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "workbench.colorTheme": "GitHub Dark Default",
  "editor.fontLigatures": true,
  "disableLigatures.mode": "Line",
  "workbench.productIconTheme": "material-product-icons",
  "todohighlight.keywords": [],
  "todohighlight.defaultStyle": {
    "color": "FF0000"
  },
  "codesnap-plus.containerPadding": "0em",
  "codesnap-plus.roundedCorners": false,
  "codesnap-plus.showWindowControls": false,
  "errorLens.scrollbarHackEnabled": true,
  "cSpell.diagnosticLevel": "Hint",
  "window.menuBarVisibility": "hidden",
  "emmet.preferences": {},
  "terminal.integrated.lineHeight": 1.2,
  "terminal.integrated.fontFamily": "monospace",
  "terminal.integrated.fontWeight": "normal",
  "terminal.integrated.rightClickBehavior": "selectWord",
  "terminal.integrated.tabs.title": "${process}${task}",
  "terminal.integrated.tabs.enabled": false,
  "editor.dragAndDrop": false,
  "window.zoomLevel": 2,
  "console-ninja.showWhatsNew": false,
  "console-ninja.featureSet": "Community",
  "console-ninja.dateTimeFormat": "",
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": "explicit"
  },
  "[javascript]": {
    "editor.defaultFormatter": "dbaeumer.vscode-eslint",
    "editor.formatOnSave": true
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "dbaeumer.vscode-eslint",
    "editor.formatOnSave": true
  },
  "eslint.alwaysShowStatus": true,
  "errorLens.exclude": [
    "⏎|·",
    "Empty components are self-closing",
    "Replace"
  ],
  "errorLens.messageBackgroundMode": "message",
  "errorLens.problemRangeDecorationEnabled": true,
  "errorLens.editorHoverPartsEnabled": {
    "messageEnabled": true
  },
  "errorLens.gutterIconSet": "squareRounded"
}


# extensions

Auto Close Tag
Auto Import ES6 TS JSX TSX
Auto Rename Tag
Better Comments
Code Spell Checker
Color Highlight
CSS Peek
Error Lens
ESLint
Github Theme
Highlight Matching Tag
Image Preview
Intellisnese for CSS Class names in HTML
JavaScript code snippets
JavaScript booster
Live server
Markdownlint
Material icon theme
Material product icons
Multiple cursor case preserve
path intellisense
Prettier
Prettier ESLint
Surround
Vscode pdf

<details>
<summary><h2>VSCode Shortcuts</h2></summary>

#### ALT

| Shortcut | Effect | Name | 
| -------- | ------ | ------ |
|   <kbd>ALT</kbd> + <kbd>1-9</kbd>       |          Go to editor number.     | `workbench.action.openEditorAtIndex`     |
|   <kbd>ALT</kbd> + <kbd>←</kbd>       |          Shrink selection. (JS BOOSTER)     | `unknown`     |
|   <kbd>ALT</kbd> + <kbd>→</kbd>       |          Expand selection. (JS BOOSTER)    | `unknown`     |
|   <kbd>ALT</kbd>       |          Toggles the small top bar with content like `File`, `Edit`, `Selection`, etc.     | `View: Toggle Menu Bar`     |
|   <kbd>ALT</kbd> + <kbd>↑</kbd>       |          Moves the current line to the line above.     | `editor.action.moveLinesUpAction`     |
|   <kbd>ALT</kbd> + <kbd>↓</kbd>       |          Moves the current line to the line below.     | `editor.action.moveLinesDownAction`     |

#### CTRL

| Shortcut | Effect | Name | 
| -------- | ------ | ------ |
|   <kbd>CTRL</kbd> + <kbd>\</kbd>       |          Splits the current editor into two editors.     | `workbench.action.splitEditor`     |
|   <kbd>CTRL</kbd> + <kbd>4</kbd>       |          Show all references.     | `workbench.view.extension.references-view`     |
|   <kbd>CTRL</kbd> + <kbd>3</kbd>       |          Join lines.     | `editor.action.joinLines`     |
|   <kbd>CTRL</kbd> + <kbd>'</kbd>       |          Focus to the previous editor group.     | `workbench.action.previousEditorGroup`     |
|   <kbd>CTRL</kbd> + <kbd>↑</kbd>       |          Scroll up by a page.     | `editorScroll`     |
|   <kbd>CTRL</kbd> + <kbd>↓'</kbd>       |          Scroll down by a page.     | `editorScroll`     |
|   <kbd>CTRL</kbd> + <kbd>CAPS</kbd>       |          Swap two letters.     | `Unknown`     |
|   <kbd>CTRL</kbd> + <kbd>#</kbd>       |          Focus to the next editor group.     | `workbench.action.nextEditorGroup`     |
|   <kbd>CTRL</kbd> + <kbd>,</kbd>       |          Close all editors but active editor in the active group.     | `workbench.action.closeEditorsInOtherGroups`     |
|   <kbd>CTRL</kbd> + <kbd>D</kbd>       |          Deletes the current lines or the selected lines.     | `editor.action.deleteLines`     |
|   <kbd>CTRL</kbd> + <kbd>S</kbd>       |          Selects the current line or adds the next line to the selection.     | `expandLineSelection`     |
|   <kbd>CTRL</kbd> + <kbd>0</kbd>       |          Toggles comment on selection.     | `editor.action.commentLine`     |
|   <kbd>CTRL</kbd> + <kbd>[</kbd>       |          Folds the current code.     | `editor.fold`     |
|   <kbd>F3</kbd>       |          Go to a specific line.     | `workbench.action.gotoLine`     |
|   <kbd>CTRL</kbd> + <kbd>Q</kbd>       |          Go to symbol in current file.     | `workbench.action.gotoSymbol`     |
|   <kbd>CTRL</kbd> + <kbd>1</kbd>       |          Go to symbol in current project.     | `workbench.action.showAllSymbols`     |
|   <kbd>CTRL</kbd> + <kbd>E</kbd>       |          Go to a certain file.     | `workbench.action.showAllSymbols`     |
|   <kbd>CTRL</kbd> + <kbd>T</kbd>       |          Quick fix.     | `editor.action.quickFix`     |
|   <kbd>CTRL</kbd> + <kbd>R</kbd>       |          Refactor.     | `editor.action.refactor`     |
|   <kbd>CTRL</kbd> + <kbd>G</kbd>       |          Search in every file in current project.    | `workbench.action.findInFiles`     |
|   <kbd>CTRL</kbd> + <kbd>]</kbd>       |          Unfolds the current code.     | `editor.unfold`     |
|   <kbd>CTRL</kbd> + <kbd>TAB</kbd>       |          Switches to the next editor.     | `workbench.action.nextEditor`     |
|   <kbd>CTRL</kbd> + <kbd>SHIFT</kbd> + <kbd>TAB</kbd>       |          Switches to the previous editor.     | `workbench.action.previousEditor`     |
|   <kbd>CTRL</kbd> + <kbd>ENTER</kbd>      |          Insert line below.     | `editor.action.insertLineAfter`     |
|   <kbd>CTRL</kbd> + <kbd>SHIFT</kbd> + <kbd>ENTER</kbd>       |          Insert line above.     | `editor.action.insertLineBefore`     |
|   <kbd>CTRL</kbd> + <kbd>W</kbd>       |          Close current editor.     | `workbench.action.closeActiveEditor`     |
|   <kbd>CTRL</kbd> + <kbd>2</kbd>       |          Add selection to next find match.     | `editor.action.addSelectionToNextFindMatch`     |

#### TERMINAL

| Shortcut | Effect | Name | 
| -------- | ------ | ------ |
|   <kbd>CTRL</kbd> + <kbd>V</kbd> + <kbd>V</kbd>       |          Paste into terminal.     | `terminal.paste`     |
|   <kbd>CTRL</kbd> + <kbd>C</kbd> + <kbd>C</kbd>       |          Copy from terminal.     | `terminal.copy`     |
|   <kbd>CAPS</kbd> + <kbd>T</kbd>       |          Toggles the terminal.     | `workbench.action.terminal.toggleTerminal`     |
|   <kbd>CAPS</kbd> + <kbd>C</kbd>       |          Clears the terminal.     | `workbench.action.terminal.clear`     |
|   <kbd>CTRL</kbd> + <kbd>←</kbd>       |          Move to left word.     | `workbench.action.terminal.moveToWordStart`     |
|   <kbd>CTRL</kbd> + <kbd>→</kbd>       |          Move to right word.     | `workbench.action.terminal.moveToWordEnd`     |
|   <kbd>CTRL</kbd> + <kbd>P</kbd>        |          Change color of terminal.     | `Unknown`     |
|   <kbd>CTRL</kbd> + <kbd>.</kbd>        |          Focus previous terminal.     | `workbench.action.terminal.focusPreviousPane`     |
|   <kbd>CTRL</kbd> + <kbd>/</kbd>        |          Focus next terminal.     | `workbench.action.terminal.focusNextPane`     |
|   <kbd>CTRL</kbd> + <kbd>B</kbd>        |          Rename terminal.     | `workbench.action.terminal.rename`     |
|   <kbd>CTRL</kbd> + <kbd>;</kbd>        |          Kill all terminal instances.     | `workbench.action.terminal.killAll`     |
|   <kbd>CTRL</kbd> + <kbd>Y</kbd>        |          Kill terminal instance.     | `workbench.action.terminal.kill`     |
|   <kbd>CTRL</kbd> + <kbd>H</kbd>        |          New terminal instance.     | `workbench.action.terminal.new`     |

#### CAPS

| Shortcut | Effect | Name | 
| -------- | ------ | ------ |
|   <kbd>CAPS</kbd> + <kbd>J</kbd>       |          Accept commit message.     | `git.commitMessageAccept`     |
|   <kbd>CAPS</kbd> + <kbd>A</kbd>       |          Open source control.     | `workbench.view.scm`     |
|   <kbd>CAPS</kbd> + <kbd>Z</kbd>       |          Removes HTML tag.     | `editor.emmet.action.removeTag`     |
|   <kbd>CAPS</kbd> + <kbd>Q</kbd>       |          Wraps selected content inside of a HTML tag.     | `editor.emmet.action.wrapWithAbbreviation`     |
|   <kbd>CAPS</kbd> + <kbd>S</kbd>       |          Saves the current file.     | `workbench.action.files.save`     |
|   <kbd>CAPS</kbd> + <kbd>E</kbd>       |          Opens and focuses on the file explorer window.     | `workbench.explorer.fileView.focus`     |
|   <kbd>CAPS</kbd> + <kbd>B</kbd>       |          Toggles the sidebar.     | `workbench.action.toggleSidebarVisibility`     |
|   <kbd>CAPS</kbd> + <kbd>↑</kbd>       |          Copies the current line to the line above.     | `editor.action.copyLinesUpAction`     |
|   <kbd>CAPS</kbd> + <kbd>↓</kbd>       |          Copies the current line to the line below.     | `editor.action.copyLinesDownAction`     |
|   <kbd>CAPS</kbd> + <kbd>G</kbd>       |          Toggles zen mode.     | `workbench.action.toggleZenMode`     |
|   <kbd>CAPS</kbd> + <kbd>P</kbd>       |          Opens quick command palette.     | `workbench.action.showCommands`     |
|   <kbd>CAPS</kbd> + <kbd>V</kbd>       |          Show markdown preview.     | `markdown.showPreview`     |
|   <kbd>CAPS</kbd> + <kbd>H</kbd>       |          Open VSC settings.     | `workbench.action.openSettings`     |

#### BASIC

| Shortcut | Effect | Name | 
| -------- | ------ | ------ |
|   <kbd>CTRL</kbd> + <kbd>+</kbd>       |          Zoom in.     | `workbench.action.zoomIn`     |
|   <kbd>CTRL</kbd> + <kbd>-</kbd>       |          Zoom out.     | `workbench.action.zoomOut`     |
|   <kbd>CTRL</kbd> + <kbd>A</kbd>       |          Select everything in the current file.     | `editor.action.selectAll`     |
|   <kbd>CTRL</kbd> + <kbd>F</kbd>       |          Find in current file.     | `actions.find`     |
|   <kbd>CTRL</kbd> + <kbd>C</kbd>       |          Copies the selected content.     | `editor.action.clipboardCopyAction`     |
|   <kbd>CTRL</kbd> + <kbd>V</kbd>       |          Pastes content from the clipboard.     | `editor.action.clipboardPasteAction`     |
|   <kbd>CTRL</kbd> + <kbd>X</kbd>       |          Cuts the selected content by copying and deleting it.     | `editor.action.clipboardCutAction`     |
|   <kbd>CTRL</kbd> + <kbd>SHIFT</kbd> + <kbd>Z</kbd>      |          Redo.     | `redo`     |
|   <kbd>CTRL</kbd> + <kbd>Z</kbd>       |          Undo.     | `undo`     |
|   <kbd>CTRL</kbd> + <kbd>SHIFT</kbd> + <kbd>BACKSPACE</kbd>        |          Deletes word to the right.     | `deleteWordRight`     |
|   <kbd>SHIFT</kbd> + <kbd>BACKSPACE</kbd>       |          Deletes character to the right.     | `deleteRight`     |

</details>

<details>
<summary><h2>Git Alias</h2></summary>

To use all of these aliases, you may wish to copy them one-by-one. However, you can do all of them at once using this command:
```bash
git config --global alias.s 'status -sb'; 
git config --global alias.co 'checkout'; 
git config --global alias.br 'branch --format="%(HEAD) %(color:yellow)%(refname:short)%(color:reset) - %(contents:subject) %(color:green)(%(committerdate:relative)) [%(authorname)]" --sort=-committerdate'; 
git config --global alias.u 'reset HEAD~1 --mixed'; 
git config --global alias.done '!git push origin HEAD'; 
git config --global alias.lg '!git log --pretty=format:"%C(magenta)%h%Creset -%C(red)%d%Creset %s %C(dim green)(%cr) [%an]" --abbrev-commit -30'; 
git config --global alias.tr 'log --oneline --graph --decorate --all'; 
git config --global alias.cp 'cherry-pick'; 
git config --global alias.gl 'config --global -l'; 
git config --global alias.se '!git rev-list --all | xargs git grep -F'; 
git config --global alias.cc 'commit -m'; 
git config --global alias.c 'commit';
```
 git config --global alias.c ‘commit’ ; git config --global alias.cc ‘commit -m’
Git: Check status using `git s`.
```bash
git config --global alias.s ‘status -sb’
```
Git: Checkout using `git co`.
```bash
git config --global alias.co ‘checkout’
```
Git: List all branches in a nice format using `git br`.
```bash
git config --global alias.br ‘branch --format='%(HEAD) %(color:yellow)%(refname:short)%(color:reset) - %(contents:subject) %(color:green)(%(committerdate:relative)) [%(authorname)]' --sort=-committerdate’
```
Git: Reset to before committing the last commit using `git u`.
```bash
git config --global alias.u ‘reset HEAD~1 --mixed’
```
Git: Commit using `git c`.
```bash
git config --global alias.c ‘git commit’
```
Git: Commit with a message using `git cc`.
```bash
git config --global alias.cc ‘git commit -m’
```
Git: Push changes to the current branch using `git d`.
```bash
git config --global alias.done ‘!git push origin HEAD’
```
Git: Log the commits in a nice format using `git lg`.
```bash
git config --global alias.lg ‘!git log --pretty=format:\"%C(magenta)%h%Creset -%C(red)%d%Creset %s %C(dim green)(%cr) [%an]\" --abbrev-commit -30’
```
Git: Search specific commit by string using `git se`.
```bash
git config --global alias.se '!git rev-list --all | xargs git grep -F'
```
Git: List user defined config using `git gl`.
```bash
git config --global alias.gl 'config --global -l'
```
Git: Cherry pick using `git cp`
```bash
git config --global alias.cp 'cherry-pick'
```
Git: Visually display every branch on the project using `git tr`.
```bash
git config --global alias.tr 'log --oneline --graph --decorate --all'
```

Possibly adding more from [here](https://gist.github.com/0livare/4960a81addfbcdc48abfe855fae0af43).
  
</details>

```
"editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
},
"eslint.validate": [
    "javascript",
    "javascriptreact",
    "typescript",
    "typescriptreact"
],
"editor.formatOnSave": true,
"prettier.requireConfig": true,

```
