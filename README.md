<div align="center">


# 🧬 爱魔豆 iModel

## AI 模型智能路由网关 · 让每一次调用都物超所值

<br>

**「省心 · 省钱 · 省力」**

> 智能分类路由 + Token 压缩 + 实时监控
> 将 API 调用成本直降 40%~70%

</div>

---

<br>

## 一、痛点直击

<br>

### ❌ 你是不是也遇到这些问题？

| 问题                              | 后果                       |
| :-------------------------------- | :------------------------- |
| 所有请求都用最强模型 → 杀鸡用牛刀 | **每月账单高得离谱**       |
| 长对话历史越积越多 → Token 飞涨   | **一半的钱花在重复计算上** |
| 手动切换模型 → 繁琐又容易出错     | **开发效率低下**           |
| 没有统一监控 → 成本失控无从优化   | **月底对账一脸懵**         |
| 多模型管理混乱 → API Key 散落各处 | **安全隐患大**             |

> **爱魔豆 iModel 一站式解决以上所有问题。**

<br>

---

## 二、产品简介

<br>

**爱魔豆 iModel** 是一款专为 AI 开发者打造的 **智能模型路由与网关管理工具**。它运行在你的电脑上，作为本地代理服务，自动为每一个 AI 请求选择 **最合适的模型**，并对长对话进行 **智能压缩**，在保证响应质量的前提下，**大幅降低 API 调用成本**。

<br>

**一句话理解爱魔豆：**

> 🎯 你只管用 AI，怎么省钱交给爱魔豆。

<br>

---

## 三、核心功能

<br>

### 🔀 智能路由 · 好钢用在刀刃上

爱魔豆自动分析每个请求的复杂程度，将简单请求路由到经济型模型，复杂请求路由到高性能模型。

```
┌─────────────────────────────────────────────────────┐
│                                                     │
│  你提问 ──→  爱魔豆分析复杂度 ──→  自动匹配最佳模型    │
│                                                     │
│  ┌─────────────────────────────────────────────┐   │
│  │  "写一个排序函数"  ──→  ✅ Simple  ──→  Flash  │   │
│  │  "设计分布式系统"  ──→  🔬 Complex ──→  Pro    │   │
│  │  "继续" / "好的"   ──→  ✅ Simple  ──→  Flash  │   │
│  │  "帮我重构整个项目" ──→  🔬 Complex ──→  Pro    │   │
│  └─────────────────────────────────────────────┘   │
│                                                     │
│  目标分布：Simple 约 65% / Complex 约 35%           │
│  → 大部分请求走经济模型，成本自然降低                 │
│                                                     │
└─────────────────────────────────────────────────────┘
```

**效果：** 日常使用中，约 **65% 的请求自动走经济模型**，仅复杂任务才调用高性能模型。

<br>

### 📦 Token 压缩 · 长对话不怕贵

AI 对话中，历史消息越长，Token 消耗越大。爱魔豆的压缩引擎能 **自动压缩长对话历史**，保留核心信息，丢掉冗余内容。

| 对话轮数 |   场景   |    压缩前     |    压缩后     | **节省**  |
| :------: | :------: | :-----------: | :-----------: | :-------: |
|  10 轮   | 代码审查 | 8,200 tokens  | 2,100 tokens  | **⬇ 74%** |
|  20 轮   | 架构设计 | 18,500 tokens | 5,800 tokens  | **⬇ 69%** |
|  30 轮   | 综合讨论 | 32,000 tokens | 11,200 tokens | **⬇ 65%** |
|  50 轮   |  长对话  | 68,000 tokens | 28,000 tokens | **⬇ 59%** |

**额外收益：**

- 🚀 响应速度提升 30%~50%（需要处理的 Token 大幅减少）
- 🎯 响应质量保持 95% 以上（智能压缩，保留关键信息）
- 🔧 压缩策略灵活可调（保护最近 N 轮对话不受压缩）

<br>

### ⚡ 并发控制 · 多任务不打架

团队共用模型时，多请求并发容易导致资源争抢。爱魔豆为每个模型设置独立的 **并发槽位**，请求自动排队，忙时智能等待。

