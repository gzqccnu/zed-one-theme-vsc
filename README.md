# zed-one-theme for vscode

## Explanation
> [!Note]
> This repository is forked from [zed-one-theme-vs](https://github.com/arrrrny/zed-one-theme-vs). Under MIT license.
> Why I forked from him and developing it? Cause when I using it, I found there's no support for **markdown** format file.

## Feature
- **zed-like:**
A **zed-like** theme for vsc. Now support **light** theme and **dark** theme
- **markdown support:**
Support highlight markdown file.

## Quick start
> build on your own, no release.

- First clone this repo.
```bash
git clone https://github.com/gzqccnu/zed-one-theme-vsc.git
```
- Then build the extension
> [!Important]
> Ensure you have node.
> you can run below to test.
```bash
node --version
```
> If you not have one, install from the [official website](https://nodejs.org/) 

```bash
cd zed-one-theme-vsc
npx @vscode/vsce package
```
- After you run this, in your folder will generate a file ends with **.vsix**.

- In vsc, type `ctrl+shift+p`, then input below:
```markdown
install from vsix
```
- Then you should select the file ends with **.vsix** related above.

- Now you can enjoy the themes.

## Bug or others
You can add issues.
