# Ngọc Phương — Work & Knowledge Portfolio

Production Accounting · SAP · Costing · Data Control · Process Improvement

Live site: https://ngoc-phuong-portfolio.vercel.app

## Current features

- Bilingual Vietnamese / English interface
- Responsive desktop / tablet / mobile layout
- Selected accounting & SAP case studies
- Searchable SAP Knowledge Base
- Category filters and expandable SAP practice notes
- Mobile navigation
- Confidentiality-first public content

## Project structure

```text
index.html
styles.css
app.js
AGENTS.md

.agents/
  skills/
    portfolio-design/
      SKILL.md
    redesign-portfolio/
      SKILL.md
    sap-accounting-portfolio/
      SKILL.md
    reference-site-study/
      SKILL.md

docs/
  DESIGN_SYSTEM.md
  KNOWLEDGE_SCHEMA.md
```

## Agent workflow

When using Codex, Cursor, Claude Code, or another coding agent on this repository:

1. Read `AGENTS.md`.
2. Read the skill relevant to the task.
3. Preserve VI/EN, mobile navigation, SAP Knowledge Base search/filter and confidentiality rules.
4. For redesign work, audit before editing.
5. Verify desktop + mobile and production deployment before calling the work complete.

Example prompt:

```text
Read AGENTS.md and the project skills first.
Audit the current portfolio, then improve the SAP Knowledge Base experience
without breaking Vietnamese/English switching or mobile behavior.
```

For a reference website:

```text
Read AGENTS.md and .agents/skills/reference-site-study/SKILL.md.
Study this reference URL for layout, typography and interaction rules.
Translate the design language into this portfolio using my own content and branding.
Do not copy protected brand assets or copy.
```

## Knowledge Base standard

SAP content should explain:

```text
Business Situation
→ SAP Logic
→ Transactions / Reports
→ Step-by-Step Check
→ Reconciliation
→ Common Errors
→ Root Cause
→ What I Learned
```

T-codes support the explanation; they are not the explanation.

## Confidentiality

Do not publish real customer/vendor names, sensitive amounts, internal PO/SO/order numbers, asset IDs, or screenshots containing identifiable business data unless explicitly approved.

## Design references

The project skills are tailored summaries inspired by:
- https://github.com/Leonxlnx/taste-skill
- https://github.com/JCodesMore/ai-website-cloner-template

They are adapted specifically for this portfolio rather than copied verbatim from upstream skill files.
