# Marketing AI Playbooks — Claude Code Configuration

This repo contains marketing AI skills that auto-load in Claude Code.

## Quick Start

```bash
claude
# Type /copywriting, /page-cro, /seo-audit, etc.
```

## Available Skills

| Command | Description |
|---------|-------------|
| `/copywriting` | Write marketing copy for any page type |
| `/fb-ads-creative` | Generate ad hooks and creatives at scale |
| `/paid-ads` | Full campaign strategy and optimization |
| `/programmatic-seo` | Build SEO pages at scale from templates |
| `/page-cro` | Conversion rate optimization analysis |
| `/seo-audit` | Technical + on-page SEO audit |
| `/competitor-alternatives` | Competitor comparison and alternative pages |

## How It Works

Skills are defined in `.claude/skills/*/SKILL.md`. When you invoke a skill (e.g., `/copywriting`), Claude Code loads the skill instructions and follows the framework defined in the file.

## Quality Standards

All output should be scored against the quality rubrics in `/scoring/`:
- **Page Quality Score**: Target 80+ before publishing
- **SEO Opportunity Score**: Prioritize 65+ opportunities

## Workflow

The standard workflow for client deliverables:

1. **Brief arrives** (intake form, kickoff notes, or Asana task)
2. **Run the skill** with client context
3. **Score the output** against quality rubric
4. **Human review** — check for accuracy, brand voice, fabricated claims
5. **Deliver** to account manager for client review
