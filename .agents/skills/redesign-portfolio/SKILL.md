---
name: redesign-portfolio
description: Audit-first workflow for improving the existing portfolio without breaking functionality.
---

# Redesign Portfolio Skill

Use this skill whenever improving the current website rather than creating a new one from scratch.

## 1. Scan

Read:
- `index.html`
- `styles.css`
- `app.js`
- `AGENTS.md`
- relevant project skill files

Identify:
- current layout
- translation model
- Knowledge Base rendering
- search/filter behavior
- responsive breakpoints
- existing design tokens

Do not migrate frameworks unless there is a clear user-approved reason.

## 2. Diagnose

Audit these categories.

### Hierarchy
- Can a recruiter understand the professional positioning in a few seconds?
- Does the page explain capability through evidence, not claims?
- Are Case Studies and SAP Knowledge clearly more important than decorative content?

### Typography
- Are headings distinct and intentional?
- Is body copy readable at mobile widths?
- Are technical identifiers visually distinct?

### Layout
- Is the page too symmetrical?
- Are there too many identical cards?
- Is spacing consistent but not mechanically uniform?
- Does mobile have a clear reading order?

### Color
- Is one accent family used consistently?
- Is there any abrupt section color change?
- Is contrast accessible?

### Interaction
- Does VI/EN work?
- Does navigation work?
- Does mobile menu work?
- Does Knowledge search/filter work?
- Are focus states visible?

### Content
- Is copy specific to Production Accounting / SAP?
- Does each project show problem, evidence, approach and outcome?
- Does Knowledge Base explain logic rather than only T-codes?

## 3. Fix

Prioritize:
1. information hierarchy
2. typography
3. spacing/layout
4. interaction states
5. responsive behavior
6. visual polish

Keep changes focused and reviewable.

## 4. Validate

Verify:
- desktop
- mobile
- VI
- EN
- search
- filters
- mobile menu
- anchor navigation
- no console-breaking JavaScript
- no horizontal overflow

After GitHub commit, verify the Vercel production deployment is READY.

## Rule

Do not claim a redesign is complete just because code was changed. Completion requires a rendered and deployed check.

## Reference

Adapted for this project from the audit-first ideas in:
https://github.com/Leonxlnx/taste-skill
