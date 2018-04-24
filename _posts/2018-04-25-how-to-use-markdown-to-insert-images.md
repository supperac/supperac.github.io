# Markdown 插入图片心得体会及编辑技巧整理
## Markdown 插入图片方法

 **1.将图片上传到github**
步骤如下:
a. 将markdown需要用的图片放到git仓库库中，发布到github上。
b. 访问github上自己存放图片的Repo。
c. 访问该图片并且点击download按钮,，在地址栏复制图片地址，或者在download按钮上直接右键“复制链接地址”。
d. 在markdown文本中引用图片 `![hello world] (图片链接3达不溜点巴拉巴拉巴拉点康姆)`

**2.插入本地图片**
需要在基础语法的括号中插入图片的位置路径就可以，支持绝对路径和相对路径。
例如:
`![hello world] (/user/desktop/meme.jpeg)`

    其缺点是不灵活，本地图片路径更改或者丢失都会造成markdown文件读取不了图片。
  
  

**3.上传至网络相册**
类似于第一种方式。上传图片于网络相册，复制图片地址即可。第一种方式相当于把github当做一个网络相册来作为一个载体。
在此，如果选择上传到网络相册，那么需要注意一下有的网络相册是不支持外部链接的。在选择的时候需要留意。

注:
个人倾向于第1种方法和第3种方法。虽然方法笨拙，但是相比较之下是最稳妥之计。虽然需要几个步骤但是链接不会失效而且不需要其他的一些技巧。

## markdown编辑器

接下来说一下markdown language 编辑器吧
markdown语言是一种简单高效率的文本编辑，使用起来其实是很方便，只需记得主要的集中方式即可，但是也有牛人开发了markdown 编辑器就使得编辑纯文本格式编写文档，然后转换成格式丰富的HTML页面的效率更高。网上主流的markdown编辑器主要有这两种, 一种是桌面编辑器，另一种是在线编辑器。在我的搜索经验看来，在线编辑器占大多数，并且功能也很强大。 
现在我正在写这篇文章使用的是stackedit。

整个界面是这个样子的，很整洁干净。
![stackedit](https://raw.githubusercontent.com/supperac/ts/master/screenshot-stackedit.io-2018.04.24-12-42-39.jpeg)

转了一圈stackedit之后发现，stackedit的强大在于：
-   管理多个 MarkDown 文档。可在线或离线编辑
-   通过模板导出 MarkDown 或 HTML 格式文件
-   云同步 MarkDown 文档
-   支持 Google Drive, Dropbox 和本地硬盘驱动器等备份
-   Post MarkDown 文档到 Blogger 、Blogspot、WordPress和Tumblr
-   发布 MarkDown 文档到GitHub，GIST，Google Drive，Dropbox或不论什么SSHserver
-   分享一个及时渲染的 MarkDown 文档链接
-   文档信息统计显示
-   转换HTML到 MarkDown
-   以Gist公布后支持分享

支持：
-   实时编辑、HTML预览并自己主动滚动定位到编辑处
-   Markdown Extra 支持 Prettify/Highlight.js 的语法高亮
-   LaTeX 数学表达式使用MathJax
-   所见即所得的控制button
-   可配置的布局
-   支持多个主题
-   A la carte extensions
-   离线编辑
-   Google Drive和Dropbox在线同步
-   一键公布支持 Blogger, Dropbox，GIST，GitHub，Google Drive，SSH server，Tumblr，WordPress

最实用的是stackedit右边界面带有cheat sheet, 忘记怎么用了可以立即查看。
![Markdown cheat sheet](https://github.com/supperac/ts/blob/master/screenshot-stackedit.io-2018.04.24-12-53-54.jpeg?raw=true)

在搜索markdown编辑器的时候，我也找到了一个可以为经常使用evernote的人带来福音的markdown编辑器。
马克飞象是是一款专为印象笔记（Evernote）打造的Markdown编辑器，可以配合印象笔记进行存储和同步笔记。
功能亮点:
支持高亮代码块、*LaTeX* 公式、流程图，本地图片以及附件上传，甚至截图粘贴，工作学习好帮手； - **得心应手** ：简洁高效的编辑器，提供桌面客户端和离线Chrome App，支持移动端 Web； - **深度整合** ：支持选择笔记本和添加标签，支持从印象笔记跳转编辑，轻松管理。 详情请戳: https://maxiang.io/
功能亮点:

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTY2MjY0MzYwMywxNDAwNzk5MjI0LDE4MT
EzMjcwNCwtMTMyNDY5NTcwLC00ODc5NDYxMzAsLTI4MDgzOTEz
OCwyMDcyMDM1NDQsLTYwNjEwNTk1NywtNTczMTk0NTAzXX0=
-->