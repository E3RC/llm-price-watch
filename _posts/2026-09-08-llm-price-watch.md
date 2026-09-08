---
layout: post
title: "LLM Price Watch — September 8, 2026"
date: 2026-09-08 07:32:00 -0400
summary: "Vercel's GLM-5.3 50% promotion ends today, Tencent Cloud discounts GLM-5.3-Flash through September 10, NVIDIA exposes free DeepSeek/Kimi/StepFun development endpoints, while OpenCode Go and Zen remain stable."
---

## 🚨 Top changes today

| Change | Why it matters |
|---|---|
| **Vercel GLM-5.3 is 50% off through today** | Vercel AI Gateway shows **$0.70 input / $2.20 output per 1M** through **September 8**; the provider table says the promotion ends today. |
| **Tencent Cloud GLM-5.3-Flash is 50% off through Sep. 10** | Tencent International says GLM-5.3-Flash usage is billed at half list price through **23:59:59 Beijing time Sep. 10**. With list at $0.15/$0.50, effective promo pricing is **$0.075/$0.25 per 1M**. |
| **NVIDIA Build has useful $0 development endpoints** | Current NIM pages expose free endpoints for **DeepSeek V4 Flash 0731**, **DeepSeek V4 Pro 0813**, **Kimi K3**, and **Step-3.7-Flash**. These are development/trial capacity, not guaranteed unlimited production service. |
| **Z.ai has a strong 5-day new-user trial** | New Z.ai/BigModel users connecting through ZCode can receive **3M GLM-5.3 + 5M GLM-5.3-Flash tokens per day for 5 days**. |
| **OpenCode Go remains 27 models** | No new Go model ID today; **GLM-5.3-Flash still carries the 2× usage promotion**. |
| **OpenCode Zen remains six documented free routes** | Muse Spark 1.3 Contributor Free remains; Muse 1.2 Contributor Free is still absent from the current list. |
| **OpenRouter MiniMax free pages still say Free** | Despite community reports that MiniMax free capacity disappeared from some UI/results, OpenRouter's first-party M3 and M2.7 free pages still explicitly show **$0 today**. Treat availability/rate limits as potentially intermittent. |
| **No new major frontier model launched this morning** | The market movement today is mostly promotions, free endpoints, and cloud-provider price competition rather than a new flagship release. |

## OpenCode Go

OpenCode Go remains **$10/month**, with **$12 per 5 hours, $30/week, and $60/month** of included model-value limits. The current lineup remains 27 models.

| Model | Input → output / 1M | Est. req/5h | Modality / privacy | Change |
|---|---:|---:|---|---|
| Grok 4.6 | $2 → $6* | 169 | text/agent · 30d | — |
| GPT-5.6 Luna | $0.20 → $1.20* | 2,050 | text+vision · 30d | — |
| **GLM-5.3-Flash** | **$0.15 → $0.50** | 1,580 base | multimodal · ZDR | **2× Go promo** |
| GLM-5.3 | $1.40 → $4.40 | 220 | agent · ZDR | — |
| GLM-5.2 | $1.40 → $4.40 | 880 | agent · ZDR | — |
| GLM-5.1 | $1.40 → $4.40 | 880 | agent · ZDR | — |
| Kimi K3 | $3 → $15 | 110 | multimodal · ZDR | — |
| Kimi K2.7 Code | $0.95 → $4 | 1,350 | image+text coding · ZDR | — |
| Kimi K2.6 | $0.95 → $4 | 1,150 | multimodal · ZDR | — |
| LongCat-2.0 | $0.30 → $1.20 | 11,400 | agent · ZDR | — |
| **MiMo-V2.5** | **$0.14 → $0.28** | **30,100** | multimodal · ZDR | volume leader |
| MiMo-V2.5-Pro | $0.435 → $0.87 | 3,250 | multimodal · ZDR | — |
| MiniMax M3 | $0.30 → $1.20 | 3,200 | multimodal · ZDR | — |
| MiniMax M2.7 | $0.30 → $1.20 | 3,400 | agent · ZDR | — |
| Muse Spark 1.3 Contributor | $0.10 → $0.20 | 45,300 | multimodal · **training permitted** | — |
| Muse Spark 1.2 Contributor | $0.10 → $0.20 | 45,300 | agent · **training permitted** | — |
| Qwen3.8 Max | $2 → $6 | 160 | multimodal · ZDR | — |
| Qwen3.8 Flash | $0.15 → $0.47 | 5,400 | text/image/video · ZDR | — |
| Qwen3.7 Max | $2.50 → $7.50 | 170 | agent · ZDR | — |
| Qwen3.7 Plus | $0.40 → $1.60* | 4,300 | multimodal · ZDR | — |
| Qwen3.6 Plus | $0.50 → $3* | 3,300 | agent · ZDR | — |
| DeepSeek V4 Pro | $0.66 → $1.98 off-peak | 1,050 | agent · **ZDR through Sep. 30** | — |
| DeepSeek V4 Flash | $0.22 → $0.66 off-peak | 7,600 | coding · **ZDR through Sep. 30** | — |
| DS V4 Flash Vision Exp | $0.22 → $0.66 off-peak | 3,800 | vision · **ZDR through Sep. 30** | — |
| Hy4 Preview | $0.834 → $2.501 | 1,350 | agent · ZDR | — |
| Hy3 | $0.14 → $0.58 | 4,300 | agent · ZDR | — |
| Omen Alpha | $0.20 → $0.66 | 11,600 | image+text · ZDR | stealth |

