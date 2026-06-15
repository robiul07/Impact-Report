# Nonprofit Impact Reporter — a Claude Skill

A reusable Claude Skill that turns a nonprofit's CSV of periodic metrics into a complete,
responsible impact report: executive summary, KPI snapshot, trend analysis, risk flags,
recommended actions, a donor update, a board summary, chart suggestions, and an enriched
CSV with AI-generated columns.

It is built around one rule: **use only the numbers in the file — never invent figures.**

## What's in here

```
nonprofit-impact-reporter/
├── SKILL.md                          # the skill: instructions Claude follows
├── assets/
│   └── sample_community_harvest.csv  # sample data to try it on
└── references/
    └── example_output.md             # a model of good output (tone + structure)
```

## How to use it

**In Claude (with Skills enabled):** install the skill, then upload any nonprofit CSV and
ask for an impact report. The skill triggers automatically when you share nonprofit metrics
and want a report, board memo, or donor update.

**As a prompt (no install needed):** paste the contents of `SKILL.md` into a Claude chat,
then upload your CSV. Claude will follow the same workflow.

**Try it fast:** use `assets/sample_community_harvest.csv` (a fictional food bank) and ask
*"Generate a full impact report from this CSV."*

## Companion project

There's also a deployed web-app version of this workflow — upload a CSV in the browser and
download a polished PDF — built with Next.js and the Claude API. (Link in repo description.)

## License / use

Free to use and adapt for your organization. Figures in any report come only from the data
you provide; interpretations are analytical, not audited.
