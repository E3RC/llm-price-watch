---
layout: post
title: "LLM Price Watch — September 6, 2026"
date: 2026-09-06 08:29:00 -0400
summary: "Vercel is serving MiniMax M3 and M2.7 for free, OpenCode Go remains unchanged with GLM-5.3-Flash at 2x usage, OpenRouter's Baidu DeepSeek route stays near five cents per million input tokens, and Azure remains a governance play rather than the raw-price winner."
---

## 🚨 Top changes today

| Change | Why it matters |
|---|---|
| **🔥 Vercel AI Gateway has BOTH MiniMax M3 and MiniMax M2.7 free** | `minimax/minimax-m3` remains free and the explicit `minimax/minimax-m2.7-free` route is also live. M3 gives 1M context and multimodal input; M2.7 Free gives ~197K context/output and is especially strong for software-engineering agents. |
| **⚠️ Community says the Vercel M3 free promo may end today** | Reddit has circulated **September 6** as the M3 expiry date, but Vercel's first-party page still says **Free** and publishes no end date. Treat the expiry claim as unverified and use it now if useful. |
| **OpenCode Go is steady at 27 models** | No new Go model ID today. GLM-5.3-Flash still gets **2× usage for a limited time**; MiMo-V2.5 remains the high-volume workhorse and Omen Alpha remains the newest stealth route. |
| **OpenCode Zen's current indexed docs show six advertised free models** | Big Pickle, MiMo-V2.5 Free, Ling 3.0 Flash Fin Free, Nemotron 3 Ultra Free, Nemotron 3.5 Lightning Free and Muse Spark 1.3 Contributor Free. An older cached `/v1/models` snapshot exposes extra legacy free IDs; those are **not counted as live deals without fresh confirmation**. |
| **🔥 OpenRouter/Baidu DeepSeek V4 Flash remains ~$0.05/$0.10 per M** | Baidu Qianfan is still **$0.04998 input / $0.09996 output**, with $0.009996 cache reads. The Nitro variant headlines $0.045/$0.09. |
| **OpenRouter free coding remains unusually strong** | Pareto Code is still $0 with 13 coding models and 2M context; Ling 3.0 Flash and Ling 3.0 Flash Sante have free routes; Dots3 Note stays free through Sep. 30. |
| **Azure is still not the raw-price winner on DeepSeek** | Azure Direct DeepSeek V4 Flash is $0.19/$0.51/cache $0.028. OpenRouter/Baidu is much cheaper, but Azure Direct has the stronger Microsoft data boundary and enterprise procurement/governance story. |
| **No major same-day frontier model launch verified** | Sunday movement is primarily free-route availability, routing discounts and subscription economics rather than a new flagship release. |

