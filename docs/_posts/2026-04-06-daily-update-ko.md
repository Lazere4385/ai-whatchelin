---
title: "MCP, 월 9700만 다운로드 돌파 — Cursor의 에이전트 우선 IDE가 카테고리를 재정의하다"
date: 2026-04-06
lang: ko
categories: [news]
tags: [cursor, openai, claude, gemini, copilot, codex]
excerpt: "Model Context Protocol이 첫 Dev Summit에서 월간 SDK 다운로드 9700만 건을 돌파했다. Cursor는 에이전트 우선 플랫폼 정비를 마치고 90점에 도달했으며, Midjourney V8은 이미지 생성 게임의 규칙을 다시 썼다."
---

Model Context Protocol이 AI 에이전트 인프라가 얼마나 빠르게 성숙하고 있는지를 보여주는 이정표를 세웠다 — 월간 SDK 다운로드 9700만 건, 뉴욕에서 열린 MCP 첫 Dev Summit에서의 쾌거다. 이번 주는 Cursor의 에이전트 우선 포지셔닝 확립, OpenAI의 GPT-5.4 패밀리 확장, Anthropic의 10조 파라미터 모델 테스트 확인도 함께 이루어졌다.

## MCP Dev Summit: 인프라의 순간

MCP Dev Summit(4월 2~3일, 뉴욕)은 95개 이상의 세션을 열고 이 프로토콜이 AI 에이전트 개발의 진정한 인프라로 자리 잡았음을 확인했다. 가장 주목할 발표는 **x402** — MCP 프로토콜 위에 구축된 AI 에이전트 거래용 결제 표준이다. 에이전트가 예약, 구매, 계약 체결 같은 실세계 결과를 낳는 행동을 점점 더 많이 취하게 되면서, 표준화된 결제 레이어가 필수적이 된다. x402 스펙은 아직 초기 단계지만 방향은 명확하다.

## Cursor: 에이전트 우선 플랫폼 완성

Cursor 3이 완전히 배포됐고, 기능 세트는 초기 출시 내용보다 더 응집력 있는 모습이다. **Composer 2**가 기본 모델이 됐으며, **Cloud Handoff**가 로컬과 클라우드 실행 간 원활한 세션 이전을 가능하게 한다. 서로 다른 저장소에서 동시에 에이전트를 실행하는 멀티 저장소 에이전트 기능이 개발자 커뮤니티에서 가장 주목받는 기능이다. Cursor는 오늘 추적에서 90점을 기록했다.

## OpenAI: GPT-5.4 Mini와 Nano

**GPT-5.4 mini**와 **GPT-5.4 nano**가 GPT-5.4 패밀리를 완성하며 낮은 비용으로 고용량 워크로드에 플래그십급 역량을 제공한다. nano 모델은 특히 추론 깊이보다 볼륨이 중요한 애플리케이션을 겨냥한다. **GPT-5.3 Codex Spark**는 1,000 토큰/초 이상의 속도로 리서치 미리보기 상태를 유지 중이다.

## Google: Gemini 3 Flash를 기본 모델로

Gemini 3 Flash가 Gemini 앱의 기본 모델이 됐다 — Flash가 Gemini 2.5 Pro를 3배 속도로 능가한다는 점에서 의미 있는 전환이다. Google은 Arena AI 오픈 모델 리더보드에서 3위를 기록한 31B 변형을 포함한 Gemma 4 오픈 모델도 공개했다.

## Anthropic: Claude Mythos 확인

Anthropic이 **Claude Mythos** — 강화된 추론, 코딩, 사이버보안 역량을 갖춘 10조 파라미터 모델 — 테스트를 진행 중임을 확인했다. 확인은 4월 2일 공개된 내부 테스트 데이터를 통해 이루어졌다. 10조 파라미터는 현재 프론티어 모델 대비 약 5배 규모다. 출시 일정은 공개되지 않았다.

## Midjourney V8: 완전한 엔진 재작성

Midjourney V8이 완전히 새로 작성된 추론 엔진과 함께 출시됐다. 5배 빠른 속도와 네이티브 2K 해상도 출력을 제공한다. 참고로 Kling 3.0은 이제 최대 2분 길이의 클립을 지원한다 — Sora 최대 길이의 5배로, Sora의 4월 26일 앱 종료가 다가올수록 더욱 의미 있는 기준점이 된다.

## Antigravity: 가장 큰 낙폭

Antigravity가 3점 하락해 52점을 기록했다 — 추적 기간 중 하루 최대 낙폭이다. 실질적인 제품 소식도 없고 Cognition 인수 불확실성도 해소되지 않은 채 마인드쉐어를 빠르게 잃고 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 97 | — | 안정 |
| Claude Code | 91 | ↑1 | 정책 논란에도 강세 |
| Cursor | 90 | ↑2 | 3.0 완전 배포 |
| GitHub Copilot | 89 | — | SDK 호재, 광고 여파 |
| Claude AI | 87 | ↑1 | Mythos 확인 후광 효과 |
| Windsurf | 75 | — | 횡보 |
| Codex CLI | 73 | ↑1 | Spark 미리보기 관심 |
| Aider | 68 | — | 안정 |
| Gemini CLI | 64 | ↑1 | Flash 기본 모델 효과 |
| Antigravity | 52 | ↓3 | 추적 이래 최대 낙폭 |

MCP 이정표는 이번 주 구조적으로 가장 중요한 데이터 포인트다. 월간 9700만 다운로드는 이 프로토콜이 얼리어답터 영역을 넘어 주류 AI 인프라로 진입했음을 의미한다. 오늘 MCP 위에 구축하는 개발자들은 에이전트형 AI의 지배적인 상호운용성 레이어가 될 수 있는 것 위에 구축하고 있다.

---

*출처: [Linux Foundation MCP Dev Summit](https://events.linuxfoundation.org), [Cursor changelog](https://cursor.com/changelog), [OpenAI blog](https://openai.com), [Google AI blog](https://blog.google), [Anthropic](https://anthropic.com), [Fortune](https://fortune.com), [Midjourney](https://midjourney.com), [TechRadar](https://techradar.com), [VentureBeat](https://venturebeat.com), [Hacker News](https://news.ycombinator.com)*
