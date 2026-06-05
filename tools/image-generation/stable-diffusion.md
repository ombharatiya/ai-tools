---
name: Stable Diffusion
slug: stable-diffusion
vendor: Stability AI and the open ecosystem
category: image-generation
subcategory: ""
website: https://stability.ai
license_model: open-source, enterprise
pricing_summary: "Free open weights; you pay your own compute; enterprise license above $1M revenue"
status: active
first_reviewed: 2026-06-05
last_verified: 2026-06-05
recommendation: top-pick
ratings:
  capability: 4
  ease_of_use: 2
  reliability: 4
  value: 5
  ecosystem: 5
  docs_support: 3
  privacy: 5
  momentum: 3
  portability: 5
disclosure: none
---

# Stable Diffusion

An open-weights image model family you download and run yourself, even offline. The pick for local, private, customizable generation with no per-image cost.

**At a glance:** Top pick | Open weights (community license) | Free weights, you pay compute

| Dimension | Score |
| --- | --- |
| Capability | 4 / 5 |
| Ease of use | 2 / 5 |
| Reliability | 4 / 5 |
| Value | 5 / 5 |
| Ecosystem | 5 / 5 |
| Docs and support | 3 / 5 |
| Privacy | 5 / 5 |
| Momentum | 3 / 5 |
| Portability | 5 / 5 |

## What it is

Stable Diffusion is an open-weights family of image models you can download and run on your own GPU, including offline. Because the weights are open, there is a large ecosystem of fine-tunes, LoRAs, ControlNets, and front-end apps built on top. The current official release is the Stable Diffusion 3.5 family from Stability AI.

## Best for

- Developers, technical artists, and researchers who want local or offline generation and deep control.
- Privacy-sensitive users who need images that never leave their machine.
- People who want no per-image cost and the freedom to fine-tune, including small businesses under the revenue cap.

## Not for

- Non-technical users who want one-click polished results.
- Anyone without a capable GPU or the budget to rent one.
- Companies over $1M revenue who do not want to buy an enterprise license.

## Pricing

The model weights are free under the Stability AI Community License. Your cost is your own hardware or cloud GPU. Companies over $1M annual revenue need a paid enterprise license. Last verified 2026-06-05.

<details>
<summary><strong>How cost works</strong></summary>

- **Weights:** $0 to download under the Community License.
- **Compute:** your own GPU, or cloud rental. A used 24 GB card such as an RTX 3090 (roughly $700 to $1,050) is a common recommendation; 12 GB is a practical floor.
- **Enterprise license:** required and custom-priced if your organization earns over $1,000,000 per year.
- **Hosted options:** Stability's own API and third-party hosts exist; their pricing was not confirmed during research.

</details>

## Strengths

- Open weights. Download, run locally, use offline, full control, and no per-image fee.
- Free for commercial use under the $1M revenue threshold.
- The largest customization ecosystem of any image tool: fine-tunes, LoRAs, ControlNet, inpainting, and node-based pipelines.
- No model-level content censorship when self-hosted. You decide what to generate.
- Runs on consumer GPUs. SD 3.5 Medium and SDXL work on mid-range cards, and quantization brings the large model down to roughly 11 GB of VRAM.

## Weaknesses and dealbreakers

- **Dealbreaker for non-technical users:** not a one-click tool. You need a capable GPU and the willingness to install and tune things.
- Hardware cost is real. 12 GB VRAM is a practical floor and 24 GB is the target, so laptop-only users are mostly out.
- The license is open weights, not true open source. There is a $1M revenue cap, an attribution requirement, and a ban on using the models to build competing foundation models.
- Default quality and prompt-following often trail the best closed models, and many in the community have shifted to alternatives like FLUX.
- The corporate backer, Stability AI, has had financial and leadership turbulence, which raises questions about long-term first-party support.

## Stability and maturity

The technology and ecosystem are mature and widely deployed, and once you download the weights they cannot be taken away. The corporate backer has been financially unstable, though, and the official release cadence has slowed (SD 3.5 dates to late 2024). The community tooling, especially ComfyUI, is now a center of gravity, which reduces dependence on Stability itself.

## Privacy and data

The best of the three when self-hosted. Run it locally and your prompts and images never leave your machine, with nothing sent to Stability. If you use a hosted API or third-party service instead, that provider's policy applies, so check it. The open models do not embed a mandatory watermark, though some hosted providers may add provenance metadata.

## Integrations

Run it locally through UIs: ComfyUI (node-based, most flexible, lowest VRAM), AUTOMATIC1111 (beginner-friendly, large extension library), Forge (a lighter A1111 fork), and Fooocus (simplest). Also available through hosted services including Stability's own platform, Hugging Face, Amazon Bedrock, and NVIDIA's hosted catalog.

## Licensing of generated images

You own the outputs and may use them at your discretion, subject to law and the acceptable use policy. Free commercial use applies only under $1M annual revenue; above that the license terminates and you need an enterprise license. Attribution is required when you distribute the model or derivatives, including a "Powered by Stability AI" notice. The same US copyright caveat applies: purely AI-generated content may not be registrable. Confirm current terms before relying on this.

## Alternatives

- **[Midjourney](midjourney.md):** when you want the most polished default look with no setup.
- **[OpenAI image generation](dall-e.md):** when you want a managed API, accurate text in images, and strong editing.

## Bottom line

**Top pick** for technical users who want to run image generation locally, privately, and free, with the deepest customization in the category. The honest tradeoffs: you need a capable GPU and patience to set it up, default quality trails the best closed models, and the backer's finances are shaky (though the open weights protect you from that). If you want polish with zero setup, choose Midjourney. If you want a managed API, choose OpenAI. If you want control and privacy, this is the one.

## Sources

- [Stability AI license](https://stability.ai/license): Community vs Enterprise license, $1M threshold, output ownership, prohibited uses. Read directly. Seen 2026-06-05.
- [SD 3.5 license on Hugging Face](https://huggingface.co/stabilityai/stable-diffusion-3.5-large/blob/main/LICENSE.md): attribution text and "Powered by Stability AI" requirement. Read directly. Seen 2026-06-05.
- [SD 3.5 announcement](https://stability.ai/news-updates/introducing-stable-diffusion-3-5): variants and release. Seen 2026-06-05.

## Changelog

- 2026-06-05: First review.
