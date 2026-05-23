# Context Management Workflow

## 언제 쓰면 좋은가

- 큰 repo에서 agent가 맥락을 잃을 때
- 긴 작업 중 요약과 기준을 유지해야 할 때
- instruction, memory, prompt를 정리하고 싶을 때

## 기본 흐름

1. 작업 목표와 변경 금지 영역을 먼저 적는다.
2. repo instruction에 반복 기준을 넣는다.
3. 필요한 파일만 단계적으로 읽게 한다.
4. 중간 요약을 남기고 다음 단계로 넘긴다.
5. 최종 diff와 테스트 결과로 검증한다.
