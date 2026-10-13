<h1 align="center">william-james.skill</h1>

<p align="center">威廉·詹姆斯 · William James</p>

[中文](README.md) · **English**

<blockquote>
<p align="center">“My experience is what I agree to attend to.”<br>— William James · <a href="https://www.gutenberg.org/cache/epub/57628/pg57628-images.html">The Principles of Psychology</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**A thinking skill for genuine options, epistemic risk, and experience: weigh mistaken belief against missed possibilities when evidence remains unsettled, and distinguish an experience’s causes, value, and truth claims.**

---

## Examples

Illustrative applications written for this README; these are not quotations from the philosopher or transcripts of a live run.

### 1. Must I keep waiting until I am certain someone deserves trust?

> Ask whether waiting would close the opportunity and whether the choice is genuinely unavoidable. Seek available evidence first. If action cannot wait, consider limited, revisable trust while identifying who bears the risk; hope is not proof.

### 2. An experience changed my life. Does that prove its supernatural explanation?

> Its effects, causes, and supernatural interpretation are three questions. Beneficial consequences deserve attention but do not alone establish a cause. A physiological explanation likewise does not automatically remove the experience’s value.

## What is distilled

| Method | What it helps examine |
|---|---|
| Genuine options | Ask whether an option is live, forced, momentous, and still open to evidence. |
| Error and missed opportunity | Identify who bears each risk and whether commitments can be revised. |
| Layers of experience | Separate reported experience, causal hypotheses, and judgments of value. |

These are selected, source-grounded methods, not a claim to cover the complete works. See [SKILL.md](SKILL.md) and [extraction notes](EXTRACTION.md) for scope and reasoning.

## Installation

This skill follows the open [Agent Skills](https://agentskills.io/) standard and can run in any skills-compatible AI agent runtime, including Claude Code, Codex, Cursor, OpenClaw, Hermes Agent, CodeBuddy, Workbuddy, Gemini CLI, OpenCode, and the broader ecosystem of 50+ runtimes.

### 1. One command

```bash
npx skills add jiushiaaa/william-james-skill
```

The [Skills CLI](https://github.com/vercel-labs/skills) can detect supported agents. To select one, append `-a codex`, `-a claude-code`, or `-a cursor`; append `-g` for a global installation. Runtime support describes the standard and installer ecosystem, not a claim that we tested every runtime.

### 2. Manual installation

Clone this repository, then copy the complete folder into your runtime's skill directory, preserving `SKILL.md` and its relative reference paths. Name the installed folder `william-james-perspective` to match its metadata. Common locations include `~/.agents/skills/` (Codex), `~/.claude/skills/` (Claude Code), and `~/.cursor/skills/` (Cursor); consult your runtime's current documentation.

```bash
git clone https://github.com/jiushiaaa/william-james-skill.git
```

### 3. Use as reference

If automatic skill loading is unavailable, provide `SKILL.md` together with the referenced files needed for your question. Research notes remain in their source languages; README and usage guides are bilingual.

## Usage

- **Neutral analysis (default):** “Use William James’s ideas to analyze this question. Distinguish source claims from contemporary applications.”
- **Persona expression (optional):** explicitly request “persona expression mode.” It is an acknowledged simulation, not a statement by the philosopher.

Fiction work uses the ideas while leaving narrative voice to the writing task. See the bilingual [usage guide](USAGE.md).

## Research sources

The Will to Believe; selections from The Varieties of Religious Experience, Pragmatism, and Essays in Radical Empiricism. The opening quotation is separately checked against The Principles of Psychology.

- [Source catalogue and reading ranges](references/research/source-catalog.md)
- [Method extraction and evidence](EXTRACTION.md)
- Opening quotation: <a href="https://www.gutenberg.org/cache/epub/57628/pg57628-images.html">The Principles of Psychology</a>, vol. I, chapter XI, p. 402. English wording is translated where the source is not English; Chinese quotations are repository translations.

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
