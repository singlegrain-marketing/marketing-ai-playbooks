# Marketing AI Playbooks

Battle-tested AI skills from the agency behind Uber, Amazon, Salesforce, and more. Not generic prompts — practitioner playbooks with built-in quality scoring.

> **Standing on the shoulders of giants.** These playbooks build on the original AI marketing skills framework created by [Corey Haines](https://coreyhaines.co). We've taken his foundation and enhanced it with operational depth, quality scoring, and the frameworks we've refined delivering campaigns for hundreds of companies. Credit where it's due — Corey's work made this possible.

---

## What's Inside

7 marketing AI skills covering copywriting, paid ads, SEO, CRO, and competitive intelligence. Each skill includes:

- **Claude.ai Quick Start** — copy-paste prompt that works in any AI tool
- **Complete framework** — the full methodology, not just a template
- **Quality gates** — must-pass checklist before delivery
- **Scoring rubrics** — 0-100 quality scoring so you know when output is ready

| Skill | What It Does | Use Case |
|-------|-------------|----------|
| `/copywriting` | Write marketing copy for any page type | Landing pages, homepages, pricing pages, full website copy |
| `/fb-ads-creative` | Generate ad hooks and creatives at scale | 60 hooks + ad copy in one session |
| `/paid-ads` | Full campaign strategy and optimization | Google, Meta, LinkedIn, TikTok campaign setup |
| `/programmatic-seo` | Build SEO pages at scale from templates | Location pages, comparison pages, directory pages |
| `/page-cro` | Conversion rate optimization analysis | Audit any page and get scored recommendations |
| `/seo-audit` | Technical + on-page SEO audit | Identify and prioritize SEO issues |
| `/competitor-alternatives` | Competitor comparison pages | vs pages, alternative pages, competitive landing pages |

---

## Three Ways to Use These Skills

### 1. Claude.ai Projects (Recommended — zero install)

No terminal. No git. No code.

1. Go to [claude.ai](https://claude.ai) → **Projects** → **New Project**
2. Name it (e.g., "Copywriting Skill")
3. Open the skill file from this repo (e.g., `copywriting/SKILL.md`)
4. Copy the **Claude.ai Quick Start** block into **Project Instructions**
5. Start a new conversation in that project with your brief
6. The skill is now active for every conversation in that project

**Pro tip**: Create one project per skill. Then you always have them ready.

### 2. Paste-and-Go (Quick one-off)

Works with Claude.ai, ChatGPT, or any AI tool:

1. Open any skill file in this repo
2. Copy the **Claude.ai Quick Start** block
3. Paste it at the start of a new conversation
4. Add your specific brief below it
5. Go

### 3. Claude Code (For developers and power users)

```bash
git clone https://github.com/singlegrain-marketing/marketing-ai-playbooks.git
cd marketing-ai-playbooks
claude
# Type /copywriting, /page-cro, /seo-audit, etc.
```

Skills auto-load from `.claude/skills/`. No configuration needed.

---

## Why These Are Different

**Built from practice, not theory.** These playbooks come from an agency that's delivered campaigns for Uber, Amazon, Salesforce, Airbnb, and hundreds of growth-stage companies. The frameworks reflect what actually converts — not what sounds good in a blog post.

**Quality scoring built in.** Every skill includes a 0-100 scoring rubric so you can objectively assess output quality before publishing or sending to a client. No more guessing whether AI output is "good enough."

**Workflow-integrated.** Skills are designed for the real agency/team workflow: client brief arrives → run the skill → human review → client delivery. Not standalone prompts — complete SOPs.

**Honest about limitations.** Each skill tells you what to check manually, what AI gets wrong, and where human judgment is required. No "just trust the AI" hand-waving.

---

## Quality Scoring

Every skill references two scoring systems. Full rubrics in [`/scoring`](scoring/):

### Page Quality Score (0-100)

| Factor | Weight | What It Measures |
|--------|--------|-----------------|
| Word count | 25% | Target 2,500-4,000 words for full pages |
| Internal links | 20% | 5-7 links to relevant pages |
| Freshness | 20% | Current year references, up-to-date examples |
| Structure | 20% | Comparison table + FAQ + heading hierarchy + CTAs |
| CTR potential | 15% | Would you click this headline in search results? |

**80+** = ready to publish | **60-79** = needs another pass | **Under 60** = rewrite

### SEO Opportunity Score (0-100)

| Factor | Weight | What It Measures |
|--------|--------|-----------------|
| Keyword difficulty | 30% | Lower KD = higher score |
| Trend direction | 20% | Rising/breakout trends score highest |
| Search volume | 20% | Log scale, 1,000+ = good |
| Conversion potential | 15% | By content type (pricing > vs > alternatives > listicle) |
| Competitive gap | 15% | Fewer/weaker competitors = higher opportunity |

**80+** = critical priority | **65-79** = high | **50-64** = medium | **Under 50** = low

---

## Repo Structure

```
marketing-ai-playbooks/
├── README.md                          # You are here
├── CLAUDE.md                          # Claude Code configuration
├── .claude/
│   └── skills/
│       ├── copywriting/SKILL.md       # Full-page copywriting
│       ├── fb-ads-creative/SKILL.md   # Bulk ad creative generation
│       ├── paid-ads/SKILL.md          # Campaign strategy & optimization
│       ├── programmatic-seo/SKILL.md  # SEO pages at scale
│       ├── page-cro/SKILL.md          # Conversion rate optimization
│       ├── seo-audit/SKILL.md         # Technical + on-page SEO audit
│       ├── competitor-alternatives/SKILL.md  # Comparison pages
│       └── CLAUDE.md                  # Skills index
├── scoring/
│   ├── quality-scorer.md              # Page quality rubric (0-100)
│   └── opportunity-scorer.md          # SEO opportunity rubric (0-100)
└── docs/
    ├── getting-started.md             # 5-min setup guide
    └── workflow-integration.md        # How skills fit your delivery process
```

---

## Getting Started

**Fastest path** (2 minutes):
1. Pick a skill from the table above
2. Open its SKILL.md file
3. Copy the "Claude.ai Quick Start" block
4. Paste into Claude.ai and add your brief

**Full setup** (5 minutes):
See [docs/getting-started.md](docs/getting-started.md)

---

## Contributing

These playbooks improve with real-world usage. If you find something that doesn't work or have a better approach:

1. Open an issue describing what didn't work and what you expected
2. Submit a PR with your improvement
3. Include before/after examples if possible

---

## Built by Single Grain

[Single Grain](https://www.singlegrain.com) is a digital marketing agency that combines data-driven strategy with AI-enhanced delivery. We've worked with Uber, Amazon, Salesforce, Airbnb, and hundreds of growth-stage companies.

These playbooks are the same skills our team uses internally for client delivery. We open-sourced them because better tools make better marketers.

**[Leveling Up Podcast](https://www.levelingup.com)** — Weekly marketing and business insights from Eric Siu

---

## License

MIT — use these however you want. Attribution appreciated but not required.
