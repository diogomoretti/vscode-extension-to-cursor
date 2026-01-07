<img src="docs/logo.png" alt="VS Code Extension Converter" width="120">

# VS Code Extension Converter

A simple web tool to convert and download VS Code extensions for use in [Cursor](https://cursor.com).

## Why?

Cursor is built on top of VS Code, which means it can run most VS Code extensions. However, some extensions available on the VS Code Marketplace are not directly listed in Cursor's extension panel.

This tool bridges that gap by allowing you to:

1. Paste any VS Code Marketplace extension URL
2. Download the `.vsix` package directly
3. Install it in Cursor by simply dragging the file into the extensions panel

No configuration needed. No command line required. Just paste, download, and drop.

## Usage

1. Visit the [web tool](https://diogomoretti.github.io/vscode-extension-to-cursor/)
2. Paste the VS Code Marketplace extension URL (e.g., `https://marketplace.visualstudio.com/items?itemName=publisher.extension`)
3. Optionally specify a version (defaults to `latest`)
4. Click "Convert and Download"
5. Drag the downloaded `.vsix` file into Cursor's extensions panel

## License

This project is licensed under the MIT License - see the [license.md](license.md) file for details.

