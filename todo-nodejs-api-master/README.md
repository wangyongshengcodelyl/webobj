# 前言
NodeJS全栈开发之后端接口开发基于Node.js+Express+Mysql实现RESTFUL API，接口包括：登录，注册，记住密码，修改密码，退出登录，todoList增删改查CRUD，查询条件筛选，点亮红星标记等。本项目场景虽然简单，但涵盖功能比较齐全，适合初学全栈开发的小伙伴。如果觉得不错的话，请大大们给个:heart:star，也期待大家一起交流学习。

[在线DEMO演示](http://106.55.168.13:8082/)

[NodeJS全栈开发一个功能完善的Express项目实战分享](https://juejin.im/post/6844904198551666701)

# 目录结构
```
│  app.js                              // 入口文件
│  ecosystem.config.js                // pm2默认配置文件
│  package.json                       // npm包管理所需模块及配置信息
├─db
│      dbConfig.js                    // mysql数据库基础配置
├─routes
│      index.js                       // 初始化路由信息，自定义全局异常处理
│      tasks.js                       // 任务路由模块
│      users.js                       // 用户路由模块
├─services
│      taskService.js                 // 业务逻辑处理 - 任务相关接口
│      userService.js                 // 业务逻辑处理 - 用户相关接口
└─utils
        constant.js                   // 自定义常量
        index.js                      // 封装连接mysql模块
        md5.js                        // 后端封装md5方法
        user-jwt.js                   // jwt-token验证和解析函数
```


# 技术栈
 * NodeJS v10
 * express
 * mysql v5.7
 * jwt
 * nodemon
 * cors
 * boom
 * pm2
 
# 功能模块
* 登录（登出）
* 注册
* 记住密码
* 修改密码
* todo增删改查
* 点亮红星标记
* 查询条件筛选

# 下载安装依赖
```
cd todo-nodejs-api
npm install 或 yarn
```




## 开发模式
```
npm start
```
运行之后，访问地址：http://localhost:8088



