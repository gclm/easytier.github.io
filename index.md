---
# https://vitepress.dev/reference/default-theme-home-page
layout: home

hero:
  name: EasyTier
  text: 由 Rust 和 Tokio 驱动
  tagline: 一个简单、安全、去中心化的内网穿透 VPN 组网方案
  actions:
    - theme: brand
      text: 快速开始
      link: /guide/introduction
    - theme: alt
      text: 在 Github 上查看
      link: https://github.com/EasyTier/EasyTier
    - theme: alt
      text: 协助改进或翻译文档
      link: https://github.com/EasyTier/easytier.github.io
    - theme: alt
      text: 参与开发
      link: https://github.com/EasyTier/EasyTier/issues

features:
  - title: 去中心化
    details: 无需依赖中心化服务，节点平等且独立。
  - title: 安全
    details: 支持利用 WireGuard 加密通信，也支持 AES-GCM 加密保护中转流量。
  - title: 高性能
    details: 全链路零拷贝，性能与主流组网软件相当。
  - title: 无公网 IP 组网
    details: 支持利用共享的公网节点组网，可参考配置指南
  - title: NAT 穿透
    details: 支持基于 UDP 的 NAT 穿透，即使在复杂的网络环境下也能建立稳定的连接。
  - title: 子网代理（点对网）
    details: 节点可以将可访问的网段作为代理暴露给 VPN 子网，允许其他节点通过该节点访问这些子网。
  - title: 智能路由
    details: 根据流量智能选择链路，减少延迟，提高吞吐量。
  - title: 跨平台
    details: |
      支持 MacOS/Linux/Windows/FreeBSD/Android 等系统。未来将支持 IOS。
      </br>
      支持 MIPS、ARM 等硬件架构。
      </br>
      可执行文件静态链接，部署简单。
  - title: GUI 支持
    details: 可通过图形界面使用，方便快捷。
---
