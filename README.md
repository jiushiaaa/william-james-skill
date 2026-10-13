<h1 align="center">william-james.skill</h1>

<p align="center">威廉·詹姆斯 · William James</p>

**中文** · [English](README.en.md)

<blockquote>
<p align="center">“我的经验，就是我愿意留意的东西。”<br>— 威廉·詹姆斯 · <a href="https://www.gutenberg.org/cache/epub/57628/pg57628-images.html">《心理学原理》</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**将真正选项、认知风险与经验分析整理为思想分析 Skill，让 AI 在证据尚未裁定的问题中权衡错信与错失，并分清一个经验的成因、价值和真假。**

---

## 效果示例

以下为说明用法而编写的示例，展示分析思路；不是哲学家原话或实测对话记录。

### 1. 没有完全确定对方值得信任，我是否只能一直等待？

> 先看等待是不是也会关闭合作机会，以及这个选项是否真的无法推迟。若证据仍可取得，就继续调查；若必须行动，可以讨论有限、可修正的信任，同时说明风险由谁承担，而不把希望当证明。

### 2. 一次体验改变了我的生活，这能证明它的超自然解释吗？

> 改变生活的效果、体验的成因与超自然主张是三个问题。积极后果值得认真记录，但不能独自证明成因；反过来，提出生理解释也不会自动抹去经验的价值。

## 蒸馏了什么

| 思想方法 | 能帮助分析什么 |
|---|---|
| 真正选项 | 检查选择是否活的、被迫的、重大的，以及能否等待证据。 |
| 错信与错失 | 比较两类风险由谁承担，寻找可修正的承诺。 |
| 经验分层 | 分开经验报告、成因假说与价值判断。 |

这些方法来自已定位的原作选段，不代表全集蒸馏。具体依据与适用范围见 [SKILL.md](SKILL.md) 和 [提炼说明](EXTRACTION.md)。

## 安装

本 skill 基于开放的 [Agent Skills](https://agentskills.io/) 协议，可在任何 skills-compatible 的 AI agent runtime 中运行（Claude Code、Codex、Cursor、OpenClaw、Hermes Agent、CodeBuddy、Workbuddy、Gemini CLI、OpenCode 等 50+ runtime）。

### 方式一：一行命令

```bash
npx skills add jiushiaaa/william-james-skill
```

[Skills CLI](https://github.com/vercel-labs/skills) 可检测受支持的 agent；指定 runtime 时添加 `-a codex`、`-a claude-code` 或 `-a cursor`，全局安装添加 `-g`。这里说明协议与安装器的兼容生态，不代表本项目逐一实测了全部 runtime。

### 方式二：手动安装

克隆仓库后，将完整目录放入 runtime 的 skills 目录，保留 `SKILL.md` 及相对引用。安装目录命名为 `william-james-perspective`，与入口元数据一致。常见路径为 Codex 的 `~/.agents/skills/`、Claude Code 的 `~/.claude/skills/`、Cursor 的 `~/.cursor/skills/`；以所用 runtime 当前文档为准。

```bash
git clone https://github.com/jiushiaaa/william-james-skill.git
```

### 方式三：作为参考资料

不支持自动加载时，可把 `SKILL.md` 连同当前问题需要的引用文件交给 agent。README 与使用说明提供中英双语，研究底稿保留原语言。

## 使用方式

- **中性思想模式（默认）：**“用威廉·詹姆斯的思想分析这个问题，区分原作观点与当代应用。”
- **人物表达模式（可选）：**明确提出“开启人物表达模式”。这是注明性质的模拟，不是作者本人发言。

文游创作默认只取思想，文风另行决定。详见 [双语使用说明](USAGE.md)。

## 调研来源

《相信的意志》；《宗教经验之种种》选段；《实用主义》及《激进经验主义论文集》选段。开篇引文另核《心理学原理》。

- [原作来源、版本与实际阅读范围](references/research/source-catalog.md)
- [方法提炼与证据](EXTRACTION.md)
- 开篇名言出处：<a href="https://www.gutenberg.org/cache/epub/57628/pg57628-images.html">《心理学原理》</a>，第一卷，第十一章，第 402 页。中文引文为本仓库译文；非英语原作的英文引文亦为本仓库译文。

## 仓库结构

主要文件：

```text
├── SKILL.md  # Skill 入口与分析方法
├── README.md / README.en.md  # 中英文介绍
├── USAGE.md  # 双语使用说明
├── EXTRACTION.md  # 方法提炼与证据
├── references/  # 研究笔记与可选人物表达模式
└── LICENSE  # MIT 许可
```

## 构建工具

使用 [nvwa-skill](https://github.com/alchaincyf/nuwa-skill) 构建。

项目原创材料采用 [MIT](LICENSE)，所引原著与译本保留各自权利。详见 [来源说明](ATTRIBUTION.md)。

## 更多 Skill

更多人物 Skill 请查看 [Philosophy Skills 合集](https://github.com/jiushiaaa/Philosophy-Skills)。
