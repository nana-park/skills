# Readable written experience stories

Use when turning discovered experience into written notes or a narrative. Preserve the single central problem, strategic framing, and concrete personal context established during discovery.

## Main story and optional depth

The main text should read naturally from start to finish without requiring the reader to read indented details. Keep the affected user and situation, central problem, essential reasoning for the chosen action, personal contribution, and result visible at this level. Each peer paragraph or bullet should advance the story rather than repeat it under a different PM label.

Start a new line and indent supporting detail directly below the claim it explains. Indentation represents the interviewer's follow-up path, not decoration, chronology, or a PM framework taxonomy. Before indenting a line, state the question an interviewer would ask about its parent. If there is no clear question, keep it at the same level, rewrite the relationship, or move it elsewhere.

Typical relationships are claim → evidence, decision → benchmark or trade-off, metric → calculation or measurement limit, and action → implementation detail or collaboration exchange. Further nesting is appropriate only when it answers a deeper follow-up question about its immediate parent. When that question thread ends, return to the appropriate parent level before starting the next decision, action, or result. Use native paragraph/list indentation in rich text and nested bullets in Markdown; “tab” here does not mean creating a separate document tab.

Keep the decisive reason in the main text; move the expanded proof or mechanism below it. “Why we chose this” cannot disappear entirely into a technical appendix if the reader needs it to understand the action. Likewise, a material measurement limitation must remain visible where needed to avoid a misleading headline result.

## Four reading layers

Build the master material at interview depth first, then compress the same supported experience into four layers:

1. **Layer 1:** a one-line explanation of the central problem, decisive contribution, and outcome or professional signal.
2. **Layer 2:** a 5W1H incident overview that an unfamiliar listener can understand without follow-up.
3. **Layer 3:** application-ready specificity with context, judgment, ownership, action, and verified result.
4. **Layer 4:** interview-ready evidence and follow-up answers, including detailed criteria, alternatives, exchanges, artifacts, execution steps, numbers, edge cases, and limitations.

These are four depths of the same experience, not four independently written stories. Layer 4 is an evidence reservoir. Create the upper layers by selecting what proves the main judgment, not by squeezing every Layer 4 detail into shorter prose. Preserve the same central problem and supported facts across all layers.

Communication and execution details are usually supporting proof. Unless they are the target competency, keep only the incident, risk, decisive criterion or mechanism, and outcome in the upper layers. Put extended stakeholder exchanges, escalation history, schedules, and test mechanics in Layer 4.

## Layering without a rigid template

A useful master-note arrangement is a short summary, a coherent problem–judgment–action–result narrative, and deeper follow-up answers. These are reading depths, not mandatory named sections, an exact sentence count, or a page quota. Tailor headings to the actual experience. Do not force every project into the same exhaustive framework.

For experience notes, prefer connected sentences or sentence-based bullets over a table of disconnected framework keywords. A table can still help compare exact alternatives when requested or genuinely useful; it should not replace the narrative. For a short application field or resume bullet, keep the main story within the requested format rather than appending an unsolicited interview notebook. Preserve supporting depth separately only when requested or appropriate to the master notes.

## Google Docs outline convention

When continuing the user's existing Google Docs experience notes, match the hierarchy already established in the current document instead of introducing a new layout.

