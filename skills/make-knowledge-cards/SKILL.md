---
name: make-knowledge-cards
description: "Convert pasted articles or local Markdown/TXT files into concise, source-grounded knowledge cards. Use when the goal is to learn or review key ideas, not to summarize web pages, PDFs, Anki decks, or a graphical interface."
---

# Make Knowledge Cards

Turn the supplied article or local `.md`, `.markdown`, or `.txt` file into a small set of high-value, standalone knowledge cards. Read the whole supplied content before selecting cards. For a local file, use its contents as the source; do not fetch URLs or attempt to process PDFs.

## Select the knowledge

- Identify the claims, concepts, mechanisms, distinctions, procedures, or decision rules that carry the article's learning value.
- Give each card exactly one coherent knowledge point. Split unrelated ideas; merge statements that explain the same point.
- Remove repetition, background filler, and details that do not improve understanding. Prefer the most central and broadly useful source-supported points.
- Aim for 5–8 cards only when the source genuinely contains that many independent important points. Produce fewer when it does not; never pad the set.
- Do not add facts, causes, qualifications, examples, names, numbers, or conclusions absent from the source. If a claim is uncertain or merely attributed in the source, preserve that framing.

## Write the cards

Use this format for every card:

```markdown
## 卡片 1：<short, specific title>
- 核心知识：<one precise statement of the point>
- 简明解释：<plain-language explanation based only on the source>
- 例子或自测：<a source example, or one short recall/application question>
```

Use a source example only when the article supplies it. Otherwise, write a short recall question using the card's source terms, whose answer can be derived from that card; do not provide an invented scenario or answer. Keep the wording compact and easy to review.

Before responding, check that every card has all four fields, covers a distinct point, and can be justified by the provided content. If the input is too short, ambiguous, or lacks substantive knowledge, say so plainly and return only the cards it supports (or no cards). State that web pages, PDFs, Anki export, and graphical interfaces are outside this skill's scope when requested.
