**[Laravel goto view](https://marketplace.visualstudio.com/items?itemName=codingyu.laravel-goto-view)**
![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/codingyu.laravel-goto-view)

# How to use

![How to use](images/use.gif)

# 🚀🚀🚀

# Settings

## regex

Custom regex for matching strings.

## maxLinesCount

Maximum number of scanning rows.

Default: 666

## folders

Search according to the configured path.

```json
"laravel_goto_view.folders": {
    "default" : "/resources/views",
    "theme_xxx": "/resources/views/theme_xxx"
}
```

## extensions

Search views according to the configured extensions.

```json
"laravel_goto_view.extensions": [
    ".blade.php",
    ".inky.php"
]
```

## quickJump

Use `Ctrl` or `Alt` + `click` to jump to the first matched file.

> Mac or Windows, It depends on your configuration

## folderTip

Display the path name of the configuration.
