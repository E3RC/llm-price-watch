---
layout: post
title: "LLM Price Watch — September 5, 2026"
date: 2026-09-05 08:26:00 -0400
summary: "OpenCode renews DeepSeek ZDR through September 30, OpenRouter's cheapest DeepSeek V4 Flash route falls to about $0.05/$0.10, MiniMax M3 is free on Vercel, and a new Ling 3.0 Flash Sante free endpoint joins the market."
---

## 🚨 Top changes today

| Change | Why it matters |
|---|---|
| **✅ OpenCode DeepSeek ZDR is renewed through Sep. 30** | Yesterday's stale Aug. 31 footnote is fixed. OpenCode now explicitly says the DeepSeek ZDR agreement is renewed monthly and the current agreement is valid through **September 30, 2026**. |
| **🔥 OpenRouter DeepSeek V4 Flash falls to ~$0.05 / $0.10 per M** | The headline route is now **$0.04998 input / $0.09996 output** via Baidu Qianfan, undercutting yesterday's $0.05/$0.16 OpenInference route. |
| **🔥 MiniMax M3 is free on Vercel AI Gateway** | Vercel currently lists `minimax/minimax-m3` as **Free**, with a 1M context window, native multimodal input and OpenAI/Anthropic-compatible API access. No expiry is published. |
| **🆕 Ling 3.0 Flash Sante Free launched Sep. 4** | OpenRouter's `inclusionai/ling-3.0-flash-sante:free` has **262K context**, tools, 32K max output and $0 token pricing. It is medicine-focused but retains general reasoning, coding and agent capability. |
| **🔥 Dots3 Note Preview remains free through Sep. 30** | 512K context, text+image, tools and structured output. The provider explicitly says the free preview goes away **September 30, 2026**. |
| **OpenCode Go remains 27 models** | No new Go ID today. GLM-5.3-Flash still has its temporary **2× usage** promotion; Omen Alpha and Muse Spark 1.3 Contributor remain the newest Go additions. |
| **Omen Alpha identity is still officially unconfirmed** | Community fingerprinting strongly points to a GLM/Zhipu-family model and a GitHub commit reportedly exposed an `OMEN-ALPHA-free:global` string, but OpenCode has not confirmed either identity or a free route. **Community-only / unverified.** |
| **SenseNova free beta differs by region** | International page: **$0, 1,500 calls/model/5h**. China page: **¥0, 60,000 credits/5h**. Both allow up to 20 API keys. |

