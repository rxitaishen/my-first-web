# 开源软件技术windows版

芒果命令行下运行 MongoDB 服务器

注意：我的都是在D盘！

```
d:\mongodb\bin\mongod --dbpath d:\data\db
```



## 连接MongoDB

```
d:\mongodb\bin\mongo.exe
```





let的作用于比var更小，只作用在那个大括号里



D盘已是全局express

## 创建项目步骤（以下在cmd的d盘目录下里运行

### 安装全局express

```undefined
npm install -g express-generator
```

### 创建一个项目

```undefined
在当前目录下创建项目的命令      
express myapp
```

### 进入项目并安装依赖

```bash
cd myapp
npm install
```

### 启动项目

npm start

### 安装成功

打开浏览器，输入http://localhost:3000/。可以看到这个界面，说明安装成功。

### 原文作者：祈澈姑娘 技术博客：[https://www.jianshu.com/u/05f416aefbe1](https://link.jianshu.com?t=http%3A%2F%2Flink.zhihu.com%2F%3Ftarget%3Dhttps%3A%2F%2Fwww.jianshu.com%2Fu%2F05f416aefbe1)



```css
项目创建成功之后，生成四个文件夹，主文件app.js与配置信息文件packetage.json

bin是项目的启动文件，配置以什么方式启动项目，默认 npm start

public是项目的静态文件，放置js css img等文件

routes是项目的路由信息文件,控制地址路由

views是视图文件，放置模板文件ejs或jade等（其实就相当于html形式文件啦~)

express这样的MVC框架模式，是一个Web项目的基本构成。
```