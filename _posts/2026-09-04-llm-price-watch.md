---
layout: post
title: "LLM Price Watch — September 4, 2026"
date: 2026-09-04 08:00:00 -0400
summary: "GPT-6 Astra lands in OpenAI and Azure, OpenCode Go adds Muse Spark 1.3 Contributor and Omen Alpha, and Azure DeepSeek pricing gets its first apples-to-apples comparison."
---

## 🚨 Top changes today

| Change | Why it matters |
|---|---|
| **GPT-6 Astra launched** | OpenAI lists $10/M input, $1/M cached input and $50/M output. Azure Foundry Global Standard matches that raw token price exactly; U.S. Data Zone is 10% higher. |
| **OpenCode Go grew to 27 models** | New **Muse Spark 1.3 Contributor** and **Omen Alpha** are now in the official Sep. 4 Go lineup. |
| **Omen Alpha has a $100 model-specific Go pool** | $0.20/M input, $0.66/M output and an estimated 11,600 requests/5h; notably generous inside a $10 Go subscription. |
| **Muse Spark 1.3 Contributor is extremely cheap—but trains** | $0.10/M input, $0.20/M output, estimated 45,300 requests/5h; OpenCode explicitly permits Meta to use prompts/completions for training. |
| **DeepSeek ZDR documentation is still stale** | OpenCode's Sep. 4 page still says the monthly DeepSeek zero-retention agreement is valid through **August 31, 2026**. Treat September ZDR as unconfirmed until that date changes. |
| **Azure DeepSeek Flash is cheaper than DeepSeek direct off-peak** | Azure: $0.19/$0.51 vs direct DeepSeek $0.22/$0.66 off-peak, although direct DeepSeek cache-hit pricing is much cheaper. OpenRouter remains the raw-price leader at $0.05/$0.16. |

## OpenCode Go

OpenCode Go remains **$10/month**, with a provider API key and base limits of **$12/5h, $30/week and $60/month**. The table below uses OpenCode's Sep. 4 estimates and nominal per-million-token rates.

| Model | Input → Output / M | Est. req/5h | Modality / privacy | Change |
|---|---:|---:|---|---|
| Grok 4.6 | $2 → $6* | 169 | text/agent · 30d | — |
| GPT-5.6 Luna | $0.20 → $1.20* | 2,050 | vision/text · 30d | — |
| GLM-5.3-Flash | $0.15 → $0.50 | 1,580 | multimodal/agent · ZDR | 2× promo banner continues |
| GLM-5.3 | $1.40 → $4.40 | 220 | agent · ZDR | — |
| GLM-5.2 | $1.40 → $4.40 | 880 | agent · ZDR | — |
| GLM-5.1 | $1.40 → $4.40 | 880 | agent · ZDR | — |
| Kimi K3 | $3 → $15 | 110 | multimodal/agent · ZDR | — |
| Kimi K2.7 Code | $0.95 → $4 | 1,350 | image+text coding · ZDR | — |
| Kimi K2.6 | $0.95 → $4 | 1,150 | multimodal · ZDR | — |
| LongCat-2.0 | $0.30 → $1.20 | 11,400 | agent · ZDR | — |
| MiMo-V2.5 | $0.14 → $0.28 | 30,100 | omnimodal · ZDR | — |
| MiMo-V2.5-Pro | $0.435 → $0.87 | 3,250 | multimodal · ZDR | — |
| MiniMax M3 | $0.30 → $1.20 | 3,200 | multimodal/agent · ZDR | — |
| MiniMax M2.7 | $0.30 → $1.20 | 3,400 | agent · ZDR | — |
| **Muse Spark 1.3 Contributor** | **$0.10 → $0.20** | **45,300** | multimodal/agent · **training YES** | **NEW** |
| Muse Spark 1.2 Contributor | $0.10 → $0.20 | 45,300 | agent · **training YES** | — |
| Qwen3.8 Max | $2 → $6 | 160 | multimodal · ZDR | — |
| Qwen3.8 Flash | $0.15 → $0.47 | 5,400 | text/image/video · ZDR | — |
| Qwen3.7 Max | $2.50 → $7.50 | 170 | agent · ZDR | — |
| Qwen3.7 Plus | $0.40 → $1.60* | 4,300 | multimodal · ZDR | — |
| Qwen3.6 Plus | $0.50 → $3* | 3,300 | agent · ZDR | — |
| DeepSeek V4 Pro | $0.66 → $1.98 off-peak | 1,050 | agent · ZDR? | stale Aug. 31 agreement |
| DeepSeek V4 Flash | $0.22 → $0.66 off-peak | 7,600 | coding · ZDR? | stale Aug. 31 agreement |
| DeepSeek V4 Flash Vision Exp | $0.22 → $0.66 off-peak | 3,800 | vision · ZDR? | stale Aug. 31 agreement |
| Hy4 Preview | $0.834 → $2.501 | 1,350 | agent · ZDR | — |
| Hy3 | $0.14 → $0.58 | 4,300 | agent · ZDR | — |
| **Omen Alpha** | **$0.20 → $0.66** | **11,600** | agent · ZDR | **NEW; $100 model pool** |

