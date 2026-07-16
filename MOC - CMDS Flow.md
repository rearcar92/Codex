---
종류: 목차
단계: 시스템
영역: 운영체계
상태: 운영중
tags:
  - CMDS
  - 옵시디언
  - 운영체계
---

# MOC - CMDS Flow

CMDS 흐름을 현재 Vault 구조에 맞게 적용하는 운영 지도입니다.

CMDS는 폴더명이 아니라 노트가 발전하는 상태로 사용합니다.

```text
Connect -> Merge -> Develop -> Share
```

## 1. Connect

관심사, 현재 업무, 문제 발견, 아이디어를 연결하는 단계입니다.

주로 아래에서 시작합니다.

- [[00_inbox/00_README|Inbox]]
- [[MOC - 현재 업무]]
- [[업무 기록 템플릿]]

대표 프로퍼티:

```yaml
단계: 연결
상태: 초안
```

## 2. Merge

관련 지식, 도메인 맥락, 참고자료를 통합하는 단계입니다.

주로 아래와 연결합니다.

- [[MOC - PG 정산 지식]]
- [[90_references/00_README|References]]
- [[정산]]
- [[대사]]

대표 프로퍼티:

```yaml
단계: 통합
상태: 정리중
```

## 3. Develop

프로젝트화, 자동화, 데이터 분석, AI 서비스 기획으로 발전시키는 단계입니다.

주로 아래와 연결합니다.

- [[MOC - 프로젝트]]
- [[MOC - PG 정산 프로젝트]]
- [[MOC - 데이터 분석]]
- [[MOC - 업무 자동화]]
- [[MOC - AI 서비스 아이디어]]

대표 프로퍼티:

```yaml
단계: 개발
상태: 운영중
```

## 4. Share

포트폴리오, 면접 답변, 발표자료, 외부 공유 산출물로 정리하는 단계입니다.

주로 아래와 연결합니다.

- [[MOC - 포트폴리오 소재]]
- [[MOC - PM PO 성장]]
- [[98_outputs-index/drive-index|Google Drive Index]]

대표 프로퍼티:

```yaml
단계: 공유
상태: 공유준비
```

## 현재 Vault 매핑

| CMDS 단계 | 현재 구조 | 역할 |
| --- | --- | --- |
| Connect | `00_inbox`, `01_projects/current-work` | 업무 기록, 문제 발견, 아이디어 수집 |
| Merge | `01_projects/pg-settlement`, `90_references` | 도메인 지식과 참고자료 통합 |
| Develop | `01_projects`, `03_data-analysis`, `04_ai-service`, `05_automation-ideas` | 프로젝트화, 분석, 자동화, 제품화 |
| Share | `02_portfolio-career`, `98_outputs-index` | 포트폴리오와 공유 산출물 |

## 사용 규칙

- 새 노트에는 가능하면 `단계`를 붙입니다.
- 한 노트가 발전하면 `단계`를 바꾸거나, 다음 단계 노트를 새로 만들어 연결합니다.
- 폴더 위치보다 현재 단계와 연결 관계를 우선합니다.
- 프로젝트 노트는 Develop을 중심으로 두고, Connect/Merge/Share 노트를 함께 링크합니다.
