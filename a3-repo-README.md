# A3 Problem-Solving Report — Patry AI Fellowship

Your personal A3 report for your Summer 2026 Fellowship project. This page is your working document **and** your presentation tool.

## Quick Start

### 1. Fork this repository
Click the **Fork** button (top right of this page) to create your own copy.

### 2. Enable GitHub Pages
Go to **Settings → Pages → Source** and select **Deploy from a branch**. Choose `main` and `/ (root)`, then click **Save**.

Your A3 will be live at: `https://[your-username].github.io/a3-report/`

### 3. Edit your A3 data
Open `a3-data.json` and fill in your project details. You can edit it:

- **On GitHub**: Click the file, then the pencil icon (✏️) to edit directly in your browser
- **Locally**: Clone the repo, edit in VS Code or any text editor, then commit and push

### 4. Commit and push
Every time you update `a3-data.json` and push to `main`, your live page updates automatically (may take 1–2 minutes).

---

## How the A3 works

The A3 is a **one-page problem-solving framework** from Lean / continuous improvement. It tells a story from left to right:

| Left Side (Problem) | Right Side (Solution) |
|---|---|
| 1. Background / Context | 5. Countermeasures / Proposed Solution |
| 2. Current Condition | 6. Implementation Plan |
| 3. Goal / Target Condition | 7. Follow-Up & Verification |
| 4. Root Cause Analysis | |

**The key rule**: Don't fill in the right side until the left side is solid. Understand the problem before proposing the solution.

---

## ROI Estimate

Every project must quantify its impact. The ROI bar at the top of your A3 tracks four metrics. Fill in whichever are relevant to your project — at least one must have a number.

| Field | Example | When to use |
|---|---|---|
| Revenue Impact | `$50,000/year` | If your project drives new revenue or prevents revenue loss |
| Cost Savings | `$18,000/year` | Dollar value of time saved, errors eliminated, vendors removed |
| Hours Saved | `6-8 hrs/week → < 30 min/week` | Almost every project will have this |
| Capacity Impact | `50 → 500+ requests/week` | If the process can now handle more volume without adding headcount |

---

## Editing `a3-data.json`

The file is standard JSON. Fill in the `"content"` field for each section. Use `\n` for line breaks.

Example:

```json
{
  "project_title": "Automated Maintenance Request Triage",
  "owner": "Jane Smith",
  "division": "Property Management",
  "date": "2026-06-15",
  "status": "in_progress",

  "roi": {
    "revenue_impact": "",
    "cost_savings": "$18,000/year",
    "hours_saved": "6-8 hrs/week → < 30 min/week",
    "capacity_impact": "50 → 500+ requests/week"
  },

  "sections": {
    "1_background": {
      "title": "Background / Context",
      "subtitle": "Why does this project exist? Who is affected?",
      "content": "Patry's property management team receives ~50 maintenance requests per week via email.\nEach request is manually logged, categorized, and assigned to a contractor.\nThis process takes 6-8 hours per week and is prone to delays."
    }
  }
}
```

### Status options
Set `"status"` to one of:
- `"proposal"` — Project is in the planning stage
- `"in_progress"` — Actively building and testing
- `"complete"` — Delivered and verified

---

## Presenting your A3

Your live page has a **▶ Present** button in the toolbar. This hides the editing chrome and shows clean, presentation-ready content. Use it when screen-sharing with leadership.

---

## File structure

```
├── index.html          ← The A3 viewer (do not edit)
├── a3-data.json        ← Your project data (edit this)
├── a3-data-demo.json   ← Example filled-in A3 (reference)
├── logo.png            ← Patry Group logo
└── README.md           ← This file
```

---

## Tips

- **Update regularly.** Your commit history shows how your thinking evolved — leadership can see this.
- **Be specific.** "Reduce processing time from 8 hrs/week to 1 hr/week by July 15" beats "Make things faster."
- **Left before right.** Resist the urge to jump to solutions. The A3 discipline is about understanding the problem first.
- **Use data.** Numbers, measurements, and evidence make your A3 credible.
- **Quantify ROI.** Every project must show measurable impact — at minimum, hours saved.

---

*Patry AI Fellowship · Summer 2026 · Continuous Improvement Program*