\* Higher-context tiers differ. DeepSeek peak rates are 2× the off-peak input/output rates shown.

Source: [OpenCode Go documentation](https://dev.opencode.ai/docs/go/).

## OpenCode free / preview deals

The live Zen model endpoint exposes **nine current $0-looking IDs**, including two unadvertised routes. Hidden routes should be considered opportunistic because OpenCode does not publish their quota, expiry or privacy terms.

| Model ID | Access Type | Cost | Notes |
|---|---|---:|---|
| `muse-spark-1.3-contributor-free` | Zen provider API | $0 | NEW; training allowed; Meta regional policy applies |
| `muse-spark-1.2-contributor-free` | Zen provider API | $0 | training allowed |
| `mimo-v2.5-free` | Zen provider API | $0 | multimodal |
| `ling-3.0-flash-fin-free` | Zen provider API | $0 | coding/agent |
| `nemotron-3-ultra-free` | Zen provider API | $0 | NVIDIA trial route |
| `nemotron-3.5-lightning-free` | Zen provider API | $0 | NVIDIA trial route |
| `big-pickle` | Zen provider API | $0 | stealth model |
| `deepseek-v4-flash-free` | Zen provider API | $0 | **hidden/unadvertised**; limits/privacy undocumented |
| `laguna-s-2.1-free` | Zen provider API | $0 | **hidden/unadvertised**; limits/privacy undocumented |

Live source: [OpenCode Zen model endpoint](https://opencode.ai/zen/v1/models). Reddit users are already reporting Muse 1.3 free-limit exhaustion and region errors; those reliability observations are community-only and not an official quota specification.

## OpenRouter deals

| Route | Access Type | Current price | Why it matters |
|---|---|---:|---|
| `openrouter/free` | OpenAI-compatible API/router | **$0** | 24-model pool, 200K router context, capability-aware routing |
| Pareto Code Router | API/router | **$0** | 2M context coding router |
| North Mini Code Free | General API | **$0** | 256K, tools, trained for OpenCode/SWE-Agent-style coding |
| MiniMax M3 Free | General API | **$0** | 1M context, text/image/video, coding/agents |
| **DeepSeek V4 Flash 0731 / OpenInference** | General API | **$0.05 → $0.16/M** | raw-cost leader; 1M+ context |
| DeepSeek V4 Flash / Relace | General API | $0.065 → $0.18/M | faster practical route; cache can lower effective input cost |
| **GLM-5.3-Flash** | General API | **$0.075 → $0.25/M** | 50%-off route, 1M+ context |
| Kimi K2.7 Code | General API | $0.66 → $3.40/M | 262K, image+text, tools and structured output |

OpenRouter's free-model account limit remains **50 requests/day at 20 RPM** with less than $10 purchased credits, or **1,000/day at 20 RPM** after adding at least $10 in credits. Free providers may log prompts, so they are not automatically appropriate for proprietary code.

Sources: [OpenRouter Free Router](https://openrouter.ai/openrouter/free), [DeepSeek V4 Flash 0731](https://openrouter.ai/deepseek/deepseek-v4-flash-0731), [GLM-5.3-Flash](https://openrouter.ai/provider/z-ai), [Kimi K2.7 Code](https://openrouter.ai/moonshotai/kimi-k2.7-code), [North Mini Code](https://openrouter.ai/cohere/north-mini-code), [MiniMax M3 Free](https://openrouter.ai/minimax/minimax-m3:free).

## Azure AI Foundry comparison

Azure is now a required part of this watch. Token-priced serverless/Standard deployments are kept separate from provisioned throughput and managed GPU compute.

| Model | Azure Foundry | Direct vendor | OpenRouter | Take |
|---|---:|---:|---:|---|
| **GPT-6 Astra, Global Standard short** | **$10 → $50/M**; cache $1, write $12.50 | OpenAI **$10 → $50/M** | — | **same raw rate as OpenAI** |
| GPT-6 Astra, US Data Zone short | $11 → $55/M; cache $1.10 | OpenAI $10 → $50/M | — | +10% for U.S. data-zone controls |
| GPT-6 Astra, Global long | $20 → $75/M | OpenAI long-context multiplier gives the same | — | same economics |
| **DeepSeek V4 Flash** | **$0.19 → $0.51/M**, cache $0.028 | direct off-peak $0.22 → $0.66; cache $0.007 | **$0.05 → $0.16** | Azure beats direct uncached/output; OR wins raw cost |
| **DeepSeek V4 Pro** | $1.74 → $3.48/M, cache $0.145 | direct off-peak $0.66 → $1.98 | about $0.58 → $1.74 headline | Azure carries a large premium |
| Kimi K2.7 Code | available in Foundry catalog | vendor/direct varies | $0.66 → $3.40 | Azure public page does not expose a stable numeric list rate |
| MiniMax M3 / GLM / Qwen families | broad Foundry/Fireworks/managed availability | vendor-specific | often cheap/free routes | compare deployment type before comparing price |

Microsoft's public Foundry pricing pages still render many third-party and provisioned-throughput prices as `$-`; use the Azure Pricing Calculator/account quote for those rather than inventing a token rate. Foundry itself is free to explore, and Azure still advertises **$200 in new-account credit for 30 days**.

Sources: [Azure GPT-6 Astra launch and pricing](https://azure.microsoft.com/en-us/blog/gpt-6-astra-frontier-intelligence-for-work-now-available-in-microsoft-foundry/), [Azure DeepSeek pricing](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/introducing-deepseek-v4-flash-and-v4-pro-in-microsoft-foundry/4515174), [Foundry pricing](https://azure.microsoft.com/en-us/pricing/details/microsoft-foundry/).

### Azure deployment-mode rule

**Azure serverless/Standard API** token rates can be compared directly with OpenRouter and vendor APIs. **Provisioned throughput** is commitment/capacity pricing and should be compared at a known utilization level. **Managed GPU compute** is infrastructure rental and must not be presented as equivalent to token-priced API inference.

Azure can still be the rational choice at a higher raw price when Entra ID, RBAC, private networking, enterprise governance, regional data boundaries, consolidated Azure procurement, or access to a difficult-to-buy model matters more than minimum token cost.

## New models

### GPT-6 Astra

OpenAI launched **GPT-6 Astra** on September 3. It has a **1.05M-token context window**, 128K maximum output, text+image input, and API pricing of **$10/M input, $1/M cached input, $12.50/M cache writes and $50/M output**. Inputs above 272K are billed at 2× input/cache and 1.5× output for the request. Batch/Flex are 50% of Standard. OpenAI says API and Plus/Pro/Business/Enterprise access is coming in the next few days, so existing ChatGPT Business users should not need a second subscription merely to try Astra.

Source: [OpenAI GPT-6 Astra model page](https://developers.openai.com/api/docs/models/gpt-6-astra).

### Muse Spark 1.3

Meta released **Muse Spark 1.3** September 2 through Muse Code and the Meta Model API. Meta says its engineers saw roughly **20% fewer tool calls and 25% fewer tokens** than Muse Spark 1.2. OpenCode added both a Go Contributor route and a free Contributor Zen route. Contributor access explicitly trades lower price for permission to train future Meta models on prompts/completions.

Source: [Meta Muse Spark 1.3 launch](https://research.meta.ai/blog/introducing-muse-spark-1-3).

## Direct Chinese API / plan scan

| Vendor | Current first-party finding | Access Type |
|---|---|---|
| **DeepSeek** | V4 Flash off-peak $0.22/$0.66; Pro $0.66/$1.98; peak is 2× | General OpenAI/Anthropic-compatible API |
| **Alibaba/Qwen** | Qwen3.8 Max US/Frankfurt/Tokyo $1.65/$4.951; Qwen3.8 Flash global regions $0.113/$0.382, Singapore $0.15/$0.47 | General API |
| **Alibaba Token Plan** | Lite **$6/mo** promo, 2,500 credits/7d, Singapore only | **Specific-client subscription** using OpenAI/Anthropic-compatible tooling; not a general backend quota |
| **Xiaomi/MiMo Lite** | **$6/mo**, 4.1B credits; first purchase 12% off; night 0.8× | **Specific-client-only coding plan**; regular API separate |
| **Tencent China General Lite** | **¥39/mo**, 780 credits; Sep. promo halves credit burn for Kimi K2.7 Code, MiniMax M3 and Auto | **Specific-client-only**; backend/automation API use explicitly prohibited |
| **Tencent Hy Lite** | **¥28/mo**, 560 credits, Hy3 + Hy4 preview | **Specific-client-only** |
| **Tencent International Lite** | **$7/mo**, 1,000 credits | **Specific-client-only** |
| **Baidu Qianfan Mini** | first-buy **¥4.9/mo** for 10M tokens; regular ¥9.9 | Plan API key / broad Agent+coding plan; check exact permitted automation scope before backend use |
| **Baidu Qianfan Lite** | first-buy **¥19.9/mo** for 42M tokens; regular ¥40; night usage from 2/10 consumption on selected models | same as above |
| **SenseNova global beta** | **$0**, 1,500 calls/model/5h, 20 API keys | Plan API/agent endpoint |
| **StepFun Entry** | **¥39/mo**, 1,300 credits, StepClaw desktop/cloud | Hosted app/agent membership, not general API |
| **MiniMax Plus** | starts around **$20/mo** | Specific-client Token Plan; separate PAYG API |
| **Z.ai ZCode Lite** | **$12.60/mo** promo | Coding-plan/client access; API separate |
| Moonshot/Kimi, ByteDance/Doubao, 01.AI/Yi | no new first-party price/release change verified today worth displacing the items above | — |

Sources: [DeepSeek API docs](https://api-docs.deepseek.com/), [Alibaba model pricing](https://www.alibabacloud.com/help/en/model-studio/model-pricing), [Alibaba Token Plan](https://www.alibabacloud.com/help/en/model-studio/token-plan-overview), [MiMo Token Plan](https://mimo.mi.com/docs/en-US/price/token-plan), [Tencent Token Plan](https://cloud.tencent.com/document/product/1823/130060), [Baidu Qianfan Token Plan](https://cloud.baidu.com/product/codingplan.html), [SenseNova Token Plan](https://www.sensenova.ai/token-plan), [StepFun membership](https://www.stepfun.com/subscription).

## Low-cost subscriptions

| Plan | Price | Access Type | Best use |
|---|---:|---|---|
| SenseNova beta | **$0** | Plan API/agent endpoint | free multimodal experimentation |
| **Command Code Go** | **$1/mo** | **agent/CLI-only — NO API** | cheap extra coding-agent bucket |
| Tencent Hy Lite | **¥28 ≈ $4.2/mo** | specific-client-only | Hy3/Hy4 coding/agents |
| MiMo Lite first purchase | **≈$5.28**, then $6 | specific-client-only | MiMo coding capacity, no 5h window |
| Tencent General Lite China | **¥39 ≈ $5.8/mo** | specific-client-only | broad Chinese model mix |
| Alibaba Token Plan Lite | **$6/mo** | specific-client-only | Qwen + multimodal/harness tools |
| Tencent International Lite | **$7/mo** | specific-client-only | international multi-model coding plan |
| **Command Code GOAT** | **$10/mo** | **agent/CLI + OpenAI/Anthropic-compatible API** | $70 monthly usage pool; $14/5h, $35/week |
| OpenCode Go | **$10/mo** | General provider/API | existing 27-model curated pool |

Command Code's distinction matters: **Go is the only plan without Provider API access**; GOAT and higher plans can call the OpenAI/Anthropic-compatible Provider API.

Sources: [Command Code Go](https://commandcode.ai/docs/plans/go), [Command Code GOAT](https://commandcode.ai/docs/plans/goat), [Command Code pricing](https://commandcode.ai/pricing).

## Best value today

**Existing OpenCode Go users:** test **Omen Alpha** first because its $100 model-specific pool is unusually generous, while **MiMo-V2.5** remains the maximum-volume non-training Go model at about 30,100 typical requests/5h. Muse Spark 1.3 Contributor stretches farther still but should not receive code you are unwilling to contribute to training.

**Cheapest paid DeepSeek Flash:** OpenRouter/OpenInference at $0.05/$0.16 wins raw price. **Azure DeepSeek Flash is unexpectedly competitive** at $0.19/$0.51 and is cheaper than DeepSeek direct off-peak for uncached input/output; direct DeepSeek still wins cache-hit pricing at $0.007/M.

**Qwen:** Alibaba direct is the clean price winner for Qwen3.8 Max in Virginia/Frankfurt/Tokyo at $1.65/$4.951 and Qwen3.8 Flash in most global regions at $0.113/$0.382.

**GPT-6 Astra:** existing ChatGPT Business users should wait for the announced rollout in the coming days rather than buy access solely for Astra. For API use, Azure Global Standard and OpenAI direct are tied at $10/$50; Azure U.S. Data Zone costs about 10% more in exchange for Azure's data-zone/enterprise controls.

## Community signal

Reddit is useful as an early-warning system, not the authority. Today the strongest signal is **Muse Spark 1.3 free-route capacity/region friction**: users report free-limit exhaustion, empty responses on some Go routes, and country restrictions. OpenCode's official documentation independently confirms Meta geographic restrictions and the training tradeoff; the exact reliability/rate-limit reports remain community-only.
