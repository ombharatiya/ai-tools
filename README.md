# WhichAI

**Find the right AI tool or app for your use case. Honest reviews, side by side comparisons, and clear ratings across every profession and domain.**

WhichAI is a community guide to AI tools and apps. The goal is simple: when you have a task in mind, or you just want to know what your profession is using, you should be able to come here and get the kind of recommendation a knowledgeable friend would give you. Not the loudest product. Not the best marketed one. The one that actually fits what you need.

We cover every kind of AI product: developer tools and everyday apps, open source, free, subscription, and enterprise. You can start two ways, by profession ("I am a teacher, what should I use?") or by domain ("I want an image generator"). No category is off limits, as long as it is genuinely powered by AI.

> Honesty first. We do not take payment for placement or ratings. If a free or open source tool is the better pick, we say so. See [our promise](docs/requirements.md#5-our-promise-the-editorial-rules).

---

## How to use this repository

```mermaid
flowchart LR
    A[Start: your profession or your task] --> B{How do you want to look?}
    B -- By profession --> P[Open your profession page]
    B -- By category --> C[Open the category]
    B -- Not sure --> D[Browse all categories]
    P --> E
    D --> C
    C --> E[Scan the shortlist and ratings]
    E --> F[Read the full review]
    F --> G[Compare your finalists]
    G --> H[Decide and get started]
```

| If you want to... | Go to |
| --- | --- |
| Find AI tools and apps for your profession | [Professions](professions/README.md) |
| Understand what this project is and how it works | [Requirements and specification](docs/requirements.md) |
| Browse tools by domain | [Categories](docs/categories.md) |
| See how we score and rate tools | [Rating methodology](docs/rating-methodology.md) |
| Read a tool review | [All tools](tools/README.md) |
| Compare tools head to head | [Comparisons](comparisons/README.md) |
| Add or correct a tool | [Contributing](CONTRIBUTING.md) |

---

## Browse by profession

New here? Start with your job. Each profession page maps the real tasks you do to the AI tools and apps that help, with honest notes on what is worth paying for and what to watch out for.

**Dedicated pages:**

| | | |
| --- | --- | --- |
| [Software Developer](professions/software-developer.md) | [Writer](professions/writer.md) | [Marketer](professions/marketer.md) |
| [Designer](professions/designer.md) | [Teacher](professions/teacher.md) | [Student](professions/student.md) |
| [Doctor and Clinician](professions/doctor.md) | [Lawyer](professions/lawyer.md) | [Accountant](professions/accountant.md) |
| [Sales Professional](professions/sales.md) | [Customer Support](professions/customer-support.md) | [Small Business Owner](professions/small-business-owner.md) |

More professions are planned. See them all, and suggest your own, in [Professions](professions/README.md).

---

## Browse by domain

The starter set below has full reviews today. The rest of the map is planned and open for contributions. See the full taxonomy in [Categories](docs/categories.md).

**Available now:**

- [Coding assistants](tools/coding-assistants/README.md): GitHub Copilot, Cursor, Aider
- [General AI assistants](tools/ai-assistants/README.md): ChatGPT, Claude, Gemini
- [Image generation](tools/image-generation/README.md): Midjourney, DALL-E, Stable Diffusion

<details>
<summary><strong>See the full domain map (planned coverage)</strong></summary>

- Build and code
- Write and edit
- Converse and assist
- Images and design
- Audio and music
- Video
- Knowledge and research
- Data and analytics
- Business and productivity
- Developer platforms (model APIs, agents, vector stores, evals)
- Marketing and media
- Education and learning
- Regulated verticals (health, legal, finance)
- Agents and automation
- Security

Full breakdown with subcategories: [Categories](docs/categories.md).

</details>

---

## How ratings work

Every tool is scored on nine dimensions, each on a 1 to 5 scale with a written rubric, so the scores mean the same thing across reviews.

| Dimension | What it measures |
| --- | --- |
| Capability | How well it does the core job |
| Ease of use | How quickly you get value, learning curve |
| Reliability | Stability, uptime, how often it breaks |
| Value | What you get for the price |
| Ecosystem | Integrations, plugins, platform support |
| Docs and support | Quality of docs, help, community |
| Privacy | Data handling, training on your data, controls |
| Momentum | Active development, adoption, longevity |
| Portability | Export, open standards, lock-in risk |

Scores are inputs, not the verdict. The bottom line is a written judgment about who the tool fits and who it does not. Details in [Rating methodology](docs/rating-methodology.md).

---

## Contributing

Anyone can suggest a tool, correct a detail, or write a full review. Start with [CONTRIBUTING.md](CONTRIBUTING.md). The short version:

1. Use the [tool entry template](docs/tool-entry-template.md).
2. Cite your sources and date them.
3. Be honest and balanced. State the dealbreakers.
4. Disclose any affiliation with the tool.

<details>
<summary><strong>Repository map</strong></summary>

```text
WhichAI/
  README.md                      You are here
  CONTRIBUTING.md                How to add or correct an entry
  CODE_OF_CONDUCT.md             Community standards
  docs/
    README.md                    Docs index
    requirements.md              What this project is, in full
    categories.md                The domain taxonomy
    rating-methodology.md        How scoring and verdicts work
    tool-entry-template.md       Copy this to add a tool or app
    profession-page-template.md  Copy this to add a profession
  professions/                   Browse by job: tasks mapped to tools
    README.md                    Index of all professions
    software-developer.md
    writer.md
    ... and ten more
  tools/                         Reviews of tools and apps, by domain
    README.md                    Index of every reviewed tool and app
    coding-assistants/
    ai-assistants/
    image-generation/
  comparisons/
    README.md                    Head to head comparisons
  .github/                       Issue and pull request templates
```

</details>

---

## A note on freshness

AI tools change fast. Prices move, models get renamed, features ship and break. Every review carries a **Last verified** date and links to its sources. If you find something out of date, please [open an issue](.github/ISSUE_TEMPLATE/correct-or-update.md) or send a fix. A dated, sourced review you can trust is worth more than a polished one you cannot.

## Disclaimer

Reviews reflect the honest judgment of contributors at the time of writing. They are not a substitute for your own testing, especially for regulated work in health, legal, or finance. Always confirm pricing and terms on the vendor's own site before you commit.
