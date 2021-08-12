# 038ssm在线选课管理系统
038ssm在线选课管理系统

## 项目介绍
````
一个简单的“在线教学平台系统”，实现基本的选课功能。
主要功能：
管理员能够实现学生基本信息的录入、修改、删除等操作，其中学生信息包括学号、姓名、性别、专业等信息；
管理员能够实现课程的录入、修改、删除等功能，其中课程信息包括课程号、课程名、课程图片、学分等；
学生能实现选课功能，每个学生可以在首页浏览课程信息，并可以进行选课操作，其中课程信息包括学分、上课地点、课程编号、授课教师、课程名等信息；
管理员可以查看学生选课信息，并可以进行添加选课学生和删除选择该课程的学生等操作；
有汇总功能，管理员首页可以查看没门课程的选课人数。
````

源码获取：[ **点此获取** ](http://www.shuyue.fun/index.php?type=productinfo&id=139)

## 环境需要
````
1.运行环境：最好是java jdk 1.8，我们在这个平台上运行的。其他版本理论上也可以。

2.IDE环境：IDEA，Eclipse,Myeclipse都可以。推荐IDEA;

3.tomcat环境：Tomcat 7.x,8.x,9.x版本均可

4.硬件环境：windows 7/8/10 1G内存以上；或者 Mac OS；

5.是否Maven项目: 是；查看源码目录中是否包含pom.xml；若包含，则为maven项目，否则为非maven项目

6.数据库：MySql 5.7版本；
````

## 软件架构
````
系统是一个基于SSM框架实现的项目，采用当前最流行的框架Spring-SpringMVC-MyBatis设计。

前端：HTML+BootStrap+CSS+Javascript
后端：Spring+SpringMVC+mybatis
````

## 使用说明
````
1. 使用IDEA/Eclipse/MyEclipse导入项目，Eclipse/MyEclipse导入时，若为maven项目请选择maven;若为maven项目，导入成功后请执行maven clean;maven install命令，下载所需jar包；

2. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并导入项目的sql文件；

3. 将项目中db.properties配置文件中的数据库配置改为自己的配置

4. 配置tomcat，然后运行项目，输入localhost:8080/xxx 登录

5. 管理员账号：admin  密码：123456

学生账号：000001   密码：123456
````

## 运行截图
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/170545_64e94b15_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/170600_f0c05d95_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/170611_201d18dc_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/170623_71d61e24_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/170648_afdc1a9c_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/170657_97a91aae_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/170727_6c7b8fed_863230.png "屏幕截图.png")
![输入图片说明](https://images.gitee.com/uploads/images/2021/0315/170801_4eade191_863230.png "屏幕截图.png")
