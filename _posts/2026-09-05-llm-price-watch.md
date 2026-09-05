---
layout: post
title: "LLM Price Watch — September 5, 2026"
date: 2026-09-05 07:56:00 -0400
summary: "Dots3 Note and MiniMax M3 add major free API options, Baidu Qianfan's sub-$2 Token Plan is first-party confirmed, OpenCode Go stays at 27 models, and Azure's Kimi K2.7 Code Direct-vs-Fireworks split is corrected."
---

## 🚨 Top changes today

| Change | Why it matters |
|---|---|
| **🔥 Dots3 Note Preview is free on OpenRouter through Sep. 30** | `dots-studio/dots-3-note-preview:free` is a **$0 API route**, 512K context, tools/structured output, aimed at reasoning, coding and agents. The provider page explicitly says the free preview goes away **September 30, 2026**. |
| **🔥 MiniMax M3 is FREE on Vercel AI Gateway today** | Vercel's first-party model page currently shows **Free** for `minimax/minimax-m3`, with OpenAI Chat Completions, Responses and Anthropic Messages compatibility plus OpenCode/Codex/Claude Code support. No expiry is stated on Vercel's page. |
| **🔥 Baidu Qianfan Mini: ¥4.9 first buy / ¥9.9 regular** | First-party Baidu promotion pages confirm **10M tokens**; that is roughly **$0.73 first buy / $1.48 regular**. Lite is ¥19.9 first buy / ¥40 regular for 42M tokens. |
| **Azure correction: Kimi K2.7 Code has BOTH a Direct-from-Azure route and Fireworks route** | The unprefixed `Kimi-K2.7-Code` catalog entry is **Moonshot AI, Direct from Azure, Preview**. `FW-Kimi-K2.7-Code` is a separate Fireworks-on-Foundry SKU with a different privacy/data-residency boundary. |
| **Azure also carries Kimi K3 via Fireworks** | `FW-Kimi-K3` is GA, 1M context, native vision, hosted on Fireworks infrastructure. This is useful access, but it is not Azure Direct. |
| **OpenCode Go remains at 27 models** | No new Go ID since yesterday. **GLM-5.3-Flash still has the 2× Go-usage promotion**, while Omen Alpha and Muse Spark 1.3 Contributor remain the newest additions. |
| **OpenCode DeepSeek ZDR footnote is still stale** | The Go privacy page still says the DeepSeek V4 Flash ZDR agreement was valid through **August 31, 2026**. Treat September ZDR as unconfirmed until OpenCode renews the footnote. |
| **01.AI / Yi public hosted API is now shut down** | 01.AI's announced cutoff was **September 3, 2026 at 24:00 China time**. Open weights/self-hosting remain separate from the discontinued hosted API. |

