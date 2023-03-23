# PC微信HookHttpApi

## 介绍
免费开源的微信HOOK和框架，提供HTTPAPI接口和封装好的框架，微信版本为3.6.0.18，内置HTTPAPI，方便您使用自己喜欢的编程语言快速开发。
支持文本代码，多人艾特，emoji表情，微信表情等，全面解决收发消息、昵称内的emoji表情等特殊字符显示问题。

## 使用说明

本文档旨在让您更方便的学习和使用DaenWxHook和千寻微信框架
您可以使用原生的`DaenWxHook`，也可以使用封装过的`千寻微信框架`

一般来说，您只需要使用其中一个即可。

`各自的使用文档请进入相应的目录查看Readme.md`

## 区别

`DaenWxHook`是DLL，可以直接注入到微信中，提供HTTPAPI接口，不同的语言，难点在于注入的方式，而且每个微信都必须使用不同的端口，不方便管理和调用，所以特别提供了千寻微信框架。

`千寻微信框架`是基于DaenWxHook开发的（当然您也可以自己开发一个框架），集中管理所有的微信，二次封装了DaenWxHook的HTTPAPI接口，您只需要调用千寻微信框架提供的HTTPAPI接口，即可实现控制所有的微信。


## 接口文档
https://gitee.com/qxvxhook/pc-vx-hook-http-api/wikis/vxhook

## 3.6.0.18版本微信下载
https://www.123pan.com/s/HtlbVv-tAf93.html

## 实现

### 事件

- [x] 账号变动事件
- [x] 收到群聊消息
- [x] 收到私聊消息
- [x] 自己发出消息
- [x] 转账事件
- [x] 撤回事件
- [x] 好友请求
- [x] 群聊邀请
- [x] 支付事件

### 接口

- [x] 获取微信列表
- [x] 微信状态检测、
- [x] 发送文本消息
- [x] 修改下载图片
- [x] 获取个人信息
- [x] 查询对象信息
- [x] 获取好友列表
- [x] 获取群聊列表
- [x] 获取公众号列表
- [x] 获取群成员列表
- [x] 发送聊天记录
- [x] 发送本地图片
- [x] 发送本地文件
- [x] 发送分享链接
- [x] 发送小程序
- [x] 发送音乐分享
- [x] 发送XML
- [x] 发送名片
- [x] 确认收款
- [x] 同意好友请求
- [x] 添加好友_通过v3
- [x] 添加好友_通过wxid
- [x] 查询陌生人信息
- [x] 邀请进群
- [x] 删除好友
- [x] 修改对象备注
- [x] 修改群聊名称
- [x] 获取登录二维码
- [x] 访问图片
- [x] 下载文件


## 交流

QQ交流群：[62476489](https://jq.qq.com/?_wv=1027&k=h5u680to)

需要更多功能请查看文档https://www.showdoc.com.cn/ebaiwl

## 感谢

感谢Aixed的资料和指导

## 预览
![img](https://www.apifox.cn/api/v1/projects/467052/resources/348154/image-preview)
![输入图片说明](%E5%8D%83%E5%AF%BB%E6%A1%86%E6%9E%B6/2B80BC4E1D8AE642D64104ED21730034.jpg)
![img](https://www.apifox.cn/api/v1/projects/467052/resources/348156/image-preview)
![img](https://www.apifox.cn/api/v1/projects/467052/resources/348157/image-preview)
![img](https://www.apifox.cn/api/v1/projects/467052/resources/348158/image-preview)