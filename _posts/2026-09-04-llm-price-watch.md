---
layout: post
title: "LLM Price Watch — September 4, 2026"
date: 2026-09-04 08:27:00 -0400
summary: "GLM-5.3-Flash officially launches and reveals Ox Alpha, OpenCode Go reaches 27 models, Pareto Code is a standout free router, and Azure DeepSeek pricing gets an enterprise-vs-raw-cost comparison."
---

## 🚨 Top changes today

| Change | Why it matters |
|---|---|
| **GLM-5.3-Flash officially launched today** | Z.ai confirmed the old anonymous **Ox Alpha** test was GLM-5.3-Flash. It is a 320B/18B-active native multimodal model with text, image, video and file understanding. |
| **OpenCode Go is now 27 models** | **Muse Spark 1.3 Contributor** and **Omen Alpha** are in the current lineup. Muse is extremely cheap but permits training; Omen is a high-volume new route. |
| **GLM-5.3-Flash gets 2× Go usage for a limited time** | OpenCode explicitly advertises a temporary 2× usage promotion on the model. |
| **DeepSeek ZDR documentation is still stale** | OpenCode's current Go docs still say its DeepSeek ZDR agreement is valid through **August 31, 2026**. Treat September ZDR as unconfirmed. |
| **OpenRouter Pareto Code is a sleeper $0 coding route** | `openrouter/pareto-code` costs **$0**, routes among 13 coding models and exposes a **2M context** window. |
| **Azure DeepSeek Flash beats DeepSeek direct on uncached off-peak tokens** | Azure is **$0.19/$0.51/M** vs DeepSeek direct **$0.22/$0.66/M** off-peak; OpenRouter still wins raw cost at **$0.05/$0.16/M**. |
| **Alibaba has another DeepSeek price anomaly** | Alibaba Model Studio's US/global route lists DeepSeek V4 Flash at **$0.14/$0.28/M**, cheaper than Azure and DeepSeek direct, though it is an Alibaba-hosted route rather than DeepSeek's own API. |
| **GPT-6 Astra: Azure Global = OpenAI list price** | Azure Standard Global is **$10 input / $1 cached / $12.50 cache-write / $50 output per M**; U.S. Data Zone is 10% higher. |

## OpenCode Go

OpenCode Go remains **$10/month**, with an API key/provider endpoint designed for OpenCode and similar coding agents. Base limits remain **$12/5h, $30/week and $60/month**. OpenCode says traffic must identify the coding tool correctly and may be monitored for abuse.

| Model | Input → output / M | Est. req/5h | Modality / privacy | Change |
|---|---:|---:|---|---|
| Grok 4.6 | $2 → $6* | 169 | text/agent · 30d | — |
| GPT-5.6 Luna | $0.20 → $1.20* | 2,050 | vision/text · 30d | — |
| **GLM-5.3-Flash** | **$0.15 → $0.50** | 1,580 base | **native multimodal/agent · ZDR** | **2× Go promo; official launch today** |
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
| **Omen Alpha** | catalog ~$0.20 → $0.66 | **11,600** | agent · ZDR | **NEW** |

\* Higher-context tiers differ. DeepSeek peak rates are 2× the off-peak rates shown.

