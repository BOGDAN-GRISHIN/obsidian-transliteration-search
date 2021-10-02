# Obsidian Smart Search Plugin

This is an Obsidian plugin for those who prefer to search files not so much fuzzy. Moreover..

- `Smart Search` can search **regardless of the appearance order of tokens**
- `Smart Search` shows file names and directory names separately
- `Smart Search` shows suggestions order by prioritizing both last opened time and modified time **even after typing**

## ⌨️Features

### Normal Search

Run `Smart Search: Normal search` on `Command palette` or push `Ctrl + Shift + P`.

![Demo](https://raw.githubusercontent.com/tadashi-aikawa/obsidian-smart-search/master/demo/normal.gif)

### Recent Search

Run `Smart Search: Recent search` on `Command palette` or push `Ctrl + Shift + E`.

![Demo](https://raw.githubusercontent.com/tadashi-aikawa/obsidian-smart-search/master/demo/recent.gif)

If the query starts with `/`, it behaves as `Normal Search`.

### Backlink Search

Run `Smart Search: Backlink search` on `Command palette` or push `Ctrl + Shift + H`.

![Demo](https://raw.githubusercontent.com/tadashi-aikawa/obsidian-smart-search/master/demo/backlink.gif)

⚠️This feature is an experimental feature. And it has unsafe implementation, so there are risks it is not working someday :)

## ⏬Install

Download 3 files from a [Releases page].

- `main.js`
- `styles.css`
- `manifest.json`

And copy to directory, `<your-vault>/.obsidian/plugins/obsidian-smart-search/`.

[Releases page]: https://github.com/tadashi-aikawa/obsidian-smart-search/releases/latest

## 🖥️For developers

### Release

```console
task release VERSION=1.2.3
```
