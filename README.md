# douban-demo
# 利用豆瓣电影的公共接口，请求获取数据，制作了一个微信小程序demo


# 小程序的知识点：
- 1>视图组件的运用：如轮播图的制作 swiper, 可滚动视图容器的运用，scroll-view,等
- 2>数据接口的两种方式：
   - 小程序通过微信的api直接发送ajax请求，wx.request;
   - 通过云函数请求数据，注意先下载依赖库request 再安装request-promise
- 3>组件间的跳转：wx.switchTap,wx.redirectTo,wx.navigateTo


# 云开发 quickstart

这是云开发的快速启动指引，其中演示了如何上手使用云开发的三大基础能力：

- 数据库：一个既可在小程序前端操作，也能在云函数中读写的 JSON 文档型数据库
- 文件存储：在小程序前端直接上传/下载云端文件，在云开发控制台可视化管理
- 云函数：在云端运行的代码，微信私有协议天然鉴权，开发者只需编写业务逻辑代码

## 参考文档

- [云开发文档](https://developers.weixin.qq.com/miniprogram/dev/wxcloud/basis/getting-started.html)

# 新增
- 解决小程序请求豆瓣报错403问题
   - 把api.douban.com换成douban.uieee.com
