---
title: "Cursor, Copilot과 90점 동률 — Google Gemma 4 오픈소스 공개"
date: 2026-04-04
lang: ko
categories: [news]
tags: [cursor, copilot, claude, gemini, openai]
excerpt: "Cursor 3.0 출시 여파로 Cursor가 GitHub Copilot과 나란히 90점에 진입했고, Google은 Gemma 4를 Apache 2.0으로 공개했다. Claude Code 소스 유출의 후폭풍도 계속되고 있다."
---

Cursor 3.0 출시 이후 리더보드가 재편되고 있다. 추적 기간 중 처음으로 Cursor와 GitHub Copilot이 90점에서 동률을 이뤘다 — 2주 전만 해도 Copilot이 4점 차 우위를 점하고 있었던 것을 감안하면 놀라운 변화다. Google의 Gemma 4 오픈소스 공개는 이번 주에 또 다른 차원을 더했다 — 개발자들에게 클라우드 호스팅 모델의 강력한 로컬 대안이 생겼다.

## Cursor: 90점 유지

Copilot과의 90점 동률은 3.0 출시 이후 모멘텀이 지속되고 있음을 보여준다. 병렬 에이전트 기능은 특히 여러 저장소를 관리하는 팀들 사이에서 큰 관심을 모으고 있다. Pro 가격이 연간 플랜 기준 월 20달러에서 16달러로 내려갔다 — Copilot에서 갈아탈지 고민하는 개인 개발자들의 흔한 반대 이유를 제거한 인하폭이다.

## GitHub Copilot: SDK와 가격 맞대응

GitHub는 Cursor의 가격 인하에 자체 인하로 응했다. Copilot Pro가 월 10달러에서 8.33달러(연 100달러)로 내려갔다. 전략적으로 더 중요한 것은 5개 언어로 공개된 Copilot SDK 미리보기 — 기업 팀이 GitHub의 로드맵을 기다리지 않고 Copilot 런타임 위에 자체 에이전트를 구축할 수 있게 됐다. 조직 수준 맞춤 지침도 정식 출시(GA)됐다.

## Google: Gemma 4 오픈 공개

Google이 Gemma 4를 2B, 7B, 14B, 31B 네 가지 크기로 Apache 2.0 라이선스 아래 공개했다. 31B 모델은 Arena AI 오픈 모델 리더보드에서 3위를 기록 — 상위 2개를 제외한 모든 오픈 모델을 앞서는 성적이다. 클라우드 의존 없이 로컬 추론이 필요한 개발자에게 올해 나온 가장 강력한 오픈 옵션이다.

## Claude Code: 유출 후폭풍

Claude Code 소스 유출의 여파가 계속되고 있다. 유출된 KAIROS 데몬 모드 — 지속형 백그라운드 어시스턴트 — 가 커뮤니티의 상세 분석 대상이 됐다. 일부 개발자들은 유출된 기능 플래그를 바탕으로 실험적 구현을 만들고 있으며, Anthropic 법무팀이 상황을 면밀히 주시하고 있다. Claude Code 점수는 논란에도 불구하고 91점을 유지했다 — 기술 커뮤니티의 반응이 경계보다는 호기심에 가깝다는 방증이다.

## Copilot 개인정보 마감 임박

GitHub Copilot 데이터 학습 옵트아웃 마감이 3주 앞으로 다가왔다(4월 24일). Copilot이 PR 광고 버그로 이미 불신을 받고 있는 상황에서 마감은 또 하나의 부정 여론 전선이 됐다. Reddit과 Hacker News에서는 "애초에 옵트아웃이 아니라 옵트인이었어야 했다"는 시각이 주류로 자리 잡고 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 97 | — | 안정 |
| Claude Code | 91 | ↑1 | 유출 논란 흡수 |
| GitHub Copilot | 90 | ↑1 | SDK 호재, 가격 인하 |
| Cursor | 90 | ↑2 | 3.0 모멘텀 지속 |
| Claude AI | 87 | ↑1 | 안정 |
| Windsurf | 76 | ↑1 | 요금 개편 |
| Codex CLI | 72 | — | 안정 |
| Aider | 68 | — | 니치하지만 충성도 높음 |
| Gemini CLI | 64 | ↑1 | Gemma 4 후광 효과 |
| Antigravity | 53 | ↓2 | 하락세 가속 |

90~91점의 3파전 — Claude Code, Copilot, Cursor — 은 추적 이래 가장 치열한 경쟁이다. Antigravity의 53점 하락은 선두권과 하위 사이의 간격을 점점 벌리고 있다. 이번 주 Cognition 팀에서 실질적인 업데이트가 없다면 하락세가 더 가팔라질 수 있다.

---

*출처: [Cursor blog](https://cursor.com/blog), [GitHub Blog](https://github.blog/changelog), [Google AI](https://ai.google.dev), [Anthropic changelog](https://code.claude.com/docs/en/changelog), [VentureBeat](https://venturebeat.com), [The Hacker News](https://thehackernews.com), [BleepingComputer](https://bleepingcomputer.com), [AfterDawn](https://afterdawn.com), [Reddit r/ClaudeAI](https://reddit.com/r/ClaudeAI)*
