---
title: "Copilot CLI, BYOK와 로컬 모델 지원 — Cursor 3 열기 지속"
date: 2026-04-08
lang: ko
categories: [news]
tags: [claude, cursor, copilot, windsurf, gemini, codex, chatgpt, antigravity, openai]
excerpt: "GitHub Copilot CLI가 자체 모델 제공자 연결과 완전 로컬 모델 실행을 지원하고, Windsurf는 적응형 모델 라우터를 도입했다. Cursor 3 출시 열기가 이어지며 Cursor는 89점으로 1점 상승했다."
---

Cursor 3 출시 여진이 계속되는 가운데 이번 주 가장 주목할 움직임은 GitHub Copilot CLI에서 나왔다. 자체 모델 제공자를 연결하거나 완전히 로컬에서 실행할 수 있는 기능이 추가돼, Copilot의 유연성이 크게 확장됐다. Windsurf의 적응형 모델 라우터와 Codex CLI의 레거시 모델 정리도 주목할 변화다.

## GitHub Copilot: BYOK와 로컬 모델

GitHub Copilot CLI가 이제 자체 모델 제공자 연결(BYOK)과 완전 로컬 모델 실행(Ollama, vLLM, Foundry Local)을 지원한다. 에어갭 환경에서는 `COPILOT_OFFLINE=true` 설정으로 사용 가능하다. 이 변화는 보안 규정상 외부 API 호출이 제한된 기업 환경이나 데이터 주권이 중요한 조직에 Copilot의 문을 더 넓게 열어준다.

4월 2일 출시된 Copilot SDK 공개 미리보기도 계속 주목받고 있다. Node.js, Python, Go, .NET, Java 등 5개 언어를 지원하며, 기업이 Copilot의 에이전트 역량을 자체 애플리케이션에 내장할 수 있는 경로를 제공한다.

## Cursor: 3 출시 모멘텀 지속

Cursor가 89점으로 1점 상승했다. Cursor 3 출시 열기가 이어진 결과다. 에이전트 창, 디자인 모드, `/worktree`, `/best-of-n`을 갖춘 에이전트 우선 IDE 패러다임 전환이 개발자들 사이에서 계속 회자되고 있다.

## Windsurf: 적응형 모델 라우터

Windsurf가 4월 6일 가격 컨텍스트를 갖춘 새로운 적응형 모델 라우터를 도입했다. Max 티어의 일일 한도도 제거됐다. 요금 구조를 이해한 상태에서 모델을 선택할 수 있게 돼, 비용과 성능을 저울질해야 하는 팀에 실용적인 개선이다.

## Codex CLI: 레거시 모델 정리

Codex CLI 모델 선택기에서 gpt-5.2-codex와 이전 모델들이 제거됐다. 4월 14일에는 ChatGPT 로그인에서도 제거된다. GPT-5.3 Codex Spark 정식 통합을 위한 정지 작업이다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 97 | — | 안정 |
| Claude Code | 92 | — | 전체 2위 유지 |
| Cursor | 89 | ↑1 | Cursor 3 출시 열기 |
| GitHub Copilot | 88 | — | BYOK 지원으로 유연성 확대 |
| Claude AI | 87 | — | 안정 |
| Windsurf | 74 | — | 횡보 |
| Codex CLI | 72 | — | 레거시 모델 정리 |
| Aider | 68 | — | 안정 |
| Gemini CLI | 64 | — | 안정 |
| Antigravity | 51 | ↓1 | 하락세 지속 |

Copilot CLI의 BYOK와 로컬 모델 지원은 Copilot의 접근성을 확장하는 의미 있는 변화다. 그러나 4월 24일 데이터 학습 옵트아웃 마감이 다가오는 상황에서 이 기능 개선이 여론 반전으로 이어질지는 미지수다. Antigravity의 51점 하락은 실질적인 제품 업데이트 없이는 마인드쉐어 회복이 어렵다는 것을 계속 보여주고 있다.

---

*출처: [Cursor changelog](https://cursor.com/changelog), [Cursor blog](https://cursor.com/blog), [GitHub Blog](https://github.blog/changelog), [Anthropic changelog](https://code.claude.com/docs/en/changelog), [Windsurf changelog](https://windsurf.com/changelog), [OpenAI Codex changelog](https://developers.openai.com/codex/changelog), [Reddit r/programming](https://reddit.com/r/programming), [Reddit r/ChatGPTCoding](https://reddit.com/r/ChatGPTCoding), [Hacker News](https://news.ycombinator.com), [TechRadar](https://techradar.com), [TechCrunch](https://techcrunch.com), [The Register](https://theregister.com)*
