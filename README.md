# MdViewer

Preview Markdown files quickly inside VS Code.

![MdViewer banner](mdviewerext-banner.png)

## Features

- Command: `Markdown Viewer: Open File`
- Right-click `.md` in Explorer and open directly from the context menu
- Open selected Markdown in an in-extension preview panel
- Commands: `Markdown Viewer: Zoom In`, `Markdown Viewer: Zoom Out`, `Markdown Viewer: Reset Zoom`
- Zoom shortcut in preview: `Cmd + Mouse Wheel` (macOS), `Ctrl + Mouse Wheel` (Windows/Linux)

## Extension Settings

- `mdviewerext.openToSide`: Open Markdown preview in side editor.
- `mdviewerext.preserveFocus`: Keep focus in current editor after opening preview.

## Scripts

- `npm run compile`: Compile TypeScript
- `npm run watch`: Watch and compile on changes
- `npm run lint`: Run ESLint
- `npm test`: Run extension tests

## Run locally

1. Install dependencies: `npm install`
2. Press `F5` in VS Code to launch Extension Development Host
3. Open using either:
   - Explorer right-click on a `.md` file -> `Markdown Viewer: Open File`
   - Command Palette -> `Markdown Viewer: Open File`

## Publish

1. Install VSCE globally: `npm i -g @vscode/vsce`
2. Login once: `vsce login michaelsam94`
3. Publish: `vsce publish`
