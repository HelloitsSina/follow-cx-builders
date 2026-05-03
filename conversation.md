# follow-cx-builders — Full Conversation Log
> Exported: 2026-05-03
> A CX Team Lead building a personal strategy learning system from following 16 CX experts.

---

## Origin: The Image

Started with a screenshot of a LinkedIn post: "16 Experts To Follow for Customer Support" by Anastasiia Belinska, featuring experts across 4 categories:
- **Customer Support & Experience**: Jeff Toister, Dan Gingiss, Adrian Swinscoe, Shep Hyken
- **B2B Support / Systems / Scaling**: Daphne Costa Lopes, Justin Chappell, Carly Agar, Lisa Stoner
- **Soft Skills & Communication**: Chris Voss, Celeste Headlee, Vanessa Van Edwards, Nate Brown
- **Support, Loyalty & Trends**: Adam Topore, Gadi Shamia, Bill Quiseng, Anika Zubair

---

## Key Decisions Made

### Naming
- Considered 3 names: `follow-cx-builders`, `cx-signal`, `cx-practitioner-kit`
- **Chose: `follow-cx-builders`** — emphasises active research and experimentation

### Focus (not content sharing)
Clarified this skill is for **learning and applying CX strategy**, not for LinkedIn sharing.

Two core problems to solve:
1. Know theory but lack structured framework to organise thinking
2. No system to track what was learned vs what was actually applied

Two desired outputs:
1. A personal CX strategy framework
2. A continuously-updated CX learning system / knowledge base

### Reference: Zara Zhang's Follow Builders
- Zara Zhang (AI/tech, not CX) built a tool that monitors 25 builders across X, YouTube, blogs
- Pushes daily/weekly digests — **signal filtering, not content aggregation**
- Philosophy: "Follow people who build and have original opinions, not influencers who regurgitate"
- Key difference: her tool is input-focused; this skill is learning + application focused

---

## The 5 Pillars Framework

Synthesised from 16 experts into 5 strategic dimensions:

| Pillar | Experts | Core tension |
|--------|---------|--------------|
| **Consistency** | Hyken, Toister, Stoner | WOW vs reliable baseline |
| **Emotion & Tension** | Voss, Headlee, Van Edwards, Brown | Empathy vs efficiency |
| **Scale & Systems** | Lopes, Chappell, Agar | Structure before scale |
| **Voice → Action** | Swinscoe, Gingiss, Quiseng | Data vs action |
| **People & Culture** | Topore, Zubair, Shamia | Human vs AI |

**Key cross-expert conflicts to resolve:**
- Consistency vs WOW (Hyken vs Gingiss)
- Empathy vs Efficiency (Voss/Brown vs Agar/Stoner)
- Proactive vs Reactive (Agar vs Toister)
- Human vs AI (Shamia vs Headlee)

---

## Tool Evolution

### v1 — CX Follow Builder
Full dashboard with 16 expert cards, content generator for LinkedIn posts.
**Problem:** Too focused on sharing, not learning.

### v2 — Digest-first (inspired by Zara)
One card at a time. Expert → insight → why → reflect question → write your take → save + next.
**Improvement:** Light start, sequential, no information overload.

### v3 — Structured Reflection
Added 3 input fields to each digest card:
- **My Take** — agree / disagree / what would you add?
- **Apply to my work** — what does this mean for my team right now?
- **Action** — one specific thing, this week

### v4 — English + Source Links + Notion Workflow
- All 16 insights rewritten in English
- Source links on every card (↗ opens original article)
- New `→ notion` tab: step-by-step guide to connect to Notion API
- Once credentials pasted: button changes to "save + sync →", auto-creates rows in Notion

**Data model for Notion (9 fields):**
```
Name (Title) | Pillar (Select) | Insight (Text) | Source (URL)
My Take (Text) | Apply (Text) | Action (Text) | Date (Date) | Status (Select)
```

---

## Notion Integration

### What was created in your Notion CX Area

**CX Area** (`355efc9a-5ab9-802c-bc0f-c82eac193525`)
→ Located under Areas Database → Command Center

**1. follow-cx-builders — Learning System** (Type: Research)
- 16 experts organised by pillar with source links
- My Emerging Framework section (Operating Principle, beliefs, tensions, blind spots)
- Weekly review template embedded

**2. CX Weekly Review — [Week of ...]** (Type: Notes)
- Duplicate each Friday, rename with date
- Digest recap table, reflection prompts, framework update section

