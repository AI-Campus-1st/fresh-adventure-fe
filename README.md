# fresh-adventure-fe

FreshLens 웹 대시보드 프런트엔드 레포 (Public).

메인 레포: [fresh-adventure](https://github.com/AI-Campus-1st/fresh-adventure)

## 화면

| 단계 | 화면 |
| --- | --- |
| MVP | 메인(이번 주 브리핑), 수요 트렌드, 원가·수익성 |
| 전체 구축 | 타깃 고객, 시즌·프로모션 캘린더, AI 마케팅 어시스턴트 |

## 기술 스택

웹 프레임워크 + 차트 라이브러리 (예: React + Plotly.js) — **팀 합의 후 확정**하고, 확정되면 이 레포에 프로젝트를 초기화합니다.

배포: Amazon S3 + CloudFront

## 규칙

- ⚠️ **Public 레포입니다.** API 키, LLM 키, DB 정보 등 비밀값을 코드나 `.env`에 넣어 커밋하지 마세요. 외부 API·LLM 호출은 모두 백엔드([fresh-adventure-be](https://github.com/AI-Campus-1st/fresh-adventure-be))를 거칩니다.
- 프런트엔드 환경변수에는 백엔드 주소처럼 **공개돼도 되는 값만** 둡니다. (빌드 결과물에 그대로 노출됩니다)
- 협업 규칙: [메인 레포 conventions](https://github.com/AI-Campus-1st/fresh-adventure/blob/main/docs/conventions.md)
