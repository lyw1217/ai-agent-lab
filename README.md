# AI Agent Dev Tools Lab

Claude Code, Codex, Antigravity 등 AI Coding Agent를 실제 개발 업무에 활용해보고,
각자 발견한 사용법, workflow, 부가 도구, prompt를 공유하는 실무형 스터디입니다.

이 레포는 스터디 모집글이자 운영 문서이며, 매주 실험 기록과 도구별 팁을 모아 최종적으로
`AI Coding Agent Cookbook`을 만드는 것을 목표로 합니다.

## 스터디 목적

이 스터디는 AI 이론을 깊게 공부하는 것이 아니라, 현업 개발자가 실제 업무에서 AI 도구를
어떻게 활용할 수 있는지 실험하고 공유하는 것을 목표로 합니다.

- Claude Code, Codex, Antigravity 사용법 익히기
- 실제 개발 업무에 적용 가능한 AI workflow 발굴
- 반복 작업, 리팩터링, 테스트, 문서화, 코드리뷰 자동화 실험
- oh-my-opencode, oh-my-claudecode, oh-my-openagent 등 부가 도구 사용법 공유
- 팀 단위로 재사용 가능한 prompt, command, hook, workflow 정리
- AI가 만든 코드의 한계와 검증 방법 공유

## 스터디 방향

이론 중심이 아니라 실험 중심으로 진행합니다.

각자 관심 있는 도구나 workflow를 자유롭게 사용해보고, 스터디 시간에는 "써보니 어땠는지",
"실무에 다시 쓸 만한지", "어떤 문제가 있었는지"를 공유합니다.

```text
역할 없음
발표 부담 없음
자유 실험 중심
실제 사용 경험 공유
성공 사례와 실패 사례 모두 기록
GitHub 레포에 결과 정리
```

## 주요 사용 도구

### 메인 도구

| 도구 | 주요 실험 내용 |
|---|---|
| Claude Code | 코드베이스 분석, 리팩터링, 테스트 생성, command/hook/subagent workflow |
| Codex | 로컬 coding agent, repo 수정, PR 리뷰, GitHub 연동, 자동 구현 실험 |
| Antigravity | 앱 생성, UI 구현, Gemini 기반 개발 workflow, 기존 repo 수정 실험 |

### 부가 도구

| 도구 | 주요 실험 내용 |
|---|---|
| oh-my-opencode | agent workflow 확장, command/prompt 관리 |
| oh-my-claudecode | Claude Code 생산성 향상 workflow |
| oh-my-openagent | Claude Code, Codex, OpenCode 등 agent harness 통합 실험 |
| OpenCode | 터미널 기반 AI coding agent 비교 |
| MCP 도구 | GitHub, 파일, DB, 브라우저, 문서 도구 연결 실험 |

## 진행 방식

- 인원: 3명
- 방식: 자유 실험 + 공유
- 주기: 주 1회
- 발표자료: 필수 아님
- 산출물: GitHub 레포에 간단한 기록
- 역할 분담: 없음
- 각자 관심 있는 도구나 workflow를 자유롭게 실험
- 작업 방식: 각자 브랜치에서 기록 후 `main`으로 PR

## 매주 진행 예시

```text
0~10분: 이번 주 각자 써본 AI 도구 경험 공유
10~35분: 가장 유용했던 workflow 또는 사용법 데모
35~50분: 실패 사례, 위험 사례, 불편했던 점 공유
50~60분: 다음 주에 써볼 도구나 주제 정하기
```

## 주차별 느슨한 주제

완전히 자유롭게 진행하되, 주제가 너무 흩어지지 않도록 매주 느슨한 태그만 정합니다.

| 주차 | 주제 | 예시 |
|---|---|---|
| 1주차 | 기본 사용법 | Claude Code, Codex, Antigravity 설치 및 기본 명령 |
| 2주차 | 코드베이스 분석 | 기존 repo 구조 파악, architecture map 생성 |
| 3주차 | 구현 자동화 | 작은 기능 구현, 버그 수정, 리팩터링 |
| 4주차 | 테스트/디버깅 | 테스트 생성, failing test 분석, CI 실패 해결 |
| 5주차 | Workflow 확장 | hooks, slash command, subagent, MCP, oh-my 계열 도구 |
| 6주차 | 팀 workflow 정리 | 실제 업무에 쓸 prompt, command, policy, cookbook 정리 |

## 공유하면 좋은 주제

### Claude Code

