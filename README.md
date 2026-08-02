# 星程免费版 · 国内本地化 AI 智能助理 / Coding Agent

**WorkBuddy / Codex / Claude Code 的国内本地化平替。**  
在你自己的电脑上跑 Agent：写代码、操控文件与浏览器、生成 Office 文档、对接微信与飞书——自备模型 API Key（通义、DeepSeek、OpenAI 兼容、Ollama 等）即可，**无需企业后端，数据默认留在本机**。

> 本仓库仅提供 **macOS 安装包与说明**（闭源分发，源码不公开）。  
> 适合检索关键词：`WorkBuddy 平替` · `Codex 平替` · `Claude Code 替代` · `国内 Coding Agent` · `本地 AI 助理` · `OpenAI 兼容桌面客户端`

---

## 为什么选星程免费版

| 痛点 | 星程免费版怎么解 |
|------|------------------|
| Claude Code / Codex 在国内不好用、不稳定 | 直连国内/自建 OpenAI 兼容接口，或本地 Ollama |
| 想要类似 WorkBuddy 的「能干活」助理 | 本地工具链：Shell / 文件 / 浏览器 / Office / 微信飞书 |
| 不想把代码与文件交给云端托管 | 默认本地执行，Key 与配置在本机 `~/.agent-desktop/` |
| 不想绑死单一海外账号体系 | 任意 OpenAI 兼容 Base URL + API Key |

一句话：**类 WorkBuddy 的桌面执行能力 + 类 Claude Code / Codex 的 Agent 编程体验，面向国内环境本地化落地。**

---

## 快速下载

| 平台 | 架构 | 安装包 |
|------|------|--------|
| macOS | Apple Silicon (arm64) | [XingCheng-Free-1.0.1-arm64.dmg](https://github.com/mxc9044/xingcheng-desktop-free/releases/download/v1.0.1/XingCheng-Free-1.0.1-arm64.dmg) |

全部版本：[Releases](https://github.com/mxc9044/xingcheng-desktop-free/releases)

### macOS 打不开？

安装包可能未做 Apple 公证。打开 **系统设置 → 隐私与安全性**，对拦截应用点 **仍要打开**。

---

## 3 步上手

1. 安装 `.dmg`，把「星程免费版」拖进「应用程序」
2. 打开应用 → **设置 → 模型配置**
3. 填写 OpenAI 兼容接口后开始对话：
   - `Base URL`：如 `https://api.deepseek.com/v1`、厂商兼容地址，或 Ollama `http://127.0.0.1:11434/v1`
   - `API Key`：你自己的密钥

配置目录：`~/.agent-desktop/`（`chat-profiles.json`、`config.json`、`mcp.json`、`mail.json` 等）。请自行保管 API Key。

---

## 核心能力（免费版）

- **智能助理 / 子代理 / Skill / 工作流** — 多步任务与可复用技能
- **编码助手（Coding Agent）** — Agent + Git/LSP，可选 OpenCode 桥接（类 Claude Code / Codex 工作流）
- **本地知识库与神经引擎** — 文档与代码上下文留在本机
- **Office** — Word / Excel / PPT 生成与解析
- **本机工具** — Shell、文件、浏览器自动化、MCP
- **协作通道** — 微信远程控制、飞书机器人（本地配置）
- **软件集成框架** — 可自行添加对接

当前免费版**不提供**：远程企业后端桥连、企业登录、iOS Companion（企业治理能力见商业版）。

---

## 和 WorkBuddy / Codex / Claude Code 怎么对照

| 维度 | WorkBuddy 类产品 | Claude Code / Codex | **星程免费版** |
|------|------------------|---------------------|----------------|
| 定位 | 桌面数字员工 / 办公执行 | 终端/IDE 向 Coding Agent | 本地智能助理 + Coding Agent |
| 国内可用性 | 视产品与账号 | 常受网络与账号限制 | **国内模型 / 自建 API / Ollama 直连** |
| 数据与执行 | 因产品而异 | 依赖服务商链路 | **默认本机执行** |
| 办公与通道 | 强 | 偏编码 | Office + 微信/飞书 + 浏览器/文件 |
| 企业治理 | 视版本 | 有限 | 免费版轻量；**商业版**补齐权限/额度/协作 |

> 说明：以上为能力定位对照，并非官方关联或兼容声明。星程是独立产品。

---

## 免费版 vs 商业版

桌面本地能力基本一致。免费版适合个人与试用；商业版面向企业落地。

| | 免费版 | 商业版 |
|---|--------|--------|
| 自备模型直连 | 支持 | 支持（也可企业统一托管） |
| 无需企业后端 | 是 | 可选私有化 / 企业后端 |
| 企业登录与权限 | — | 有 |
| 额度与成本治理 | — | 有 |
| 云同步 / 共享知识库 | — | 有 |
| 部门协作与组织能力 | — | 有 |
| 企业级部署与支持 | — | 有 |

### 采购商业版

企业账号、私有化、组织协作、成本管控或定制集成：

- 邮箱：`llmxc@foxmail.com`
- 手机：`13584744264`

---

## Topics / 检索标签

`workbuddy-alternative` · `claude-code-alternative` · `codex-alternative` · `coding-agent` · `ai-desktop-agent` · `openai-compatible` · `ollama` · `local-ai` · `china-ai` · `electron-agent`

---

## 许可

见 [LICENSE](./LICENSE)。个人与试用可免费使用本安装包；源码不开放；企业商用与规模化部署请联系采购商业版。
