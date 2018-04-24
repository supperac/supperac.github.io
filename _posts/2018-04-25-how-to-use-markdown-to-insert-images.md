# Markdown 插入图片心得体会及编辑技巧整理
## Markdown 插入图片方法

## **1.将图片上传到github**
步骤如下:
a. 将markdown需要用的图片放到git仓库库中，发布到github上。
b. 访问github上自己存放图片的Repo。
c. 访问该图片并且点击download按钮,，在地址栏复制图片地址，或者在download按钮上直接右键“复制链接地址”。
d. 在markdown文本中引用图片 `![hello world] (图片链接3达不溜点巴拉巴拉巴拉点康姆)`

## 2.插入本地图片
需要在基础语法的括号中插入图片的位置路径就可以，支持绝对路径和相对路径。
例如:
`![hello world] (/user/desktop/meme.jpeg)`

    其缺点是不灵活，本地图片路径更改或者丢失都会造成markdown文件读取不了图片。
  
  

## 3.上传至网络相册
类似于第一种方式。上传图片于网络相册，复制图片地址即可。第一种方式相当于把github当做一个网络相册来作为一个载体。
在此，如果选择上传到网络相册，那么需要注意一下有的网络相册是不支持外部链接的。在选择的时候需要留意。

注:
个人倾向于第1种方法和第3种方法。虽然方法笨拙，但是相比较之下是最稳妥之计。虽然需要几个步骤但是链接不会失效而且不需要其他的一些技巧。


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTcyNzk1NjUxNiwyMDcyMDM1NDQsLTYwNj
EwNTk1NywtNTczMTk0NTAzXX0=
-->