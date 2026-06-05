---
name: Aider
slug: aider
vendor: Aider-AI (Paul Gauthier and community)
category: coding-assistants
subcategory: ""
website: https://aider.chat
license_model: open-source
pricing_summary: "Free tool (Apache 2.0); you pay only for the LLM you connect"
status: active
first_reviewed: 2026-06-05
last_verified: 2026-06-05
recommendation: solid-choice
ratings:
  capability: 4
  ease_of_use: 2
  reliability: 3
  value: 5
  ecosystem: 4
  docs_support: 3
  privacy: 5
  momentum: 3
  portability: 5
disclosure: none
---

# Aider

An open source command line pair programmer that edits code in your local Git repo using whatever model you choose. Free, model agnostic, and private.

**At a glance:** Solid choice | Open source (Apache 2.0) | Free tool, pay for model use

| Dimension | Score |
| --- | --- |
| Capability | 4 / 5 |
| Ease of use | 2 / 5 |
| Reliability | 3 / 5 |
| Value | 5 / 5 |
| Ecosystem | 4 / 5 |
| Docs and support | 3 / 5 |
| Privacy | 5 / 5 |
| Momentum | 3 / 5 |
| Portability | 5 / 5 |

## What it is

Aider is a command line tool that edits code in your local Git repository by talking to a language model you pick. It is model agnostic and bring your own key, so the tool is free and you pay only for the model usage, or nothing if you run a local model. It commits each accepted change to Git, so everything is easy to review and undo.

## Best for

- Developers who like the command line and Git and want full control over which model they use.
- People who want an open source, privacy preserving tool with no subscription lock-in.
- Anyone who wants to run a local or offline model, or manage model costs directly.

## Not for

- Developers who want a GUI with inline ghost-text autocomplete and visual diffs.
- Teams that need vendor support, SLAs, or an enterprise contract.
- Anyone uncomfortable with the terminal and Git.

## Pricing

The tool is free under Apache 2.0. There is no hosted service to buy. Your only cost is the model API usage from whatever provider you connect, or zero with a local model. Last verified 2026-06-05.

<details>
<summary><strong>How cost works</strong></summary>

- The Aider tool itself: $0, open source.
- Model usage: whatever your chosen provider charges (for example Anthropic, OpenAI, DeepSeek, Google), billed by them.
- Local model via Ollama: $0 to run, you just need the hardware.

Some reviews cite roughly $10/mo of API usage for moderate use, but the real figure depends entirely on your model and how much you use it.

</details>

## Strengths

- Free and open source (Apache 2.0), fully usable with your own keys or local models.
- Model agnostic through LiteLLM, so you are not locked to one vendor and can switch as models improve.
- Strong Git integration: a commit per accepted change with a generated message, so changes are easy to diff and undo.
- Builds a repository map to work across larger codebases, and you control exactly which files are in context.
- Works in any terminal, alongside any editor, so it does not force a tool switch.

## Weaknesses and dealbreakers

- **Dealbreaker for IDE-style workflows:** terminal only. No GUI, no inline autocomplete, no built-in visual diff viewer or debugger.
- You must explicitly add files to the chat context. It does not auto-navigate the codebase the way IDE tools do.
- Costs are on you and can be unpredictable in heavy sessions, since there is no usage cap.
- No vendor support, SLAs, or enterprise contract. Support is community based.
- Momentum looks slower than the big commercial tools. The last tagged stable release on GitHub is v0.86.0, dated 2025-08-09, even though commits continued into 2026. Worth checking the current state before you rely on it.

## Stability and maturity

Mature and popular for an independent project, with roughly 45,800 GitHub stars, 90 plus releases, and 13,000 plus commits. It is largely associated with one primary maintainer, so the bus factor and release cadence are real risks. Because it depends on external model APIs, its behavior also shifts when those models change.

## Privacy and data

Strong, and the best in this category. The Aider tool does not train on your code and, per its analytics docs, never collects your code, chat, keys, or personal info. Analytics are opt-in, and when enabled only usage metrics go to PostHog under a random id. You can disable analytics permanently or per session. The one caveat: whatever model provider you connect has its own data policy, so your code does leave your machine to that provider unless you run a local model.

## Integrations

Interface: terminal and CLI, usable next to any editor. Models: many providers via LiteLLM, including Anthropic Claude, OpenAI, DeepSeek, Google Gemini, and local models through Ollama. Languages: Python, JavaScript, Rust, Ruby, Go, C++, PHP, and many more. Version control: native Git with automatic commits, diffs, and undo.

## Alternatives

- **[Cursor](cursor.md):** when you want a powerful GUI editor with inline AI and visual diffs.
- **[GitHub Copilot](github-copilot.md):** when you want inline completion in your existing editor with vendor support.

## Bottom line

**Solid choice**, and the clear pick for developers who value open source, want to choose their own model (including local and free), and are comfortable in the terminal and Git. It is also the strongest privacy option here. If you want a polished GUI with inline suggestions, or you need vendor support, look at Cursor or Copilot instead. Check the current release activity before betting a team on it.

## Sources

- [Aider on GitHub](https://github.com/Aider-AI/aider): Apache 2.0, stars, Git auto-commit, model and language support, last tagged release v0.86.0 dated 2025-08-09. Seen 2026-06-05.
- [Aider homepage](https://aider.chat/): what it is, repo map, free tool with pay-for-model. Seen 2026-06-05.
- [Aider analytics docs](https://aider.chat/docs/more/analytics.html): opt-in analytics, never collects code or keys, disable flags. Seen 2026-06-05.
- [Aider LLM support](https://aider.chat/docs/llms.html): broad provider support including local models. Seen 2026-06-05.

## Changelog

- 2026-06-05: First review.
