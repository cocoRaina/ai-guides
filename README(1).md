# AI 使用教程

面向所有人的通用教程，不依赖任何具体 App 或框架。只要你想把 Claude（或其他大模型）用得更省、更聪明、更能"记住你"，都能用得上。

---

## 💰 省钱 · Prompt Caching（提示词缓存）

| 教程 | 内容 |
|---|---|
| [**Prompt Caching 入门**](prompt-caching.md) | 让 Claude 长对话省 ~10 倍成本：原理、两个必要条件、怎么挑中转站、怎么验证命中、踩坑 |
| [**Anthropic Prompt Cache 保活**](Anthropic%20Prompt%20Cache%20保活.md) | 缓存为什么会过期、怎么用定时 ping 给它"续命"、什么时候续划算、成本账怎么算 |

## 🧠 记忆 · 让 AI 记住你

| 教程 | 内容 |
|---|---|
| [**给 Claude 造一个长期记忆（原理篇）**](memory-system.md) | 为什么 Claude 会失忆、常驻注入 vs 向量搜索、RRF 混合检索、记忆生命周期、自动提取去重、访问追踪、AI 自管理 |
| [**用 Supabase 做记忆库（实操篇·小白向）**](supabase-memory-101.md) | 零后端基础也能跟着做：建项目 → 建表 → 向量搜索原理 → 数据库函数 → Edge Function 串起来；附 Supabase 能做什么 vs 何时上 VPS、用 MCP 让 AI 帮你管后端 |

---

> 这两个主题是一对：**缓存**让长对话便宜，**记忆**让 AI 跨会话记住你。两篇"原理 + 实操"配套食用效果最佳 🍰
