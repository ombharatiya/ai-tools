---
name: Claude
slug: claude
vendor: Anthropic
category: ai-assistants
subcategory: ""
website: https://claude.ai
license_model: free, subscription, usage-based, enterprise
pricing_summary: "Free tier; Pro $17/mo; Max from $100/mo; API usage based"
status: active
first_reviewed: 2026-06-05
last_verified: 2026-06-05
recommendation: top-pick
ratings:
  capability: 5
  ease_of_use: 4
  reliability: 4
  value: 4
  ecosystem: 4
  docs_support: 4
  privacy: 4
  momentum: 5
  portability: 3
disclosure: none
---

# Claude

Anthropic's assistant, known for coding and long-document work and a privacy default of not training on your chats. The pick for developers and the privacy conscious.

**At a glance:** Top pick | Free, subscription, enterprise | Free, from $17/mo

| Dimension | Score |
| --- | --- |
| Capability | 5 / 5 |
| Ease of use | 4 / 5 |
| Reliability | 4 / 5 |
| Value | 4 / 5 |
| Ecosystem | 4 / 5 |
| Docs and support | 4 / 5 |
| Privacy | 4 / 5 |
| Momentum | 5 / 5 |
| Portability | 3 / 5 |

## What it is

Claude is a general assistant for writing, analysis, coding, and long-document work, used through chat, desktop apps, and a coding tool. It runs on the Claude 4 model family, with Opus 4.8 as the flagship (1M-token context), Sonnet 4.6 for balance, and Haiku 4.5 for speed. It is known for strong coding and a safety-focused design.

## Best for

- Developers and technical teams. Its coding tool and agentic work are mature.
- People doing long-document analysis who need a large context window.
- Writers and analysts who value a no-training-by-default posture and no ads.

## Not for

- People who want strong built-in image generation or voice.
- Casual users who want the broadest consumer feature set.
- Heavy individual users who want an annual discount on the top usage tier.

## Pricing

Free tier. Pro is $17/mo billed annually, or $20 monthly. Max starts at $100/mo. Read directly from the pricing page during research. Last verified 2026-06-05.

<details>
<summary><strong>Full pricing</strong></summary>

- **Free:** $0. Web, mobile, and desktop apps, with daily limits.
- **Pro:** $17/mo billed annually, or $20 monthly. Adds more usage, the coding tool, projects, research, and more models.
- **Max:** from $100/mo. Choose 5x or 20x more usage than Pro; the 20x tier is widely reported at $200/mo. Monthly only, no annual discount.
- **Team:** $20/seat/mo annual or $25 monthly (Standard); higher Premium tier; 5-seat minimum.
- **Enterprise:** $20/seat plus API usage, with SSO, SCIM, audit logs, custom retention, and a HIPAA-ready option.

</details>

## Strengths

- Among the best for coding and agentic, long-horizon work, with mature developer tooling.
- Very large context window (1M tokens on the flagship and balanced models), good for whole-codebase or large-document analysis.
- Does not train on your conversations unless you turn it on. This is a stronger default than ChatGPT or Gemini.
- No ads on any tier.
- Strong enterprise data controls (SSO, SCIM, audit logs, custom retention, HIPAA-ready), with a clear split between consumer and commercial data terms.

## Weaknesses and dealbreakers

- **Privacy caveat to read carefully:** while training is off by default, the training toggle is presented during onboarding, and if you accept it, data retention jumps from 30 days to 5 years. Press coverage framed this as "opt out or share your chats," because many people click through the prompt. If training stays off, retention stays at 30 days.
- **Dealbreaker for some:** the consumer feature set is smaller than ChatGPT. Image generation and voice are weak or absent.
- Free tier daily limits are fairly tight, so heavy users hit caps quickly.
- The higher-usage Max tiers are monthly only, so heavy individual use gets expensive with no annual discount.
- Had reliability incidents during the early-May 2026 window that hit all major providers.

## Stability and maturity

Backed by Anthropic with major Amazon and Google investment, and served through Anthropic's API, AWS Bedrock, Google Vertex AI, and Microsoft Foundry. Mature for text and coding. The model cadence is fast (Opus 4.5 to 4.8 within roughly seven months), but the naming is orderly across the Opus, Sonnet, and Haiku tiers.

## Privacy and data

For Free, Pro, and Max, training happens only if you turn the setting on. With it on, retention is 5 years for new or resumed chats. With it off, retention is 30 days, and you can change the setting anytime. Deleting a conversation excludes it from future training. Commercial products (Team, Enterprise, and the API) are not used for training by default. This is the strongest default of the three big assistants, with the 5-year retention being the catch if you accept the prompt.

## Integrations

Web, iOS, Android, native desktop apps, a terminal and IDE coding tool, and the developer API. Connectors via MCP, plus Google Workspace and Microsoft 365 integrations on paid tiers. Also available through AWS Bedrock, Google Vertex AI, and Microsoft Foundry.

## Alternatives

- **[ChatGPT](chatgpt.md):** when you want the broadest features, including strong image generation and voice.
- **[Gemini](gemini.md):** when you want AI inside Google products and built-in image and video generation.

## Bottom line

**Top pick** for coding, long-document work, and anyone who wants a privacy default of no training unless you opt in, with no ads. The honest tradeoffs: a smaller consumer feature set than ChatGPT, weak or absent image and voice, and a 5-year retention window if you accept the training prompt during onboarding. If you want an all-purpose consumer assistant with every feature, ChatGPT is broader. For building, analysis, and privacy, Claude leads.

## Sources

- [Claude pricing](https://claude.com/pricing): Free, Pro $17 annual / $20 monthly, Max from $100, Team, Enterprise. Read directly. Seen 2026-06-05.
- [Claude models overview](https://platform.claude.com/docs/en/about-claude/models/overview): Opus 4.8 flagship with 1M context, Sonnet 4.6, Haiku 4.5. Read directly. Seen 2026-06-05.
- [Opus 4.8 release](https://www.anthropic.com/news/claude-opus-4-8): flagship release 2026-05-28. Seen 2026-06-05.
- [Consumer terms update](https://www.anthropic.com/news/updates-to-our-consumer-terms): opt-in training, 5-year vs 30-day retention, commercial exclusion. Read directly. Seen 2026-06-05.
- [Independent coverage of the data policy change](https://techcrunch.com/2025/08/28/anthropic-users-face-a-new-choice-opt-out-or-share-your-data-for-ai-training/): how the onboarding choice is presented. Seen 2026-06-05.

## Changelog

- 2026-06-05: First review.