Sources: [OpenRouter Dots3 Note](https://openrouter.ai/dots-studio/dots-3-note-preview:free) · [Vercel MiniMax M3](https://vercel.com/ai-gateway/models/minimax-m3) · [Baidu Qianfan promo](https://cloud.baidu.com/theme/E/2509933-1) · [Azure Kimi K2.7 Code Direct](https://ai.azure.com/catalog/models/Kimi-K2.7-Code) · [Azure Fireworks K2.7](https://ai.azure.com/catalog/models/FW-Kimi-K2.7-Code) · [Azure Fireworks K3](https://ai.azure.com/catalog/models/FW-Kimi-K3)

## OpenCode Go

OpenCode Go remains **$10/month** and works as a provider with an API key for OpenCode or other agents. Base limits remain **$12/5h, $30/week and $60/month**. The current advertised lineup is 27 models. [OpenCode Go docs](https://dev.opencode.ai/docs/go/) · [Go landing page](https://dev.opencode.ai/go)

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
| Omen Alpha | $0.20 → $0.66 | 11,600 | image+text agent · ZDR | stealth identity unconfirmed |

\* Higher-context tiers differ. DeepSeek peak rates are 2× the off-peak rates shown.

**Privacy caution:** Muse Contributor access explicitly permits training use. DeepSeek is the oddity: OpenCode's table says 0-day retention, but its footnote still says the monthly ZDR agreement was valid only through **August 31**. For sensitive code, treat DeepSeek-on-Go September ZDR as unconfirmed.

## OPENCODE FREE / PREVIEW DEALS

The current documented Zen free list remains **seven models**. OpenCode does not publish one universal quota/context rule for all of them, so capacity should be treated as route-specific. [OpenCode Zen](https://dev.opencode.ai/docs/zen)

| Model / ID | Access Type | Cost | Modality / context | Limits / privacy / status |
|---|---|---:|---|---|
| `mimo-v2.5-free` | Zen provider API | **$0** | multimodal / large context | limited-time; feedback/model-improvement period |
| `ling-3.0-flash-fin-free` | Zen provider API | **$0** | coding/text | limited-time; feedback/model-improvement period |
| `nemotron-3-ultra-free` | Zen provider API | **$0** | text/agent | NVIDIA trial logging; avoid confidential work |
| `nemotron-3.5-lightning-free` | Zen provider API | **$0** | text/agent | NVIDIA trial logging; avoid confidential work |
| `big-pickle` | Zen provider API | **$0** | stealth | limited-time; feedback/model-improvement period |
| **`muse-spark-1.3-contributor-free`** | Zen provider API | **$0** | multimodal agent | **training permitted; Meta-region restrictions** |
| `muse-spark-1.2-contributor-free` | Zen provider API | **$0** | agent | **training permitted; Meta-region restrictions** |
| Ox Alpha Free | ended preview | — | became GLM-5.3-Flash | no longer a free preview ID |
| Hy3 Free | former route | — | — | no longer on current documented list |

Also active: **GPT-5.6 Sol is 50% off on Zen through September 18, 2026.**

**Reddit signal, unverified quota:** Muse Spark 1.3 Contributor Free users report anything from hundreds of millions of cached tokens to hitting a five-hour limit after roughly 400K–500K tokens, plus occasional 502s. The free route is official; exact user-observed limits are not.

## OPENROUTER DEALS

| Route | Access Type | Current price | Why it matters |
|---|---|---:|---|
| **Dots3 Note Preview Free** `dots-studio/dots-3-note-preview:free` | OpenAI-compatible API | **$0** | **512K context; expires Sep. 30; tools + structured output; coding/agents** |
| `openrouter/free` | OpenAI-compatible API/router | **$0** | capability-aware free routing; free-account daily limits apply |
| `openrouter/pareto-code` | OpenAI/Anthropic-compatible API/router | **$0** | 13 coding models, **2M context**, coding-quality routing |
| North Mini Code Free | General API | **$0** | 256K context, 64K max output, tools; coding-harness focused |
| **MiniMax M3 Free** | General API | **$0** | **1M**, text/image/video, tools; upstream rate limits can apply |
| **MiniMax M3 paid** | General API | **$0.24 → $0.96/M** | currently shown **60% off**, useful when the free route is throttled |
| **GLM-5.3-Flash** | General API | **$0.075 → $0.25/M** | **50% off**, 1.31M context |
| **DeepSeek V4 Flash 0731** | General API | **$0.05 → $0.16/M** | canonical raw-price leader; provider quality varies |

OpenRouter's free-model policy remains **50 free requests/day** for accounts below $10 lifetime purchased credits and **1,000/day** once at least $10 of credits has been purchased; individual upstream models can impose tighter limits. [OpenRouter limits](https://openrouter.ai/docs/faq)

Sources: [Dots3 Note Free](https://openrouter.ai/dots-studio/dots-3-note-preview:free) · [Pareto Code](https://openrouter.ai/openrouter/pareto-code) · [North Mini Code Free](https://openrouter.ai/cohere/north-mini-code:free) · [MiniMax M3 Free](https://openrouter.ai/minimax/minimax-m3:free) · [DeepSeek V4 Flash 0731](https://openrouter.ai/deepseek/deepseek-v4-flash-0731) · [Z.ai provider](https://openrouter.ai/provider/z-ai)

## FREE ACCESS OUTSIDE OPENCODE / OPENROUTER

| Offer | Access Type | Current deal | Expiry / caveat |
|---|---|---|---|
| **Vercel AI Gateway — MiniMax M3** | **OpenAI/Anthropic-compatible API gateway** | **FREE today** | First-party Vercel page states Free; **no expiry published there**. Reddit claims Sep. 6, but that date is unverified. |
| **SenseNova public beta** | Plan API / agent endpoint | **¥0; 60,000 credits/5h** | public beta; paid tiers coming later; up to 20 API keys |
| **Z.ai AutoClaw new-user grant** | Specific-client desktop agent | **100M GLM-5.3-Flash tokens** | new-user offer; not unrestricted backend API credit |
| **Command Code Laguna S 2.1** | Go = agent/CLI-only; API on higher tiers | **$0 model usage while capacity lasts** | promo/capacity dependent |
| **Command Code LongCat 2.0** | Go = agent/CLI-only; API on higher tiers | **$0 while it lasts** | promo/capacity dependent |
| Azure new-account credit | Azure services credit | **$200 / 30 days** | Foundry/Marketplace eligibility depends on deployment/offer |

[Vercel MiniMax M3](https://vercel.com/ai-gateway/models/minimax-m3) · [SenseNova Token Plan](https://www.sensenova.cn/en/token-plan)

## AZURE AI FOUNDRY COMPARISON

Azure needs to be split into **Direct from Azure**, **Fireworks-on-Foundry**, and **managed/provisioned compute**. They do not have the same data boundary or economics.

| Model | Azure route | Azure price / billing | Direct / other comparison | Take |
|---|---|---:|---|---|
| **DeepSeek V4 Flash** | **Direct from Azure serverless** | **$0.19 in / $0.51 out / $0.028 cache per M** | DeepSeek direct off-peak $0.22/$0.66/$0.007; OpenRouter canonical $0.05/$0.16 | Azure beats direct on uncached sticker price; direct wins cache; OR wins raw cost |
| **DeepSeek V4 Pro** | Direct from Azure serverless | **$1.74 / $3.48 / $0.145** | DeepSeek direct off-peak $0.66/$1.98/$0.022 | significant Azure premium |
| **Kimi K2.7 Code** | **Direct from Azure, Preview** | Azure pricing page currently renders `$-` in public crawl; portal/calculator required | Moonshot direct **$0.19 cache / $0.95 miss / $4 output** | **Correction:** Direct Azure route exists; good enterprise option if portal rate is acceptable |
| Kimi K2.7 Code | **Fireworks on Foundry, GA** | partner pay/token or PTU | same model family; separate Fireworks infrastructure | different privacy/residency; don't treat as Azure Direct |
| **Kimi K3** | **Fireworks on Foundry, GA** | partner pay/token/PTU | OpenCode Go $3/$15 sticker | Azure catalog access exists, but data leaves Microsoft systems |
| **MiniMax M3** | Fireworks on Foundry, GA | partner pay/token/PTU | OR/Vercel currently have free routes | Azure path is about governance/procurement, not cheapest testing |
| Qwen3.8-27B | open-weight catalog / managed deployment | managed compute | Qwen Cloud hosted API is separate | not apples-to-apples with token-priced serverless |
| Fireworks provisioned models | Azure provisioned throughput | PTU/hour or reservations | model-specific minimums/capacity | Kimi K2.7, Kimi K3-class routes, MiniMax M3, DeepSeek V4 and Qwen families require workload sizing |

**Direct Azure privacy:** Microsoft documents that Direct-from-Azure prompts/completions are not sent to the original model provider for training, and Azure supplies its normal identity/governance/private-networking controls. **Fireworks is explicitly different**: Microsoft states data is shared with Fireworks, leaves Microsoft systems and is not covered by Foundry's normal data-residency documentation.

**Azure billing watch — community report, not proven platform-wide:** a Microsoft Q&A user reported a DeepSeek V4 Flash cached-token meter billed at roughly **$10/M** versus Microsoft's published **$0.028/M** cache rate. Microsoft has not established this as a general pricing change. For a large Azure rollout, verify the Cost Management meter on a small deployment before scaling.

Sources: [Azure DeepSeek pricing](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/introducing-deepseek-v4-flash-and-v4-pro-in-microsoft-foundry/4515174) · [DeepSeek V4 Flash catalog](https://ai.azure.com/catalog/models/DeepSeek-V4-Flash) · [Kimi K2.7 Direct](https://ai.azure.com/catalog/models/Kimi-K2.7-Code) · [Kimi K2.7 Fireworks](https://ai.azure.com/catalog/models/FW-Kimi-K2.7-Code) · [Kimi K3 Fireworks](https://ai.azure.com/catalog/models/FW-Kimi-K3) · [Fireworks on Foundry](https://learn.microsoft.com/en-us/azure/foundry/how-to/fireworks/enable-fireworks-models) · [PTU sizing](https://learn.microsoft.com/en-us/azure/foundry/openai/how-to/provisioned-throughput-sizing)

### Azure catalog scan of the requested Chinese vendors

- **DeepSeek:** Azure Direct V4 Flash/Pro plus separate Fireworks SKUs.
- **Moonshot/Kimi:** Direct K2.5/K2.6/K2.7 Code entries plus Fireworks variants; Kimi K3 is surfaced via Fireworks.
- **Alibaba/Qwen:** open-weight Qwen3.8 catalog entries and Fireworks Qwen families; these are not the same as Alibaba's hosted Qwen Cloud API.
- **MiniMax:** MiniMax M3 is present via Fireworks.
- **Zhipu/GLM:** GLM open-weight/catalog and Fireworks routes are present; no Azure-Direct GLM-5.3-Flash token-priced SKU surfaced in today's scan.
- **Xiaomi/MiMo, Tencent/Hunyuan, Baidu/ERNIE, ByteDance/Doubao, StepFun, SenseNova, 01.AI/Yi:** no comparable **Azure Direct token-priced** endpoint surfaced in today's catalog scan. Open-weight artifacts may exist separately; that is not equivalent to an Azure serverless API.

## DIRECT CHINESE API PRICING / FIRST-PARTY SCAN

CNY conversions below use roughly **¥1 ≈ $0.149**.

| Vendor | Current first-party finding | Access Type |
|---|---|---|
| **DeepSeek** | V4 Flash/Vision **$0.22/$0.66 off-peak**, $0.44/$1.32 peak; cache hit **$0.007** off-peak. V4 Pro $0.66/$1.98 off-peak. | **General OpenAI + Anthropic-compatible API** |
| **Alibaba / Qwen** | Qwen3.8 Flash Virginia **¥0.8/¥2.7 ≈ $0.119/$0.402**. Qwen3.8 Max `0902` has a much tighter **150K TPM** limit in Virginia/Frankfurt/Tokyo than the high-capacity Asian regions. | **General API** |
| **Alibaba Token Plan** | Personal Lite is now **$6/mo promo ($8 list)**, 2,500 credits/7d, Singapore only; dedicated `sk-sp-` key + OpenAI/Anthropic-compatible Base URL. | **OpenAI/Anthropic-compatible subscription API — agent/coding plan** |
| **Moonshot / Kimi** | K2.7 Code **$0.19 cache / $0.95 cache miss / $4 output**, 262K. Kimi Code plans start above the $10 watch band globally. | **General API**; separate specific-client subscription |
| **Z.ai / GLM** | AutoClaw new users: **100M GLM-5.3-Flash tokens**; ZCode new-user trial remains separate coding-client capacity. | Specific-client coding/agent offers; general API separate |
| **MiniMax** | Current M3 Token Plan is **$20/mo Plus** (~1.7B M3 tokens/month); not a sub-$10 plan. | Specific-client Token Plan; general API separate |
| **Xiaomi / MiMo** | Lite remains **$6/mo** with MiMo V2.5 family and coding-agent integrations. | **Specific-client-only** Token Plan |
| **Tencent / Hunyuan** | Hy Lite remains **¥28/mo (~$4.17)**. Through Sep. 30, selected General Token Plan models including **Kimi K2.7 Code and MiniMax M3 consume 50% of normal credits**. | Specific-client subscription; TokenHub PAYG API separate |
| **Baidu / Qianfan** | **Mini ¥4.9 first buy / ¥9.9 regular, 10M tokens; Lite ¥19.9 / ¥40, 42M tokens.** | **Plan API / OpenAI+Anthropic-compatible** |
| **ByteDance / Doubao** | No fresh first-party sub-$10 offer was independently confirmed today; community/vendor-post leads about older Coding Plan promos remain checkout-unverified. | API + separate coding-plan products |
| **StepFun** | StepFun AI Entry **¥39/mo (~$5.81)** for 1,300 credits, StepClaw desktop/cloud and messaging integrations. | **Specific-client / hosted agent membership** |
| **SenseTime / SenseNova** | **¥0 public beta**, 60,000 credits/5h, 6.8 Flash Lite + U1 Fast, multimodal, up to 20 API keys. | **Plan API / agent endpoint** |
| **01.AI / Yi** | Public hosted model experience/API stopped **Sep. 3, 2026 24:00 China time**; refund window continues through Dec. 3. | **Hosted API discontinued**; open weights separate |

Sources: [DeepSeek pricing](https://api-docs.deepseek.com/quick_start/pricing/) · [Alibaba model pricing](https://www.alibabacloud.com/help/en/model-studio/model-pricing) · [Alibaba Token Plan](https://www.alibabacloud.com/help/en/model-studio/token-plan-overview) · [Kimi K2.7 Code](https://www.kimi.ai/resources/kimi-k2-7-code) · [MiniMax M3](https://www.minimax.io/blog/minimax-m3) · [Tencent September promo](https://cloud.tencent.com/document/product/1823/133811) · [Baidu Qianfan](https://cloud.baidu.com/theme/E/2509933-1) · [StepFun membership](https://www.stepfun.com/subscription) · [SenseNova Token Plan](https://www.sensenova.cn/en/token-plan)

## LOW-COST SUBSCRIPTIONS — $3–$10 WATCH

| Plan | Price | Access Type | Note |
|---|---:|---|---|
| **Baidu Qianfan Mini** | **~$0.73 first buy / $1.48 regular** | Plan API / OpenAI+Anthropic-compatible | below the normal watch band; 10M tokens |
| **Command Code Go** | **$1/mo** | **Agent/CLI-only — NO Provider API** | $10 monthly credits; some models currently free while capacity lasts |
| Tencent Hy Lite | **~$4.17/mo** | Specific-client-only | Hy4 Preview + Hy3 |
| **Alibaba Token Plan Lite** | **$6/mo promo** | OpenAI/Anthropic-compatible subscription API — agent/coding plan | Singapore; 2,500 credits/7d |
| **Xiaomi MiMo Lite** | **$6/mo** | Specific-client-only | MiMo V2.5 family; coding-agent integrations |
| **StepFun AI Entry** | **~$5.81/mo** | Specific-client / hosted agent | 1,300 credits + StepClaw |
| Tencent International Lite | **~$7/mo** | Specific-client-only | coding/OpenClaw plan |
| **Command Code GOAT** | **$10/mo** | **Agent/CLI + OpenAI/Anthropic-compatible Provider API** | $70 monthly usage; Provider API included |
| OpenCode Go | **$10/mo** | Provider/API for coding agents | existing broad curated model pool |

**Classification reminder:** Command Code **Go remains agent/CLI-only** and is the only Command Code plan without Provider API access; GOAT and higher tiers expose OpenAI/Anthropic-compatible Provider API access.

## NEW MODELS / RELEASE WATCH

No major new coding flagship launched on the morning of **September 5**. The newest meaningful production release remains **GLM-5.3-Flash** from September 4, now confirmed as the model previously tested anonymously as Ox Alpha. Today's more important market changes are **new/free access routes** rather than a brand-new flagship model.

Azure's catalog is nevertheless moving: **Kimi K3 is now prominent as a Fireworks-on-Foundry model**, while the separate **Direct-from-Azure Kimi K2.7 Code** entry corrects yesterday's overly narrow classification.

## 🏆 BEST VALUE TODAY

**Best zero-cost coding API to test first:** **Dots3 Note Preview Free on OpenRouter** if 512K context is enough. It has a known end date—**Sep. 30**—so it is exactly the kind of temporary deal worth using now.

**Best zero-cost 1M-context multimodal route:** **MiniMax M3**. You now have at least two current free surfaces: OpenRouter's M3 Free and **Vercel AI Gateway**, whose first-party page shows M3 as Free today. Vercel's page does not publish an expiry, so do not assume Reddit's Sep. 6 claim is guaranteed.

**Best free OpenCode-native experiment:** **Muse Spark 1.3 Contributor Free** if the code is non-sensitive and training use is acceptable. For private work inside Go, **GLM-5.3-Flash** remains more attractive because of the current **2× usage promo** and documented ZDR.

**Best ultra-cheap paid subscription:** **Baidu Qianfan Mini** at roughly **$1.48/month regular** (about $0.73 first buy) is now the standout first-party-confirmed price. The tradeoff is China-region onboarding/availability rather than cost.

**Best raw DeepSeek V4 Flash price:** OpenRouter's canonical route at **$0.05/$0.16/M** remains far below Azure Direct or DeepSeek direct. **Azure Direct at $0.19/$0.51** is compelling when Entra/RBAC, private networking, Microsoft procurement and the Azure data boundary are worth more than the raw token spread.

**Best correction to yesterday's Azure view:** Kimi K2.7 Code is **not Fireworks-only** in Foundry. There is a Direct-from-Azure preview route and a separate Fireworks route. For proprietary code, that distinction matters more than a few cents of model pricing.
