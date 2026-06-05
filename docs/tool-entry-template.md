# Tool entry template

Every tool review uses this format. It keeps reviews comparable, machine readable, and honest. To add a tool, copy the skeleton at the bottom into `tools/<category>/<slug>.md` and fill it in.

Read the [rating methodology](rating-methodology.md) before scoring, and the [editorial rules](requirements.md#5-our-promise-the-editorial-rules) before writing.

## The front matter

A small block of structured fields at the very top of the file, between `---` lines. This lets the content power an index or a website later without a rewrite. Every field is required unless marked optional.

| Field | Meaning |
| --- | --- |
| `name` | The tool's display name |
| `slug` | Lowercase, hyphenated id. Matches the filename |
| `vendor` | Company or maintainer |
| `category` | The category folder this lives in |
| `subcategory` | Optional, finer grouping |
| `website` | Official site |
| `license_model` | One or more of: open-source, free, subscription, usage-based, enterprise |
| `pricing_summary` | One line, for example "From $10/mo, free tier available" |
| `status` | active, beta, or deprecated |
| `first_reviewed` | Date the first review was written |
| `last_verified` | Date the volatile facts were last checked |
| `recommendation` | top-pick, solid-choice, situational, caution, or avoid-for-now |
| `ratings` | The nine dimension scores, 1 to 5, or `N/A` |
| `disclosure` | `none`, or a plain statement of any conflict of interest |

## The body sections

In order:

1. **Title and one-liner.** The name, then a single sentence on what it is and who it is for.
2. **At a glance.** The recommendation tier, license model, and price in one line, plus the ratings table.
3. **What it is.** Two or three sentences, plain language.
4. **Best for / Not for.** Who should use it, and who should not. Be specific.
5. **Pricing.** A short summary, with the full tier breakdown in a collapsible block. Always dated.
6. **Strengths.** Concrete points, not adjectives.
7. **Weaknesses and dealbreakers.** Honest limits. Name at least one dealbreaker.
8. **Stability and maturity.** Backing, release pace, breaking changes, track record.
9. **Privacy and data.** Default training behavior, opt-outs, retention, enterprise controls.
10. **Integrations.** What it connects to and how you run it.
11. **Alternatives.** Two or three other tools and when each beats this one.
12. **Bottom line.** The verdict, in words, with the recommendation tier and who it applies to.
13. **Sources.** Dated links for the volatile facts.
14. **Changelog.** Dated list of edits, so corrections are visible.

## The skeleton to copy

````markdown
---
name: Example Tool
slug: example-tool
vendor: Example Inc
category: coding-assistants
subcategory: ""
website: https://example.com
license_model: subscription
pricing_summary: "From $10/mo, free tier available"
status: active
first_reviewed: 2026-06-05
last_verified: 2026-06-05
recommendation: solid-choice
ratings:
  capability: 4
  ease_of_use: 4
  reliability: 4
  value: 3
  ecosystem: 4
  docs_support: 4
  privacy: 3
  momentum: 4
  portability: 3
disclosure: none
---

# Example Tool

One sentence on what it is and who it is for.

**At a glance:** Solid choice | Subscription, free tier | From $10/mo

| Dimension | Score |
| --- | --- |
| Capability | 4 / 5 |
| Ease of use | 4 / 5 |
| Reliability | 4 / 5 |
| Value | 3 / 5 |
| Ecosystem | 4 / 5 |
| Docs and support | 4 / 5 |
| Privacy | 3 / 5 |
| Momentum | 4 / 5 |
| Portability | 3 / 5 |

## What it is

Two or three plain sentences.

## Best for

- Who should use it, and for what.

## Not for

- Who should look elsewhere, and why.

## Pricing

One line summary. Last verified 2026-06-05.

<details>
<summary><strong>Full pricing</strong></summary>

- Tier and price, with what you get.

</details>

## Strengths

- Concrete point.

## Weaknesses and dealbreakers

- Honest limit. Name at least one real dealbreaker.

## Stability and maturity

Backing, release pace, breaking changes, track record.

## Privacy and data

Default training behavior, opt-outs, retention, enterprise controls.

## Integrations

What it connects to and how you run it.

## Alternatives

- **Other tool A:** when it beats this one.
- **Other tool B:** when it beats this one.

## Bottom line

The verdict in words, the recommendation tier, and who it applies to.

## Sources

- [Title](https://example.com): what it confirmed. Seen 2026-06-05.

## Changelog

- 2026-06-05: First review.
````

---

Back to [README](../README.md) | [Rating methodology](rating-methodology.md) | [Contributing](../CONTRIBUTING.md)
