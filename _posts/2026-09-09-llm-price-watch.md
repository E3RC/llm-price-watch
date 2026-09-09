---
layout: post
title: "LLM Price Watch — September 9, 2026"
date: 2026-09-09 07:32:00 -0400
summary: "Mercury 2.5 launches with an 80%-off $0.04/$0.15 rate and a 100M-token trial, OpenRouter Inkling adds strong free agent capacity with a training/privacy tradeoff, Tencent's GLM-5.3-Flash discount remains live, and OpenCode Go stays at 27 models."
---

## 🚨 Top changes today

| Change | Why it matters |
|---|---|
| **Mercury 2.5 is the standout new coding/agent deal** | Inception launched Mercury 2.5 on Sep. 8 at **$0.04 input / $0.15 output per 1M** during an **80%-off launch promotion**, with 260K context, tool calling, structured output and claimed 1,107 tok/s. Inception is also offering **100M free API tokens** to try it. |
| **OpenRouter Inkling + Inkling Small are useful $0 agent routes** | Both are **free**, 1M-context, multimodal and tool-capable. Catch: the free research endpoint is restricted to agentic harnesses, logs prompts/outputs for model/product improvement and explicitly says not to submit confidential or personal data. |
| **OpenRouter MiniMax free routes still show Free** | First-party pages for **M3 Free** and **M2.7 Free** remain $0 despite community reports of intermittent disappearance/failures. Treat them as opportunistic free capacity, not guaranteed production capacity. |
| **MiniMax paid routes are also discounted** | OpenRouter lists **M3 at 60% off ($0.12/$0.48)** and **M2.7 at 30% off ($0.21/$0.84)**. |
| **Tencent GLM-5.3-Flash promo has one day left** | Tencent Cloud bills GLM-5.3-Flash at **50% of $0.15/$0.50 list** through **23:59:59 Beijing time Sep. 10** — effectively about **$0.075/$0.25 per 1M**. |
| **OpenCode Go is unchanged at 27 models** | No new Go model ID today. **GLM-5.3-Flash still gets 2× Go usage** for a limited time, and DeepSeek ZDR remains confirmed through Sep. 30. |
| **OpenCode Zen remains six official free models** | Muse Spark 1.3 Contributor Free remains; Muse 1.2 Contributor Free and Hy3 Free are not on the current list. |
| **ZCode trial terms changed from the earlier GLM offer** | Current first-party docs now show a **5-day trial with 3M GLM-5.3 + 2M GLM-5-Turbo tokens/day**, rather than the previously surfaced GLM-5.3-Flash allowance. |
| **Vercel's GLM-5.3 Sep. 8 promo is over** | The provider page explicitly says the promotional pricing ended Sep. 8. Remove it from time-limited-deal assumptions. |