\* Higher-context tiers differ. DeepSeek peak rates are higher than the off-peak rates shown.

Sources: [OpenCode Go docs](https://dev.opencode.ai/docs/go/) · [Go landing page](https://dev.opencode.ai/go)

## OPENCODE FREE / PREVIEW DEALS

The current Zen page still documents exactly **six free routes**:

| Model / ID | Access Type | Cost | Important catch |
|---|---|---:|---|
| `big-pickle` | Zen provider API | **$0** | stealth; free-period data may improve model |
| `mimo-v2.5-free` | Zen provider API | **$0** | limited-time |
| `ling-3.0-flash-fin-free` | Zen provider API | **$0** | limited-time |
| `nemotron-3-ultra-free` | Zen provider API | **$0** | NVIDIA trial/logging terms |
| `nemotron-3.5-lightning-free` | Zen provider API | **$0** | NVIDIA trial/logging terms |
| `muse-spark-1.3-contributor-free` | Zen provider API | **$0** | **Meta training permitted** |
| Muse Spark 1.2 Contributor Free | former route | — | not on current documented list |
| Ox Alpha | ended preview | — | identified as GLM-5.3-Flash |
| Hy3 Free | former route | — | no longer documented |

Source: [OpenCode Zen pricing/privacy](https://dev.opencode.ai/docs/zen)

## OPENROUTER DEALS

| Route | Access Type | Current price | Why it matters |
|---|---|---:|---|
| `openrouter/free` | OpenAI-compatible API/router | **$0** | capability-aware rotating free pool |
| `openrouter/pareto-code` | OpenAI/Anthropic-compatible API/router | **$0** | 13 coding models, **2M context** |
| **MiniMax M3 Free** | General API | **$0 page price** | **1M context**, text/image/video; free endpoints are rate-limited |
| **MiniMax M2.7 Free** | General API | **$0 page price** | 205K context, agent/productivity focus |
| Dots3 Note Preview | General API | **$0 through Sep. 30** | 512K, vision + tools |
| Ling 3.0 Flash / Sante free variants | General API | **$0** | 262K-class free routes |
| **DeepSeek V4 Flash 0731 — OpenInference** | General API | **$0.05 / $0.16; cache $0.013** | cheapest named provider on the current provider table |
| DeepSeek V4 Flash 0731 — DeepInfra | General API | **$0.06 / $0.18** | faster named-provider alternative |
| DeepSeek V4 Flash 0731 — Baidu | General API | **$0.14 / $0.28** | current Baidu route |
| DeepSeek V4 Flash 0731 — DeepSeek direct via OR | General API | **$0.22 / $0.66; cache $0.007** | first-party provider route |

Community reports today say MiniMax free routes disappeared for some users, but OpenRouter's own M3 and M2.7 free pages still explicitly say Free. That is a useful warning about **availability**, not enough evidence to mark the endpoints expired.

Sources: [MiniMax M3 Free](https://openrouter.ai/minimax/minimax-m3:free) · [MiniMax M2.7 Free](https://openrouter.ai/minimax/minimax-m2.7:free) · [Pareto Code](https://openrouter.ai/openrouter/pareto-code) · [DeepSeek V4 Flash 0731](https://openrouter.ai/deepseek/deepseek-v4-flash-0731)

## FREE ACCESS OUTSIDE OPENCODE / OPENROUTER

| Offer | Access Type | Cost | Notes |
|---|---|---:|---|
| **NVIDIA NIM DeepSeek V4 Flash 0731** | development API endpoint | **$0 trial endpoint** | NVIDIA Build currently says Free Endpoint Available |
| **NVIDIA NIM DeepSeek V4 Pro 0813** | development API endpoint | **$0 trial endpoint** | Free Endpoint Available |
| **NVIDIA NIM Kimi K3** | development API endpoint | **$0 trial endpoint** | current NVIDIA Build free endpoint |
| **NVIDIA NIM Step-3.7-Flash** | development API endpoint | **$0 trial endpoint** | 262K, text+image coding/agent model |
| **Z.ai GLM trial** | coding/client trial | **$0 for 5 days** | 3M GLM-5.3 + 5M GLM-5.3-Flash tokens/day for eligible new users |
| **SenseNova Token Plan public beta** | plan API / agent endpoint | **¥0** | 60,000 credits / 5h, up to 20 API keys |
| **Vercel MiniMax M2.7 Free** | OpenAI/Anthropic-compatible API gateway | **$0** | dedicated free model ID remains live |
| Command Code Laguna S 2.1 | Go = agent/CLI-only | **$0 model usage** | while capacity lasts |
| Command Code Ling 3.0 Flash | Go = agent/CLI-only | **$0 model usage** | current free model route |
| Command Code LongCat 2.0 | Go = agent/CLI-only | **$0 model usage** | while offer lasts |

Sources: [NVIDIA DeepSeek Flash](https://build.nvidia.com/deepseek-ai/deepseek-v4-flash-0731) · [NVIDIA DeepSeek Pro](https://build.nvidia.com/deepseek-ai/deepseek-v4-pro-0813) · [NVIDIA Kimi](https://build.nvidia.com/moonshotai) · [NVIDIA StepFun](https://build.nvidia.com/stepfun-ai/step-3.7-flash) · [ZCode/Z.ai setup](https://zcode.z.ai/en/docs/configuration) · [SenseNova Token Plan](https://www.sensenova.cn/token-plan)

## AZURE AI FOUNDRY COMPARISON

Azure remains most attractive when **Microsoft-hosted governance/privacy** matters more than raw token cost.

| Model | Azure offer | Azure price / billing | Lower-cost comparison | Take |
|---|---|---:|---|---|
| **DeepSeek V4 Flash** | **Azure Direct serverless** | **$0.19 in / $0.51 out / $0.028 cache per M** | OpenRouter/OpenInference $0.05/$0.16; Alibaba Global $0.138/$0.275 | good enterprise price, not raw-price winner |
| **DeepSeek V4 Pro** | Azure Direct serverless | **$1.74 / $3.48 / $0.145 cache** | DeepSeek direct off-peak $0.66/$1.98 | large Azure premium |
| Kimi K2.7 Code / Kimi family | partner/Foundry options | partner PAYG/PTU varies | Moonshot/direct market routes | check whether deployment is Azure Direct vs partner |
| MiniMax family | Fireworks/partner options | partner PAYG/PTU | OpenRouter M3/M2.7 free pages today | not cheapest for experimentation |
| GLM family | Fireworks/partner options | partner PAYG/PTU | Tencent/Vercel promos today | route/privacy matters |
| Qwen open weights | managed deployment | GPU/compute | Alibaba serverless API | **not token-price equivalent** |
| Managed A100/H100/H200/MI300 | Azure managed compute | public table currently `$-` | dedicated GPU alternatives | calculator/quote required |

For **models sold by Azure**, Microsoft states prompts/completions are not available to OpenAI or other model providers and are not used to train foundation models without permission. That provider-isolation boundary can justify higher prices for proprietary code, Entra/RBAC, private networking, regional controls, and consolidated procurement.

Managed Compute and provisioned throughput remain separate economics. The public pricing page still shows `$-` for A100/H100/H200/MI300 managed compute rows, so no fake $/M-token comparison is made here.

No fresh public Azure Direct listing surfaced today for MiMo/Xiaomi, Hunyuan/Tencent, Baidu/ERNIE, Doubao/ByteDance, StepFun, SenseNova, or Yi; that is a catalog-scan result, not a claim that those models can never be deployed through Azure/partners.

Sources: [Azure Foundry model pricing](https://azure.microsoft.com/en-us/pricing/details/ai-foundry-models/microsoft/) · [Azure data/privacy](https://learn.microsoft.com/en-us/azure/foundry/responsible-ai/openai/data-privacy) · [DeepSeek V4 pricing announcement](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/introducing-deepseek-v4-flash-and-v4-pro-in-microsoft-foundry/4515174/)

## DIRECT CHINESE API / PLAN SCAN

| Vendor | Current first-party finding | Access Type |
|---|---|---|
| **DeepSeek** | V4 Flash off-peak cache hit **$0.007**, cache miss **$0.22**, output **$0.66**; peak is 2× | **General API** |
| **Alibaba/Qwen** | Qwen3.8 Flash Global **$0.113/$0.382**; Qwen3.8 Max Global **$1.65/$4.951** | **General API** |
| **Alibaba-hosted DeepSeek** | V4 Flash Global **$0.138/$0.275**; 0731 idle **$0.212/$0.636** | **General API** |
| **Moonshot/Kimi** | Kimi K3 **$3 uncached input / $0.30 cached / $15 output** | **General API** |
| **Xiaomi/MiMo** | MiMo-V2.5 **$0.14 cache-miss input / $0.0028 cache-hit / $0.28 output** | **General API** |
| Xiaomi MiMo Lite | **$6 monthly list; $5.28/mo annual equivalent** | **specific-client Token Plan** |
| **Tencent Cloud** | GLM-5.3-Flash list **$0.15/$0.50**, but **50% billing through Sep. 10**; Hy3 $0.132/$0.528 | **General API** |
| Tencent Hy Lite | **¥28/mo** | **specific-client-only** |
| **Z.ai/GLM** | new-user 5-day GLM trial; overseas Coding Lite currently advertises **$12.60/mo promotional** | API + coding-plan access, depending endpoint |
| **SenseNova** | public-beta Token Plan **¥0**, 60,000 credits/5h, up to 20 keys | **Plan API / agent endpoint** |
| **StepFun** | Starter membership **¥39/mo**; Step Plan/API products are separate | **hosted/specific-client membership** |
| Baidu/Qianfan | legacy Coding Plan stopped renewals June 25 and migrated toward Token Plan | **plan/tool access** |
| ByteDance/Doubao | no fresh first-party coding/API discount strong enough to add today | API / hosted plans |
| 01.AI/Yi | no fresh first-party hosted-API deal surfaced today | open weights/self-host focus |

Alibaba's Personal Token Plan remains a classification trap: Lite is **$8 list / $6 limited-time**, but the terms explicitly restrict it to interactive coding/agent tools and prohibit automation scripts, custom application backends, and non-interactive batch calls. It is **not general production API access**.

Sources: [DeepSeek pricing](https://api-docs.deepseek.com/quick_start/pricing/) · [Alibaba model pricing](https://www.alibabacloud.com/help/en/model-studio/model-pricing) · [Alibaba Personal Token Plan](https://docs.modelstudio.console.alibabacloud.com/en/model-studio/token-plan-personal-overview) · [Kimi K3 announcement](https://forum.moonshot.ai/t/kimi-k3-is-here-our-most-capable-model/480) · [Xiaomi MiMo](https://platform.xiaomimimo.com/) · [Tencent International model pricing](https://intl.cloud.tencent.com/document/product/1300/78937) · [StepFun membership](https://www.stepfun.com/subscription)

## LOW-COST SUBSCRIPTIONS ($3-$10 WATCH)

| Plan | Price | Access Type | Why it matters |
|---|---:|---|---|
| **Command Code Go** | **$1/mo** | **agent/CLI-only — NO Provider API** | $10 credits; Laguna/Ling/LongCat currently $0 model usage |
| Tencent Hy Lite | **¥28/mo** | specific-client-only | inexpensive Hunyuan coding bucket |
| StepFun Starter | **¥39/mo** | hosted/specific-client | StepClaw + 1,300 credits |
| **Xiaomi MiMo Lite** | **$6/mo list; $5.28 annual equivalent** | specific-client Token Plan | 49.2B annual credits, no 5h/weekly cap advertised |
| **Alibaba Token Plan Lite** | **$8 list / $6 promo** | specific-client/tool-oriented plan API | 2,500 credits/7d; interactive coding/agent tools only |
| **Command Code GOAT** | **$10/mo** | **agent/CLI + OpenAI/Anthropic-compatible Provider API** | $70 monthly credits |
| **OpenCode Go** | **$10/mo** | provider/API for coding agents | curated 27-model pool, $60 monthly nominal value cap |

Command Code's distinction remains explicit: **Go is the only plan without Provider API access**. GOAT, Pro, Max, Team, and Provider can use its OpenAI/Anthropic-compatible Provider API. Current Command Code free/deal models include Laguna S 2.1, Ling 3.0 Flash, and LongCat 2.0; MiniMax M3 gets a 2× usage multiplier and MiMo V2.5 is heavily discounted.

Sources: [Command Code pricing/limits](https://commandcode.ai/docs/resources/pricing-limits) · [Command Code Provider API](https://commandcode.ai/docs/provider)

## NEW MODELS / COMMUNITY WATCH

No major same-day flagship release surfaced for **September 8**. The newest major releases in the current coding market remain GPT-6 Astra / Astra Pro, GLM-5.3-Flash, Ling 3.0 Flash Sante, Qwen3.8 Max-0902, Muse Spark 1.3, and Gemini 3.8 Flash from the prior week.

**Omen Alpha** remains an unidentified paid OpenCode route. Community probes continue to speculate about a GLM/Zhipu relationship and possible future free IDs, but OpenCode has confirmed neither the underlying identity nor a free endpoint. Treat that as community investigation, not a deal.

A separate Reddit signal today claimed the MiniMax M3/M2.7 free tier vanished from OpenRouter for some users. First-party OpenRouter pages still report both free routes at $0, so the correct status is **officially listed free, potentially intermittent/rate-limited** rather than expired.

## 🏆 BEST VALUE TODAY

1. **Use the expiring Vercel GLM-5.3 50% route today if you need GLM-5.3:** $0.70/$2.20 ends September 8.
2. **For GLM-5.3-Flash paid API traffic, Tencent's 50%-billing promotion is excellent through Sep. 10:** effective $0.075/$0.25 against the $0.15/$0.50 list rate.
3. **Add NVIDIA Build as a no-cost development fallback:** DeepSeek V4 Flash/Pro, Kimi K3, and Step-3.7-Flash all have free developer endpoints currently exposed.
4. **For cheap paid DeepSeek, OpenRouter/OpenInference remains excellent at $0.05/$0.16**, while DeepSeek direct retains the advantage of first-party routing and extremely cheap $0.007 cache hits off-peak.
5. **For proprietary/company code, OpenCode Go ZDR routes and Azure Direct remain the safer value story** than chasing every marketplace discount; Azure is especially defensible when provider isolation, Entra/RBAC, private networking, or procurement consolidation matters.
6. **No new $20-class subscription looks necessary today.** The strongest incremental value remains in $0 development endpoints, short launch promotions, and the $1–$10 coding-plan tier.
