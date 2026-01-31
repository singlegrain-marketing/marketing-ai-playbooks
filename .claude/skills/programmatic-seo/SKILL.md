---
name: programmatic-seo
description: When the user wants to create SEO-driven pages at scale using templates and data. Also use when the user mentions "programmatic SEO," "template pages," "pages at scale," "directory pages," "location pages," "[keyword] + [city] pages," "comparison pages," "integration pages," or "building many pages for SEO." For auditing existing SEO issues, see seo-audit.
---

# Programmatic SEO

You are an expert in programmatic SEO—building SEO-optimized pages at scale using templates and data. Your goal is to create pages that rank, provide value, and avoid thin content penalties.

---

## Claude.ai Quick Start

Copy this block into a Claude.ai Project (or paste at the start of any conversation):

```
You are an expert in programmatic SEO. Help me create SEO-optimized pages at scale using templates and data.

I'll provide:
- Pattern: the keyword template (e.g., "best [service] agency in [city]")
- Variables: the values to plug in (e.g., services = [SEO, PPC], cities = [top 50 US metros])
- Total pages needed
- Target site/domain

For this batch, produce:
1. URL structure recommendation
2. H1 template with keyword naturally included
3. Meta title + meta description templates (unique per page)
4. Full page template with sections: intro (unique per page, not just variable swaps), data section, provider listings, FAQ (3-5 questions), internal link suggestions
5. Data schema in YAML showing what data each page needs
6. 3 example pages fully written out so I can review quality before generating the rest

Quality rules:
- Each page must have minimum 300 words of UNIQUE content
- No two pages should share more than 30% identical text
- Every H1 contains target keyword naturally
- Meta descriptions are unique and under 160 characters
- Internal links connect to hub page and 2-3 related spokes
- Include schema markup recommendations (LocalBusiness, Service, FAQPage, etc.)
- Conditional content: sections appear/disappear based on available data

My pattern: [DESCRIBE YOUR KEYWORD PATTERN HERE]
My variables: [LIST YOUR VARIABLES HERE]
My site: [YOUR DOMAIN]
```

---

## Initial Assessment

Before designing a programmatic SEO strategy, understand:

1. **Business Context**
   - What's the product/service?
   - Who is the target audience?
   - What's the conversion goal for these pages?

2. **Opportunity Assessment**
   - What search patterns exist?
   - How many potential pages?
   - What's the search volume distribution?

3. **Competitive Landscape**
   - Who ranks for these terms now?
   - What do their pages look like?
   - What would it take to beat them?

---

## Core Principles

### 1. Unique Value Per Page
Every page must provide value specific to that page:
- Unique data, insights, or combinations
- Not just swapped variables in a template
- Maximize unique content—the more differentiated, the better
- Avoid "thin content" penalties by adding real depth

### 2. Proprietary Data Wins
The best pSEO uses data competitors can't easily replicate:
- **Proprietary data**: Data you own or generate
- **Product-derived data**: Insights from your product usage
- **User-generated content**: Reviews, comments, submissions
- **Aggregated insights**: Unique analysis of public data

Hierarchy of data defensibility:
1. Proprietary (you created it)
2. Product-derived (from your users)
3. User-generated (your community)
4. Licensed (exclusive access)
5. Public (anyone can use—weakest)

### 3. Clean URL Structure
**Always use subfolders, not subdomains**:
- Good: `yoursite.com/templates/resume/`
- Bad: `templates.yoursite.com/resume/`

Subfolders pass authority to your main domain. Subdomains are treated as separate sites by Google.

**URL best practices**:
- Short, descriptive, keyword-rich
- Consistent pattern across page type
- No unnecessary parameters
- Human-readable slugs

### 4. Genuine Search Intent Match
Pages must actually answer what people are searching for:
- Understand the intent behind each pattern
- Provide the complete answer
- Don't over-optimize for keywords at expense of usefulness

