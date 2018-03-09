---
ID: 102
post_title: >
  StackEdit写作，同步到GitHub和WordPress上
post_name: stackedit_sync_github_wordpress
post_date: 2018-02-27 14:19:29
layout: post
link: >
  http://www.233lab.com/stackedit_sync_github_wordpress/
published: true
tags:
  - GitHub Sync WordPress
  - Tools
  - WordPress
categories:
  - Tools
---
今天在看[阮一峰老师的博客](http://www.ruanyifeng.com/blog/)，忽然想到自己搁置已久的[博客](www.233lab.com)，顿感羞愧，“如果我也能这么高产就好了”。So，在阮老师的GitHub上，翻找到了[articles项目](https://github.com/ruanyf/articles)，一看commit信息包含好多 `Published with https://stackedit.io/`  ，
然后就来到了StackEdit这个网站一探究竟。

##  1.StackEdit

![StackEdit](http://www.233lab.com/wp-content/uploads/2018/02/stackedit-logo.png)

显然，[`StackEdit`](https://stackedit.io/)是一款在线markdown编辑器，直接点击“START WRITING”，开始体验。
在StackEdit的右侧MENU，提供了如下选项：  

![StackEdit Menu](http://www.233lab.com/wp-content/uploads/2018/02/StackEdit_menu.jpg)

点击“Add GitHub account”,

![StackEditwithGitHub](http://www.233lab.com/wp-content/uploads/2018/02/stackedit_github.jpg)
  
操作一番后，直接链接到自己所属的GitHub上。
接下来，将自己编辑好的文档，Publish到你想要Publish到的GitHub 项目下就行啦。
![PublishtoGitHub](http://www.233lab.com/wp-content/uploads/2018/02/publishtogithub.jpg)

**需要注意的是：**

 1. 文件名一直不变化的情况下，每次Publish后，会覆盖GitHub上的原文件；转而言之，如果在StackEdit上修改了文件名，并Publish后，GitHub上会出现两个md文档。
 2. “File publication”是管理当前文件的publication locations.一旦地址发生变化，GitHub上也会有相应的变化。
![enter image description here](http://www.233lab.com/wp-content/uploads/2018/02/publication_location.jpg)

目前为止，最简单的StackEdit同步到GitHub上基本完成。StackEdit也提供了其他各式各样的功能，例如目录功能“Table of contents”，Markdown语法速查，本地导入导出等功能，可以自行发掘。
总之，StackEdit解决了我想要在线Markdown写作，并同步到GitHub上的需求。

接下来介绍的内容适合拥有WordPress建站的人群。



## 2.GitHub sync WordPress

那么如何将GitHub的markdown文件同步到WordPress上呢？
需要用到一个WordPress插件：[`writing_on_github`](https://github.com/litefeel/writing-on-github)，具体的配置可以看Github页面上的[**如何配置**](https://github.com/litefeel/writing-on-github#configuring-the-plugin)。

简略步骤如下：
 1. 安装`writing_on_github`插件；在WordPress的插件管理页面中选择“安装插件”，搜索“writing on github”即可，安装后并激活。如有问题可查看[`安装`](https://github.com/litefeel/writing-on-github#installation)。
 2. 在GitHub上生成“Personal oauth token”,[**点此链接**](https://github.com/settings/tokens/new)，勾选repo中的public_repo即可。
![enter image description here](http://www.233lab.com/wp-content/uploads/2018/02/oauth_token.png)
 点击最下方的“Generate token”就会得到一个token。
 复制下新生成的token值，后面会用到。
 ![enter image description here](http://www.233lab.com/wp-content/uploads/2018/02/token.png)
 
 3. 登录到WordPress后台，writing_on_github设置页面。
   ![setting](http://www.233lab.com/wp-content/uploads/2018/02/WordPress-setting.png)
   其中 Webhook密匙，自己设定一个强密码，后面在添加webhook的时候会用到。
   项目名称填写自己要关联的项目。格式类似于`coolMusk/test`。
   
 4. 在GitHub上，该项目的Settings页面，点击“Webhooks”，来添加webhook。webhook的作用是一旦GitHub有更新，就会同步到WordPress上。![webhook setting](http://www.233lab.com/wp-content/uploads/2018/02/webhooksetting.png)
 5. 然后会发现添加的webhook会立即ping一下所填写的PayLoad URL.如果你的webhook前面有个绿色的勾，则表示已经ping通。

现在，可以欢快的在stackedit上写文章，同步到WordPress上了！


## 3.参考资料

 - https://github.com/litefeel/writing-on-github ,by litefeel
 - https://developer.github.com/webhooks/, by GitHub
 
 （完）