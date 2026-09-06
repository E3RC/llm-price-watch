---
layout: post
title: "LLM Price Watch — September 6, 2026"
date: 2026-09-06 08:08:00 -0400
summary: "OpenCode Zen drops Muse Spark 1.2 Contributor Free, GPT-6 Astra Batch/Flex cuts API cost in half, Command Code Go has three free model routes, and Alibaba undercuts Azure on DeepSeek and Qwen raw inference."
---

## 🚨 Top changes today

| Change | Why it matters |
|---|---|
| **OpenCode Zen free list shrank from 7 to 6** | `muse-spark-1.2-contributor-free` is gone from the current English Zen endpoint/pricing list. Muse Spark 1.3 Contributor Free remains $0, with Meta-training permission. |
| **GPT-6 Astra has a verified half-price route** | OpenAI says Batch and Flex cost **50% of Standard**. OpenRouter exposes `openai/gpt-6-astra:batch` at **$5 input / $25 output per M**, vs $10/$50 Standard. |
| **Command Code Go currently has three $0 model routes** | Laguna S 2.1, **Ling 3.0 Flash**, and LongCat 2.0 are listed as free model usage. Go remains agent/CLI-only — **no Provider API**. |
| **DeepSeek V4 Flash remains absurdly cheap on OpenRouter/Baidu** | Baidu Qianfan is still **$0.04998/$0.09996/M**, cache read $0.009996. OpenRouter Nitro headlines even lower at about $0.045/$0.09, but provider mix is less explicit. |
| **Alibaba now undercuts Azure on two key Chinese models** | Virginia/Global: DeepSeek V4 Flash **$0.138/$0.275**, Qwen3.8 Flash **$0.113/$0.382**. Azure Direct DeepSeek Flash is $0.19/$0.51. |
| **Azure Kimi K3 carries an enterprise/partner premium** | Fireworks-on-Foundry Kimi K3 is **$3.30/$16.50**, cache $0.33; Moonshot first-party pricing is about ¥20/¥100 (roughly $2.98/$14.90 at today's FX). |
| **No major same-day frontier launch verified** | Today's movement is mostly route availability, price cuts and free-tier churn rather than a new flagship model release. |

Sources: [OpenCode Zen](https://dev.opencode.ai/docs/zen) · [OpenCode Go](https://dev.opencode.ai/docs/go/) · [OpenAI GPT-6 Astra](https://developers.openai.com/api/docs/models/gpt-6-astra) · [OpenRouter Astra Batch](https://openrouter.ai/openai/gpt-6-astra:batch) · [Command Code pricing](https://commandcode.ai/docs/resources/pricing-limits) · [Alibaba Model Studio pricing](https://www.alibabacloud.com/help/en/model-studio/model-pricing)

## OpenCode Go

Go remains **$10/month**, with shared limits of **$12/5h, $30/week and $60/month**. The lineup is unchanged at 27 models. GLM-5.3-Flash still carries the limited-time **2× Go usage** promotion. DeepSeek ZDR is documented through **September 30, 2026**.

| Model | $/M input → output | Est. req/5h | Modality | Privacy / training | Δ today |
|---|---:|---:|---|---|---|
| Grok 4.6 | $2 → $6* | 169 | text/agent | 30-day retention | — |
| GPT-5.6 Luna | $0.20 → $1.20* | 2,050 | text + vision | 30-day retention | — |
| **GLM-5.3-Flash** | **$0.15 → $0.50** | 1,580 base | multimodal | ZDR | **2× promo active** |
| GLM-5.3 | $1.40 → $4.40 | 220 | text/agent | ZDR | — |
| GLM-5.2 | $1.40 → $4.40 | 880 | text/agent | ZDR | — |
| GLM-5.1 | $1.40 → $4.40 | 880 | text/agent | ZDR | — |
| Kimi K3 | $3 → $15 | 110 | multimodal/agent | ZDR | — |
| Kimi K2.7 Code | $0.95 → $4 | 1,350 | image + text coding | ZDR | — |
| Kimi K2.6 | $0.95 → $4 | 1,150 | multimodal | ZDR | — |
| LongCat-2.0 | $0.30 → $1.20 | 11,400 | text/agent | ZDR | — |
| **MiMo-V2.5** | **$0.14 → $0.28** | **30,100** | multimodal | ZDR | volume leader |
| MiMo-V2.5-Pro | $0.435 → $0.87 | 3,250 | multimodal | ZDR | — |
| MiniMax M3 | $0.30 → $1.20 | 3,200 | multimodal/agent | ZDR | — |
| MiniMax M2.7 | $0.30 → $1.20 | 3,400 | text/agent | ZDR | — |
| Muse Spark 1.3 Contributor | $0.10 → $0.20 | **45,300** | multimodal/agent | **training permitted** | — |
| Muse Spark 1.2 Contributor | $0.10 → $0.20 | 45,300 | text/agent | **training permitted** | — |
| Qwen3.8 Max | $2 → $6 | 160 | multimodal | ZDR | — |
| Qwen3.8 Flash | $0.15 → $0.47 | 5,400 | text/image/video | ZDR | — |
| Qwen3.7 Max | $2.50 → $7.50 | 170 | text/agent | ZDR | — |
| Qwen3.7 Plus | $0.40 → $1.60* | 4,300 | multimodal | ZDR | — |
| Qwen3.6 Plus | $0.50 → $3* | 3,300 | text/agent | ZDR | — |
| DeepSeek V4 Pro | $0.66 → $1.98 off-peak | 1,050 | text/agent | **ZDR through Sep. 30** | — |
| DeepSeek V4 Flash | $0.22 → $0.66 off-peak | 7,600 | coding/text | **ZDR through Sep. 30** | — |
| DeepSeek V4 Flash Vision Exp | $0.22 → $0.66 off-peak | 3,800 | vision + text | **ZDR through Sep. 30** | — |
| Hy4 Preview | $0.834 → $2.501 | 1,350 | text/agent | ZDR | — |
| Hy3 | $0.14 → $0.58 | 4,300 | text/agent | ZDR | — |
| Omen Alpha | $0.20 → $0.66 | 11,600 | image + text | ZDR | identity unconfirmed |

\* Higher-context tiers differ. DeepSeek peak pricing is 2× the off-peak rates shown; weekends are off-peak all day. The Muse Contributor routes explicitly permit training on prompts/completions.

Source: [OpenCode Go docs](https://dev.opencode.ai/docs/go/)

## OPENCODE FREE / PREVIEW DEALS

The current canonical English Zen endpoint/pricing list now shows **six free models**, down from seven yesterday.

| Model ID | Access Type | Cost | Context / modality | Limits / privacy / status |
|---|---|---:|---|---|
| `big-pickle` | Zen provider API | **$0** | stealth | free-period data may improve model |
| `mimo-v2.5-free` | Zen provider API | **$0** | ~1M / multimodal | limited-time |
| `ling-3.0-flash-fin-free` | Zen provider API | **$0** | coding/text | limited-time |
| `nemotron-3-ultra-free` | Zen provider API | **$0** | text/agent | NVIDIA trial/logging terms |
| `nemotron-3.5-lightning-free` | Zen provider API | **$0** | text/agent | NVIDIA trial/logging terms |
| `muse-spark-1.3-contributor-free` | Zen provider API | **$0** | multimodal/agent | **Meta training permitted** |
| `muse-spark-1.2-contributor-free` | former Zen free route | — | agent | **removed from current English list** |
| Ox Alpha | ended preview | — | became GLM-5.3-Flash | no longer free preview |
| Hy3 Free | ended/unlisted | — | agent | no longer documented |

Also active: **GPT-5.6 Sol remains 50% off on Zen through September 18**.

Source: [OpenCode Zen](https://dev.opencode.ai/docs/zen)

## OPENROUTER DEALS

| Route | Access Type | Current price | Why it matters |
|---|---|---:|---|
| `openrouter/free` | OpenAI-compatible API/router | **$0** | rotating capability-aware pool; 200K router context |
| `openrouter/pareto-code` | OpenAI/Anthropic-compatible router | **$0** | 13 coding models, **2M context** |
| North Mini Code Free | General API | **$0** | 256K, 64K max output, tools, coding-harness optimized |
| Ling 3.0 Flash Sante Free | General API | **$0** | 262K, tools; medical focus but usable for general agent/coding work |
| **Dots3 Note Preview Free** | General API | **$0 through Sep. 30** | 512K, multimodal, tools; explicit expiry |
| MiniMax M3 Free | General API | **$0 this morning** | 1M multimodal; community expiry chatter remains unverified |
| **DeepSeek V4 Flash / Baidu Qianfan** | General API | **$0.04998 → $0.09996/M** | cache read $0.009996; cheapest clearly identified paid route found |
| DeepSeek V4 Flash Nitro | General API/router | headline **~$0.045 → $0.09/M** | even lower headline; provider mix is less explicit |
| GLM-5.3-Flash | General API | **$0.075 → $0.25/M** | deeply discounted low-cost route |
| **GPT-6 Astra Batch** | General API / batch | **$5 → $25/M** | **50% below $10/$50 Standard**; cache read $0.50, cache write $6.25 |

**Astra discount is real, not a mystery anomaly:** OpenAI's own model page says Batch and Flex are priced at **50% of Standard**, while Fast is 2×. Use Batch/Flex for jobs where latency/queue semantics are acceptable rather than interactive coding loops.

Sources: [OpenRouter DeepSeek V4 Flash](https://openrouter.ai/deepseek/deepseek-v4-flash-0731) · [Dots3 Note](https://openrouter.ai/dots-studio/dots-3-note-preview:free) · [Astra Batch](https://openrouter.ai/openai/gpt-6-astra:batch) · [OpenAI Astra docs](https://developers.openai.com/api/docs/models/gpt-6-astra)

## FREE ACCESS OUTSIDE OPENCODE / OPENROUTER

| Offer | Access Type | Current deal | Catch |
|---|---|---|---|
| **Vercel AI Gateway — MiniMax M3** | OpenAI/Anthropic-compatible API gateway | **FREE today** | 1M context, text/image/video; no published expiry |
| SenseNova International beta | Plan API / agent endpoint | **$0; 1,500 calls/model/5h** | regional public beta; up to 20 API keys |
| SenseNova China beta | Plan API / agent endpoint | **¥0; 60,000 credits/5h** | separate regional quota |
| Z.ai AutoClaw new-user grant | specific-client desktop agent | **100M GLM-5.3-Flash tokens** | not unrestricted backend API credit |
| **Command Code Laguna S 2.1** | Go = agent/CLI-only | **$0 while capacity lasts** | model usage consumes no credits during promo |
| **Command Code Ling 3.0 Flash** | Go = agent/CLI-only | **$0** | newly confirmed alongside Laguna/LongCat |
| **Command Code LongCat 2.0** | Go = agent/CLI-only | **$0 while it lasts** | 1M context |
| Azure new account | Azure services credit | **$200 / 30 days** | Marketplace/model eligibility varies |

Source: [Command Code pricing](https://commandcode.ai/docs/resources/pricing-limits)

## AZURE AI FOUNDRY COMPARISON

Azure's catalog is broad, but **catalog presence does not mean one billing or privacy model**. Separate Azure Direct, partner-hosted Fireworks, managed compute and PTU.

| Model | Azure route | Azure price / billing | Comparable alternative | Verdict |
|---|---|---:|---|---|
| **DeepSeek V4 Flash** | **Azure Direct serverless** | **$0.19 in / $0.51 out / $0.028 cached per M** | OR/Baidu $0.04998/$0.09996; Alibaba Virginia $0.138/$0.275; DeepSeek direct off-peak $0.22/$0.66 | **good enterprise value; not raw-price winner** |
| **DeepSeek V4 Pro** | Azure Direct serverless | **$1.74 / $3.48 / $0.145** | DeepSeek direct off-peak $0.66/$1.98/$0.022 | substantial premium |
| Kimi K2.6 | Azure Direct Preview | portal/calculator | Moonshot/direct alternatives | Azure privacy/procurement advantage |
| **Kimi K3** | **Fireworks on Foundry** | **$3.30 / $16.50 / cache $0.33** | Moonshot first-party ≈$2.98/$14.90/cache $0.30; Alibaba $2.827/$14.133/cache $0.283 | ~10%+ partner premium, different privacy boundary |
| MiniMax M3 | Fireworks on Foundry | partner PAYG/PTU | free routes exist today | enterprise procurement, not cheapest testing |
| GLM family | Fireworks/open-weight catalog | partner or managed compute | newer GLM-5.3-Flash is cheaper elsewhere | catalog trails latest direct route in places |
| Qwen/open weights | managed deployment | GPU/endpoint billing | Qwen hosted API | not apples-to-apples with $/M tokens |
| Provisioned throughput | Azure PTU | commitment/throughput billing | serverless PAYG | size by sustained load; public numeric V4 PTU rate is not exposed |

**Azure Direct privacy:** Microsoft says serverless model prompts/outputs are processed by Microsoft, are not shared with the model provider, and are not used to train Microsoft/provider/third-party models. **Fireworks on Foundry is explicitly different:** customer data is sent outside Microsoft systems and Foundry data-residency documentation does not apply.

Azure's public DeepSeek pricing page still renders many current V4/PTU cells as `$-`; those require calculator/portal/quote rather than pretending GPU/PTU capacity has a token-equivalent public rate.

Sources: [Azure DeepSeek catalog](https://ai.azure.com/catalog/models/DeepSeek-V4-Flash) · [Azure Kimi K3 catalog](https://ai.azure.com/catalog/models/FW-Kimi-K3) · [Foundry privacy](https://learn.microsoft.com/azure/foundry-classic/how-to/concept-data-privacy) · [Fireworks on Foundry](https://learn.microsoft.com/azure/foundry/how-to/fireworks/enable-fireworks-models) · [Azure DeepSeek pricing](https://azure.microsoft.com/en-us/pricing/details/ai-foundry-models/deepseek/)

## DIRECT CHINESE API PRICING / FIRST-PARTY SCAN

| Vendor | Current first-party finding | Access Type |
|---|---|---|
| **DeepSeek** | V4 Flash **$0.22/$0.66 off-peak**, $0.44/$1.32 peak; cache hit $0.007 off-peak. Weekends are off-peak all day. | General OpenAI/Anthropic-compatible API |
| **Alibaba/Qwen** | Qwen3.8 Flash Virginia/Global **$0.113/$0.382**; Qwen3.8 Max Global **$1.65/$4.951**. | General API |
| **Alibaba-hosted DeepSeek** | V4 Flash Virginia/Global **$0.138/$0.275**, cache $0.028. | General API |
| **Alibaba-hosted Kimi** | Kimi K3 **$2.827/$14.133**, cache $0.283. | General API |
| **Moonshot/Kimi** | K3 list ≈¥20/¥100; K2.7 Code ≈¥6.5/¥27. No same-day price change found. | General API |
| **Tencent/Hunyuan** | Hy4 preview PAYG **¥6/¥18**; Hy3 **¥1/¥4**. GLM-5.3-Flash is **50% of list through Sep. 10 Beijing time**. | General API PAYG + separate Token Plans |
| **Z.ai/GLM** | AutoClaw new-user 100M GLM-5.3-Flash grant remains; ZCode coding-plan trial is separate from unrestricted API. | General API + specific-client coding plans |
| **MiniMax** | M3 first-party API remains tiered by context; no new first-party price change surfaced this morning. | General API + separate Token Plan |
| **Xiaomi/MiMo** | Lite remains ~$6-class; current plan is designed for coding frameworks/clients, not arbitrary backend automation. | specific-client Token Plan |
| **Baidu/Qianfan** | 50K-credit welfare pack **¥45 first buy / ¥50 list**; supports coding tools and multiple models. | specific-client/token pack |
| **ByteDance/Doubao** | Seed Code API starts at **¥1.2 input / ¥8 output per M** for 0–32K; 32–128K is ¥1.4/¥12; 128–256K is ¥2.8/¥16. | General API PAYG; separate Coding Plan exists |
| **StepFun** | New Step Plan shows 400M/1.6B/8B/40B monthly credits, but live public page hides numeric prices to the crawler. | specific-client/agent plan |
| **SenseTime/SenseNova** | No verified change from current regional public-beta offers. | Plan API / agent endpoint |
| **01.AI/Yi** | No new public hosted API price surfaced; current first-party site is enterprise/solution focused. | enterprise/self-host/open-weight paths |

Sources: [DeepSeek pricing](https://api-docs.deepseek.com/quick_start/pricing/) · [Alibaba pricing](https://www.alibabacloud.com/help/en/model-studio/model-pricing) · [Alibaba DeepSeek V4 Flash](https://www.alibabacloud.com/help/en/model-studio/deepseek-v4-flash) · [Alibaba Kimi K3](https://docs.modelstudio.console.alibabacloud.com/en/model-studio/aliyun-kimi-k3) · [Tencent TokenHub pricing](https://cloud.tencent.com/document/product/1823/130055) · [Baidu Qianfan welfare pack](https://cloud.baidu.com/product/qianfan_home/token.html) · [Step Plan](https://platform.stepfun.com/step-plan) · [Doubao Seed Code community documentation](https://developer.volcengine.com/articles/7574423405575798790)

## LOW-COST SUBSCRIPTIONS ($3–$10 focus)

| Plan | Price | Access Type | Note |
|---|---:|---|---|
| **Command Code Go** | **$1/mo** | **agent/CLI-only — NO Provider API** | $10 monthly credits; three current $0 model routes |
| Tencent Hy Lite | **¥28 ≈ $4.17/mo** | specific-client-only | AI-tool use; non-interactive automation restricted |
| Tencent General Lite | **¥39 ≈ $5.81/mo** | specific-client-only | broad model mix; same usage restriction |
| Xiaomi MiMo Lite | **~$6/mo** | specific-client-only | coding-client Token Plan; no 5h cap |
| Baidu Qianfan 50K welfare pack | **¥45 first buy / ¥50 list ≈ $6.71/$7.45** | specific-client/token pack | first-buy discount; multi-model |
| **Command Code GOAT** | **$10/mo** | **agent/CLI + OpenAI/Anthropic-compatible Provider API** | $70 included usage; unlike Go, API explicitly included |
| OpenCode Go | **$10/mo** | provider/API for coding agents | 27-model curated pool |

**Classification reminder:** an API-shaped key tied to a vendor coding plan is still **specific-client-only** if the terms prohibit custom backends, automation or batch use. Command Code Go is **not API access**; Command Code's Provider API is a separate eligible plan/path.

Sources: [Command Code Provider API](https://commandcode.ai/docs/provider) · [Tencent Token Plan overview](https://cloud.tencent.com/developer/article/2676529) · [Baidu Qianfan welfare pack](https://cloud.baidu.com/product/qianfan_home/token.html)

## NEW MODELS

No major frontier model release was verified on September 6. The most recent consequential launches remain **GLM-5.3-Flash** (September 4, production identity of Ox Alpha), **GPT-6 Astra** (September 3/4 rollout), and **Muse Spark 1.3** (September 2). Today's changes are primarily pricing, provider routes and free-tier churn.

### Community watch — unverified

Reddit discussion around **Omen Alpha** continues to point toward a GLM/Zhipu-family identity based on tokenizer/behavior fingerprinting, with mixed reports on coding/tool reliability. OpenCode still does **not** identify the model. A community claim says the GLM-5.3-Flash 2× Go promo ends Sep. 13; OpenCode's first-party page only says “limited time,” so Sep. 13 remains **unverified**.

## BEST VALUE TODAY

**Best free coding capacity:** OpenCode's six Zen freebies, OpenRouter Pareto Code, and Vercel/OpenRouter MiniMax M3 are still the strongest no-cost pool. Treat Contributor routes as training-permitted and avoid confidential code there.

**Best cheap paid DeepSeek:** OpenRouter/Baidu at **$0.04998/$0.09996/M** wins raw token cost. Alibaba Virginia at **$0.138/$0.275** is the stronger hyperscaler-style middle ground. Azure Direct at **$0.19/$0.51** costs more but can be worth it for Microsoft governance, privacy, Entra/RBAC, procurement and private-networking requirements. DeepSeek direct remains valuable for first-party routing and **$0.007/M off-peak cache hits**.

**Best cheap OpenAI route for asynchronous work:** GPT-6 Astra Batch/Flex at **$5/$25/M**, exactly half Standard, is a better value than paying $10/$50 when latency is not important.

**Best value inside OpenCode Go:** GLM-5.3-Flash remains attractive while its 2× usage promo is live; MiMo-V2.5 remains the high-volume workhorse. The current DeepSeek ZDR agreement removes the privacy uncertainty that existed earlier in the week.
