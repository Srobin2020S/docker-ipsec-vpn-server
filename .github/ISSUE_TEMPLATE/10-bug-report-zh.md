---
name: 错误报告
about: 请使用这个模板来提交 bug
title: ''
labels: ''
assignees: ''

---

**任务列表**

- [ ] 我已阅读 [自述文件](https://github.com/hwdsl2/docker-ipsec-vpn-server/blob/master/README-zh.md)
- [ ] 我已阅读 [重要提示](https://github.com/hwdsl2/docker-ipsec-vpn-server/blob/master/README-zh.md#重要提示)
- [ ] 我已按照说明 [配置 VPN 客户端](https://github.com/hwdsl2/docker-ipsec-vpn-server/blob/master/README-zh.md#下一步)
- [ ] 我检查了 [IKEv1 故障排除](https://github.com/hwdsl2/setup-ipsec-vpn/blob/master/docs/clients-zh.md#ikev1-故障排除)，[IKEv2 故障排除](https://github.com/hwdsl2/setup-ipsec-vpn/blob/master/docs/ikev2-howto-zh.md#ikev2-故障排除)，[启用日志](https://github.com/hwdsl2/docker-ipsec-vpn-server/blob/master/docs/advanced-usage-zh.md#启用-libreswan-日志) 并查看了 [VPN 状态](https://github.com/hwdsl2/setup-ipsec-vpn/blob/master/docs/clients-zh.md#检查日志及-vpn-状态)
- [ ] 我搜索了已有的 [Issues](https://github.com/hwdsl2/docker-ipsec-vpn-server/issues?q=is%3Aissue)
- [ ] 这个 bug 是关于 IPsec VPN 服务器 Docker 镜像，而不是 IPsec VPN 本身

<!---
如果你发现了 IPsec VPN 的一个可重复的程序漏洞，请在 https://github.com/libreswan/libreswan 提交一个错误报告。VPN 的相关问题可在 [Libreswan](https://lists.libreswan.org) 或 [strongSwan](https://lists.strongswan.org) 用户邮件列表提问，或者搜索比如 [Stack Overflow](https://stackoverflow.com/questions/tagged/vpn) 等网站。
--->

**问题描述**
使用清楚简明的语言描述这个 bug。

**重现步骤**
重现该 bug 的步骤：

1. ...
2. ...

**期待的正确结果**
简要地描述你期望的正确结果。

**日志**
[启用日志](https://github.com/hwdsl2/docker-ipsec-vpn-server/blob/master/docs/advanced-usage-zh.md#启用-libreswan-日志)，检查 [VPN 状态](https://github.com/hwdsl2/setup-ipsec-vpn/blob/master/docs/clients-zh.md#检查日志及-vpn-状态)，并且添加错误日志以帮助解释该问题（如果适用）。

**服务器信息（请填写以下信息）**
- Docker 主机操作系统: [比如 Ubuntu 24.04]
- 服务提供商（如果适用）: [比如 GCP, AWS]

**客户端信息（请填写以下信息）**
- 设备: [比如 iPhone 12]
- 操作系统: [比如 iOS 15]
- VPN 模式: [IPsec/L2TP, IPsec/XAuth ("Cisco IPsec") 或 IKEv2]

**其它信息**
添加关于该 bug 的其它信息。
