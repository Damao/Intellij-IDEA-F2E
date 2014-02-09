#Mac系统下控制台输出乱码

---

* **工具名称**：IntelliJ IDEA
* **工具版本**：12.1.6
* **操作系统**：Mac OS
* **问题描述**：
![问题描述](http://external-img.b0.upaiyun.com/mac-system-IntelliJ-IDEA-Chinese-garbled.jpg)
* **解决方案**：
在配置IntelliJ IDEA的tomcat时，给VM选项添加此参数：-Dfile.encoding=UTF-8
更具体请参考http://www.kafeitu.me/tools/2013/03/26/intellij-deal-chinese-disorderly-code.html

---

* **作者**：Judas.n [作者Blog](http://www.YouMeek.com "个人博客")
* **时间**：2014年2月9日 16:57:28
