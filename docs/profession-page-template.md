# Profession page template

Profession pages answer one question: "I do this job, what AI tools and apps should I use?" They map a role's real tasks to the tools that help, link to full reviews where we have them, and stay honest about what is not yet verified.

Copy the skeleton at the bottom into `professions/<slug>.md`.

## Two rules that keep these pages honest

1. **No invented scores or prices.** Profession pages do not carry the nine-dimension ratings. Those live in the full [tool reviews](../tools/README.md). Here we use coarse price labels only (see below). A tool we have not reviewed yet is named and marked `(review pending)`, never given a score or a precise price we have not checked.
2. **Link, do not duplicate.** When a tool has a full review, link to it. The review holds the detail, the pricing, and the verdict.

## Price labels

Use one short label per tool, not a dollar figure. Exact prices change too fast to repeat on every page, and they belong in the review or on the vendor's site.

| Label | Meaning |
| --- | --- |
| `free` | Genuinely free to use |
| `freemium` | Free tier, with paid upgrades |
| `paid` | Subscription only, no useful free tier |
| `enterprise` | Custom or quote-based, sales-led |
| `open source` | Run it yourself, code is open |

## Tool naming convention

- Reviewed tool: link it, for example `[ChatGPT](../tools/ai-assistants/chatgpt.md)`.
- Not yet reviewed: bold the name and add the label and `(review pending)`, for example `**Otter.ai** (freemium, review pending)`.

## The skeleton to copy

````markdown
---
name: Example Profession
slug: example-profession
sector: Example sector
last_verified: 2026-06-05
related_categories: [ai-assistants, coding-assistants]
---

# AI tools and apps for an Example Profession

One sentence on the role and what this page covers.

## Who this is for

A line or two on the variations of this role the page serves.

## Starter stack

The three to five tools to try first, in plain order of priority.

1. **Tool** (label): why start here.

## Tasks and the tools that help

### Task one

- **Tool** (label): what it does for this task. Link if reviewed.
- **Tool** (label, review pending): what it does.

### Task two

- **Tool** (label): what it does.

## Cautions for this profession

- The honest warnings: privacy, accuracy, compliance, cost. Be specific.

## How to choose

A short paragraph on the main tradeoff for this role.

## Related

- Categories: links to the relevant `docs/categories.md` groups.
- Reviews: links to the most relevant full reviews.

## Sources

- [Title](https://example.com): what it confirmed. Seen 2026-06-05.

## Changelog

- 2026-06-05: First version.
````

---

Back to [README](../README.md) | [Professions](../professions/README.md) | [Contributing](../CONTRIBUTING.md)
