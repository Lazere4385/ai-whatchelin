---
title: "Cursor 3.0 Lands With Parallel Agents as GPT-4o Era Ends"
date: 2026-04-03
lang: en
categories: [news]
tags: [cursor, openai, claude, gemini, copilot]
excerpt: "Cursor's biggest-ever release brings parallel agent execution and a browser design mode, while OpenAI officially closes the GPT-4o chapter and Google drops a faster Flash model into Gemini CLI."
---

Cursor shipped its most ambitious release yet on April 2, and the market responded immediately. The AI-native editor jumped two points to 90, pulling within one point of Claude Code's 91 and putting real pressure on GitHub Copilot for the first time. Meanwhile, GPT-4o entered its final hours and Google quietly upgraded Gemini CLI with a model that outperforms its predecessor at three times the speed.

## Cursor: Version 3.0

Cursor 3.0 is a ground-up agent-first rebuild. The headlining feature is the **Agents Window** — a panel for running multiple agents in parallel across different repositories, environments, or git worktrees simultaneously. **Design Mode** lets developers annotate live browser UIs directly and feed those annotations to the agent, closing the gap between design intent and implementation. Additional highlights include Agent Tabs for switching between concurrent tasks, `/worktree` for isolated git changes, and `/best-of-n` for running a prompt across multiple models and selecting the best output.

The release positions Cursor as more than an editor — it's a coordination layer for agentic work across a developer's entire stack.

## GitHub Copilot: SDK Public Preview

GitHub shipped the Copilot SDK in public preview on April 2, exposing the same agent runtime that powers Copilot's cloud and CLI products. The SDK is available in Node.js, Python, Go, .NET, and Java — an unusually broad language surface for a first release. This gives enterprise teams a path to build custom Copilot-powered agents without waiting for GitHub's product roadmap.

## OpenAI: GPT-4o Retirement

GPT-4o is officially retired as of today. All ChatGPT plans — including Business, Enterprise, and Edu Custom GPTs — now run exclusively on GPT-5.x models. The transition has been smoother than some expected, though a handful of Custom GPT operators have reported compatibility issues with prompt structures built around GPT-4o's specific behavior.

## Gemini CLI: Flash Upgrade

Gemini 3 Flash is now the default model in Gemini CLI v0.36.0+, and the numbers are notable: it outperforms Gemini 2.5 Pro on standard benchmarks at three times the speed and lower cost. Gemini 3.1 models are also supported in preview. The jump moved Gemini CLI one point up to 64.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 97 | — | Stable |
| Claude Code | 91 | ↑1 | Leading coding tools |
| Cursor | 90 | ↑2 | 3.0 launch momentum |
| GitHub Copilot | 89 | — | SDK positive, ad drag |
| Claude AI | 87 | ↑1 | Steady |
| Windsurf | 75 | — | Flat |
| Codex CLI | 72 | — | Stable |
| Aider | 68 | — | Niche, loyal |
| Gemini CLI | 64 | ↑1 | Flash model boost |
| Antigravity | 54 | ↓1 | Continued slide |

Cursor's 3.0 launch is the most significant competitive event in the coding tool market this week. The parallel agent capability is genuinely differentiated — no other IDE-native tool offers this at production quality yet. Whether Cursor can convert the launch momentum into sustained score gains over Claude Code remains the key question for the next two weeks.

---

*Sources: [Cursor changelog](https://cursor.com/changelog), [GitHub Blog](https://github.blog/changelog), [Anthropic changelog](https://code.claude.com/docs/en/changelog), [OpenAI developer docs](https://developers.openai.com/codex/changelog), [Google AI blog](https://developers.googleblog.com), [Reddit r/ChatGPTCoding](https://reddit.com/r/ChatGPTCoding), [Hacker News](https://news.ycombinator.com)*
