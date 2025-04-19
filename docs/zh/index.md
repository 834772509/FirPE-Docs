---
# 官方文档相关配置：https://vitepress.dev/reference/default-theme-layout
layout: home
home: true

# 官方文档相关配置：https://vitepress.dev/reference/default-theme-home-page
lang: zh-CN
title: FirPE
titleTemplate: 官方帮助文档
editLink: true
lastUpdated: true

# 指定要为当前页面注入的额外头标签。将附加在站点级配置注入的头标签之后
head:
  - - meta
    - name: description
      content: FirPE、WinPE
  - - meta
    - name: keywords
      content: FirPE、WinPE

hero:
  name: "FirPE"
  text: "第三方 WinPE"
  tagline: "也许是最适合年轻人使用的第三方 WinPE 🎉"
  image: # text 和 tagline 区域旁的图片
    src: /logo.svg
    alt: "FirPE"
  # 按钮相关
  actions:
    - theme: brand
      text: "🏠首页"
      link: "/"
    - theme: alt
      text: "🚀快速开始"
      link: "/guide/quickstart/"

# 按钮下方的描述
features:
  - icon: ⚙️
    title: "双内核适配"
    details: "集成 Win11PE 与 Win03PE 双内核，全面覆盖新旧硬件平台，支持 UEFI/Legacy 双启动模式。"
  - icon: 🧰
    title: "系统安装与维护"
    details: "支持系统安装、备份、恢复和维护等功能，能够显著提高系统安装效率。"
  - icon: 💾
    title: "全能启动盘制作"
    details: "支持双分区/三分区/Ventoy 多种模式制作，智能识别U盘状态，失败自动还原空间，兼容新旧主板启动。"
  - icon: 🌐
    title: "全场景网络支持"
    details: "支持有线/无线网络，集成大量网卡驱动，支持 SMB 共享连接、IP 固定配置等高级功能。"
  - icon: 🎨
    title: "深度个性化定制"
    details: "支持壁纸/LOGO 替换、分辨率调节、任务栏布局修改，提供 20+ 项可视化配置参数。"
  - icon: 🧪
    title: "开放插件生态"
    details: "无缝兼容 Edgeless/HotPE 插件体系，可扩展维护环境、办公组件等 200+ 工具。"
  - icon: 📜
    title: "自动化运维方案"
    details: "通过生命周期钩子脚本实现静默装机、批量部署、远程维护等企业级操作。"
  - icon: 🛡️
    title: "安全纯净保障"
    details: "零广告零捆绑，通过 MPL 2.0 协议开源验证，工具链规避主流杀软误报。"
---
