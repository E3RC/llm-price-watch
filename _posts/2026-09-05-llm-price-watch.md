---
layout: post
title: "LLM Price Watch — September 5, 2026"
date: 2026-09-05 07:30:00 -0400
summary: "Baidu Qianfan's sub-$2 Token Plan becomes the standout paid deal, 01.AI shuts its public API, OpenCode Go stays at 27 models with GLM-5.3-Flash 2× usage, and Azure's Kimi deployment split is clarified."
---

## 🚨 Top changes today

| Change | Why it matters |
|---|---|
| **🔥 Baidu Qianfan Mini is now first-party confirmed at ¥4.9 first buy / ¥9.9 regular** | The personal Token Plan includes **10M tokens**, a dedicated plan API key, OpenAI + Anthropic protocol compatibility and agent/coding support. At today's FX this is roughly **$0.73 first month / $1.48 regular**. |
| **Baidu Qianfan Lite is ¥19.9 first buy / ¥40 regular** | **42M tokens**, roughly **$2.97 / $5.96**. First-buy inventory is limited; the first renewal is discounted and nighttime token consumption can be lower. |
| **🚫 01.AI / Yi shut down their public hosted API** | 01.AI says public model experience and API calls stopped at **September 3, 2026 24:00 China time**. Open weights/self-hosting remain separate. |
| **OpenCode Go remains 27 models** | No new Go ID since yesterday. **GLM-5.3-Flash still has the 2× Go-usage promo**; Muse Spark 1.3 Contributor and Omen Alpha remain the newest additions. |
| **OpenCode DeepSeek ZDR is still not cleanly renewed for September** | Current Go documentation still exposes an August 31 footnote for the DeepSeek ZDR arrangement. Treat September ZDR as **unconfirmed**, despite the table continuing to show 0-day retention. |
| **Azure Kimi classification corrected** | **Kimi K2.7 Code is currently a Fireworks-on-Foundry partner offer**, with the Fireworks data boundary. **Kimi K2.6** is the Azure-hosted Direct-from-Azure preview. |
| **OpenRouter DeepSeek pricing has a provider-index anomaly** | Canonical DeepSeek V4 Flash 0731 detail is **$0.05/$0.16/M**, while OpenRouter's provider index has briefly advertised output near **$0.10/M**. Verify the selected provider before assuming the lower number. |
| **New cheap China plans worth watching** | StepFun Entry **¥39/mo**, MiniMax Plus **¥49/mo**, and Kimi Andante **¥49/mo** all land in the roughly $5.81–$7.30/month range, but they are **specific-client/personal-workflow plans**, not unrestricted backend APIs. |

## OpenCode Go

