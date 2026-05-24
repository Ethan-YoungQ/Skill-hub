<div align="center">

**English** | [中文](README_zh.md)

</div>

# Skill-hub

A shared collection of skills across multiple AI coding agents (Claude Code, Antigravity, Codex, etc.), totaling **73** skills.

## Purpose

- **Backup and single source of truth**: Backed up online; if lost, you can pull it back from here.
- **Easy to find**: Three lookup entry points (alphabetical / domain / tech stack) to help you quickly determine whether a skill has already been captured or needs to be created.
- **Shared + project-specific coexistence**: General-purpose skills live in `skills/`; private skills scoped to a specific repository live in `projects/`.

## Directory Structure

```
skills/                        # 64 shared skills across 11 domains
├── 01-agent-engineering/      Agent engineering (building, debugging, autonomy loops, harness, etc.)
├── 02-coding-languages/       Programming languages (Swift + general)
├── 03-frameworks/             Framework stacks (Next.js, React, etc.)
├── 04-testing-quality/        Testing, TDD, code review
├── 05-devops-infra/           DevOps and infrastructure
├── 06-data-search/            Data scraping, retrieval, deep research
├── 07-media-content/          Multimedia (PPT, video, PDF, images)
├── 08-writing-marketing/      Writing and marketing
├── 09-ops-productivity/       Office automation (Slack, Jira, etc.)
├── 10-business-industry/      Industry-specific (healthcare, legal, finance, etc.)
└── 12-ai-api/                 AI API, LLM pipelines, token budgeting

projects/                      # 9 project-specific skills
_meta/                         # Index entry points (Chinese)
docs/                          # Conventions documentation
scripts/                       # Sync and junction setup scripts
```

## How to Find Skills

Choose an entry point based on the dimension you care about:

| Entry Point | Best For |
|---|---|
| [By Name](./_meta/by-name.md) | You already know the skill name (e.g., `agent-browser`) |
| [By Domain](./_meta/by-domain.md) | You want to browse categories like "Agent Engineering" / "Testing" / "Industry" |
| [By Tech Stack](./_meta/by-platform.md) | You want to find "Python-related" / "Browser Automation" skills |
| [Machine-Readable](./_meta/skills-lock.json) | Scripts, automation, external tool integration |

## Skill Format

Each skill is a directory containing a `SKILL.md` file with the following YAML frontmatter:

```markdown
---
name: skill-name
description: One-line trigger condition: when should the agent use this skill.
---

# Body: instructions, references, examples
```

The same frontmatter format works across multiple AI agents.

## Local Setup (User-Configured)

Different agents use different skills directory paths. On Windows, Directory Junctions are commonly used locally to point to a single source, avoiding duplicate copies.

Script: [`scripts/setup-junctions.ps1`](./scripts/setup-junctions.ps1)

```powershell
# Preview
.\scripts\setup-junctions.ps1 -Source "D:\path\to\your\skills" -DryRun

# Execute
.\scripts\setup-junctions.ps1 -Source "D:\path\to\your\skills"
```

## Sync Mechanism

Locally, a flat structure is preferred; the repository is organized by domain. Two scripts handle bidirectional sync:

- [`scripts/sync-push.ps1`](./scripts/sync-push.ps1): Local flat structure → Repository grouped structure
- [`scripts/sync-pull.ps1`](./scripts/sync-pull.ps1): Repository grouped structure → Local flat structure
- [`scripts/build-indexes.ps1`](./scripts/build-indexes.ps1): Rebuild indexes under `_meta/`

The mapping relationship comes from [`_meta/skills-lock.json`](./_meta/skills-lock.json).

## Naming and Directory Conventions

See [`docs/directory-conventions.md`](./docs/directory-conventions.md).

## Privacy and Anonymization

This repository is public. All skills undergo an anonymization scan before being added:

- Email addresses, phone numbers → Placeholders
- API keys / tokens / secrets → Placeholders
- Local user directories → `%USERPROFILE%` or `~`
- Private tools / service names → Generic descriptions

See [`docs/privacy-audit.md`](./docs/privacy-audit.md) for details.

**When using someone else's skill, fill in your own credentials using the `<YOUR_*>` / `<your-*>` placeholders; do not commit files with real credentials back to the repository.**

## License

For personal showcase and learning only. External PRs are not accepted by default.
