## js-ratel-client

[![](https://img.shields.io/badge/license-Apache-blue)]()[![build status](https://img.shields.io/badge/build-passing-brightgreen)]()[![](https://img.shields.io/badge/javascript-%3E%3D%20ES6-brightgreen)]()

`js-ratel-client` 是一款运行在浏览器上的[ratel](https://github.com/ainilili/ratel)客户端。此客户端对原先的`ratel-client`功能进行了**100%**还原。

并且与其他客户端相比，其具有以下特点：

1. 使用更加简单，无需下载编译客户端，最简便的方式仅仅是输入一个网址即可使用
2. 页面更加友好，借助`html` + `css`的强大渲染能力下，我们对展示界面进行了一些优化
3. 更好的隐蔽性，我们在页面上嵌入了百度等网页，你可以边打牌边假装查资料
4. 支持自定义化配置，打造你的专属页面

另外需要强调的是：虽然此客户端使用`websocket`协议进行通信，但是可以和其他客户端用户一起游戏

### Install

#### 下载

```shell
git clone https://github.com/marmot-z/js-ratel-client.git
cd js-ratel-client
```

#### 部署

1. 直接双击`index.html`使用浏览器打开页面进行游戏
2. 部署在`tomacat`、`jetty`等应用服务器或者`nginx`代理服务器上，可提供外部访问进行游戏
3. 访问已部署的地址（如：http://47.103.16.48:8080/js-client/）进行游戏

### Usage

1. 连接服务器，输入页面显示的服务地址编号选择公共服务器连接，或者输入`ip:port`形式服务器地址进行连接
2. 同[ratel](https://github.com/ainilili/ratel)项目游戏规则
3. 支持快捷键（`ctrl` + ⬆️/⬇️）展示/关闭游戏页面

### Roadmap

- 更友善的页面
  - 使用`css`优化页面显示
- 自定义配置，定制用户页面
  - 自定义嵌入页面，不仅仅是百度
  - 显示/隐藏 快捷键设置
  - 背景，字体自定义
- 用户聊天

### Contribution

- 如果你有发现什么问题请提`ISSUE`
- 如果你有好的想法，欢迎提供`PR`
