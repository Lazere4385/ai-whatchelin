---
title: "Claude Code Source Leak Exposes 512K Lines and 44 Unreleased Features"
date: 2026-04-02
lang: en
categories: [news]
tags: [claude, openai, copilot, antigravity]
excerpt: "Anthropic accidentally published half a million lines of Claude Code source to npm, then issued DMCA takedowns against thousands of GitHub repos — while OpenAI quietly retired GPT-4o."
---

In what may be the most dramatic open-source accident in AI history, Anthropic published 512,000 lines of Claude Code's TypeScript source code to the public npm registry via a misconfigured debug file. The leak — which included 1,906 TypeScript files and 44 unreleased feature flags — triggered a cascade of events that dominated developer communities through the day. Separately, OpenAI confirmed that GPT-4o will be fully retired tomorrow across all plans.

## Claude Code: The Source Leak

The code appeared on the npm registry on March 31 as part of package v2.1.88's unobfuscated source map. Within hours, thousands of developers were cloning and analyzing the repository, with forks spreading to ~8,100 GitHub repos before Anthropic responded. The company issued DMCA takedowns against most of those repositories on April 1, then retracted the majority — a reversal that drew criticism for its inconsistency.

Among the leaked feature flags was a "persistent assistant" background mode codenamed KAIROS daemon mode, suggesting Anthropic is working on an always-on coding companion. No customer data or credentials were exposed. Anthropic described the incident as a packaging error, but U.S. Rep. Gottheimer is now pressing the company on safety protocols. This is Anthropic's second security issue in days, following the Claude Mythos data leak on March 27.

## Claude Code: v2.1.90 Update

Alongside the leak chaos, Anthropic shipped Claude Code v2.1.90 with a new `/powerup` interactive lessons feature, `.husky` directory protection, a fix for the rate-limit dialog infinite loop, a `--resume` cache miss regression fix, and compatibility improvements for the Edit/Write format-on-save hook.

## OpenAI: GPT-4o Final Retirement

GPT-4o reaches end-of-life tomorrow, April 3, with the Enterprise grace period closing. All ChatGPT plans — Business, Enterprise, and Edu Custom GPTs — will migrate to the GPT-5.x series. OpenAI also released GPT-5.4 nano today, targeting simple high-volume tasks. The Message Batches API max_tokens limit was raised to 300K for Claude Opus 4.6 and Sonnet 4.6.

## Antigravity: Accelerating Decline

Antigravity dropped two more points to 53 amid the ongoing quota controversy. With no substantive updates from the Cognition team, community patience is running thin.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 97 | — | Stable |
| Claude Code | 91 | ↑1 | Leak controversy, still rising |
| GitHub Copilot | 89 | — | Ad fallout continuing |
| Cursor | 88 | — | Steady |
| Claude AI | 87 | ↑1 | App Store momentum |
| Windsurf | 75 | — | Flat |
| Codex CLI | 72 | — | Stable |
| Aider | 68 | — | Niche, loyal |
| Gemini CLI | 63 | — | Flat |
| Antigravity | 53 | ↓2 | Accelerating decline |

Counterintuitively, the Claude Code source leak appears to be driving interest rather than eroding it — the score ticked up to 91 even as the DMCA chaos unfolded. Exposure to the codebase may be building developer confidence in Anthropic's technical approach.

---

*Sources: [Bloomberg](https://bloomberg.com), [TechCrunch](https://techcrunch.com), [Axios](https://axios.com), [BleepingComputer](https://bleepingcomputer.com), [OpenAI Help Center](https://help.openai.com), [Anthropic changelog](https://code.claude.com/docs/en/changelog), [Reddit r/ClaudeAI](https://reddit.com/r/ClaudeAI), [Hacker News](https://news.ycombinator.com)*
