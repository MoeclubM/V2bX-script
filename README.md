# V2bX
A V2board node server based on Sing-Box.

一个基于Sing-Box的V2board节点服务端，支持Vmess,Vless,Trojan,TUIC,Shadowsocks,AnyTLS,Hysteria,Naive协议

Find the source code here: [MoeclubM/V2bX](https://github.com/MoeclubM/V2bX)

当前脚本默认面向新版 Xboard `machine` API。

- 新版推荐配置：仅需 `ApiHost`、`ApiKey`、`MachineID`
- 节点参数、证书与 ECH 由面板在线下发
- 传统 Node 生成方式仅作为兼容入口保留
- 如需兼容旧版 API，可在生成配置时手动选择传统 Node

# 一键安装

```
wget -N https://raw.githubusercontent.com/MoeclubM/V2bX-script/master/install.sh && bash install.sh
```
