---
title: "Cursor 3.0, 병렬 에이전트로 판을 바꾸다 — GPT-4o 시대 공식 종막"
date: 2026-04-03
lang: ko
categories: [news]
tags: [cursor, openai, claude, gemini, copilot]
excerpt: "Cursor가 역대 최대 규모의 업데이트를 출시하며 병렬 에이전트 실행과 브라우저 디자인 모드를 선보였고, OpenAI는 GPT-4o 시대를 공식 마감했다. Google은 Gemini CLI에 3배 빠른 Flash 모델을 조용히 투입했다."
---

Cursor가 4월 2일 역대 가장 야심 찬 릴리스를 선보였고, 시장은 즉각 반응했다. AI 네이티브 에디터는 2점 상승해 90점을 기록하며 Claude Code의 91점 바로 아래까지 치고 올라왔고, GitHub Copilot에 처음으로 실질적인 압박을 가했다. 한편 GPT-4o는 마지막 시간을 보내고 있으며, Google은 전작보다 3배 빠른 모델로 Gemini CLI를 조용히 업그레이드했다.

## Cursor: 버전 3.0

Cursor 3.0은 에이전트 우선으로 처음부터 새로 설계한 제품이다. 핵심 기능은 **에이전트 창(Agents Window)** — 서로 다른 저장소, 환경, git 워크트리에서 여러 에이전트를 동시에 병렬로 실행하는 패널이다. **디자인 모드**는 개발자가 라이브 브라우저 UI에 직접 주석을 달고 그 내용을 에이전트에 전달해, 디자인 의도와 구현 사이의 간극을 좁힌다. 동시 작업 전환을 위한 에이전트 탭, 격리된 git 변경을 위한 `/worktree`, 여러 모델에 프롬프트를 실행해 최선의 결과를 고르는 `/best-of-n`도 추가됐다.

이번 릴리스는 Cursor를 단순 에디터 이상으로 — 개발자의 전체 스택에 걸친 에이전트 작업의 조율 레이어로 — 자리매김시킨다.

## GitHub Copilot: SDK 공개 미리보기

GitHub가 4월 2일 Copilot SDK를 공개 미리보기로 출시했다. Copilot의 클라우드 및 CLI 제품을 구동하는 동일한 에이전트 런타임을 외부에 공개한 것이다. Node.js, Python, Go, .NET, Java 등 5개 언어를 지원 — 첫 릴리스치고 이례적으로 넓은 언어 지원 범위다. 기업 팀이 GitHub의 제품 로드맵을 기다리지 않고 자체적으로 Copilot 기반 에이전트를 구축할 수 있는 길이 열렸다.

## OpenAI: GPT-4o 퇴역 완료

GPT-4o가 오늘부로 공식 퇴역했다. ChatGPT의 모든 플랜 — Business, Enterprise, Edu Custom GPT 포함 — 이 이제 GPT-5.x 모델만을 사용한다. 전환은 일부의 우려보다 순조로웠지만, GPT-4o 특유의 동작 방식에 맞게 구축된 Custom GPT 운영자들 사이에서는 호환성 문제가 보고되고 있다.

## Gemini CLI: Flash 모델로 업그레이드

Gemini 3 Flash가 Gemini CLI v0.36.0+의 기본 모델이 됐다. 수치가 주목할 만하다 — 표준 벤치마크에서 Gemini 2.5 Pro를 3배 빠른 속도와 낮은 비용으로 능가한다. Gemini 3.1 모델도 미리보기로 지원된다. 이 개선으로 Gemini CLI는 1점 상승해 64점을 기록했다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 97 | — | 안정 |
| Claude Code | 91 | ↑1 | 코딩 도구 선두 |
| Cursor | 90 | ↑2 | 3.0 출시 모멘텀 |
| GitHub Copilot | 89 | — | SDK 호재, 광고 여파 |
| Claude AI | 87 | ↑1 | 안정 |
| Windsurf | 75 | — | 횡보 |
| Codex CLI | 72 | — | 안정 |
| Aider | 68 | — | 니치하지만 충성도 높음 |
| Gemini CLI | 64 | ↑1 | Flash 모델 효과 |
| Antigravity | 54 | ↓1 | 하락세 지속 |

Cursor 3.0 출시는 이번 주 코딩 도구 시장에서 가장 중요한 경쟁 이벤트다. 병렬 에이전트 기능은 진정으로 차별화된 요소 — 아직 어떤 IDE 네이티브 도구도 이를 프로덕션 품질로 제공하지 못하고 있다. Cursor가 이 출시 모멘텀을 Claude Code 대비 지속적인 점수 상승으로 전환할 수 있을지가 앞으로 2주간의 핵심 질문이다.

---

*출처: [Cursor changelog](https://cursor.com/changelog), [GitHub Blog](https://github.blog/changelog), [Anthropic changelog](https://code.claude.com/docs/en/changelog), [OpenAI developer docs](https://developers.openai.com/codex/changelog), [Google AI blog](https://developers.googleblog.com), [Reddit r/ChatGPTCoding](https://reddit.com/r/ChatGPTCoding), [Hacker News](https://news.ycombinator.com)*
