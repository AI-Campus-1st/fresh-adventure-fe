# fresh-adventure-fe

fresh-adventure의 프런트엔드 레포입니다 (Public).

## 목적과 범위

- 사용자 화면과 사용자 경험
- 대시보드 표시와 데이터 시각화
- 백엔드 API(`fresh-adventure-be`) 연동

## 폴더 구조 (잠정)

```text
public/         정적 이미지, 아이콘, 폰트
src/
├── app/        앱 진입점과 공통 설정(provider)
├── pages/      페이지 단위 화면
├── layouts/    공통 레이아웃
├── components/ common, charts, dashboard, feedback
├── features/   기능별 모듈
├── services/api/ 백엔드 API 클라이언트
├── hooks/ types/ utils/ constants/ styles/
tests/          unit, integration, e2e
docs/           레포 내부 문서
```

프런트엔드 기술 스택이 승인될 때까지 이 구조는 잠정안입니다.

## 화면 구성

화면 구성과 개수는 MVP·PRD 단계에서 정합니다. 기준 문서는 메인 레포의 [PTS](https://github.com/AI-Campus-1st/fresh-adventure/blob/main/docs/planning/PTS.md)입니다.

## 관련 레포

| 레포 | 공개 | 역할 |
| --- | --- | --- |
| [fresh-adventure](https://github.com/AI-Campus-1st/fresh-adventure) | Public | 프로젝트 문서, 관리, 공유 계약(데이터·API), 산출물 |
| [fresh-adventure-data](https://github.com/AI-Campus-1st/fresh-adventure-data) | Private | 데이터 수집, 전처리, 분석, 검증, 적재 |
| [fresh-adventure-fe](https://github.com/AI-Campus-1st/fresh-adventure-fe) | Public | 사용자 화면, 대시보드, 데이터 시각화 |
| [fresh-adventure-be](https://github.com/AI-Campus-1st/fresh-adventure-be) | Private | API 서비스, DB 조회, 비즈니스 로직, AI·LLM 연동 |

Private 레포는 팀원만 접근할 수 있습니다.

## 현재 상태

- Phase 01: 폴더 구조만 있습니다. 프레임워크는 초기화하지 않았고 의존성도 설치하지 않았습니다.

## 보안

이 레포는 **Public**입니다. API 키, LLM 키, DB 정보를 코드나 환경 파일에 넣지 마세요.
프런트엔드 환경변수는 빌드 결과물에 그대로 포함되므로, 공개돼도 되는 값만 사용합니다.

## 문서

- 레포 내부: [docs/README.md](docs/README.md)
- 공유 문서: https://github.com/AI-Campus-1st/fresh-adventure/tree/main/docs
