# Getting Started

Three ways to use these skills, from easiest to most powerful.

---

## Option 1: Claude.ai Projects (Recommended)

**Time to start: 2 minutes. No install needed.**

1. Go to [claude.ai](https://claude.ai) and sign in
2. Click **Projects** in the sidebar → **New Project**
3. Name it after the skill (e.g., "Copywriting")
4. Click **Project Instructions**
5. Open the skill you want from this repo (e.g., `.claude/skills/copywriting/SKILL.md`)
6. Find the **Claude.ai Quick Start** section at the top
7. Copy the entire block inside the code fence
8. Paste it into the Project Instructions field
9. Save
10. Start a new conversation in that project — the skill is now active

**Repeat for each skill you want.** You'll end up with projects like:
- "Copywriting"
- "Ad Creative"
- "SEO Audit"
- "Page CRO"

Every conversation in that project will have the skill loaded automatically.

### Tips

- **Be specific in your first message.** Don't just say "write copy." Say "Write homepage copy for [client]. Target audience: [who]. CTA: [what]. Here's their current site: [url]"
- **Iterate.** The first output is a draft. Ask for revisions: "Make the hero more specific to [industry]" or "Add a competitor comparison section."
- **Check quality gates.** Each skill has a quality checklist at the bottom. Run through it before delivery.

---

## Option 2: Paste-and-Go

**Time to start: 30 seconds. Works with any AI tool.**

1. Open any skill file from this repo
2. Find the **Claude.ai Quick Start** code block
3. Copy it
4. Open Claude.ai, ChatGPT, or any AI chat
5. Paste the block, then add your specific brief below it
6. Send

This works for one-off tasks. For repeated use, set up a Project (Option 1).

---

## Option 3: Claude Code

**Time to start: 5 minutes. Most powerful option.**

### Prerequisites
- [Node.js](https://nodejs.org) 18+
- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) CLI

### Setup

```bash
# Install Claude Code (if not already installed)
npm install -g @anthropic-ai/claude-code

# Clone this repo
git clone https://github.com/singlegrain-marketing/marketing-ai-playbooks.git
cd marketing-ai-playbooks

# Start Claude Code
claude
```

### Usage

Skills are available as slash commands:

```
/copywriting
/fb-ads-creative
/paid-ads
/programmatic-seo
/page-cro
/seo-audit
/competitor-alternatives
```

Type the command, then provide your brief in the same message or follow-up.

### Advantages of Claude Code

- Skills auto-load from the repo — no copying/pasting
- Can read files, URLs, and other context directly
- Can write output to files (HTML, CSV, JSON)
- Updates when you `git pull`

---

## Next Steps

1. **Pick your first skill** — whichever matches your next deliverable
2. **Run it on a real project** — not a test. Use real client context.
3. **Check output against quality gates** — every skill has a checklist
4. **Score it** — use the rubrics in `/scoring/` to rate output 0-100
5. **Iterate** — refine the output until it scores 80+
