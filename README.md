# Radon VSCode Language Support
The official Language Support made for the Radon language. 
## Features
- Comments
    - Singleline comments: `//`
    - Block comments: `/*` `*/`
- Variables
    - `int`
    - `string`
- Brackets
    - `()`
    - `{}`
    - `[]`
- Keywords
    - `if/while/return/else/for/true/false`

## Building
```bash
vsce package
```

This requires the `vsce` package to be installed. If you don't have it, you can install it with:
```bash
npm install -g vsce
```

This generates a `.vsix` file that you can install in VSCode.