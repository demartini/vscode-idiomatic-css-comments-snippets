<h1 align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=demartini.vscode-idiomatic-css-comments-snippets">
    <img width="256" src="./images/icon.png" alt="Logo">
  </a>
  <div>VS Code - Idiomatic CSS Comments</div>

  [![Visual Studio Marketplace Version][version-badge]][marketplace-link] [![Visual Studio Marketplace Installs][installs-badge]][marketplace-link] [![Visual Studio Marketplace Rating][rating-badge]][marketplace-link] [![license MIT][license-badge]][license-link]
</h1>

## Table of Contents <!-- omit in toc -->

- [Features](#features)
- [Installation](#installation)
- [Supported Languages](#supported-languages)
- [Usage](#usage)
- [Snippets](#snippets)
- [Examples](#examples)
  - [Basic Comment](#basic-comment)
  - [Section Comment](#section-comment)
  - [Sub-Section Comment](#sub-section-comment)
  - [Long Comment](#long-comment)
- [Contributing](#contributing)
- [Changelog](#changelog)
- [License](#license)

## Features

This extension adds snippets for Nicolas Gallagher's [Idiomatic CSS][idiomatic-css-link] comments principles in VS Code.

## Installation

1. Launch VS Code.
2. Press <kbd>Ctrl</kbd> + <kbd>P</kbd> or <kbd>Control</kbd> + <kbd>P</kbd> (for macOS).
3. Paste command `ext install demartini.vscode-idiomatic-css-comments-snippets` and press <kbd>Enter</kbd>.
4. Reload VS Code.

## Supported Languages

- CSS `(.css)`
- HTML `(.html)`
- Less `(.less)`
- PostCSS `(.postcss)`
- SCSS `(.scss)`

## Usage

In Visual Studio Code, snippets appear in IntelliSense (<kbd>Ctrl</kbd> + <kbd>Space</kbd> or <kbd>Control</kbd> + <kbd>Space</kbd> (for macOS)) mixed with other suggestions, as well as in a dedicated snippet picker (**Insert Snippet** in the Command Palette). There is also support for tab-completion: Enable it with `"editor.tabCompletion": "on"`, type a **snippet prefix** (trigger text), and press <kbd>Tab</kbd> to insert a snippet.

## Snippets

Below is a list of all available snippets and the triggers for each one.

| Trigger                         | Content                  |
| ------------------------------- | ------------------------ |
| `com-css-basic` <kbd>⇥</kbd>    | CSS Basic Comment        |
| `com-css-section` <kbd>⇥</kbd>  | CSS Section Comment      |
| `com-css-sub` <kbd>⇥</kbd>      | CSS Sub-Section Comment  |
| `com-css-long` <kbd>⇥</kbd>     | CSS Long Comment         |
| `com-scss-basic` <kbd>⇥</kbd>   | SCSS Basic Comment       |
| `com-scss-section` <kbd>⇥</kbd> | SCSS Section Comment     |
| `com-scss-sub` <kbd>⇥</kbd>     | SCSS Sub-Section Comment |
| `com-scss-long` <kbd>⇥</kbd>    | SCSS Long Comment        |

<sub><sup>The <kbd>⇥</kbd> means the <kbd>Tab</kbd> key.</sup></sub>

## Examples

### Basic Comment

- CSS

```css
/* Basic Comment */
```

- SCSS

```scss
// Basic Comment
```

### Section Comment

- CSS

```css
/* ==========================================================================
  Section Comment Block
  ========================================================================== */
```

- SCSS

```scss
// ==========================================================================
// Section Comment Block
// ==========================================================================
```

### Sub-Section Comment

- CSS

```css
/* Sub-section Comment Block
  ========================================================================== */
```

- SCSS

```scss
//
// Sub-section Comment Block
//==========================================================================
```

### Long Comment

- CSS

```css
/**
 * Short description using Doxygen-style comment format
 *
 * The first sentence of the long description starts here and continues on this
 * line for a while finally concluding here at the end of this paragraph.
 *
 * The long description is ideal for more detailed explanations and
 * documentation. It can include example HTML, URLs, or any other information
 * that is deemed necessary or useful.
 *
 * @tag This is a tag named 'tag'
 *
 * TODO: This is a todo statement that describes an atomic task to be completed
 *   at a later date. It wraps after 80 characters and following lines are
 *   indented by 2 spaces.
 */
```

- SCSS

```scss
//
// Short description using Doxygen-style comment format
//
// The first sentence of the long description starts here and continues on this
// line for a while finally concluding here at the end of this paragraph.
//
// The long description is ideal for more detailed explanations and
// documentation. It can include example HTML, URLs, or any other information
// that is deemed necessary or useful.
//
// @tag This is a tag named 'tag'
//
// TODO: This is a todo statement that describes an atomic task to be completed
//   at a later date. It wraps after 80 characters and following lines are
//   indented by 2 spaces.
//
```

## Contributing

If you are interested in helping contribute, please take a look at our [contribution guidelines][contributing-link] and open an [issue][issue-link] or [pull request][pull-request-link].

## Changelog

See [CHANGELOG][changelog-link] for a human-readable history of changes.

## License

Distributed under the MIT License. See [LICENSE][license-link] for more information.

[changelog-link]: ./CHANGELOG.md
[contributing-link]: https://github.com/demartini/.github/blob/main/CONTRIBUTING.md
[idiomatic-css-link]: https://github.com/necolas/idiomatic-css#3-comments
[installs-badge]: https://img.shields.io/visual-studio-marketplace/i/demartini.vscode-idiomatic-css-comments-snippets?style=flat-square&labelColor=292a44&color=663399
[issue-link]: https://github.com/demartini/vscode-idiomatic-css-comments-snippets/issues
[license-badge]: https://img.shields.io/github/license/demartini/vscode-idiomatic-css-comments-snippets?style=flat-square&labelColor=292a44&color=663399
[license-link]: ./LICENSE
[marketplace-link]: https://marketplace.visualstudio.com/items?itemName=demartini.vscode-idiomatic-css-comments-snippets
[pull-request-link]: https://github.com/demartini/vscode-idiomatic-css-comments-snippets/pulls
[rating-badge]: https://img.shields.io/visual-studio-marketplace/r/demartini.vscode-idiomatic-css-comments-snippets?style=flat-square&labelColor=292a44&color=663399
[version-badge]: https://img.shields.io/visual-studio-marketplace/v/demartini.vscode-idiomatic-css-comments-snippets?style=flat-square&labelColor=292a44&color=663399
