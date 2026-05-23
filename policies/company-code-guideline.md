# Company Code Guideline

회사 업무에 AI coding agent를 적용할 때의 기준을 정리합니다.

## 기본 원칙

- 민감 정보는 입력하지 않는다.
- AI가 생성한 결과물의 책임은 최종 반영자가 진다.
- 코드 리뷰와 테스트를 생략하지 않는다.
- agent가 만든 prompt, command, hook은 팀원이 이해할 수 있게 문서화한다.

## 권장 사용처

- 반복적인 boilerplate 작성
- 테스트 케이스 초안 생성
- 리팩터링 후보 분석
- 문서 초안 작성
- PR self-review
- 에러 로그 원인 후보 정리

## 주의가 필요한 사용처

- 인증/권한 관련 코드
- 결제, 정산, 개인정보 처리
- 대규모 자동 리팩터링
- 데이터 마이그레이션
- destructive command 실행
