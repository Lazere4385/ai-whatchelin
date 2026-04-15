---
title: "Claude Code 소스 51만 줄 유출 — DMCA 대란에 OpenAI는 GPT-4o 퇴역"
date: 2026-04-02
lang: ko
categories: [news]
tags: [claude, openai, copilot, antigravity]
excerpt: "Anthropic이 잘못 설정된 디버그 파일로 Claude Code 소스 코드 반백만 줄을 npm에 공개 유출한 뒤 수천 개 GitHub 저장소에 DMCA 삭제를 요청했다가 대부분 철회했다. OpenAI는 GPT-4o 내일부로 완전 퇴역을 확정했다."
---

AI 역사상 가장 극적인 오픈소스 사고가 발생했다. Anthropic이 잘못 설정된 디버그 파일을 통해 Claude Code의 TypeScript 소스 코드 51만 2천 줄을 공개 npm 레지스트리에 유출했다. 1,906개의 TypeScript 파일과 44개의 미출시 기능 플래그를 담은 이 유출은 하루 종일 개발자 커뮤니티를 뒤흔들었다. 별개로 OpenAI는 GPT-4o가 내일 모든 플랜에서 완전히 퇴역한다고 공식 확인했다.

## Claude Code: 소스 코드 유출 전말

코드는 3월 31일 패키지 v2.1.88의 난독화되지 않은 소스 맵에 담겨 npm 레지스트리에 등장했다. 수시간 만에 수천 명의 개발자가 저장소를 복제해 분석하기 시작했고, 포크는 약 8,100개의 GitHub 저장소로 퍼졌다. Anthropic은 4월 1일 대부분의 저장소에 DMCA 삭제 요청을 보냈다가 곧 대부분을 철회했다 — 일관성 없는 대응이 추가 비판을 불렀다.

유출된 기능 플래그 중에는 KAIROS 데몬 모드라는 코드명의 "영구 어시스턴트" 백그라운드 모드가 포함돼 있어, Anthropic이 상시 작동형 코딩 보조 도구를 개발 중임을 시사했다. 고객 데이터나 자격증명은 노출되지 않았다. Anthropic은 패키징 오류라고 설명했지만, 미 하원의원 Gottheimer가 안전 프로토콜에 대해 회사를 압박하고 나섰다. 이는 3월 27일 Claude Mythos 데이터 유출에 이어 며칠 사이 두 번째 보안 사고다.

## Claude Code: v2.1.90 업데이트

유출 혼란 속에서도 Anthropic은 Claude Code v2.1.90을 출시했다. 새 `/powerup` 인터랙티브 학습 기능, `.husky` 디렉토리 보호, 속도 제한 다이얼로그 무한 루프 수정, `--resume` 캐시 미스 회귀 수정, Edit/Write 포맷 온 세이브 훅 호환성 개선이 포함됐다.

## OpenAI: GPT-4o 최종 퇴역

GPT-4o가 내일 4월 3일부로 서비스를 종료한다. Enterprise 유예 기간이 마감되며, ChatGPT의 모든 플랜 — Business, Enterprise, Edu Custom GPT — 이 GPT-5.x 시리즈로 전환된다. OpenAI는 오늘 단순 고용량 작업을 겨냥한 GPT-5.4 nano도 출시했다. Claude Opus 4.6 및 Sonnet 4.6의 Message Batches API max_tokens 한도는 300K로 상향됐다.

## Antigravity: 하락세 가속

Antigravity가 2점 더 하락해 53점을 기록했다. 할당량 논란이 계속되는 가운데 Cognition 팀의 실질적인 업데이트가 없어 커뮤니티의 인내심이 바닥을 드러내고 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 97 | — | 안정 |
| Claude Code | 91 | ↑1 | 유출 논란에도 상승 |
| GitHub Copilot | 89 | — | 광고 여파 지속 |
| Cursor | 88 | — | 안정 |
| Claude AI | 87 | ↑1 | App Store 모멘텀 |
| Windsurf | 75 | — | 횡보 |
| Codex CLI | 72 | — | 안정 |
| Aider | 68 | — | 니치하지만 충성도 높음 |
| Gemini CLI | 63 | — | 횡보 |
| Antigravity | 53 | ↓2 | 하락세 가속 |

역설적이게도 Claude Code 소스 유출은 신뢰를 갉아먹기보다 오히려 관심을 끌어모은 것으로 보인다 — DMCA 혼란이 벌어지는 와중에도 점수는 91로 올랐다. 코드베이스에 대한 노출이 Anthropic의 기술적 접근 방식에 대한 개발자 신뢰를 오히려 높이고 있을 수 있다.

---

*출처: [Bloomberg](https://bloomberg.com), [TechCrunch](https://techcrunch.com), [Axios](https://axios.com), [BleepingComputer](https://bleepingcomputer.com), [OpenAI Help Center](https://help.openai.com), [Anthropic changelog](https://code.claude.com/docs/en/changelog), [Reddit r/ClaudeAI](https://reddit.com/r/ClaudeAI), [Hacker News](https://news.ycombinator.com)*
