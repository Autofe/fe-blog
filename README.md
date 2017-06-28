## 汽车之家车服务前端博客

Vue2, Vue SSR, Koa2, MongoDB and Redis

前后端分离 + 服务端渲染的博客系统, 前端SPA + 后端RESTful服务器

# Demo 
前端：[http://wangshiyang.com)

后台管理截图：暂无 

目录
=================

* [TODO](#todo)
* [构建与部署](#构建与部署)
  * [前置](#前置)
  * [server](#server)
  * [front](#front)
  * [admin](#admin)
* [后端RESTful API](#后端restful-api)
  * [说明](#说明)
  * [HTTP动词](#http动词)
  * [权限验证](#权限验证)
      * [获得Token](#获得token)
      * [撤销Token](#撤销token)
      * [Token说明](#token说明)
  * [查询](#查询)
  * [新建](#新建)
  * [替换](#替换)
  * [更新](#更新)
  * [删除](#删除)  

  
  # TODO
- [x] 前台单页
  - [x] vue2.0
  - [x] vuex状态管理
  - [x] vue SSR服务端渲染
  - [x] 客户端谷歌统计 
  - [x] 组件级缓存
  - [x] Loading组件
  - [x] 侧边栏图片
  - [x] 文章toc
  - [x] 页面meta
  - [x] SSR服务端不可用时进行降级
- [x] 后台管理单页
  - [x] vue2.0
  - [x] 使用element ui
  - [x] 七牛云图片上传
  - [x] 文章toc的生成与编辑
  - [x] 草稿的自动生成与手动恢复
  - [x] 上传图片后指定img标签的高度以避免闪烁
  - [x] 扫描所有文章，指定img高度
- [x] RESTful服务器
  - [x] RESTful添加select字段过滤
  - [x] 标签及分类移至文章中 
  - [x] 七牛access_token下发及鉴权
  - [x] lint

  
# 构建与部署

- Node v6
- webpack
- pm2
- MongoDB
- Redis







 