| 能力             | 说明                                   |
| :--------------- | :------------------------------------- |
| **独立并发控制** | 每个模型可单独设置最大并发数           |
| **自动排队**     | 超量请求自动排队，不丢失               |
| **智能超时**     | 排队超时自动通知，避免死等             |
| **故障转移**     | 模型出错自动切换到备用模型，服务不中断 |
| **冷却保护**     | 失败模型自动冷却，避免连续报错         |

<br>

### 📊 实时监控 · 每一分钱都看得见

内置 Web 监控面板，打开浏览器即可查看：

```
┌─────────────────────────────────────────────────────────┐
│                    📊 实时监控面板                         │
│                                                           │
│     ┌──────────┐   ┌──────────┐   ┌──────────┐          │
│     │  活跃请求  │   │  排队请求  │   │ 今日总调用 │          │
│     │    3      │   │    0      │   │  12,847   │          │
│     └──────────┘   └──────────┘   └──────────┘          │
│                                                           │
│   模型延迟 (P50 / P95 / P99):                              │
│   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━       │
│   claude-flash:  1.2s / 3.8s / 6.1s                      │
│   claude-pro:    3.5s / 9.2s / 15.3s                     │
│                                                           │
│   Token 消耗趋势 (今日):                                   │
│   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━       │
│   压缩前: 3,500,000  |  压缩后: 1,200,000  |  节省 66%    │
│                                                           │
│   最近错误:                                                │
│   ❌ claude-pro  rate_limit  12:34:56                     │
│   ⚠️ gpt-4o     timeout     12:30:22                     │
└─────────────────────────────────────────────────────────┘
```

**所有数据永久保存**，支持按天/周/月查看历史趋势，帮你持续优化成本。

<br>

### 🖥️ 跨平台 · 全桌面覆盖

| 平台          |    支持    | 体验                    |
| :------------ | :--------: | :---------------------- |
| 🍎 **macOS**   | ✅ 完整支持 | 菜单栏图标 + 原生通知   |
| 🪟 **Windows** | ✅ 完整支持 | 系统托盘 + Toast 通知   |
| 🐧 **Linux**   | ✅ 完整支持 | AppIndicator + X11 支持 |

**安装后做什么？** 双击打开 → 登录 → 启动服务 → 开始使用，全程不超过 1 分钟。

<br>

### 💻 CLI · 命令行一键接入

> **imodel-cli** 是 iModel 内置的命令行工具，专为 AI 智能体设计，无需启动 Dashboard，一条命令就能创建 API 令牌并获取 Base URL。

```
安装位置（macOS）：
  /Applications/iModel.app/Contents/MacOS/imodel-cli

安装位置（Windows）：
  %ProgramFiles%\iModel\imodel-cli.exe

安装位置（Linux）：
  /usr/local/bin/imodel-cli
```

#### 三大核心功能

| 命令     | 作用                    | 典型场景                                                     |
| -------- | ----------------------- | ------------------------------------------------------------ |
| `token`  | 创建/查询/删除 API 令牌 | 为 Claude Code、Hermes、Codex CLI 等 AI 工具配置 iModel 网关 |
| `agent`  | Agent 授权管理          | 首次授权 AI 工具调用 CLI，建立白名单机制                     |
| `config` | 本地 App 一键配置       | 自动检测并配置本地 App 使用 iModel 代理（支持 Claude Code、Cursor、Cline 等） |

#### 快速开始：为 Hermes 配置 iModel

```bash
# ① 首次使用：授权 Hermes Agent
imodel-cli agent authorize hermes --name "Hermes"

# ② 创建 OpenAI 协议令牌（Hermes 使用 Chat Completions API）
IMODEL_AGENT_ID=hermes imodel-cli token create openai \
  --name "Hermes 令牌" \
  --id hermes

# ③ 查看创建的令牌详情
IMODEL_AGENT_ID=hermes imodel-cli token get hermes

# ④ 列出所有令牌
IMODEL_AGENT_ID=hermes imodel-cli token list
```

> **输出结果**：创建成功后会返回 `api_key` 和 `base_url`，直接填入 Hermes 的环境变量即可：
>
> ```
> OPENAI_API_KEY=mr-hermes-xxxxxxxxxxxx
> OPENAI_BASE_URL=http://127.0.0.1:8788/v1/
> ```

#### 支持的协议类型

