---
name: fb-ads-creative
description: When the user wants to generate Facebook/Instagram ad creatives at scale. Also use when the user mentions "fb ads," "facebook ads," "ad creative," "hormozi style," "meta ads," "ad hooks," or "bulk ad variations."
---

# FB Ads Creative Generator

Generate Hormozi/School-style Facebook ad creatives at scale. Creates 60+ hooks and 180+ images in minutes.

---

## Claude.ai Quick Start

Copy this block into a Claude.ai Project (or paste at the start of any conversation):

```
You are an expert performance marketer specializing in Facebook/Instagram ad creative. Generate Hormozi/School-style ad campaigns at scale.

I'll provide a target avatar. For that avatar, generate:

1. **30 Pain Points** — specific, emotional, with numbers/timelines/measurable outcomes. Not generic motivation.

2. **60 Hooks** (2 per pain point) — scored by:
   - Specificity (1-10): How targeted is this to the avatar?
   - Emotional impact (1-10): How much does this sting?
   Format: "If you're a [avatar] who [specific pain]..."

3. **Top 10 Hooks** — flag the highest-scoring hooks for priority testing

4. **Ad Copy for Top 10** — for each top hook, write:
   - Primary text (125 chars)
   - Headline (40 chars)
   - Description (30 chars)
   - CTA recommendation

5. **Image Text** — for each top hook, provide the exact text for a white-background, black-text ad image (readable at mobile size)

Output as a table with columns: Hook ID, Hook Text, Specificity Score, Emotional Score, Primary Text, Headline, Image Text.

Quality rules:
- Every hook must be specific to this avatar (not generic motivational)
- Pain points must include numbers, timelines, or measurable outcomes
- No fabricated testimonials or claims
- All hooks must pass brand safety review

My avatar: [DESCRIBE YOUR TARGET AVATAR HERE]
```

---

## When to Use

Use this skill when the user wants to:
- Generate Facebook/Instagram ad creatives
- Create Hormozi-style text ads (white background, black text)
- Produce bulk ad variations for testing

## What It Produces

1. **Pain Points** — Specific, emotional pain points for the target avatar
2. **Hooks** — 2 hook variations per pain point, scored by specificity and emotional impact
3. **Ad Copy** — Primary text, headlines, descriptions for Meta Ads Manager
4. **Image Text** — Ready for text-on-white image generation (feed, story, landscape sizes)

---

## Parameters

- **Avatar** (required): Description of the target audience
  - Example: "Agency owners doing $50K-$200K MRR, struggling with lead generation"
- **Count** (optional): Number of pain points to generate (default: 30)
  - Each pain point generates 2 hooks = 60 hooks total

### Examples

```
Avatar: "Marketing agency owners doing $50K-$200K MRR who are stuck and can't break through to the next level"

Avatar: "SaaS founders at $500K ARR struggling with churn"

Avatar: "E-commerce store owners doing $1M+ revenue who are tired of rising ad costs"
```

---

## Hook Style Guide

### The Hormozi/School Formula

Pattern: "If you're a [specific avatar] who [specific pain with numbers]..."

**Strong hooks:**
- "If you're an agency owner who's been stuck at $50K MRR for 6+ months..."
- "If you're spending $10K+/mo on ads and your ROAS just dropped below 2x..."
- "If you've hired 3 media buyers in the last year and none of them lasted..."

**Weak hooks (avoid):**
- "If you want to grow your business..." (too generic)
- "If you're ready for success..." (motivational, not painful)
- "Are you tired of working hard?" (no specificity)

### Scoring Criteria

**Specificity (1-10)**
- 1-3: Generic, could apply to anyone
- 4-6: Somewhat targeted, mentions the industry
- 7-8: Includes specific numbers, timelines, or situations
- 9-10: Laser-targeted, avatar feels personally called out

**Emotional Impact (1-10)**
- 1-3: Mild inconvenience
- 4-6: Frustration, moderate pain
- 7-8: Fear, embarrassment, significant financial pain
- 9-10: Existential threat to business, identity-level pain

---

## Multi-Platform Adaptation

This skill generates Meta-style text ads. Adapt for other platforms:

| Platform | Creative Type | How to Adapt |
|----------|--------------|--------------|
| Meta (FB/IG) | Text-on-white (Hormozi style) | Use as-is |
| Meta (FB/IG) | Image-based ads | Add visuals to top hooks |
| Google | Responsive display ads | Adapt hooks to 90-char headlines + 30-char descriptions |
| LinkedIn | Sponsored content | Adapt hooks to professional tone |
| TikTok | Video scripts | Use hooks as opening lines |

---

## Quality Gates

Before uploading to ad platforms:

- [ ] All hooks are specific to the avatar (not generic motivational)
- [ ] Pain points include numbers, timelines, or measurable outcomes
- [ ] Top 10 hooks manually reviewed for brand safety
- [ ] No fabricated testimonials or claims in ad copy
- [ ] Ad copy fits character limits (primary: 125, headline: 40, description: 30)
- [ ] Image text is readable at mobile size (test at 375px width)

---

## Testing Strategy

### Week 1: Validate hooks
- Upload top 10 hooks as separate ads
- $5-10/day per ad
- Kill anything below 1% CTR after 1,000 impressions

### Week 2: Scale winners
- Take top 3 CTR performers
- Create 5 variations of each (change one element)
- Increase budget on winners

### Week 3: Full campaign
- Expand winning hooks to all 3 sizes (feed, story, landscape)
- Add retargeting audiences
- Test against manually-created ads (measure CTR and CPA difference)

---

## Output Format

```
Campaign: [Avatar Name] - [Date]
Pain Points: [Count]
Hooks: [Count]

## Top 10 Hooks

| # | Hook | Spec | Emot | Primary Text | Headline | Image Text |
|---|------|------|------|-------------|----------|------------|
| 1 | ...  | 9    | 8    | ...         | ...      | ...        |

## All Hooks

[Full table of 60 hooks with scores]

## Upload Instructions
1. Download hooks.csv
2. Go to Meta Ads Manager → Bulk Upload
3. Select campaign and ad set
4. Upload CSV
5. Review and publish
```

---

## Related Skills

- **paid-ads**: For full campaign strategy, targeting, and optimization
- **copywriting**: For landing page copy that converts ad traffic
- **page-cro**: For optimizing post-click conversion rates
- **ab-test-setup**: To properly test ad variations
