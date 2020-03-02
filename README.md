# Github Preview Theme

A default Markdown preview theme for [Inkdrop](https://www.inkdrop.info/).

 * `styles/github-markdown.less` - Styles for light UI theme
 * `styles/github-markdown-dark.less` - Styles for dark UI theme

## Theming code blocks

Highlighting code blocks is built with [CodeMirror](https://codemirror.net/demo/theme.html), and CSS selectors for styling code blocks are compatible with it.
CSS selectors always start with `cm-`.
You can easily import styles from [CodeMirror's theme](https://github.com/codemirror/CodeMirror/tree/master/theme).

## Development

* Ensure that the InkDrop application is in Development Mode
* Run the command `ipm link --dev` in this repository to link theme

> Reference: https://docs.inkdrop.app/manual/creating-a-theme/#creating-a-preview-theme

