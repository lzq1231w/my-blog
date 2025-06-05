# my-blog## 介绍

一个基于vue + node.js + mongodb的前后端分离个人博客😆
![my_blog](https://segmentfault.com/img/bVcTgBV)

## 环境

vue-cli 4.5.0
node.js 14.16.0
mongodb 4.4.5

## 技术栈

前端：vue-cli，vue-router，vuex，axios，bootstrap
后端：node.js，mongodb，express

## 主要功能

前台：文章详情，文章列表、文章分类，文章搜索、评论和点赞、用户登陆、登出和注册，发送邮件
后台：发布、修改、删除文章（仅站长），账户设置、信息修改（所有人）

## 数据库

用户信息、文章信息、评论信息

## 其他

除了使用技术栈实现博客的基本框架外，还包括一些其他的关键技术，包括：

1. 通过bootstrap、@media、rem单位等相关技术实现了网页的响应式布局；
2. 通过设置响应头部解决跨域问题；
3. 通过mavon-editor实现markdown格式文本的编辑和解析；
4. 通过md5对用户的密码进行加密；
5. 通过animate.css实现动画效果；
6. 通过nodemailer实现邮件的发送功能；
7. 通过FileReader对象实现图片保存功能

## How to start

克隆远程库

```
git clone https://github.com/xmie233/vueblog.git
```

安装依赖

```
cd my_blog   // 进入项目所在目录
npm install
```

启动mongodb数据库

```
mongod --dbpath d:\data      // d:\data 为数据库存放位置，可自行设置
```

启动服务器（上一步的终端不要关，打开新的终端）

```
cd serve   //进入项目目录中的serve目录,即my_blog/serve
node app.js
```

开启博客（上一步的终端不要关，打开新的终端，等待一会页面将在8081端口自动弹出）

```
npm run serve
```

## 效果(部分展示)

### 前台

导航
![header](https://segmentfault.com/img/bVcTgzw)
页脚
![footer](https://segmentfault.com/img/bVcTgCc)
首页
![home](https://segmentfault.com/img/bVcTgzU)
所有文章
![articles](https://segmentfault.com/img/bVcTgzJ)
留言板
![contact](https://segmentfault.com/img/bVcTgzM)
文章详情
![article](https://segmentfault.com/img/bVcTgzv)
登陆界面
![login](https://segmentfault.com/img/bVcTgzW)

### 后台

文章列表
![post](https://segmentfault.com/img/bVcTgzX)
编辑文章
![editor](https://segmentfault.com/img/bVcTgzV)

### 移动端

![移动端](https://segmentfault.com/img/bVcTgzZ)
