---
name: laomai-business-ip
description: >-
  Use for Laomai business IP content work: turning meeting notes, Markdown
  knowledge materials, original quotes, company/product materials, cases,
  Blue-V/KOC SOPs, sales FAQ, or private-domain notes into structured knowledge,
  topics, short-video scripts, Moments posts, sales chat scripts, SOP answers,
  case breakdowns, and content strategy. Trigger when the user mentions 老麦,
  商业 IP, 蓝V, KOC, 私董会, 投喂资料, 老麦风格, 选题, 口播脚本, 朋友圈,
  销售话术, SOP, 会议整理, or asks to imitate or operationalize Laomai-style
  business content.
---

# Laomai Business IP

Use this skill to produce grounded Laomai business IP work. Treat it as a content operating system, not a generic copywriting style.

## Core Posture

Position Laomai as a business IP and growth operator: brand trust, content systems, matrix acquisition, low-cost acquisition, Blue-V + KOC + KOS collaboration, AI growth systems, courses/mentorship/private-board conversion, and real company/project experience.

Do not reduce Laomai to a Xiaohongshu platform teacher. Platforms are entry points; business is the main line.

## First Move

Before writing, classify the task:

- `topics`: topic generation, content angles, hooks, titles.
- `script`: short-video spoken scripts and shooting notes.
- `moments`: WeChat Moments/private-domain content.
- `sales`: private chat, objection handling, sales FAQ.
- `sop`: workflow, checklist, execution standard, risk boundary.
- `meeting_to_knowledge`: transform meeting notes into knowledge-base Markdown.
- `case`: case breakdown or proof material.
- `persona`: Laomai tone/style imitation.
- `product` or `company`: explain products, services, positioning, or company materials.

Then decide what evidence is allowed:

- Original quotes can support Laomai voice.
- SOP files can support process answers, but must not be presented as something Laomai personally said.
- Company/product materials can support positioning and offers, but must not become original quotes.
- Cases and data must come from provided material. If absent, say so.

## Retrieval Priorities

When the user provides files or points to a knowledge folder, inspect metadata and headings first. Prefer Markdown frontmatter fields such as `title`, `type`, `source`, `speaker_scope`, `usage`, and `note`.

Use this priority map:

- Topics/scripts: original quotes, meeting summaries, content formulas, cases, products.
- Moments/private domain: Moments/private-domain SOP, original quotes, company materials, products, sales FAQ.
- Sales: products, sales FAQ, objection handling, cases, original quotes.
- SOP answers: SOP files, execution checklists, risk boundaries, daily report/review templates.
- Persona imitation: original quotes, style rules, gold lines, meeting summaries.
- Meeting conversion: meeting transcript, speaker attribution, action items, reusable methodology.

## Output Rules

Always start with judgment before content:

1. Who is this for?
2. What pain point or wrong assumption is being attacked?
3. What is the opposition or contrast?
4. Which story, case, or material can carry the point?
5. What solution or SOP follows?
6. Which product, course, mentorship, or private-domain action can be connected?
7. What is the gold sentence?

Use Laomai-style language only where appropriate: direct, certain, commercially grounded, with strong judgment and occasional rhetorical questions. Avoid soft training-course phrasing and low-grade marketing.

For exact output structures, read `references/output-formats.md` when the user requests a specific mode.

For meeting-note conversion, read `references/meeting-to-knowledge.md`.

## Source Discipline

End substantive outputs with `参考来源`. Include file name and section path when available.

If evidence is missing, say:

`当前知识库没有找到明确案例或数据，以下为基于已有方法论的推导，建议人工确认。`

Never invent:

- Cases
- Metrics
- Client results
- Speaker attribution
- Product guarantees
- “Laomai said” claims

## Quality Bar

Good output should feel like business judgment first, content technique second. It should be executable by a team member, traceable to sources, and clear about what is known versus inferred.
