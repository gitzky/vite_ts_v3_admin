# 使用 vite + typescript + vue3.0 搭建一个企业级的后台管理系统

## 生成基础框架

推荐使用 ```Yarn``` 命令构建基础框架. ``` yarn create vite app --template vue-ts ```


### 3

#### 权限管理

- 动态路由
  - 添加菜单
  - 添加角色用户
  - 路由拦截next参数
  - 路由权限接口
  - 生成路由组件
  - addRoute 动态添加路由  
  - 动态路由的跳转
- 元素级全下
  - 注册自定义指令
  - 应用自定义指定
  - 元素级权限逻辑
  - 权限编码整合

- 路由守卫
  - 登录逻辑
  - Cookie
  - Action 异步
    - 异步登录
    - 目录别名
  - 路由守卫
    - to，form,next 参数
    - 校验token
    - 数据源
    - 退出