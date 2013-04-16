# 迅雷离线（Alfred v2）

#### 使用此插件需要：

- Alfred Powerpack
- 迅雷离线账号
- [fakeThuner][fake]（可选）

[fake]:https://github.com/MartianZ/fakeThunder

#### 该插件可以：

* 添加 链接/种子（支持批量任务）
* 查询 离线任务
* 复制 任务下载链接（支持BT）
* 调用 fakeThuner 下载任务（剪切板链接）

#### 个人说明

对于立刻需要下载的链接，调用fakeThunder下载最方便，但是它不支持上传种子，可使用本插件方便的 **批量** 添加种子或链接。


### [使用帮助](https://github.com/CrazyApi/Alfred-XLixian/wiki/使用说明)

---

TODO：

- 使用 aria2c 和 yaaw 管理和下载任务
- 删除任务
- ~~获取bt任务内所有文件的下载链接~~

使用反馈可用[Issues][githubiss]，或在[Blog][myblog]留言

[githubiss]: https://github.com/CrazyApi/Alfred-XLixian/issues?state=open
[myblog]: http://imwuyu.me/talk-about/xlixian-for-alfred-v2.html/

更新日志：

* v1.34 [修复] 更新离线api，更新 Alleyoop 支持 @ 2013.4.16
* v1.33 [修复] lxf 文件名中有特殊符号导致添加失败 @ 2013.4.11
* v1.32 [增强] lxf links文件类型调整，可自行在filetype中配置 @ 2013.4.3
* v1.30 [发布] 支持 Alfred v2 @ 2013.4.2

---

### 本插件使用了：

- [xunlei-lixian](https://github.com/iambus/xunlei-lixian "迅雷离线下载脚本")
- [alp](https://github.com/phyllisstein/alp "A Python Module for Alfred Workflows")