- Use Heading 2 only for a new experience or project unit at the same scope as the existing numbered project titles.
- Treat interview question categories such as `문제정의`, `Action`, `Metrics`, and `Result` as container labels. Put the first substantive answer exactly one indentation level beneath its label; never write the label and answer on the same line or at the same level.
- Within one project, use an unbulleted parent line for a concrete action area or decision area beneath the relevant container. Bold it only when the surrounding document uses bold for comparable parent lines; do not turn every PM label into a heading.
- Put numbered items such as `Decision 1` and `Decision 2` beneath that parent as ordinary nested list items. The number is part of the label; do not assume it should become a native numbered list.
- Put a benchmark, trade-off, evidence source, mechanism, calculation, limitation, or concrete example one level beneath the exact claim it answers.
- After the last numbered item, reduce the indentation to the parent level. Create another Heading 2 only when the next content is genuinely a new project unit.
- Preserve the document's established type size, paragraph spacing, list style, and provenance colors. Do not silently restyle existing user text or make new material indistinguishable from it.
- Use separate paragraphs for separate outline nodes. Do not simulate multiple nodes with tabs, soft line breaks, or several labels inside one paragraph.
- Match the existing document's numbered-outline sequence before introducing symbol bullets. In the reference document this means using the available numbered levels first—decimal, alphabetic, and Roman variants—and switching to a symbol bullet only after the numbered nesting levels are exhausted. Do not replace that hierarchy with a new `disc → circle → square` bullet list.
- Every outline node must carry the list marker appropriate to its level. Do not create hierarchy by combining an unlisted paragraph, manual left padding, and a list marker with a mismatched hanging indent; this produces missing markers and blank gaps before text.
- Split compound facts when an interviewer could question them independently. Put a short parent label such as `기존 구조` on its own node, then place the sequence, architecture, and component responsibility on separate child nodes instead of joining them with periods in one long line.

Do not convert the whole case into a nested outline in which the only top-level content is labels such as `Problem`, `Tension`, and `Action`. If removing indented lines leaves only framework labels, essential story claims have been nested too deeply and must be promoted.

The container-label rule and the readable-main-story rule operate together: the label occupies the outer level, while its core answer occupies the immediately inner level and remains readable without deeper follow-ups. Evidence, mechanisms, examples, and limitations may then go one level beneath that core answer. Do not skip directly from a label to second-level detail.

Example hierarchy:

```text
[Heading 2] 2. Project or experience title

Problem Definition
    Concrete user problem
        • Evidence or causal detail

Action
    Decision area expressed in the experience's own language
        • Decision 1: chosen approach
            • Benchmark
                • Concrete comparison case
            • Trade-off
        • Decision 2: second approach
            • Follow-up evidence

Metrics
    Success metric
        • Calculation or measurement limit

Result
    Verified outcome
        • Scope or interpretation limit

[Heading 2] 3. Next project or experience title
```

## Readable professional language

Write so a PM outside this particular domain can follow the story. Name the concrete actor and task, explain specialist mechanisms only as far as the decision requires, and use causal transitions where supported. Do not turn all notes into a long unbroken essay: paragraph breaks and light headings should aid reading.

When consulting mentor-annotated versions, learn from the hierarchy and reasoning, not the literal shorthand. Colored fragments, arrows, English labels, and placeholders may be working notes rather than publication-ready sentences. Convert them into readable prose, resolve ambiguities through questions, and do not treat an older version's claims as automatically current. Color indicates review provenance according to the user's explanation, while indentation indicates conceptual depth; these serve different purposes.

## Review before presenting

- Skip every indented block: does the main story still explain the problem, choice, and outcome naturally?
- For every child line, what exact interviewer follow-up question does it answer?
- Is the core answer exactly one level beneath its question-category label, rather than on the same line or two levels down?
- Ask a follow-up about a main claim: is its answer immediately underneath rather than buried elsewhere?
- Check each child: does it elaborate its parent, or should it move to another parent or a separate story?
- When a numbered question thread ends, does the next line return to the correct parent level?
- In Google Docs, are new project units the only content promoted to Heading 2?
- Does the outline use the document's numbered levels before falling back to symbol bullets, without missing markers or artificial spaces?
- Has each multi-claim sentence been split into parent and child nodes when the claims answer different follow-up questions?
- If understanding requires reading a lower-level detail, promote its essential point and leave the expanded explanation below.
- Remove duplicate explanations, not unique reasoning or context that makes this the user's experience.

If a needed bridge is missing, ask one focused question instead of filling it with jargon or invented connective logic.

## Destination and privacy

Apply this writing method wherever the user requests the output. A previously used experience document is a reference, not a permanent automatic write destination. Analysis-only requests do not authorize document or skill edits. Keep private source links and mentoring excerpts out of the distributable skill; retain only generalized writing guidance.