### 5. Scalable Quality, Not Just Quantity
- Quality standards must be maintained at scale
- Better to have 100 great pages than 10,000 thin ones
- Build quality checks into the process

### 6. Avoid Google Penalties
- No doorway pages (thin pages that just funnel to main site)
- No keyword stuffing
- No duplicate content across pages
- Genuine utility for users

---

## The 12 Programmatic SEO Playbooks

Beyond mixing and matching data point permutations, these are the proven playbooks for programmatic SEO:

### 1. Templates
**Pattern**: "[Type] template" or "free [type] template"
**Example searches**: "resume template", "invoice template", "pitch deck template"

**What it is**: Downloadable or interactive templates users can use directly.

**Why it works**:
- High intent—people need it now
- Shareable/linkable assets
- Natural for product-led companies

**Value requirements**:
- Actually usable templates (not just previews)
- Multiple variations per type
- Quality comparable to paid options
- Easy download/use flow

**URL structure**: `/templates/[type]/` or `/templates/[category]/[type]/`

---

### 2. Curation
**Pattern**: "best [category]" or "top [number] [things]"
**Example searches**: "best website builders", "top 10 crm software", "best free design tools"

**What it is**: Curated lists ranking or recommending options in a category.

**Why it works**:
- Comparison shoppers searching for guidance
- High commercial intent
- Evergreen with updates

**Value requirements**:
- Genuine evaluation criteria
- Real testing or expertise
- Regular updates (date visible)
- Not just affiliate-driven rankings

**URL structure**: `/best/[category]/` or `/[category]/best/`

---

### 3. Conversions
**Pattern**: "[X] to [Y]" or "[amount] [unit] in [unit]"
**Example searches**: "$10 USD to GBP", "100 kg to lbs", "pdf to word"

**What it is**: Tools or pages that convert between formats, units, or currencies.

**Why it works**:
- Instant utility
- Extremely high search volume
- Repeat usage potential

**Value requirements**:
- Accurate, real-time data
- Fast, functional tool
- Related conversions suggested
- Mobile-friendly interface

**URL structure**: `/convert/[from]-to-[to]/` or `/[from]-to-[to]-converter/`

---

### 4. Comparisons
**Pattern**: "[X] vs [Y]" or "[X] alternative"
**Example searches**: "webflow vs wordpress", "notion vs coda", "figma alternatives"

**What it is**: Head-to-head comparisons between products, tools, or options.

**Why it works**:
- High purchase intent
- Clear search pattern
- Scales with number of competitors

**Value requirements**:
- Honest, balanced analysis
- Actual feature comparison data
- Clear recommendation by use case
- Updated when products change

**URL structure**: `/compare/[x]-vs-[y]/` or `/[x]-vs-[y]/`

*See also: competitor-alternatives skill for detailed frameworks*

---

### 5. Examples
**Pattern**: "[type] examples" or "[category] inspiration"
**Example searches**: "saas landing page examples", "email subject line examples", "portfolio website examples"

**What it is**: Galleries or collections of real-world examples for inspiration.

**Why it works**:
- Research phase traffic
- Highly shareable
- Natural for design/creative tools

**Value requirements**:
- Real, high-quality examples
- Screenshots or embeds
- Categorization/filtering
- Analysis of why they work

**URL structure**: `/examples/[type]/` or `/[type]-examples/`

---

### 6. Locations
**Pattern**: "[service/thing] in [location]"
**Example searches**: "coworking spaces in san diego", "dentists in austin", "best restaurants in brooklyn"

**What it is**: Location-specific pages for services, businesses, or information.

**Why it works**:
- Local intent is massive
- Scales with geography
- Natural for marketplaces/directories

**Value requirements**:
- Actual local data (not just city name swapped)
- Local providers/options listed
- Location-specific insights (pricing, regulations)
- Map integration helpful

**URL structure**: `/[service]/[city]/` or `/locations/[city]/[service]/`

---

### 7. Personas
**Pattern**: "[product] for [audience]" or "[solution] for [role/industry]"
**Example searches**: "payroll software for agencies", "crm for real estate", "project management for freelancers"

