# VS Code Settings Documentation

## Security & Workspace

- `security.workspace.trust.untrustedFiles`: "open"
  - Allows opening untrusted files without prompting for security confirmation

## Workbench Settings

- `workbench.startupEditor`: "none"
  - Disables the welcome page when VS Code starts
- `workbench.colorTheme`: "GitHub Dark"
  - Sets the color theme to GitHub Dark
- `workbench.iconTheme`: "material-icon-theme"
  - Uses Material Icon Theme for file and folder icons
- `workbench.editor.limit.enabled`: true
  - Enables limit on number of open editors
- `workbench.editor.limit.value`: 6
  - Sets maximum number of open editors to 6

## Editor Configuration

- `editor.inlineSuggest.enabled`: true
  - Enables inline suggestions (like GitHub Copilot)
- `editor.accessibilitySupport`: "off"
  - Disables screen reader optimizations
- `editor.defaultFormatter`: "esbenp.prettier-vscode"
  - Sets Prettier as the default formatter for all file types
- `editor.formatOnSave`: true
  - Automatically formats files when saving
- `editor.formatOnPaste`: true
  - Automatically formats content when pasting
- `editor.tabSize`: 2
  - Sets tab size to 2 spaces
- `editor.fontFamily`: "CommitMono"
  - Sets editor font to CommitMono

## File Management

- `files.autoSave`: "onFocusChange"
  - Automatically saves files when focus moves away from editor
- `explorer.confirmDelete`: false
  - Disables confirmation dialog when deleting files
- `explorer.confirmDragAndDrop`: false
  - Disables confirmation when dragging and dropping files

## Language-Specific Settings

### HTML

- `[html].editor.defaultFormatter`: "esbenp.prettier-vscode"
  - Sets Prettier as the default formatter for HTML files

### TypeScript

- `typescript.inlayHints.variableTypes.enabled`: true
  - Enables TypeScript variable type hints
- `typescript.inlayHints.parameterNames.enabled`: "all"
  - Shows parameter names for all TypeScript function calls

## GitHub Copilot

- `github.copilot.enable`:
  - Enables Copilot for specific file types:
    - `"*"`: true (all files)
    - `"yaml"`: true
    - `"plaintext"`: true
    - `"markdown"`: true

## Terminal

- `terminal.integrated.fontFamily`: "MesloLGS NF"
  - Sets the terminal font to MesloLGS NF (commonly used with Oh My Zsh)

## Cursor Extension Settings

- `cursor.cpp.disabledLanguages`: ["plaintext"]
  - Disables Cursor features for plaintext files
- `cursor.terminal.usePreviewBox`: true
  - Enables preview box in terminal
- `cursor.cmdk.useThemedDiffBackground`: true
  - Enables themed diff background for CMD+K feature
- `cursor.diffs.useCharacterLevelDiffs`: true
  - Enables character-level diffs

## Code Quality

- `editor.codeActionsOnSave`:
  - `"source.fixAll.eslint"`: "always"
  - Automatically fixes ESLint issues on save
