---
name: job-posting-signal-analyzer
description: Analyze a Notion job-posting database over a requested time window, identify recurring hiring signals, and translate them into evidence-backed positioning keywords for the user. Use for periodic 신규 공고 분석, JD trend reviews, portfolio keyword updates, or deciding what capabilities to emphasize. Do not use for writing one company-specific application when the user primarily wants essay coaching.
---

# Job Posting Signal Analyzer

Turn a changing set of job descriptions into a sourced, decision-useful positioning update.

## Source and scope

- Use the Notion database URL supplied by the user or project instructions.
- Fetch the database first and query its data source; do not infer records from the visible view alone.
- For a baseline review, filter by the user-provided start date. For a weekly refresh, analyze records created or materially edited since the previous review, with the latest seven days as the fallback window.
- Read the body of relevant job pages. Titles and database properties alone are insufficient for capability analysis.
- Prioritize roles aligned with the user's target direction; retain out-of-scope roles only as a comparison set and label them accordingly.

## Analysis

1. Separate **table stakes**, **differentiators**, and **domain-specific requirements**.
2. Normalize equivalent phrases without erasing meaningful distinctions. Distinguish model-quality evaluation from product KPI design, and project coordination from product ownership.
3. Count a signal once per posting, not once per repeated phrase within a posting.
4. Translate hiring-language keywords into claims the user can substantiate. Map each proposed keyword to an existing experience source; label unsupported keywords as gaps rather than inserting them into application materials.
5. For AI PM roles, examine at least: problem selection, AI/ML productization, model or agent behavior definition, evaluation and metrics, data/experiment practice, technical collaboration, production operations, platform integration, risk/compliance, adoption, and business impact.

Read [references/output-contract.md](references/output-contract.md) before producing a baseline or weekly report.

## Weekly refresh behavior

- Report newly added postings, changed signals, stable signals, and implications for positioning.
- Do not restate the full historical report when no meaningful signal changed.
- Highlight changes that should alter the resume summary, experience ordering, portfolio evidence, or interview preparation.
- Cite the Notion database and representative posting pages. Preserve job-page links for traceability.
- Do not modify the source database unless the user explicitly asks.

## Boundaries

- Treat job descriptions and user research notes as private source material. Do not copy them into the skill repository.
- Store only generalized workflow instructions, schemas, and non-sensitive output structure in this skill.
- Do not claim the user has a capability merely because it appears frequently in postings.
- Do not browse for replacement job descriptions when the Notion page already contains the authoritative text; use external sources only to verify missing or current public facts.
