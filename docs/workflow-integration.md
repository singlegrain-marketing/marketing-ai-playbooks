# Workflow Integration

How AI skills fit into your existing delivery process.

---

## The Standard Workflow

```
Client Brief → AI Skill → Human Review → Client Delivery
```

### Step 1: Brief Arrives

Briefs typically come from:
- **Intake form / questionnaire** — client fills out before kickoff
- **Kickoff call notes** — meeting notes with goals, audience, constraints
- **Project management task** — Asana/Monday/ClickUp task with requirements

**What you need before running a skill:**
- Who is the audience?
- What's the goal/CTA?
- What's the product/service?
- What exists today? (current URL if rewrite)
- Any brand guidelines or constraints?

### Step 2: Run the AI Skill

Choose the right skill for the deliverable:

| Deliverable | Skill | Expected Output |
|-------------|-------|----------------|
| Landing page copy | `/copywriting` | Full page copy with headline options, CTAs, meta content |
| Homepage rewrite | `/copywriting` | Complete homepage copy organized by section |
| Ad campaign creative | `/fb-ads-creative` | 60 hooks + ad copy + image text |
| Campaign strategy | `/paid-ads` | Campaign structure, targeting, budget allocation |
| 50 location pages | `/programmatic-seo` | Template + batch page content |
| Page performance audit | `/page-cro` | Scored analysis + prioritized recommendations |
| SEO health check | `/seo-audit` | Technical + on-page findings + action plan |
| Comparison/vs page | `/competitor-alternatives` | Full page copy with comparison tables |

### Step 3: Human Review

**What AI gets right:**
- Structure and organization
- Comprehensive coverage of topics
- Consistent formatting
- Volume of variations (headlines, CTAs, hooks)

**What humans must check:**
- [ ] Factual accuracy (AI fabricates stats and testimonials)
- [ ] Brand voice match (compare to existing client materials)
- [ ] Competitive claims (verify competitor info is current)
- [ ] Specificity (replace generic claims with real client data)
- [ ] Quality score (run through `/scoring/quality-scorer.md`, target 80+)

### Step 4: Client Delivery

Standard delivery format:
- Google Doc with copy organized by section
- Annotations explaining key choices (clients value this)
- 2-3 headline/CTA alternatives with rationale
- Meta title + description for SEO pages

---

## Skill Combinations

Some deliverables benefit from chaining skills:

| Project | Skill Chain |
|---------|------------|
| Full website redesign | `/page-cro` (audit current) → `/copywriting` (write new) |
| SEO content strategy | `/seo-audit` (find gaps) → `/programmatic-seo` (build pages) |
| Campaign launch | `/paid-ads` (strategy) → `/fb-ads-creative` (creative) → `/copywriting` (landing page) |
| Competitive content | `/competitor-alternatives` (comparison pages) → `/programmatic-seo` (scale to many competitors) |

---

## Measuring Impact

Track these to know if skills are working:

| Metric | Where to Find It | Target |
|--------|-----------------|--------|
| Hours saved per deliverable | Self-report | Compare to pre-AI baseline |
| Output quality score | Quality scorer rubric | 80+ consistently |
| Client satisfaction | Client feedback / NPS | Same or better than pre-AI |
| Delivery margin | Revenue - cost per project | Improving month over month |

---

## Common Pitfalls

**Don't skip the brief.** AI output is only as good as the input. "Write me a landing page" produces generic output. "Write a landing page for B2B SaaS targeting CFOs who are frustrated with manual reporting, CTA is book a demo, current page is [URL]" produces something useful.

**Don't skip human review.** AI will fabricate statistics, invent testimonials, and make claims about competitors that aren't true. Every output needs a human checking facts before it reaches a client.

**Don't over-polish in AI.** Get the structure and key messages from AI, then do final voice/tone adjustments manually. Trying to get AI to perfectly match brand voice takes longer than just editing.

**Don't use one skill for everything.** If you need CRO analysis, use `/page-cro`, not `/copywriting`. Each skill is optimized for its specific job.
