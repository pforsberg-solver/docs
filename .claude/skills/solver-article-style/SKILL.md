---
name: solver-article-style
description: Solver docs house style. Use when writing, editing, or reviewing any how-to or feature article (.mdx) in this repo, so it follows the Report Designer article's structure and conventions.
---

# Solver article style

Model article: `rd.mdx` (Report Designer). Match its structure and voice.

## Page structure (in this order; omit sections that don't apply)

1. Frontmatter: `title`, `description`, `keywords`. No `mode` unless asked.
2. `## Before you begin`: a "Required license and permissions" table (Requirement | Purpose), then a "What you'll need" bullet list.
3. `## How <feature> works`: 1–2 paragraphs and the key concepts as a table.
4. Task sections, one `##` per task, in the order a user does them. Put the steps inside `<Steps>`, or use a numbered list for short tasks.
5. `## Button and action reference`: one table per surface (toolbar, menu, pane): Button | What it does.
6. `## Best practices`: bullets that start with a **bold imperative**, then one sentence explaining why.
7. `## Troubleshooting`: table, Problem | Solution. Write each problem the way a user would describe it.
8. `## Glossary`: table, Term | Definition, sorted alphabetically.

## Headings

- Sentence case. Don't number headings ("Create a template", not "3. Step 1: Create a Template").
- Use `###` for subsections and `####` for labels inside a section. Never use a bold line as a heading.
- No `---` horizontal rules.

## Procedures

- One action per numbered step: "On the toolbar, click **New**, then select **Create New Template**."
- Use sub-bullets only for details or options within a step.
- State the result after the steps ("The new template appears in the template list.").
- Offer alternatives as `### Option A: …` / `### Option B: …`.

## UI and formatting conventions

- Bold the exact UI label text: buttons, tabs, menus, fields, dialog names, and permissions.
- Write the overflow menu as **…** (more actions).
- Italicize example values: *Data Warehouse*, *General Ledger*.
- Use inline code for symbols and syntax users type or see literally: `@Period`, `»`.
- Use tables for any reference content with 3 or more items that share attributes.
- Give every code block a language tag (use `text` for plain text).

## Callouts (Mintlify components, not blockquotes)

- `<Note>`: extra context or a limitation.
- `<Tip>`: a shortcut or a faster way.
- `<Warning>`: anything that loses work, overwrites data, or can't be undone (the model article's "Important").
- Keep each callout to one or two sentences. Don't stack several in a row.
- Never write callouts as `> **Note:**` blockquotes; they render as plain quotes.

## Links

- Link other articles with root-relative paths: `[Sharing templates](/sharing-templates)`. Never italicize a title instead of linking it.

## Voice

- Second person ("you"), present tense, active voice. One idea per sentence.
- Use the terms from the Glossary consistently (template, module, dimension, attribute, measure, parameter).

## Review checklist

When asked to review an article, check each rule above and report violations as a table: Location | Issue | Fix.