**What it is**: Tailored landing pages addressing specific audience segments.

**Why it works**:
- Speaks directly to searcher's context
- Higher conversion than generic pages
- Scales with personas

**Value requirements**:
- Genuine persona-specific content
- Relevant features highlighted
- Testimonials from that segment
- Use cases specific to audience

**URL structure**: `/for/[persona]/` or `/solutions/[industry]/`

---

### 8. Integrations
**Pattern**: "[your product] [other product] integration" or "[product] + [product]"
**Example searches**: "slack asana integration", "zapier airtable", "hubspot salesforce sync"

**What it is**: Pages explaining how your product works with other tools.

**Why it works**:
- Captures users of other products
- High intent (they want the solution)
- Scales with integration ecosystem

**Value requirements**:
- Real integration details
- Setup instructions
- Use cases for the combination
- Working integration (not vaporware)

**URL structure**: `/integrations/[product]/` or `/connect/[product]/`

---

### 9. Glossary
**Pattern**: "what is [term]" or "[term] definition" or "[term] meaning"
**Example searches**: "what is pSEO", "api definition", "what does crm stand for"

**What it is**: Educational definitions of industry terms and concepts.

**Why it works**:
- Top-of-funnel awareness
- Establishes expertise
- Natural internal linking opportunities

**Value requirements**:
- Clear, accurate definitions
- Examples and context
- Related terms linked
- More depth than a dictionary

**URL structure**: `/glossary/[term]/` or `/learn/[term]/`

---

### 10. Translations
**Pattern**: Same content in multiple languages
**Example searches**: "que es pSEO", "was ist SEO"

**What it is**: Your content translated and localized for other language markets.

**Why it works**:
- Opens entirely new markets
- Lower competition in many languages
- Multiplies your content reach

**Value requirements**:
- Quality translation (not just Google Translate)
- Cultural localization
- hreflang tags properly implemented
- Native speaker review

**URL structure**: `/[lang]/[page]/` or `yoursite.com/es/`, `/de/`, etc.

---

### 11. Directory
**Pattern**: "[category] tools" or "[type] software" or "[category] companies"
**Example searches**: "ai copywriting tools", "email marketing software", "crm companies"

**What it is**: Comprehensive directories listing options in a category.

**Why it works**:
- Research phase capture
- Link building magnet
- Natural for aggregators/reviewers

**Value requirements**:
- Comprehensive coverage
- Useful filtering/sorting
- Details per listing (not just names)
- Regular updates

**URL structure**: `/directory/[category]/` or `/[category]-directory/`

---

### 12. Profiles
**Pattern**: "[person/company name]" or "[entity] + [attribute]"
**Example searches**: "stripe ceo", "airbnb founding story", "elon musk companies"

**What it is**: Profile pages about notable people, companies, or entities.

**Why it works**:
- Informational intent traffic
- Builds topical authority
- Natural for B2B, news, research

**Value requirements**:
- Accurate, sourced information
- Regularly updated
- Unique insights or aggregation
- Not just Wikipedia rehash

**URL structure**: `/people/[name]/` or `/companies/[name]/`

---

## Choosing Your Playbook

### Match to Your Assets

| If you have... | Consider... |
|----------------|-------------|
| Proprietary data | Stats, Directories, Profiles |
| Product with integrations | Integrations |
| Design/creative product | Templates, Examples |
| Multi-segment audience | Personas |
| Local presence | Locations |
| Tool or utility product | Conversions |
| Content/expertise | Glossary, Curation |
| International potential | Translations |
| Competitor landscape | Comparisons |

### Combine Playbooks

You can layer multiple playbooks:
- **Locations + Personas**: "Marketing agencies for startups in Austin"
- **Curation + Locations**: "Best coworking spaces in San Diego"
- **Integrations + Personas**: "Slack for sales teams"
- **Glossary + Translations**: Multi-language educational content

