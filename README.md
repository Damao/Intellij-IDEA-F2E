#Intellij-IDEA-F2E

**[IntelliJ IDEA](http://www.jetbrains.com/idea), [PHPStrom](http://www.jetbrains.com/phpstorm), [WebStorm](http://www.jetbrains.com/webstorm) 前端开发指南.**

常规文本编辑器之于IDE(集成开发环境), 好比 Markdown 之于 HTML

Markdown 杀鸡嗷嗷叫, 但做网站必须得 HTML

这件事情告诉我们, 高帅富配白富美, 屌丝配右手

最适合你的编辑器,就是世界上最好的编辑器

切莫活在别人的世界里

##编辑器选择
配置较差的同学推荐 PHPStrom , 因为前端开发的同学基本都会玩点 PHP, 所以不推荐 WebStorm

对于配置好,气质佳的同学,墙裂推荐 Intellij IDEA Ultimate, 功能全面,更新最快,性能最好,吃内存相对多

社区免费版阉割的略微有点过...自重

##因特里基友QQ群(人多,严禁跑题,违者T)
* 149725975 (CSS/HTML/JavaScript/PHP Intellij IDE/PHPStorm/WebStorm)


##序列号
12 注册机在群共享里有了.

所有大版本序列号都是通用的

等你脚的 Intellij IDEA 帮你赚钱了,记得购买正版授权,或者传递真爱给身边的同学

##编辑器界面
`Settings > Appearance > Look and Feel`,
黑色的到 Intellij IDEA 12 才有,叫 Darcula

##配色
妹纸到手,第一步就是扒光

Intellij IDEA 的配色是 xml 或 jar 文件

xml:

* for Mac OS, ~/Library/Preferences/IntelliJIDEA10CE/colors/
* for Linux, ~/.IntelliJIDEA10CE/config/colors/
* for Windows, C:\Documents and Settings\user\.IntelliJIDEA10CE\config\colors

jar: `File > Import Settings`

比较常用的有 [intellij-colors-solarized](https://github.com/jkaving/intellij-colors-solarized) , [Twilight](https://github.com/eed3si9n/color-themes/tree/master/IntelliJ-IDEA/Twilight)

比较全面的有 [Idea Color Schemes](http://ideacolorschemes.com/)

###字体
`Settings > Editor > Colors & Fonts > Font`

因为没法 GUI 界面中英文分开设置,简单的方法就是安装 Yahei Consolas hybrid 字体(群共享有)

字号我这里 17px 英文相对清晰,你可以根据预览来微调

IDEA12 开始自带了 Source Code Pro, Adobe 家的开源等宽字体,也很舒服滴

##性能优化
* 使用最新版
* 关闭不认识的插件
* Project 下的文件不要太多,否则会有大量的 I/O
* 关掉版本控制(svn git 啥的)
* 升级硬件, SSD 神马的


##FAQ

* 如何自动换行? 答:全局 Settings>Editor>use soft wraps in editor ; 当前文档 在行号的位置右键选择 use soft wraps
* 有木有 ST2 那种同时选中多个区域? 答:木有,我们一般用[Refactor 重构](http://ooxx.me/intellij-idea-refactor.orz)(Shift + F6),列编辑(Alt + 拖动),批量替换(Ctrl + r) 来实现.
* 右边那条线是啥? Settings>Appearance>Show right margin ; 这玩意儿格式化的时候控制换行区域,不用的话可以禁用

##教程

* [Java Development Kit(JDK)下载及环境设置](http://willerce.com/post/jdk)
* [PHP 支持](http://ooxx.me/intellij-idea-php.orz)
* [配置 Project](http://ooxx.me/intellij-idea-project.orz)
* [Local History](http://ooxx.me/intellij-idea-local-history.orz)
* [Live Template](http://ooxx.me/intellij-idea-live-template.orz)
* [Task](http://ooxx.me/intellij-idea-task.orz)
* [File Path](http://ooxx.me/intellij-idea-file-path.orz)
* [Surround / unwrap](http://ooxx.me/intellij-idea-surround-unwrap.orz)
* [Refactor 重构](http://ooxx.me/intellij-idea-refactor.orz)
* [Appearance](http://ooxx.me/intellij-idea-appearance.orz)
* [LiveEdit Plugin](http://ooxx.me/intellij-idea-liveedit-plugin.orz)
* [WebStorm 使用外部工具](http://willerce.com/post/intellij-external-tools)
* [Yabo(鸭脖) - CSS 压缩合并工具](http://ooxx.me/yabo.orz)
* [实现 remote host 远程开发](http://www.cssha.com/webstorm-phpstorm-remote-host)
* [WebStorm：令人眼前一亮的一款前端开发IDE](http://www.cssha.com/webstorm)
* [IDEA 配置同步](http://willerce.com/post/intellij-idea-config-sync)
* [安装后的一些设置技巧](http://www.cnblogs.com/sky100/archive/2009/01/22/1379949.html)
* [插件 QuickJump](http://ooxx.me/intellij-idea-quickjump.orz)

---

*此文档由 Intellij IDEA [Markdown 插件](https://github.com/nicoulaj/idea-markdown)编辑 && Github 插件提交,欢迎补充*
