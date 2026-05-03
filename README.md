# follow-cx-builders

> A weekly CX digest — curated from 18 practitioners, delivered to Notion, built to become your personal CX framework.

---

## What this is

Most CX learning looks like this: save an article, forget it. Follow an expert, scroll past their posts. Attend a webinar, take no action.

`follow-cx-builders` is different. Every week, ≤10 fresh reads from the 18 experts land in your Notion workspace — curated, contextualised, and ready to read. Each item comes with three reflection prompts:

- **My Take** — do I agree? what would I add or push back on?
- **Apply to my work** — what does this mean for my team right now?
- **Action** — one specific thing I'll do this week

Over time, your answers become your personal CX operating principle.

---

## Who it's for

CX Team Leads and Managers who are:
- Reading a lot but not retaining or applying it
- Building their strategic thinking alongside day-to-day ops
- Want a living framework that evolves with their experience

Not for: content creators, people primarily focused on sharing insights publicly.

---

## How to use

### Option A — Claude.ai (chat)

Message Claude:

```
run the weekly CX digest
```

Claude searches the past 7 days, picks ≤10 most relevant pieces, and pushes a formatted note to your Notion CX area.

### Option B — Claude Code (terminal)

Install the skill once:

```bash
cd ~/.claude/skills/
git clone https://github.com/HelloitsSina/follow-cx-builders.git
```

Then in any Claude Code session:

```
run the weekly CX digest
```

or invoke directly:

```
/follow-cx-builders
```

### Requirements

- Claude connected to your Notion workspace
- A CX area in your Notion where digests will be pushed

---

## The 18 Experts

Curated across 5 strategic pillars for a CX Manager role.

### Pillar 1 — Consistency
| Expert | Focus | Base | Source |
|--------|-------|------|--------|
| Shep Hyken | Service culture · "Amazing" CX | 🇺🇸 USA | [hyken.com](https://hyken.com) |
| Jeff Toister | Conversations · Team training | 🇺🇸 USA | [toister.com](https://www.toister.com/blog) |
| Lisa Stoner | Operational efficiency at scale | 🇺🇸 USA | [LinkedIn](https://www.linkedin.com/in/lisastonercx/) |
| **Jaquie Scammell** | Service culture · EX → CX · 5D framework | 🇦🇺 **Australia** | [jaquiescammell.com](https://jaquiescammell.com) |

### Pillar 2 — Emotion & Tension
| Expert | Focus | Base | Source |
|--------|-------|------|--------|
| Chris Voss | FBI negotiation · Difficult conversations | 🇺🇸 USA | [MasterClass](https://www.masterclass.com/classes/chris-voss-teaches-the-art-of-negotiation) |
| Celeste Headlee | Listening · Presence | 🇺🇸 USA | [celesteheadlee.com](https://www.celesteheadlee.com/talks) |
| Vanessa Van Edwards | Reading people · Rapport | 🇺🇸 USA | [scienceofpeople.com](https://www.scienceofpeople.com/communication/) |
| Nate Brown | Empathy · Experience design | 🇺🇸 USA | [LinkedIn](https://www.linkedin.com/in/nate-brown-cx/) |

### Pillar 3 — Scale & Systems
| Expert | Focus | Base | Source |
|--------|-------|------|--------|
| Daphne Costa Lopes | SaaS scale · Process design | 🇺🇸 USA | [LinkedIn](https://www.linkedin.com/in/daphnecostalopescsm/) |
| Justin Chappell | Playbooks · Support org design | 🇺🇸 USA | [LinkedIn](https://www.linkedin.com/in/justinchappell/) |
| Carly Agar | Ticket deflection · Proactive support | 🇺🇸 USA | [LinkedIn](https://www.linkedin.com/in/carlyagar/) |
| **Justin Tippett** | Contact centre ops · ANZ benchmarking | 🇦🇺 **Australia** | [acxpa.com.au](https://acxpa.com.au) · [LinkedIn](https://www.linkedin.com/in/justintippett/) |

### Pillar 4 — Voice → Action
| Expert | Focus | Base | Source |
|--------|-------|------|--------|
| Adrian Swinscoe | VoC → Action · Punk CX | 🇬🇧 UK | [adrianswinscoe.com](https://adrianswinscoe.com) |
| Dan Gingiss | Remarkable experiences · CX cases | 🇺🇸 USA | [dangingiss.com](https://dangingiss.com/blog/) |
| Bill Quiseng | Sharp service insights | 🇺🇸 USA | [billquiseng.com](https://billquiseng.com/blog/) |

### Pillar 5 — People & Culture
| Expert | Focus | Base | Source |
|--------|-------|------|--------|
| Adam Topore | Frontline agent coaching | 🇺🇸 USA | [LinkedIn](https://www.linkedin.com/in/adamtopore/) |
| Gadi Shamia | AI & automation in support | 🇺🇸 USA | [LinkedIn](https://www.linkedin.com/in/gadishamia/) |
| Anika Zubair | Career growth · Systems thinking | 🇺🇸 USA | [LinkedIn](https://www.linkedin.com/in/anika-zubair/) |

> 🇦🇺 **Australia-based experts** are highlighted in bold — their work is grounded in the ANZ market context, regulatory environment, and organisational culture.

---

## The Weekly Digest Format

Each digest contains ≤10 items. Every item includes:

- **Who** — one sentence on who this expert is
- **What** — what they said, jargon explained in plain English
- **Why it matters for you** — framed for a CX Team Lead specifically
- **One question to sit with** — a reflection prompt tied to real work
- **↗ Source link** — direct link to the original

Ends with: one "this week's one thing" recommendation + one reflection prompt across all items.

---

## The Framework

After working through the digests, five strategic questions to answer for yourself:

```
1. CONSISTENCY       What does "good" look like reliably, not occasionally?
2. EMOTION & TENSION How does your team handle the hard human moments?
3. SCALE & SYSTEMS   What breaks first when your team grows?
4. VOICE → ACTION    How does customer feedback become change?
5. PEOPLE & CULTURE  What are you doing for the people doing the work?
```

Your answers — built from real reflections, not theory — are your CX operating principle.

---

## Files

```
follow-cx-builders/
├── README.md                    ← you are here
├── SKILL.md                     ← Claude Code skill definition
├── docs/
│   ├── conversation-log.md     ← full build log of this project
│   ├── weekly-digest.md        ← digest format + prompt template
│   └── framework-guide.md      ← building your personal CX framework
├── examples/
│   ├── sample-entries.md       ← example filled-in reflections
│   └── sample-framework.md     ← example synthesised framework
└── .github/
    └── workflows/
        └── weekly-digest.yml   ← optional: Friday reminder automation
```

---

## Philosophy

> "Follow people who build and have original opinions, not influencers who regurgitate."
> — inspired by Zara Zhang's follow-builders

The goal isn't to consume more content. It's to build your own point of view — one forced reflection at a time.

The differentiator isn't what you read. It's **My Take**.

---

## Contributing

If you're a CX practitioner and want to:
- Add an expert to the list (with rationale and base location)
- Share a sample framework or entries
- Suggest a new pillar or reframe an existing one

Open a PR or issue. Kept deliberately small — quality over breadth.

---

## License

MIT — use freely, adapt for your team, no attribution required.
