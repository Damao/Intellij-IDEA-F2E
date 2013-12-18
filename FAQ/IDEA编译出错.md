# 序
IDEA编译出错信息
 

**将eclipse里的java文件拷贝到idea里,文件没提示任何错误,编译提示如下：**

      IntelliJ IDEA中错误提示：java: Syntax error on token "Invalid Character", delete this token**
	  IntelliJ IDEA中错误提示：“非法字符： \65279"**

**解决方案：**

	  在网上找了解决方法的地址 [解决方法] (http://qiaoshi.iteye.com/blog/1850027)
	  将eclipse里的java文件拷贝到idea里,文件没提示任何错误,编译提示如下:
      IntelliJ IDEA中错误提示：java: Syntax error on token "Invalid Character", delete this token**
	  IntelliJ IDEA中错误提示：“非法字符： \65279"**
      由于我在MAC下尝试了网上的第一种解决方案不行,第二种方案由于电脑上没有NotePad++所以没有尝试
      最后我的解决方法是将提示编译报错的文件,将file encodings由utf-8改成utf-16,再将utf-16改成utf-8就好了

 