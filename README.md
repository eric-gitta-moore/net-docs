# net-docs
网络工具

> 梯子另说，这里主要是通用的网络工具

- [brook](https://github.com/txthinking/brook)
  - 虽然是梯子出生，但是全能网络工具（dns、socks、ws、quic）
  - 创建 UDP 支持的 socks5
  - testsock5 可以支持 UDP 检测
  - 全平台客户端支持 tun2socks
- [every proxy](https://play.google.com/store/apps/details?id=com.gorillasoftware.everyproxy&hl=en_US)
  - Android 提供 socks5
- [Android Proxy Server](https://play.google.com/store/apps/details?id=cn.adonet.proxyevery&hl=en_US)
  - Android 提供 socks5、ss
  - **重点 socks5 支持 udp**
- [tun2socks APP](https://play.google.com/store/apps/details?id=com.elseplus.tun2socks&hl=en_US)
  - 顾名思义
- [tun2proxy](https://github.com/tun2proxy/tun2proxy)
  - 全端 tun2socks5 or tun2http
- [curl-h3](https://gist.github.com/sinwoobang/c83af540a2df8b149a59007e5f5814ec)
  - curl quic 支持
  - 建议使用 [cloudflare](https://dev.to/gjrdiesel/installing-curl-with-http3-on-macos-2di2) 的 curl.rb
- v2rayNG | NekoBox
  - 开启 fake-ip + 全局模式之后 等同于 tun2socks
  - 可以替代 every proxy，[自定义配置](https://github.com/eric-gitta-moore/sub-diversion-rules/blob/main/src/sing-box/direct-socks.json)
- [DNS Changer for IPv4/IPv6](https://github.com/XTLS/Xray-core/issues/2280#issuecomment-1616774179)
  - 免 root 查看本机各个接口 DNS
  - https://play.google.com/store/apps/details?id=com.frostnerd.dnschanger&hl=en
  - https://apkpure.com/dnschanger-for-ipv4-ipv6/com.frostnerd.dnschanger
  - https://github.com/emtee40/dnschanger-frostnerd

## Troubleshooting

### Fake-ip
- [rfc3089 - 一种基于SOCKS的IPv6/IPv4网关机制](https://rfc2cn.com/rfc3089.html)
- [我有特别的 DNS 配置和使用技巧](https://blog.skk.moe/post/i-have-my-unique-dns-setup/)
