---
title: "Anthropic, 서드파티 Claude 클라이언트 차단 — Copilot은 무료 체험 중단"
date: 2026-04-11
lang: ko
categories: [news]
tags: [claude, copilot, codex, gemini, chatgpt, openai, anthropic]
excerpt: "Anthropic이 OpenClaw 같은 서드파티 Claude 도구의 API 접근을 차단했고, GitHub은 남용 우려로 Copilot Pro 신규 체험을 조용히 중단했다. 플랫폼들이 통제권을 강화하고 있다는 두 가지 신호."
---

4월 11일 AI 개발자 뉴스는 두 가지 플랫폼 정책 변화가 주도했다. Anthropic이 서드파티 구독 도구의 Claude 접근을 차단하고, GitHub이 남용을 이유로 Copilot Pro 신규 체험을 중단한 것이다. 두 결정 모두 도입 규모가 커질수록 AI 기업들이 허용적인 접근 정책을 거두어들이는 더 넓은 흐름을 반영한다.

## Anthropic: OpenClaw 및 서드파티 도구 차단

Anthropic은 OpenClaw를 포함한 서드파티 클라이언트의 Claude 구독 접근을 차단했다. OpenClaw는 비공식 채널을 통해 구독 요금으로 Claude 모델에 접근하게 해주던 인기 우회 도구였다. 이 도구 사용자들은 이제 최대 50배의 비용 증가에 직면하게 됐다. 구독 정액제와 직접 API 가격의 차이다. OpenClaw 제작자는 임시 차단 조치도 받았다.

이 조치는 Claude의 상업적 영역이 넓어짐에 따라 Anthropic이 이용약관을 더 적극적으로 집행할 의도를 보여준다. 개발자 반응은 엇갈렸다. 합법적인 사업 보호라는 시각과 Claude를 둘러싼 개방 생태계에서 후퇴라는 시각이 공존한다.

## GitHub Copilot: 무료 체험 중단이 보여주는 전환율 고민

GitHub은 4월 10일부로 체험 제도 남용을 이유로 Copilot Pro 신규 체험을 중단했다. 기존 체험과 유료 구독은 영향이 없다. 이 중단은 주목할 만한 인정이다. 무료 체험은 표준적인 성장 도구인데, 중단은 전환율이나 남용률(혹은 둘 다)이 내부 기준선을 넘었다는 의미다.

Copilot은 1점 더 하락해 추적 기간 최저점인 86점을 기록했다. 데이터 학습 반발, 체험 중단, 주요 기능 발표 없음이 겹친 상황은 버티기 어려운 포지션이다.

## Codex CLI: v1.0.23에 자동조종 플래그 추가

Codex CLI v1.0.23이 4월 10일 출시됐다. `--mode`, `--autopilot`, `--plan` 세 가지 새 시작 플래그가 추가됐다. 이를 통해 개발자는 메뉴 탐색 없이 특정 에이전트 모드로 바로 시작할 수 있다. 편의성 개선이지만 도구를 한 단계 상위 시장으로 밀어올리는 효과가 있다. Codex CLI는 이 릴리스로 1점 올라 73점이 됐다.

## Claude Code: CLI에서 팀 온보딩과 컴퓨터 사용

4월 9일 출시된 Claude Code v2.1.98은 `/team-onboarding` 워크플로우, 자동 원격 세션 설정, MCP 컨텍스트 50만 자 제한, 그리고 가장 주목할 만한 기능으로 CLI에서 직접 컴퓨터 사용을 추가했다. 터미널 환경에서 그래픽 인터페이스와 상호작용하는 기능은 Claude Code 에이전트가 자율적으로 수행할 수 있는 작업의 범위를 넓혔다.

## OpenAI와 Google: SuperApp과 3D 시각화

OpenAI의 ChatGPT 5.5 SuperApp은 4월 6일 출시되어 ChatGPT, Codex, Atlas 브라우저를 하나의 데스크톱 앱으로 통합했다. 한편 Google Gemini(Pro)는 4월 10일 채팅 인터페이스 내에서 직접 인터랙티브 3D 모델, 물리 시뮬레이션, 조정 가능한 차트를 생성하는 진정한 신규 기능을 추가했다. 두 회사 모두 서로의 움직임을 주목하지 않았지만, 합쳐보면 다음 경쟁 전선이 컨텍스트 내 출력의 풍부함임을 시사한다.

별도로 OpenAI는 Sora 종료 일정을 명확히 했다. 앱은 4월 26일, API는 9월 24일에 종료된다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 97 | — | 선두, 안정적 |
| Claude Code | 92 | — | 2위 유지 |
| Cursor | 89 | — | 3위 유지 |
| Claude AI | 87 | — | 안정적 |
| GitHub Copilot | 86 | ↓1 | 체험 중단, 반발 지속 |
| Windsurf | 74 | — | 횡보 |
| Codex CLI | 73 | ↑1 | v1.0.23 자동조종 플래그 |
| Aider | 68 | — | 조용 |
| Gemini CLI | 65 | — | 안정적 |
| Antigravity | 51 | — | 횡보 |

Copilot은 이제 Cursor에 3점 뒤처지며 잘못된 방향으로 흘러가고 있다. 체험 중단은 개발자 콘퍼런스 시즌이 신규 가입을 늘리는 시기에 핵심 상단 깔때기 도구를 제거한 셈이다.

---

*출처: [Anthropic 뉴스](https://anthropic.com/news), [Claude Code changelog](https://code.claude.com/changelog), [GitHub Copilot changelog](https://github.blog/changelog), [OpenAI 헬프 센터](https://help.openai.com), [Gemini CLI changelog](https://geminicli.com/docs/changelogs), [Codex 릴리스](https://github.com/openai/codex/releases), Reddit [r/ChatGPTCoding](https://reddit.com/r/ChatGPTCoding), [Hacker News](https://news.ycombinator.com), TechCrunch, VentureBeat*