- `CLAUDE.md` 작성법
- slash command 만들기
- hook 사용법
- subagent 분리
- plan mode 활용
- 큰 repo에서 context 관리하기
- 테스트 실행 후 자동 수정시키기
- 반복 작업 자동화하기

### Codex

- Codex CLI 기본 사용법
- 로컬 repo에서 agent 활용하기
- repo instruction 작성하기
- GitHub PR 리뷰에 활용하기
- issue 기반 구현 실험
- sandbox 권한 관리
- 브라우저 / 웹 작업 연동

### Antigravity

- 새 프로젝트 빠르게 생성하기
- UI 구현 품질 비교
- Gemini 모델과 개발 workflow 궁합 확인
- 기존 repo 수정 능력 확인
- Claude Code / Codex와 장단점 비교

### 부가 도구

- oh-my-opencode 사용법
- oh-my-claudecode 사용법
- oh-my-openagent 사용법
- command / prompt / workflow 관리
- MCP 연결
- 팀원에게 공유 가능한 설정 구성

## 스터디 규칙

```text
1. 발표자료는 필수가 아니다.
2. 이론 설명보다 실제 사용 경험을 우선한다.
3. 매주 최소 1개 이상의 실험 기록을 남긴다.
4. 프롬프트, 명령어, 설정 파일은 가능하면 함께 공유한다.
5. 성공 사례뿐 아니라 실패 사례도 기록한다.
6. 회사 기밀, 실제 고객 데이터, 민감 정보는 사용하지 않는다.
7. AI가 만든 코드는 반드시 사람이 검토한다.
8. 실무에 다시 쓸 수 있는 workflow를 찾는 것을 목표로 한다.
```

## 레포 구조

```text
ai-agent-lab/
├── README.md
├── tools/
├── workflows/
├── prompts/
├── experiments/
├── comparisons/
├── policies/
├── templates/
└── cookbook/
```

- `tools/`: 도구별 사용법, 장단점, 실험 메모
- `workflows/`: 상황별 AI coding workflow 정리
- `prompts/`: 반복해서 쓸 prompt와 command 정리
- `experiments/`: 매주 각자 남기는 실험 기록
- `comparisons/`: 도구 비교와 scoreboard
- `policies/`: 안전 사용, 코드 리뷰, 회사 코드 적용 기준
- `templates/`: 실험/비교/workflow 기록 템플릿
- `cookbook/`: 스터디 종료 후 정리할 최종 산출물

## 기록 방법

1. 실험을 하나 했다면 `templates/experiment.md`를 복사해 `experiments/YYYY-MM-topic.md`로 기록합니다.
2. 재사용할 만한 사용 순서가 생기면 `templates/workflow.md`를 복사해 `workflows/`에 정리합니다.
3. 도구를 비교했다면 `templates/tool-comparison.md`를 복사해 `comparisons/`에 남깁니다.
4. 좋은 prompt나 command는 `prompts/`에 짧게라도 추가합니다.

## GitHub 작업 방식

각자 자신의 브랜치에서 실험 기록, prompt, workflow를 작성한 뒤 `main`으로 PR을 보냅니다.

| 참여자 | 브랜치 |
|---|---|
| lyw | `lyw` |
| oht | `oht` |
| bth | `bth` |

기본 흐름:

```bash
git checkout main
git pull
git checkout lyw
git merge main

# 기록 작성 후
git add .
git commit -m "Add experiment note"
git push origin lyw
```

PR은 발표자료가 아니라 공유와 코멘트를 위한 공간으로 사용합니다.

## 최종 산출물

스터디가 끝나면 `cookbook/ai-coding-agent-cookbook.md` 문서를 남기는 것을 목표로 합니다.

예상 목차:

```text
1. Claude Code 실전 사용법
2. Codex 실전 사용법
3. Antigravity 실전 사용법
4. 상황별 추천 도구
5. 자주 쓰는 프롬프트
6. 자주 쓰는 slash command / hook / skill
7. 테스트 생성 workflow
8. 리팩터링 workflow
9. PR review workflow
10. 회사 업무에 적용할 때 주의사항
```

## 기대 효과

- 각 도구의 장단점을 실제 사용 경험 기반으로 파악
- 개발 업무에 바로 적용 가능한 AI workflow 확보
- 반복 업무 자동화 아이디어 발굴
- AI 생성 코드 검증 기준 마련
- 팀 단위 AI 활용 가이드 작성
- 개인별 개발 생산성 향상