OpenCode Go remains **$10/month**, with a provider/API key for coding-agent use and overall limits of **$12/5h, $30/week and $60/month**. The advertised lineup remains 27 models. [OpenCode Go docs](https://dev.opencode.ai/docs/go/) · [Go landing page](https://dev.opencode.ai/go)

| Model | Input → output / M | Est. req/5h | Modality / privacy | Change vs Sep. 4 |
|---|---:|---:|---|---|
| Grok 4.6 | $2 → $6* | 169 | agent · 30d | — |
| GPT-5.6 Luna | $0.20 → $1.20* | 2,050 | vision/text · 30d | — |
| **GLM-5.3-Flash** | **$0.15 → $0.50** | 1,580 base | native multimodal · ZDR | **2× promo continues** |
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
| Muse Spark 1.3 Contributor | $0.10 → $0.20 | **45,300** | multimodal/agent · **TRAINING YES** | stable |
| Muse Spark 1.2 Contributor | $0.10 → $0.20 | 45,300 | agent · **TRAINING YES** | — |
| Qwen3.8 Max | $2 → $6 | 160 | multimodal · ZDR | — |
| Qwen3.8 Flash | $0.15 → $0.47 | 5,400 | text/image/video · ZDR | — |
| Qwen3.7 Max | $2.50 → $7.50 | 170 | agent · ZDR | — |
| Qwen3.7 Plus | $0.40 → $1.60* | 4,300 | multimodal · ZDR | — |
| Qwen3.6 Plus | $0.50 → $3* | 3,300 | agent · ZDR | — |
| DeepSeek V4 Pro | $0.66 → $1.98 off-peak | 1,050 | agent · **ZDR?** | stale Aug. 31 footnote |
| DeepSeek V4 Flash | $0.22 → $0.66 off-peak | 7,600 | coding · **ZDR?** | stale Aug. 31 footnote |
| DeepSeek V4 Flash Vision Exp | $0.22 → $0.66 off-peak | 3,800 | vision · **ZDR?** | stale Aug. 31 footnote |
| Hy4 Preview | $0.834 → $2.501 | 1,350 | agent · ZDR | — |
| Hy3 | $0.14 → $0.58 | 4,300 | agent · ZDR | — |
| Omen Alpha | $0.20 → $0.66 | 11,600 | image+text agent · ZDR | stealth identity still unconfirmed |

\* Higher-context tiers differ. DeepSeek peak rates are 2× the off-peak rates shown.

### Privacy note

Muse Contributor access explicitly permits Meta to use prompts/completions for future training and has regional restrictions. Omen Alpha and most of the Chinese-model Go routes are listed as 0-day retention/no training. DeepSeek is the exception where OpenCode's **table and footnote remain internally inconsistent for September**, so sensitive DeepSeek work should not rely on Go's claimed ZDR until the footnote is renewed.

## OPENCODE FREE / PREVIEW DEALS

The current documented Zen free list is still **seven models**. OpenCode does not publish a single universal context/quota for these free routes, so route-specific limits should be treated as capacity-dependent unless explicitly documented. [OpenCode Zen](https://dev.opencode.ai/docs/zen)

| Model / ID | Access Type | Cost | Modality / context | Limits / privacy / status |
|---|---|---:|---|---|
| `mimo-v2.5-free` | Zen provider API | **$0** | multimodal / large context | limited-time; free-period data may improve model |
| `ling-3.0-flash-fin-free` | Zen provider API | **$0** | coding/text | limited-time; free-period data may improve model |
| `nemotron-3-ultra-free` | Zen provider API | **$0** | text/agent | NVIDIA trial logging; avoid confidential work |
| `nemotron-3.5-lightning-free` | Zen provider API | **$0** | text/agent | NVIDIA trial logging; avoid confidential work |
| `big-pickle` | Zen provider API | **$0** | stealth | limited-time; data may improve model |
| **`muse-spark-1.3-contributor-free`** | Zen provider API | **$0** | multimodal agent | **training permitted; Meta-region restrictions** |
| `muse-spark-1.2-contributor-free` | Zen provider API | **$0** | agent | **training permitted; Meta-region restrictions** |
| Ox Alpha Free | ended preview | — | became GLM-5.3-Flash | no longer a free preview ID |
| Hy3 Free | former route | — | — | no longer on current documented list |

Also active: **GPT-5.6 Sol is 50% off on Zen through September 18, 2026.**

**Community signal:** Reddit users continue to report extremely generous Muse 1.3 Contributor Free usage in some regions, but also region locks, occasional 502s and free-limit messages. The free route and regional restrictions are official; exact community-observed quotas are **unverified**.

## OPENROUTER DEALS

| Route | Access Type | Current price | Why it matters |
|---|---|---:|---|
| `openrouter/free` | OpenAI-compatible API/router | **$0** | 24-model capability-aware pool; 200K router context |
| **`openrouter/pareto-code`** | OpenAI/Anthropic-compatible API/router | **$0** | **13 coding models, 2M context**; quality-tier routing |
| **North Mini Code Free** | General API | **$0** | 256K context, 64K max output, tools; purpose-built for coding harnesses |
| **GLM-5.3-Flash** | General API | **$0.075 → $0.25/M** | 50%-off route; official production model behind Ox Alpha |
| **DeepSeek V4 Flash 0731** | General API | **canonical $0.05 → $0.16/M** | raw-price leader on canonical detail page; 1M+ context |
| DeepSeek V4 Flash provider-index anomaly | General API | **headline as low as ~$0.05 → $0.10/M** | provider/index display differs from canonical route; verify selected provider |
| DeepSeek V4 Flash — DeepSeek provider | General API | **$0.22 → $0.66/M** | first-party provider route on OpenRouter |

Sources: [Free Router](https://openrouter.ai/openrouter/free/providers) · [Pareto Code](https://openrouter.ai/openrouter/pareto-code) · [North Mini Code Free](https://openrouter.ai/cohere/north-mini-code:free) · [DeepSeek V4 Flash 0731](https://openrouter.ai/deepseek/deepseek-v4-flash-0731)

**Community signal:** OpenRouter users continue to warn that automatic provider hopping can reduce prompt-cache reuse on long coding sessions. If cache hit rate matters, pinning a provider can outperform the absolute cheapest headline route. This is community experience rather than a platform guarantee.

## AZURE AI FOUNDRY COMPARISON

Azure Foundry now needs three separate buckets: **Azure Direct serverless**, **partner inference such as Fireworks**, and **managed/provisioned compute**. Mixing them produces misleading $/token comparisons.

| Model | Azure route | Azure price / billing | Comparison | Take |
|---|---|---:|---|---|
| **DeepSeek V4 Flash** | **Direct from Azure serverless** | **$0.19 input / $0.51 output / $0.028 cache per M** | DeepSeek direct off-peak $0.22/$0.66/$0.007; OpenRouter canonical $0.05/$0.16 | Azure beats direct uncached; OpenRouter wins raw cost; direct wins cache-hit price |
| **DeepSeek V4 Pro** | Direct from Azure serverless | **$1.74 / $3.48 / $0.145** | DeepSeek direct off-peak $0.66/$1.98/$0.022 | Azure premium is substantial |
| **Kimi K2.7 Code** | **Fireworks on Foundry** | Marketplace/partner billing | Moonshot direct $0.95/$4, cache $0.19 | **Not Azure Direct**; Fireworks data boundary applies |
| **Kimi K2.6** | **Direct from Azure, Preview** | token pricing depends on region/deployment surface | Moonshot-family direct pricing roughly same class | Azure-native Kimi option; text+image, 262K |
| MiniMax M3 | Fireworks on Foundry | partner billing | MiniMax direct $0.30/$1.20 ≤512K | enterprise procurement route, not cheapest experimentation |
| Qwen3.8-27B and other open weights | managed deployment | dedicated GPU/endpoint compute | not directly comparable with serverless $/M tokens | size workload before comparing |
| Managed A100/H100/H200/MI300 | Azure managed compute preview | hourly per accelerator; public pricing surface currently shows quote/calculator placeholders | dedicated compute | separate economics; scale-to-zero supported in preview |
| Provisioned throughput | Azure PTU | PTU/hour; minimum varies by model/deployment | serverless PAYG only comparable after workload sizing | do not assume older-model PTU minimums apply to V4 models |

For **Azure Direct models**, Microsoft documents Entra/RBAC, private networking and the Azure data/privacy boundary; prompts and outputs are not handed to the underlying model provider for training. **Fireworks-on-Foundry is different:** Microsoft identifies it as a non-Microsoft partner product, with customer data sent to Fireworks infrastructure and a different residency/privacy boundary.

Azure's public pricing pages still show calculator/quote placeholders for some V4/PTU/managed-GPU combinations. Those are marked **quote required**, not guessed. Azure also continues to advertise **$200 of new-account credit for 30 days**; Marketplace/model eligibility should be checked at deployment.

Sources: [Azure DeepSeek pricing announcement](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/introducing-deepseek-v4-flash-and-v4-pro-in-microsoft-foundry/4515174) · [DeepSeek V4 Flash catalog](https://ai.azure.com/catalog/models/DeepSeek-V4-Flash) · [Fireworks Kimi K2.7 Code](https://ai.azure.com/catalog/models/FW-Kimi-K2.7-Code) · [Azure model deployment options](https://learn.microsoft.com/en-us/azure/foundry/concepts/deployments-overview) · [Azure data/privacy](https://learn.microsoft.com/en-us/azure/foundry/responsible-ai/openai/data-privacy) · [Azure free account](https://azure.microsoft.com/en-us/pricing/purchase-options/azure-account)

## NEW MODELS / RELEASE WATCH

No new major coding flagship surfaced on the morning of **September 5**. The newest significant release remains **GLM-5.3-Flash**, officially released September 4 and revealed as the production identity of Ox Alpha. Muse Spark 1.3 (September 2) and OpenCode's Omen Alpha route remain the other recent additions.

Moonshot is also previewing a **Kimi K2.7 Code HighSpeed** variant internally, targeting roughly 5–6× higher generation speed. It is a watch item, not a generally available production endpoint yet.

## DIRECT CHINESE API PRICING / FIRST-PARTY SCAN

Today's CNY/USD reference is approximately **¥1 = $0.1490**.

| Vendor | Current first-party finding | Access Type |
|---|---|---|
| **DeepSeek** | V4 Flash/Vision **$0.22/$0.66 off-peak**, $0.44/$1.32 peak; cache hit $0.007 off-peak. V4 Pro $0.66/$1.98 off-peak. | **General OpenAI + Anthropic-compatible API** |
| **Alibaba / Qwen** | Qwen3.8 Flash Virginia **¥0.8/¥2.7 ≈ $0.119/$0.402**; 1M-class context. | **General API** |
| **Moonshot / Kimi** | K2.7 Code **$0.19 cache hit / $0.95 cache miss / $4 output**, 262K. | **General API** |
| **Z.ai / GLM** | AutoClaw new users currently get **100M GLM-5.3-Flash tokens**; ZCode new users get 5 days × 8M tokens/day. These are coding-agent/client offers, not unrestricted API credit. | Specific-client coding/agent |
| **MiniMax** | M3 direct ≤512K **$0.30/$1.20**, cache $0.06. China Plus Token Plan **¥49/mo**. | General API + separate specific-client plan |
| **Xiaomi / MiMo** | Lite **$6/mo**, first purchase 12% off; annual **$63.36 ($5.28/mo effective)**; 4.1B monthly credits. | Specific-client-only coding plan |
| **Tencent / Hunyuan** | China Hy Lite **¥28/mo (~$4.17)**; International Lite **$7/mo**. | Specific-client-only |
| **Baidu / Qianfan** | **Mini ¥4.9 first / ¥9.9 regular, 10M tokens; Lite ¥19.9 first / ¥40 regular, 42M. Dedicated Plan API key, OpenAI+Anthropic protocols.** | **Plan API / OpenAI+Anthropic-compatible** |
| **ByteDance / Doubao** | No new sub-$10 coding-plan promotion was cleanly re-verified today. | General API / separate plans |
| **StepFun** | AI Entry **¥39/mo (~$5.81)**, 1,300 credits; separate Step Plan API tiers exist but public numeric pricing was not exposed cleanly today. | Specific-client/hosted agent + separate API |
| **SenseTime / SenseNova** | Public beta remains **¥0**, 60,000 credits/5h, multimodal models, up to 20 API keys. | Plan API / agent endpoint |
| **01.AI / Yi** | **Public hosted model/API service ended Sep. 3 at 24:00 China time.** | Hosted API discontinued; open weights separate |

DeepSeek source: [current pricing](https://api-docs.deepseek.com/quick_start/pricing)

## FREE ACCESS

| Offer | Access Type | Current free capacity | Catch |
|---|---|---|---|
| **SenseNova public beta** | Plan API / agent endpoint | **¥0; 60K credits/5h** | public beta; paid tiers may replace it later |
| **OpenCode Muse Spark 1.3 Contributor Free** | Zen provider API | **$0** | **training permitted**; regional restrictions |
| **OpenRouter Pareto Code** | API/router | **$0** | route pool changes; provider limits apply |
| **OpenRouter North Mini Code Free** | General API | **$0** | upstream free-rate limits |
| **Z.ai AutoClaw** | Specific-client desktop agent | **100M GLM-5.3-Flash tokens for new users** | not general API credit |
| **Z.ai ZCode trial** | Specific-client coding endpoint | **5 days × 8M tokens/day** | coding endpoint only |
| Command Code Laguna / LongCat promos | Command Go = agent/CLI-only | **$0 model consumption during promo/capacity** | promotion/capacity can end |

A Reddit lead claims an even more generous ZCode GLM-5.3-Flash free period through September 20; the exact hours/date were **not verified on a first-party plan page**, so that claim is not treated as an entitlement here.

## LOW-COST SUBSCRIPTIONS

| Plan | Price | Access Type | Useful detail |
|---|---:|---|---|
| **Baidu Qianfan Mini** | **¥4.9 first / ¥9.9 regular (~$0.73/$1.48)** | **Plan API / OpenAI+Anthropic-compatible** | 10M tokens |
| **Command Code Go** | **$1/mo** | **Agent/CLI-only — NO API** | $10 credits; free promo models |
| **Baidu Qianfan Lite** | **¥19.9 first / ¥40 regular (~$2.97/$5.96)** | **Plan API / OpenAI+Anthropic-compatible** | 42M tokens |
| Tencent Hy Lite | **¥28 (~$4.17)** | Specific-client-only | 560 credits |
| **StepFun AI Entry** | **¥39 (~$5.81)** | Specific-client / hosted agent | 1,300 credits |
| **MiMo Lite** | **$6/mo** | Specific-client-only | annual $63.36 = $5.28/mo effective |
| Alibaba Lite | **¥39 (~$5.81)** | Specific-client-only | coding/agent tools |
| **MiniMax Plus** | **¥49 (~$7.30)** | Specific-client-only | annual ¥490 ≈ $6.08/mo effective |
| **Kimi Andante** | **¥49 (~$7.30)** | Specific-client-only | K2.7 Code membership coding endpoint |
| Tencent International Lite | **$7/mo** | Specific-client-only | 1,000 credits |
| Command Code GOAT | **$10/mo** | Agent/CLI + OpenAI/Anthropic-compatible API | $70 monthly credits |
| OpenCode Go | **$10/mo** | Provider/API for coding agents | broad curated model pool |

The classification matters: **Command Code Go remains agent/CLI-only and does not include Provider API access.** Kimi, MiniMax, MiMo, Tencent and many regional Token Plans may issue API-shaped keys, but when the vendor restricts them to approved coding/agent clients they are classified here as **specific-client-only**, not general backend APIs.

## BEST VALUE TODAY

**New deal to test first:** **Baidu Qianfan Mini**. The first-party price is finally re-confirmed: roughly **$0.73 first month / $1.48 regular for 10M tokens**, with a documented plan API key and OpenAI/Anthropic compatibility. Availability of the half-price first-buy inventory is limited, so the regular ¥9.9 price is the safer baseline.

**Best free private-ish coding capacity:** inside OpenCode Go, **GLM-5.3-Flash** remains attractive because of the 2× promo and documented ZDR/no-training. **Muse Spark 1.3 Contributor Free** is excellent $0 experimental capacity, but only for non-sensitive work because training is permitted.

**Best free general coding router:** **OpenRouter Pareto Code**. For a fixed free coding model, North Mini Code Free remains a useful purpose-built alternative.

**DeepSeek economics:** OpenRouter wins raw PAYG price on V4 Flash, but DeepSeek direct has an unusually cheap **$0.007/M cache-hit** rate. In long, heavily cached agent sessions, provider pinning and cache reuse can matter more than the lowest headline input price.

**Azure:** Azure Direct DeepSeek V4 Flash at **$0.19/$0.51** is genuinely competitive versus DeepSeek direct uncached off-peak, while adding Microsoft identity/networking/procurement controls. It is still materially more expensive than OpenRouter's cheapest route. For Kimi, remember that **K2.7 Code is Fireworks-on-Foundry**, while **K2.6 is the Azure-hosted Direct preview**.

For a stack that already has a capable coding subscription plus direct API access, today's best additions are **cheap/free capacity**, not another $20–$30 subscription.
