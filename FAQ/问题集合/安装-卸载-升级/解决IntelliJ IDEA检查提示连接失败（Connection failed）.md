#IntelliJ IDEA检查更新提示连接失败（Connection failed）

---

* **工具名称**：IntelliJ IDEA
* **工具版本**：13.0.1
* **操作系统**：windows 8
* **问题描述**：
通过菜单栏-->Help-->Check for Update 进行检查更新，提示连接失败
* **解决方案**：
在IDE Settings里面设置HTTP Proxy，原本是No Proxy，设置为使用Use Proxy。
配置根据你的代理设置进行配置。我使用的是goagent，代理配置为127.0.0.1，端口8087，
这样更新成功。

```
PS：
	从版本13.0到13.0.1的更新，我是用电信的网络，4M带宽，会出现上面描述的错误。
	But，今天下午发现用宿舍联通的网络可以直接更新了。从330到331，更新补丁大小为1M。
```

>详细配图解答过程请移步：[http://t.cn/8kCZ3Ty](http://t.cn/8kCZ3Ty "笔记记录")

---

* **作者**：Charkey [新浪微博](http://weibo.com/worldfather168 "新浪微博")
* **时间**：2013年12月18日 18：55
