---
name: follow-cx-builders
description: Run the weekly CX digest — search recent posts from 16 CX experts, curate ≤10 most relevant reads, and push to Notion CX area. Use when asked to "run the weekly CX digest", "CX weekly update", or "what have my CX experts been writing".
---

# follow-cx-builders

A weekly CX digest — curated from 16 practitioners, delivered to Notion, built to become your personal CX strategy framework.

## When to use this skill

Trigger on any of:
- "run the weekly CX digest"
- "run the CX digest"
- "what have my CX experts been writing"
- "CX weekly update"
- "update my CX digest"

## The 16 experts to search

Search each expert's primary publishing channel for content from the past 14 days:

| Expert | Where to look |
|--------|--------------|
| Shep Hyken | hyken.com/blog + Forbes column |
| Jeff Toister | toister.com/blog |
| Dan Gingiss | dangingiss.com/blog |
| Adrian Swinscoe | adrianswinscoe.com (publishes 2–3x/week) |
| Daphne Costa Lopes | LinkedIn |
| Justin Chappell | LinkedIn |
| Carly Agar | LinkedIn |
| Lisa Stoner | LinkedIn |
| Chris Voss | LinkedIn + masterclass.com |
| Celeste Headlee | celesteheadlee.com |
| Vanessa Van Edwards | scienceofpeople.com |
| Nate Brown | LinkedIn |
| Adam Topore | LinkedIn |
| Gadi Shamia | LinkedIn |
| Bill Quiseng | billquiseng.com/blog |
| Anika Zubair | LinkedIn |

## Selection criteria

**Include if:**
- Published in the past 14 days (stretch to 30 if a slow week)
- Directly relevant to managing a CX team — not just general business advice
- Has a specific, actionable angle — not just "CX is important"
- Challenges a common assumption or surfaces new data

**Skip if:**
- Pure promotional content for a product or event
- Generic listicles without original thinking
- Older content with no new angle

Max 10 items. Quality over volume — fewer sharp items beats 10 mediocre ones.

## Output format

Write each item as follows:

```
### N · Expert Name — Article/post title
**Who:** One sentence on who this person is — what they're known for.
**What:** What they said. Explain any jargon in plain English in parentheses.
**Why it matters for you:** Why a CX Team Lead managing a support team should care. Be specific.
**One question to sit with:** A reflection prompt tied to real work — not generic.
↗ [Read: title](url)
```

End the digest with:

```
## This week's one thing
[Single most important read — 2 sentences on why]

## Reflection prompt
[One question that cuts across all items this week]
```

## Notion destination

Push the completed digest as a new note to the user's Notion CX Area:
- **Parent:** CX Area Notes database
- **Title format:** `CX Weekly Digest — Week of [DD Mon YYYY]`
- **Type:** Research
- **Linked to:** CX area

## Tone

- Plain English throughout
- Jargon always explained inline in parentheses on first use
- Framed for a CX Team Lead — not a CX analyst, not a C-suite exec
- Direct and useful — no padding
