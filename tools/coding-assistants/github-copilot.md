---
name: GitHub Copilot
slug: github-copilot
vendor: GitHub (Microsoft)
category: coding-assistants
subcategory: ""
website: https://github.com/features/copilot
license_model: subscription, free, usage-based, enterprise
pricing_summary: "Free tier; from $10/mo individual; $19/seat Business"
status: active
first_reviewed: 2026-06-05
last_verified: 2026-06-05
recommendation: solid-choice
ratings:
  capability: 4
  ease_of_use: 5
  reliability: 3
  value: 4
  ecosystem: 5
  docs_support: 4
  privacy: 2
  momentum: 5
  portability: 3
disclosure: none
---

# GitHub Copilot

An AI coding assistant that adds completions, chat, and agent tasks inside the editor you already use. The safe default if your team is on GitHub.

**At a glance:** Solid choice | Subscription, free tier, enterprise | Free, from $10/mo individual, $19/seat Business

| Dimension | Score |
| --- | --- |
| Capability | 4 / 5 |
| Ease of use | 5 / 5 |
| Reliability | 3 / 5 |
| Value | 4 / 5 |
| Ecosystem | 5 / 5 |
| Docs and support | 4 / 5 |
| Privacy | 2 / 5 |
| Momentum | 5 / 5 |
| Portability | 3 / 5 |

## What it is

GitHub Copilot suggests code completions and runs chat and agent tasks inside editors like VS Code, Visual Studio, and JetBrains. It is a plugin, not a separate editor, so it sits on top of your current setup. It can use models from OpenAI, Anthropic, Google, and others, which you pick per task.

## Best for

- Teams already on GitHub, especially Business and Enterprise customers who want training-data exclusion by contract.
- Developers who want broad editor support and tight links to pull requests and Actions.
- Individuals who want a free or low cost completion tool and do not mind opting out of training.

## Not for

- Privacy sensitive individuals on Free or Pro who will not opt out of training on their code.
- People who want stable, predictable flat pricing, given the 2026 move to usage based credits.

## Pricing

Free tier exists. Paid individual plans start at $10/mo. Business is $19 per seat. Billing moved to usage based credits for all plans on 2026-06-01. Last verified 2026-06-05.

<details>
<summary><strong>Full pricing</strong></summary>

- **Free:** $0. About 2,000 completions per month and a limited model set.
- **Pro:** $10/user/mo, with a monthly credit allowance.
- **Pro+:** $39/user/mo, premium models including Claude Opus, larger allowance.
- **Max:** $100/user/mo, highest individual allowance.
- **Business:** $19 per seat/mo.
- **Enterprise:** $39 per seat/mo, and it requires GitHub Enterprise Cloud billed separately, so the real per seat cost is higher.

Notes: new signups for paid individual plans were paused starting 2026-04-20 (existing users keep or upgrade). The per-plan credit dollar amounts come from the marketing plans page and change more often than the headline prices, so treat them as approximate.

</details>

## Strengths

- Widest editor support: VS Code, Visual Studio, JetBrains, Neovim, Eclipse, and a CLI.
- Multiple model choices in one subscription (OpenAI GPT-5 family, Anthropic Claude, Google Gemini, xAI Grok).
- Tight integration with the GitHub platform: pull requests, code review, Actions.
- A genuine free tier so you can try it without paying.
- Backed by Microsoft and GitHub, so it is unlikely to disappear and has real enterprise support.

## Weaknesses and dealbreakers

- **Dealbreaker for privacy sensitive individuals:** since 2026-04-24, interaction data on Free, Pro, and Pro+ (including code snippets and context) is used to train models by default. You must opt out in settings. Business and Enterprise are excluded.
- The 2026 move to usage based credits makes costs less predictable, and paused individual signups for a stretch in 2026 disrupted new users.
- Inline completion context is limited, so it can miss project-wide conventions in large repos. Community sources cite roughly 8,000 tokens; the exact figure is not confirmed on an official page.
- Like all such tools it can hallucinate APIs and produce insecure code. Some 2026 reviews report quality changes tied to model swaps.

## Stability and maturity

Mature and widely deployed, generally available since 2022, backed by Microsoft. The company is stable, but 2026 brought frequent product changes: a billing overhaul on 2026-06-01, a training-data policy reversal on 2026-04-24, paused individual signups from 2026-04-20, and ongoing model swaps. Expect the terms and pricing to keep moving.

## Privacy and data

From 2026-04-24, Free, Pro, and Pro+ interaction data is used to train models unless you opt out under Copilot privacy settings. Business, Enterprise, and enterprise-owned repositories are excluded by contract. GitHub states data may be shared within the GitHub and Microsoft family but not with third-party model providers for training.

## Integrations

Editors: VS Code, Visual Studio, JetBrains, Neovim, Eclipse, Azure Data Studio, and the GitHub CLI. Strong across common languages, with Python, JavaScript, TypeScript, Go, C#, and C++ among the best supported. Models from OpenAI, Anthropic, Google, xAI, and Microsoft.

## Alternatives

- **[Cursor](cursor.md):** when you want a more powerful, agent-style in-editor experience and can budget usage based cost.
- **[Aider](aider.md):** when you want open source, your own model choice, and the terminal.

## Bottom line

**Solid choice**, and the safe default for teams on GitHub who want broad editor support with the least setup. Business and Enterprise customers also get training-data exclusion by contract, which matters. For individuals, the 2026 switch to training on your data by default is a real catch: usable, but opt out first. The move to usage based credits means you should watch your monthly cost rather than assume a flat fee.

## Sources

- [Copilot plans](https://github.com/features/copilot/plans): individual tier prices, credit amounts, paused signups. Seen 2026-06-05.
- [Copilot plans docs](https://docs.github.com/en/copilot/get-started/plans): Business $19/seat, Enterprise $39/seat, signup pause. Seen 2026-06-05.
- [Interaction data usage policy update](https://github.blog/news-insights/company-news/updates-to-github-copilot-interaction-data-usage-policy/): opt-out training from 2026-04-24, Free/Pro/Pro+ included, Business/Enterprise excluded. Seen 2026-06-05.
- [Billing and plans changelog](https://github.blog/changelog/2026-06-01-updates-to-github-copilot-billing-and-plans/): usage based billing live 2026-06-01, Max tier. Seen 2026-06-05.
- [Supported models](https://docs.github.com/en/copilot/reference/ai-models/supported-models): models by vendor. Seen 2026-06-05.

## Changelog

- 2026-06-05: First review.
