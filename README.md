<div align="center">

# ✦ PTPHAP · 天空岛观测台 ✦

### `自托管语音 / 世界维护 / 开源开发`

<img src="https://raw.githubusercontent.com/PTPHAP/PTPHAP/main/assets/observatory.svg" alt="PTPHAP · Sky Island Observatory" width="100%" />

[![WebTS](https://img.shields.io/badge/WebTS-Rust%20%2B%20React%20%2B%20TypeScript-38bdf8?style=flat-square&logo=webrtc&logoColor=white)](https://github.com/PTPHAP/WebTS)
[![SkyIslandSystem](https://img.shields.io/badge/天空岛体系-Paper%201.20.1-8b5cf6?style=flat-square&logo=minecraft&logoColor=white)](https://github.com/PTPHAP/SkyIslandSystem)
[![Java](https://img.shields.io/badge/Java-17%2B-c084fc?style=flat-square&logo=openjdk&logoColor=white)](https://github.com/PTPHAP/SkyIslandSystem)
[![Open Source](https://img.shields.io/badge/Open%20Source-MIT-a78bfa?style=flat-square&logo=github&logoColor=white)](https://github.com/PTPHAP/SkyIslandSystem)

</div>

> **「愿星海中的每一座世界，都有人守望。」**
>
> 这里是 Nicole Reeyn 的个人开发空间。正在制作面向 Minecraft 服务器的“天空岛体系”：让五位独立 Agent 负责巡查、判断与治理，把服务器维护做成一个有角色、有记忆、有秩序的世界系统。

## ✦ 当前项目

### 🎙️ WebTS · 把 TeamSpeak 带进浏览器

面向社区的自托管网页语音客户端：邮箱登录、多个真实 TS 身份、频道与聊天、权限继承、经典服务器头像、本地 AI 降噪，以及中文一条命令安装与 `webts` 管理菜单。

| 技术 | 内容 |
| :--- | :--- |
| 前端 | **TypeScript · React · Vite**，中文、深浅主题、响应式 |
| 后端 | **Rust · Tokio · Axum · SQLite**，单进程协议网关 |
| 语音 | **WebRTC · Opus · WASM · GTCRN / RNNoise**，本机降噪与加密传输 |
| 部署 | **Bash · Python · Docker Compose · Caddy**，中文配置、备份与更新 |
| 状态 | **0.1 开发预览**；TS3已有真实联调，TS6/移动语音/完整兼容与容量仍在验收 |

[查看项目](https://github.com/PTPHAP/WebTS) · [安装教程](https://github.com/PTPHAP/WebTS/blob/main/docs/INSTALL.md) · [配置教程](https://github.com/PTPHAP/WebTS/blob/main/docs/CONFIGURATION.md) · [支持范围](https://github.com/PTPHAP/WebTS/blob/main/docs/SUPPORT.md) · [隐私政策](https://github.com/PTPHAP/WebTS/blob/main/PRIVACY.md)

<sub>语音采用两段传输加密，网关能接触音频；不是端到端加密。网站权限与 TeamSpeak 身份权限独立。MIT开源，第三方依赖保留原许可。</sub>


### 🌌 天空岛体系 · SkyIslandSystem

Paper 1.20.1 服务器维护插件，连接独立 OpenClaw 实例，设定五位治理角色：

| 角色 | 权能 | 状态 |
| :---: | :--- | :---: |
| **天理－法涅斯** | 全局规划与四影审批 | `最高治理` |
| **死之执政－若娜瓦** | 死亡、实体过载、灾难风险 | `调查中` |
| **生之执政－纳贝里士** | 生物生态与生成压力 | `观察中` |
| **时之执政－伊斯塔露** | TPS、时间线与备份状态 | `巡查中` |
| **空之执政－阿斯莫代** | 维度、区块、边界与传送 | `守望中` |

<a href="https://github.com/PTPHAP/SkyIslandSystem"><img src="https://github-readme-stats.vercel.app/api/pin/?username=PTPHAP&repo=SkyIslandSystem&theme=tokyonight&hide_border=true" alt="SkyIslandSystem" /></a>

已实现：离线身份注册与登录、临时封禁、TPS 与世界指标、四影提案审批、受限世界动作、审计记录、一命赛季、OpenClaw 会话隔离。

## ✦ 其他仓库

- [**webteamspeak**](https://github.com/PTPHAP/webteamspeak) · Web TeamSpeak 相关实验
- [**ZeroBot-Plugin**](https://github.com/PTPHAP/ZeroBot-Plugin) · OneBot / ZeroBot 插件开发

## ✦ 技术偏好

```text
Rust · TypeScript · React · WebRTC · Python · Docker
Java · PaperMC · Gradle · OpenClaw · Go · OneBot
服务器自动化 · Agent 记忆隔离 · 可审计的世界治理
```

## ✦ 正在前往的地方

```text
玩家行为证据 → 普通方块可恢复回滚 → 更可靠的反作弊信号
→ 四影资源包现身 → 一个真正会守护世界的天空岛体系
```

<div align="center">

### `✧ 愿你的世界永远稳定，愿你的夜晚总有星光 ✧`

<sub>非官方同人项目 · 角色与世界设定仅用于创作与服务器玩法</sub>

</div>
