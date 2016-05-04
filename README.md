#SublimeText相关

##下载 Sublime Text 3

[Sublime Text 3](http://www.sublimetext.com/3)

##Sublime Text Package

[Package Control](https://packagecontrol.io)

###安装 Package

输入 `ctrl+`\` 或者打开 `View > Show Console menu`. 在打开的console输入框粘贴如下代码。

Sublime Text 3:

```
import urllib.request,os,hashlib; h = '2915d1851351e5ee549c20394736b442' + '8bc59f460fa1548d1514676163dafc88'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)
```

这段代码可能会变化，如果无效，请访问[这个页面](https://packagecontrol.io/installation)。

###常用 Package

- [Emmet](https://packagecontrol.io/packages/Emmet): Emmet (ex-Zen Coding) for Sublime Text.
- [HTML-CSS-JS Prettify](https://packagecontrol.io/packages/HTML-CSS-JS%20Prettify): HTML, CSS, JavaScript and JSON code formatter for Sublime Text 2 and 3 via node.js.
- [Jade](https://packagecontrol.io/packages/Jade): This was made specifically for Sublime Text 2, but was tested and works with Textmate 2 and Sublime Text 3.
- [jQuery](https://packagecontrol.io/packages/jQuery): Sublime Text package bundle for jQuery.
- [Sass](https://packagecontrol.io/packages/Sass): Sass support for TextMate & Sublime Text (2 & 3).
- [MarkdownEditing](https://packagecontrol.io/packages/MarkdownEditing): Powerful Markdown package for Sublime Text with better syntax understanding and good color schemes.
- [Color Highlighter](https://packagecontrol.io/packages/Color%20Highlighter): which underlays selected hexadecimal colorcodes (like "#FFFFFF", "rgb(255,255,255)", "white", etc.) with their real color. Also, plugin adds color picker to easily modify colors.
- [CSS3](https://packagecontrol.io/packages/CSS3): The most complete CSS 
- support for Sublime Text 3.
- [New Moon Color Scheme](https://packagecontrol.io/packages/New%20Moon%20Color%20Scheme): New Moon Color Scheme for Sublime Text.
- [Material Theme](https://github.com/equinusocio/material-theme): Material Theme for Sublime Text 3 3103+
- [SideBarEnhancements](https://packagecontrol.io/packages/SideBarEnhancements): Enhancements to Sublime Text sidebar. Files and folders.
- [Sublime​Linter-jshint](https://packagecontrol.io/packages/SublimeLinter-jshint): **[SublimeLinter](http://www.sublimelinter.com/en/latest/)** plugin for JavaScript, using jshint.
- [Doc​Blockr](https://packagecontrol.io/packages/DocBlockr):Simplifies writing DocBlock comments in Javascript, PHP, CoffeeScript, Actionscript, C & C++

###Package操作

- `Cmd+shift+P` 输入 `ip`,找到 `Install Package`
- `Cmd+shift+P` 输入 `rp`,找到 `Remove Package`
- `Cmd+shift+P` 输入 `lp`,找到 `List Packages`


##个性化 Sublime

`Preferences -> Settings - User`

```
{
    "font_face": "Monaco",
    "font_size": 16,
    "highlight_line": true,
    "tab_size": 2,
    "translate_tabs_to_spaces": true,
    "ignored_packages":
    [
        "Markdown",
        "Vintage"
    ],
    "save_on_focus_lost": false
}
```

##其他

[https://github.com/jikeytang/sublime-text](https://github.com/jikeytang/sublime-text)
