# Awesome Claude Code 中文指南

> 📘 **精选 Claude Code 技能、工具、插件和资源列表**
> 
> 📦 原版项目：[hesreallyhim/awesome-claude-code](https://github.com/hesreallyhim/awesome-claude-code) (33,360⭐)
> 
> 📝 中文维护者：[@toyball860721](https://github.com/toyball860721)
> 
> ☕ 支持本项目：[爱发电](https://afdian.com/a/toyball) | [GitHub Sponsors](https://github.com/sponsors/toyball860721)

---

## 🚀 项目简介

这是一个精选列表，收集了能够增强你 [Claude Code](https://docs.anthropic.com/en/docs/claude-code) 工作流的技能、代理、插件、hooks 和其他工具。

---

## 📌 最新添加

| 项目 | 描述 |
|------|------|
| **[agnix](https://github.com/agent-sh/agnix)** | Claude Code 代理文件的综合 linter，验证 CLAUDE.md、AGENTS.md、SKILL.md、hooks、MCP 等 |
| **[Codebase to Course](https://github.com/zarazhangrui/codebase-to-course)** | 将任何代码库变成精美的交互式单页 HTML 课程 |
| **[Ruflo](https://github.com/ruvnet/ruflo)** | 多代理集群的编排平台，自学习、自主多代理集群、向量多层记忆 |

---

## 📑 目录

1. [代理技能 🤖](#代理技能-)
2. [工作流与知识指南 🧠](#工作流与知识指南-)
3. [工具 🧰](#工具-)
4. [状态行 📊](#状态行-)
5. [Hooks 🪝](#hooks-)
6. [斜杠命令 🔪](#斜杠命令-)
7. [CLAUDE.md 文件 📂](#claudemd-文件-)
8. [替代客户端 📱](#替代客户端-)

---

## 代理技能 🤖

> 代理技能是模型控制的配置（文件、脚本、资源等），使 Claude Code 能够执行需要特定知识或能力的专业任务。

### 精选推荐

| 项目 | Stars | 描述 |
|------|-------|------|
| **[AgentSys](https://github.com/avifenesh/agentsys)** | - | 工作流自动化系统，包含有用的插件、代理和技能 |
| **[Claude Code Agents](https://github.com/undeadlist/claude-code-agents)** | - | 端到端开发工作流，适合独立开发者 |
| **[Claude Scientific Skills](https://github.com/K-Dense-AI/claude-scientific-skills)** | - | 研究、科学、工程、分析、金融和写作的代理技能 |
| **[Trail of Bits Security Skills](https://github.com/trailofbits/skills)** | - | 10+ 个安全聚焦的技能，用于代码审计和漏洞检测 |
| **[Superpowers](https://github.com/obra/superpowers)** | - | 软件工程核心能力 bundle，覆盖大部分 SDLC |

---

## 工作流与知识指南 🧠

> 工作流是紧密耦合的 Claude Code 原生资源集，促进特定项目。

### 精选推荐

| 项目 | 描述 |
|------|------|
| **[AB Method](https://github.com/ayoubben18/ab-method)** | 原则性、规范驱动的工作流，将大问题转化为聚焦的增量任务 |
| **[Claude Code Handbook](https://nikiforovall.blog/claude-code-rules/)** | Claude Code 开发工作流的最佳实践、技巧和技巧集合 |
| **[Claude Code Ultimate Guide](https://github.com/FlorianBruniaux/claude-code-ultimate-guide)** | 从初学者到高级用户的完整指南，包含生产就绪模板 |
| **[RIPER Workflow](https://github.com/tony/claude-code-riper-5)** | 结构化开发工作流，强制分离研究、创新、计划、执行和审查阶段 |

### Ralph Wiggum 技术

| 项目 | 描述 |
|------|------|
| **[Ralph for Claude Code](https://github.com/frankbria/ralph-claude-code)** | 自主 AI 开发框架，使 Claude Code 能够迭代工作直到完成 |
| **[The Ralph Playbook](https://github.com/ClaytonFarr/ralph-playbook)** | Ralph Wiggum 技术的详细指南，包含理论评论和实践建议 |

---

## 工具 🧰

> 工具表示建立在 Claude Code 之上的应用程序，由比斜杠命令和 CLAUDE.md 文件更多的组件组成。

### IDE 集成

| 项目 | 平台 | 描述 |
|------|------|------|
| **[Claude Code Chat](https://marketplace.visualstudio.com/items?itemName=AndrePimenta.claude-code-chat)** | VS Code | 优雅的 Claude Code 聊天界面 |
| **[claude-code.nvim](https://github.com/greggh/claude-code.nvim)** | Neovim | Claude Code 与 Neovim 的无缝集成 |
| **[Claudix](https://github.com/Haleclipse/Claudix)** | VS Code | 直接在编辑器中运行 Claude Code |

### 使用监控

| 项目 | 描述 |
|------|------|
| **[ccusage](https://github.com/ryoppippi/ccusage)** | 分析 Claude Code 使用情况的 CLI 工具 |
| **[ccflare](https://github.com/snipeship/ccflare)** | 带有精美 Web UI 的使用仪表板 |
| **[better-ccflare](https://github.com/tombii/better-ccflare/)** | ccflare 的增强 fork，性能优化 + Docker 部署 |
| **[Claudex](https://github.com/kunwar-shah/claudex)** | 浏览 Claude Code 对话历史的 Web 界面 |

### 编排器

| 项目 | 描述 |
|------|------|
| **[Auto-Claude](https://github.com/AndyMik90/Auto-Claude)** | 自主多代理编码框架，集成完整 SDLC |
| **[Claude Squad](https://github.com/smtg-ai/claude-squad)** | 在单独工作区中管理多个 Claude Code 会话 |
| **[Ruflo](https://github.com/ruvnet/ruflo)** | 部署和协调多代理集群的编排平台 |

---

## Hooks 🪝

> Hooks 是在特定事件（如用户消息、模型响应、工具调用）之前或之后运行的自定义脚本。

### 精选推荐

| 项目 | 描述 |
|------|------|
| **[cc-tools](https://github.com/Veraticus/cc-tools)** | Go 实现的高性能 hooks 和工具 |
| **[ContextKit](https://github.com/FlineDev/ContextKit)** | 系统开发框架，将 Claude Code 转变为主动开发伙伴 |

---

## 斜杠命令 🔪

> 斜杠命令是快速执行常见任务的快捷方式。

### 分类推荐

| 类别 | 代表项目 |
|------|----------|
| **版本控制 & Git** | git-pushing, using-git-worktrees |
| **代码分析 & 测试** | test-fixing, review-implementing |
| **上下文加载** | context-priming, session-restore |
| **文档 & Changelog** | changelog-generator, documentation-writer |
| **项目管理** | task-manager, project-bootstrapper |

---

## CLAUDE.md 文件 📂

> CLAUDE.md 文件包含项目范围的规则，AI 助手在每次对话中遵循。

### 语言特定

| 项目 | 描述 |
|------|------|
| **Language-specific CLAUDE.md** | 针对特定语言的最佳实践和约定 |

### 领域特定

| 项目 | 描述 |
|------|------|
| **Domain-specific CLAUDE.md** | 针对特定领域（如 Web 开发、数据科学）的规则 |

---

## 🤝 参与贡献

欢迎提交 Issue 和 Pull Request 改进中文文档！

---

## 📄 许可证

本项目遵循原项目的 MIT 许可证。

---

## ☕ 支持作者

如果你觉得这个中文文档对你有帮助，欢迎支持：

- [爱发电](https://afdian.com/a/toyball)
- [GitHub Sponsors](https://github.com/sponsors/toyball860721)

**中文维护者持续更新中...** 🦞

*最后更新：2026-03-28*
