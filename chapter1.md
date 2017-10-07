# 使用方法

####1.安装环境
* 1.安装Node.js,进入[Node.js](https://nodejs.org/en/)官网下载Node.js安装,进入终端输入node -v可以查看node.js版本就说明安装成功了
* 2.在终端输入 sudo npm install gitbook-cli -g 安装gitbook,加上sudo,获取管理员权限否则可能报错，或者下载客户端软件[gitbook](https://www.gitbook.com/editor/)
* 3.如果需要本地生成pdf,mobi,epub等格式的书籍需要安装[Calibre](https://calibre-ebook.com/download)

####2.Markdown语法
###### 1.网上的一些介绍：
* [Markdown 语法手册 （完整整理版） ](http://blog.csdn.net/witnessai1/article/details/52551362)
* [Markdown——入门指南](http://www.jianshu.com/p/1e402922ee32/)
* [Markdown 语法说明 (简体中文版) ](http://www.appinn.com/markdown/)

######2.常用的语法
* 1.标题字体


```
    # 一级标题
    ## 二级标题
    ### 三级标题
    #### 四级标题
    ##### 五级标题
    ###### 六级标题
```
效果：
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题



* 2.斜体和粗体


```
    *斜体*或_斜体_
    **粗体**
    ***加粗斜体***
    ~~删除线~~
```
效果：
*斜体*或_斜体_
**粗体**
***加粗斜体***
~~删除线~~


* 3.超链接

快捷键:[command + shift + 9]
3.1. 行内式
[]里写链接文字，()里写链接地址, ()中的”“中可以为链接指定title属性，title属性可加可不加。title属性的效果是鼠标悬停在链接上会出现指定的 title文字。[链接文字](链接地址 “链接标题”)这样的形式。链接地址与链接标题前有一个空格。


```
[百度主页](https://www.baidu.com/）

```
效果：
[百度主页](https://www.baidu.com/)










