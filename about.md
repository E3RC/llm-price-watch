---
layout: default
permalink: /about/
title: Methodology
---

<section class="hero">
<p class="eyebrow">How the watch works</p>
<h1>Methodology</h1>
<p class="lede">LLM Price Watch focuses on practical coding and agent economics: what a model really costs, how you can actually access it, and whether the cheap route is usable.</p>
</section>

## Sources checked

The daily scan prioritizes first-party pricing and documentation, then uses aggregators and community sources to discover anomalies and short-lived deals.

- **OpenCode:** Go, Zen, advertised free routes, live model IDs, previews/stealth models, contributor/training routes, privacy and usage limits.
- **OpenRouter:** Free Router, free variants, provider-by-provider pricing, latency/rate-limit observations, promotions and newly listed models.
- **Microsoft Azure AI Foundry:** model catalog, serverless/API-as-a-service, managed compute, provisioned throughput, region availability, enterprise/privacy considerations and promotions.
- **Direct model vendors:** DeepSeek, Alibaba/Qwen, Moonshot/Kimi, Zhipu/GLM, MiniMax, Xiaomi/MiMo, Tencent/Hunyuan, Baidu/ERNIE, ByteDance/Doubao, StepFun, SenseTime/SenseNova, 01.AI/Yi and emerging vendors.
- **Community discovery:** Reddit and similar sources are used aggressively to find same-day deals and deployment issues, but community-only claims are labeled unverified until a vendor/provider source confirms them.

## Access types

Pricing is meaningless if the product cannot be used the way you expect. Every deal is classified as one of these:

| Access Type | Meaning |
|---|---|
| **API** | General documented API access suitable for applications/backends. |
| **OpenAI-compatible API** | General API exposing an OpenAI-style endpoint. |
| **Agent-only / CLI-only** | Access exists only through the vendor's coding agent or CLI. |
| **Web-chat-only** | Hosted chat/application access without programmable API access. |
| **Specific-client-only** | API-shaped key/endpoint restricted by terms to approved interactive coding clients. |
| **Azure serverless API** | Azure-hosted token-priced API/serverless model endpoint. |
| **Azure managed compute** | Dedicated or managed Azure compute; not directly comparable to token-priced serverless API. |
| **Azure provisioned throughput** | Reserved/provisioned Azure capacity with commitment and throughput economics. |

**Important example:** Command Code Go is classified as agent/CLI-only unless that specific tier's terms explicitly add API access.

## Price comparison rules

For token-priced APIs, the watch compares input, output and cache rates per million tokens whenever the providers expose comparable units. Regional pricing and currencies are preserved and normalized to approximate USD when useful.

Azure VM/GPU or managed-compute pricing is **never** mixed into token-price tables as though it were the same product. Provisioned throughput is evaluated using its commitments and effective utilization economics.

## Privacy and training

Zero-data-retention, retention periods, training/contributor use, and provider routing policies are surfaced whenever published. A $0 endpoint that permits training is intentionally treated differently from a $0 ZDR endpoint.

## What "Best Value Today" means

The winner is not automatically the lowest number. The recommendation considers price, useful coding/agent capability, modality, context, latency, rate-limit reliability, access restrictions, privacy and whether the user's existing subscriptions already provide equivalent capacity.

Prices and promotions change quickly. Always verify the latest daily report before making a purchase or production deployment decision.
