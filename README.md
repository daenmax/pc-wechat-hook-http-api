# PC微信HookHttpApi

#### 介绍
免费的微信HOOK和框架，提供HTTPAPI接口和封装好的框架，微信版本为3.6.0.18


#### 使用说明

本文档旨在让您更方便的学习和使用DaenWxHook和千寻微信框架
您可以使用原生的`DaenWxHook`，也可以使用封装过的`千寻微信框架`

一般来说，您只需要使用其中一个即可。

#### 区别

DaenWxHook是DLL，可以直接注入到微信中，提供HTTPAPI接口，不同的语言，难点在于注入的方式，而且每个微信都必须使用不同的端口，不方便管理和调用，所以特别提供了千寻微信框架。

千寻微信框架是基于DaenWxHook开发的（当然您也可以自己开发一个框架），集中管理所有的微信，二次封装了DaenWxHook的HTTPAPI接口，您只需要调用千寻微信框架提供的HTTPAPI接口，即可实现控制所有的微信。

## 实现

### 事件

账号变动事件、收到群聊消息、收到私聊消息、自己发出消息、转账事件、撤回事件、好友请求、群聊邀请、支付事件等

### 接口
![image.png](https://api.apifox.cn/api/v1/projects/1222856/resources/347791/image-preview)

#### 交流
我的QQ：1330166564
QQ交流群：[62476489](https://jq.qq.com/?_wv=1027&k=h5u680to)
![image.png](https://api.apifox.cn/api/v1/projects/1222856/resources/347548/image-preview)