---
layout: post
title: "LLM Price Watch — September 4, 2026"
date: 2026-09-04 08:56:00 -0400
summary: "GLM-5.3-Flash officially launches and reveals Ox Alpha, OpenCode Go reaches 27 models, Muse Spark 1.3 Contributor is free on Zen, and Azure DeepSeek pricing is compared with direct, Alibaba and OpenRouter routes."
---

## 🚨 Top changes today

| Change | Why it matters |
|---|---|
| **GLM-5.3-Flash officially launches today** | Z.ai confirms the old anonymous **Ox Alpha** preview was GLM-5.3-Flash. It is a 320B/18B-active native multimodal model, supports million-token-class context, and its weights are available under MIT. |
| **OpenCode Go is now 27 models** | **Muse Spark 1.3 Contributor** and stealth route **Omen Alpha** are now in the lineup. Omen gets about **11,600 estimated requests/5h** and is ZDR; Muse gets about **45,300/5h** but **permits training on prompts/completions**. |
| **🔥 Muse Spark 1.3 Contributor Free is live on OpenCode Zen** | `muse-spark-1.3-contributor-free` is $0. It is a limited-time Contributor route and should be treated as **non-private/test-code capacity**, because Contributor access permits training. |
| **GLM-5.3-Flash has a 2× Go usage promo** | OpenCode explicitly advertises 2× usage for a limited time. |
| **DeepSeek ZDR documentation is still stale** | OpenCode's current Go docs still say its DeepSeek ZDR agreement is valid only through **August 31, 2026**. September ZDR is not explicitly documented yet. |
| **OpenRouter Pareto Code is a standout $0 coding router** | `openrouter/pareto-code` is free, routes among **13 coding models**, and exposes a **2M context** window. |
| **Azure DeepSeek Flash is cheaper than DeepSeek direct off-peak on uncached tokens** | Azure Direct is **$0.19/$0.51/M** vs DeepSeek direct **$0.22/$0.66/M** off-peak. OpenRouter remains far cheaper at **$0.05/$0.16/M**. Alibaba Virginia is about **$0.149/$0.298/M** at today's FX rate. |
| **SenseNova free beta remains exceptional** | SenseNova's China/English public-beta page still shows **¥0/month and 60,000 credits/5h**, with multimodal models and up to 20 API keys. |

## OpenCode Go

OpenCode Go remains **$10/month**, with a provider/API key usable by OpenCode and other agents. Base overall limits remain **$12/5h, $30/week and $60/month**. The current advertised lineup is 27 models.

| Model | Input → output / M | Est. req/5h | Modality / privacy | Change |
|---|---:|---:|---|---|
| Grok 4.6 | $2 → $6* | 169 | text/agent · 30d | — |
| GPT-5.6 Luna | $0.20 → $1.20* | 2,050 | vision/text · 30d | — |
| **GLM-5.3-Flash** | **$0.15 → $0.50** | 1,580 base | **native multimodal/agent · ZDR** | **2× promo; official launch today** |
| GLM-5.3 | $1.40 → $4.40 | 220 | agent · ZDR | — |
| GLM-5.2 | $1.40 → $4.40 | 880 | agent · ZDR | — |
| GLM-5.1 | $1.40 → $4.40 | 880 | agent · ZDR | — |
| Kimi K3 | $3 → $15 | 110 | multimodal/agent · ZDR | — |
| Kimi K2.7 Code | $0.95 → $4 | 1,350 | image+text coding · ZDR | — |
| Kimi K2.6 | $0.95 → $4 | 1,150 | multimodal · ZDR | — |
| LongCat-2.0 | $0.30 → $1.20 | 11,400 | agent · ZDR | — |
| **MiMo-V2.5** | **$0.14 → $0.28** | **30,100** | multimodal · ZDR | volume leader |
| MiMo-V2.5-Pro | $0.435 → $0.87 | 3,250 | multimodal · ZDR | — |
| MiniMax M3 | $0.30 → $1.20 | 3,200 | multimodal/agent · ZDR | — |
| MiniMax M2.7 | $0.30 → $1.20 | 3,400 | agent · ZDR | — |
| **Muse Spark 1.3 Contributor** | **$0.10 → $0.20** | **45,300** | multimodal/agent · **TRAINING YES** | **NEW; limited regions** |
| Muse Spark 1.2 Contributor | $0.10 → $0.20 | 45,300 | agent · **TRAINING YES** | — |
| Qwen3.8 Max | $2 → $6 | 160 | multimodal · ZDR | — |
| Qwen3.8 Flash | $0.15 → $0.47 | 5,400 | text/image/video · ZDR | — |
| Qwen3.7 Max | $2.50 → $7.50 | 170 | agent · ZDR | — |
| Qwen3.7 Plus | $0.40 → $1.60* | 4,300 | multimodal · ZDR | — |
| Qwen3.6 Plus | $0.50 → $3* | 3,300 | agent · ZDR | — |
| DeepSeek V4 Pro | $0.66 → $1.98 off-peak | 1,050 | agent · **ZDR?** | stale Aug. 31 agreement |
| DeepSeek V4 Flash | $0.22 → $0.66 off-peak | 7,600 | coding · **ZDR?** | stale Aug. 31 agreement |
| DeepSeek V4 Flash Vision Exp | $0.22 → $0.66 off-peak | 3,800 | vision · **ZDR?** | stale Aug. 31 agreement |
| Hy4 Preview | $0.834 → $2.501 | 1,350 | agent · ZDR | — |
| Hy3 | $0.14 → $0.58 | 4,300 | agent · ZDR | — |
| **Omen Alpha** | **$0.20 → $0.66** | **11,600** | image+text agent · ZDR | **NEW stealth route** |

