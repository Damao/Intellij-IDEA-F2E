#使用Live edit插件修网页外部css文件时在chrome中无法显示变化效果

---

* **工具名称**：IntelliJ IDEA
* **工具版本**：13.1.6
* **操作系统**：windows 7


* **问题描述**：
>在intellij IDEA中使用live edit插件修改网页文件的连接的外部css文件代码时，
在chrome浏览器中网页样色没有发生变化。修改内部css跟行内css的代码时正常显示变化。


* **引起问题的原因**；
>问题源于chromium的一次更新,详情请看
http://src.chromium.org/viewvc/blink/trunk/Source/devtools/protocol.json?revision=166228    
以下是官方的live edit讨论区对于这个问题的谈论，第一条评论指出的问题所在。 http://youtrack.jetbrains.com/issue/WEB-11393#comment=27-722471



* **解决方案**：

>总之凡是那一次版本更新后的chrom内核版本都不能用，最新版的chrome肯定不行。
可以考虑使用低版本内核的chrome浏览器或者其他基于chrome内核的浏览器，比如基于chrome 32的UC浏览器。








---

* **作者**：Genji [新浪微博](http://weibo.com/u/1612465254 "个人微博")
* **时间**：2014年5月31日 17：26：05