| 协议        | 用途                    | 代理端点                    | 适用工具                      |
| ----------- | ----------------------- | --------------------------- | ----------------------------- |
| `anthropic` | Anthropic Messages API  | `POST /v1/messages`         | Claude Code、Claude Desktop   |
| `openai`    | OpenAI Chat Completions | `POST /v1/chat/completions` | Hermes、GMOS、OpenAI 兼容工具 |
| `responses` | OpenAI Responses API    | `POST /v1/responses`        | Codex CLI                     |

#### 一键配置本地 App

```bash
# 查看支持配置的 App 列表
imodel-cli config list

# 自动配置 Claude Code
imodel-cli config setup claude-code

# 查看配置状态
imodel-cli config status
```

> `config setup` 会自动检测 App 安装状态，创建令牌并修改配置文件，全程无需手动操作。

#### 安全机制（三层保护）

```
  身份识别 ────▶ IMODEL_AGENT_ID 声明调用方身份
      │
  Agent 授权 ────▶ 首次使用需 agent authorize 加入白名单
      │
  iModel 登录 ────▶ 未登录时拒绝所有 CLI 操作
```

- **授权管理**：`agent list` 查看已授权列表，`agent revoke` 撤销授权
- **删除保护**：删除令牌需要交互式终端确认，防止误删
- **JSON 输出**：所有命令支持 `--json` 参数，便于 AI 工具解析

#### AI 智能体集成示例

```bash
# 智能体自动获取令牌（JSON 格式，便于脚本解析）
IMODEL_AGENT_ID=my-agent imodel-cli --json token create openai --name "My Agent"

# 返回结构化 JSON：
# {
#   "api_key": "mr-my-agent-a1b2c3d4e5f6",
#   "base_url": "http://127.0.0.1:8788/v1/",
#   "protocol": "openai"
# }
```

> **最佳实践**：每个 AI 应用使用独立的 Agent ID，便于审计和权限管理。

<br>

---

## 四、谁在用

<br>

### 👨‍💻 独立开发者 · 小明

> *"以前每个月 API 账单 3000+，用了爱魔豆之后降到 800 左右。智能路由自动把大部分简单请求走 Flash 模型，完全不影响日常写代码，但钱省了一大半。"*

### 👥 创业团队 · 某 AI 工具公司

> *"团队 5 个人共用 API Key，并发控制帮了大忙。以前经常有人抢资源导致报错，现在自动排队，谁都不用等太久。Dashboard 还能看到每个人的使用量，月底对账清清楚楚。"*

### 🏢 企业用户 · 某互联网公司

> *"我们给内部 20 多个开发者统一配置了爱魔豆企业版，自定义分类能力让不同团队用不同的模型路由策略。Token 压缩每个月省下 40%+ 的 Token 费，老板非常满意。"*

<br>

---

## 五、方案与定价

<br>

| 方案             |       月费        | API Key 数 | 模型总数 | 自定义分类 | Token 压缩 | 局域网访问 | 适合谁             |
| :--------------- | :---------------: | :--------: | :------: | :--------: | :--------: | :--------: | :----------------- |
| 🆓 **Free**       |      **¥0**       |    1 个    |   3 个   |     ❌      |     ❌      |     ❌      | 先试试看           |
| 🥉 **Trial**      | **¥0**（7天试用） |   10 个    |  10 个   |     ❌      |     ✅      |     ❌      | 体验个人版全部功能 |
| 🥈 **Pro** 🔥      |     **¥9.99**     |   10 个    |  10 个   |     ❌      |     ✅      |     ❌      | **开发者首选**     |
| 🥇 **Enterprise** |    **¥99.99**     |   无上限   |  无上限  |  ✅ 无上限  |     ✅      |     ✅      | 团队/企业          |

> 💳 支持 **支付宝 / 微信 / 抖音** 支付，一键订阅，随时升级。

<br>

**为什么选订阅制而不是按量付费？**

- ✅ **成本可预测** — 每月固定支出，不怕突发调用量
- ✅ **用得越多越划算** — 高频用户相当于 Token 成本节约大半
- ✅ **随时升级降级** — 需求变化灵活调整

<br>

---

## 六、和竞品比好在哪？

<br>

