---
layout: post
title: "LLM Price Watch — September 6, 2026"
date: 2026-09-06 07:31:00 -0400
summary: "OpenCode Zen drops Muse Spark 1.2 Contributor Free, MiniMax M3 remains free on OpenRouter and Vercel, Alibaba refreshes DeepSeek and Qwen pricing, and Azure's enterprise premium is weighed against cheaper routes."
---

## 🚨 Top changes today

| Change | Why it matters |
|---|---|
| **OpenCode Zen free list shrank from 7 to 6** | `muse-spark-1.2-contributor-free` has disappeared from the current documented free list. Muse Spark 1.3 Contributor Free remains $0, with Meta-training permission. |
| **MiniMax M3 Free is still live on OpenRouter** | Community posts had suggested September 6 as an expiry date, but OpenRouter still shows the free route active this morning. Treat the expiry claim as unverified and use the route while it lasts. |
| **Vercel AI Gateway still lists MiniMax M3 as Free** | 1M context, native text/image/video input and coding/agent support, with no published expiry on the current model page. |
| **Alibaba refreshed Global-region pricing** | DeepSeek V4 Flash is now **$0.138/$0.275 per M** in Virginia Global and Qwen3.8 Flash is **$0.113/$0.382 per M**, both lower than the figures carried yesterday. |
| **Command Code has three current $0 model routes** | Laguna S 2.1, **Ling 3.0 Flash**, and LongCat 2.0 are currently listed as no-credit model usage while the promotions/capacity last. Go remains agent/CLI-only, not Provider API access. |
| **No major same-day model launch confirmed** | Today's movement is mostly pricing, free-route churn and provider positioning rather than a new frontier release. |

