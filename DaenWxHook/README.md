## 使用说明

> DaenWxHook.dll完全免费，请勿用于违法用途，

如果你不会注入本DLL到微信中，可以使用我们提供的注入器，也可以使用千寻微信框架，见【千寻微信框架】章节。

`注意，从2022年7月7日起，DaenWxHook.dll将不再内置HPSocket4C.dll依赖。`
`所以你需要在注入之前，将HPSocket4C.dll放到对应微信目录下。`
`例如
‪D:\Program Files (x86)\Tencent\WeChat[3.9.9.34]\HPSocket4C.dll`


## 微信版本

PC 3.9.9.34
`如果你已经安装了其他版本，不用卸载，直接下载3.9.9.34的安装包，覆盖更新即可，聊天记录不会丢失`
官方群文件内可以下载

## 下载地址
`DaenWxHook.dll、Daen注入器、HPSocket4C.dll`
https://gitee.com/daenmax/pc-wechat-hook-http-api

## 监听端口

HOOK启动后，监听的是0.0.0.0，即如果你的机器有公网，那么支持公网直接访问。
路由为：/DaenWxHook/client/

## 注入

你有`3`种注入方式，在注入之前，你首先需要学习一下配置参数
配置参数是一段json，里面包含了以下参数

1.使用千寻微信框架

2.使用version劫持注入

3.使用Daen微信注入器

详细参数和教程请参考开发文档