<div align="center">

# PTPHAP · WebTS

### `自托管语音 / 真实身份 / 开源开发`

<img src="https://raw.githubusercontent.com/PTPHAP/PTPHAP/main/assets/observatory.svg" alt="PTPHAP · WebTS" width="100%" />

[![WebTS](https://img.shields.io/badge/WebTS-Open%20Source-38bdf8?style=flat-square&logo=webrtc&logoColor=white)](https://github.com/PTPHAP/WebTS)
[![Rust](https://img.shields.io/badge/Rust-Backend-e8795a?style=flat-square&logo=rust)](https://github.com/PTPHAP/WebTS/tree/main/server)
[![TypeScript](https://img.shields.io/badge/TypeScript-Frontend-3178c6?style=flat-square&logo=typescript&logoColor=white)](https://github.com/PTPHAP/WebTS/tree/main/web)
[![MIT](https://img.shields.io/badge/License-MIT-a78bfa?style=flat-square)](https://github.com/PTPHAP/WebTS/blob/main/LICENSE)

</div>

## WebTS · 把 TeamSpeak 带进浏览器

面向社区的自托管网页语音客户端。通过邮箱登录，管理多个真实 TeamSpeak 身份，在浏览器中加入已有频道，与原生客户端交流。

**邮箱账号 · 多身份管理 · 权限继承 · 频道与聊天 · 经典服务器头像 · 本地 AI 降噪 · 中文一键安装**

| 技术 | 内容 |
| :--- | :--- |
| 前端 | **TypeScript · React · Vite**，中文、深浅主题、响应式 |
| 后端 | **Rust · Tokio · Axum · SQLite**，单进程协议网关 |
| 语音 | **WebRTC · Opus · WASM · GTCRN / RNNoise**，本机降噪与加密传输 |
| 部署 | **Bash · Python · Docker Compose · Caddy**，中文 `webts` 菜单、配置、备份与更新 |
| 状态 | **0.1 开发预览**；TS3已有真实联调，TS6/移动语音/完整兼容与容量仍在验收 |

[查看项目](https://github.com/PTPHAP/WebTS) · [文档中心](https://github.com/PTPHAP/WebTS/blob/main/docs/README.md) · [安装教程](https://github.com/PTPHAP/WebTS/blob/main/docs/INSTALL.md) · [配置教程](https://github.com/PTPHAP/WebTS/blob/main/docs/CONFIGURATION.md)

[支持范围](https://github.com/PTPHAP/WebTS/blob/main/docs/SUPPORT.md) · [隐私政策](https://github.com/PTPHAP/WebTS/blob/main/PRIVACY.md) · [更新记录](https://github.com/PTPHAP/WebTS/blob/main/CHANGELOG.md)

> 语音采用两段传输加密，网关能接触音频；不是端到端加密。网站管理员权限与 TeamSpeak 身份权限独立。只向可信站点托管身份。

---

<div align="center">

**WebTS · 让声音相聚**

<sub>MIT 开源，第三方依赖保留原许可。独立第三方项目，与 TeamSpeak 官方无隶属关系。</sub>

</div>
