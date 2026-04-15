---
title: "Anthropic, 서드파티 Claude 도구 차단 — GPT-5.4 Thinking 첫선"
date: 2026-04-05
lang: ko
categories: [news]
tags: [claude, openai, cursor, gemini, windsurf, codex]
excerpt: "Anthropic이 OpenClaw 같은 서드파티 하네스의 Claude 구독 한도 사용을 조용히 차단하면서 일부 사용자는 최대 50배 비용 증가를 마주했다. 같은 주 OpenAI는 코딩 기능을 갖춘 첫 번째 메인라인 추론 모델 GPT-5.4 Thinking을 출시했다."
---

Anthropic이 Claude 개발자 커뮤니티 일부를 당황하게 만든 정책 변경을 단행했다. Claude API를 경유하는 서드파티 도구는 더 이상 구독 할당량을 사용할 수 없다. OpenClaw처럼 비용 효율적인 Claude 접근 수단으로 의존해 온 도구들은 이제 별도의 종량제 요금이 필요하며, 일부 사용자는 최대 50배의 비용 증가에 직면했다. 이 변경이 OpenAI가 코딩 기능을 내장한 첫 메인라인 추론 모델 GPT-5.4 Thinking을 출시한 주와 겹쳤다.

## Claude Code: 구독 정책 변경과 v2.1.92

이번 주 가장 논란이 된 Claude 변화는 서드파티 하네스에 영향을 주는 정책 변경이다. Anthropic의 공식 입장은 구독 한도가 외부 오케스트레이션 레이어가 아닌 Claude Code 직접 사용을 위해 설계됐다는 것이다. 개발자 커뮤니티의 반응은 거셌다 — 구독 가격 구조를 기반으로 워크플로우를 구축한 OpenClaw 사용자들은 근본적으로 다른 비용 구조를 마주하게 됐다. 유예 기간 발표는 없었다.

제품 측면에서는 Claude Code v2.1.92가 출시됐다. 인터랙티브 Bedrock 설정 마법사, 세션별 각 모델 비용을 확인할 수 있는 `/cost` 분석, Linux 샌드박스 개선이 포함됐다. Write 도구 60% 속도 향상은 헤비 유저에게 의미 있는 품질 개선이다.

## OpenAI: GPT-5.4 Thinking과 Codex Spark

**GPT-5.4 Thinking**이 Plus, Team, Pro 사용자를 대상으로 GPT-5.2 Thinking을 대체했다 — 내장 추론과 코딩 기능을 갖춘 첫 번째 메인라인 GPT-5 모델이다. 복잡한 다단계 작업에서 Claude의 확장 사고 모드와 직접 경쟁하는 포지셔닝이다.

**GPT-5.3 Codex Spark**가 리서치 미리보기에 진입했다. 초당 1,000 토큰 이상을 생성하는 실시간 코딩 모델이다. 이 속도에서는 코딩 루프에서 지연이 사실상 사라진다 — AI 보조 코딩이 느껴지는 방식의 질적 전환이다. 텍스트 전용, 128K 컨텍스트 창이다.

**Codex CLI v0.118.0**도 출시됐다. Windows 샌드박스 프록시 전용 네트워킹, 퍼스트클래스 플러그인 지원, 서브에이전트 경로 기반 주소 지정, 디바이스 코드 인증이 추가됐다.

## Gemini: 3.1 Ultra와 오픈 모델

Gemini 3.1 Ultra가 4월 초 출시됐다. 2M 토큰 컨텍스트 창과 텍스트, 이미지, 오디오, 비디오를 아우르는 네이티브 멀티모달 추론을 탑재했다. Google은 Apache 2.0 아래 **Gemma 4** 오픈소스 패밀리도 공개했다 — 31B 모델이 Arena AI 오픈 모델 리더보드 3위에 올랐다.

## Windsurf: 요금 개편

Windsurf가 크레딧 기반 요금제에서 할당량 기반 요금제로 전환했다. 가격 구조는 단순해졌지만 기존 크레딧이 어떻게 전환되는지에 대한 혼란이 일부 있다. **아레나 모드** — 블라인드 모델 비교 기능 — 가 가장 흥미로운 신기능으로, 개발자가 자신의 구체적인 작업에 어떤 모델이 가장 잘 맞는지 편견 없이 평가할 수 있다.

## Sora: 종료 확정

OpenAI가 모든 Sora 서비스와 Sora API가 2026년 9월 24일부로 종료된다고 확인했다. 앱은 4월 26일 닫힌다. 경쟁사 Kling, Runway, Vidu는 이미 증가하는 트래픽을 흡수하고 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 97 | — | 안정 |
| Claude Code | 91 | ↑1 | 정책 논란에도 점수 유지 |
| Cursor | 90 | ↑2 | 3.0 모멘텀 지속 |
| GitHub Copilot | 89 | — | 횡보 |
| Claude AI | 87 | ↑1 | 안정 |
| Windsurf | 76 | ↑1 | 요금 변경 혼란 |
| Codex CLI | 73 | ↑1 | v0.118.0 개선 |
| Aider | 68 | — | 니치하지만 충성도 높음 |
| Gemini CLI | 64 | ↑1 | 3.1 Ultra 후광 효과 |
| Antigravity | 54 | ↓1 | 완만한 하락 |

서드파티 구독 차단은 시장 역학을 조용히 재편할 수 있는 종류의 정책 변경이다 — OpenClaw를 중심으로 워크플로우를 구축한 개발자들이 지금 적극적으로 대안을 모색하고 있다. Claude Code 점수는 91점을 유지했지만, 커뮤니티 반발이 심화되면 이번 주가 전환점이 될 수도 있다.

---

*출처: [Anthropic changelog](https://code.claude.com/docs/en/changelog), [TechCrunch](https://techcrunch.com), [Bloomberg](https://bloomberg.com), [OpenAI](https://openai.com), [Codex CLI releases](https://developers.openai.com/codex/changelog), [Google AI blog](https://blog.google), [Windsurf changelog](https://windsurf.com/changelog), [Devin release notes](https://docs.devin.ai/release-notes), [Hacker News](https://news.ycombinator.com), [Reddit r/ClaudeAI](https://reddit.com/r/ClaudeAI)*
