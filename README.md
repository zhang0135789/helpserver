# 校园综合服务平台小程序后台服务端

#### 项目链接
本项目配合以下两端使用：<br>
[1.小程序端地址：https://github.com/landalfYao/help.git](https://github.com/landalfYao/help.git)<br>
[2.后台客户端地址：https://github.com/landalfYao/helpclient.git](https://github.com/landalfYao/helpclient.git)<br>

#### 线上部署教程
1. 后台服务端部署教程[https://my.oschina.net/u/4053979/blog/3026392](https://my.oschina.net/u/4053979/blog/3026392)

#### 安装教程

1.新建数据库
数据库文件 help.sql

```
CREATE SCHEMA `help` DEFAULT CHARACTER SET utf8mb4 ;
```

2.修改配置文件
路径 pub/config/config.js

```
  MYSQL: {
    host: "localhost:3306",
    user: "root",
    password: "", //数据库密码
    port: "3306",
    database: "help", //数据库名
    timezone: "+08:00",
    dateStrings: true
  },


  APP_ID: "", //微信小程序APPID
  APP_SECRET: "", //微信小程序APP密钥
  Mch_id: "", //商户号
  Mch_key: "", //商户密钥
```

3.安装依赖并启动

```
npm install
npm start
```

访问[http://localhost:3337](http://localhost:3337)

#### 交流
微信号:landalfyzy<br>
![输入图片说明](https://images.gitee.com/uploads/images/2019/0320/102250_efc7b2d0_1930998.jpeg "微信图片_20190320102141.jpg")
