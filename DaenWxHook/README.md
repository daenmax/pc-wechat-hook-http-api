# DaenWxHook

## 使用说明

> DaenWxHook.dll完全免费，请勿用于违法用途，

如果你不会注入本DLL到微信中，可以使用我们提供的注入器，也可以使用千寻微信框架，见【千寻微信框架】目录。

`注意，从2022年7月7日起，DaenWxHook.dll将不再内置HPSocket4C.dll依赖。`
`所以你需要在注入之前，将HPSocket4C.dll放到对应微信目录下。`
`例如
‪D:\Program Files (x86)\Tencent\WeChat[3.6.0.18]\HPSocket4C.dll`

## 微信版本

PC 3.6.0.18
`如果你已经安装了其他版本，不用卸载，直接下载3.6.0.18的安装包，覆盖更新即可，聊天记录不会丢失`

## 实现

### 事件

- [x] 收到群聊消息
- [x] 收到私聊消息
- [x] 自己发出消息
- [x] 转账事件
- [x] 撤回事件
- [x] 好友请求
- [x] 群聊邀请
- [x] 支付事件

### 接口

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


## 监听端口

HOOK启动后，监听的是0.0.0.0，即如果你的机器有公网，那么支持公网直接访问。
路由为：/DaenWxHook/client/

## 进程启动参数

在注入时，提供以下参数可选，每个参数非必填，仅供自定义使用，因为不填写的话，也不影响使用，因为每个参数都有默认值
每个参数之间用&分隔开
具体可配置的参数如下

#### callBackUrl

> 微信收到事件将推送到你的服务地址上，POST方式，详情见【回调事件】章节
> 如果不填，那将不会做任何推送

#### port

> 此目录下微信Hook使用的TCP端口
> 默认值为8055
> 启动两个及以上时，务必传此参数，否则将会发生端口被占用导致启动失败

#### imgData

> 收到微信图片的保存文件夹，最后要带斜杠
> 默认值为C:\Users\xxx\Documents\DaenWxHookImg即位于 我的文档 中的DaenWxHookImg文件夹

#### timeOut

> 图片下载超时时间，单位毫秒，因为解密图片需要先下载好图片才可以进行解密
> 默认值为5000

#### autoLogin

> 是否自动点击 登录/进入微信 按钮，实验性功能
> 1=开启，0=不开启
> 默认值为0

#### wxData

> 微信的数据目录，最后要带斜杠，在设置中可以看到
> 不用管输入框里是多少，我这里改过，跟默认的不一样
> ![image.png](https://api.apifox.cn/api/v1/projects/1222856/resources/348160/image-preview)
> 直接点击"打开文件夹"，会弹出文件夹，复制地址栏
![image.png](https://api.apifox.cn/api/v1/projects/1222856/resources/348159/image-preview)
D:\Program Files\微信数据\WeChat Files\wxid_3sq4tklb6c3121
我们只需要填写"WeChat Files"前面的部分，即
> 那我就需要填写为D:\Program Files\微信数据\

#### flag

> 自定义标识，无特殊含义


#### tcp

> 建议留空，如果不为空，那么将尝试连接TCP，并发送自身port

### 示例

`callBackUrl=http://localhost:8089/wechat/&port=8055&imgData=C:\Users\xxx\Documents\DaenWxHookImg&timeOut=5000&autoLogin=0&wxData=D:\Program Files\微信数据&flag=ABCD`