<h1 align="center">schelling.skill</h1>

<p align="center">谢林 · F. W. J. Schelling</p>

[中文](README.md) · **English**

<blockquote>
<p align="center">“Nature should be visible spirit, and spirit invisible nature.”<br>— F. W. J. Schelling · <a href="https://assets.meiner.de/Medien-Dateien/9783787315833.pdf">Ideas for a Philosophy of Nature</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**A thinking skill for subject–object relations, ground and existence, and freedom and evil: inspect explanatory starting points, distinguish grounds from earlier causes, and expose definitions that decide the problem in advance.**

---

## Examples

Illustrative applications written for this README; these are not quotations from the philosopher or transcripts of a live run.

### 1. If freedom can choose only what is right, is it still freedom?

> Ask whether the definition excludes the possibility of evil in advance. Admitting that possibility does not require evil or justify it. Conditions of freedom and judgments of conduct remain distinct.

### 2. If one thing is another’s ground, must it have occurred earlier?

> Not necessarily. Determine whether the argument concerns temporal order, conceptual dependence, or an ontological relation. Treating every ground as an earlier cause changes the problem before it has been argued.

## What is distilled

| Method | What it helps examine |
|---|---|
| Subject and object | Compare explanations moving from nature to intelligence and from subject to object. |
| Ground and prior cause | Distinguish temporal, logical, and ontological priority. |
| Freedom and evil | Separate the possibility of evil, its occurrence, and its justification. |

These are selected, source-grounded methods, not a claim to cover the complete works. See [SKILL.md](SKILL.md) and [extraction notes](EXTRACTION.md) for scope and reasoning.

## Installation

This skill follows the open [Agent Skills](https://agentskills.io/) standard and can run in any skills-compatible AI agent runtime, including Claude Code, Codex, Cursor, OpenClaw, Hermes Agent, CodeBuddy, Workbuddy, Gemini CLI, OpenCode, and the broader ecosystem of 50+ runtimes.

### 1. One command

```bash
npx skills add jiushiaaa/schelling-skill
```

The [Skills CLI](https://github.com/vercel-labs/skills) can detect supported agents. To select one, append `-a codex`, `-a claude-code`, or `-a cursor`; append `-g` for a global installation. Runtime support describes the standard and installer ecosystem, not a claim that we tested every runtime.

### 2. Manual installation

Clone this repository, then copy the complete folder into your runtime's skill directory, preserving `SKILL.md` and its relative reference paths. Name the installed folder `schelling-perspective` to match its metadata. Common locations include `~/.agents/skills/` (Codex), `~/.claude/skills/` (Claude Code), and `~/.cursor/skills/` (Cursor); consult your runtime's current documentation.

```bash
git clone https://github.com/jiushiaaa/schelling-skill.git
```

### 3. Use as reference

If automatic skill loading is unavailable, provide `SKILL.md` together with the referenced files needed for your question. Research notes remain in their source languages; README and usage guides are bilingual.

## Usage

- **Neutral analysis (default):** “Use F. W. J. Schelling’s ideas to analyze this question. Distinguish source claims from contemporary applications.”
- **Persona expression (optional):** explicitly request “persona expression mode.” It is an acknowledged simulation, not a statement by the philosopher.

Fiction work uses the ideas while leaving narrative voice to the writing task. See the bilingual [usage guide](USAGE.md).

## Research sources

Selections from the introduction to the System of Transcendental Idealism, the Philosophical Investigations into the Essence of Human Freedom, and the introduction to Clara.

- [Source catalogue and reading ranges](references/research/source-catalog.md)
- [Method extraction and evidence](EXTRACTION.md)
- Opening quotation: <a href="https://assets.meiner.de/Medien-Dateien/9783787315833.pdf">Ideas for a Philosophy of Nature</a>, Introduction, SW II, p. 56; quoted in the publisher preview. English wording is translated where the source is not English; Chinese quotations are repository translations.

## Repository structure

Main files:

```text
├── SKILL.md  # Skill entry point and analysis methods
├── README.md / README.en.md  # Chinese and English introduction
├── USAGE.md  # Bilingual usage guide
├── EXTRACTION.md  # Method extraction and evidence
├── references/  # Research notes and optional expression mode
└── LICENSE  # MIT license
```

## Built with

Built with [nvwa-skill](https://github.com/alchaincyf/nuwa-skill).

Original project material is [MIT licensed](LICENSE); quoted works and translations retain their separate rights. See [source notices](ATTRIBUTION.md).

## More skills

Explore more thinkers and writers in the [Philosophy Skills collection](https://github.com/jiushiaaa/Philosophy-Skills).
