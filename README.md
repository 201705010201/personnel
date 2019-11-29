# 人事管理系统
本项目的环境介绍：
eclipse， JDK 1.8， MySQL 5.7， （mysql的辅助工具，Nivicat for MySQL）， tomcat 8.5.
此项目是基于ssm框架编写的，前端页面是JQuery实现的。有需要的可以做了解，一起学习。
部署到tomcat之后，运行，可以在eclipse中设置自动跳转浏览器，也可以运行结束之后，输入http://localhost:8080/personnel/，进行访问。
一共包含了6个模块，用户管理，部门管理，职位管理，员工管理，公告管理，下载中心。
说一下在下载中心模块，可以进行文档的查询，以及上传文档，在你上传文档之前，先看一下src源码中的com.rain.controller.DocumentController类，
里面有一个路径：path = "E://personnel-document//";你首先在你自己电脑的E盘建立personnel-document文件夹，然后再选选择你锁上传到的文件，即可，如果你要是不建这个文件夹，会报500错误，找不到代码位置。
