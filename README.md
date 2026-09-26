<div align="center">

# 🧰 HiTools

**Hi 系列工具 · 工程师自己的工具！**

一系列面向工程师们的实战工具合集，覆盖代理配置、DNSLog、目录扫描、AI 自动化渗透、代码编辑与 SSH 终端。

[![License](https://img.shields.io/badge/License-MIT-2EA043?logo=opensourceinitiative&logoColor=white)](LICENSE)
[![Website](https://img.shields.io/badge/%E5%AE%98%E7%BD%91-tools.hicode.top-1F6FEB?logo=googlechrome&logoColor=white)](https://tools.hicode.top)
[![WeChat](https://img.shields.io/badge/%E5%BE%AE%E4%BF%A1-hicode0101-07C160?logo=wechat&logoColor=white)](#-联系作者)

中文 ✦ [English](README.en.md)

</div>

---

## 📦 工具一览

| 工具 | 类型 | 简介 |
|:---|:---|:---|
| [🛡️ **HiProxy**](https://github.com/hicode0101/HiProxy) | Chrome 插件 | 适用于所有 Chrome 内核浏览器的代理设置插件 |
| [🎭 **HiModify**](https://github.com/hicode0101/HiModify) | Chrome 插件 | 请求头修改与 API Mock 的 Chrome 扩展（MV3） |
| [🔌 **HiLocalProxy**](https://github.com/hicode0101/HiLocalProxy) | 本地代理 | 把需用户名密码的代理 → 转本地免密代理 |
| [🌐 **HiDnsLog**](https://github.com/hicode0101/HiDnsLog-Release) | DNSLog 平台 | 可私有化部署，支持重绑定与 SSRF 绕过 |
| [📂 **HiDir**](https://github.com/hicode0101/HiDir) | 目录扫描 | Go 实现的类 dirsearch 目录扫描工具 |
| [🤖 **HiSecAgent**](https://github.com/hicode0101/HiSecAgent) | AI 安全智能体 | AI 驱动的自动化渗透测试与漏洞评估平台 |
| [✏️ **HiEditor**](https://github.com/hicode0101/HiEditor) | 代码编辑器 | 轻量、快速、插件化的跨平台编辑器 |
| [🚀 **HiEditor Pro**](https://github.com/hicode0101/HiEditorPro-Release) | 大文件编辑器 | 对标 EmEditor，GB 级文件毫秒级打开 |
| [🖥️ **HiShell**](https://github.com/hicode0101/HiShell-Release) | SSH 终端 | 跨平台 SSH 终端与 SFTP 管理，完美替代 Xshell / Tabby |

---

## 🛡️ HiProxy — Chrome 代理设置插件

> 让每个 Chrome 内核浏览器都拥有顺手好用的代理管理。

- 🌍 适用于**所有 Chrome 内核浏览器**
- 🧩 基于谷歌扩展规范 **MV3** 开发
- 📤 支持**代理配置数据导入导出**，方便白帽子师傅们分享自己的 ByPassHost 设置

[![GitHub](https://img.shields.io/badge/%F0%9F%9B%A0%EF%B8%8F_%E8%8E%B7%E5%8F%96%E5%B7%A5%E5%85%B7-GitHub%E4%BB%93%E5%BA%93-0969DA?logo=github&logoColor=white)](https://github.com/hicode0101/HiProxy)

---

## 🎭 HiModify — 请求修改与 API Mock 插件

> 改写请求头、模拟接口响应，请求调试尽在指尖。

- 🧩 基于**谷歌扩展规范 MV3** 开发，适用于所有 Chrome 内核浏览器
- 📝 按域名 / URL 规则**增删改请求头与响应头**，规则可独立开关
- 🎭 拦截 XHR / Fetch 请求，自定义状态码、响应体与延迟，实现 **API Mock / 重放**，支持录制真实流量
- 📤 支持规则配置 **JSON 导入导出**，方便备份与团队共享

[![GitHub](https://img.shields.io/badge/%F0%9F%9B%A0%EF%B8%8F_%E8%8E%B7%E5%8F%96%E5%B7%A5%E5%85%B7-GitHub%E4%BB%93%E5%BA%93-0969DA?logo=github&logoColor=white)](https://github.com/hicode0101/HiModify)

---

## 🔌 HiLocalProxy — 本地代理

> 带认证的代理，一键变为本地免认证代理。

- 🔐 将需要**用户名密码验证**的代理，转换为**无用户名密码**的代理
- 💻 在本地直接使用，无需再处理繁琐的认证环节

[![GitHub](https://img.shields.io/badge/%F0%9F%9B%A0%EF%B8%8F_%E8%8E%B7%E5%8F%96%E5%B7%A5%E5%85%B7-GitHub%E4%BB%93%E5%BA%93-0969DA?logo=github&logoColor=white)](https://github.com/hicode0101/HiLocalProxy)

---

## 🌐 HiDnsLog — DNSLog 平台

> 可私有化部署的 DNSLog 平台，解析规则尽在掌控。

- 🔍 可查询、管理 DNS 解析记录，支持 **DNSLog 私有化部署**（使用自己的域名）
- 🖥️ 完整的 **DNS Server** 功能，支持自动从其它 DNS Server 返回解析记录
- 🔁 支持**域名解析自动二次绑定**，绕过一些检测
- ⚡ 支持 **TTL = 0** —— 白帽必备功能，几乎所有域名服务商都不支持，所以要用自己的
- 🎯 支持 **A 记录 / CNAME 记录重绑定**，并可指定重绑定的解析顺序，一切尽在掌控，无需大量随机碰撞
- 🧪 支持 **SSRF 跳转绕过**，兼容 **Burp Collaborator**

[![Release](https://img.shields.io/badge/%F0%9F%9B%A0%EF%B8%8F_%E8%8E%B7%E5%8F%96%E5%B7%A5%E5%85%B7-%E4%BA%8C%E8%BF%9B%E5%88%B6%E4%B8%8B%E8%BD%BD-F0883E?logo=github&logoColor=white)](https://github.com/hicode0101/HiDnsLog-Release/releases)

---

## 📂 HiDir — 目录扫描工具

> Go 语言打造的目录扫描利器，快速发现企业潜在安全问题。

- ⚙️ 使用 **Go 语言**实现，类似 dirsearch
- 🕵️ 通过多字典快速扫描目标网站，发现企业潜在的安全问题
- 🔎 帮企业高效找出可能泄漏的**隐藏文件、敏感文件和目录**

[![GitHub](https://img.shields.io/badge/%F0%9F%9B%A0%EF%B8%8F_%E8%8E%B7%E5%8F%96%E5%B7%A5%E5%85%B7-GitHub%E4%BB%93%E5%BA%93-0969DA?logo=github&logoColor=white)](https://github.com/hicode0101/HiDir)

---

## 🤖 HiSecAgent — AI 安全智能体

> AI 驱动的网络安全自动化工具，让渗透测试更智能。

- 🧠 由 **HiCyberServer** 和 **HiCyberMCP** 组成
- 🎯 专为**渗透测试、漏洞评估和安全研究**设计
- 🛠️ 采用 **Go 语言**实现，集成多个安全工具与**智能决策引擎**
- 📊 提供全面的安全评估和漏洞发现能力

[![GitHub](https://img.shields.io/badge/%F0%9F%9B%A0%EF%B8%8F_%E8%8E%B7%E5%8F%96%E5%B7%A5%E5%85%B7-GitHub%E4%BB%93%E5%BA%93-0969DA?logo=github&logoColor=white)](https://github.com/hicode0101/HiSecAgent)

---

## ✏️ HiEditor — 跨平台文本 / 代码编辑器

> 一个工具解决白帽师傅一天所有的编辑和阅读需求。

- 🪶 **轻量、快速**，简洁的记事本风格界面
- 🌈 内置 **15 门语言语法高亮**与 **JSON / XML 格式化**
- 🔍 支持Markdown编辑和预览、PDF阅读等常用格式
- 🧩 原生 **C ABI 插件体系**，跨平台可用

[![GitHub](https://img.shields.io/badge/%F0%9F%9B%A0%EF%B8%8F_%E8%8E%B7%E5%8F%96%E5%B7%A5%E5%85%B7-GitHub%E4%BB%93%E5%BA%93-0969DA?logo=github&logoColor=white)](https://github.com/hicode0101/HiEditor)

---

## 🚀 HiEditor Pro — Windows 大文件编辑器

> 对标 EmEditor，让 GB 级大文件的编辑像打开记事本一样轻松。

- 🪟 专为 **Windows** 打造的大文件文本编辑器
- ⚡ **GB 级文件毫秒级打开**，告别漫长加载等待
- 🔍 **全文件搜索秒级完成**，大海捞针只在瞬息之间

[![Release](https://img.shields.io/badge/%F0%9F%9B%A0%EF%B8%8F_%E8%8E%B7%E5%8F%96%E5%B7%A5%E5%85%B7-%E4%BA%8C%E8%BF%9B%E5%88%B6%E4%B8%8B%E8%BD%BD-F0883E?logo=github&logoColor=white)](https://github.com/hicode0101/HiEditorPro-Release/releases)

---

## 🖥️ HiShell — SSH 终端工具

> 一款工程师爱用的 SSH 终端，完美替代 XShell 和 Tabby。

- 🖥️ 支持 **Windows 10+ / macOS / Linux** 跨平台桌面环境
- 🗂️ **多标签 SSH 终端** + **SFTP 文件管理**，双栏视图与传输队列，传输进度 / 速度 / 剩余时间一目了然
- 🔑 内置**密钥管理**，支持生成与导入导出 **RSA / ECDSA / ED25519** 密钥（含 **PuTTY ppk** 格式）
- 🔀 支持**本地 / 远程 / 动态（SOCKS5）三种 SSH 端口转发**
- 🌍 界面支持**中英双语**，会话管理器可拖拽排序、复制与快速连接

[![Release](https://img.shields.io/badge/%F0%9F%9B%A0%EF%B8%8F_%E8%8E%B7%E5%8F%96%E5%B7%A5%E5%85%B7-%E4%BA%8C%E8%BF%9B%E5%88%B6%E4%B8%8B%E8%BD%BD-F0883E?logo=github&logoColor=white)](https://github.com/hicode0101/HiShell-Release/releases)

---

> 🚧 **更多工具持续孵化中**，将不定期公布在本页面，欢迎 Star 关注 ⭐

---

## ⚠️ 作者申明

> 本系列工具软件**仅供工程师们研究和技术交流使用，禁止用于商业用途**。

## 💬 联系作者

- 👨‍💻 昵称：**犀利的远哥**
- ✉️ 微信：`hicode0101`

遇到问题请随时联系我，我会及时回复；对工具功能有新的想法和需求，也请告知我，我非常乐意尝试满足。

<div align="center">

| 📱 我的微信 |
|:---:|
| <img src="images/weixin.png" width="200" /> |

</div>

---

<div align="center">

**HiTools** ✦ Made with ❤️ by [hicode0101](https://github.com/hicode0101)

</div>
