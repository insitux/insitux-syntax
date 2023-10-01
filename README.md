**insitux-syntax vscode extension**

- for the language [Insitux](https://github.com/phunanon/Insitux)
- [vscode marketplace](https://marketplace.visualstudio.com/items?itemName=insitux.insitux-syntax) from where it can be installed
- opens `*.ix`, `*.isx`, or `*.clj` files
- it is recommended to enable `bracket pair colorization` in vscode settings also

**Notes to self**
- Update version in `package.json`
- Login to https://marketplace.visualstudio.com/manage/publishers/ with Insitux Github
- Follow "Get a Personal Access Token" from https://code.visualstudio.com/api/working-with-extensions/publishing-extension
- Publish with `npm install -g @vscode/vsce` then `vsce package` then `vsce publish`
