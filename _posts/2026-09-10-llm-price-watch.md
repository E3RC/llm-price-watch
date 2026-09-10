---
layout: post
title: "LLM Price Watch — September 10, 2026"
date: 2026-09-10 07:31:00 -0400
summary: "DeepSeek V4.1 Flash launches with native vision and sharply lower pricing, lands immediately on OpenCode Go with temporary 4x usage, while Azure and OpenRouter have not yet surfaced the new model in their current catalogs."
---

## 🚨 Top changes today

| Change | Why it matters |
|---|---|
| **DeepSeek V4.1 Flash launched today** | New `deepseek-flash` API model, 1M context, 384K max output, native vision, tool calls, Responses + Anthropic APIs. DeepSeek says it now beats V4 Pro across performance, cost, speed and total time. |
| **Direct API price drops hard** | V4.1 Flash is **$0.15 input / $0.60 output off-peak**, $0.30/$1.20 peak, with **$0.003/M cache hits off-peak**. |
| **OpenCode Go added V4.1 Flash immediately** | Model ID `deepseek-flash`; normal Go allowance is $15/month, but the current Go landing page shows a **temporary 4x boost to $60 and ~26,000 requests/5h**. |
| **Legacy DeepSeek aliases are being retired upstream** | `deepseek-v4-flash` and `deepseek-v4-flash-vision-exp` now temporarily route to V4.1 Flash. From **Sep. 14 at 12:00 Beijing time**, `deepseek-v4-pro` will also route to V4.1 Flash and bill at Flash rates until V4.1 Pro arrives. |
| **Azure is behind the model transition this morning** | Foundry still surfaces Azure Direct **DeepSeek V4 Flash**, not V4.1 Flash, in today's catalog scan. Azure's older Flash route remains $0.19/$0.51/M. |
| **OpenRouter has not surfaced V4.1 Flash yet** | No first-party OpenRouter model page for V4.1 Flash surfaced in today's scan; the older V4 Flash 0731 remains available from multiple providers. |
| **Tencent GLM-5.3-Flash 50% promo ends TODAY** | Effective ~$0.075 input / $0.25 output per M through **23:59:59 Beijing time Sep. 10** (about noon EDT). |
| **Mercury 2.5 launch pricing is still live** | OpenRouter still shows **80% off: $0.04/$0.15/M**. |

