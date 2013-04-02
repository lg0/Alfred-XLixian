# 迅雷离线（Alfred v2）

### 使用此插件需要：

- 迅雷离线账号

#### 设置账号（原来使用旧版插件的可跳过此步）

- lx user username password

![lx user](http://i.minus.com/ibfDiiVpnU8T9Z.png)

#### 上传链接

- lx：「剪切板」高亮，上传剪切板中的「链接/info-hash」
- lx --bt：「剪切板」高亮时按「tab」自动补全，适用于「链接」为种子文件下载地址

#### 上传单个文件

- lxf links.txt，保存多个下载链接
- lxf 1.torrent，单个种子文件
- lxf *，列出指定域中所有[.torrent]和[.txt]文件供选择

#### 上传多个文件

在 Finder 中选中要上传的所有[.torrent]或[.txt]，然后按「option+cmd+\」打开 File Action，选择「离线下载」

#### 查询离线任务

- list 「关键字」/「序号」@，当输入「@」时开始检索离线任务，请耐心等待

使用举例：

* list 权利的游戏@：使用关键字
* list '大爆炸 福尔摩斯'@：多个关键字
* list 'mp4 mkv'@：多种格式
* list 0@：序号「0」为最新添加的任务
* list 0-9@：列出最新添加的10项任务，使用方向键或「ctrl+n/p」来上下移动可查看没有显示的条目
* list '0 2 4 8-10'@
* list 2013.04.01@：按时间搜索

#### 获取下载链接

- 使用「list」查询到的任务按下「Enter」即可复制下载链接到剪切板。
- 当列出的任务为「BT」，「Enter」会获取「BT」任务内所有文件的下载链接
- 当列出的任务为「BT」，「Shift+Enter」可查看「BT」任务内单文件的状态并可复制链接。

#### 自动更新

支持 [Alleyoop](http://www.alfredforum.com/topic/1582-alleyoop-update-alfred-workflows/) 

#### Bonus

如果在使用 fakeThunder，在 Alfred 中输入 「ft」可将剪切板链接添加到 fakeThunder 中，适合立刻就要下载的任务。

---

TODO：

- ~~获取bt任务内所有文件的下载链接~~
- 删除任务

使用反馈可用[Issues][githubiss],或在[Blog][myblog]留言

[githubiss]: https://github.com/CrazyApi/Alfred-XLixian/issues?state=open
[myblog]: http://imwuyu.me/talk-about/xlixian-for-alfred-v2.html/

---

### 本插件使用了：

- [xunlei-lixian](https://github.com/iambus/xunlei-lixian "迅雷离线下载脚本")
- [alp](https://github.com/phyllisstein/alp "A Python Module for Alfred Workflows")
