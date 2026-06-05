---
name: OpenAI Image Generation (GPT Image, formerly DALL-E)
slug: dall-e
vendor: OpenAI
category: image-generation
subcategory: ""
website: https://platform.openai.com
license_model: usage-based, free, subscription
pricing_summary: "Usage based via the API; free tier inside ChatGPT"
status: active
first_reviewed: 2026-06-05
last_verified: 2026-06-05
recommendation: top-pick
ratings:
  capability: 5
  ease_of_use: 5
  reliability: 4
  value: 3
  ecosystem: 5
  docs_support: 5
  privacy: 3
  momentum: 5
  portability: 2
disclosure: none
---

# OpenAI Image Generation (GPT Image, formerly DALL-E)

OpenAI's image system, built into ChatGPT and available through the API. The developer's pick, and the best at putting accurate text inside images.

**At a glance:** Top pick | Usage based, free tier in ChatGPT | Pay per image via tokens

| Dimension | Score |
| --- | --- |
| Capability | 5 / 5 |
| Ease of use | 5 / 5 |
| Reliability | 4 / 5 |
| Value | 3 / 5 |
| Ecosystem | 5 / 5 |
| Docs and support | 5 / 5 |
| Privacy | 3 / 5 |
| Momentum | 5 / 5 |
| Portability | 2 / 5 |

## What it is

OpenAI's image generation is a text-to-image and image-editing system in ChatGPT and the API. The current family is branded GPT Image, and the older DALL-E brand is being retired. The newer models are natively multimodal, which gives strong prompt-following and the best rendering of text inside images. The flagship, GPT Image 2, supports up to 4K output.

## Best for

- Developers who want a reliable official API with SDKs and documentation.
- Anyone who needs accurate text in images, precise editing, or multilingual output.
- ChatGPT users who want image generation in the same place they chat.

## Not for

- People who need unwatermarked output. Every image carries provenance markers.
- Anyone needing uncensored or edgy content, given strict filters.
- People who want the most artistic default look, offline use, or flat per-image pricing.

## Pricing

Usage based through the API, priced by tokens, plus a limited free tier inside ChatGPT and access on ChatGPT paid plans. Last verified 2026-06-05.

<details>
<summary><strong>Full pricing</strong></summary>

API token prices per 1M tokens (read directly from the developer pricing page):

- **gpt-image-2** (flagship): text input $5.00, image input $8.00, image output $30.00.
- **gpt-image-1.5:** text input $5.00, image input $8.00, image output $32.00.
- **gpt-image-1-mini** (cheapest): text input $2.00, image input $2.50, image output $8.00.

Per-image cost depends on quality and resolution. Reported ranges run from under a cent to around $0.25 per image. The token prices above are the authoritative figures.

Inside ChatGPT: Free has a few images per day; Plus ($20/mo) gives more; Pro is effectively unlimited with guardrails. The ChatGPT tier figures are corroborated from secondary sources, since the consumer pricing page blocked direct fetch during research.

</details>

## Strengths

- Best-in-class text rendering inside images, with very high character accuracy across many scripts.
- Very strong prompt adherence and editing, because the language model drives the image.
- Available right inside ChatGPT and through a clean, documented official API with SDKs.
- Multilingual, and high resolution up to 4K on the flagship.
- Clear, user-favorable output ownership terms.
- Scales from a free consumer tier up to high-volume API use.

## Weaknesses and dealbreakers

- **Dealbreaker for unwatermarked work:** since around 2026-05, all outputs carry invisible provenance markers (C2PA metadata plus a SynthID watermark).
- Token-based pricing is hard to predict. Cost varies by quality and resolution and adds up at scale.
- Strict content filters refuse many prompts, including real-person likenesses and various styles. A real limit for some creative and adult use cases.
- The default aesthetic is competent but often less distinctive than Midjourney.
- The free tier image limit is very tight, a few images per day.
- Closed and cloud only. No self-hosting, and you depend on OpenAI's uptime, pricing, and model deprecation schedule.

## Stability and maturity

Very mature and well-resourced, with first-party docs and SDKs. The model lineup churns quickly, though: DALL-E was retired, and GPT Image 1 was already slated for deprecation months after launch. Expect frequent model turnover and occasional throttling as capacity shifts.

## Privacy and data

API and Business and Enterprise inputs are not used to train models by default. Consumer ChatGPT (Free and Plus) inputs can be used for training unless you turn it off. All generated images since around 2026-05-19 carry C2PA metadata and an embedded SynthID watermark, and OpenAI runs a public checker.

## Integrations

Use it in the ChatGPT web and mobile apps, the OpenAI API (REST plus official SDKs), a coding agent, and through Microsoft Azure OpenAI Service. No local install.

## Licensing of generated images

OpenAI's terms assign output ownership to you, to the extent allowed by law, and you may use outputs commercially subject to the usage policies. Two caveats: OpenAI disclaims any warranty that output does not infringe third-party rights, and under current US copyright law purely AI-generated content may not be registrable. Confirm current terms before relying on this.

## Alternatives

- **[Midjourney](midjourney.md):** when you want the most polished default look and do not need an API.
- **[Stable Diffusion](stable-diffusion.md):** when you want local, private, uncensored, customizable generation with no per-image fee.

## Bottom line

**Top pick** for developers and for anyone who needs accurate text in images, strong editing, or multilingual output, all behind a clean official API. The honest tradeoffs: token pricing that is hard to predict, strict content filters, and provenance watermarks on every output. If you need unwatermarked or uncensored images, or full local control, choose Stable Diffusion. If you want the most artistic default look, choose Midjourney.

## Sources

- [OpenAI API pricing](https://developers.openai.com/api/docs/pricing): GPT Image token prices. Read directly. Seen 2026-06-05.
- [GPT Image 2 announcement](https://openai.com/index/introducing-chatgpt-images-2-0/): flagship release 2026-04-21 and features. Seen 2026-06-05.
- [C2PA in ChatGPT images](https://help.openai.com/en/articles/8912793-c2pa-in-chatgpt-images): C2PA and SynthID watermarking on all outputs. Read directly. Seen 2026-06-05.
- [OpenAI terms of use](https://openai.com/policies/row-terms-of-use/): output ownership and commercial use (via search). Seen 2026-06-05.

## Changelog

- 2026-06-05: First review.
