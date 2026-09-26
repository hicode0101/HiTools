<div align="center">

# 🧰 HiTools

**Hi Series Tools · Built for White-Hat Security Researchers!**

A collection of battle-tested tools for white-hat security research — proxy configuration, DNSLog, directory scanning, AI-driven pentest automation, code editing, and SSH terminal.

[![License](https://img.shields.io/badge/License-MIT-2EA043?logo=opensourceinitiative&logoColor=white)](LICENSE)
[![Website](https://img.shields.io/badge/Website-tools.hicode.top-1F6FEB?logo=googlechrome&logoColor=white)](https://tools.hicode.top)
[![WeChat](https://img.shields.io/badge/WeChat-hicode0101-07C160?logo=wechat&logoColor=white)](#-contact)

[中文](README.md) ✦ English

</div>

---

## 📦 Toolkit

| Tool | Type | Description |
|:---|:---|:---|
| [🛡️ **HiProxy**](https://github.com/hicode0101/HiProxy) | Chrome Extension | Proxy switcher for all Chromium-based browsers |
| [🎭 **HiModify**](https://github.com/hicode0101/HiModify) | Chrome Extension | Request header modifier & API mocker (MV3) |
| [🔌 **HiLocalProxy**](https://github.com/hicode0101/HiLocalProxy) | Local Proxy | Authenticated proxy → credential-free local proxy |
| [🌐 **HiDnsLog**](https://github.com/hicode0101/HiDnsLog-Release/releases) | DNSLog Platform | Self-hostable, with rebinding & SSRF bypass |
| [📂 **HiDir**](https://github.com/hicode0101/HiDir) | Directory Scanner | dirsearch-like directory scanner in Go |
| [🤖 **HiSecAgent**](https://github.com/hicode0101/HiSecAgent) | AI Security Agent | AI-driven automated pentest & vulnerability assessment |
| [✏️ **HiEditor**](https://github.com/hicode0101/HiEditor) | Code Editor | Lightweight, fast, plugin-based, cross-platform |
| [🚀 **HiEditor Pro**](https://github.com/hicode0101/HiEditorPro-Release) | Large-File Editor | EmEditor-class for Windows; opens GB-scale files in milliseconds |
| [🖥️ **HiShell**](https://github.com/hicode0101/HiShell-Release/releases) | SSH Terminal | Cross-platform SSH terminal & SFTP manager — a great Xshell / Tabby alternative |

---

## 🛡️ HiProxy — Chrome Proxy Switcher

> Handy proxy management for every Chromium-based browser.

- 🌍 Works with **all Chromium-based browsers**
- 🧩 Built on Chrome's **MV3** extension standard
- 📤 **Import / export** proxy profiles — share your ByPassHost settings with ease

[![GitHub](https://img.shields.io/badge/%F0%9F%9B%A0%EF%B8%8F_Get_the_Tool-GitHub_Repo-0969DA?logo=github&logoColor=white)](https://github.com/hicode0101/HiProxy)

---

## 🎭 HiModify — Request Modifier & API Mock

> Rewrite headers and mock API responses — full control at your fingertips.

- 🧩 Built on Chrome's **MV3** extension standard, works with all Chromium-based browsers
- 📝 **Add, override, append or delete** request / response headers by domain / URL rules, each rule independently toggleable
- 🎭 Intercept XHR / Fetch and return custom status codes, bodies and delays for **API mocking / replay**, with real-traffic recording
- 📤 **JSON import / export** of all rules for backup and team sharing

[![GitHub](https://img.shields.io/badge/%F0%9F%9B%A0%EF%B8%8F_Get_the_Tool-GitHub_Repo-0969DA?logo=github&logoColor=white)](https://github.com/hicode0101/HiModify)

---

## 🔌 HiLocalProxy — Local Proxy

> Turn an authenticated proxy into a credential-free local one.

- 🔐 Converts a proxy requiring **username / password auth** into a **credential-free** proxy
- 💻 Use it locally without the hassle of authentication

[![GitHub](https://img.shields.io/badge/%F0%9F%9B%A0%EF%B8%8F_Get_the_Tool-GitHub_Repo-0969DA?logo=github&logoColor=white)](https://github.com/hicode0101/HiLocalProxy)

---

## 🌐 HiDnsLog — DNSLog Platform

> A self-hostable DNSLog platform — every resolution under your control.

- 🔍 Query and manage DNS records; supports **private DNSLog deployment** on your own domain
- 🖥️ Full **DNS Server** features, returning records forwarded from other DNS servers
- 🔁 Automatic **secondary binding** of resolutions to bypass certain checks
- ⚡ **TTL = 0** — a must-have for white hats; almost no domain registrar supports it, so run your own
- 🎯 **A / CNAME rebinding** with configurable resolution order — no more massive random collisions
- 🧪 **SSRF redirect bypass**, compatible with **Burp Collaborator**

[![Release](https://img.shields.io/badge/%F0%9F%9B%A0%EF%B8%8F_Get_the_Tool-Binary_Download-F0883E?logo=github&logoColor=white)](https://github.com/hicode0101/HiDnsLog-Release/releases)

---

## 📂 HiDir — Directory Scanner

> A Go-powered directory scanner to uncover hidden paths fast.

- ⚙️ Implemented in **Go**, similar to dirsearch
- 🕵️ Dictionary-based brute forcing to scan target sites quickly
- 🔎 Efficiently surfaces **hidden files, sensitive files and directories**

[![GitHub](https://img.shields.io/badge/%F0%9F%9B%A0%EF%B8%8F_Get_the_Tool-GitHub_Repo-0969DA?logo=github&logoColor=white)](https://github.com/hicode0101/HiDir)

---

## 🤖 HiSecAgent — AI Security Agent

> AI-driven security automation for smarter penetration testing.

- 🧠 Composed of **HiCyberServer** and **HiCyberMCP**
- 🎯 Designed for **penetration testing, vulnerability assessment and security research**
- 🛠️ Written in **Go**, integrating multiple security tools and an **intelligent decision engine**
- 📊 Comprehensive security assessment and vulnerability discovery

[![GitHub](https://img.shields.io/badge/%F0%9F%9B%A0%EF%B8%8F_Get_the_Tool-GitHub_Repo-0969DA?logo=github&logoColor=white)](https://github.com/hicode0101/HiSecAgent)

---

## ✏️ HiEditor — Cross-Platform Text / Code Editor

> A single tool that meets all the editing and reading needs of a white-hat hacker for the entire day.

- 🪶 **Lightweight and fast**, with a minimalist notepad-style UI
- 🌈 Syntax highlighting for **15 languages** plus **JSON / XML formatting**
- 🔍 Supports Markdown editing and previewing, PDF reading, and other common formats.
- 🧩 Native **C ABI plugin system**, cross-platform

[![GitHub](https://img.shields.io/badge/%F0%9F%9B%A0%EF%B8%8F_Get_the_Tool-GitHub_Repo-0969DA?logo=github&logoColor=white)](https://github.com/hicode0101/HiEditor)

---

## 🚀 HiEditor Pro — Windows Large-File Editor

> EmEditor-class editing — open GB-scale files like a notepad.

- 🪟 A large-file text editor built exclusively for **Windows**
- ⚡ Opens **GB-scale files in milliseconds** — no more long waits
- 🔍 **Whole-file search in seconds** — finding a needle in a haystack, instantly

[![Release](https://img.shields.io/badge/%F0%9F%9B%A0%EF%B8%8F_Get_the_Tool-Binary_Download-F0883E?logo=github&logoColor=white)](https://github.com/hicode0101/HiEditorPro-Release/releases)

---

## 🖥️ HiShell — SSH Terminal

> An engineer-friendly SSH terminal — a perfect replacement for XShell and Tabby.

- 🖥️ Cross-platform, running on **Windows 10+ / macOS / Linux** desktops
- 🗂️ **Multi-tab SSH terminal** + **SFTP file manager**, with a dual-pane view and transfer queue showing progress, speed and ETA
- 🔑 Built-in **key management** — generate and import/export **RSA / ECDSA / ED25519** keys (incl. **PuTTY ppk** format)
- 🔀 **Local / remote / dynamic (SOCKS5)** SSH port forwarding
- 🌍 **Chinese & English** UI, with a session manager supporting drag-to-sort, duplication and quick connect

[![Release](https://img.shields.io/badge/%F0%9F%9B%A0%EF%B8%8F_Get_the_Tool-Binary_Download-F0883E?logo=github&logoColor=white)](https://github.com/hicode0101/HiShell-Release/releases)

---

> 🚧 **More tools are in the incubator** and will be published here from time to time. Star to stay tuned ⭐

---

## ⚠️ Disclaimer

> All tools in this series are **for white-hat security research and technical exchange only. Commercial use is prohibited.**

## 💬 Contact

- 👨‍💻 White-hat alias: **犀利的远哥**
- ✉️ WeChat: `hicode0101`
- 💞 WeChat Official Account: **远哥说安全**

If you run into any issues with the tools, feel free to reach out — I reply promptly. Feature requests are more than welcome; I'd love to try making them happen.

<div align="center">

| 📱 WeChat | 📢 Official Account |
|:---:|:---:|
| <img src="images/weixin.png" width="200" /> | <img src="images/gzh.png" width="280" /> |

</div>

---

<div align="center">

**HiTools** ✦ Made with ❤️ by [hicode0101](https://github.com/hicode0101)

</div>