**3. CX Weekly Digest — Week of 03 May 2026** (Type: Research)
- First live weekly digest, 8 reads from: Shep Hyken, Adrian Swinscoe, Gadi Shamia, Dan Gingiss / Bill Quiseng
- Format: who the expert is → what they said → why it matters for a CX Manager → one question

### Weekly Digest Format (max 10 reads)
Each item contains:
- **Who** — plain English intro to the expert
- **What** — what they said, jargon explained in parentheses
- **Why it matters for you** — framed for a CX Team Lead specifically
- **One question to sit with**
- **↗ Source link**

Ends with: "this week's one thing" (the single most important read) + one reflection prompt.

---

## Key Insights Captured (from experts)

### Shep Hyken — Consistency
- Amazing = consistently and predictably slightly above average (not occasional WOW)
- Eliminating Un-WOW moments = as important as creating WOW
- 2026 data: 96% say product quality > service; 65% say convenience > friendliness
- AI transparency is non-negotiable — don't pretend bots are humans

### Chris Voss — Emotion & Tension
- Label the emotion before offering the solution ("It sounds like this has been really frustrating")
- "No" is not the end — it's the beginning of real dialogue
- Mirroring (repeat last 2-3 words) → invite more expression
- "That's right" = trust established

### Carly Agar — Scale & Systems
- Deflect > Resolve: best support is support that never needed to happen
- Better onboarding cuts 30-50% of support volume in first 90 days

### Adrian Swinscoe — Voice → Action
- VoC must be a closed loop: Listen → Act → Close the loop
- Customer satisfaction is the ultimate moat (March 2026)
- AI traffic surged 393% YoY in Q1 2026 — customers arrive more informed
- "VUCA on steroids": front office needs culture reset, not more tools

### Justin Chappell — Scale & Systems
- Playbook = decision framework, not rule book
- Goal: 80% of common issues resolved without Manager input

### Gadi Shamia — People & Culture
- Automating a broken process = failing faster
- At least one top-10 BPO may file for bankruptcy in 2026 as AI contracts expire
- Human-in-the-loop is the practical AI transition model

### Nate Brown — People & Culture
- EX → CX: you cannot create enjoyable CX with miserable employees

### Anika Zubair — Systems Thinking
- Root cause of recurring support problems is almost always upstream (product / process)
- Ask 5 Whys before assuming the fix is in the support team

---

## The Notion Document Structure (from document shared in conversation)

Recommended structure for capturing insights (from the document shared mid-conversation):

**Layer 1 — Basic Info**
- Title, Source, Expert, Category, Link, Date

**Layer 2 — Thinking Conversion (the differentiator)**
- Problem: what does this content solve?
- Insight: core idea in one sentence
- Why it matters: in your own words
- **My Take: do you agree? what would you add? what do you disagree with?**

**Layer 3 — Application**
- Apply to my work: how to use this at Edrolo/current role?
- Action Idea: concrete next steps
- Impact: which metrics? (CES / ticket volume / SLA)

**Layer 4 — Output (not used in this skill — removed as not needed)**
- Content Angle, Hook, Status

**20-minute input rhythm:**
1. Read 5 items, pick 2 that feel most relevant
2. Write 2 insights (one sentence each)
3. Write one action for the week

---

## How to Run the Weekly Digest

Just message Claude: **"run the weekly CX digest"**

Claude will:
1. Search for content published in the past 7 days from the 16 experts
2. Select ≤10 most relevant pieces
3. Write each up in the standard format (who / what / why it matters / question)
4. Push a new note into your CX Area Notes (Type: Research, linked to CX area)

---

## Files Created

| File | Description |
|------|-------------|
| `follow-cx-builders-v4.html` | Main digest tool — English, source links, Notion sync |
| `follow-cx-builders.html` | v1 — full dashboard (archived) |
| `follow-cx-builders-v2.html` | v2 — digest-first (archived) |
| `follow-cx-builders-v3.html` | v3 — structured reflection, Chinese (archived) |

---

## Next Steps

- [ ] Run weekly digest each Friday (ask Claude)
- [ ] After 3–5 digests: hit "synthesize my thinking" in the tool
- [ ] Update "My Emerging Framework" section in the master Notion note
- [ ] Duplicate CX Weekly Review note each Friday, fill in 10 min
- [ ] When something shifts in your framework, update the master note
- [ ] Consider: push digest entries directly to CX Area Notes via the v4 tool's Notion sync