\* Higher-context tiers differ. DeepSeek peak rates are 2× the off-peak rates shown.

Sources: [OpenCode Go docs](https://dev.opencode.ai/docs/go/) · [OpenCode Go landing page](https://dev.opencode.ai/go)

## OPENCODE FREE / PREVIEW DEALS

The current documented Zen free list contains seven models. **Hy3 Free is no longer on the documented list.** Ox Alpha has ended as a preview and has now been identified as GLM-5.3-Flash.

| Model / ID | Access Type | Cost | Context / modality | Limits / privacy / status |
|---|---|---:|---|---|
| `mimo-v2.5-free` | Zen provider API | **$0** | ~1M / multimodal | limited-time; free-period data may improve model |
| `ling-3.0-flash-fin-free` | Zen provider API | **$0** | coding/text | limited-time; free-period data may improve model |
| `nemotron-3-ultra-free` | Zen provider API | **$0** | text/agent | limited-time NVIDIA trial logging |
| `nemotron-3.5-lightning-free` | Zen provider API | **$0** | text/agent | limited-time NVIDIA trial logging |
| `big-pickle` | Zen provider API | **$0** | stealth | limited-time; data may improve model |
| **`muse-spark-1.3-contributor-free`** | Zen provider API | **$0** | ~1M / multimodal agent | **NEW; training permitted; limited Meta regions** |
| `muse-spark-1.2-contributor-free` | Zen provider API | **$0** | agent | **training permitted; limited Meta regions** |
| Ox Alpha Free | preview route | ended | now identified | **became GLM-5.3-Flash** |
| Hy3 Free | former free route | ended/unlisted | — | **removed from current documented free list** |

Also active: **GPT-5.6 Sol is 50% off on Zen through September 18, 2026.**

Community signal: Reddit users are seeing very generous Muse Spark 1.3 Contributor Free usage, but also occasional 502s and some reports of rate limits. Those limits are **community-reported**, not a published entitlement.

Sources: [OpenCode Zen](https://dev.opencode.ai/docs/zen) · [Reddit community thread](https://www.reddit.com/r/opencode/comments/1w5ziqj/meta_muse_spark_13_is_free_on_opencode_zen/)

## OPENROUTER DEALS

| Route | Access Type | Current price | Why it matters |
|---|---|---:|---|
| `openrouter/free` | OpenAI-compatible API/router | **$0** | 24-model capability-aware free pool; 200K router context |
| **`openrouter/pareto-code`** | OpenAI/Anthropic-compatible API/router | **$0** | **13 coding models, 2M context**; High tier default, Nitro can favor speed |
| GLM-5.2 Free | General API | **$0** | 256K free route; tools + structured output |
| MiniMax M3 Free | General API | **$0** | **1M**, text/image/video, tools; rate-limited free endpoint |
| North Mini Code Free | General API | **$0** | 256K; purpose-built for coding-agent harnesses |
| Muse Spark 1.3 | General API | **$1.25 → $4.25/M** | Regular Meta route; 1M multimodal context |
| Muse Spark 1.3 Contributor | General API | **$0.10 → $0.20/M** | Cheap Contributor route; contributor/training tradeoff applies |
| **DeepSeek V4 Flash 0731** | General API | **$0.05 → $0.16/M** | raw-price leader; OpenInference is headline-cheapest, route quality varies |

Sources: [Free Router](https://openrouter.ai/openrouter/free/providers) · [Pareto Code](https://openrouter.ai/openrouter/pareto-code) · [MiniMax M3 Free](https://openrouter.ai/minimax/minimax-m3:free) · [GLM-5.2 Free](https://openrouter.ai/z-ai/glm-5.2:free) · [Muse Spark 1.3](https://openrouter.ai/meta/muse-spark-1.3) · [DeepSeek V4 Flash 0731](https://openrouter.ai/deepseek/deepseek-v4-flash-0731)

## AZURE AI FOUNDRY COMPARISON

Azure has a huge catalog, but **catalog presence is not one billing model**. Azure Direct serverless, Fireworks-on-Foundry, managed compute and provisioned throughput must be compared separately.

| Model | Azure route | Azure price / billing | Comparison | Take |
|---|---|---:|---|---|
| **DeepSeek V4 Flash** | **Direct from Azure serverless** | **$0.19 input / $0.51 output / $0.028 cache per M** | DeepSeek direct off-peak $0.22/$0.66/$0.007; Alibaba Virginia ~$0.149/$0.298; OpenRouter $0.05/$0.16 | Azure beats DeepSeek direct on uncached tokens; not raw-cost winner |
| **DeepSeek V4 Pro** | Direct from Azure serverless | **$1.74 / $3.48 / $0.145** | DeepSeek direct off-peak $0.66/$1.98/$0.022 | Azure premium is substantial |
| **Kimi K2.7 Code** | **Direct from Azure** | **$0.95 / $4.00 / $0.19 cache** | Moonshot direct is the same $0.95/$4/$0.19 | price tie; Azure adds procurement/governance |
| Kimi K2.7 Code | Fireworks on Foundry | Marketplace/Fireworks billing; calculator/quote may be needed | Direct Azure route exists | privacy/data-residency boundary is different |
| MiniMax M3 | Fireworks on Foundry | Fireworks/Foundry billing; calculator/quote varies | OpenRouter free currently; MiniMax direct $0.30/$1.20 ≤512K | Azure route is about enterprise deployment, not cheapest testing |
| Open-weight Qwen/DeepSeek variants | Managed compute | GPU/endpoint compute, **not $/token equivalent** | compare only after workload sizing | keep separate from serverless API economics |

### Azure privacy is a real differentiator

For **models sold by Azure / Direct from Azure**, Microsoft says prompts, completions and training data are not made available to the model provider and are not used to train foundation models without permission. That can justify an Azure premium for proprietary code, Entra/RBAC, unified billing, private networking and compliance workflows.

**Fireworks on Foundry is different.** Microsoft’s catalog says Fireworks models run on Fireworks infrastructure; customer data is shared outside Microsoft systems and Foundry data-residency rules do not apply in the same way. Do not treat every model visible in Azure as having the same privacy boundary.

Azure also advertises **$200 of new-account Azure credit for 30 days**. Whether a specific Marketplace/model meter is eligible should be checked at deployment.

Sources: [Azure DeepSeek pricing announcement](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/introducing-deepseek-v4-flash-and-v4-pro-in-microsoft-foundry/4515174) · [DeepSeek V4 Flash catalog](https://ai.azure.com/catalog/models/DeepSeek-V4-Flash) · [Kimi K2.7 Code catalog](https://ai.azure.com/catalog/models/Kimi-K2.7-Code) · [Fireworks Kimi catalog](https://ai.azure.com/catalog/models/FW-Kimi-K2.7-Code) · [Azure model data/privacy](https://learn.microsoft.com/en-us/azure/foundry/responsible-ai/openai/data-privacy) · [Azure free account](https://azure.microsoft.com/en-us/pricing/purchase-options/azure-account)

## NEW MODELS

### 🔥 GLM-5.3-Flash — September 4

Z.ai officially released GLM-5.3-Flash today. It is the first natively multimodal GLM-5 model, with **320B total / 18B active parameters**, hybrid sparse + linear attention and training on a 30T-token multimodal corpus. It supports text, image, video and file understanding. Z.ai also confirmed that the pre-release model was anonymously evaluated as **Ox Alpha**. The weights are available under the MIT license.

Source: [Z.ai / AutoClaw release](https://autoclaw.z.ai/blog/model/glm-5.3-flash/)

### Muse Spark 1.3 — September 2

Meta released Muse Spark 1.3 two days ago with improved long-horizon agentic and coding behavior. Meta says it uses roughly **20% fewer tool calls and 25% fewer tokens** than 1.2 in its engineering comparisons. It is natively multimodal and available through Muse Code / Meta Model API; OpenCode and OpenRouter now expose it as well.

Source: [Meta AI Research](https://research.meta.ai/blog/introducing-muse-spark-1-3)

### Omen Alpha — new OpenCode route

OpenCode now exposes `omen-alpha` with **$0.20/$0.66/M**, $0.04 cache reads, 0-day retention/no training and about **11,600 estimated requests per five hours**. OpenCode has not publicly identified the underlying model/provider, so it should be treated as a **stealth route**, not attributed speculatively.

## DIRECT CHINESE API PRICING / FIRST-PARTY SCAN

Today’s CNY/USD reference rate is about **¥1 = $0.1489**.

| Vendor | Current first-party finding | Access Type |
|---|---|---|
| **DeepSeek** | V4 Flash/Vision **$0.22/$0.66 off-peak**, $0.44/$1.32 peak; cache hit $0.007 off-peak. V4 Pro $0.66/$1.98 off-peak. 1M context. | **General OpenAI + Anthropic-compatible API** |
| **Alibaba / Qwen** | Qwen3.8 Flash Virginia **¥0.8/¥2.7 ≈ $0.119/$0.402/M**; cache ¥0.1. Alibaba-hosted DeepSeek V4 Flash Virginia **¥1/¥2 ≈ $0.149/$0.298/M**. | **General API** |
| **Alibaba Token Plan** | Lite **¥39/mo (~$5.81)** limited-time vs ¥60 list, 2,500 credits/7d. | **Specific-client-only personal plan** |
| **Moonshot / Kimi** | Kimi K2.7 Code **$0.95 input / $0.19 cache hit / $4 output**, 262K. | **General API**; Code memberships separate |
| **MiniMax** | M3 direct API is **$0.30/$1.20/cache $0.06 ≤512K** and $0.60/$2.40/cache $0.12 above 512K; Token Plan starts **$20/mo**. | **General API** + separate Token Plan |
| **Xiaomi / MiMo** | Lite displays **$5.28/mo vs $6 list**, V2.5 text/multimodal/speech, dedicated plan key/Base URL, no 5h/weekly cap, nighttime 0.8×. | **Specific coding-client Token Plan** |
| **Tencent / Hunyuan** | China Hy Lite **¥28/mo (~$4.17)**, 560 credits, Hy4 Preview + Hy3. International Lite remains **$7/mo / 1,000 credits**. | **Specific-client Token Plan endpoints** |
| **SenseTime / SenseNova** | Public beta **¥0/mo**, 60,000 credits/5h, 6.8 Flash Lite + U1 Fast, up to 20 API keys. | **Plan API / agent endpoint** |
| **StepFun** | Current Step Plan page confirms 400M/1.6B/8B/40B-credit tiers and standard API-style integration, but its public page does **not expose trustworthy current prices** to the crawler today. | API + separate Step Plan |
| **Baidu / Qianfan** | Personal Token Plan continues to exist, but today’s first-party public surface did not cleanly expose the old ultra-low personal-plan checkout prices. | General API + personal plan; **price re-check at checkout** |
| **ByteDance / Doubao** | No newly verified sub-$10 promotion or price change surfaced today. | General Ark API + separate coding products |
| **Z.ai / GLM** | **GLM-5.3-Flash launches today**; OpenCode/OpenRouter distribution is already live. | General API / third-party routes |
| **01.AI / Yi** | No fresh first-party coding-plan/API deal surfaced today. | — |

Sources: [DeepSeek pricing](https://api-docs.deepseek.com/quick_start/pricing/) · [Alibaba Qwen3.8 Flash](https://help.aliyun.com/en/model-studio/qwen3-8-flash) · [Alibaba DeepSeek V4 Flash](https://help.aliyun.com/en/model-studio/deepseek-v4-flash) · [Alibaba Token Plan](https://help.aliyun.com/en/model-studio/token-plan-personal-overview) · [Kimi K2.7 Code pricing](https://www.kimi.ai/resources/kimi-k2-7-code-pricing) · [MiniMax pricing](https://platform.minimax.io/subscribe/token-plan?tab=api-enterprise) · [Xiaomi MiMo](https://platform.xiaomimimo.com/) · [Tencent Token Plan](https://cloud.tencent.com/document/product/1823/130060) · [SenseNova Token Plan](https://www.sensenova.cn/en/token-plan) · [Step Plan](https://platform.stepfun.com/step-plan)

## FREE ACCESS

| Offer | Access Type | Free amount | Catch |
|---|---|---|---|
| **Muse Spark 1.3 Contributor Free on OpenCode** | Zen provider API | **$0** | **training permitted**; limited regions; community reports occasional 502/rate limiting |
| OpenRouter Pareto Code | General router API | **$0** | routes among 13 coding models; provider/model can vary |
| OpenRouter MiniMax M3 Free | General API | **$0** | 1M multimodal; free endpoint rate limits |
| OpenRouter GLM-5.2 Free | General API | **$0** | 256K route context; free endpoint rate limits |
| SenseNova public beta | Plan API / agent endpoint | **¥0** | beta terms/capacity may change |
| Command Code Laguna S 2.1 | **Go is agent/CLI-only**; API only on higher plans | **$0 model credits while capacity lasts** | requires account/credits; capacity-limited |
| Command Code LongCat 2.0 | same | **$0 while it lasts** | capacity/promo-limited |

## LOW-COST SUBSCRIPTIONS

| Plan | Price | Access Type | Key value / catch |
|---|---:|---|---|
| **Command Code Go** | **$1/mo** | **Agent/CLI-only — NO Provider API** | $10 credits; Laguna + LongCat currently free; M3 2×; MiMo up to 99% off |
| Tencent Hy Lite China | **¥28 ≈ $4.17/mo** | Specific-client-only | 560 credits, Hy4 Preview + Hy3 |
| **MiMo Lite** | **$5.28 displayed / $6 list** | Specific-client Token Plan | no weekly/5h cap; dedicated key/Base URL for supported coding tools |
| Alibaba Lite | **¥39 ≈ $5.81/mo** | Specific-client-only | 2,500 credits/7d; tool-use restrictions matter |
| Tencent International Lite | **$7/mo** | Specific-client-only | 1,000 credits; OpenCode/Codex/Claude Code-style tools |
| **Command Code GOAT** | **$10/mo** | **Agent/CLI + OpenAI/Anthropic-compatible API** | $70 credits; every tier except Go has Provider API access |
| OpenCode Go | **$10/mo** | **Provider/API for coding agents** | 27-model curated pool; $12/5h, $30/week, $60/month |

Command Code’s classification is important: **Go does not have Provider API access. GOAT and higher plans do.**

Sources: [Command Code Go](https://commandcode.ai/docs/plans/go) · [Command Code GOAT](https://commandcode.ai/docs/plans/goat) · [Command Code Provider API](https://commandcode.ai/docs/provider) · [MiMo Token Plan](https://platform.xiaomimimo.com/) · [Tencent international Token Plan](https://intl.cloud.tencent.com/document/product/1300/81315)

## BEST VALUE TODAY

**Best immediate $0 coding experiment:** **Muse Spark 1.3 Contributor Free on OpenCode Zen.** It is new, very fast, multimodal and costs nothing. The catch is material: **Contributor prompts/completions may be used for Meta model training**, so use it for public/non-sensitive work, not proprietary code.

**Best free general coding router:** **OpenRouter Pareto Code**. It costs $0, automatically chooses from 13 coding models and has a 2M router context. It is a particularly good “just give me a competent free coder” fallback.

**Best privacy-conscious option already in the paid stack:** **GLM-5.3-Flash on OpenCode Go**. It is ZDR/no-training, is the production model behind Ox Alpha, and currently has a **2× usage promotion**. Omen Alpha is also interesting for high-volume ZDR work, but it is still a stealth route.

**Cheapest metered DeepSeek Flash route:** **OpenRouter at $0.05/$0.16/M** if provider variability is acceptable. Alibaba Virginia at about **$0.149/$0.298/M** is the strongest hyperscaler-style raw-price alternative found today. Azure Direct at **$0.19/$0.51/M** is not the cheapest, but it beats DeepSeek direct off-peak uncached pricing and adds Microsoft governance/privacy/procurement benefits.

**No compelling reason to add another expensive subscription today.** The existing mix of OpenCode Go, direct DeepSeek, Codex/ChatGPT, Gemini and a vision/image-generation route already covers the premium side. Today’s incremental wins are all **free or cheap capacity**: Muse Contributor Free, Pareto Code, Command Code’s $1 lane, MiMo Lite, and Azure when enterprise controls matter.
