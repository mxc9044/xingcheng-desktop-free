# 星程免费版

本地电脑操控的 AI 智能助理客户端。自备模型 API Key（或 Ollama）即可使用，**无需企业后端**。

> 本仓库仅提供**安装包与说明**，产品源码不公开（闭源分发）。

## 下载

| 平台 | 架构 | 安装包 |
|------|------|--------|
| macOS | Apple Silicon (arm64) | [XingCheng-Free-1.0.0-arm64.dmg](https://github.com/mxc9044/xingcheng-desktop-free/releases/download/v1.0.0/XingCheng-Free-1.0.0-arm64.dmg) |

更多版本见 [Releases](https://github.com/mxc9044/xingcheng-desktop-free/releases)。

### macOS 打开提示

安装包当前可能未做 Apple 公证。若提示无法打开：

1. 打开 **系统设置 → 隐私与安全性**
2. 在被拦截的应用旁点击 **仍要打开**

## 使用方式

1. 下载并安装 `.dmg`，将「星程免费版」拖入「应用程序」
2. 启动应用 → **设置 → 模型配置**
3. 填写 OpenAI 兼容接口：
   - `Base URL`（例如 `https://api.openai.com/v1`，或本地 Ollama `http://127.0.0.1:11434/v1`）
   - `API Key`
4. 选择模型后，在「智能助理」中开始对话

本机配置目录：`~/.agent-desktop/`（如 `chat-profiles.json`、`config.json`、`mcp.json`、`mail.json` 等）。

请妥善保管你的模型 API Key，勿泄露给他人。

## 主要能力

免费版桌面端本地能力包括：

- 智能助理 / 子代理 / Skill / 工作流
- 本地知识库与神经引擎
- 编码助手（Agent + Git/LSP，可选 OpenCode 桥接）
- Office（Word / Excel / PPT）生成与解析
- 浏览器自动化、文件与 Shell 等本地工具
- 微信远程控制、飞书机器人（本地配置）
- 软件集成框架（可自行添加对接）

## 免费版 vs 商业版

**桌面本地能力基本一致。** 免费版面向个人与轻量使用；商业版面向企业落地与治理。

| | 免费版 | 商业版 |
|---|--------|--------|
| 自备模型直连 | 支持 | 支持（也可企业统一托管） |
| 无需企业后端 | 是 | 可选私有化 / 企业后端 |
| 企业登录与权限 | — | 有 |
| 额度与成本治理 | — | 有 |
| 云同步 / 共享知识库 | — | 有 |
| 部门协作与组织能力 | — | 有 |
| 企业级部署与支持 | — | 有 |

## 采购商业版

如需企业账号、私有化部署、组织协作、成本管控或定制集成，请联系采购：

- 邮箱：`llmxc@foxmail.com`
- 手机：`13584744264`

## 许可说明

见 [LICENSE](./LICENSE)。个人与试用可免费使用本安装包；源码不开放；企业商用与规模化部署请联系采购商业版。