Sources: [OpenCode Go](https://dev.opencode.ai/docs/go/) · [OpenCode Zen](https://dev.opencode.ai/docs/zen) · [Vercel M3](https://vercel.com/ai-gateway/models/minimax-m3) · [Vercel M2.7 Free](https://vercel.com/ai-gateway/models/minimax-m2.7-free) · [OpenRouter DeepSeek](https://openrouter.ai/deepseek/deepseek-v4-flash-0731) · [Azure DeepSeek](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/introducing-deepseek-v4-flash-and-v4-pro-in-microsoft-foundry/4515174)

## OpenCode Go

Go remains **$10/month**, with shared limits of **$12/5h, $30/week and $60/month**. The lineup remains 27 models. GLM-5.3-Flash still has the temporary **2× usage** promotion. DeepSeek ZDR remains documented through **September 30, 2026**.

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
| Omen Alpha | $0.20 → $0.66 | 11,600 | image + text | ZDR | stealth / identity unconfirmed |

\* Higher-context tiers differ. OpenCode's current Go rate/allowance table still uses the DeepSeek peak/off-peak schedule; weekends are off-peak all day. Muse Contributor explicitly permits training on prompts/completions.

Sources: [OpenCode Go docs](https://dev.opencode.ai/docs/go/) · [Go landing page](https://dev.opencode.ai/go)

## OPENCODE FREE / PREVIEW DEALS

The freshest indexed English Zen pricing page currently advertises **six** free models. Per-model free quotas/reset windows are not published, so do not treat $0 as unlimited.

| Model / ID | Access Type | Cost | Context / modality | Limits / privacy / status |
|---|---|---:|---|---|
| `big-pickle` | Zen provider API | **$0** | stealth | limited-time; free-period data may improve model |
| `mimo-v2.5-free` | Zen provider API | **$0** | ~1M / multimodal | limited-time; feedback/model improvement |
| `ling-3.0-flash-fin-free` | Zen provider API | **$0** | ~262K / coding-text | limited-time; feedback/model improvement |
| `nemotron-3-ultra-free` | Zen provider API | **$0** | agent | NVIDIA trial/logging terms |
| `nemotron-3.5-lightning-free` | Zen provider API | **$0** | agent | NVIDIA trial/logging terms |
| `muse-spark-1.3-contributor-free` | Zen provider API | **$0** | ~1M / multimodal-agent | **training permitted; limited-time** |
| `muse-spark-1.2-contributor-free` | former documented free route | — | agent | no longer in current indexed free list |
| Ox Alpha | ended preview | — | became GLM-5.3-Flash | ended |
| Hy3 Free | ended/unlisted | — | agent | no longer documented free |

**Stealth/catalog watch:** a cached Zen `/v1/models` response from an older crawl contains IDs such as `deepseek-v4-flash-free`, `north-mini-code-free`, `laguna-s-2.1-free`, `longcat-2.0-free`, `ling-3.0-tiny-free` and `ling-3.0-flash-free`. Because that snapshot is stale and today's indexed pricing page does not advertise them, they are **watch-list IDs, not confirmed live deals**.

Also active: **GPT-5.6 Sol remains 50% off on Zen through September 18**.

Source: [OpenCode Zen](https://dev.opencode.ai/docs/zen)

## OPENROUTER DEALS

| Route | Access Type | Current price | Why it matters |
|---|---|---:|---|
| `openrouter/free` | OpenAI-compatible API/router | **$0** | **24-model** rotating capability-aware pool; 200K router context |
| `openrouter/pareto-code` | OpenAI/Anthropic-compatible router | **$0** | **13 coding models, 2M context** |
| Ling 3.0 Flash Free | General API | **$0** | 262K coding/agent model; free endpoint is rate-limited |
| **Ling 3.0 Flash Sante Free** | General API | **$0** | 262K, tools; medical specialization but retains coding/agent capability |
| Ling 3.0 Flash Fin Free | General API | **$0** | 262K finance-specialized sibling |
| **Dots3 Note Preview Free** | General API | **$0 through Sep. 30** | 512K, text+image, tools; explicit expiry |
| MiniMax M3 Free | General API | **$0 this morning** | 1M multimodal; rate-limited/free-route availability can change |
| **DeepSeek V4 Flash / Baidu Qianfan** | General API | **$0.04998 → $0.09996/M** | cache read $0.009996; cheapest clearly identified paid route found |
| DeepSeek V4 Flash Nitro | General API/router | headline **$0.045 → $0.09/M** | speed-oriented variant; provider routing may vary |

OpenRouter's ordinary free-model allowance is up to **50 requests/day**, increasing to **1,000/day after $10 in purchased credits**; individual free providers can be tighter.

Sources: [Free Router](https://openrouter.ai/openrouter/free/providers) · [Pareto Code](https://openrouter.ai/openrouter/pareto-code) · [DeepSeek V4 Flash](https://openrouter.ai/deepseek/deepseek-v4-flash-0731) · [Ling Sante](https://openrouter.ai/inclusionai/ling-3.0-flash-sante:free) · [Dots3 Note](https://openrouter.ai/dots-studio/dots-3-note-preview:free)

## FREE ACCESS OUTSIDE OPENCODE / OPENROUTER

| Offer | Access Type | Current deal | Catch |
|---|---|---|---|
| **Vercel AI Gateway — MiniMax M3** | OpenAI/Anthropic-compatible API gateway | **FREE now** | 1M context, text/image/video; first-party page has no expiry |
| **Vercel AI Gateway — MiniMax M2.7 Free** | OpenAI/Anthropic-compatible API gateway | **FREE now** | `minimax/minimax-m2.7-free`, ~197K context/output, GMICloud free route |
| SenseNova International beta | Plan API / agent endpoint | **$0; 1,500 calls/model/5h** | SenseNova 6.8 Flash Lite + U1 Fast; up to 20 API keys |
| **Command Code Laguna S 2.1** | Go = agent/CLI-only | **$0 while capacity lasts** | requests consume no credits during promo |
| **Command Code Ling 3.0 Flash** | Go = agent/CLI-only | **$0** | current $0 model route |
| **Command Code LongCat 2.0** | Go = agent/CLI-only | **$0 while it lasts** | 1M context |
| Azure new account | Azure services credit | **$200 / 30 days** | Marketplace/model eligibility varies |

**Reddit lead, verified partially:** community posts say the Vercel/GMI MiniMax M3 free route expires **today, Sep. 6**. Vercel still shows it as Free right now and publishes no expiry, so the route is confirmed live but the end date is **community-only / unverified**.

Sources: [Vercel M3](https://vercel.com/ai-gateway/models/minimax-m3) · [Vercel M2.7 Free](https://vercel.com/ai-gateway/models/minimax-m2.7-free) · [SenseNova Token Plan](https://www.sensenova.ai/token-plan) · [Command Code pricing](https://commandcode.ai/docs/resources/pricing-limits)

## AZURE AI FOUNDRY COMPARISON

Azure now advertises **11,000+ catalog models**, but catalog presence does not imply a single hosting, pricing or privacy model. Separate **Direct from Azure**, **Fireworks/partner inference**, **managed compute**, and **provisioned throughput (PTU)**.

| Model | Azure route | Azure price / billing | Comparable route | Verdict |
|---|---|---:|---|---|
| **DeepSeek V4 Flash** | **Azure Direct serverless** | **$0.19 in / $0.51 out / $0.028 cache per M** | OR/Baidu $0.04998/$0.09996; Alibaba routes can also be lower | **enterprise value; not raw-price winner** |
| **DeepSeek V4 Pro** | Azure Direct serverless | **$1.74 / $3.48 / $0.145** | direct/aggregator routes can be materially lower | substantial Azure premium |
| DeepSeek V4 Flash 0731 | Azure Direct Preview | portal/catalog pricing | OR/Baidu route is public and cheap | Azure deployment boundary is the value |
| Kimi K2.7 Code | **Fireworks on Foundry** | partner/portal | common market rate ~$0.95/$4 | partner infrastructure, not Azure Direct privacy |
| Kimi K3 | Fireworks on Foundry | partner PAYG/PTU | direct/aggregator alternatives | procurement convenience, partner boundary |
| MiniMax M3 | Fireworks on Foundry | partner PAYG/PTU | **free routes exist today** | not a value route for experiments |
| Qwen3.8-27B | open-weight catalog / managed deployment | GPU/compute billing | Qwen hosted API | not apples-to-apples with $/M tokens |
| Managed A100/H100/H200/MI300 | Azure managed compute | public table currently `$-` | self-host/provider GPU | calculator/quote required |
| Provisioned throughput | Azure PTU | commitment/throughput billing | serverless PAYG | older DeepSeek rows show **100 PTU minimum**; V4 numeric PTU price not public |

**Azure Direct privacy:** Microsoft says prompts, outputs, embeddings and training data are **not available to the model provider** and are not used to train foundation models without permission. Global deployments may process in any geography where the model is deployed; Data Zone restricts processing to the specified zone.

**Partner warning:** Fireworks-on-Foundry models are explicitly Non-Microsoft products. Their catalog pages say data is sent outside Microsoft systems and normal Foundry data-residency documentation does not apply.

Sources: [Foundry pricing](https://azure.microsoft.com/en-us/pricing/details/ai-foundry-models/deepseek/) · [DeepSeek V4 Flash catalog](https://ai.azure.com/catalog/models/DeepSeek-V4-Flash) · [Fireworks DeepSeek example](https://ai.azure.com/catalog/models/FW-DeepSeek-V4-Flash) · [Foundry data privacy](https://learn.microsoft.com/en-us/azure/foundry/responsible-ai/openai/data-privacy)

## DIRECT CHINESE API PRICING / FIRST-PARTY SCAN

| Vendor | Current first-party finding | Access Type |
|---|---|---|
| **DeepSeek** | Current V4 pricing uses peak/off-peak scheduling after the Aug. 16 adjustment; V4 Flash is commonly listed at **$0.22/$0.66 off-peak** and 2× peak, with very cheap cache hits. First-party V4 supports OpenAI Responses and Anthropic-compatible endpoints. | **General API** |
| **Alibaba/Qwen** | Current international `qwen3.8-flash` listing is **$0.15 input / $0.47 output per M**, 1M-class context; region-specific rates can be lower. | **General API** |
| **Alibaba Token Plan** | Personal Lite is **$6/mo limited-time** ($8 list), 2,500 credits/7d. It has an API-shaped key but is **interactive coding/agent use only**; production automation/backends/batch are prohibited. | **specific-client-only / interactive API-shaped subscription** |
| **Moonshot/Kimi** | No new first-party pricing change surfaced today; Kimi K2.7 Code remains widely available across direct and aggregator routes. | General API |
| **Zhipu/GLM** | No new pricing change after the Sep. 4 GLM-5.3-Flash launch surfaced today. | General API |
| **MiniMax** | M3/M2.7 remain available on MiniMax's open platform; no new first-party price change surfaced. Vercel is the standout free access today. | General API + coding plan |
| **Xiaomi/MiMo** | No new first-party subscription/API price change surfaced today. MiMo-V2.5 remains one of the cheapest high-volume models across coding plans. | API + specific-client plans |
| **Tencent/Hunyuan** | No new same-day pricing change surfaced; Hy-focused low-cost plan remains a watch item. | API + specific-client plans |
| **Baidu/Qianfan** | Current 50K-credit welfare pack is **¥45 first purchase / ¥50 list** (~$6.71/$7.45 at today's FX), with larger packs scaling up. | specific-client/token pack |
| **ByteDance/Doubao** | No newly verified coding-plan promotion today; recent vendor material continues to advertise aggressive Seed 2.1 API pricing. | General API + hosted plans |
| **StepFun** | No new verified pricing/model launch surfaced today. | API + hosted plans |
| **SenseTime/SenseNova** | International public beta remains **$0**, 1,500 calls per model every 5h. | **Plan API / agent endpoint** |
| **01.AI/Yi** | No new hosted API/deal surfaced today; open-weight/self-hosted Yi is a separate category. | open weights / self-host |

Sources: [DeepSeek changelog](https://api-docs.deepseek.com/updates/) · [Alibaba model pricing](https://docs.modelstudio.console.alibabacloud.com/en/model-studio/model-pricing) · [Alibaba Token Plan](https://www.alibabacloud.com/help/en/model-studio/token-plan-overview) · [Baidu Token pack](https://cloud.baidu.com/product/qianfan_home/token.html) · [SenseNova](https://www.sensenova.ai/token-plan)

## LOW-COST SUBSCRIPTIONS ($3–$10 focus)

| Plan | Price | Access Type | Current value |
|---|---:|---|---|
| **Command Code Go** | **$1/mo** | **agent/CLI-only — NO Provider API** | $10 monthly credits; Laguna, Ling and LongCat currently cost no model credits |
| Tencent Hy Lite | ~**$4.17/mo** (¥28) | specific-client-only | low-cost Hy-focused coding/agent capacity |
| **Alibaba Token Plan Lite** | **$6/mo promo** | **specific-client-only / interactive API-shaped key** | 2,500 credits/7d; Singapore; OpenAI/Anthropic protocol tools supported, automation/backends prohibited |
| Baidu 50K-credit welfare pack | ~**$6.71 first buy / $7.45 list** | specific-client/token pack | current first-party ¥45/¥50 pricing |
| **Command Code GOAT** | **$10/mo** | **agent/CLI + OpenAI/Anthropic-compatible Provider API** | $70 monthly credits; unlike Go, API access is explicitly included |
| OpenCode Go | **$10/mo** | provider/API for coding agents | broad curated pool with $60 monthly nominal model value |

Command Code's current Provider documentation is explicit: **every plan except Go has Provider API access**. The standalone Provider plan is $15/month, while GOAT/Pro/Max/Team can use the same OpenAI/Anthropic-compatible endpoints against their plan credits.

Sources: [Command Code Provider API](https://commandcode.ai/docs/provider) · [Command Code pricing](https://commandcode.ai/docs/resources/pricing-limits) · [Alibaba Token Plan rules](https://docs.modelstudio.console.alibabacloud.com/en/model-studio/token-plan-personal-overview)

## NEW MODELS

No major frontier coding model was verified as launching on **September 6**. The newest notable releases in the active deal pool remain:

- **GLM-5.3-Flash — Sep. 4:** the production identity of Ox Alpha, natively multimodal and currently promoted at 2× Go usage.
- **Ling 3.0 Flash Sante — Sep. 4:** medicine-specialized Ling variant retaining general coding/agent skills, with a free OpenRouter endpoint.
- **Muse Spark 1.3 — Sep. 2:** stronger long-horizon agent/coding behavior; its Contributor variant trades privacy for dramatically lower cost.

## 🏆 BEST VALUE TODAY

**Use-now temporary deal:** add **Vercel MiniMax M3 and M2.7 Free** as fallbacks. M3 is the more interesting multimodal/1M-context agent; M2.7 Free is a strong coding route with an explicit free model ID. The community believes M3 may expire today, but Vercel still shows it live and free.

**Best free coding router:** **OpenRouter Pareto Code** remains hard to beat at $0 with a 2M context window and a 13-model coding pool.

**Best tiny paid DeepSeek route:** OpenRouter's **Baidu Qianfan DeepSeek V4 Flash** at ~$0.05/$0.10 per M remains the raw-price winner found today. For code where route provenance and first-party handling matter more than the last few cents, keep the direct DeepSeek API in the toolbox.

**Best bundled private open-model capacity:** **OpenCode Go** remains excellent value, especially MiMo-V2.5 for volume and GLM-5.3-Flash while the 2× promotion is active. DeepSeek's Go routes remain documented ZDR through Sep. 30.

**Azure:** pay the premium when Azure Direct's identity/governance, private-networking options, consolidated procurement and Microsoft data boundary are worth more than raw inference cost. Do not pay Azure partner/managed-compute pricing expecting it to compete with promotional free API routes.

**No new subscription is compelling enough today to replace a stack that already covers premium coding agents, direct DeepSeek, a $10 open-model coding pool, Google access and a dedicated image-generation path.** Today's wins are free fallback capacity, not another $20 subscription.
