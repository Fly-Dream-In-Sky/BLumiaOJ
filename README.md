# BLumiaOJ HustOJ_Web 分支

一个旧版HustOJ的前端界面模板

概述
===
该分支和BLumiaOJ并无关联，而是旧版HustOJ的一个模板，因为早期的二次开发版本，故置于此。
这是一个基于旧版HustOJ的前端界面模板，针对学校需求增加和改变了部分功能，并调整了界面。
如果您对新OJ的开发有兴趣，请移步master分支。

本HustOJ的修改版基于[zhblue的hustoj（广泛使用但较旧）](https://github.com/zhblue/hustoj) 而非[freefcw的hustoj（官方新版但用户并不多）] https://github.com/freefcw/hustoj/。使用则全部替换JudgeOnline目录下（或您的网站文件夹所在位置）的所有文件即可。数据库结构未变更，您可能需要先修改include文件夹内的配置文件才能使用。关于配置文件的相关内容可以参见[这里](http://blog.csdn.net/zhblue/article/details/7366194)。如果您希望全新配置一个oj以供使用，建议选择上面提到的freefcw的hustoj，或者待BLOJ开发完成后选择我们的OJ（2333）。

功能
===
该改进版中所提供的功能：

* 基于bootstrap3的界面美化（ie8+以及其他支持html5的浏览器）
* 根据关键词搜索结果并排名（针对学号注册账号的学校进行同届或班级排名信息）
* 题目分类功能补充
* 修改了统计图表的显示区间使之更适于学校

>注：关于附带的HustOJ修改版
>---
>* 您需要使用ie8+浏览器以达到网页支持
>* 您需要修改配置文件以适配您的服务器
>* 您需要适当修改主页(template/bs3/index.php)以改变首页的部分为学校定制的内容
>* 反馈版（吐槽版）没有包含在本修改版的代码中，但您可以轻易的实现它
>* 新OJ开发计划将保持数据库和此修改版一致，并提供基于旧hustoj到BLOJ的迁移解决方案(2333)

>注意：

>* 该版本并没有任何其它特色功能。
>* 该版本和新OJ项目没有任何关系。并且已经不再进行主要维护。
>* 在新OJ项目基本成型后，旧的基于HustOJ的修改版将停止维护。
