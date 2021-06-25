# oss_project
# 开源软件技术期末大作业项目说明书

#### 项目概述

​		这次大作业我设计的是一个笔记信息管理系统，是基于千锋教育的开源课程的基础上改进的，用户登录后可以创建笔记、修改笔记、删除笔记，网站是一个共享平台，用户在网站中不仅可以看到自己创建的笔记，还可以看到其他用户的笔记，方便笔记共享。

#### 技术介绍

前端使用ejs渲染，后端使用nodejs和express，数据库使用mongodb，创建笔记功能使用了xheditor

#### 参考项目

https://github.com/hfpp2012/express-todolist

https://github.com/jiayisheji/jianshu

https://github.com/tangguangyao/know

#### 启动

要求nodejs和mongodb环境

在项目文件夹下打开终端，输入命令:

`npm start`

在运行bin文件夹下的www.js:

`node ./bin/www`

然后在浏览器中输入:

`localhost：3000`



![Screenshot from 2021-06-24 05-35-30](/home/ubuntu1804/Pictures/Screenshot from 2021-06-24 05-35-30.png)

#### 系统界面

登录页

用户输入用户名和密码登录，没有账号可以点"立即注册"进入注册页面，管理员账户可以通过"管理员登录"进行登录

![Screenshot from 2021-06-24 05-36-56](/home/ubuntu1804/Pictures/Screenshot from 2021-06-24 05-36-56.png)

注册页

注册时需要输入用户名，输入密码后需要再确认一遍，注册完毕后会跳转到登录界面，用户即可登录刚刚创建好的账号

![Screenshot from 2021-06-24 05-41-32](/home/ubuntu1804/Pictures/Screenshot from 2021-06-24 05-41-32.png)

首页

进入首页可以看到所有用户在系统内创建的笔记，点击笔记标题即可进入笔记详情页，查看笔记内容，笔记按创建时间顺序排列，可以看到该笔记的创建时间、作者以及笔记标题，点击右侧编辑可以进入笔记修改页面编辑笔记内容，点击删除即可删除笔记，在导航栏左侧有home图标，点击可返回首页，右侧会显示当前登录的账户，点击创建笔记就可以在当前账户下创建新的笔记，点击退出，退出系统，回到登录页面

![Screenshot from 2021-06-24 05-38-59](/home/ubuntu1804/Pictures/Screenshot from 2021-06-24 05-38-59.png)

创建笔记页

点击创建笔记后，进入创建笔记页，输入笔记标题与笔记内容后，点击创建笔记即可完成创建

![Screenshot from 2021-06-24 05-39-40](/home/ubuntu1804/Pictures/Screenshot from 2021-06-24 05-39-40.png)

笔记详情页

点击笔记标题，进入笔记详情页，可以看到笔记详细内容

![Screenshot from 2021-06-24 05-40-29](/home/ubuntu1804/Pictures/Screenshot from 2021-06-24 05-40-29.png)

笔记编辑页

点击编辑，进入笔记编辑页，以当前账户在原笔记的基础进行修改，点击修改，即修改完成

![Screenshot from 2021-06-24 05-41-03](/home/ubuntu1804/Pictures/Screenshot from 2021-06-24 05-41-03.png)

#### 数据库设计

创建了project数据库，创建了三个collections：admins，articles，users

![Screenshot from 2021-06-24 05-07-10](/home/ubuntu1804/Pictures/Screenshot from 2021-06-24 05-07-10.png)

users

创建了四个用户：kkk，pp，oo，ff

![Screenshot from 2021-06-24 04-46-10](/home/ubuntu1804/Pictures/Screenshot from 2021-06-24 04-46-10.png)

admins

创建了两个管理员：admin，管理员

![Screenshot from 2021-06-24 04-58-16](/home/ubuntu1804/Pictures/Screenshot from 2021-06-24 04-58-16.png)

articles

创建了20余篇笔记，包括管理员创建的和用户创建的

![Screenshot from 2021-06-24 05-00-01](/home/ubuntu1804/Pictures/Screenshot from 2021-06-24 05-00-01.png)

![Screenshot from 2021-06-24 05-00-20](/home/ubuntu1804/Pictures/Screenshot from 2021-06-24 05-00-20.png)

![Screenshot from 2021-06-24 05-00-36](/home/ubuntu1804/Pictures/Screenshot from 2021-06-24 05-00-36.png)

![Screenshot from 2021-06-24 05-01-03](/home/ubuntu1804/Pictures/Screenshot from 2021-06-24 05-01-03.png)

#### git链接

https://github.com/TrexLC/oss_project

