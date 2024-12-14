# PC微信HookHttpApi

## 介绍
免费开源的微信HOOK和框架，提供HTTPAPI接口和封装好的框架，支持微信版本为`3.9.10.16`、`3.9.9.34`、`3.6.0.18`。内置HTTPAPI、WebSocket，方便您使用自己喜欢的编程语言快速开发。
支持versioin方式注入，更方便快捷。支持文本代码，多人艾特，emoji表情，微信表情等，全面解决收发消息、昵称内的emoji表情等特殊字符显示问题。

## 支持微信版本选择
[3.9.10.16](https://gitee.com/daenmax/pc-wechat-hook-http-api/tree/391016/)（当前分支）

[3.9.9.34](https://gitee.com/daenmax/pc-wechat-hook-http-api/tree/39934/)

[3.6.0.18](https://gitee.com/daenmax/pc-wechat-hook-http-api/tree/36018/)

## 使用说明

本文档旨在让您更方便的学习和使用DaenWxHook和千寻微信框架
您可以使用原生的`DaenWxHook`，也可以使用封装过的`千寻微信框架`

一般来说，您只需要使用其中一个即可。

`各自的使用文档请进入相应的目录查看Readme.md`

## 区别

`DaenWxHook`是DLL，可以直接注入到微信中，提供HTTPAPI接口，不同的语言，难点在于注入的方式，而且每个微信都必须使用不同的端口，不方便管理和调用，所以特别提供了千寻微信框架。

`千寻微信框架`是基于DaenWxHook开发的（当然您也可以自己开发一个框架），集中管理所有的微信，二次封装了DaenWxHook的HTTPAPI接口，提供WebSocket，您只需要调用千寻微信框架提供的HTTPAPI、WebSocket接口，即可实现控制所有的微信。


## 接口文档

![](https://img.cdn.apipost.cn/client/user/0/avatar/748dd95d0520f728a75156a010ed8378667f6b977c2d7.png)

开发文档中包括 千寻微信框架、DaenWxHook的完整开发HTTP、WebSocket接口文档、包含注入器教程、version注入教程

文档是在线的，更新后，你F5刷新页面即可看到。

需要开发文档请联系Daen QQ1330166564

（开发文档收费200元，QQ好友列表3000满了上限了，请您确认要购买再加我好友，精力有限，仅向购买了开发文档的客户提供技术支持）

（开发文档收费200元，QQ好友列表3000满了上限了，请您确认要购买再加我好友，精力有限，仅向购买了开发文档的客户提供技术支持）

（开发文档收费200元，QQ好友列表3000满了上限了，请您确认要购买再加我好友，精力有限，仅向购买了开发文档的客户提供技术支持）


## 微信安装包下载
https://pan.baidu.com/s/1dQJd7wpkAPCd-rRU7vG4nA?pwd=aicz

## 实现

### 事件

- [x] 账号变动事件
- [x] 收到群聊消息
- [x] 收到私聊消息
- [x] 自己发出消息
- [x] 转账事件
- [x] 好友请求
- [x] 支付事件
- [x] 注入成功

### 接口

- [x] 获取微信列表
- [x] 修改微信版本号
- [x] 获取登录状态
- [x] 获取登录二维码
- [x] 设置下载图片时间
- [x] 结束微信进程
- [x] 解密dat图片
- [x] 微信状态检测
- [x] 下载文件/图片
- [x] 发送文本消息
- [x] 发送图片
- [x] 发送文件
- [x] 发送动态表情
- [x] 获取个人信息
- [x] 获取好友列表
- [x] 获取群聊列表
- [x] 获取公众号列表
- [x] 删除好友
- [x] 修改对象备注
- [x] 查询对象信息
- [x] 查询群聊信息
- [x] 获取群成员列表
- [x] 获取群成员昵称


## 预览
截图是老图，仅供预览，
![](https://img.cdn.apipost.cn/client/user/0/avatar/748dd95d0520f728a75156a010ed8378667f6d0c60e76.png)
![](https://img.cdn.apipost.cn/client/user/0/avatar/748dd95d0520f728a75156a010ed8378667f6d16d339b.png)
![](https://img.cdn.apipost.cn/client/user/0/avatar/748dd95d0520f728a75156a010ed8378667f71d265bda.png)
![](https://img.cdn.apipost.cn/client/user/0/avatar/748dd95d0520f728a75156a010ed8378667f6d223089c.png)