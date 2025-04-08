# 前言
鉴于部分用户的需求，我们开发了`Pro付费版本`

您当前正在浏览的页面为`git开源免费版`，继续往下翻可以看到`git开源免费版`所拥有的接口和事件

`Pro付费版本`所拥有的接口和事件请前往[官网](https://qxpro.apifox.cn/)查看

| 比较项    | git开源免费版                                                                                                                  | Pro付费版本     |
|--------|---------------------------------------------------------------------------------------------------------------------------|-------------|
| 官网     | gitee码云 https://gitee.com/daenmax/pc-wechat-hook-http-api/<br/>github https://github.com/daenmax/pc-wechat-hook-http-api/ | https://qxpro.apifox.cn/          |
| 开发文档   | 一次性收费200                                                                                                                  | 免费          |
| 官方交流社群 | ❌无                                                                                                                        | ✅有          |
| 微信版本更新迭代 | ❌滞后                                                                                                                       | ✅积极更新       |
| API接口数量 | ❌少                                                                                                                        | ✅多，丰富       |
| 回调事件数量 | ❌少                                                                                                                        | ✅多，丰富       |
| 防封逻辑   | ✅一般                                                                                                                       | ✅深度防检测      |
| HTTP   | ✅有                                                                                                                        | ✅有 |
| WebSocket | ❌只有正向                                                                                                                     | ✅正向、反向、更多功能 |
| 框架emoji显示 | ❌不支持                                                                                                                      | ✅全面支持       |
| 自动重登   | ❌不支持                                                                                                                      | ✅支持         |
| 技术支持   | ❌无                                                                                                                        | ✅有          |
| 疑问解答   | ❌无                                                                                                                        | ✅有          |


# git开源免费版

免费开源的微信HOOK和框架，提供HTTPAPI接口和封装好的框架。

内置HTTPAPI、WebSocket，方便您使用自己喜欢的编程语言快速开发。

支持version方式注入，更方便快捷。支持文本代码，多人艾特，emoji表情，微信表情等，全面解决收发消息、昵称内的emoji表情等特殊字符显示问题。


## 🎉 支持的微信版本

[3.9.10.16](https://gitee.com/daenmax/pc-wechat-hook-http-api/tree/391016/)（当前分支）

[3.9.9.34](https://gitee.com/daenmax/pc-wechat-hook-http-api/tree/39934/)

[3.6.0.18](https://gitee.com/daenmax/pc-wechat-hook-http-api/tree/36018/)

## 🎉 快速开始

### 1.安装指定版本微信

微信安装包下载
https://pan.baidu.com/s/1dQJd7wpkAPCd-rRU7vG4nA?pwd=aicz

### 2.使用千寻微信框架

1. 启动框架
   双击千寻微信框架.exe运行
2. 设置框架

   (1) 点击框架设置，在微信设置分组中，设置好微信安装目录和数据缓存目录，如果不会设置，请将鼠标箭头移动到蓝色问号image.png上查看提示即可

   (2) 在HOOK设置分组中，选择你使用的PC微信版本

   (3) 点击保存修改按钮
3. 添加微信
   点击微信管理，右键鼠标添加微信，随机端口或者指定端口，然后登录微信即可
4. 开始开发

   (1) 自己使用易语言SDK开发插件或者使用别人分享的插件，在插件管理右键添加

   (2) 使用HTTP API或者WebSocket接入开发

### 3.不使用千寻微信框架，而是直接使用DLL（进阶）

请参见`开发文档`内的讲解和教程

## 🎉 接口文档（开发文档）

![](https://img.cdn.apipost.cn/client/user/0/avatar/748dd95d0520f728a75156a010ed837867cd0376913ed.png)


开发文档中包括 千寻微信框架、DaenWxHook的完整开发HTTP、WebSocket接口文档、包含注入器教程、version注入教程

文档是在线的，更新后，你F5刷新页面即可看到。

需要开发文档请联系Daen QQ1330166564

**🔖 开发文档一次性收费200元，QQ好友列表3000满了上限了，请您确认要购买再加我好友，精力有限，仅向购买了开发文档的客户提供技术支持**

## 🎉 实现

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

## 🎉 预览

截图是旧版本截图，仅供预览，
![](https://img.cdn.apipost.cn/client/user/0/avatar/748dd95d0520f728a75156a010ed8378667f6d0c60e76.png)
![](https://img.cdn.apipost.cn/client/user/0/avatar/748dd95d0520f728a75156a010ed8378667f6d16d339b.png)
![](https://img.cdn.apipost.cn/client/user/0/avatar/748dd95d0520f728a75156a010ed8378667f71d265bda.png)
![](https://img.cdn.apipost.cn/client/user/0/avatar/748dd95d0520f728a75156a010ed8378667f6d223089c.png)