Sources: [OpenCode Go](https://dev.opencode.ai/docs/go/) · [OpenRouter DeepSeek](https://openrouter.ai/deepseek) · [Vercel MiniMax M3](https://vercel.com/ai-gateway/models/minimax-m3/about) · [Ling Sante Free](https://openrouter.ai/inclusionai/ling-3.0-flash-sante:free) · [Dots Studio](https://openrouter.ai/dots-studio) · [SenseNova International](https://www.sensenova.ai/token-plan) · [SenseNova China](https://www.sensenova.cn/en/token-plan)

## OpenCode Go

OpenCode Go remains **$10/month** with overall limits of **$12/5h, $30/week and $60/month**. It provides a Go API key/provider endpoint designed for OpenCode and compatible coding agents.

| Model | Input → output / M | Est. req/5h | Modality / privacy | Change |
|---|---:|---:|---|---|
| Grok 4.6 | $2 → $6* | 169 | agent · 30d | — |
| GPT-5.6 Luna | $0.20 → $1.20* | 2,050 | vision/text · 30d | — |
| **GLM-5.3-Flash** | **$0.15 → $0.50** | 1,580 base | multimodal · ZDR | **2× promo active** |
| GLM-5.3 | $1.40 → $4.40 | 220 | agent · ZDR | — |
| GLM-5.2 | $1.40 → $4.40 | 880 | agent · ZDR | — |
| GLM-5.1 | $1.40 → $4.40 | 880 | agent · ZDR | — |
| Kimi K3 | $3 → $15 | 110 | multimodal/agent · ZDR | — |
| Kimi K2.7 Code | $0.95 → $4 | 1,350 | coding/multimodal · ZDR | — |
| Kimi K2.6 | $0.95 → $4 | 1,150 | multimodal · ZDR | — |
| LongCat-2.0 | $0.30 → $1.20 | 11,400 | agent · ZDR | — |
| **MiMo-V2.5** | **$0.14 → $0.28** | **30,100** | multimodal · ZDR | volume leader |
| MiMo-V2.5-Pro | $0.435 → $0.87 | 3,250 | multimodal · ZDR | — |
| MiniMax M3 | $0.30 → $1.20 | 3,200 | multimodal/agent · ZDR | — |
| MiniMax M2.7 | $0.30 → $1.20 | 3,400 | agent · ZDR | — |
| Muse Spark 1.3 Contributor | $0.10 → $0.20 | **45,300** | multimodal/agent · **TRAINING YES** | — |
| Muse Spark 1.2 Contributor | $0.10 → $0.20 | 45,300 | agent · **TRAINING YES** | — |
| Qwen3.8 Max | $2 → $6 | 160 | multimodal · ZDR | — |
| Qwen3.8 Flash | $0.15 → $0.47 | 5,400 | text/image/video · ZDR | — |
| Qwen3.7 Max | $2.50 → $7.50 | 170 | agent · ZDR | — |
| Qwen3.7 Plus | $0.40 → $1.60* | 4,300 | multimodal · ZDR | — |
| Qwen3.6 Plus | $0.50 → $3* | 3,300 | agent · ZDR | — |
| **DeepSeek V4 Pro** | $0.66 → $1.98 off-peak | 1,050 | agent · **ZDR through Sep. 30** | **privacy renewed** |
| **DeepSeek V4 Flash** | $0.22 → $0.66 off-peak | 7,600 | coding · **ZDR through Sep. 30** | **privacy renewed** |
| **DS V4 Flash Vision Exp** | $0.22 → $0.66 off-peak | 3,800 | vision · **ZDR through Sep. 30** | **privacy renewed** |
| Hy4 Preview | $0.834 → $2.501 | 1,350 | agent · ZDR | — |
| Hy3 | $0.14 → $0.58 | 4,300 | agent · ZDR | — |
| Omen Alpha | $0.20 → $0.66 | 11,600 | stealth agent · ZDR | identity unconfirmed |

\* Higher-context tiers differ. DeepSeek peak pricing is 2× the off-peak rates shown, but peak windows apply only Monday-Friday; weekends are off-peak all day.

**Privacy change:** OpenCode's Sep. 5 docs now explicitly say: "DeepSeek: ZDR agreement is renewed monthly. The current agreement is valid through September 30, 2026." Muse Contributor remains the exception: prompts/completions may train future Meta models.

Sources: [OpenCode Go docs](https://dev.opencode.ai/docs/go/) · [Go landing page](https://dev.opencode.ai/go)

## OPENCODE FREE / PREVIEW DEALS

The current documented Zen free list remains **seven** models.

| Model / ID | Access Type | Cost | Context / modality | Privacy / limits |
|---|---|---:|---|---|
| `big-pickle` | Zen provider API | **$0** | stealth / not published | limited-time; data may improve model |
| `mimo-v2.5-free` | Zen provider API | **$0** | ~1M / multimodal | limited-time feedback/model-improvement period |
| `ling-3.0-flash-fin-free` | Zen provider API | **$0** | ~262K / coding-text | limited-time feedback/model-improvement period |
| `nemotron-3-ultra-free` | Zen provider API | **$0** | not stated on Zen page | NVIDIA trial logging; avoid confidential data |
| `nemotron-3.5-lightning-free` | Zen provider API | **$0** | not stated on Zen page | NVIDIA trial logging; avoid confidential data |
| `muse-spark-1.3-contributor-free` | Zen provider API | **$0** | multimodal/agent | **training permitted; regional restrictions** |
| `muse-spark-1.2-contributor-free` | Zen provider API | **$0** | agent | **training permitted; regional restrictions** |
| Ox Alpha Free | ended preview | — | became GLM-5.3-Flash | preview ended |
| Hy3 Free | former route | — | not on current free list | no longer documented free |
| **Omen Alpha Free** | **community watch only** | **not live/confirmed** | — | GitHub string reportedly spotted; **unverified** |

Also active: **GPT-5.6 Sol is 50% off on Zen through September 18, 2026.**

Source: [OpenCode Zen](https://dev.opencode.ai/docs/zen)

## OPENROUTER DEALS

| Route | Access Type | Current price | Why it matters |
|---|---|---:|---|
| `openrouter/free` | OpenAI-compatible API/router | **$0** | 24-model capability-aware pool; 200K router context |
| `openrouter/pareto-code` | OpenAI/Anthropic-compatible API/router | **$0** | 13 coding models, **2M context** |
| **Ling 3.0 Flash Sante Free** | OpenAI-compatible API | **$0** | **NEW** Sep. 4; 262K, 32K max output, tools; medical focus but general coding retained |
| **Dots3 Note Preview Free** | OpenAI-compatible API | **$0 through Sep. 30** | 512K, text+image, tools/structured output |
| MiniMax M3 Free | General API | **$0** | 1M, multimodal/tools; free endpoint may rate-limit |
| **DeepSeek V4 Flash 0731** | General API | **$0.04998 → $0.09996/M** | **new raw-cost leader via Baidu Qianfan** |
| DeepSeek V4 Flash / OpenInference | General API | $0.05 → $0.16/M | previous headline bargain; still competitive |
| **GLM-5.3-Flash** | General API | **$0.075 → $0.25/M** | 50%-off Z.ai route; temporary launch promo |
| Kimi K3 | General API | about **$2.55 → $12.75/M** | ~15% below Moonshot's common $3/$15 direct route |

**Provider anomaly of the day:** OpenRouter's DeepSeek V4 Flash page now headlines the Baidu Qianfan route at $0.04998 input / $0.09996 output per million tokens. That is dramatically below DeepSeek direct off-peak sticker pricing. Route provenance, latency and provider policies still matter.

Sources: [DeepSeek on OpenRouter](https://openrouter.ai/deepseek) · [Free Router](https://openrouter.ai/openrouter/free) · [Dots Studio](https://openrouter.ai/dots-studio) · [Ling Sante Free](https://openrouter.ai/inclusionai/ling-3.0-flash-sante:free) · [Z.ai provider](https://openrouter.ai/provider/z-ai)

## FREE ACCESS OUTSIDE OPENCODE / OPENROUTER

| Offer | Access Type | Current deal | Catch |
|---|---|---|---|
| **Vercel AI Gateway — MiniMax M3** | OpenAI/Anthropic-compatible API gateway | **FREE today** | 1M context, text/image/video; no expiry published |
| **SenseNova International beta** | Plan API / agent endpoint | **$0; 1,500 calls/model/5h** | 6.8 Flash Lite + U1 Fast; up to 20 API keys |
| **SenseNova China beta** | Plan API / agent endpoint | **¥0; 60,000 credits/5h** | regional plan; do not confuse with international quota |
| **Z.ai AutoClaw new-user grant** | specific-client desktop agent | **100M GLM-5.3-Flash tokens** | not unrestricted backend API credit |
| **Command Code Laguna S 2.1** | Go = agent/CLI-only; API on eligible Provider plans | **$0 while capacity lasts** | requires account/credit balance to start |
| **Command Code LongCat 2.0** | Go = agent/CLI-only; API on eligible Provider plans | **$0 while it lasts** | 1M context |
| Azure free account | Azure services credit | **$200 / 30 days** | specific Marketplace/model eligibility varies |

Sources: [Vercel MiniMax M3](https://vercel.com/ai-gateway/models/minimax-m3/about) · [SenseNova International](https://www.sensenova.ai/token-plan) · [SenseNova China](https://www.sensenova.cn/en/token-plan) · [AutoClaw](https://autoclaw.z.ai/) · [Command Code pricing](https://commandcode.ai/docs/resources/pricing-limits)

## AZURE AI FOUNDRY COMPARISON

Azure's model catalog now contains **11,000+ entries**, but catalog presence is not one billing/privacy model. Separate **Direct from Azure**, **Fireworks/partner inference**, and **managed/provisioned compute**.

| Model | Azure route | Azure pricing / billing | Comparison | Take |
|---|---|---:|---|---|
| **DeepSeek V4 Flash** | **Direct from Azure serverless** | **$0.19 in / $0.51 out / $0.028 cached per M** | DeepSeek direct off-peak $0.22/$0.66/$0.007; Alibaba global ~$0.149/$0.298; OR Baidu ~$0.05/$0.10 | Azure beats DeepSeek direct on uncached sticker price; not cheapest raw inference |
| **DeepSeek V4 Pro** | Direct from Azure serverless | **$1.74 / $3.48 / $0.145** | DeepSeek direct off-peak $0.66/$1.98/$0.022 | substantial Azure premium |
| **Kimi K2.6** | **Direct from Azure, Preview** | portal/calculator | Moonshot direct/provider pricing varies | 262K, text+image; Azure governance/privacy advantage |
| **Kimi K2.7 Code** | Azure catalog + Fireworks route | portal/partner billing | common Moonshot rate ~$0.95/$4 | verify deployment type before assuming Microsoft data boundary |
| **Kimi K3** | **Fireworks on Foundry, GA** | partner PAYG/PTU | OpenRouter about $2.55/$12.75; direct common rate $3/$15 | 1M + vision, but data leaves Microsoft systems |
| **MiniMax M3** | Fireworks on Foundry | partner PAYG/PTU | Vercel/OpenRouter have free access today | Azure route is governance/procurement, not lowest-cost testing |
| **GLM-5** | Fireworks on Foundry | partner PAYG/PTU | GLM-5.3-Flash is newer elsewhere | current Azure partner catalog trails latest Flash release |
| Qwen/open-weight models | Managed deployment | GPU/compute billing | not directly comparable with Qwen Cloud $/token | size workload first |

**Azure privacy advantage:** for **Azure Direct Models**, Microsoft says prompts, outputs and training data are not made available to the original model provider and are not used to train foundation models without permission. **Fireworks on Foundry is explicitly different:** Fireworks models run on Fireworks infrastructure, data is shared outside Microsoft systems, and Microsoft Foundry data-residency documentation does not apply to that partner route.

**Managed Compute/PTU:** Azure's public pricing page currently leaves many managed-GPU and third-party/PTU numeric cells as `$-`; use the Azure calculator/portal for the exact subscription/region quote rather than inventing a token-equivalent price. DeepSeek R1/V3 provisioned tables list a **100 PTU minimum**, while the current public page does not expose a numeric V4 PTU rate.

Sources: [Azure DeepSeek pricing](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/introducing-deepseek-v4-flash-and-v4-pro-in-microsoft-foundry/4515174) · [Azure Direct privacy](https://learn.microsoft.com/en-us/azure/foundry/responsible-ai/openai/data-privacy) · [DeepSeek V4 Flash catalog](https://ai.azure.com/catalog/models/DeepSeek-V4-Flash) · [Kimi K2.6 catalog](https://ai.azure.com/catalog/models/Kimi-K2.6) · [FW Kimi K3](https://ai.azure.com/catalog/models/FW-Kimi-K3) · [FW MiniMax M3](https://ai.azure.com/catalog/models/FW-MiniMax-M3) · [FW GLM-5](https://ai.azure.com/catalog/models/FW-GLM-5) · [Azure pricing](https://azure.microsoft.com/en-us/pricing/details/ai-foundry-models/deepseek/)

### Azure requested-vendor scan

| Vendor | Azure status today |
|---|---|
| DeepSeek | **Direct from Azure** V4 Flash/Pro plus other catalog variants |
| Moonshot/Kimi | Direct K2.6 preview; K2.7 Code catalog presence plus Fireworks K2.7; K3 via Fireworks |
| Alibaba/Qwen | open-weight/managed catalog entries such as Qwen3.8-27B; not the same as Qwen Cloud PAYG |
| Zhipu/GLM | GLM-5 via Fireworks; no Azure Direct GLM-5.3-Flash token SKU surfaced today |
| MiniMax | M3 via Fireworks |
| Xiaomi/MiMo | no comparable Azure Direct token-priced SKU surfaced today |
| Tencent/Hunyuan | no comparable Azure Direct token-priced SKU surfaced today |
| Baidu/ERNIE | no comparable Azure Direct token-priced SKU surfaced today |
| ByteDance/Doubao | no comparable Azure Direct token-priced SKU surfaced today |
| StepFun | no comparable Azure Direct token-priced SKU surfaced today |
| SenseTime/SenseNova | no comparable Azure Direct coding-model SKU surfaced today |
| 01.AI/Yi | no comparable current Azure Direct hosted Yi API surfaced today |

## DIRECT CHINESE API PRICING / FIRST-PARTY SCAN

CNY conversions below use roughly **¥1 = $0.149** today.

| Vendor | Current finding | Access Type |
|---|---|---|
| **DeepSeek** | V4 Flash/Vision **$0.22/$0.66 off-peak**, 2× peak; Pro **$0.66/$1.98 off-peak**. Cache hits remain extremely cheap at $0.007 Flash / $0.022 Pro off-peak. | **General OpenAI + Anthropic-compatible API** |
| **Alibaba/Qwen PAYG** | Qwen3.8 Flash Virginia **¥0.8/¥2.7 ≈ $0.119/$0.402**; Qwen3.8 Max Virginia **¥12/¥36 ≈ $1.79/$5.36**. | **General API** |
| **Alibaba-hosted DeepSeek** | V4 Flash Virginia Global **¥1/¥2 ≈ $0.149/$0.298**; US-scoped `-us` route **¥1.499/¥2.998 ≈ $0.223/$0.447**. | **General API** |
| **Alibaba Token Plan Personal** | **¥39/mo (~$5.81), ¥60 list**, 2,500 credits/7d; 50% night-credit discount on selected models. | **specific-client-only** — explicitly forbids automation scripts/custom backends/non-interactive batch |
| **Baidu Qianfan Token Plan** | Mini **¥4.9 first buy / ¥9.9 regular (~$0.73/$1.48)** for 10M tokens; Lite **¥19.9/¥40 (~$2.97/$5.96)** for 42M. | **specific-client-only** under the conservative classification rule; do not treat the plan key as unrestricted backend API |
| **Tencent Token Plan** | General Lite **¥39 (~$5.81)**; Hy Lite **¥28 (~$4.17)**. Sep. 1-30 promo halves credit coefficients for Auto, Kimi K2.7 Code and MiniMax M3. | **specific-client-only** |
| **SenseNova International** | **$0 public beta, 1,500 calls/model/5h**, up to 20 keys. | Plan API / agent endpoint |
| **SenseNova China** | **¥0 public beta, 60,000 credits/5h**, up to 20 keys. | Plan API / agent endpoint |
| **StepFun AI** | Hosted membership **¥9.9/week** or **¥39/month**; separate Step Plan exposes 400M-40B monthly credits but current page does not render prices. | hosted/specific-client for membership; separate API plan |
| **MiniMax** | First-party Token Plan starts around **$200/year (~$16.67/mo)** for Plus; no sub-$10 first-party plan surfaced. | specific-client Token Plan; API separate |
| **Xiaomi/MiMo** | ~$6-class Token Plan remains in the market, but the first-party pricing surface did not crawl reliably today; no price change claimed. | specific-client-only Token Plan |
| **Z.ai/GLM** | GLM-5.3-Flash launch pricing is currently exposed through partner routes at **$0.075/$0.25**; first-party direct price surface was not cleanly crawlable today. | API / coding-plan routes differ |
| **Moonshot/Kimi** | K2.7 Code common direct-provider rate remains around **$0.95/$4**; K3 around **$3/$15**. First-party price page was not reliably crawlable today. | General API |
| **ByteDance/Doubao** | No current sub-$10 first-party launch promo re-verified today; older ¥9.9-era coding promos are not carried forward. | API / coding plan separate |
| **01.AI/Yi** | Public hosted API/model experience ended after **Sep. 3, 2026** per the company's announced shutdown timeline; open weights/self-hosting remain separate. | hosted public API ended |

Sources: [DeepSeek updates/pricing](https://api-docs.deepseek.com/updates/) · [Alibaba model pricing](https://help.aliyun.com/en/model-studio/model-pricing) · [Alibaba Token Plan](https://help.aliyun.com/en/model-studio/token-plan-personal-overview) · [Tencent September discount](https://cloud.tencent.com/document/product/1823/133811) · [Tencent Token Plan](https://cloud.tencent.com/act/pro/tokenplan) · [SenseNova International](https://www.sensenova.ai/token-plan) · [StepFun membership](https://chat.stepfun.com/subscription) · [Step Plan](https://platform.stepfun.com/step-plan) · [MiniMax Token Plan](https://platform.minimax.io/subscribe)

## LOW-COST SUBSCRIPTIONS

| Plan | Price | Access Type | Best use |
|---|---:|---|---|
| **Baidu Qianfan Mini** | **~$0.73 first buy / $1.48 regular** | **specific-client-only** | absurdly cheap multi-model coding/agent plan if regional signup works |
| **Command Code Go** | **$1/mo** | **agent/CLI-only — NO Provider API** | cheap independent coding-agent bucket |
| Tencent Hy Lite | **~$4.17/mo** | specific-client-only | Hy3/Hy4 coding/agent use |
| Alibaba Token Plan Lite | **~$5.81/mo promo** | **specific-client-only** | Qwen/DeepSeek/GLM in approved interactive tools |
| Tencent General Lite | **~$5.81/mo** | specific-client-only | broad multi-model coding plan; Sep discount active |
| StepFun AI Entry | **~$5.81/mo** | hosted/specific-client agent | StepClaw desktop/cloud + messaging integrations |
| Xiaomi MiMo Lite | **~$6-class** | specific-client-only | MiMo coding plan; current first-party price surface not re-verified today |
| **Command Code GOAT** | **$10/mo** | agent/CLI + Provider API eligibility | $70 monthly credits, broader model access |
| OpenCode Go | **$10/mo** | provider/API for coding agents | curated 27-model pool with strong MiMo/DeepSeek value |

**Command Code classification:** Go remains agent/CLI-only for Provider API purposes. Command Code's Provider API documentation is separate; its dedicated Provider plan starts at $15/mo + fee, while higher agent plans may have provider-access eligibility according to current account/plan rules. Do not label Go as API access.

Source: [Command Code pricing](https://commandcode.ai/pricing) · [Provider API](https://commandcode.ai/docs/provider)

## NEW MODELS / MARKET CHANGES

### Ling 3.0 Flash Sante Free — released Sep. 4

InclusionAI's medicine-focused Ling 3.0 Flash Sante is now free on OpenRouter with **262,144 context**, **32,768 max output**, tool calling and general coding/agent capability. This is the most notable newly listed free endpoint since yesterday.

### Omen Alpha — stealth watch

OpenCode still publishes only the name, price and privacy status. Reddit users have produced tokenizer/vision fingerprints and captured a transient Zhipu provider tag that strongly suggest a GLM-family model. A GitHub commit reportedly contained an `OMEN-ALPHA-free:global` identifier. **Neither the model identity nor a future free endpoint is officially confirmed.** Omen Alpha is **not free today**; Go pricing remains $0.20/$0.66 with $0.04 cache reads.

### No new major flagship surfaced on Sep. 5

GLM-5.3-Flash (Sep. 4 reveal/launch) remains the newest major coding/agent flagship in this watch. Its OpenCode Go 2× promo and partner launch discounts remain active.

## 🏆 BEST VALUE TODAY

1. **Free multimodal agent:** Vercel **MiniMax M3** — 1M context, native image/video, API access, currently $0 with no published expiry.
2. **Cheapest paid DeepSeek route:** OpenRouter's **Baidu Qianfan** route at about **$0.05 input / $0.10 output per M**. For repeated cached workloads, DeepSeek direct's **$0.007/M cache-hit** rate remains excellent.
3. **Best news for existing OpenCode Go users:** DeepSeek's **ZDR is now explicitly renewed through Sep. 30**, removing yesterday's privacy ambiguity. GLM-5.3-Flash's 2× Go promo also remains active.
4. **Temporary free route to grab:** **Dots3 Note Preview Free** before Sep. 30; 512K + vision + tools is unusually generous.
5. **Ultra-cheap subscription:** Baidu Qianfan Mini is ~$0.73 first-buy / ~$1.48 regular, but treat it as **specific-client-only**, not general backend API access.
6. **No reason to chase another expensive subscription solely for capacity:** free Vercel/OpenRouter/OpenCode routes plus the $1-$10 coding-plan market continue to offer much better marginal value for experimentation.

## Sources / methodology

Pricing is normalized to per-million-token rates where possible. Provider subscriptions that expose an API-shaped key but prohibit custom backends, automation or batch use are classified **specific-client-only**, not general API. Azure Direct, Fireworks-on-Foundry, managed compute and PTU are kept separate because their economics and data boundaries are different. Community reports are used as leads but are marked unverified until a provider confirms them.
