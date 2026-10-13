<h1 align="center">schelling.skill</h1>

<p align="center">谢林 · F. W. J. Schelling</p>

**中文** · [English](README.en.md)

<blockquote>
<p align="center">“自然应当是可见的精神，精神应当是不可见的自然。”<br>— 谢林 · <a href="https://assets.meiner.de/Medien-Dateien/9783787315833.pdf">《自然哲学的观念》</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**将主客关系、根据与存在、自由与恶的区分整理为思想分析 Skill，让 AI 检查解释从何出发，避免把哲学根据误作时间原因，或在定义里提前消除真正的问题。**

---

## 效果示例

以下为说明用法而编写的示例，展示分析思路；不是哲学家原话或实测对话记录。

### 1. 如果自由只能选择正确的事，还算自由吗？

> 先检查定义有没有把作恶的可能预先排除。容纳这种可能并不等于要求作恶，更不等于替恶辩护；需分别处理自由条件与行为评价。

### 2. 某物是另一物的“根据”，就表示它更早发生吗？

> 不一定。先看原论证说的是时间上的先后、概念依赖还是存在关系；把这些都译成先后因果，会使问题在尚未论证时就被改写。

## 蒸馏了什么

| 思想方法 | 能帮助分析什么 |
|---|---|
| 主客关系 | 比较从自然到智性与从主观到客观的解释方向。 |
| 根据与先因 | 辨明先行指时间、逻辑还是本体关系。 |
| 自由与恶 | 分开作恶的可能、实际发生与道德正当化。 |

这些方法来自已定位的原作选段，不代表全集蒸馏。具体依据与适用范围见 [SKILL.md](SKILL.md) 和 [提炼说明](EXTRACTION.md)。

## 安装

本 skill 基于开放的 [Agent Skills](https://agentskills.io/) 协议，可在任何 skills-compatible 的 AI agent runtime 中运行（Claude Code、Codex、Cursor、OpenClaw、Hermes Agent、CodeBuddy、Workbuddy、Gemini CLI、OpenCode 等 50+ runtime）。

### 方式一：一行命令

```bash
npx skills add jiushiaaa/schelling-skill
```

[Skills CLI](https://github.com/vercel-labs/skills) 可检测受支持的 agent；指定 runtime 时添加 `-a codex`、`-a claude-code` 或 `-a cursor`，全局安装添加 `-g`。这里说明协议与安装器的兼容生态，不代表本项目逐一实测了全部 runtime。

### 方式二：手动安装

克隆仓库后，将完整目录放入 runtime 的 skills 目录，保留 `SKILL.md` 及相对引用。安装目录命名为 `schelling-perspective`，与入口元数据一致。常见路径为 Codex 的 `~/.agents/skills/`、Claude Code 的 `~/.claude/skills/`、Cursor 的 `~/.cursor/skills/`；以所用 runtime 当前文档为准。

```bash
git clone https://github.com/jiushiaaa/schelling-skill.git
```

### 方式三：作为参考资料

不支持自动加载时，可把 `SKILL.md` 连同当前问题需要的引用文件交给 agent。README 与使用说明提供中英双语，研究底稿保留原语言。

## 使用方式

- **中性思想模式（默认）：** “用谢林的思想分析这个问题，区分原作观点与当代应用。”
- **人物表达模式（可选）：** 明确提出“开启人物表达模式”。这是注明性质的模拟，不是作者本人发言。

文游创作默认只取思想，文风另行决定。详见 [双语使用说明](USAGE.md)。

## 调研来源

《先验唯心论体系》导论选段；《论人类自由的本质》选段；《克拉拉》导论选段。

- [原作来源、版本与实际阅读范围](references/research/source-catalog.md)
- [方法提炼与证据](EXTRACTION.md)
- 开篇名言出处：<a href="https://assets.meiner.de/Medien-Dateien/9783787315833.pdf">《自然哲学的观念》</a>，导论，旧版全集 II，第 56 页；出版社试读引述。中文引文为本仓库译文；非英语原作的英文引文亦为本仓库译文。

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
