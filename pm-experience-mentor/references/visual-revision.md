# Visual Revision

Use this reference only when an original draft exists and the user wants visible changes.

## Preserve provenance

Keep the original available as the baseline. Prefer a comparison copy or a clearly separated comparison section. Do not silently overwrite the only copy.

Every visible change must belong to one of these categories:

| Category | Rich-text treatment | Markdown fallback |
| --- | --- | --- |
| Original retained | black text | plain text |
| Proposed deletion | red strikethrough | `~~deleted~~` |
| Mentor rewrite | blue text | `**[제안 문장]**` |
| Strategic reframing or connection | blue text with framing label | `**[재구성 제안]**` |
| Newly discovered fact or judgment | purple text | `**[새로 발굴]**` |
| Unresolved fact or evidence | orange highlight/text | `[확인 필요: ...]` |
| Mentor rationale or question | gray comment where supported | `> 멘토 코멘트: ...` |

If the target surface already has a meaningful color convention, preserve it and either reuse it consistently or add a short legend. Do not rely on color alone; use labels, comments, or strikethrough so the comparison remains accessible.

## Revision rules

- Deletion means the original wording is weak, redundant, misleading, or misplaced. It does not mean the underlying experience never happened.
- A rewrite may change professional vocabulary, emphasis, narrative structure, and interpretation; it need not preserve the user's initial wording or framing. Label a new interpretation as a reframing proposal rather than a newly discovered fact. Do not silently introduce new historical claims.
- A newly discovered statement must be supported by the user's conversation or source material.
- An unresolved statement remains a question or placeholder and must not appear as fact in the clean copy.
- When content moves, mark the old location as moved and identify the new section; do not make it look deleted.
- Add a brief rationale only when the reason is not visually obvious.

## Interaction

Do not update the comparison after every conversational turn. When one topic stabilizes, ask whether the user wants it reflected now or wants to keep exploring.

After presenting the comparison, ask the user to accept, revise, or reject consequential changes. Produce a clean version only from accepted, evidence-backed content.

## Example

Original:

> AI 영상통화 서비스를 기획하고 자막과 아바타를 적용했다.

Comparison in Markdown:

> ~~AI 영상통화 서비스를 기획하고~~
>
> **[제안 문장] 기존 음성 AI 통화에서 반복되던 대화 중단 문제를 검증하기 위해 영상통화 PoC를 기획했다.**
>
> **[새로 발굴] 짧은 통화 표본의 대화 원문을 분류해 사용자가 AI 발화를 이해하지 못한 채 종료하는 패턴을 확인했다.**
>
> [확인 필요: 표본 수와 패턴의 발생 비율]

The example demonstrates annotation, not reusable facts.
