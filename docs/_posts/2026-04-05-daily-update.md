---
title: "Anthropic Cuts Off Third-Party Claude Tools, GPT-5.4 Thinking Arrives"
date: 2026-04-05
lang: en
categories: [news]
tags: [claude, openai, cursor, gemini, windsurf, codex]
excerpt: "Anthropic quietly blocks third-party harnesses like OpenClaw from using Claude subscription limits, forcing users onto pay-as-you-go billing — while OpenAI ships its first mainline reasoning model with coding capability."
---

Anthropic made a policy move that blindsided a segment of the Claude developer community: third-party tools that route through Claude's API can no longer draw on subscription quotas. Tools like OpenClaw — which many developers relied on for cost-efficient Claude access — now require separate pay-as-you-go billing, with some users facing up to a 50x cost increase. The change arrived the same week OpenAI shipped GPT-5.4 Thinking, its first mainline model with native reasoning and coding capability.

## Claude Code: Subscription Policy and v2.1.92

The policy change affecting third-party harnesses is the most controversial Claude move this week. Anthropic's official position is that subscription limits are designed for direct Claude Code usage, not external orchestration layers. The developer community reaction has been sharp — OpenClaw users who built workflows around subscription pricing now face a fundamentally different cost structure. No grandfather period was announced.

On the product side, Claude Code v2.1.92 shipped with an interactive Bedrock setup wizard, per-model `/cost` breakdown so developers can see exactly what each model costs per session, and Linux sandbox improvements. The 60% faster Write tool is a meaningful quality-of-life improvement for heavy users.

## OpenAI: GPT-5.4 Thinking and the Codex Spark

**GPT-5.4 Thinking** replaces GPT-5.2 Thinking for Plus, Team, and Pro users — making it the first mainline GPT-5 model with built-in reasoning and coding capability. The model is positioned as a direct competitor to Claude's extended thinking mode for complex multi-step tasks.

**GPT-5.3 Codex Spark** entered research preview: a real-time coding model capable of generating over 1,000 tokens per second. At that speed, latency effectively disappears from the coding loop — a qualitative shift in how interactive AI-assisted coding feels. The model is text-only with a 128K context window.

**Codex CLI v0.118.0** also shipped, adding Windows sandbox proxy-only networking, first-class plugin support, sub-agent path-based addressing, and device code authentication.

## Gemini: 3.1 Ultra and Open Models

Gemini 3.1 Ultra landed in early April with a 2M token context window and native multimodal reasoning across text, image, audio, and video. Google also released the open-source **Gemma 4** family under Apache 2.0 — the 31B model ranked third on the Arena AI open model leaderboard.

## Windsurf: Billing Overhaul

Windsurf transitioned from a credit-based billing system to quota-based billing, a change that simplifies pricing but has caused some confusion among existing users about how their remaining credits convert. **Arena Mode** — a blind model comparison feature — is the most interesting new capability, giving developers an unbiased way to evaluate which model performs best for their specific tasks.

## Sora: Shutdown Confirmed

OpenAI confirmed that all Sora experiences and the Sora API will shut down by September 24, 2026, with the app closing on April 26. Competitors Kling, Runway, and Vidu are already seeing increased traffic.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 97 | — | Stable |
| Claude Code | 91 | ↑1 | Policy controversy, score holds |
| Cursor | 90 | ↑2 | Sustained 3.0 momentum |
| GitHub Copilot | 89 | — | Flat |
| Claude AI | 87 | ↑1 | Steady |
| Windsurf | 76 | ↑1 | Billing change noise |
| Codex CLI | 73 | ↑1 | v0.118.0 improvements |
| Aider | 68 | — | Niche, loyal |
| Gemini CLI | 64 | ↑1 | 3.1 Ultra halo |
| Antigravity | 54 | ↓1 | Slow decline |

The third-party subscription block is the kind of policy move that can quietly reshape market dynamics — developers who built around OpenClaw are now actively evaluating alternatives. Claude Code's score held at 91, but if the community backlash intensifies, this week could mark a turning point.

---

*Sources: [Anthropic changelog](https://code.claude.com/docs/en/changelog), [TechCrunch](https://techcrunch.com), [Bloomberg](https://bloomberg.com), [OpenAI](https://openai.com), [Codex CLI releases](https://developers.openai.com/codex/changelog), [Google AI blog](https://blog.google), [Windsurf changelog](https://windsurf.com/changelog), [Devin release notes](https://docs.devin.ai/release-notes), [Hacker News](https://news.ycombinator.com), [Reddit r/ClaudeAI](https://reddit.com/r/ClaudeAI)*
