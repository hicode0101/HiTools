<div align="center">

# 🧰 HiTools

**Hi 系列工具 · 专为白帽师傅们打造！**

一系列面向白帽安全研究的实战工具合集，覆盖代理配置、DNSLog、目录扫描、AI 自动化渗透与代码编辑，贴近实战、开箱即用。

[![License](https://img.shields.io/badge/License-MIT-2EA043?logo=opensourceinitiative&logoColor=white)](LICENSE)
[![Website](https://img.shields.io/badge/%E5%AE%98%E7%BD%91-tools.hicode.top-1F6FEB?logo=googlechrome&logoColor=white)](https://tools.hicode.top)
[![WeChat](https://img.shields.io/badge/%E5%BE%AE%E4%BF%A1-hicode0101-07C160?logo=wechat&logoColor=white)](#-联系作者)

</div>

---

## 📦 工具一览

| 工具 | 类型 | 简介 |
|:---|:---|:---|
| [🛡️ **HiProxy**](https://github.com/hicode0101/HiProxy) | Chrome 插件 | 适用于所有 Chrome 内核浏览器的代理设置插件 |
| [🔌 **HiLocalProxy**](https://github.com/hicode0101/HiLocalProxy) | 本地代理 | 带用户名密码的代理 → 本地免认证代理 |
| [🖥️ **HiProxyServer**](https://github.com/hicode0101/HiLocalProxy) | 代理服务端 | 自建 HTTP / SOCKS5 代理服务器 |
| [🌐 **HiDnsLog**](https://github.com/hicode0101/HiDnsLog-Release/releases) | DNSLog 平台 | 可私有化部署，支持重绑定与 SSRF 绕过 |
| [📂 **HiDir**](https://github.com/hicode0101/HiDir) | 目录扫描 | Go 实现的类 dirsearch 目录扫描工具 |
| [🤖 **HiSecAgent**](https://github.com/hicode0101/HiSecAgent) | AI 安全智能体 | AI 驱动的自动化渗透测试与漏洞评估平台 |
| [✏️ **HiEditor**](https://github.com/hicode0101/HiEditor) | 代码编辑器 | 轻量、快速、插件化的跨平台编辑器 |
| [🚀 **HiEditor Pro**](https://github.com/hicode0101/HiEditorPro) | 大文件编辑器 | 对标 EmEditor，GB 级文件毫秒级打开 |

---

## 🛡️ HiProxy — Chrome 代理设置插件

> 让每个 Chrome 内核浏览器都拥有顺手好用的代理管理。

- 🌍 适用于**所有 Chrome 内核浏览器**
- 🧩 基于谷歌扩展规范 **MV3** 开发
- 📤 支持**代理配置数据导入导出**，方便师傅们分享自己的 ByPassHost 设置

[![GitHub](https://img.shields.io/badge/%F0%9F%9B%A0%EF%B8%8F_%E8%8E%B7%E5%8F%96%E5%B7%A5%E5%85%B7-GitHub%E4%BB%93%E5%BA%93-0969DA?logo=github&logoColor=white)](https://github.com/hicode0101/HiProxy)

---

## 🔌 HiLocalProxy — 本地代理

> 带认证的代理，一键变为本地免认证代理。

- 🔐 将需要**用户名密码验证**的代理，转换为**无用户名密码**的代理
- 💻 在本地直接使用，无需再处理繁琐的认证环节

[![GitHub](https://img.shields.io/badge/%F0%9F%9B%A0%EF%B8%8F_%E8%8E%B7%E5%8F%96%E5%B7%A5%E5%85%B7-GitHub%E4%BB%93%E5%BA%93-0969DA?logo=github&logoColor=white)](https://github.com/hicode0101/HiLocalProxy)

---

## 🖥️ HiProxyServer — 代理服务器

> 几分钟架起一台属于自己的代理服务器。

- 🌐 支持 **HTTP** 和 **SOCKS5** 两种代理协议
- 🔑 可自由选择**有密码**或**无密码**方式提供服务
- 📦 与 HiLocalProxy 共用一个仓库，源码在不同目录下

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

> Go 语言打造的目录扫描利器，快速发现网站隐藏路径。

- ⚙️ 使用 **Go 语言**实现，类似 dirsearch
- 🕵️ 通过**字典暴力破解**的方式，快速扫描目标网站
- 🔎 高效找出可能存在的**隐藏文件、敏感文件和目录**

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

> 轻量、快速、插件化，简洁的记事本风格。

- 🪶 **轻量、快速**，简洁的记事本风格界面
- 🌈 内置 **15 门语言语法高亮**与 **JSON / XML 格式化**
- 🧩 原生 **C ABI 插件体系**，跨平台可用

[![GitHub](https://img.shields.io/badge/%F0%9F%9B%A0%EF%B8%8F_%E8%8E%B7%E5%8F%96%E5%B7%A5%E5%85%B7-GitHub%E4%BB%93%E5%BA%93-0969DA?logo=github&logoColor=white)](https://github.com/hicode0101/HiEditor)

---

## 🚀 HiEditor Pro — Windows 大文件编辑器

> 对标 EmEditor，让 GB 级大文件的编辑像打开记事本一样轻松。

- 🪟 专为 **Windows** 打造的大文件文本编辑器
- ⚡ **GB 级文件毫秒级打开**，告别漫长加载等待
- 🔍 **全文件搜索秒级完成**，大海捞针只在瞬息之间

[![GitHub](https://img.shields.io/badge/%F0%9F%9B%A0%EF%B8%8F_%E8%8E%B7%E5%8F%96%E5%B7%A5%E5%85%B7-GitHub%E4%BB%93%E5%BA%93-0969DA?logo=github&logoColor=white)](https://github.com/hicode0101/HiEditorPro)

---

> 🚧 **更多工具持续孵化中**，将不定期公布在本页面，欢迎 Star 关注 ⭐

---

## ⚠️ 作者申明

> 本系列工具软件**仅供白帽子安全研究和技术交流使用，禁止用于商业用途**。

## 💬 联系作者

- 👨‍💻 白帽昵称：**犀利的远哥**
- ✉️ 微信：`hicode0101`
- 💞 微信公众号：**远哥说安全**

遇到问题请随时联系我，我会及时回复；对工具功能有新的想法和需求，也请告知我，我非常乐意尝试满足。

<div align="center">

| 📱 我的微信 | 📢 微信公众号 |
|:---:|:---:|
| <img src="images/weixin.png" width="200" /> | <img src="images/gzh.png" width="280" /> |

</div>

---

<div align="center">

**HiTools** ✦ Made with ❤️ by [hicode0101](https://github.com/hicode0101)

</div>
