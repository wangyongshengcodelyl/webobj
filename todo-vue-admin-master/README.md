
# 部分截图

│  package.json                      // npm包管理所需模块及配置信息
│  vue.config.js                     // webpack配置
├─public
│      favicon.ico                   // 图标
│      index.html                    // 入口html文件
└─src
    │  App.vue                       // 根组件
    │  main.js                       // 程序入口文件
    ├─assets                         // 存放公共图片文件夹
    ├─components
    │      Footer.vue                // 页面底部公用组件
    │      Header.vue                // 页面头部公用组件
    ├─router
    │      index.js                  // 单页面路由注册组件 
    ├─store
    │  │  index.js                   // 状态管理仓库入口文件
    │  └─modules
    │          userInfo.js           // 用户模块状态管理文件
    ├─styles
    │      base.scss                 // 基础样式文件 
    ├─utils
    │      api.js                    // 统一封装API接口调用方法
    │      network.js                // axios封装与拦截器配置
    │      url.js                    // 自动部署服务器环境
    │      valid.js                  // 统一封装公用模块方法
    └─views
            Home.vue                 // 首页界面
            Login.vue                // 登录界面