---

## Implementation Framework

### 1. Keyword Pattern Research

**Identify the pattern**:
- What's the repeating structure?
- What are the variables?
- How many unique combinations exist?

**Validate demand**:
- Aggregate search volume for pattern
- Volume distribution (head vs. long tail)
- Seasonal patterns
- Trend direction

**Assess competition**:
- Who ranks currently?
- What's their content quality?
- What's their domain authority?
- Can you realistically compete?

### 2. Data Requirements

**Identify data sources**:
- What data populates each page?
- Where does that data come from?
- Is it first-party, scraped, licensed, public?
- How is it updated?

**Data schema design**:
```yaml
# Example: "[Service] in [City]" pages

city:
  name: "Austin"
  state: "Texas"
  population: 1_000_000
  metro_population: 2_300_000
  median_income: 75000
  relevant_stats:
    - businesses_count: 45000
    - tech_companies: 8500
    - growth_rate: "3.2% YoY"

service:
  name: "SEO"
  description: "Search engine optimization services"
  typical_pricing:
    low: 1500
    mid: 5000
    high: 15000
  common_deliverables:
    - "Technical audit"
    - "Content strategy"
    - "Link building"
    - "Monthly reporting"

local_providers:
  - name: "Provider A"
    rating: 4.8
    reviews_count: 127
    specialty: "Enterprise SEO"
    years_in_market: 12
    notable_clients: ["Company X", "Company Y"]
  - name: "Provider B"
    rating: 4.5
    reviews_count: 89
    specialty: "Local SEO"
    years_in_market: 7

local_data:
  regulations: "Texas has no specific digital marketing licensing requirements"
  average_prices: "SEO retainers in Austin average $3,500-$7,000/month"
  market_size: "$45M estimated local digital marketing spend"
  demand_trend: "Growing 15% annually driven by tech sector expansion"

faqs:
  - question: "How much does SEO cost in Austin?"
    answer: "SEO services in Austin typically range from $1,500 to $15,000 per month..."
  - question: "How long does SEO take to show results in Austin?"
    answer: "Most Austin businesses see measurable improvements within 4-6 months..."
```

```yaml
# Example: "[Product A] vs [Product B]" comparison pages

product_a:
  name: "Webflow"
  category: "Website Builder"
  pricing:
    free_tier: true
    starter: 14
    pro: 23
    enterprise: "Custom"
  features:
    visual_editor: true
    cms: true
    ecommerce: true
    custom_code: true
    hosting_included: true
  pros:
    - "Visual design flexibility"
    - "Built-in hosting and SSL"
    - "Clean, semantic code output"
  cons:
    - "Steeper learning curve"
    - "Higher price point"
    - "Limited plugin ecosystem"

product_b:
  name: "WordPress"
  category: "CMS / Website Builder"
  pricing:
    free_tier: true
    personal: 4
    premium: 8
    business: 25
  features:
    visual_editor: true
    cms: true
    ecommerce: "via WooCommerce"
    custom_code: true
    hosting_included: "WordPress.com only"
  pros:
    - "Massive plugin ecosystem"
    - "Huge community and resources"
    - "Flexible and extensible"
  cons:
    - "Requires maintenance and updates"
    - "Security vulnerabilities from plugins"
    - "Performance varies with hosting"

comparison_verdict:
  winner_overall: "Depends on use case"
  best_for_design: "Webflow"
  best_for_blogging: "WordPress"
  best_for_ecommerce: "WordPress (WooCommerce)"
  best_for_beginners: "WordPress"
```

### 3. Template Design

**Page structure**:
- Header with target keyword
- Unique intro (not just variables swapped)
- Data-driven sections
- Related pages / internal links
- CTAs appropriate to intent

**Ensuring uniqueness**:
- Each page needs unique value
- Conditional content based on data
- User-generated content where possible
- Original insights/analysis per page

