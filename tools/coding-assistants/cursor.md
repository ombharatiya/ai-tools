---
name: Cursor
slug: cursor
vendor: Anysphere
category: coding-assistants
subcategory: ""
website: https://cursor.com
license_model: subscription, free, usage-based, enterprise
pricing_summary: "Free tier; from $20/mo individual; usage based overage"
status: active
first_reviewed: 2026-06-05
last_verified: 2026-06-05
recommendation: solid-choice
ratings:
  capability: 5
  ease_of_use: 4
  reliability: 3
  value: 2
  ecosystem: 4
  docs_support: 4
  privacy: 3
  momentum: 5
  portability: 3
disclosure: none
---

# Cursor

A standalone AI code editor, built as a fork of VS Code, with AI woven into the editor itself. The most powerful in-editor experience, if you can stomach the pricing.

**At a glance:** Solid choice | Subscription, free tier, usage based | Free, from $20/mo

| Dimension | Score |
| --- | --- |
| Capability | 5 / 5 |
| Ease of use | 4 / 5 |
| Reliability | 3 / 5 |
| Value | 2 / 5 |
| Ecosystem | 4 / 5 |
| Docs and support | 4 / 5 |
| Privacy | 3 / 5 |
| Momentum | 5 / 5 |
| Portability | 3 / 5 |

## What it is

Cursor is an AI code editor built on the open source VS Code base, with AI features in the editor rather than added as a plugin. It does autocomplete, multi-file edits, chat, and autonomous agent runs over your codebase. Because it is a full editor, it can do multi-file and agent work that a plugin cannot do as directly.

## Best for

- Developers and teams who want the strongest in-editor AI experience and do heavy multi-file or agent work.
- People comfortable adopting a VS Code based editor, which keeps most extensions, keybindings, and themes.
- Anyone who can budget for, or carefully cap, usage based cost.

## Not for

- Anyone who needs strictly predictable monthly costs.
- Teams locked into a non VS Code toolchain.
- Privacy sensitive users who will not verify and enforce Privacy Mode.

## Pricing

Free Hobby tier. Individual paid from $20/mo with included usage, then pay as you go overage. Last verified 2026-06-05.

<details>
<summary><strong>Full pricing</strong></summary>

- **Hobby:** $0, no card, limited agent requests and completions.
- **Pro:** $20/mo, includes about $20 of API usage value plus a separate completion pool.
- **Pro+:** $60/mo, includes about $70 of API usage value.
- **Ultra:** $200/mo, includes about $400 of API usage value.
- **Teams Standard:** $40/user/mo, or $32/user/mo billed annually.
- **Teams Premium:** $120/user/mo, or $96/user/mo annually, with 5x the Standard usage.
- **Enterprise:** custom.

Teams changes took effect 2026-06-01 for new customers and 2026-07-01 for renewals. The marketing page nests the individual tiers under a single $20 entry; the per-tier prices above come from the official docs.

</details>

## Strengths

- AI is built into the editor, enabling multi-file edits, inline diffs, and agent workflows a plugin cannot match.
- Built on VS Code, so most extensions, keybindings, and themes carry over and the learning curve is low for VS Code users.
- Access to frontier models from several providers, plus support for MCP, skills, and hooks.
- Strong autocomplete and a Composer agent that many developers rate highly for daily coding.
- Privacy Mode with zero data retention agreements at model providers, enforceable across an org on Teams and Enterprise.

## Weaknesses and dealbreakers

- **Dealbreaker for predictable budgets:** pricing has been a repeated trust problem. A 2025 shift to compute and credit based limits, then a mid-2026 restructuring, led to reports of bills far above the old roughly $20/mo expectation, with some users citing hundreds of dollars in days. The most extreme figures come from user reports, not official sources, but the pattern is well documented.
- The credit model is hard to predict; heavy agent and long-context use burns through included usage quickly.
- It is a separate editor you must adopt. If your team standardizes elsewhere, that is friction.
- As a VS Code fork it can lag upstream VS Code, and some Microsoft-licensed extensions may be unavailable.
- With Privacy Mode off, Cursor may store and train on your code, prompts, and editor actions, so the default settings need checking per user.

## Stability and maturity

Younger than Copilot. Anysphere was founded in 2022 and the product saw wide adoption from 2023 onward. It is heavily venture funded but does not have a large parent company behind it. The product changes quickly, and the 2025 to 2026 pricing changes caused notable backlash, so expect frequent change.

## Privacy and data

Privacy Mode is opt-in for individuals. When on, it guarantees zero data retention at model providers and no training on your code by Cursor or third parties. With it off, Cursor may store and use your codebase data, prompts, and editor actions to improve and train its models. Privacy Mode can be enforced across an org on Teams and Enterprise. Enterprise adds audit logs, an AI code tracking API, access controls, and SOC 2 Type II on request. Whether Privacy Mode is on by default for Enterprise is not confirmed on the official data-use page, so verify it.

## Integrations

The editor inherits the VS Code extension ecosystem and broad language support. Supports MCP, skills, hooks, cloud agents, and a Bugbot code reviewer. Frontier models from OpenAI, Anthropic, Google, and xAI are selectable.

## Alternatives

- **[GitHub Copilot](github-copilot.md):** when you want predictable plans, broad editor support, and a large vendor.
- **[Aider](aider.md):** when you want open source and your own model choice from the terminal.

## Bottom line

**Solid choice**, and arguably the best in-editor AI for developers doing heavy multi-file and agent work, if you adopt a VS Code based editor. The catch is cost. The usage based model has produced surprise bills, so set a budget and watch it. If predictable spend matters more than peak capability, Copilot is the calmer pick.

## Sources

- [Cursor account pricing docs](https://cursor.com/docs/account/pricing): per-tier prices and included usage. Seen 2026-06-05.
- [Cursor pricing](https://cursor.com/pricing): Hobby free, Individual entry, Teams, Enterprise. Seen 2026-06-05.
- [Teams pricing change](https://cursor.com/blog/teams-pricing-june-2026): 2026-06-01 Teams change and effective dates. Seen 2026-06-05.
- [Cursor data use](https://cursor.com/data-use): Privacy Mode behavior and training when off. Seen 2026-06-05.
- [Pricing backlash timeline](https://www.wearefounders.uk/cursors-pricing-disaster-the-full-timeline-of-how-an-ai-coding-darling-burned-its-most-loyal-users/): secondary account of 2025 to 2026 cost complaints. Seen 2026-06-05.

## Changelog

- 2026-06-05: First review.