Sources: [DeepSeek change log](https://api-docs.deepseek.com/updates/), [DeepSeek pricing](https://api-docs.deepseek.com/quick_start/pricing/), [OpenCode Go](https://dev.opencode.ai/docs/go/), [OpenCode Go landing page](https://dev.opencode.ai/go), [Tencent TokenHub pricing](https://www.tencentcloud.com/document/product/1300/78937), [Azure catalog](https://ai.azure.com/catalog), [OpenRouter](https://openrouter.ai/).

## OpenCode Go

OpenCode Go remains **$10/month** and behaves as a provider/API for coding agents. Today's docs expose DeepSeek V4.1 Flash alongside the legacy DeepSeek IDs while those aliases are in transition upstream. OpenCode continues to state that its DeepSeek ZDR agreement is valid through **September 30, 2026**.

| Model | $/M input → output | Normal monthly allowance | Modality / privacy | Change |
|---|---:|---:|---|---|
| Omen Alpha | $0.20 → $0.66 | $100 | image+text · ZDR | stealth |
| GLM-5.3-Flash | $0.15 → $0.50 | $60 | multimodal · ZDR | 2x promo still advertised |
| GLM-5.3 | $1.40 → $4.40 | $15 | text/agent · ZDR | — |
| GLM-5.2 | $1.40 → $4.40 | $60 | text/agent · ZDR | — |
| GLM-5.1 | $1.40 → $4.40 | $60 | text/agent · ZDR | — |
| GPT 5.6 Luna | $0.20 → $1.20* | $15 | vision+text · 30d | — |
| Kimi K3 | $3 → $15 | $15 | multimodal · ZDR | — |
| Kimi K2.7 Code | $0.95 → $4 | $60 | image+text coding · ZDR | — |
| Kimi K2.6 | $0.95 → $4 | $60 | multimodal · ZDR | — |
| LongCat-2.0 | $0.30 → $1.20 | $60 | agent · ZDR | — |
| MiMo-V2.5 | $0.14 → $0.28 | $60 | multimodal · ZDR | — |
| MiMo-V2.5-Pro | $0.435 → $0.87 | $15 | multimodal · ZDR | — |
| MiniMax M3 | $0.30 → $1.20 | $60 | multimodal · ZDR | — |
| MiniMax M2.7 | $0.30 → $1.20 | $60 | agent · ZDR | — |
| Muse Spark 1.3 Contributor | $0.10 → $0.20 | $60 | multimodal · **training permitted** | — |
| Muse Spark 1.2 Contributor | $0.10 → $0.20 | $60 | agent · **training permitted** | — |
| Qwen3.8 Max | $2 → $6 | $15 | multimodal · ZDR | — |
| Qwen3.8 Flash | $0.15 → $0.47 | $30 | text/image/video · ZDR | — |
| Qwen3.7 Max | $2.50 → $7.50 | $30 | agent · ZDR | — |
| Qwen3.7 Plus | $0.40 → $1.60* | $60 | multimodal · ZDR | — |
| Qwen3.6 Plus | $0.50 → $3* | $60 | agent · ZDR | — |
| **DeepSeek V4.1 Flash** | **$0.15 → $0.60 off-peak** | **$15 normal → $60 promo** | **native multimodal · ZDR** | **NEW · 4x usage** |
| DeepSeek V4 Pro | $0.66 → $1.98 off-peak | $15 | text · ZDR | upstream retirement Sep. 14 |
| DeepSeek V4 Flash | $0.15 → $0.60 off-peak | $30 | legacy alias · ZDR | now V4.1-priced |
| DeepSeek V4 Flash Vision Exp | $0.15 → $0.60 off-peak | $15 | legacy alias · ZDR | now V4.1-priced |
| Hy4 Preview | $0.834 → $2.501 | $30 | agent · ZDR | — |
| Hy3 | $0.14 → $0.58 | $60 | agent · ZDR | — |

\* Higher-context tiers differ. DeepSeek peak rates are 2x off-peak. Current Go docs define 5-hour limits at 20% and weekly limits at 50% of each model's monthly allowance.

**Catalog-count oddity:** OpenCode's current docs expose 28 selectable names while the landing page still says “all 27 models.” The most plausible reason is that retired DeepSeek aliases remain temporarily exposed while routing to V4.1 Flash; treat the model IDs, not the marketing counter, as the source of truth.

Sources: [OpenCode Go docs](https://dev.opencode.ai/docs/go/) and [Go landing page](https://dev.opencode.ai/go).

## OPENCODE FREE / PREVIEW DEALS

Zen still documents six $0 routes:

| Model ID | Access Type | Cost | Notes |
|---|---|---:|---|
| `big-pickle` | Zen provider API | **$0** | stealth; data may be used for model improvement |
| `mimo-v2.5-free` | Zen provider API | **$0** | limited-time |
| `ling-3.0-flash-fin-free` | Zen provider API | **$0** | limited-time |
| `nemotron-3-ultra-free` | Zen provider API | **$0** | NVIDIA trial/logging terms |
| `nemotron-3.5-lightning-free` | Zen provider API | **$0** | NVIDIA trial/logging terms |
| `muse-spark-1.3-contributor-free` | Zen provider API | **$0** | **Meta training permitted** |

GPT-5.6 Sol remains **50% off through September 18** at $2/$10 per M for <=272K-token requests. Source: [OpenCode Zen](https://dev.opencode.ai/docs/zen).

## OPENROUTER DEALS

| Route | Access Type | Current price | Note |
|---|---|---:|---|
| `openrouter/free` | OpenAI-compatible API/router | **$0** | 200K router context; chooses among compatible free models |
| `openrouter/pareto-code` | API/router | **$0 page price** | 13 coding models, 2M context |
| MiniMax M3 Free | General API | **$0** | 1M multimodal; rate limited |
| Inkling Free | General API / special research terms | **$0** | 1M multimodal; avoid confidential data |
| Mercury 2.5 | General API | **$0.04/$0.15** | still 80% off |
| DeepSeek V4 Flash 0731 / OpenInference | General API | ~$0.05/$0.16 | **old V4**, not today's V4.1 |
| MiniMax M2.7 paid | General API | $0.21/$0.84 | 8 providers; provider-specific discounts vary |

**V4.1 status:** no current OpenRouter page for DeepSeek V4.1 Flash surfaced in this morning's scan. Do not confuse the very cheap V4 Flash 0731 routes with the new V4.1 model.

Sources: [OpenRouter Free Router](https://openrouter.ai/openrouter/free), [MiniMax M3 Free](https://openrouter.ai/minimax/minimax-m3:free), [Mercury 2.5](https://openrouter.ai/inception/mercury-2.5), [OpenRouter free collection](https://openrouter.ai/collections/free-models).

## AZURE AI FOUNDRY COMPARISON

Azure's big news today is actually what it **doesn't** have yet: the catalog still exposes Direct-from-Azure DeepSeek V4 Flash, while V4.1 Flash launched on DeepSeek direct and OpenCode Go this morning.

| Model / route | Azure mode | Azure cost | Best current comparison | Take |
|---|---|---:|---|---|
| **DeepSeek V4 Flash** | Azure Direct serverless PAYG | **$0.19/$0.51; cache $0.028** | DeepSeek **V4.1** direct $0.15/$0.60 off-peak, cache $0.003 | Azure cheaper on output than V4.1 off-peak, but serves older text-only model |
| **DeepSeek V4.1 Flash** | **not surfaced in today's Azure catalog scan** | — | DeepSeek direct / OpenCode Go | direct has model freshness + native vision lead |
| DeepSeek V4 Pro | Azure Direct serverless PAYG | $1.74/$3.48; cache $0.145 | direct Pro $0.66/$1.98 off-peak; Pro retires upstream Sep. 14 | hard to justify on raw cost |
| Kimi K3 | Fireworks on Foundry | partner PAYG/PTU | direct/aggregator pricing | not Azure Direct privacy boundary |
| MiniMax M3 | Fireworks on Foundry | partner PAYG/PTU | OpenRouter currently free | governance route, not bargain route |
| Qwen3.8-27B | open-weight/managed deployment | GPU/compute | Alibaba serverless API | not apples-to-apples |
| A100/H100/H200/MI300 | Azure managed compute | public page shows `$-` | dedicated GPU hosting | quote/calculator required |

For **Models sold by Azure**, Microsoft says inference is stateless and prompts/completions are not used to train or improve base models; processing follows the selected geography rules, with Global/DataZone exceptions. Fireworks-on-Foundry is a separate non-Microsoft product with a different data boundary.

Azure's public managed-compute table still shows `$-` for A100/H100/H200/MI300 compute-hour pricing. The DeepSeek provisioned table also currently exposes `$-` for V4 PTU pricing; older DeepSeek R1/V3 rows show a 100-PTU minimum. Do not convert these into fake $/M-token equivalents.

Sources: [Azure model catalog](https://ai.azure.com/catalog), [DeepSeek V4 Flash catalog](https://ai.azure.com/catalog/models/DeepSeek-V4-Flash), [Azure Foundry data/privacy](https://learn.microsoft.com/en-us/azure/foundry/responsible-ai/openai/data-privacy), [Foundry pricing](https://azure.microsoft.com/en-us/pricing/details/ai-foundry-models/).

## DIRECT CHINESE API PRICING / FIRST-PARTY SCAN

| Vendor | Current first-party finding | Access Type |
|---|---|---|
| **DeepSeek** | **V4.1 Flash NEW: $0.15/$0.60 off-peak; $0.30/$1.20 peak; cache $0.003/$0.006** | **General OpenAI + Anthropic-compatible API** |
| **Alibaba/Qwen** | Qwen3.8 Flash Virginia Global: **¥0.8/¥2.7 per M** (~$0.12/$0.41 at ~¥1=$0.15) | General API |
| Alibaba-hosted DeepSeek | still lists pre-V4.1 DeepSeek routes; no V4.1 surfaced this morning | General API |
| **Xiaomi/MiMo** | MiMo-V2.5: **$0.14 input / $0.28 output / $0.0028 cache hit**, 1M multimodal | General API |
| **Tencent** | GLM-5.3-Flash list $0.15/$0.50, **50% billed through Sep. 10** | General API |
| Moonshot/Kimi | Kimi K3 remains current flagship; no material same-day first-party price change surfaced | General API |
| MiniMax | M3 remains current 1M multimodal coding/agent flagship; no same-day direct-price change surfaced | General API / Token Plan |
| **SenseNova** | Public beta still **¥0, 60,000 credits/5h, up to 20 API keys** | Plan API / agent endpoint |
| **StepFun** | Entry subscription **¥39/month, 1,300 credits** | hosted/specific-client agent |
| Baidu/Qianfan | Enterprise Token Plan still advertises DeepSeek/GLM/Kimi + night usage discounts; no V4.1 listing surfaced | plan/tool access |
| ByteDance/Doubao | no newly verified same-day coding/API promotion surfaced | API / hosted |
| 01.AI/Yi | no new hosted-API bargain surfaced | open weights/self-host |

Currency reference is approximate; regional billing and taxes can differ.

Sources: [DeepSeek pricing](https://api-docs.deepseek.com/quick_start/pricing/), [Alibaba Model Studio pricing](https://help.aliyun.com/zh/model-studio/model-pricing), [Xiaomi MiMo pricing](https://mimo.mi.com/models/en-US/mimo-v2.5), [Tencent TokenHub pricing](https://www.tencentcloud.com/document/product/1300/78937), [SenseNova Token Plan](https://www.sensenova.cn/en/token-plan), [StepFun subscription](https://www.stepfun.com/subscription).

## LOW-COST SUBSCRIPTIONS ($3-$10)

| Plan | Price | Access Type | Note |
|---|---:|---|---|
| Command Code Go | **$1/mo** | **agent/CLI-only — NO Provider API** | current free/discounted model routes make it an excellent spare bucket |
| Tencent Hy Lite | ~¥28/mo | specific-client-only | Hunyuan-oriented plan |
| StepFun Entry | **¥39/mo** | hosted/specific-client | 1,300 credits |
| Xiaomi MiMo Lite | **$6/mo / ¥39** | specific-client/tool-oriented Token Plan | 4.1B credits; OpenCode/Codex/Claude Code supported |
| Alibaba Token Plan Lite | **$8 list / $6 promo** | specific-client/tool-oriented | 2,500 credits per 7 days |
| Command Code GOAT | **$10/mo** | **agent/CLI + OpenAI/Anthropic-compatible Provider API** | unlike Go, Provider API is included |
| OpenCode Go | **$10/mo** | coding-agent provider/API | model-specific allowance pools; V4.1 Flash temporarily 4x |

Command Code's current docs remain explicit that **Go is the exception without Provider API access**; eligible higher tiers can use its OpenAI/Anthropic-compatible API.

Sources: [Command Code Provider API](https://commandcode.ai/docs/provider), [Xiaomi Token Plan](https://mimo.mi.com/docs/en-US/price/token-plan), [Alibaba Token Plan](https://help.aliyun.com/en/model-studio/token-plan).

## NEW MODEL: DeepSeek V4.1 Flash

This is the release that matters today. DeepSeek calls V4.1 Flash the smallest model in a new architecture family and gives it native visual understanding, 1M context and 384K maximum output. Its own published benchmarks include **Terminal-Bench 2.1 90.6, DeepSWE v1.1 74.2 and NL2Repo-Bench 65.4**. DeepSeek says its internal/external testing found V4.1 Flash better than V4 Pro on performance, cost, speed and total task time.

The transition is unusually aggressive: legacy Flash and Vision aliases already map to V4.1 Flash, and **V4 Pro will map to it starting Sep. 14 at noon Beijing time** until V4.1 Pro is released. That makes V4.1 Flash both a new model release and a de facto replacement for the current Pro endpoint.

Source: [DeepSeek September 10 change log](https://api-docs.deepseek.com/updates/).

## BEST VALUE TODAY

**1. First test: DeepSeek V4.1 Flash through OpenCode Go.** The 4x usage promotion makes the normal $15 model pool behave like $60 during the promo, while preserving OpenCode's current DeepSeek ZDR terms. If the public landing page and community timing agree, this is a short-lived window worth using heavily.

**2. Also test direct DeepSeek V4.1 Flash.** Off-peak $0.15/$0.60 with a $0.003 cache-hit rate is cheap enough that a heavily cached coding agent can consume enormous context for very little money, and direct API gets the freshest model immediately.

**3. Tencent GLM-5.3-Flash is a use-it-today deal.** Its 50% discount expires at 23:59:59 Beijing time today, roughly noon U.S. Eastern time.

**4. Mercury 2.5 remains a great scout/subagent route.** OpenRouter still shows $0.04/$0.15 under the 80%-off launch promotion.

**5. Azure is not where to test V4.1 today.** Azure Direct remains compelling for enterprise governance and Microsoft-hosted data handling, but model freshness currently favors DeepSeek direct/OpenCode. Recheck Foundry as soon as V4.1 appears.

**6. No need to add another premium $20-class seat just for today's changes.** The interesting incremental value is concentrated in the existing OpenCode Go tier, direct DeepSeek, free OpenRouter routes, Mercury's launch promo and the $1-$10 coding-agent plans.
