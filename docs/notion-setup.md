# Notion Setup

Connect `follow-cx-builders` to your Notion workspace so every digest entry auto-logs as a database row.

---

## Step 1 — Create the database

Create a new Notion page → add a full-page **Table** database. Name it `CX Insight Engine`.

Add these exact properties:

| Property | Type | Notes |
|----------|------|-------|
| Name | Title | Expert name — auto-filled |
| Pillar | Select | Consistency / Emotion & Tension / Scale & Systems / Voice → Action / People & Culture |
| Insight | Text | Core insight text |
| Source | URL | Link to original article |
| My Take | Text | Your agree/disagree/add |
| Apply | Text | How to use in your work |
| Action | Text | One specific next step |
| Date | Date | When you logged it |
| Status | Select | new / applied / tested |

Property names must match exactly — the tool maps to these.

---

## Step 2 — Create your Notion integration

1. Go to [notion.so/my-integrations](https://www.notion.so/my-integrations)
2. Click `+ New integration`
3. Name it `follow-cx-builders`
4. Select your workspace
5. Submit — copy the **Internal Integration Token** (starts with `secret_`)

---

## Step 3 — Connect the integration to your database

1. Open your `CX Insight Engine` database
2. Click `···` (top right) → `Add connections`
3. Select `follow-cx-builders`

---

## Step 4 — Get your Database ID

Open the database. Copy the URL. The ID is the 32-character string between the last `/` and `?v=`:

```
https://notion.so/My-DB-abc123def456ghi789jkl012mno345?v=xxx
                        ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
                        this is your Database ID
```

---

## Step 5 — Connect in the tool

1. Open `follow-cx-builders.html` in your browser
2. Click `→ notion` in the top nav
3. Paste your token and Database ID
4. Click `test connection` — should show ✓ connected
5. The save button now reads `save + sync →`

From this point every saved entry auto-creates a Notion row.

---

## Optional: useful Notion views

### "Actions this week" filter view
- Filter: `Action` is not empty + `Date` is this week
- Open every Monday — your week's commitments are right there

### Status board
- Board view grouped by `Status`
- See at a glance what's still `new`, what you've `applied`, what you've `tested`

---

## Weekly status update ritual

Each entry starts as `new`. When you try something at work:
- Change to `applied`
- If you learned something from it: change to `tested`, add a note in `My Take`

Friday review: open the "Actions this week" view. Ask:
- Which action did I actually do?
- What happened?
- What stayed `new` — and why?
