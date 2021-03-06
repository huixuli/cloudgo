﻿# CloudGo应用程序开发
标签（空格分隔）： go语言学习

---
此次的作业，我完成了一个与CloudGo应用程序类似的项目。

## 框架介绍

在我本次的项目开发中，用到了老师在课堂上用到的三个框架[mux](https://studygolang.com/articles/7268)，[negroni](http://blog.csdn.net/abqchina/article/details/53906963)，[render](http://blog.csdn.net/lb7758zx/article/details/51694373)。
## 代码编写

此次实验中我所编写的服务器与客户端代码都是参考了老师在课程上所介绍的博客[HTTP 协议 与 golang web 应用服务](http://blog.csdn.net/pmlpml/article/details/78404838)。加以理解与修改完成我此次的代码编写，编写完成后从网络上下载服务器用到的框架结构文件，在对自己的main.go进行编译运行。

## 测试

***运行自己的main代码***

![代码运行截图](/截图/4.png)

***curl测试***

![curl截图](/截图/2.png)

***在网页上查看结果***

![网页结果截图](/截图/1.png)

***压力测试***

![](/截图/3.1.png)
![](/截图/3.2.png)
根据上面截图的结果所示。一共有1000个请求，失败了0个请求，端口为8080， 平均请求响应时间为 9.472ms 每个请求实际相应时间的平均值 0.094ms

最大的响应时间为41ms毫秒等等


