# Katnip Syntax Highlighting

Syntax highlighting and language configuration support for the Katnip programming language (`.knip` files) in Visual Studio Code.

---

## Features

- Syntax highlighting for Katnip keywords, constants, numbers, strings, comments, and operators.
- Support for Katnip’s unique comment styles including single-line (`#`), and block comments (`#> ... <#`).
- Bracket matching and auto-closing pairs for `{}`, `[]`, `()`, `"`, and `'`.
- Folding support for Katnip’s block comments and region markers.

---

## Installation

### From VSCode Marketplace (coming soon)

Search for **Katnip Syntax Highlighting** in the Extensions Marketplace and install.

### Manual Installation

1. Download or build the `.vsix` package.

2. Open VSCode, go to the Extensions sidebar.

3. Click on the `...` menu in the top right corner, choose **Install from VSIX...**

4. Select the `.vsix` file and install.

---

## Usage

- Open any `.knip` file in VSCode.

- The editor will automatically use Katnip syntax highlighting and language features.

- Use `#` for single-line comments.

- Use `#> ... <#` to create block comments.

- Folding and bracket auto-closing will work out of the box.

---

## Development

If you'd like to contribute or modify the extension:

```bash
git clone https://github.com/yourusername/katnip-syntax-highlighting.git
cd katnip-syntax-highlighting
npm install
code .
