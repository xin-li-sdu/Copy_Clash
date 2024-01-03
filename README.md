![bonus](https://github.com/xin-li-sdu/SDU-rewards/assets/40687850/43e45c4a-a078-4aa5-b945-7b468f258dd9)


**这是已经跑路的clash的副本**

## 特点

- 本地HTTP/HTTPS/SOCKS服务器，支持身份验证
- 支持Shadowsocks(R)、VMess、Trojan、Snell、SOCKS5、HTTP(S)出站代理
- 内置的[fake-ip](https://www.rfc-editor.org/rfc/rfc3089) DNS服务器，旨在最小化DNS污染攻击的影响。支持DoH/DoT上游。
- 基于域名、GEOIP、IP-CIDR或进程名称的规则，将数据包路由到不同的目标
- 代理组允许用户实现强大的规则。支持自动回退、负载平衡或根据延迟自动选择代理
- 远程提供者，允许用户远程获取代理列表，而不是在配置文件中硬编码
- 透明代理：重定向TCP和TProxy TCP/UDP，并自动管理路由表/规则
- 通过全面的HTTP RESTful API控制器进行热重载


## 入门指南
文档可在[GitHub Wiki](https://github.com/Dreamacro/clash/wiki)上找到。

## 开发
如果您想构建一个使用Clash作为库的Go应用程序，请查看[GitHub Wiki](https://github.com/Dreamacro/clash/wiki/Using-Clash-in-your-Golang-program)。

## 许可证
此软件以GPL-3.0许可证发布。

[![FOSSA状态](https://app.fossa.io/api/projects/git%2Bgithub.com%2FDreamacro%2Fclash.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FDreamacro%2Fclash?ref=badge_large)
