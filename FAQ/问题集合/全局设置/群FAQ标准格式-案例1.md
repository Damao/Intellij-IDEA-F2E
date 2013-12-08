#修改文件提示save file failed

---

* **工具名称(必填)**：IntelliJ IDEA
* **工具版本(必填)**：13.1.6
* **操作系统(必填)**：windows 7
* **JDK版本(必填)**：JDK 1.6
* **部署容器(选填)**：jetty 9.1
* **问题描述(必填)**：  
(描述尽量详细、清晰，宁肯文字多点，也不要让人看不懂)
使用jetty运行web项目时，修改文件提示save file failed，并且生成 *.\___jb\_old\____格式的文件
* **解决方案(必填)**：  
在web.xml中添加如下配置：
```
<servlet>       
	<!-- Override init parameter to avoid nasty -->       
	<!-- file locking issue on windows. -->       
	<servlet-name>default</servlet-name>       
		<init-param>           
			<param-name>useFileMappedBuffer</param-name>           
			<param-value>false</param-value>       
		</init-param> 
</servlet>
```
>(另一写法，外链化，鼓励的方式。但是请牢记，让别人多移步一次，尽量不能让别人失望)
>详细解答过程请移步：http://t.cn/8kZZ1Uy

* **参考链接(可选)**：
>http://devnet.jetbrains.com/thread/432700

---

* **作者**：Judas.n [作者Blog](http://www.YouMeek.com "个人博客")
* **时间**：2013年12月1日 23:06:45
