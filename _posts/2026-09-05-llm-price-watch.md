---
layout: post
title: "LLM Price Watch — September 5, 2026"
date: 2026-09-05 07:56:00 -0400
summary: "Dots3 Note and MiniMax M3 add major free API options, Baidu Qianfan's sub-$2 Token Plan is first-party confirmed, OpenCode Go stays at 27 models, and Azure's Kimi K2.7 Code Direct-vs-Fireworks split is clarified."
---

## 🚨 Top changes today

| Change | Why it matters |
|---|---|
| **🔥 Dots3 Note Preview is free through Sep. 30** | OpenRouter's `dots-studio/dots-3-note-preview:free` is $0, 512K context, text+image, tools and structured output. The provider explicitly says it goes away **September 30, 2026**. |
| **🔥 MiniMax M3 is free on Vercel AI Gateway** | Vercel currently shows `minimax/minimax-m3` as **Free**, with 1M context, native multimodality, API access and support for OpenCode/Codex/Claude Code. No expiry is published on Vercel's page. |
| **🔥 Baidu Qianfan Mini is ¥4.9 first buy / ¥9.9 regular** | First-party Baidu material confirms **10M tokens**. Lite is ¥19.9 first buy / ¥40 regular for 42M tokens. |
| **Azure Kimi classification clarified** | Kimi K2.7 Code has a **Direct from Azure Preview** route *and* a separate **Fireworks-on-Foundry GA** route. They have different data/privacy boundaries. |
| **Azure also carries Kimi K3 through Fireworks** | Kimi K3 is GA via Fireworks, with native vision and a 1M context window. It is not an Azure Direct model. |
| **OpenCode Go remains 27 models** | No new Go model ID today. GLM-5.3-Flash retains its **2× usage** promotion; Omen Alpha and Muse Spark 1.3 Contributor remain the newest additions. |
| **OpenCode DeepSeek ZDR footnote is still stale** | Current Go docs still say the DeepSeek ZDR agreement was valid through **August 31, 2026**. Treat September ZDR as unconfirmed despite the table showing 0-day retention. |
| **01.AI / Yi hosted API has ended** | The announced public hosted API/model-experience cutoff was **September 3, 2026 24:00 China time**. Open weights/self-hosting are separate. |

