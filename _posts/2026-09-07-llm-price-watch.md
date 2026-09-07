---
layout: post
title: "LLM Price Watch — September 7, 2026"
date: 2026-09-07 07:32:00 -0400
summary: "Vercel MiniMax M3 free access ends while M2.7 stays free, OpenRouter M3 remains free, DeepSeek provider pricing is corrected, and Alibaba's current $6 Token Plan is clarified."
---

## 🚨 Top changes today

| Change | Why it matters |
|---|---|
| **Vercel MiniMax M3 is no longer free** | The live Vercel AI Gateway page now starts around **$0.26 input / $1.02 output per 1M**. The prior free promotion has ended. |
| **Vercel MiniMax M2.7 Free is still live** | `minimax/minimax-m2.7-free` remains a **$0** OpenAI/Anthropic-compatible route with roughly 197K context/output and a software-engineering focus. |
| **OpenRouter MiniMax M3 Free is still live** | The explicit `minimax/minimax-m3:free` route remains **$0**, 1M-context and multimodal even though Vercel's M3 promo ended. |
| **DeepSeek provider-price correction** | OpenRouter's overall V4 Flash headline is as low as **$0.045/$0.09**, OpenInference can be pinned at **$0.05/$0.16**, while Baidu's current pinned route is **$0.14/$0.28** — yesterday's ~$0.05/$0.10 Baidu figure is no longer current. |
| **Alibaba Token Plan Lite is $6 promotional, not ¥39** | Alibaba's current Personal Token Plan Lite is **$8 list / $6 promotional**, 2,500 credits per 7-day window, Singapore region. It is restricted to interactive coding/agent tools, not arbitrary production backends. |
| **OpenCode Go remains 27 models** | No new Go model ID today. GLM-5.3-Flash still carries the temporary **2× usage** promotion. |
| **OpenCode Zen remains six documented free routes** | Muse Spark 1.3 Contributor Free remains; Muse 1.2 Contributor Free is no longer on the current list. |

## OpenCode Go

OpenCode Go remains **$10/month** with overall included usage pools of **$12 per 5 hours, $30/week and $60/month**. The current lineup remains 27 models.

| Model | $/M input → output | Est. req/5h | Modality / privacy | Change |
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
| Muse Spark 1.3 Contributor | $0.10 → $0.20 | **45,300** | multimodal · **training permitted** | — |
| Muse Spark 1.2 Contributor | $0.10 → $0.20 | 45,300 | agent · **training permitted** | — |
| Qwen3.8 Max | $2 → $6 | 160 | multimodal · ZDR | — |
| Qwen3.8 Flash | $0.15 → $0.47 | 5,400 | text/image/video · ZDR | — |
| Qwen3.7 Max | $2.50 → $7.50 | 170 | agent · ZDR | — |
| Qwen3.7 Plus | $0.40 → $1.60* | 4,300 | multimodal · ZDR | — |
| Qwen3.6 Plus | $0.50 → $3* | 3,300 | agent · ZDR | — |
| DeepSeek V4 Pro | $0.66 → $1.98 off-peak | 1,050 | agent · ZDR through Sep. 30 | — |
| DeepSeek V4 Flash | $0.22 → $0.66 off-peak | 7,600 | coding · ZDR through Sep. 30 | — |
| DS V4 Flash Vision Exp | $0.22 → $0.66 off-peak | 3,800 | vision · ZDR through Sep. 30 | — |
| Hy4 Preview | $0.834 → $2.501 | 1,350 | agent · ZDR | — |
| Hy3 | $0.14 → $0.58 | 4,300 | agent · ZDR | — |
| Omen Alpha | $0.20 → $0.66 | 11,600 | image+text · ZDR | stealth |

\* Higher-context tiers differ. DeepSeek peak rates are higher than the off-peak values shown.

