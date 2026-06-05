# Rating methodology

This page defines how WhichAI scores tools so that a 4 in one review means the same as a 4 in another. The scores are inputs to a decision. They are not the decision. The written verdict is what matters most.

## The two rules that keep scores honest

1. **The verdict is a judgment, not an average.** A tool can score well on most dimensions and still be the wrong pick because one dimension is a dealbreaker for a use case. We never compute a single mean and call it the answer.
2. **Context sets the weight.** Privacy matters more for a clinic than a hobby project. Each review notes which dimensions matter most for which readers.

## The 1 to 5 scale

Every dimension uses the same scale. Whole numbers only.

| Score | Meaning |
| --- | --- |
| 5 | Excellent. Among the best available. Hard to beat. |
| 4 | Good. Strong with minor gaps. |
| 3 | Adequate. Works, with real tradeoffs. |
| 2 | Weak. Notable problems that affect daily use. |
| 1 | Poor. A likely dealbreaker for most people. |

When a dimension cannot be assessed, mark it `N/A` and say why, rather than guessing.

## The nine dimensions

Open each one for its rubric and what we look at.

<details>
<summary><strong>1. Capability and output quality</strong></summary>

Does it do the core job well? Quality, accuracy, and range of what it produces.

| Score | Looks like |
| --- | --- |
| 5 | Best in class output. Handles hard cases that rivals fail. |
| 3 | Solid on common tasks, struggles on harder ones. |
| 1 | Output is unreliable or low quality for the core job. |

We look at: real output on representative tasks, credible third-party benchmarks (cited, not vendor claims alone), and how it handles edge cases.

</details>

<details>
<summary><strong>2. Ease of use and learning curve</strong></summary>

How quickly a new user gets value, and how much friction stays after that.

| Score | Looks like |
| --- | --- |
| 5 | Useful in minutes. Little to learn for the common path. |
| 3 | Usable after some setup or reading. |
| 1 | Steep setup or constant friction to get results. |

We look at: onboarding, setup steps, defaults, and how much expertise the common path needs.

</details>

<details>
<summary><strong>3. Reliability and stability</strong></summary>

Does it work consistently? Uptime, error rates, and how often updates break things.

| Score | Looks like |
| --- | --- |
| 5 | Dependable. Rare outages. Changes do not break workflows. |
| 3 | Mostly fine, with occasional outages or breaking changes. |
| 1 | Frequent outages, regressions, or breaking changes. |

We look at: public status history, breaking-change frequency, and the maturity of the release process.

</details>

<details>
<summary><strong>4. Value for money</strong></summary>

What you get for the price, across free, subscription, usage based, and enterprise.

| Score | Looks like |
| --- | --- |
| 5 | Strong value. Free or fairly priced for what it delivers. |
| 3 | Fair, but you can feel the cost or the limits. |
| 1 | Overpriced for the value, or limits make tiers near useless. |

We look at: real cost at typical usage, free tier usefulness, hidden limits, and value versus alternatives. Cheap is not automatically better and free is not automatically best.

</details>

<details>
<summary><strong>5. Ecosystem and integrations</strong></summary>

How well it fits the tools and workflows you already use.

| Score | Looks like |
| --- | --- |
| 5 | Connects to most things people need. Strong plugin or API support. |
| 3 | Covers the common integrations, gaps elsewhere. |
| 1 | Isolated. Few integrations, awkward to fit into a workflow. |

We look at: official integrations, API quality, plugins, and platform coverage.

</details>

<details>
<summary><strong>6. Documentation and support</strong></summary>

Can you get unstuck? Docs, help channels, and community knowledge.

| Score | Looks like |
| --- | --- |
| 5 | Clear, complete docs. Responsive support. Active community. |
| 3 | Docs cover the basics. Support is slow or limited. |
| 1 | Sparse or outdated docs. Little help when stuck. |

We look at: official docs, support responsiveness, and the size and health of the community.

</details>

<details>
<summary><strong>7. Privacy and data handling</strong></summary>

What happens to your data. This often decides whether a tool is usable at all for sensitive work.

| Score | Looks like |
| --- | --- |
| 5 | Does not train on your data by default, or runs fully local. Clear controls and terms. |
| 3 | Reasonable defaults with opt-outs you have to find and set. |
| 1 | Trains on your data with no real opt-out, or vague and risky terms. |

We look at: default training behavior, opt-out paths, retention, enterprise controls, and clarity of the terms.

</details>

<details>
<summary><strong>8. Momentum and longevity</strong></summary>

Is it likely to be here, and improving, a year from now?

| Score | Looks like |
| --- | --- |
| 5 | Active development, healthy adoption, stable backing. Low risk of going away. |
| 3 | Steady but uncertain. Slowing pace or thin backing. |
| 1 | Stalled, shrinking, or at clear risk of shutting down. |

We look at: release cadence, adoption, funding or backing, and for open source the contributor and maintainer health.

</details>

<details>
<summary><strong>9. Portability and lock-in</strong></summary>

How easily you can leave, take your work, or switch providers.

| Score | Looks like |
| --- | --- |
| 5 | Open formats, easy export, self-host or swap providers. Low lock-in. |
| 3 | Export exists but switching costs real effort. |
| 1 | Proprietary formats, no export, heavy lock-in. |

We look at: data export, open standards, self-hosting options, and how hard a real migration would be.

</details>

## Which dimensions matter most, by reader

A score is only useful once you know which dimensions count for you.

| Reader | Usually weights most |
| --- | --- |
| The builder (developer) | Capability, ecosystem, portability, reliability |
| The professional (task focused) | Capability, ease of use, value |
| The decision maker (team buyer) | Privacy, reliability, value, momentum, portability |
| The explorer (curious) | Ease of use, value, capability |

Reviews call out the weighting that fits the tool, so you are not left to guess.

## The verdict: recommendation tiers

Each review ends with one tier. The tier is a judgment that accounts for the scores, the dealbreakers, and who the tool is for.

| Tier | Meaning |
| --- | --- |
| **Top pick** | The one to beat in its category for a clearly named set of users. |
| **Solid choice** | Strong and recommendable, even if not the category leader. |
| **Situational** | The right call only for specific needs, named in the review. |
| **Caution** | Usable, but with real risks or gaps you must weigh first. |
| **Avoid for now** | Not recommendable today. The review says why and what would change it. |

A tier always comes with a sentence on who it applies to. No tool is a top pick for everyone.

## Honesty and conflicts

Scores and verdicts follow the editorial rules in [Requirements, section 5](requirements.md#5-our-promise-the-editorial-rules). In short: no paid placement, disclose conflicts, no affiliate influence, and state the dealbreakers. A review that breaks these rules does not get merged.

## Freshness

Volatile facts (pricing, model names, limits) carry a Last verified date and are re-checked on a roughly 90 day target. The overall verdict is revisited on a roughly 6 month target. Entries past their window are flagged for review rather than presented as current.

---

Back to [README](../README.md) | [Requirements](requirements.md) | [Tool entry template](tool-entry-template.md)
