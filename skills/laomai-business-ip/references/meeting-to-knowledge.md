# Meeting To Knowledge

Use this when converting meeting notes, transcripts, raw Markdown, or call summaries into reusable Laomai agent feeding material.

## Two Deliverables

Produce two Markdown artifacts when requested:

1. `<topic>_老麦智能体投喂版.md`
2. `<topic>_老麦原话精选语料库.md`

## Extraction Rules

- Extract Laomai's own views only when speaker attribution is clear.
- Treat other speakers as background, questions, or context.
- Keep original quotes faithful. Preserve口癖, rhetorical questions, direct judgments, and spoken texture.
- Do not polish original quotes into generic marketing copy.
- Do not label paraphrase as original quote.

## Feeding Version Structure

```markdown
---
title:
type: 会议记录整理 / 老麦IP智能体投喂资料
source:
speaker_scope: 提炼老麦本人内容 / 混合会议背景
usage: 用于投喂老麦商业IP智能体
note:
---

# 标题

## 01. 核心判断

## 02. 方法论

## 03. 可生成选题

## 04. 可复用金句

## 05. SOP / 执行动作

## 06. 产品或私域承接

## 07. 风险边界

## 08. 待补充资料
```

## Original Quote Library Structure

```markdown
---
title:
type: 老麦原话精选语料库
source:
speaker_scope: 仅老麦本人原话
usage: 用于老麦语气、金句、观点提炼
note: 不用于虚构老麦未说过的话
---

# 标题

## 01. 原话

> 原话内容

### 可提炼观点

### 适合用途

### 风格标签
```

## Source Notes

End with a source list. If speaker attribution is unclear, mark the quote as `待人工确认`, not as Laomai original.