Sources: [OpenCode Go docs](https://dev.opencode.ai/docs/go/) · [Go landing page](https://dev.opencode.ai/go)

## OPENCODE FREE / PREVIEW DEALS

The current Zen page documents **six free routes**:

| Model / ID | Access Type | Cost | Context/modality | Important catch |
|---|---|---:|---|---|
| `big-pickle` | Zen provider API | **$0** | stealth | free-period data may improve model |
| `mimo-v2.5-free` | Zen provider API | **$0** | multimodal | limited-time |
| `ling-3.0-flash-fin-free` | Zen provider API | **$0** | coding/text | limited-time |
| `nemotron-3-ultra-free` | Zen provider API | **$0** | text/agent | NVIDIA trial/logging terms |
| `nemotron-3.5-lightning-free` | Zen provider API | **$0** | text/agent | NVIDIA trial/logging terms |
| `muse-spark-1.3-contributor-free` | Zen provider API | **$0** | multimodal/agent | **Meta training permitted** |
| Muse Spark 1.2 Contributor Free | former route | — | — | no longer on current documented list |
| Ox Alpha | ended preview | — | — | identified as GLM-5.3-Flash |
| Hy3 Free | former route | — | — | no longer documented |

Source: [OpenCode Zen pricing/privacy](https://dev.opencode.ai/docs/zen)

## OPENROUTER DEALS

| Route | Access Type | Current price | Why it matters |
|---|---|---:|---|
| `openrouter/free` | OpenAI-compatible API/router | **$0** | 24-model capability-aware free pool; 200K router context |
| `openrouter/pareto-code` | OpenAI/Anthropic-compatible API/router | **$0** | 13 coding models, **2M context** |
| **MiniMax M3 Free** | General API | **$0** | **1M context**, text/image/video, tools |
| DeepSeek V4 Flash 0731 headline | General API/router | **from $0.045 → $0.09/M** | cheapest aggregate headline currently shown |
| DeepSeek V4 Flash — OpenInference pinned | General API | **$0.05 → $0.16/M** | stable named provider option |
| DeepSeek V4 Flash — Baidu pinned | General API | **$0.14 → $0.28/M** | current Baidu provider price; prior lower figure is stale |

Sources: [Free Router](https://openrouter.ai/openrouter/free/providers) · [Pareto Code](https://openrouter.ai/openrouter/pareto-code) · [MiniMax M3 Free](https://openrouter.ai/minimax/minimax-m3:free) · [DeepSeek V4 Flash](https://openrouter.ai/deepseek/deepseek-v4-flash-0731) · [OpenInference](https://openrouter.ai/provider/open-inference) · [Baidu](https://openrouter.ai/provider/baidu)

## FREE ACCESS OUTSIDE OPENCODE / OPENROUTER

| Offer | Access Type | Cost | Status |
|---|---|---:|---|
| **Vercel MiniMax M2.7 Free** | OpenAI/Anthropic-compatible API gateway | **$0** | live today; ~197K context/output |
| Vercel MiniMax M3 | API gateway | **paid: from ~$0.26/$1.02** | **free promotion ended** |
| Command Code Laguna S 2.1 | Go agent/CLI-only; API on eligible Provider plans | **$0 model usage** | while capacity lasts |
| Command Code Ling 3.0 Flash | Go agent/CLI-only; API on eligible Provider plans | **$0 model usage** | promotion |
| Command Code LongCat 2.0 | Go agent/CLI-only; API on eligible Provider plans | **$0 model usage** | while promotion lasts |

Sources: [Vercel MiniMax M3](https://vercel.com/ai-gateway/models/minimax-m3) · [Vercel MiniMax M2.7 Free](https://vercel.com/ai-gateway/models/minimax-m2.7-free) · [Command Code pricing](https://commandcode.ai/docs/resources/pricing-limits)

## AZURE AI FOUNDRY COMPARISON

Azure remains most interesting where **Microsoft-hosted governance/privacy** matters rather than raw token price.

| Model | Azure offer | Azure price / billing | Lower-cost comparison | Take |
|---|---|---:|---|---|
| **DeepSeek V4 Flash** | **Azure Direct serverless, Global** | **$0.19 in / $0.51 out / $0.028 cache per M** | DeepSeek direct off-peak $0.22/$0.66; OpenRouter from $0.045/$0.09 | Azure beats direct uncached off-peak, but not aggregators |
| **DeepSeek V4 Pro** | Azure Direct serverless | **$1.74 / $3.48 / $0.145 cache** | DeepSeek direct off-peak $0.66/$1.98 | substantial Azure premium |
| Kimi K2.7 Code | **Fireworks on Foundry** | partner PAYG/PTU | market routes around $0.95/$4 | partner privacy boundary differs |
| MiniMax M3 | **Fireworks on Foundry** | partner PAYG/PTU | OpenRouter free today | Azure route is procurement/governance, not cheapest |
| GLM-5 | **Fireworks on Foundry** | partner PAYG/PTU | newer GLM-5.3-Flash available elsewhere | older family route |
| Qwen3.8-27B | open-weight catalog / managed deployment | GPU/compute | Alibaba serverless API | **not token-price equivalent** |
| Yi 1.5 6B | open-weight catalog artifact | managed deployment | self-host/open weights | not a current hosted Yi API bargain |

**Azure Direct privacy:** Microsoft states prompts, outputs and training data for Azure Direct models are not shared with the original model provider and are not used to train foundation models without permission. That can justify a higher price for proprietary code, Entra/RBAC, private networking, regional controls and consolidated procurement.

**Fireworks on Foundry is different:** Fireworks models run on partner infrastructure; Microsoft states data leaves Microsoft systems and normal Foundry data-residency documentation does not apply.

Current public Foundry Managed Compute/PTU pricing still exposes `$-`/calculator-required rows for many relevant deployments. Do not compare those GPU/PTU commitments directly with serverless $/M token pricing. Older DeepSeek PTU rows show a 100-PTU minimum, but current V4 provisioned prices are not reliably published in the static table.

No current public catalog hit surfaced in today's scan for a Microsoft-hosted Direct offering of MiMo/Xiaomi, Hunyuan/Tencent, Baidu/ERNIE, Doubao/ByteDance, StepFun or SenseNova. Catalog availability changes quickly, so that is a scan result rather than a claim that deployment is impossible.

Sources: [Azure DeepSeek V4 Flash](https://ai.azure.com/catalog/models/DeepSeek-V4-Flash-0731) · [Azure DeepSeek pricing](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/introducing-deepseek-v4-flash-and-v4-pro-in-microsoft-foundry/4515174/) · [Azure Direct privacy](https://learn.microsoft.com/en-us/azure/foundry/responsible-ai/openai/data-privacy) · [Kimi K2.7 Code / Fireworks](https://ai.azure.com/catalog/models/FW-Kimi-K2.7-Code) · [MiniMax M3 / Fireworks](https://ai.azure.com/catalog/models/FW-MiniMax-M3) · [GLM-5 / Fireworks](https://ai.azure.com/catalog/models/FW-GLM-5) · [Qwen3.8-27B](https://ai.azure.com/catalog/models/qwen--qwen3.8-27b)

## DIRECT CHINESE API / PLAN SCAN

At the September 7 reference rate, **¥1 ≈ $0.1490**.

| Vendor | Current verified finding | Access Type |
|---|---|---|
| **DeepSeek** | V4 Flash/Vision off-peak: cache hit **$0.007**, cache miss **$0.22**, output **$0.66**; peak is higher | **General API** |
| **Alibaba/Qwen** | Qwen3.8 Flash Global regions **$0.113/$0.382**; Singapore **$0.15/$0.47**; Qwen3.8 Max Global **$1.65/$4.951** | **General API** |
| **Alibaba Token Plan Lite** | **$8 list / $6 promo**, 2,500 credits per 7-day window, Singapore | **specific-client/tool-oriented plan API** |
| **Tencent Hy Lite** | **¥28/mo (~$4.17)** | specific-client-only |
| **Tencent International Lite** | **$7/mo**, 1,000 credits | specific-client-only |
| Moonshot/Kimi | no material new first-party price change surfaced today | General API |
| Zhipu/GLM | no new price change beyond current GLM-5.3-Flash launch/promotions | General API |
| MiniMax | M3 direct remains paid; today's standout is free access through OpenRouter | General API / client plans |
| Xiaomi/MiMo | no newly verified first-party price change surfaced today | API / client plans |
| Baidu/Qianfan | no new direct plan price verified today; OpenRouter Baidu route repriced to $0.14/$0.28 | API / plans |
| ByteDance/Doubao | no newly verified coding-plan change surfaced today | API / plans |
| StepFun | no new verified pricing/release today | API / plans |
| SenseNova | no new verified pricing change surfaced today | Plan API / agent endpoint |
| 01.AI/Yi | no current first-party hosted-API deal surfaced today | open weights/self-host |

Alibaba's Personal Token Plan deserves a classification warning: it supplies an API-shaped key and supports OpenAI/Anthropic-compatible coding tools, but its current terms prohibit automation scripts, custom application backends and non-interactive batch workloads. It is therefore **not general production API access**.

Sources: [DeepSeek pricing](https://api-docs.deepseek.com/quick_start/pricing/) · [Alibaba Model Studio pricing](https://www.alibabacloud.com/help/en/model-studio/model-pricing) · [Alibaba Token Plan](https://www.alibabacloud.com/help/en/model-studio/token-plan-overview) · [Alibaba personal-plan restrictions](https://docs.modelstudio.console.alibabacloud.com/en/model-studio/token-plan-personal-overview) · [Tencent international Token Plan](https://intl.cloud.tencent.com/document/product/1300/81315)

## LOW-COST SUBSCRIPTIONS ($3-$10)

| Plan | Price | Access Type | Notes |
|---|---:|---|---|
| **Command Code Go** | **$1/mo** | **agent/CLI-only — NO Provider API** | $10 credits; several $0 model routes |
| Tencent Hy Lite | **¥28 (~$4.17)/mo** | specific-client-only | Hunyuan-focused coding plan |
| **Alibaba Token Plan Lite** | **$6 promo** | specific-client/tool-oriented | 2,500 credits / 7 days; Singapore; no custom backends/batch |
| Tencent International Lite | **$7/mo** | specific-client-only | 1,000 credits |
| **Command Code GOAT** | **$10/mo** | **agent/CLI + OpenAI/Anthropic-compatible Provider API** | $70 monthly credits |
| OpenCode Go | **$10/mo** | provider/API for coding agents | $60 nominal monthly usage pool |

Command Code remains an important access-type distinction: **Go is the only plan here without Provider API access**; GOAT and higher eligible plans expose OpenAI/Anthropic-compatible Provider API endpoints.

Sources: [Command Code pricing](https://commandcode.ai/docs/resources/pricing-limits) · [Command Code Provider API](https://commandcode.ai/docs/provider) · [Alibaba Token Plan](https://www.alibabacloud.com/help/en/model-studio/token-plan-overview)

## NEW MODELS / COMMUNITY WATCH

No major same-day frontier model launch was verified as of the September 7 morning scan. The newest material releases in this market watch remain GLM-5.3-Flash (September 4) and Muse Spark 1.3 (September 2).

**Omen Alpha remains unidentified.** Reddit tokenizer/vision probing continues to suggest a possible GLM/Zhipu-family relationship, and a possible `OMEN-ALPHA-free:global` breadcrumb has circulated, but OpenCode has not confirmed either the underlying model or a free endpoint. Treat both as community speculation, not a deal.

## 🏆 BEST VALUE TODAY

**Best free coding API to add today:** Vercel's explicit **MiniMax M2.7 Free** plus OpenRouter's **MiniMax M3 Free** and **Pareto Code**. The Vercel M3 free window is over, so remove that route from any “free” assumptions.

**Best cheap paid DeepSeek:** OpenRouter's aggregate V4 Flash routing currently advertises as low as **$0.045/$0.09/M**. For a named/pinned provider, OpenInference is **$0.05/$0.16**. DeepSeek direct remains attractive for first-party routing and exceptionally cheap cache-hit tokens, while Azure Direct is the enterprise/governance choice.

**Best $3-$10 new subscription worth considering:** Alibaba's corrected **$6 Token Plan Lite** is interesting for interactive coding agents, but it is not a production backend API and it carries Singapore/cross-border handling considerations. It should be compared with OpenCode Go as a tool-capacity subscription, not with raw serverless API pricing.

**For private/proprietary work:** Azure Direct DeepSeek and OpenCode Go's ZDR routes remain more strategically useful than chasing the absolute cheapest marketplace endpoint.

### Primary sources

- [OpenCode Go](https://dev.opencode.ai/docs/go/)
- [OpenCode Zen](https://dev.opencode.ai/docs/zen)
- [OpenRouter Free Router](https://openrouter.ai/openrouter/free/providers)
- [OpenRouter DeepSeek V4 Flash](https://openrouter.ai/deepseek/deepseek-v4-flash-0731)
- [Vercel MiniMax M3](https://vercel.com/ai-gateway/models/minimax-m3)
- [Vercel MiniMax M2.7 Free](https://vercel.com/ai-gateway/models/minimax-m2.7-free)
- [Azure Foundry](https://ai.azure.com/catalog)
- [DeepSeek pricing](https://api-docs.deepseek.com/quick_start/pricing/)
- [Alibaba Model Studio](https://www.alibabacloud.com/help/en/model-studio/model-pricing)
- [Command Code](https://commandcode.ai/docs/resources/pricing-limits)
