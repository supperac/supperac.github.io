刚刚开了博客，不为别的。除了以后找工作铺垫、展示自己，也希望以后回头能看看自己的心路历程，自己进步了多少。到那时技术更成熟的我回头观望技能尚青涩的我应该也是满满的欣慰吧。<br>
刚开了博那就先说说我是怎么开始的，以此纪念一下。

## 起点
想用github pages作为我的技术博客一方面是因为它是和github联通的，写一些博文发表很方便。另一方面是它的线上资源比较多，整合起来比较容易。
其他国内的技术博客我觉得做的还不错的有csdn和简书。

## 开始
要建立一个github pages博客，首先你需要:<br>
 1. github 账号<br>
 2. 一个markdown编辑器(如果自己的md语言十分强硬，语言格式信手拈来，那么可以在github上直接编辑)
 
## 设置步骤
1. 打开[Jekyll Themes](http://jekyllthemes.org/), 选择你喜欢的主题。
![](https://github.com/supperac/ts/blob/master/screenshot-jekyllthemes.org-2018.04.25-01-59-27.jpeg?raw=true)<br>
点击demo出现预览，选择好后点击hompage来到github该主题页面。
<br>
2. 仔细阅读该主题repo的README.md, 里面有详细讲解如何设置并使用为自己github pages的主题。基本为以下三种方法。<br>
	a. fork该repo到自己的仓库<br>
	b. Ruby Gem<br>
	c. Jekyll Remote Theme<br><br>
我是用第一种方法克隆到自己的仓库的，步骤为下:<br><br>
	a. 在页面右上方点击fork该主题克隆到自己的仓库
	![](https://github.com/supperac/ts/blob/master/screenshot-github.com-2018.04.25-02-19-10.jpeg?raw=true)<br>
b.  点击菜单栏右边的settings会出现设置页面。在Repository name 里写上`用户名.github.io` 。
例如我的: `supperac.github.io`。
点击Rename你的博客的地址就修改完成了。如果你立即打开你的博客页面，可能会看到error 404的情况，不要着急，github pages更新需要时间，在github上的更新有时候需要最多15-20分钟的间隔才会在博客上看到。如果你写了一篇新的帖子，在博客里点进去这个帖子出现`error 404, the file can not be found` 也是同样的原因，只要等几分钟就会出来了。
![](https://github.com/supperac/ts/blob/master/screenshot-github.com-2018.04.25-02-24-22.jpeg?raw=true)


## 设置博客基本信息
接下来到这个模板的repo里找到README.md文件。里面有具体的模板特点介绍、安装信息(每个模板的安装方法细节稍有不同，要根据README.md文件中Installation的步骤来安装）、和安装后所需要做出更改的介绍。
基本信息储存在repo根目录下`_config.yml` 文件里。<br>
`title`改成你的博客名称<br>
`description`是鼠标悬停在博客名称上时显示的名称<br>
`author`是博主名字<br>
还有其他一些设置就不一一列举了。<br>
## 创建博文
在repo的根目录下找到_posts的文件夹，点击进入，在这里面创建你要写的博客文章。
点击Create new file 创建新的文章。在`Name your file` 中写入文章的名称。格式按照`YYYY-MM-DD-Your-File-Name.md`。
这样就可以开始你的博客旅程了。

## Markdown编辑器
我用的是Stackedit，因为它可以和github账号连接并同步，在stackedit编辑好博文可以直接推送到github。
但是有一点我观察到在使用stackedit的时候，如果不用vpn它的auto sync功能受限，经常会显示sync not possible的现象，如果你也遇到这样的问题，尝试连接vpn解决这一问题。

这就是我探索的开播方法，看似简单，我用了将近2-3个小时，不要笑，这就是自学的过程。哈哈哈哈


<!--stackedit_data:
eyJoaXN0b3J5IjpbMjAxMDg0NzU5NCwtMTIyMDU1OTkwLDMzNT
c4OTUyOCw2MDk3MTUxNDcsLTEyNDgzMDY1NjEsLTE4NTI3OTYz
NDcsMTU5Nzk3MjU5OCwxNTExNTc5ODUzLC0xMjY0Mjc1NjUsMT
kxOTAzNjI5MywxODM1MTkyNDM0LDEzNTEzNTU2OTMsLTEzOTY3
Mzg3MDMsLTE3NzQxNTk3MTIsMjk3MTM0MTY4LDQyMzA0MDI0My
wtMzA2ODgyOTcxLC0yMTQxMTIzODgsLTIxMjcyNzA5MTEsLTE0
Mzc3ODc5XX0=
-->