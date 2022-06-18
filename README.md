[![alt](/snickerdoodle.png)](https://snickerdoodlelabs.io)

# Snickerdoodle Labs Light VSCode Theme

This repository implements a light theme for the VSCode IDE with [Snickerdoodle Labs](https://snickerdoodlelabs.io) color palette. 

![alt](/demo.png)

## Build

To build the `.vsix` package for installation, use the VSCode publishing tool, `vsce`:

```shell
npm install -g vsce
vsce package
# snickerdoodle-light-0.0.x.vsix generated
```

## Publish a new version to Open VSX

After building the `vsix` package, use `ovsx` to pushlish to the open-vsx registry:

```shell
npx ovsx publish snickerdoodle-light-0.0.x.vsix -p <access token>
```

## For more information
* [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
* [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/)

**Enjoy!**