Sources: [OpenRouter Dots3 Note](https://openrouter.ai/dots-studio/dots-3-note-preview:free) · [Vercel MiniMax M3](https://vercel.com/ai-gateway/models/minimax-m3) · [Baidu Qianfan promotion](https://cloud.baidu.com/theme/E/2509933-1) · [Azure Kimi K2.7 Direct](https://ai.azure.com/catalog/models/Kimi-K2.7-Code) · [Azure Kimi K2.7 Fireworks](https://ai.azure.com/catalog/models/FW-Kimi-K2.7-Code) · [Azure Kimi K3 Fireworks](https://ai.azure.com/catalog/models/FW-Kimi-K3)

## OpenCode Go

OpenCode Go remains **$10/month** with base pools of **$12/5h, $30/week and $60/month**. It provides an API key/provider endpoint intended for OpenCode and compatible coding agents. [OpenCode Go](https://dev.opencode.ai/docs/go/) · [Go landing page](https://dev.opencode.ai/go)

| Model | Input → output / M | Est. req/5h | Modality / privacy | Change |
|---|---:|---:|---|---|
| Grok 4.6 | $2 → $6 | 169 | agent · 30d | — |
| GPT-5.6 Luna | $0.20 → $1.20* | 2,050 | vision/text · 30d | — |
| **GLM-5.3-Flash** | **$0.15 → $0.50** | 1,580 base | native multimodal · ZDR | **2× promo** |
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
| Muse Spark 1.3 Contributor | $0.10 → $0.20 | **45,300** | multimodal/agent · **TRAINING YES** | — |
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

### Privacy caution

Muse Contributor routes explicitly permit training use. OpenCode lists DeepSeek as 0-day retention but still says its ZDR agreement was valid through August 31, so sensitive September DeepSeek workloads should treat ZDR as **unconfirmed** until that footnote rolls forward.

## OPENCODE FREE / PREVIEW DEALS

The documented Zen free list remains seven models. [OpenCode Zen](https://dev.opencode.ai/docs/zen)

| Model / ID | Access Type | Cost | Modality / status | Privacy / limits |
|---|---|---:|---|---|
| `mimo-v2.5-free` | Zen provider API | **$0** | multimodal | limited-time feedback/model-improvement period |
| `ling-3.0-flash-fin-free` | Zen provider API | **$0** | coding/text | limited-time feedback/model-improvement period |
| `nemotron-3-ultra-free` | Zen provider API | **$0** | text/agent | NVIDIA trial logging |
| `nemotron-3.5-lightning-free` | Zen provider API | **$0** | text/agent | NVIDIA trial logging |
| `big-pickle` | Zen provider API | **$0** | stealth | limited-time feedback/model-improvement period |
| **`muse-spark-1.3-contributor-free`** | Zen provider API | **$0** | multimodal/agent | **training permitted; regional restrictions** |
| `muse-spark-1.2-contributor-free` | Zen provider API | **$0** | agent | **training permitted; regional restrictions** |
| Ox Alpha Free | ended preview | — | became GLM-5.3-Flash | no longer a free preview ID |
| Hy3 Free | former route | — | removed from current documented free list | — |

Also active: **GPT-5.6 Sol is 50% off on Zen through September 18, 2026.**

Reddit reports on Muse 1.3 Contributor Free show wildly different effective quotas plus occasional 502s. Treat the free route as confirmed but community-observed limits as **unverified**.

## OPENROUTER DEALS

| Route | Access Type | Current price | Why it matters |
|---|---|---:|---|
| **Dots3 Note Preview Free** | OpenAI-compatible API | **$0** | **512K**, text+image, tools/structured output; **ends Sep. 30** |
| `openrouter/free` | OpenAI-compatible API/router | **$0** | capability-aware rotating free pool |
| `openrouter/pareto-code` | OpenAI/Anthropic-compatible API/router | **$0** | 13 coding models, **2M context** |
| North Mini Code Free | General API | **$0** | 256K, 64K max output, tools; coding-harness focused |
| **MiniMax M3 Free** | General API | **$0** | **1M**, text/image/video, tools |
| **MiniMax M3 paid** | General API | **~$0.23–$0.24 → $0.96/M** | cheap fallback when free capacity throttles |
| **GLM-5.3-Flash** | General API | **$0.075 → $0.25/M** | 50%-off route |
| **DeepSeek V4 Flash 0731** | General API | **$0.05 → $0.16/M** | raw-cost leader; provider quality matters |

Sources: [Dots3 Note](https://openrouter.ai/dots-studio/dots-3-note-preview:free) · [MiniMax M3 Free](https://openrouter.ai/minimax/minimax-m3:free) · [MiniMax provider page](https://openrouter.ai/minimax) · [Pareto Code](https://openrouter.ai/openrouter/pareto-code)

## FREE ACCESS OUTSIDE OPENCODE / OPENROUTER

| Offer | Access Type | Current deal | Caveat |
|---|---|---|---|
| **Vercel AI Gateway — MiniMax M3** | **OpenAI/Anthropic-compatible API gateway** | **FREE today** | Vercel publishes no expiry on its current model page |
| **SenseNova public beta** | Plan API / agent endpoint | **¥0; 60,000 credits/5h** | paid tiers coming later; up to 20 API keys |
| **Z.ai AutoClaw new-user grant** | specific-client desktop agent | **100M GLM-5.3-Flash tokens** | not unrestricted backend API credit |
| **Command Code Laguna S 2.1** | Go agent/CLI; API on GOAT+ | **$0 while capacity lasts** | requires account/credits to start session |
| **Command Code LongCat 2.0** | Go agent/CLI; API on GOAT+ | **$0 while it lasts** | 1M context |
| Azure new-account credit | Azure services credit | **$200 / 30 days** | model/Marketplace eligibility varies |

Sources: [Vercel MiniMax M3](https://vercel.com/ai-gateway/models/minimax-m3) · [SenseNova Token Plan](https://www.sensenova.cn/en/token-plan) · [Command Code pricing](https://commandcode.ai/docs/resources/pricing-limits)

## AZURE AI FOUNDRY COMPARISON

Azure should be split into **Direct from Azure**, **partner inference such as Fireworks**, and **managed/provisioned compute**. These are not interchangeable.

| Model | Azure route | Azure price / billing | Direct / aggregator comparison | Take |
|---|---|---:|---|---|
| **DeepSeek V4 Flash** | **Direct from Azure serverless** | **$0.19 in / $0.51 out / $0.028 cache per M** | DeepSeek direct off-peak $0.22/$0.66/$0.007; OpenRouter $0.05/$0.16 | Azure beats direct uncached; direct wins cache; OR wins raw cost |
| **DeepSeek V4 Pro** | Direct from Azure serverless | **$1.74 / $3.48 / $0.145** | DeepSeek direct off-peak $0.66/$1.98/$0.022 | substantial Azure premium |
| **Kimi K2.7 Code** | **Direct from Azure, Preview** | public crawl currently points to portal/calculator rather than a stable numeric table | Moonshot direct $0.19 cache / $0.95 miss / $4 output | Direct Azure route is real; enterprise option |
| Kimi K2.7 Code | **Fireworks on Foundry, GA** | partner pay/token or PTU | same model family | separate Fireworks data boundary |
| **Kimi K3** | **Fireworks on Foundry, GA** | partner pay/token/PTU | OpenCode Go $3/$15 sticker | 1M + vision, but not Azure Direct |
| MiniMax M3 | Fireworks on Foundry | partner pay/token/PTU | OpenRouter/Vercel currently have free routes | governance/procurement route, not cheapest testing |
| Qwen/open-weight models | managed deployment | GPU/endpoint compute | not equivalent to hosted Qwen API $/token | size workload first |
| Fireworks provisioned models | Azure provisioned throughput | PTU / reservation | model/region minimums vary | use calculator/portal; don't guess PTU economics |

Microsoft says models **sold by Azure** keep prompts/outputs unavailable to the original provider and do not use them to train provider foundation models without permission. Fireworks-on-Foundry is explicitly a **non-Microsoft product**: customer data is sent outside Microsoft systems and Foundry's standard residency commitments do not apply. Fireworks Data Zone deployments are currently listed in East US, East US 2, Central US, North Central US, West US and West US 3; Fireworks also supports provisioned throughput. [Azure data/privacy](https://learn.microsoft.com/en-us/azure/foundry/responsible-ai/openai/data-privacy) · [Fireworks on Foundry](https://learn.microsoft.com/en-us/azure/foundry/how-to/fireworks/enable-fireworks-models)

### Azure catalog scan — requested Chinese vendors

| Vendor | Azure status today |
|---|---|
| DeepSeek | Azure Direct V4 Flash/Pro plus partner options |
| Moonshot/Kimi | Direct K2.7 Code preview plus Fireworks K2.7; K3 via Fireworks |
| Alibaba/Qwen | open-weight/managed and partner catalog options; not the same as Qwen Cloud PAYG |
| Zhipu/GLM | catalog/partner routes exist; no comparable Azure-Direct GLM-5.3-Flash PAYG SKU surfaced today |
| MiniMax | M3 via Fireworks |
| Xiaomi/MiMo | no comparable Azure Direct token-priced endpoint surfaced |
| Tencent/Hunyuan | no comparable Azure Direct token-priced endpoint surfaced |
| Baidu/ERNIE | no comparable Azure Direct token-priced endpoint surfaced |
| ByteDance/Doubao | no comparable Azure Direct token-priced endpoint surfaced |
| StepFun | no comparable Azure Direct token-priced endpoint surfaced |
| SenseTime/SenseNova | no comparable Azure Direct coding-model endpoint surfaced |
| 01.AI/Yi | no comparable current Azure Direct hosted Yi API surfaced |

## DIRECT CHINESE API PRICING / FIRST-PARTY SCAN

| Vendor | Current first-party finding | Access Type |
|---|---|---|
| **DeepSeek** | V4 Flash/Vision **$0.22/$0.66 off-peak**, peak 2×; Pro **$0.66/$1.98 off-peak**; low cache-hit rates remain a major direct advantage | **General OpenAI + Anthropic-compatible API** |
| **Alibaba/Qwen** | Qwen3.8 Flash **$0.15/$0.47**, 1M context; Qwen3.8 Max/0902 Virginia **$1.65/$4.951** | **General API** |
| **Alibaba Token Plan** | Lite **$6/mo promo ($8 list)**, Singapore-only, 2,500 Credits/7d | **OpenAI/Anthropic-compatible subscription API — agent/coding plan** |
| **Moonshot/Kimi** | K2.7 Code **¥1.3 cache hit / ¥6.5 input / ¥27 output per MTok** on current China platform (~$0.19/$0.97/$4.02); 256K | **General API** |
| **Z.ai/GLM** | GLM-5.3-Flash remains the newest flagship release; large AutoClaw/ZCode introductory capacity remains the notable deal | general API + separate client plans |
| **MiniMax** | M3 API is live with long-context tiering; current Token Plan Plus is $20/mo globally, above this watch's sub-$10 band | General API + specific-client plan |
| **Xiaomi/MiMo** | Lite **$6/mo / ¥39**, **4.1B Credits**, six MiMo V2.5-family models; OpenCode/Codex/Claude Code integration | **Specific-client-only Token Plan** |
| **Tencent/Hunyuan** | Sep. 1–30: Kimi K2.7 Code and MiniMax M3 consume **50%** of standard Token Plan credits; Hy Lite remains a low-cost China plan | Specific-client plan; PAYG API separate |
| **Baidu/ERNIE/Qianfan** | **Mini ¥4.9 first buy / ¥9.9 regular (10M tokens); Lite ¥19.9 / ¥40 (42M)** | **Plan API / OpenAI+Anthropic-compatible** |
| **ByteDance/Doubao** | no fresh first-party sub-$10 coding-plan checkout was independently confirmed today | API + separate client products |
| **StepFun** | Entry **¥39/mo**, 1,300 credits, StepClaw desktop/cloud + messaging | **Specific-client / hosted agent** |
| **SenseTime/SenseNova** | **¥0 public beta**, 60,000 credits/5h, multimodal models, up to 20 API keys | **Plan API / agent endpoint** |
| **01.AI/Yi** | public hosted API/model experience discontinued Sep. 3; open weights remain separate | **Hosted API discontinued** |

Sources: [DeepSeek updates/pricing](https://api-docs.deepseek.com/updates/) · [Alibaba model pricing](https://www.alibabacloud.com/help/en/model-studio/model-pricing) · [Alibaba Token Plan](https://www.alibabacloud.com/help/en/model-studio/token-plan-overview) · [Kimi platform](https://test-platform.kimi.com/) · [MiniMax M3](https://www.minimax.io/blog/minimax-m3) · [MiMo Token Plan](https://mimo.mi.com/docs/en-US/price/token-plan) · [Tencent September promo](https://cloud.tencent.com/document/product/1823/133811) · [Baidu Qianfan](https://cloud.baidu.com/theme/E/2509933-1) · [StepFun](https://www.stepfun.com/subscription) · [SenseNova](https://www.sensenova.cn/en/token-plan)

## LOW-COST SUBSCRIPTIONS — $3–$10 WATCH

| Plan | Price | Access Type | Note |
|---|---:|---|---|
| **Baidu Qianfan Mini** | ~**$0.73 first buy / $1.48 regular** | Plan API / OpenAI+Anthropic-compatible | below normal watch band; 10M tokens |
| **Command Code Go** | **$1/mo** | **Agent/CLI-only — NO Provider API** | $10 monthly credits |
| Tencent Hy Lite | ~**$4.17/mo** | specific-client-only | China plan |
| **StepFun AI Entry** | ~**$5.81/mo** | specific-client / hosted agent | 1,300 credits + StepClaw |
| **Alibaba Token Plan Lite** | **$6/mo promo** | OpenAI/Anthropic-compatible subscription API — agent/coding plan | Singapore; 2,500 Credits/7d |
| **Xiaomi MiMo Lite** | **$6/mo** | specific-client-only | 4.1B Credits; MiMo V2.5 family |
| Tencent International Lite | ~**$7/mo** | specific-client-only | international coding/agent plan |
| **Command Code GOAT** | **$10/mo** | **Agent/CLI + OpenAI/Anthropic-compatible Provider API** | $70 monthly credits; $14/5h, $35/week |
| OpenCode Go | **$10/mo** | provider/API for coding agents | existing 27-model pool |

**Command Code classification:** Go is the **only** Command Code plan without Provider API access. GOAT and higher plans can call its OpenAI/Anthropic-compatible Provider API; the separate $15 Provider plan is optimized for pay-as-you-go API traffic. [Command Code Provider API](https://commandcode.ai/docs/provider)

## NEW MODELS / RELEASE WATCH

No major new coding flagship launched on the morning of **September 5**. The newest important production release remains **GLM-5.3-Flash** from September 4, the production identity of the former Ox Alpha preview. Today's more important changes are **new/free routes and catalog availability**, especially Dots3 Note Free, Vercel MiniMax M3 Free, and Azure's Direct-vs-Fireworks Kimi split.

## 🏆 BEST VALUE TODAY

**Best zero-cost coding API:** **Dots3 Note Preview Free** if 512K context is enough. Its Sep. 30 end date makes it a use-now deal.

**Best zero-cost 1M multimodal route:** **MiniMax M3**, currently free on both OpenRouter and Vercel AI Gateway. Vercel does not state an expiry on its first-party page.

**Best free OpenCode-native experiment:** **Muse Spark 1.3 Contributor Free** for non-sensitive code where training use is acceptable. For private work inside Go, **GLM-5.3-Flash** is more attractive because of the 2× usage promo and documented no-training posture.

**Best ultra-cheap paid plan:** **Baidu Qianfan Mini** is now the standout first-party-confirmed sticker price, with China-region onboarding/availability as the practical tradeoff.

**Best raw DeepSeek V4 Flash price:** OpenRouter's canonical low-cost route remains far below Azure Direct or DeepSeek direct. **Azure Direct** makes sense when Microsoft procurement, Entra/RBAC, private networking and the Azure data boundary are worth the token-price premium.
