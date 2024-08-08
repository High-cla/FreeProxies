# FreeProxies
永久免费翻墙/科学上网，节点每10分钟自动更新，仅保留可用节点。订阅链接可一键导入，无需频繁更换。如果觉得有帮助，请点个星星支持一下。为了防止链接丢失，建议fork到自己的仓库。

## 订阅链接&加时卡
当前最新公共订阅链接为（每日21点30分更新第二天的链接）：
```
https://blue2sea.com/clash/f32c5d2f9e27e43b2f873bb23cde62ff
```
当前最新加时卡代码为（每30分钟更新1次）：
```
8cbba
```

为防止恶意使用，影响大家使用。公共节点，只是作为一个入口，需要每天更换。
## 使用说明
1.下载代理工具clash,关于下载地址和下载、下载使用说明参考
https://blue2sea.com/order/querySubscriptionLink/%20


2.复制公共订阅链接放到浏览器打开，在其页面中找到“个人订阅”，以生成属于自己的订阅链接。这样做，方便省去后续更换订阅链接的烦恼。当然，如果你不嫌麻烦，你也可以直接每天手动更换链接使用公共订阅链接。

3.将属于自己的订阅链接粘贴到clash进导入，即可正常使用。

4.每天使用免费领取加时卡代码进行加时（加时见上节），实现永久免费翻墙/科学上网。

5.欢迎分享你发现的公开节点，我们会对其进行测速并考虑将其添加到订阅服务中。[前往>](https://github.com/bq2015/FreeProxies/issues/1)

## 基本实现原理
1.从网络获取公开任意协议（torjan、ssh、vless、vmess）节点并转化成clash类型代理数据，然后加入数据库存档。

2.定时从数据库提取节点，通过clashspeedtest进行测速，剔除已失效的节点。

3.开启订阅链接服务，获取可用节点。

## 一些注意事项
使用过程请遵纪守法，建议仅用于学习和研究，一切风险自行承担。
