# Alfred 迅雷离线插件

### 使用此插件需要：

- 迅雷离线账号
- [Alfred][alfred] & [powerpack][alfred-pp]
- [迅雷离线下载脚本][xunlei-lixian]

### 此插件可实现的功能:

- 批量添加bt任务(种子文件或者magnet链接)
- 批量添加http/ftp/thunder/qqdl/flashget/ed2k/magnet url任务(将链接保存到link.txt)
- 获取离线任务下载链接

### 插件使用方法:

[详细使用方法](http://imwuyu.me/blog/alfred-extension-for-xunlei-lixian.html/ "使用方法-博客")

#### 测试通过

✔ lx push :剪切板普通链接（httpURL, magnet, ftp带中文与空格, thunderURL，ed2k带中文）

✔ lx push -t : 剪切板 种子链接,torrent-info-hash

✔ lx push -lf :本地link.txt，本地连接文件混合多种链接，批量添加 magnet 链接

✔ lx push -tf :本地种子文件(中文名，带空格)，选择多个文件添加

### Bonus

[TextExpander][TE] Snippets (Alfred-XLixian.textexpander)

- x   >>> lx push
- xt  >>> lx push -t
- xtf >>> lx push -tf
- xlf >>> lx push -lf

[alfred]:http://www.alfredapp.com/
[alfred-pp]: http://www.alfredapp.com/powerpack/ 
[xunlei-lixian]: https://github.com/iambus/xunlei-lixian "迅雷离线下载脚本"
[TE]:http://smilesoftware.com/TextExpander/ "TextExpander"