#IntelliJ-IDEA-F2E
  
**[IntelliJ IDEA](http://www.jetbrains.com/idea), [PHPStorm](http://www.jetbrains.com/phpstorm), [WebStorm](http://www.jetbrains.com/webstorm) 前端开发指南.**  
  
常规文本编辑器之于IDE(集成开发环境), 好比 Markdown 之于 HTML  
Markdown 杀鸡嗷嗷叫, 但做网站必须得 HTML  
这件事情告诉我们, 高帅富配白富美, 屌丝配右手  
最适合你的编辑器,就是世界上最好的编辑器  
切莫活在别人的世界里  
  
##编辑器选择  
WebStorm 针对前端开发集成了一些比较常用的例如node.js LESS之类,性能好速度快  
PHPStorm 针对PHP也做了一些优化,并且包含了 WebStorm  
IntelliJ IDEA 则通过插件形式集成上面两者的功能,并且是主力 JAVA IDE, 功能强,速度慢,吃内存多  
我目前是同时装了 WebStorm 和 IntelliJ IDEA,反正配置通用,按需取用。  
  
##因特里基友QQ群(人多,严禁跑题,违者T)  
  
我在使用XX遇到了问题。  
我已经尝试过XXX方法。  
现在问题的具体表现、信息为XXXXXX。  
这样的格式更有利于解决问题。  
  
附赠:[提问的智慧](http://www.wapm.cn/smart-questions/smart-questions-zh.html)  
  
避免无意义的讨论,例如`打招呼`,例如`美化`比较主观,没有固定答案的问题都不能讨论  
如果对大部分人都无价值的话题,建议`私聊`  
  
群号：149725975 (CSS/HTML/JavaScript/PHP IntelliJ IDE/PHPStorm/WebStorm)  
群号：244908708 (偏后端)  
  
入群问题答案请 **包含小写有空格的关键字** `intellij idea`  
  
  
##注册  
在群共享里有jar包.
下载后运行 java -jar IntelliJIDEAKeyGen.jar
所有大版本序列号都是通用的  
等你脚的 IntelliJ IDEA 帮你赚钱了,记得购买正版授权,或者传递真爱给身边的同学  
  
##促销  
[开源中国正版全系列7折](http://www.oschina.net/shop/jetbrains)  
  
##编辑器界面  
`Settings > Appearance > Look and Feel`,  
黑色的到 IntelliJ IDEA 12 才有,叫 Darcula  
  
##配色  
妹纸到手,第一步就是扒光  
IntelliJ IDEA 的配色是 icls 或 jar 文件
可能还有些xml的丢到目录里会自动转换为 icls 文件
  
icls:
  
* for Mac OS, ~/Library/Preferences/IntelliJIdea13/colors/
* for Linux, ~/.IntelliJIdea13/config/colors/
* for Windows, C:\Documents and Settings\user\.IntelliJIdea13\config\colors
  
jar: `File > Import Settings`  
  
比较常用的有 [intellij-colors-solarized](https://github.com/jkaving/intellij-colors-solarized) , [Twilight](https://github.com/eed3si9n/color-themes/tree/master/IntelliJ-IDEA/Twilight) , [Obsidian](https://github.com/mekwall/obsidian-color-scheme 'A dark color scheme for code editors and highlighters'), [Tomorrow](https://github.com/chriskempson/tomorrow-theme/tree/master/Jetbrains)
  
比较全面的有 [Idea Color Schemes](http://ideacolorschemes.com/) [PHPStorm Themes](http://www.phpstorm-themes.com/)  
  
Sublime Text2 转过来的同学还有 [Obsidian Color Scheme](https://github.com/mekwall/obsidian-color-scheme)  
  
[Sublime Text2 的配色转成 idea](https://github.com/JetBrains/colorSchemeTool) (感谢 ash)  
  
###编辑器字体  
`Settings > Editor > Colors & Fonts > Font`  
字号我这里 17px 英文相对清晰,你可以根据预览来微调  
IDEA12 开始自带了 Source Code Pro, Adobe 家的开源等宽字体,也很舒服滴  
[IntelliJ IDEA 中文乱码,字体优化解决之道](http://bigc.at/intellij-idea-font-famliy.orz) 按照教程设置英文和中文2个字体，就可以分别爽了  
  
##性能优化
* 如果有杀毒软件,请排除掉项目路径
* 使用最新版  
* 关闭不认识的插件  
* Project 下的文件不要太多,否则会有大量的 I/O  
* Excluded 掉无需索引的目录  
* 关掉版本控制(svn git 啥的)  
* 升级硬件, SSD 神马的  
  
  
##FAQ  
  
* Windows 7 sometimes breaks FTP connections on Java 7 if firewall is enabled.Command netsh advfirewall set global StatefulFTP disable usually fixes [the problem](http://youtrack.jetbrains.com/issue/WI-17206).  
* 官方[《IDEA 30天速成》](http://blogs.jetbrains.com/idea/tag/30-days-guide/)  
* 常用快捷键? 'Help > Default Keymap reference'  
* 如何自动换行? 答:全局 `Settings > Editor > use soft wraps in editor` ; 当前文档 在行号的位置右键选择 use soft wraps  
* 有木有 ST2 那种同时选中多个区域? 答:木有,我们一般用[Refactor 重构](http://bigc.at/intellij-idea-refactor.orz)(Shift + F6),列编辑(Alt + 拖动),批量替换(Ctrl + r) 来实现.  
* 右边那条线是啥? Settings>Appearance>Show right margin ; 这玩意儿格式化的时候控制换行区域,不用的话可以禁用  
* 关闭任意位置编辑（也称虚拟空格）？ Settings>Editor>Allow placement of caret after end of line  
* 界面中文乱码？Setting>Appearance>Override default fonts by ，下拉框中选“微软雅黑”，可能找不到微软雅黑，因为中文字体也乱码了，所以先选一个乱码名字的字体就可以找到了。  
* 显示多列/行文件? tag 上右键选择 Split vertically / Split horizontally  
* 全屏模式? 'View>Enter full screen'  
* 注释在行首而不是紧接着代码? Code Style > Java > Comment Code > Line comment at first column  
* Project侧边里不显示文件夹？ [因为没有 Module ](http://stackoverflow.com/questions/1147336/how-to-get-intellij-idea-to-display-directories)  
  
  
##教程  
  
###基础设置  
* [常用快捷键](http://note.youdao.com/share/?id=973d61880d78c34797a978afc5bc8846&type=note)  
* [Java Development Kit(JDK)下载及环境设置](http://willerce.com/post/jdk)  
* [PHP 支持](http://bigc.at/intellij-idea-php.orz)  
* [配置 Project](http://bigc.at/intellij-idea-project.orz)  
* [Appearance](http://bigc.at/intellij-idea-appearance.orz)  
* [IntelliJ IDEA 中文乱码,字体优化解决之道](http://bigc.at/intellij-idea-font-famliy.orz)  
* [实现 remote host 远程开发](http://www.cssha.com/webstorm-phpstorm-remote-host)  
* [WebStorm：令人眼前一亮的一款前端开发IDE](http://www.cssha.com/webstorm)  
* [IDEA 配置同步](http://willerce.com/post/intellij-idea-config-sync)  
* [IDEA 字体美化](http://willerce.com/post/intellij-ide-fontconfig)  
* [LESS 自动编译](http://www.screenr.com/yn47) *(WebStorm 6)*  
* [LESS -> CSS编译支持](https://github.com/damao/Intellij-IDEA-F2E/wiki/Compile-Less-to-CSS-with--IntelliJ-IDEA) *(IDEA 12)*  
* [Intellij IDEA中使用Ant进行前端构建](http://www.cssha.com/intellij-idea-ant)  
* [Intellij IDEA 视频专讲](http://www.youmeek.com/category/software-system/my-intellij-idea/)  
* [如何在 IntelliJ IDEA 里配置 PhoneGap 3.3](http://bigc.at/phonegap-with-intellij-idea.orz)  
  
###技巧  
  
* [安装后的一些设置技巧](http://www.cnblogs.com/sky100/archive/2009/01/22/1379949.html)  
* [插件 QuickJump](http://bigc.at/intellij-idea-quickjump.orz)  
* [Local History](http://bigc.at/intellij-idea-local-history.orz)  
* [Live Template](http://bigc.at/intellij-idea-live-template.orz)  
* [Task](http://bigc.at/intellij-idea-task.orz)  
* [File Path](http://bigc.at/intellij-idea-file-path.orz)  
* [Surround / unwrap](http://bigc.at/intellij-idea-surround-unwrap.orz)  
* [Refactor 重构](http://bigc.at/intellij-idea-refactor.orz)  
* [LiveEdit Plugin](http://bigc.at/intellij-idea-liveedit-plugin.orz)  
* [WebStorm 使用外部工具](http://willerce.com/post/intellij-external-tools)  
* [Yabo(鸭脖) - CSS 压缩合并工具](http://bigc.at/yabo.orz)  
* [IntelliJ IDEA解决GBK乱码](http://nornor.net/Intellij-IDEA-gbk-fix.htm)  
* [对比文件/文件夹](http://blog.jetbrains.com/webide/2013/02/comparing-files-and-folders-within-your-ide/)  
* [Emmet/ZenCoding 快捷键](http://docs.emmet.io/cheat-sheet/)  
* [WebStorm：令人眼前一亮的一款前端开发IDE](http://www.cssha.com/webstorm)  
* [缩进, Tab 还是空格?](http://bigc.at/tabs-vs-spaces.orz)  
  
#Bug  
  
* SVN 1.8 的支持要到13版本才行 [IDEA-94942](http://youtrack.jetbrains.com/issue/IDEA-94942)  
* 如果通过FTP方式同步会导致中文文件名乱码,推荐用SFTP  
* 英文字体会导致中文显示成口口口,[IntelliJ IDEA 中文乱码,字体优化解决之道](http://bigc.at/intellij-idea-font-famliy.orz)  
* win8 拼音输入法吞字,请使用[QQ拼音4.5](http://pan.baidu.com/s/1vL2sn)提取密码：a4k3，要么用QQ拼音4.6的设置里高级关掉英文词语联想,或者安装第三方JDK如[Oracle JRockit](http://www.oracle.com/technology/products/jrockit)  
* 拖动滚动条浏览代码，松开鼠标，会自动滚回光标的位置，在哪里设置？有道词典的屏幕取词和划词翻译的勾选去掉(感谢阿安)  
* idea12 server log中文乱码的问题，解决办法是修改idea/bin目录下的idea.exe.vmoptions文件，增加配置-Dfile.encoding=UTF-8 (感谢匆匆过客)；如果这样还不能解决，请参考 [idea12 server log中文乱码解决方法](http://www.kafeitu.me/tools/2013/03/26/intellij-deal-chinese-disorderly-code.html)  
* [IDEA下tomcat启动报错解决](https://github.com/Damao/Intellij-IDEA-F2E/wiki/IDEA-%E4%B8%8B%E5%90%AF%E5%8A%A8tomcat%E6%8A%A5%E9%94%99)  
  
---  
  
*此文档由 IntelliJ IDEA [Markdown 插件](https://github.com/nicoulaj/idea-markdown)编辑 && Github 插件提交,欢迎补充*())  