| 对比维度                 |  🧬 爱魔豆 iModel   | OpenRouter | LiteLLM  | One API  |
| :----------------------- | :----------------: | :--------: | :------: | :------: |
| **智能路由（按复杂度）** |     ✅ **独家**     |     ❌      |    ❌     |    ❌     |
| **Token 压缩**           |     ✅ **独家**     |     ❌      |    ❌     |    ❌     |
| **跨平台桌面应用**       |     ✅ **独家**     |     ❌      |    ❌     |    ❌     |
| **订阅制（成本可控）**   |         ✅          | ❌ 按量付费 |    ❌     |    ❌     |
| **中国本土化**           |  ✅ 中文+国内支付   | ❌ 可能被墙 |    ❌     |    ✅     |
| **数据本地化**           |    ✅ 数据在本地    |   ❌ SaaS   | ✅ 自托管 | ✅ 自托管 |
| **实时监控面板**         |     ✅ 功能完整     |   ⚠️ 基础   |  ⚠️ 基础  |  ⚠️ 基础  |
| **自动故障转移**         |         ✅          |     ✅      |  ⚠️ 有限  |    ❌     |
| **双协议支持**           | ✅ OpenAI+Anthropic |     ✅      |    ✅     |    ✅     |

**爱魔豆的三大独家优势：**

1. 🧠 **智能路由** — 只有爱魔豆能按请求复杂度自动分配模型
2. 📦 **Token 压缩** — 独家技术，长对话成本直降 60%+
3. 🖥️ **桌面应用** — 开机自启、系统托盘、一键管理，体验最佳

<br>

---

## 七、下载与安装

<br>

### 一键安装 — 免费版

