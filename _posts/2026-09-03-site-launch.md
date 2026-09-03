---
layout: post
title: "LLM Price Watch is live"
date: 2026-09-03 14:45:00 -0400
summary: "The daily model-market report now has a permanent public home, with OpenCode, OpenRouter, Azure AI Foundry, direct vendor pricing, free access and low-cost coding plans tracked together."
---

<div class="callout"><strong>New today:</strong> Azure AI Foundry is now a mandatory source in the daily comparison, alongside OpenCode, OpenRouter and direct model-vendor pricing.</div>

## What this site tracks

LLM Price Watch is built around one practical question: **where is the cheapest sensible place to run a useful coding or agent model today?**

Every daily report checks:

- OpenCode Go and Zen, including free, preview, stealth and contributor routes.
- OpenRouter Free Router, free variants, provider-specific pricing anomalies and temporary discounts.
- Microsoft Azure AI Foundry, including serverless APIs, managed compute and provisioned-throughput options.
- Direct first-party pricing from major Chinese and global model vendors.
- Free access, trial credits and low-cost coding subscriptions.
- New model releases and newly exposed model IDs.
- Reddit/community reports as an aggressive discovery source, with unverified claims labeled accordingly.

## Azure changes the comparison

Azure is especially interesting because the same open or Chinese model may be available through several very different routes. The daily watch will compare **Azure serverless token pricing directly against the vendor API, OpenRouter and OpenCode when the billing units are comparable**.

Azure managed GPU compute and provisioned throughput will be shown separately so dedicated-compute costs are not misleadingly compared with simple per-token APIs.

The report will also flag cases where Azure costs more but provides useful enterprise advantages such as identity integration, compliance controls, private networking, regional deployment or easier US access to a model that is awkward to buy directly.

## Access type matters

A cheap plan is only useful if it works in the workflow you need. The watch explicitly distinguishes general API access from OpenAI-compatible APIs, vendor-agent/CLI-only subscriptions, web-chat access, specific-client-only coding plans, Azure serverless APIs and dedicated Azure compute.

That means a $1 coding-agent plan is never presented as equivalent to a $1 general-purpose API subscription when it is not.

## What comes next

Beginning with the next daily run, the complete report will be published here and archived by date. The **Current Deals** page will track worthwhile offers that remain active across multiple days, while expired promotions will be removed rather than cluttering the archive.
