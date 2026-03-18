# AI Rank

A Claude Code skill for optimizing content so it gets cited by LLM answer engines (ChatGPT, Perplexity, Claude) and consumed by autonomous AI agents.

Two audiences, two frameworks:
- **LLM Framework** — Make your content quotable by answer engines
- **AGENT Framework** — Make your product accessible to autonomous AI agents

## What It Does

- Audits pages for LLM discoverability and agent readiness
- Rewrites content to be answer-engine-friendly
- Generates discovery files (llms.txt, agents.txt, API catalogs)
- Produces structured data and schema recommendations
- Covers landing pages, docs, blog posts, pricing pages, and API docs

## Installation

```bash
git clone https://github.com/entpnomad/ai-rank.git ~/.claude/skills/ai-rank
```

Or for a specific project:

```bash
git clone https://github.com/entpnomad/ai-rank.git .claude/skills/ai-rank
```

## Usage

```
/ai-rank              # Full workflow
/ai-rank audit        # Dual audit only
/ai-rank rewrite      # Rewrite with both frameworks
/ai-rank discovery    # Generate discovery files
/ai-rank agent        # Agent readiness only
/ai-rank answer       # Answer engine only
/ai-rank checklist    # Full page + site checklists
/ai-rank schema       # Schema suggestions
```

## License

MIT