| 平台          | 架构                | 下载链接                                                     |  大小  | 系统要求                  |
| :------------ | :------------------ | :----------------------------------------------------------- | :----: | :------------------------ |
| 🍎 **macOS**   | Apple Silicon (ARM) | [下载 iModel-2.0.35-macOS-arm64.pkg](https://github.com/keerlums/iModel/releases/download/v2.0.35/iModel-2.0.35-macOS-arm64.pkg) | ~22 MB | macOS 13.x 或更高版本     |
| 🍎 **macOS**   | Intel (X64)         | [下载 iModel-2.0.35-macOS-x64.pkg](https://github.com/keerlums/iModel/releases/download/v2.0.35/iModel-2.0.35-macOS-x64.pkg) | ~36 MB | macOS 13.x 或更高版本     |
| 🪟 **Windows** | X64                 | [下载 iModel-2.0.35-windows-x64-setup.exe](https://github.com/keerlums/iModel/releases/download/v2.0.35/iModel-2.0.35-windows-x64-setup.exe) | ~19 MB | Windows 10/11             |
| 🪟 **Windows** | ARM                 | [下载 iModel-2.0.35-windows-arm64-setup.exe](https://github.com/keerlums/iModel/releases/download/v2.0.35/iModel-2.0.35-windows-arm64-setup.exe) | ~18 MB | Windows 10/11             |
| 🐧 **Linux**   | X64                 | [下载 iModel-2.0.35-linux-x64.tar.gz](https://github.com/keerlums/iModel/releases/download/v2.0.35/iModel-2.0.35-linux-x64.tar.gz) | ~36 MB | Ubuntu 20.04+ / CentOS 7+ |
| 🐧 **Linux**   | ARM64               | [下载 iModel-2.0.35-linux-arm64.tar.gz](https://github.com/keerlums/iModel/releases/download/v2.0.35/iModel-2.0.35-linux-arm64.tar.gz) | ~35 MB | Ubuntu 24.04 或更高版本   |

### 一键安装 — Pro 版

> ⚠️ Pro 版桌面客户端目前支持 Windows X64、macOS、Linux 平台，**暂不支持 Windows ARM**，Windows ARM 用户可继续使用免费版。

| 平台          | 架构                | 下载链接                                                     |  大小   | 系统要求                  |
| :------------ | :------------------ | :----------------------------------------------------------- | :-----: | :------------------------ |
| 🍎 **macOS**   | Apple Silicon (ARM) | [下载 iModel-Pro-2.0.35-macOS-arm64.pkg](https://github.com/keerlums/iModel/releases/download/v2.0.35/iModel-Pro-2.0.35-macOS-arm64.pkg) | ~271 MB | macOS 13.x 或更高版本     |
| 🍎 **macOS**   | Intel (X64)         | [下载 iModel-Pro-2.0.35-macOS-x64.pkg](https://github.com/keerlums/iModel/releases/download/v2.0.35/iModel-Pro-2.0.35-macOS-x64.pkg) | ~163 MB | macOS 13.x 或更高版本     |
| 🪟 **Windows** | X64                 | [下载 iModel-Pro-2.0.35-windows-x64-setup.exe](https://github.com/keerlums/iModel/releases/download/v2.0.35/iModel-Pro-2.0.35-windows-x64-setup.exe) | ~196 MB | Windows 10/11             |
| 🐧 **Linux**   | X64                 | [下载 iModel-Pro-2.0.35-linux-x64.tar.gz](https://github.com/keerlums/iModel/releases/download/v2.0.35/iModel-Pro-2.0.35-linux-x64.tar.gz) | ~372 MB | Ubuntu 20.04+ / CentOS 7+ |
| 🐧 **Linux**   | ARM64               | [下载 iModel-Pro-2.0.35-linux-arm64.tar.gz](https://github.com/keerlums/iModel/releases/download/v2.0.35/iModel-Pro-2.0.35-linux-arm64.tar.gz) | ~330 MB | Ubuntu 24.04 或更高版本   |

### 3 步上手

```
1️⃣ 下载安装 →  2️⃣ 手机号登录 →  3️⃣ 启动服务 → 开始使用

总耗时：不超过 1 分钟
```

**然后就可以在你的 AI 工具中使用了：**

- 🛠️ Claude Code / Claude Desktop → 指向 `http://127.0.0.1:8788/v1`
- 🛠️ OpenAI API → 指向 `http://127.0.0.1:8788/v1`
- 🛠️ LangChain / LlamaIndex → 配置代理地址即可
- 🛠️ 任何兼容 OpenAI / Anthropic SDK 的工具 → 开箱即用

<br>

---

## 八、用户反馈

<br>

> ⭐⭐⭐⭐⭐ *"用了两周，账单从 2000 降到 600，强烈推荐。"* — 独立开发者 张工

> ⭐⭐⭐⭐⭐ *"团队 5 个人一起用，并发控制和监控面板最实用，谁花了多少一目了然。"* — 某 AI 创业公司 CTO

> ⭐⭐⭐⭐⭐ *"Token 压缩太香了，长对话从 3 万 Token 压缩到 1 万，质量完全没影响。"* — 某互联网公司 算法工程师

<br>

---

## 九、常见问题

<br>

**Q：爱魔豆会收集我的数据吗？**
A：不会。所有请求数据都存储在你的本地电脑上，爱魔豆只做智能路由和压缩，不收集、不上传你的对话内容。

**Q：支持哪些模型供应商？**
A：支持 OpenAI Chat Completions 和 Anthropic Messages 两种主流协议。兼容 Claude Code、Claude Desktop、OpenAI API 客户端，以及任何支持这两种协议的 AI 工具。更多模型持续接入中。

**Q：安装后对现有工具有影响吗？**
A：完全没有。只需将 API 地址改为 `http://127.0.0.1:8788/v1`，现有代码和工具无需任何改动。

**Q：免费版和付费版有什么区别？**
A：免费版可体验核心路由功能，有 1 个 API Key 额度、3 个模型上限。Pro 版（¥9.99/月）解锁 Token 压缩、最多 10 个 API Key 和 10 个模型等高级功能。企业版（¥99.99/月）提供无上限的 API Key、模型和自定义分类路由，支持局域网分发。

**Q：可以按月订阅吗？可以随时取消吗？**
A：可以。按月订阅，随时取消，不扣违约金。

<br>

---

<div align="center">


<br>

# 🧬 爱魔豆 iModel

**让每一次 AI 调用都物超所值**

<br>

[🌐 官方网站](https://imodel.work)
[📖 使用文档](https://docs.imodel.work)
[💬 用户反馈](https://imodel.work/feedback)
[⬇️ 立即下载](https://imodel.work/download)

<br>

*版本 2.0.35 · 支持 macOS / Windows / Linux*
*如有任何问题，请发送邮件至 support@imodel.work*

<br>

</div>
