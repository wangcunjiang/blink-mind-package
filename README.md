Awesome outliner is an outliner app. All data is stored locally.

Now only provide the Chinese version. The English version will be provided in the next release. So the remaining part of the document will be written in Chinese. The English document and app will be provided in the next release.

# 简介

Awesome outliner 是一款大纲笔记app,所有的数据都保存在本地。

软件的主界面如下:
![image](./screenshots/dashboard.jpg)
其中我的文档选项卡显示用户创建的所有文件和文件夹。

编辑中文档选项卡显示用户正在编辑的文档

回收站选项卡显示用户的回收站，回收站里面的内容可以被恢复或者彻底删除。


# 使用说明

## 创建文档
在我的文档界面中点击新建按钮，弹出新建文件和新建文件夹菜单。
![image](./screenshots/create-doc.jpg)
点击新建文件按钮创建一个新的文档，点击新建文件夹按钮则创建一个新的文件夹。

多层文件夹嵌套可以通过上方的文件夹导航栏进行跳转。
![image](./screenshots/file-nav.jpg)

光标移到文档图标上时文档会高亮，点击之后会打开文档
![image](./screenshots/open-file.jpg)

## 文档管理
光标移到文档或者文件夹图标上时会高亮，并且在右上角还会出现一个齿轮状按钮，点击这个按钮会弹出菜单，可以对文档进行重命名，移动和删除操作。目前移动到功能尚未开发。

![image](./screenshots/file-context-menu.jpg)

点击删除按钮会弹出对话框
![image](./screenshots/remove-file-to-trash.jpg)

## 文档编辑
打开文档之后会自动跳转到编辑中文档选项卡，所有正在编辑中的文档都会以tab页的方式显示在其中。
![image](./screenshots/opening-files.jpg)

按住鼠标并拖动文档的标题栏，将会将这个文档脱离原来的主界面，新开的窗口进行编辑。

![image](./screenshots/file-tabs.jpg)

新窗口如下：
![image](./screenshots/new-edit-window.jpg)

### 编辑器内部操作
与[workflow](https://workflowy.com/) 非常类似。
在某个条目下按enter 键新建一个兄弟节点。按tab 键将当前项变成其上面的兄弟节点的子节点。

#### 编辑描述项

在某个条目下右键弹出右键菜单，可以进行编辑描述操作。
![image](./screenshots/item-context-menu.jpg)

在编辑描述时可以从网页复制内容直接粘贴进去。编辑器会进行排版，文字的图片都会以很好的格式保存。
![image](./screenshots/paste-html.jpg)

可以直接粘贴截图软件的截图到这里，在截图软件里面把截图保存在剪切板，然后在这里按Ctrl + V 或者 Command + V 进行粘贴。

![image](./screenshots/paste-image.jpg)

可以在IDE 里面直接复制粘贴代码到这里。
![image](./screenshots/paste-code.jpg)