Sources: [OpenCode Go](https://dev.opencode.ai/docs/go/), [OpenCode Zen](https://dev.opencode.ai/docs/zen/), [OpenRouter](https://openrouter.ai/), [Azure Foundry](https://ai.azure.com/catalog), [Alibaba Model Studio](https://www.alibabacloud.com/help/en/model-studio/), [Command Code pricing](https://commandcode.ai/docs/resources/pricing-limits).

## OpenCode Go

OpenCode Go remains **$10/month** with shared limits of **$12/5h, $30/week and $60/month**. The lineup is unchanged at 27 models. GLM-5.3-Flash still carries the limited-time **2× Go usage** promotion.

| Model | Approx. req/5h | Modality | Privacy / training | Δ today |
|---|---:|---|---|---|
| Grok 4.6 | 169 | text/agent | 30-day retention | — |
| GPT-5.6 Luna | 2,050 | text + vision | 30-day retention | — |
| **GLM-5.3-Flash** | 1,580 base | multimodal | ZDR | **2× promo active** |
| GLM-5.3 | 220 | text/agent | ZDR | — |
| GLM-5.2 | 880 | text/agent | ZDR | — |
| GLM-5.1 | 880 | text/agent | ZDR | — |
| Kimi K3 | 110 | multimodal/agent | ZDR | — |
| Kimi K2.7 Code | 1,350 | image + text coding | ZDR | — |
| Kimi K2.6 | 1,150 | multimodal | ZDR | — |
| LongCat-2.0 | 11,400 | text/agent | ZDR | — |
| **MiMo-V2.5** | **30,100** | multimodal | ZDR | volume leader |
| MiMo-V2.5-Pro | 3,250 | multimodal | ZDR | — |
| MiniMax M3 | 3,200 | multimodal/agent | ZDR | — |
| MiniMax M2.7 | 3,400 | text/agent | ZDR | — |
| Muse Spark 1.3 Contributor | **45,300** | multimodal/agent | **training permitted** | — |
| Muse Spark 1.2 Contributor | 45,300 | text/agent | **training permitted** | — |
| Qwen3.8 Max | 160 | multimodal | ZDR | — |
| Qwen3.8 Flash | 5,400 | text/image/video | ZDR | — |
| Qwen3.7 Max | 170 | text/agent | ZDR | — |
| Qwen3.7 Plus | 4,300 | multimodal | ZDR | — |
| Qwen3.6 Plus | 3,300 | text/agent | ZDR | — |
| DeepSeek V4 Pro | 1,050 | text/agent | **ZDR through Sep. 30** | — |
| DeepSeek V4 Flash | 7,600 | coding/text | **ZDR through Sep. 30** | — |
| DeepSeek V4 Flash Vision Exp | 3,800 | vision + text | **ZDR through Sep. 30** | — |
| Hy4 Preview | 1,350 | text/agent | ZDR | — |
| Hy3 | 4,300 | text/agent | ZDR | — |
| Omen Alpha | 11,600 | image + text | ZDR | stealth identity still unconfirmed |

The Muse Contributor routes are intentionally not private capacity: OpenCode says Contributor prompts/completions can be used to train future Meta models. The DeepSeek ZDR agreement is currently documented through **September 30, 2026**.

## OPENCODE FREE / PREVIEW DEALS

The current documented Zen free list is now **six models**.

| Model ID | Access Type | Cost | Context / modality | Limits / privacy / status |
|---|---|---:|---|---|
| `big-pickle` | Zen provider API | **$0** | stealth | free-period data may improve model |
| `mimo-v2.5-free` | Zen provider API | **$0** | ~1M / multimodal | limited-time; model-improvement terms apply |
| `ling-3.0-flash-fin-free` | Zen provider API | **$0** | coding/text | limited-time |
| `nemotron-3-ultra-free` | Zen provider API | **$0** | text/agent | NVIDIA trial/logging terms |
| `nemotron-3.5-lightning-free` | Zen provider API | **$0** | text/agent | NVIDIA trial/logging terms |
| `muse-spark-1.3-contributor-free` | Zen provider API | **$0** | multimodal/agent | **Meta training permitted** |
| `muse-spark-1.2-contributor-free` | former Zen free route | — | agent | **removed from current documented free list** |
| Ox Alpha | ended preview | — | became GLM-5.3-Flash | no longer a free preview |
| Hy3 Free | ended/unlisted | — | agent | no longer documented |

## OPENROUTER DEALS

| Route | Access Type | Current price | Why it matters |
|---|---|---:|---|
| Free Router | OpenAI-compatible API/router | **$0** | rotating capability-aware free pool |
| Pareto Code | OpenAI/Anthropic-compatible router | **$0** | 13 coding models, 2M context |
| North Mini Code Free | General API | **$0** | 256K, tools, coding-harness optimized |
| **MiniMax M3 Free** | General API | **$0 this morning** | 1M multimodal; community-reported Sep. 6 expiry remains unverified |
| **DeepSeek V4 Flash / Baidu Qianfan** | General API | **$0.04998 / $0.09996** | cheapest clearly identified paid DeepSeek route found today |
| DeepSeek V4 Flash Nitro | General API/router | headline **$0.045 / $0.09** | even lower headline, but provider/routing mix is less transparent |
| GLM-5.3-Flash | General API | discounted routes remain available | strong low-cost multimodal/coding option |

OpenRouter's provider-specific discounts matter more than the model's headline card price. Pin providers when privacy, latency or data-location requirements matter.

## AZURE AI FOUNDRY COMPARISON

Azure remains useful as an enterprise-safe route, but it is rarely today's raw-price winner.

| Model | Azure offer | Azure price / billing | Lower-cost comparison | Take |
|---|---|---:|---|---|
| **DeepSeek V4 Flash** | Azure Direct serverless API | **$0.19 / $0.51; cache $0.028/M** | OR/Baidu $0.04998/$0.09996; Alibaba Virginia $0.138/$0.275; DeepSeek direct off-peak $0.22/$0.66 | **good enterprise value, not cheapest** |
| **DeepSeek V4 Pro** | Azure Direct serverless API | **$1.74 / $3.48; cache $0.145/M** | DeepSeek direct off-peak $0.66/$1.98 | substantial Azure premium |
| Kimi K2.6 | Azure Direct Preview | calculator/portal | direct/provider alternatives vary | useful for Azure governance and procurement |
| MiniMax M3 | Fireworks on Foundry | partner PAYG/PTU | **OpenRouter + Vercel are free today** | governance route, not value route |
| Open-weight catalog models | managed deployment | GPU/endpoint billing | hosted token APIs | **not apples-to-apples** |
| Provisioned throughput | Azure PTU | commitment/throughput billing | serverless PAYG | size by sustained load, not $/M headline |

For **Azure Direct** models, Microsoft provides the enterprise control plane and does not expose prompts/outputs to the original model provider under the Azure Direct privacy model. **Fireworks on Foundry is different**: those deployments run on Fireworks infrastructure and customer data can leave Microsoft systems. Do not treat every model visible in the Azure catalog as the same privacy or billing product.

Sources: [DeepSeek V4 Flash catalog](https://ai.azure.com/catalog/models/DeepSeek-V4-Flash), [DeepSeek V4 Pro catalog](https://ai.azure.com/catalog/models/DeepSeek-V4-Pro), [Microsoft Foundry data privacy](https://learn.microsoft.com/azure/foundry/responsible-ai/openai/data-privacy), [Fireworks on Foundry](https://learn.microsoft.com/azure/foundry/how-to/fireworks/enable-fireworks-models).

## DIRECT CHINESE API PRICING / FIRST-PARTY SCAN

| Vendor | Current first-party finding | Access Type |
|---|---|---|
| **DeepSeek** | V4 Flash **$0.22/$0.66 off-peak**, $0.44/$1.32 peak; cache hit $0.007 off-peak. V4 Pro $0.66/$1.98 off-peak. | General OpenAI/Anthropic-compatible API |
| **Alibaba/Qwen** | Qwen3.8 Flash Virginia/Global **$0.113/$0.382**; Qwen3.8 Max Global **$1.65/$4.951**. | General API |
| **Alibaba-hosted DeepSeek** | V4 Flash Virginia Global **$0.138/$0.275**. | General API |
| **Moonshot/Kimi** | No newly verified direct-price change today; Azure Direct Kimi K2.6 preview remains notable. | General API / Azure Direct where offered |
| **Tencent/Hunyuan** | GLM-5.3-Flash PAYG is **50% of list through Sep. 10 Beijing time**; personal selected-model coefficients are 50% through Sep. 30. | API PAYG + specific-client Token Plans |
| **Xiaomi/MiMo** | Lite shows **$5.28/mo annual-equivalent / $6 monthly**, no 5h cap, compatible coding clients. | specific-client Token Plan |
| **Baidu/Qianfan** | Current 50K-credit welfare pack: **¥45 first buy / ¥50 list (~$6.71/$7.45)**. Intl PAYG DeepSeek V4 Flash is $0.14/$0.28. | specific-client token pack + general API PAYG |
| **StepFun** | Current docs list **Flash Mini ¥49/mo (~$7.30)**; live checkout page currently hides numeric price. | specific-client/agent plan |
| **ByteDance/Doubao** | Seed Code PAYG starts around **¥1.2 input / ¥8 output per M** for 0–32K; a ¥9.9 first-month Coding Plan is vendor-community reported and should be verified at checkout. | general API PAYG / specific-client Coding Plan |
| **Z.ai/GLM** | AutoClaw new-user grant remains **100M GLM-5.3-Flash tokens**; ZCode trial is 8M tokens/day for first 5 days. Coding Plan endpoint is not the unrestricted general API. | specific-client coding plan + separate API |
| **MiniMax** | Token Plan Plus is about $20 monthly / $200 yearly; production usage is recommended on PAYG. | specific-client developer plan + separate API |
| SenseNova | No verified change from the current public-beta offers today. | Plan API / agent endpoint |
| 01.AI / Yi | No new public hosted API offer surfaced; open weights/self-hosting remain separate. | self-host/open weights where applicable |

DeepSeek's pricing page still carries the effective **Aug. 16, 2026 peak/off-peak schedule**, so older $0.14/$0.28 direct-API examples should not be treated as the current all-day price.

## FREE ACCESS

| Offer | Access Type | Cost | Note |
|---|---|---:|---|
| **Vercel AI Gateway MiniMax M3** | OpenAI/Anthropic-compatible gateway | **FREE** | 1M context, multimodal, no published expiry on current page |
| OpenRouter MiniMax M3 Free | General API | **FREE today** | use-now; community expiry claim is unverified |
| OpenRouter Pareto Code | API/router | **FREE** | strong general coding fallback |
| OpenCode Zen six-model free pool | Zen provider API | **FREE** | privacy/training varies by model |
| Z.ai AutoClaw grant | specific-client desktop agent | **100M tokens for new users** | GLM-5.3-Flash; not unrestricted backend API credit |
| Command Code Laguna S 2.1 / Ling 3.0 Flash / LongCat 2.0 | Go = agent/CLI-only; Provider API only on eligible higher plans | **$0 model usage** | capacity/promo dependent |

## LOW-COST SUBSCRIPTIONS ($3–$10 focus)

| Plan | Price | Access Type | Note |
|---|---:|---|---|
| **Command Code Go** | **$1/mo** | **agent/CLI-only — NO Provider API** | $10 monthly credits; free promo models extend value |
| Tencent Hy Lite | **¥28 ≈ $4.17/mo** | specific-client-only | Hy-focused coding/agent plan |
| Tencent General Lite | **¥39 ≈ $5.81/mo** | specific-client-only | selected-model Sep. coefficient promo |
| Xiaomi MiMo Lite | **$5.28 annual-equivalent / $6 monthly** | specific-client-only | no 5h cap; coding-client token plan |
| **Baidu Qianfan 50K welfare pack** | **¥45 first buy / ¥50 list ≈ $6.71/$7.45** | specific-client/token pack | current first-party welfare-pack pricing |
| **StepFun Flash Mini** | **¥49 ≈ $7.30/mo** | hosted/specific-client agent | docs list price; live checkout currently hides it |
| **Command Code GOAT** | **$10/mo** | **agent/CLI + OpenAI/Anthropic-compatible Provider API** | unlike Go, API access is explicitly included |
| OpenCode Go | **$10/mo** | provider/API for coding agents | broad curated 27-model pool |

## NEW MODELS

No major frontier model release was verified on September 6. The most recent consequential launches remain **GLM-5.3-Flash** (September 4, revealed as the production identity of Ox Alpha) and **Muse Spark 1.3** (September 2). Today's changes are primarily route availability, pricing and free-tier churn.

## BEST VALUE TODAY

**Best free agent model:** Vercel's **MiniMax M3 Free** is the least ambiguous persistent-looking free M3 route today because the current first-party model page says Free and publishes no expiry. OpenRouter's M3 Free is also still live, but Reddit's claimed September 6 expiry makes it a use-now route rather than something to build around.

**Best cheap paid DeepSeek:** OpenRouter's **Baidu Qianfan DeepSeek V4 Flash route at $0.04998/$0.09996/M** is dramatically cheaper than DeepSeek direct, Alibaba and Azure for uncached inference. DeepSeek direct remains valuable for first-party routing and its unusually cheap off-peak cache hits.

**Best private capacity already in OpenCode Go:** GLM-5.3-Flash remains compelling while its 2× usage promotion is active, and DeepSeek routes are documented ZDR through September 30. Avoid Muse Contributor for proprietary code because training is explicitly permitted.

**Best Azure case:** pay the Azure premium only when Entra/RBAC, private networking, procurement, compliance, regional controls or Microsoft-held data boundaries are worth more than raw token savings. For ordinary experimentation, OpenRouter, Alibaba and direct Chinese APIs are much cheaper.

For the current baseline stack, there is **no strong reason to add another paid subscription today**. The useful additions are free/cheap routes: Vercel MiniMax M3, OpenRouter/Baidu DeepSeek, and Command Code's current no-credit models if extra agent capacity is useful.
