# 雷霆战机！
雷霆战机，CS架构，服务器计算事件，本地浏览器渲染画面。
这是大学网络应用系统开发课程的课程作业
在我的认知中，大学的课程对做这个东西的帮助绝对没有一个deepseek的帮助大，甚至可以被完全覆盖。
所以我准备在学期初就全速把这个东西做出来。
起始时间：2025-2-18
计划结束时间：2025-2-28
diary
2-19： 
和deepseek聊了很多，感觉工作量大约有90个小时左右，ds辅助能快些，但也快不了多少。
我计划今天晚上先做出来一个demo，把浏览器与服务器连接起来，至少能收到浏览器端的事件。

2-20
接着聊，现在使用python搭建服务器，使用HTML5 Cavans + JavaScript 作为前端
现在的逻辑还算是比较简单，用python搭建服务器，如果有对象连接8080端口，发送请求"http://127.0.0.1:8000/game.html"那就把本地的game.html文件送过去，对面浏览器就会自动运行。

ai是真的快！

2-21
现在使用deepseek的方式是在腾讯云上建一个新的应用，25号，之前都是免费的。
每次需要什么新的功能就找deepseek实现一个功能单一的，然后把内容融合到主体的文件之中，deepseek对于这种定制的项目没有特别强的效果，至于那种自动编程的并改错的，我记得有这种软件，以后搞来试试看。

2-22
  今天看了课程项目的设计需求，为本项目增加以下内容以拿分。
  1.反向代理服务器：负载均衡分发请求，就是接收请求，然后把任务分发出去。
  2.数据库服务器：用户登录请求验证
  3.应用服务器:与数据库服务器合作完成登录处理
  4.Web服务器:分发web页面（把game.html传过去）