Sources: [OpenCode Go docs](https://dev.opencode.ai/docs/go/) and [OpenCode Go landing page](https://dev.opencode.ai/go).

## OPENCODE FREE / PREVIEW DEALS

The **current documented Zen free list is seven models**. A cached `/models` snapshot contains additional free-looking IDs, but it is stale; those extra routes are no longer treated as confirmed live deals unless current docs or a fresh request verifies them.

| Model / ID | Access Type | Cost | Context / modality | Limits / privacy / status |
|---|---|---:|---|---|
| `mimo-v2.5-free` | Zen provider API | **$0** | ~1M / multimodal | limited-time; free-period data may improve model |
| `ling-3.0-flash-fin-free` | Zen provider API | **$0** | coding/text | limited-time; free-period data may improve model |
| `nemotron-3-ultra-free` | Zen provider API | **$0** | text/agent | limited-time NVIDIA trial logging |
| `nemotron-3.5-lightning-free` | Zen provider API | **$0** | text/agent | limited-time NVIDIA trial logging |
| `big-pickle` | Zen provider API | **$0** | stealth | limited-time; data may improve model |
| `muse-spark-1.3-contributor-free` | Zen provider API | **$0** | multimodal/agent | **training permitted; limited Meta regions** |
| `muse-spark-1.2-contributor-free` | Zen provider API | **$0** | agent | **training permitted; limited Meta regions** |
| **Ox Alpha Free** | preview route | — | now identified | **preview ended; revealed Sep. 4 as GLM-5.3-Flash** |
| Cached extras such as `deepseek-v4-flash-free` / `laguna-s-2.1-free` | opportunistic | $0-looking | undocumented | **not confirmed by current public Zen docs; verify before relying** |

Source: [OpenCode Zen pricing/privacy](https://dev.opencode.ai/docs/zen).

## OPENROUTER DEALS

| Route | Access Type | Current price | Why it matters |
|---|---|---:|---|
| `openrouter/free` | OpenAI-compatible API/router | **$0** | capability-aware free routing across a rotating free pool |
| **`openrouter/pareto-code`** | OpenAI/Anthropic-compatible API/router | **$0** | **13 coding models, 2M context; High tier by default, Nitro can favor speed** |
| North Mini Code Free | General API | **$0** | 256K, 64K max output, tools; trained for OpenCode/SWE-Agent-style harnesses |
| MiniMax M3 Free | General API | **$0** | **1M**, text/image/video, tools; free endpoints are rate limited |
| **GLM-5.3-Flash** | General API | **$0.075 → $0.25/M** | **50% off**, 1M+ context; official model released today |
| **DeepSeek V4 Flash 0731** | General API | **$0.05 → $0.16/M** | raw-price leader; OpenInference route; 1M+ context |
| Kimi K2.7 Code | General API | **$0.66 → $3.40/M** | cheaper than Moonshot direct; 262K, image+text, tools |
| DeepSeek V4 Pro | General API | about **$0.58 → $1.74/M headline** | below DeepSeek direct off-peak sticker rate |

**Community reliability note:** Reddit reports on MiniMax M3 Free continue to mention 429s/overload and conflicting promo-expiry dates. The endpoint is officially free today; specific expiry claims remain **unverified community reports**.

Sources: [Pareto Code Router](https://openrouter.ai/openrouter/pareto-code), [North Mini Code Free](https://openrouter.ai/cohere/north-mini-code:free), [MiniMax M3 Free](https://openrouter.ai/minimax/minimax-m3:free), [DeepSeek V4 Flash 0731](https://openrouter.ai/deepseek/deepseek-v4-flash-0731), [Z.ai on OpenRouter](https://openrouter.ai/provider/z-ai), [Kimi K2.7 Code](https://openrouter.ai/moonshotai/kimi-k2.7-code).

## AZURE AI FOUNDRY COMPARISON

Azure's catalog is broad, but **catalog presence does not mean every model is a Microsoft-hosted, token-priced serverless API**. The important split is Azure Direct vs Fireworks/partner inference vs managed compute/PTU.

| Model | Azure offer | Azure price / billing | Best comparison | Take |
|---|---|---:|---|---|
| **GPT-6 Astra** | Azure Direct, Standard Global | **$10 input / $1 cached / $12.50 write / $50 output per M** | OpenAI direct is the same raw rate | **price tie; Azure adds enterprise controls** |
| GPT-6 Astra US Data Zone | Azure Direct, Standard | **$11 / $1.10 / $13.75 / $55** | OpenAI $10/$50 | +10% for U.S. processing boundary |
| **DeepSeek V4 Flash** | Azure Direct serverless | **$0.19 → $0.51/M; cache $0.028** | DeepSeek direct off-peak $0.22/$0.66; Alibaba $0.14/$0.28; OR $0.05/$0.16 | Azure beats direct uncached; OR raw-cost winner |
| **DeepSeek V4 Pro** | Azure Direct serverless | **$1.74 → $3.48/M; cache $0.145** | DeepSeek direct off-peak $0.66/$1.98 | Azure premium is large |
| Kimi K2.7 Code | **Fireworks on Foundry** | pay/token + PTU; public numeric rate may require calculator/quote | OpenRouter $0.66/$3.40; Moonshot $0.95/$4 | availability is useful; privacy boundary differs |
| MiniMax M3 | **Fireworks on Foundry** | pay/token/PTU; quote surface varies | OpenRouter free currently | Azure route is for governance/procurement, not cheapest experimentation |
| GLM-5.2 | Fireworks on Foundry | pay/token + PTU | direct/OpenRouter vary | Azure currently trails today's GLM-5.3-Flash release |
| Qwen3.8-27B | open-weight catalog / managed deployment | **managed compute, not token API equivalent** | Qwen Cloud hosted API is separate | do not compare GPU rental directly to $/M tokens |

### Azure privacy boundary matters

For **Azure Direct Models**, Microsoft says prompts, outputs and training data are **not shared with the model provider** and are not used to train foundation models without permission. That can justify paying more for proprietary code, Entra/RBAC, private networking, regional controls and consolidated Azure procurement.

**Fireworks on Foundry is different.** Microsoft explicitly says customer data is shared with Fireworks, sent outside Microsoft systems, and is **not covered by Foundry data-residency documentation**. Kimi K2.7 Code and MiniMax M3 currently carry that disclosure. This is an important distinction when comparing “Azure-hosted” model access.

Azure's public pricing pages still show `$-` for some third-party/PTU/managed-compute rows; those should be treated as **calculator/quote required**, not guessed. Azure continues to advertise **$200 of new-account credit for 30 days**, but marketplace/model eligibility should be verified per deployment.

Sources: [Azure DeepSeek pricing](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/introducing-deepseek-v4-flash-and-v4-pro-in-microsoft-foundry/4515174), [Azure Direct Models privacy](https://learn.microsoft.com/en-us/azure/foundry/responsible-ai/openai/data-privacy), [Fireworks on Foundry](https://learn.microsoft.com/en-us/azure/foundry/how-to/fireworks/enable-fireworks-models), [Kimi K2.7 Code catalog](https://ai.azure.com/catalog/models/FW-Kimi-K2.7-Code), [Qwen3.8-27B catalog](https://ai.azure.com/catalog/models/qwen--qwen3.8-27b), [Astra on Foundry](https://azure.microsoft.com/en-us/blog/gpt-6-astra-frontier-intelligence-for-work-now-available-in-microsoft-foundry/).

## NEW MODELS

### 🔥 GLM-5.3-Flash — released September 4

Z.ai says GLM-5.3-Flash is its first **natively multimodal GLM-5** model: **320B total / 18B active parameters**, hybrid sparse + linear attention, up to million-token-class context, and training on a 30T-token multimodal corpus. It supports text, images, video and files. Z.ai also confirmed the pre-release model was anonymously evaluated as **Ox Alpha** under real production traffic and served on Chinese AI accelerators. Weights are published under MIT.

Source: [Z.ai / AutoClaw release](https://autoclaw.z.ai/blog/model/glm-5.3-flash/).

### GPT-6 Astra — released September 3

OpenAI's current API list rate is **$10/M input, $1/M cached input, $12.50/M cache write and $50/M output**, with a 1.05M context window and higher rates above 272K input. Azure Global Standard matches the raw token price. Existing ChatGPT paid plans are expected to receive Astra as rollout reaches their tier, so adding another OpenAI subscription solely to test it is not attractive.

## DIRECT CHINESE API PRICING / FIRST-PARTY SCAN

| Vendor | Current first-party finding | Access Type |
|---|---|---|
| **DeepSeek** | V4 Flash **$0.22/$0.66 off-peak**, $0.44/$1.32 peak; cache hit $0.007 off-peak. V4 Pro $0.66/$1.98 off-peak. | **General OpenAI + Anthropic-compatible API** |
| **Alibaba/Qwen** | Qwen3.8 Max / `0902` global **$1.65/$4.951**; Qwen3.8 Flash Singapore **$0.15/$0.47**. Alibaba's US/global DeepSeek V4 Flash route is **$0.14/$0.28**. | **General PAYG API** |
| **Moonshot/Kimi** | Kimi K2.7 Code direct **$0.95/$4**, cache $0.19; OpenRouter currently undercuts it. | **General API** |
| **Z.ai/GLM** | **GLM-5.3-Flash launched today**; direct first-party numeric list price was not cleanly re-verified in the public pricing surface this morning. | General API / hosted model |
| **MiniMax** | PAYG M2.7 **$0.30/$1.20**; docs still list a **$10 Starter** Token Plan for M2.7, while the current M3 subscription storefront emphasizes $20+ plans. | General API + separate specific-client Token Plan |
| **Xiaomi/MiMo** | Lite **$6/mo**, 4.1B credits; **12% first purchase (~$5.28)**; 0.8× night consumption; no 5-hour cap. | **Specific-client coding plan**; PAYG API separate |
| **Tencent/Hunyuan** | Hy Lite **¥28/mo**, General Lite **¥39/mo**. | **Specific-client-only** personal plans; backend/automation use prohibited |
| **Baidu/Qianfan** | Mini **¥4.9 first buy / ¥9.9 regular, 10M tokens**; Lite **¥19.9 / ¥40, 42M**; dedicated compatible plan API. | **Plan API / OpenAI + Anthropic-compatible** |
| **ByteDance/Doubao** | Seed Code PAYG: **¥1.2/M input + ¥8/M output** at 0–32K, rising by context tier; Coding Plan Lite is **¥9.9 first month / ¥40 renewal**. | General Ark API; Coding Plan is **specific-client-only** |
| **StepFun** | Entry **¥39/mo**, 1,300 credits; StepClaw desktop/cloud. | **Hosted app/agent membership**, not general API |
| **SenseTime/SenseNova** | **Free public beta**, 60,000 credits/5h, up to 20 API keys; 6.8 Flash Lite + U1 Fast. | **Plan API / agent endpoint** |
| **01.AI/Yi** | No fresh first-party pricing/model change found today. | — |

Sources: [DeepSeek pricing](https://api-docs.deepseek.com/quick_start/pricing/), [Alibaba Model Studio pricing](https://www.alibabacloud.com/help/en/model-studio/model-pricing), [Xiaomi MiMo Token Plan](https://mimo.mi.com/docs/en-US/price/token-plan), [MiniMax Token Plan](https://platform.minimax.io/docs/guides/pricing-token-plan), [StepFun membership](https://www.stepfun.com/subscription), [SenseNova Token Plan](https://www.sensenova.cn/en/token-plan).

## FREE ACCESS

| Offer | Access Type | Free amount / catch |
|---|---|---|
| **OpenRouter Pareto Code** | General compatible API/router | **$0**, 13 coding models, 2M context |
| OpenRouter North Mini Code | General API | **$0**, 256K + tools; coding-harness focused |
| OpenRouter MiniMax M3 | General API | **$0**, 1M multimodal; rate-limited |
| OpenCode Zen seven documented free routes | Zen provider API | $0; privacy/training differs by model |
| SenseNova public beta | Plan API/agent endpoint | **¥0**, 60K credits/5h, up to 20 keys |
| Command Code Laguna / Ling / LongCat | Command Code agent/CLI | **free model usage while capacity/promo lasts** |

## LOW-COST SUBSCRIPTIONS

| Plan | Price | Access Type | Key point |
|---|---:|---|---|
| **Command Code Go** | **$1/mo** | **agent/CLI-only — NO general API** | $10 credits; Laguna S 2.1, Ling 3.0 Flash and LongCat 2.0 currently free |
| Baidu Qianfan Mini | **¥4.9 first / ¥9.9 regular** | **Plan API / compatible** | 10M tokens; unusually low entry price |
| Baidu Qianfan Lite | **¥19.9 first / ¥40 regular** | Plan API / compatible | 42M tokens |
| Tencent Hy Lite | **¥28/mo** | specific-client-only | Hunyuan-focused |
| **MiMo Lite** | **$6/mo; 12% first-buy discount** | specific-client-only | no 5-hour cap; OpenCode/Codex/Claude Code support |
| **Alibaba Token Plan Lite** | **$6/mo promo ($8 list)** | **specific-client-only** | Singapore only; 2,500 credits/7d; automation/custom backend prohibited |
| Tencent International Lite | about **$7/mo** | specific-client-only | coding/agent plan |
| **Command Code GOAT** | **$10/mo** | **agent/CLI + Provider API** | $70 usage, $14/5h, $35/week |
| OpenCode Go | **$10/mo** | provider/API for coding agents | 27-model pool; $12/5h, $30/week, $60/month base |
| MiniMax Starter | **$10/mo docs-listed** | specific-client Token Plan | M2.7; verify current checkout because M3 storefront emphasizes higher tiers |

Command Code's own pricing still distinguishes the **$1 Go plan from its Provider API product**. Do not classify Go as API access. GOAT's Provider-API entitlement remains a separate benefit from Go.

Sources: [Command Code pricing](https://commandcode.ai/pricing), [Command Code limits](https://commandcode.ai/docs/resources/usage-limits), [Alibaba Token Plan](https://www.alibabacloud.com/help/en/model-studio/token-plan-overview), [MiMo Token Plan](https://mimo.mi.com/docs/en-US/price/token-plan).

## BEST VALUE TODAY

**Best $0 coding API/router:** **OpenRouter Pareto Code**. A free 2M-context coding router across 13 models is hard to beat when you do not need deterministic model selection.

**Best $0 multimodal model:** **MiniMax M3 Free on OpenRouter** for 1M context plus image/video input — but community reports make it a fallback rather than the only route for a long autonomous job.

**Best use of OpenCode Go:** **MiMo-V2.5** remains the volume monster at ~30,100 typical requests/5h; **GLM-5.3-Flash** is especially attractive during the temporary 2× allowance; **Omen Alpha** is worth testing at ~11,600 requests/5h. Avoid sensitive code on Muse Contributor routes because training is explicitly permitted.

**Best DeepSeek raw cost:** OpenRouter Flash 0731 at **$0.05/$0.16**. Alibaba's **$0.14/$0.28** route is the next notable anomaly. Azure at **$0.19/$0.51** is not the cheapest, but it is a compelling enterprise compromise and even beats DeepSeek direct off-peak for uncached input/output. DeepSeek direct still wins cache-hit price at **$0.007/M**.

**Best ultra-cheap plan to test:** Baidu Qianfan Mini/Lite if signup and region requirements work for you. Unlike many coding subscriptions, Qianfan exposes a dedicated compatible plan endpoint and explicitly positions the plan for coding/Agent/automation workflows.

**Best no-window coding subscription:** Xiaomi MiMo Lite at **$6/month** (about **$5.28 first purchase**) because it has no 5-hour token cap.

**Azure rule of thumb:** pay the Azure premium when **Entra ID, RBAC, private networking, data controls or procurement** matter. But check the model card: **Azure Direct** has Microsoft's stronger data boundary; **Fireworks on Foundry** sends inference data outside Microsoft systems.

The broad stack still does not justify another expensive $20+ subscription today: the most interesting incremental capacity remains **free routes, $1–$10 coding plans, and provider-shopping for the same open model**.
