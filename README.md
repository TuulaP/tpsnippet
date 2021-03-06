# tpsnippet README

This is the README for the extension "tpsnippet". 

## Features

Provides simple 'snippet' or template for a usecase for the Visual Studio Code editor.

For example if there is an image subfolder under your extension project workspace:

\!\[feature X\]\(images/feature-x.png\)

> Tip: Many popular extensions utilize animations. This is an excellent way to show off your extension! We recommend short, focused animations that are easy to follow.

## Requirements

* Visual Studio Code 
* http://pandoc.org/installing.html  for html generation
* pandoc inputfile.md -o output.docx 


## Known Issues

Probably some... 

## Utilization

After folder has been downloaded, it can be put to `%USERPROFILE%\.vscode\extensions\`  , then the plugin is
available at all times.

See `keybindings.json` for customizing a key for the snippet use. After applying that, `Ctrl+u`
will insert snippet to the cursor location.

### HTML generation

`pandoc.exe  -s -o output.html input.md 

## Release Notes


### 0.0

Empty version based on generated basics

### 0.0.1

Fine-tuned use case text a bit.
 
### 0.0.2

Keybinding for snippet & updating this

### 0.0.3

Some adjustments for HTML generation. Starting to think gradle for deploying changes
automagically to VSCode config path.

-----------------------------------------------------------------------------------------------------------

## Working with Markdown

**Note:** You can author your README using Visual Studio Code.  Here are some useful editor keyboard shortcuts:

* Split the editor (`Cmd+\` on OSX or `Ctrl+\` on Windows and Linux)
* Toggle preview (`Shift+CMD+V` on OSX or `Shift+Ctrl+V` on Windows and Linux)
* Press `Ctrl+Space` (Windows, Linux) or `Cmd+Space` (OSX) to see a list of Markdown snippets

### For more information

* [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
* [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/)

**Enjoy!**