Sources: [Inception Mercury 2.5](https://www.inceptionlabs.ai/blog/introducing-mercury-2-5) · [OpenRouter Mercury 2.5](https://openrouter.ai/inception/mercury-2.5-preview) · [OpenRouter Inkling Free](https://openrouter.ai/thinkingmachines/inkling:free) · [Tencent Cloud pricing](https://www-sg.tencentcloud.com/ko/document/product/1300/78937)

## OpenCode Go

Go remains **$10/month**, with base usage-value limits of **$12/5h, $30/week and $60/month**. OpenCode currently lists 27 models. The request figures below are OpenCode's own estimates for typical coding-agent traffic.

| Model | Input → output / 1M | Est. req/5h | Modality / privacy | Change |
|---|---:|---:|---|---|
| Grok 4.6 | $2 → $6 | 169 | text/agent · ZDR caveats | — |
| GPT-5.6 Luna | $0.20 → $1.20* | 2,050 | vision/text · 30d abuse logs | — |
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
| DeepSeek V4 Pro | $0.66 → $1.98 off-peak | 1,050 | **ZDR through Sep. 30** | — |
| DeepSeek V4 Flash | $0.22 → $0.66 off-peak | 7,600 | **ZDR through Sep. 30** | — |
| DS V4 Flash Vision Exp | $0.22 → $0.66 off-peak | 3,800 | vision · **ZDR through Sep. 30** | — |
| Hy4 Preview | $0.834 → $2.501 | 1,350 | agent · ZDR | — |
| Hy3 | $0.14 → $0.58 | 4,300 | agent · ZDR | — |
| Omen Alpha | $0.20 → $0.66 | 11,600 | stealth · ZDR | — |

\* Higher-context tiers differ. DeepSeek peak rates are higher than the off-peak rates shown.

Sources: [OpenCode Go docs](https://dev.opencode.ai/docs/go/) · [OpenCode Go landing page](https://dev.opencode.ai/go)

## OPENCODE FREE / PREVIEW DEALS

The current official Zen list is still **six free routes**:

| Model / ID | Access Type | Cost | Context / modality | Privacy / status |
|---|---|---:|---|---|
| `big-pickle` | Zen provider API | **$0** | stealth | limited-time; feedback/model improvement |
| `mimo-v2.5-free` | Zen provider API | **$0** | multimodal | limited-time; feedback/model improvement |
| `ling-3.0-flash-fin-free` | Zen provider API | **$0** | coding/text | limited-time; feedback/model improvement |
| `nemotron-3-ultra-free` | Zen provider API | **$0** | agent/text | NVIDIA trial logging terms |
| `nemotron-3.5-lightning-free` | Zen provider API | **$0** | agent/text | NVIDIA trial logging terms |
| `muse-spark-1.3-contributor-free` | Zen provider API | **$0** | multimodal/agent | **Meta training permitted** |
| Muse Spark 1.2 Contributor Free | former route | — | — | not on current list |
| Ox Alpha | ended preview | — | — | identified as GLM-5.3-Flash |
| Hy3 Free | former route | — | — | not on current list |

**GPT-5.6 Sol remains 50% off through Sep. 18** on Zen.

Source: [OpenCode Zen](https://dev.opencode.ai/docs/zen)

## OPENROUTER DEALS

| Route | Access Type | Current price | Why it matters |
|---|---|---:|---|
| `openrouter/free` | OpenAI-compatible API/router | **$0** | rotating **24-model** free pool, 200K router context |
| `openrouter/pareto-code` | OpenAI/Anthropic-compatible API/router | **$0** | 13 coding models, **2M context** |
| **Thinking Machines Inkling Free** | general API, **agentic-harness-only terms** | **$0** | 1M, text/image/audio, tools; **logs prompts/outputs for improvement** |
| **Inkling Small Free** | general API | **$0** | 1M, text/image/audio, tools; smaller/faster family member |
| MiniMax M3 Free | general API | **$0** | 1M multimodal; rate-limited/intermittent reports |
| MiniMax M2.7 Free | general API | **$0** | 205K agent/productivity; rate-limited |
| **Mercury 2.5** | general API | **$0.04/$0.15; cache $0.004** | **80% off**, 260K, extremely fast agent/subagent route |
| **MiniMax M3 paid** | general API | **$0.12/$0.48; cache $0.024** | **60% off** |
| **MiniMax M2.7 paid** | general API | **$0.21/$0.84; cache $0.042** | **30% off** |
| DeepSeek V4 Flash 0731 — OpenInference | general API | **$0.05/$0.16; cache $0.013** | cheapest simple named-provider DeepSeek route |

**Community note:** Reddit users continue reporting MiniMax free routes disappearing in some clients/regions. The first-party OpenRouter model pages still show both free today, so this is an availability warning rather than an expiration call.

Sources: [Free Router](https://openrouter.ai/openrouter/free) · [Pareto Code](https://openrouter.ai/openrouter/pareto-code) · [Inkling Free](https://openrouter.ai/thinkingmachines/inkling:free) · [MiniMax M3](https://openrouter.ai/minimax/minimax-m3) · [MiniMax M2.7](https://openrouter.ai/minimax/minimax-m2.7) · [DeepSeek V4 Flash](https://openrouter.ai/deepseek/deepseek-v4-flash-0731)

## NEW MODELS

### 🔥 Mercury 2.5 — launched September 8

Inception says Mercury 2.5 is its most capable production diffusion LLM yet, with a **40% intelligence increase over Mercury 2**, claimed **1,107 tokens/sec** on widely available NVIDIA GPUs, **260K context**, tunable reasoning, parallel tool calls and schema-aligned JSON. List price is $0.20/$0.75 per 1M; launch pricing is **80% off at $0.04/$0.15**. Inception offers **100 million free API tokens** for evaluation.

That combination makes Mercury 2.5 unusually interesting for coding subagents, compaction, routing, search/RAG pipelines and other high-call-count agent workflows where latency compounds.

Source: [Inception Mercury 2.5 release](https://www.inceptionlabs.ai/blog/introducing-mercury-2-5)

## AZURE AI FOUNDRY COMPARISON

Azure still matters most when **Microsoft-hosted governance/privacy** is part of the requirement rather than when raw token price alone decides the winner.

| Model | Azure offer | Azure price / billing | Cheaper/current comparison | Take |
|---|---|---:|---|---|
| **DeepSeek V4 Flash** | **Direct from Azure / serverless PAYG** | **$0.19 in / $0.51 out / $0.028 cache per M** | OpenRouter/OpenInference $0.05/$0.16; Alibaba Global $0.138/$0.275 | Azure premium buys provider isolation/governance |
| **DeepSeek V4 Pro** | Direct from Azure / serverless PAYG | **$1.74/$3.48; cache $0.145** | DeepSeek direct off-peak $0.66/$1.98 | substantial Azure premium |
| DeepSeek V4 Flash 0731 | Direct from Azure Preview | catalog/portal pricing | OpenRouter $0.05/$0.16 | Azure-hosted privacy boundary |
| **Kimi K3** | **Fireworks on Foundry** | partner PAYG/PTU | Moonshot/aggregator pricing varies | **not Azure Direct**; data leaves Microsoft systems |
| **MiniMax M3** | **Fireworks on Foundry** | partner PAYG/PTU | OR free route or $0.12/$0.48 paid | not a raw-price winner today |
| Qwen3.8-27B | open-weight catalog / managed deployment | compute-based | Qwen Cloud/API pricing separate | **do not compare GPU-hours to $/M tokens** |
| Managed/provisioned compute | Azure managed compute / PTU | calculator/quote; older DeepSeek PTU rows show 100-PTU minimum | serverless PAYG is separate | commitment economics, not token-route pricing |

For **Models sold by Azure**, Microsoft says prompts, completions and training data are not available to underlying model providers and are not used to train foundation models without permission. The current catalog separately marks Kimi K3 and MiniMax M3 as **Fireworks on Foundry**, where data is shared with Fireworks and processed outside Microsoft systems. Those are materially different privacy boundaries.

The current Foundry catalog features **DeepSeek-V4-Pro, FW-Kimi-K3, qwen--qwen3.8-27b and FW-MiniMax-M3**. No fresh Azure Direct catalog listing surfaced today for Mercury 2.5, MiMo/Xiaomi, Hunyuan/Tencent, Baidu/ERNIE, Doubao/ByteDance, StepFun, SenseNova or Yi.

Sources: [Microsoft Foundry catalog](https://ai.azure.com/catalog) · [DeepSeek V4 pricing](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/introducing-deepseek-v4-flash-and-v4-pro-in-microsoft-foundry/4515174/) · [Azure data/privacy](https://learn.microsoft.com/en-us/azure/foundry/responsible-ai/openai/data-privacy) · [FW-Kimi-K3](https://ai.azure.com/catalog/models/FW-Kimi-K3) · [FW-MiniMax-M3](https://ai.azure.com/catalog/models/FW-MiniMax-M3)

## DIRECT CHINESE API / PLAN SCAN

| Vendor | Current first-party finding | Access Type |
|---|---|---|
| **DeepSeek** | V4 Flash off-peak **$0.22/$0.66**, cache hit **$0.007**; peak $0.44/$1.32 | **general OpenAI + Anthropic-compatible API** |
| **Alibaba/Qwen** | Qwen3.8 Flash Global (Virginia/Frankfurt/Tokyo) **$0.113/$0.382**, cache read $0.014 | **general API** |
| **Alibaba-hosted DeepSeek** | `deepseek-v4-flash` Global **$0.138/$0.275**, cache $0.028; US-only scope $0.20/$0.40 | **general API** |
| **Xiaomi/MiMo** | MiMo-V2.5 **$0.14 input / $0.0028 cache / $0.28 output**, 1M context, multimodal | **general API** |
| **Tencent Cloud** | GLM-5.3-Flash list **$0.15/$0.50**, billed **50% through Sep. 10**; Hy3 $0.132/$0.528 | **general API** |
| **SenseNova** | public beta **¥0**, 60,000 credits/5h, up to 20 API keys | **plan API / agent endpoint** |
| **StepFun** | Starter **¥39/mo**, 1,300 credits | **hosted/specific-client agent plan** |
| Moonshot/Kimi | no material first-party price change surfaced today | general API |
| MiniMax | no new first-party direct-price change surfaced; OR is where today's discounts/free capacity are | general API / plans |
| Baidu/ERNIE | no newly verified standout coding/API promo today | API / plans |
| ByteDance/Doubao | no newly verified standout coding/API promo today | API / plans |
| 01.AI/Yi | no new hosted-API bargain surfaced | open weights / self-host |

Sources: [DeepSeek pricing](https://api-docs.deepseek.com/quick_start/pricing/) · [Alibaba Qwen pricing](https://www.alibabacloud.com/help/en/model-studio/qwen3-8-flash) · [Alibaba DeepSeek V4 Flash](https://www.alibabacloud.com/help/en/model-studio/deepseek-v4-flash) · [Xiaomi MiMo API pricing](https://mimo.mi.com/docs/en-US/price/pay-as-you-go) · [Tencent Cloud model pricing](https://www-sg.tencentcloud.com/ko/document/product/1300/78937) · [SenseNova Token Plan](https://www.sensenova.cn/en/token-plan) · [StepFun membership](https://www.stepfun.com/subscription)

## LOW-COST SUBSCRIPTIONS ($3–$10)

| Plan | Price | Access Type | Important distinction |
|---|---:|---|---|
| **Command Code Go** | **$1/mo** | **agent/CLI-only — NO Provider API** | $10 monthly credits; current free Laguna/Ling/LongCat model routes |
| Tencent Hy Lite | ~¥28/mo | specific-client-only | low-cost Hunyuan coding plan |
| StepFun Starter | **¥39/mo** | hosted/specific-client | 1,300 credits + StepClaw |
| **Xiaomi MiMo Lite** | **$6/mo** | **specific-client/tool-oriented Token Plan** | 4.1B credits; OpenCode/Codex/Claude Code compatible; backend automation prohibited |
| **Alibaba Token Plan Lite** | **$8 list / $6 promo** | **specific-client/tool-oriented plan API** | 2,500 credits/7d; interactive coding/agent use only; automation/custom backends prohibited |
| **Command Code GOAT** | **$10/mo** | **agent/CLI + OpenAI/Anthropic-compatible Provider API** | $70 monthly credits; unlike Go, API access is included |
| **OpenCode Go** | **$10/mo** | coding-agent provider/API | 27-model curated pool; $12/5h, $30/week, $60/month usage-value limits |

Command Code's first-party docs remain explicit: **every plan except Go can use the Provider API**. Go therefore stays classified as agent/CLI-only, even though GOAT and higher plans expose standard OpenAI/Anthropic-compatible endpoints.

Sources: [Command Code pricing](https://commandcode.ai/docs/resources/pricing-limits) · [Command Code Provider API](https://commandcode.ai/docs/provider) · [Xiaomi Token Plan](https://mimo.mi.com/docs/en-US/price/token-plan) · [Alibaba Token Plan](https://www.alibabacloud.com/help/en/model-studio/token-plan-overview)

## FREE ACCESS

| Offer | Access Type | Cost | Status |
|---|---|---:|---|
| **Inception Mercury 2.5 trial** | general API trial | **100M tokens** | launch evaluation offer |
| **OpenRouter Inkling / Inkling Small** | agentic-harness API routes | **$0** | 1M multimodal; data logged/training-style improvement terms |
| **OpenRouter MiniMax M3 / M2.7 Free** | general API | **$0** | live pages still free; rate limits/intermittence reported |
| OpenCode six Zen routes | Zen provider API | **$0** | current official list |
| SenseNova public beta | plan API / agent endpoint | **¥0** | 60K credits/5h |
| **ZCode first-user trial** | hosted coding/client trial | **5 days** | current docs: 3M GLM-5.3 + 2M GLM-5-Turbo tokens/day |
| Command Code Laguna / Ling / LongCat | Go agent/CLI route | **$0 model usage** | promotion/capacity dependent |

## 🏆 BEST VALUE TODAY

**Mercury 2.5 is today's model to test first.** At **$0.04/$0.15 per 1M**, a 100M-token evaluation offer and claimed four-digit-token-per-second throughput, it has unusually favorable economics for coding subagents, repo summarization, compaction, routing and repeated tool-loop support calls. Do not assume benchmark parity with a premium coding flagship; use the free allocation to benchmark it against your real workloads.

For **free agent capacity**, Inkling is now a strong addition because it gives 1M context, multimodal input and tool use at $0, but the provider's own notice makes it unsuitable for confidential code or personal data. MiniMax M3/M2.7 Free and Pareto Code remain useful opportunistic fallbacks.

For **cheap paid DeepSeek**, OpenRouter/OpenInference at **$0.05/$0.16** remains the simple named-provider bargain; Alibaba Global `deepseek-v4-flash` at **$0.138/$0.275** is the strongest hyperscaler-style price; Azure Direct at **$0.19/$0.51** is attractive when Microsoft governance/provider isolation is worth more than the raw-price delta.

For **very high-volume multimodal coding**, Xiaomi MiMo-V2.5 remains exceptional at **$0.14/$0.28 with $0.0028 cache hits**. For a subscription-shaped workflow, its $6 Lite Token Plan is compelling, but it must stay inside supported interactive coding tools rather than being treated as a production backend API allowance.

The current market still favors **stacking free/cheap capacity rather than buying another premium $20-class seat**: Mercury's launch deal, OpenRouter free routes, OpenCode Go, Command Code Go/GOAT-class plans and Chinese direct APIs cover an enormous amount of experimentation for very little money.
