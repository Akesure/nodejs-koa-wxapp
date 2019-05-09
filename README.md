## 项目介绍
![image](https://img.shields.io/badge/koa-%5E2.7.0-brightgreen.svg) ![koa--bodyparser](https://img.shields.io/badge/koa--bodyparser-%5E4.2.1-brightgreen.svg) 
![koa--router](https://img.shields.io/badge/koa--router-%5E7.4.0-brightgreen.svg)
![require--directory](https://img.shields.io/badge/require--directory-%5E2.1.1-brightgreen.svg)
![sequelize](https://img.shields.io/badge/sequelize-%5E5.6.1-brightgreen.svg)
![mysql2](https://img.shields.io/badge/mysql2-%5E1.6.5-brightgreen.svg)
![validator](https://img.shields.io/badge/validator-%5E10.11.0-brightgreen.svg)
![lodash](https://img.shields.io/badge/lodash-%5E4.17.11-brightgreen.svg)

Node.js Koa2 实战开发微信小程序服务端API接口。

## 数据库
启动项目前一定要在创建好 `wxapp` 数据库。
```
# 登录数据库
$ mysql -uroot -p密码

# 创建 wxapp 数据库
$ CREATE DATABASE IF NOT EXISTS wxapp DEFAULT CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci;
```

## 项目使用
首先使克隆项目，然后进入项目根目录使用命令安装包，最后命令启动项目，代码会根据模型自动创建数据库表的。
```
# 克隆项目代码
$ git clone https://github.com/liangfengbo/nodejs-koa-wxapp.git

# 进入koa项目根目录
$ cd nodejs-koa-wxapp

# 安装包
$ npm install

# 运行服务
$ npm run dev

# 打开浏览器输入回车：http://localhost:3000
```

## 项目技术栈
Koa服务端编程、异步编程、面向对象编程。

- Koa 与 Koa 二次开发API 
- 多 koa-router 拆分路由
- require-directory 自动路由加载
- nodemon修改文件自动重启
- 异步编程，async/await 
- 异步异常链与全局异常处理 
- Sequelize ORM 管理 MySQL
- JWT 权限控制中间件 
- Validator 与 LinValidator 验证器
- [更多介绍..](./doc/Koa项目基础.md)


## 接口v1

- [x] [正在开发中，敬请期待..](###)

## License
[MIT](https://github.com/liangfengbo/nodejs-koa-wxapp/blob/master/LICENSE)

Copyright (c) 2019 - present, Fengbo Liang