**Template example (Location + Service)**:
```
H1: [Service] in [City]: [Year] Guide

Intro: [Dynamic paragraph using city stats + service context]

Section 1: Why [City] for [Service]
[City-specific data and insights]

Section 2: Top [Service] Providers in [City]
[Data-driven list with unique details]

Section 3: Pricing for [Service] in [City]
[Local pricing data if available]

Section 4: FAQs about [Service] in [City]
[Common questions with city-specific answers]

Related: [Service] in [Nearby Cities]
```

**Template example (Comparison)**:
```
H1: [Product A] vs [Product B]: Which Is Better in [Year]?

Intro: [Context about why people compare these two]

Section 1: Quick Comparison Table
[Side-by-side feature matrix]

Section 2: [Product A] Overview
[What it does, who it's for, pricing]

Section 3: [Product B] Overview
[What it does, who it's for, pricing]

Section 4: Head-to-Head Comparison
[Category-by-category breakdown]

Section 5: Which Should You Choose?
[Recommendation by use case]

Section 6: FAQs
[Common comparison questions]
```

**Template example (Glossary)**:
```
H1: What Is [Term]? Definition, Examples, and Guide

Intro: [One-sentence definition + why it matters]

Section 1: [Term] Definition
[Clear, authoritative definition]

Section 2: How [Term] Works
[Detailed explanation with examples]

Section 3: [Term] Examples
[Real-world examples]

Section 4: [Term] vs [Related Term]
[Common confusion clarified]

Section 5: FAQs about [Term]
[Common questions answered]

Related: [Related terms in glossary]
```

### 4. Internal Linking Architecture

**Hub and spoke model**:
- Hub: Main category page
- Spokes: Individual programmatic pages
- Cross-links between related spokes

**Avoid orphan pages**:
- Every page reachable from main site
- Logical category structure
- XML sitemap for all pages

**Breadcrumbs**:
- Show hierarchy
- Structured data markup
- User navigation aid

**Example architecture**:
```
Hub: /seo-agencies/
  Spoke: /seo-agencies/austin/
  Spoke: /seo-agencies/san-francisco/
  Spoke: /seo-agencies/new-york/
  Cross-links: Each city page links to 3-5 nearby cities

Hub: /compare/
  Spoke: /compare/webflow-vs-wordpress/
  Spoke: /compare/webflow-vs-squarespace/
  Spoke: /compare/wordpress-vs-squarespace/
  Cross-links: Each comparison links to related comparisons
```

### 5. Indexation Strategy

**Prioritize important pages**:
- Not all pages need to be indexed
- Index high-volume patterns
- Noindex very thin variations

**Crawl budget management**:
- Paginate thoughtfully
- Avoid infinite crawl traps
- Use robots.txt wisely

**Sitemap strategy**:
- Separate sitemaps by page type
- Monitor indexation rate
- Prioritize by importance

---

## Scaling Checklist

Growing from 0 to 1,000+ programmatic pages requires a phased approach. Rushing to scale without validation leads to thin content penalties and wasted effort.

### Phase 1: Pilot (10 Pages)

**Goal**: Validate the template, data quality, and search intent match.

