# AImagician 开源自荐话术

仓库：https://github.com/TobeMagic/aimagician
Demo：https://tobemagic.github.io/aimagician/
作者：计算机魔术师

下面每条都可以直接贴。不要同一天在所有渠道群发同一段，按渠道改第一句。

## 1. 掘金（推荐先发）

标题：我把技术号的选题、写作和多平台发布收成了一套开源 MCP

正文：

写技术号最烦的不是模型写不出来，是一篇稿要在公众号、掘金、知乎、CSDN 各贴一次。稿在编辑器里，链接在备忘录里，失败原因在聊天记录里。Agent 再能干，也只能对着散落的草稿复制粘贴。

我把自己在用的这条链路拆出来了，开源仓库叫 AImagician：

- 选题、正文版本、每个平台的草稿 / 链接 / 失败原因记在同一篇文章上
- Cursor / Claude 走 MCP 读写这一份 Postgres，不是五个后台
- 网页工作台能看大盘、写作台、发布矩阵
- 账号、cookie、浏览器 profile 不进仓库，只留基建

静态 Demo（不连库，只能点界面）：
https://tobemagic.github.io/aimagician/

源码：
https://github.com/TobeMagic/aimagician

真发文章要自己的 Postgres 和平台会话。欢迎拍砖。

标签：开源 / MCP / 自媒体 / FastAPI

## 2. V2EX · 分享创造

标题：AImagician：把技术自媒体收成一套可被 Agent 操作的开源控制台

正文：

https://github.com/TobeMagic/aimagician

自己写技术号时踩过的坑：多平台不是「一键分发」的问题，是状态记不住。这篇在掘金发了、公众号草稿还停在上周，Agent 也帮不上忙。

这个仓库把选题、成稿、封面、发布矩阵放进同一套 FastAPI + Postgres，MCP 挂在 /mcp。GitHub Pages 上有静态 Demo：

https://tobemagic.github.io/aimagician/

不带任何登录态。本地跑需要 Python 3.11、Node、Postgres。

## 3. HelloGitHub 提交

项目标题：AImagician：Agent 可操作的技术自媒体操作系统

描述（300 字内）：

AImagician 是计算机魔术师开源的技术自媒体基建。它把选题、文章版本、封面和多平台发布状态放进同一套 Postgres，Cursor / Claude 通过 MCP 读写这一份事实，而不是在公众号、掘金、知乎之间复制粘贴。仓库包含 FastAPI 后端、React 工作台、发布 worker 和浏览器适配器，不包含任何账号 cookie。可用 GitHub Pages 静态 Demo 先看界面，真发布需自备 Postgres 与平台会话。Apache-2.0。

提交入口：https://hellogithub.com/

## 4. 阮一峰《科技爱好者周刊》issue

标题：AImagician：开源的 AI 技术自媒体操作系统

正文：

- 仓库：https://github.com/TobeMagic/aimagician
- Demo：https://tobemagic.github.io/aimagician/
- 一句话：把技术号的选题、成稿、封面和多平台发布状态收成一套 MCP，给 Cursor / Claude 反复操作。
- 协议：Apache-2.0
- 说明：静态 Demo 不连数据库；账号和 cookie 不进仓库。

投稿入口：https://github.com/ruanyf/weekly/issues

## 5. 开源中国 OSCHINA 投递软件

软件名：AImagician
官网 / 源码：https://github.com/TobeMagic/aimagician
许可证：Apache-2.0
简介：

面向技术自媒体作者的开源操作系统。选题、文章多版本、封面流程和公众号 / 掘金 / 知乎 / CSDN 等平台发布状态记在同一篇文章库里，并提供 MCP，供 Cursor、Claude 等 Agent 调用。适合想自托管内容流水线、又不愿意把登录态交给 SaaS 的开发者。

投递入口：登录 OSCHINA → 投递资讯 / 软件

## 6. GitHubDaily issue

标题：AImagician — 开源 AI 技术自媒体操作系统（MCP + 发布矩阵）

https://github.com/TobeMagic/aimagician

把选题、写作、封面、多平台发布收成一套可自托管的控制台。Cursor / Claude 走 MCP。静态 Demo：https://tobemagic.github.io/aimagician/

## 7. Show HN

Title: Show HN: AImagician – a self-hosted MCP control plane for technical blogging

Text:

I write a Chinese tech blog across WeChat, Juejin, Zhihu and CSDN. The painful part was never the model — it was keeping one article's drafts, links and failures in the same place, so an agent could actually operate the workflow.

AImagician is the control plane I extracted:

- FastAPI + Postgres + MCP at /mcp
- React console for topics, writing, covers and a publish matrix
- Browser adapters for the platforms; cookies stay on your machine
- Apache-2.0, no live credentials in the repo

Static demo (fixtures only): https://tobemagic.github.io/aimagician/
Repo: https://github.com/TobeMagic/aimagician

Local run needs Python 3.11, Node and Postgres.

## 不要发的写法

- 不要写「一键分发全网爆款」
- 不要把私有仓的 cookie、gh_ id、个人邮箱贴出去
- 不要同一段话复制到 V2EX 和 Show HN
- Show HN 不要求 upvote，也不要让朋友刷票