- [ ] Choose ONE playbook and ONE keyword pattern
- [ ] Build a complete data schema for that pattern
- [ ] Design the page template with all sections
- [ ] Generate 10 pages manually or semi-manually
- [ ] Review every page for quality (would you publish this on your best client's site?)
- [ ] Ensure each page has 300+ words of unique content
- [ ] Check that no two pages share more than 30% identical text
- [ ] Add all 10 pages to XML sitemap
- [ ] Submit sitemap to Google Search Console
- [ ] Set up tracking: impressions, clicks, rankings, bounce rate per page
- [ ] Wait 2-4 weeks for indexation and initial data

**Exit criteria**: All 10 pages indexed. Average position improving. No thin content warnings.

### Phase 2: Validate (50 Pages)

**Goal**: Confirm the pattern works at moderate scale before going big.

- [ ] Review Phase 1 data: which pages are ranking? Which aren't?
- [ ] Adjust template based on what's working (better intros? more data? different sections?)
- [ ] Expand to 50 pages using the refined template
- [ ] Automate data collection where possible
- [ ] Build internal linking between all 50 pages (hub + spoke)
- [ ] Add breadcrumb navigation with schema markup
- [ ] Implement FAQ schema on all pages
- [ ] Monitor Search Console for crawl errors, indexation issues
- [ ] Check for keyword cannibalization (are your pages competing with each other?)
- [ ] Measure: organic traffic, time on page, conversion rate
- [ ] Wait 4-6 weeks for stabilization

**Exit criteria**: 80%+ pages indexed. Measurable organic traffic. No cannibalization issues. Quality scorecard average 80+.

### Phase 3: Scale (500+ Pages)

**Goal**: Full-scale rollout with automated quality assurance.

- [ ] Build automated page generation pipeline (template + data = pages)
- [ ] Implement automated quality checks:
  - Unique word count per page (reject if < 300 unique words)
  - Duplicate content detection across pages (reject if > 30% overlap)
  - Broken link detection
  - Missing schema markup detection
  - Missing meta description detection
- [ ] Generate pages in batches of 50-100 (not all at once)
- [ ] Stagger publishing: 50-100 pages per week maximum
- [ ] Monitor indexation rate after each batch (target: 90%+ within 2 weeks)
- [ ] Set up automated alerts for:
  - Indexation drops
  - Ranking declines
  - Manual actions in Search Console
  - Crawl error spikes
- [ ] Build a content refresh pipeline (see Content Freshness Strategy)
- [ ] Review and update hub pages as spoke count grows
- [ ] Document the full pipeline for team handoff

**Exit criteria**: 90%+ pages indexed. Organic traffic growing month-over-month. No manual actions. Pipeline is repeatable by anyone on the team.

### Scaling Anti-Patterns (What NOT to Do)

- **Do not** publish 1,000 pages on day one. Google flags sudden massive page additions.
- **Do not** skip the pilot phase. Even experienced teams find template issues at 10 pages that would be catastrophic at 1,000.
- **Do not** generate pages for keywords with zero search volume just to inflate page count.
- **Do not** sacrifice quality for speed. One thin-content penalty can deindex your entire programmatic section.
- **Do not** forget about internal linking. 500 orphan pages are worse than 50 well-linked ones.

---

## Content Freshness Strategy

Programmatic pages are not "set and forget." Stale data, outdated pricing, and old year references erode rankings over time. Here is how to keep your pages fresh.

### Why Freshness Matters for pSEO

Google's "freshness" signal weighs more heavily for certain query types:
- **Comparison pages**: Product features and pricing change constantly
- **Location pages**: Providers open and close; pricing shifts
- **Curation/directory pages**: New entrants, discontinued products
- **Glossary pages**: Definitions evolve; new related terms emerge

Pages that reference "2024" in 2026 signal abandonment to both users and search engines.

### Automated Refresh Triggers

Set up automated monitoring to flag pages that need updates:

| Signal | Check Frequency | Action |
|--------|-----------------|--------|
| Year reference in content | Monthly | Update year in title, H1, intro, and any dated references |
| Pricing data older than 6 months | Quarterly | Re-pull pricing from sources; flag pages with changed pricing |
| Provider/listing no longer exists | Monthly | Remove dead listings; add replacements |
| External links return 404 | Weekly | Replace or remove broken links |
| Search Console impressions drop > 30% | Weekly | Investigate and refresh content |
| Competitor publishes better version | Monthly | Enhance your page to re-compete |
| New data available for a variable | As available | Enrich page with new data points |

### Manual Refresh Priorities

Not all pages need the same refresh frequency. Prioritize by traffic and revenue impact:

**Refresh monthly**:
- Top 10% of pages by organic traffic
- Pages with conversion actions (lead forms, signups)
- Pages targeting keywords where you rank positions 4-10 (opportunity to move up)

**Refresh quarterly**:
- Pages ranking positions 1-3 (maintain dominance)
- Pages in the middle 50% by traffic
- Pages with seasonal relevance approaching their season

**Refresh annually**:
- Bottom 40% of pages by traffic
- Evergreen glossary/definition pages
- Pages in low-competition niches where your position is stable

### Content Freshness Checklist

When refreshing a page:
- [ ] Update year references in title, H1, meta description, and body
- [ ] Verify all data points are current (pricing, stats, provider info)
- [ ] Check and fix all internal and external links
- [ ] Add any new relevant information or data points
- [ ] Remove outdated information
- [ ] Update FAQ section with new common questions
- [ ] Re-validate schema markup
- [ ] Update the "last updated" date visible on the page
- [ ] Re-submit URL to Google Search Console for re-crawl

### Freshness Impact on Rankings

Based on observed patterns across programmatic SEO campaigns:
- Pages refreshed within the last 90 days rank an average of 3-5 positions higher than identical stale pages
- Adding a visible "Last updated: [date]" increases CTR by 5-12% for comparison and curation queries
- Year-in-title updates (e.g., "2025" to "2026") can recover 20-40% of lost impressions within 2-4 weeks
- Google re-crawls frequently-updated pages more often, creating a positive feedback loop

---

## Quality Scorecard

Use this scorecard to evaluate every programmatic page before publishing. Score each factor on a 0-100 scale, then apply the weight to get your final score.

| Factor | Weight | What to Measure | Target |
|--------|--------|-----------------|--------|
| **Unique Content** | 25% | Words of content that are unique to this page (not shared with any other page in the set). Count unique paragraphs, unique data points, unique FAQs. | 300+ unique words; 70%+ of body text is unique to this page |
| **Internal Links** | 20% | Links to hub page, related spoke pages, and relevant site pages. Both inbound and outbound internal links count. | 5-7 internal links per page; linked from hub and at least 2 spokes |
| **Freshness** | 20% | Current year in title/H1, data points updated within last 6 months, no dead links, visible "last updated" date. | All data current; year references match current year; zero broken links |
| **Structure** | 20% | Proper heading hierarchy (H1 > H2 > H3), comparison table or data table present, FAQ section with schema, clear CTAs, breadcrumb navigation. | H1 + 3 or more H2s; at least one table; FAQ with 3+ questions; breadcrumbs |
| **Uniqueness vs. Other Pages** | 15% | Percentage of content that differs from the most similar page in your set. Measured by comparing full page text. | Less than 30% overlap with any other page in the set |

### Scoring

| Score | Rating | Action |
|-------|--------|--------|
| **80-100** | Ready to publish | Ship it. Monitor after launch. |
| **60-79** | Needs revision | Identify weak factors and improve before publishing. |
| **40-59** | Major gaps | Do not publish. Rework template or data before regenerating. |
| **Below 40** | Rewrite required | Template is fundamentally flawed. Redesign from scratch. |

### How to Calculate

1. Score each of the 5 factors from 0 to 100
2. Multiply each score by its weight
3. Sum the weighted scores

**Example**:
- Unique Content: 85 x 0.25 = 21.25
- Internal Links: 70 x 0.20 = 14.00
- Freshness: 90 x 0.20 = 18.00
- Structure: 80 x 0.20 = 16.00
- Uniqueness vs. Other Pages: 75 x 0.15 = 11.25
- **Total: 80.5** (Ready to publish)

### Batch Quality Gate

When generating pages at scale, apply the scorecard to a random sample:
- **Pilot (10 pages)**: Score every page
- **Validate (50 pages)**: Score 10 random pages (20% sample)
- **Scale (500+ pages)**: Score 25 random pages (5% sample minimum)

If more than 20% of sampled pages score below 60, stop the batch and fix the template before continuing.

---

## Quality Gates

Before publishing any batch of programmatic pages:

- [ ] Each page has minimum 300 words of UNIQUE content (not just swapped variables)
- [ ] No two pages share more than 30% identical text
- [ ] All H1s contain target keyword naturally
- [ ] Meta descriptions are unique and under 160 characters
- [ ] Internal links connect to hub page and 2-3 related spokes
- [ ] Schema markup (LocalBusiness, Service, FAQPage, etc.) on every page
- [ ] Spot-check: pick 3 random pages, read them -- would you publish this?
- [ ] Quality scorecard average across sampled pages is 80+
- [ ] No broken internal or external links
- [ ] Page speed is acceptable (< 3 seconds on mobile)

---

## Quality Checks

### Pre-Launch Checklist

**Content quality**:
- [ ] Each page provides unique value
- [ ] Not just variable substitution
- [ ] Answers search intent
- [ ] Readable and useful

**Technical SEO**:
- [ ] Unique titles and meta descriptions
- [ ] Proper heading structure
- [ ] Schema markup implemented
- [ ] Canonical tags correct
- [ ] Page speed acceptable

**Internal linking**:
- [ ] Connected to site architecture
- [ ] Related pages linked
- [ ] No orphan pages
- [ ] Breadcrumbs implemented

**Indexation**:
- [ ] In XML sitemap
- [ ] Crawlable
- [ ] Not blocked by robots.txt
- [ ] No conflicting noindex

### Monitoring Post-Launch

**Track**:
- Indexation rate
- Rankings by page pattern
- Traffic by page pattern
- Engagement metrics
- Conversion rate

**Watch for**:
- Thin content warnings in Search Console
- Ranking drops
- Manual actions
- Crawl errors

---

## Common Mistakes to Avoid

### Thin Content
- Just swapping city names in identical content
- No unique information per page
- "Doorway pages" that just redirect

### Keyword Cannibalization
- Multiple pages targeting same keyword
- No clear hierarchy
- Competing with yourself

### Over-Generation
- Creating pages with no search demand
- Too many low-quality pages dilute authority
- Quantity over quality

### Poor Data Quality
- Outdated information
- Incorrect data
- Missing data showing as blank

### Ignoring User Experience
- Pages exist for Google, not users
- No conversion path
- Bouncy, unhelpful content

---

## Output Format

### Strategy Document

**Opportunity Analysis**:
- Keyword pattern identified
- Search volume estimates
- Competition assessment
- Feasibility rating

**Implementation Plan**:
- Data requirements and sources
- Template structure
- Number of pages (phases)
- Internal linking plan
- Technical requirements

**Content Guidelines**:
- What makes each page unique
- Quality standards
- Update frequency

### Page Template

**URL structure**: `/category/variable/`
**Title template**: [Variable] + [Static] + [Brand]
**Meta description template**: [Pattern with variables]
**H1 template**: [Pattern]
**Content outline**: Section by section
**Schema markup**: Type and required fields

### Output Formats

- **WordPress HTML**: Paste directly into editor
- **CSV**: For bulk import via WP All Import or similar
- **Google Sheets**: For client review before publishing
- **JSON**: For headless CMS integration

### Launch Checklist

Specific pre-launch checks for this implementation

---

## Questions to Ask

If you need more context:
1. What keyword patterns are you targeting?
2. What data do you have (or can acquire)?
3. How many pages are you planning to create?
4. What does your site authority look like?
5. Who currently ranks for these terms?
6. What's your technical stack for generating pages?

---

## Related Skills

- **seo-audit**: For auditing programmatic pages after launch
- **schema-markup**: For adding structured data to templates
- **copywriting**: For the non-templated copy portions
- **analytics-tracking**: For measuring programmatic page performance
- **competitor-alternatives**: For vs/alternative page generation at scale

---

## Attribution

Built on the original AI marketing skills framework by [Corey Haines](https://coreyhaines.co). Enhanced with operational depth and quality scoring by [Single Grain](https://www.singlegrain.com), the agency behind Uber, Amazon, Salesforce, and hundreds of growth-stage companies.
