# Setup

## 새 컴퓨터에서 시작하기

1. Git 설치
2. Obsidian 설치
3. GitHub 저장소 clone
4. Obsidian에서 clone한 폴더를 Vault로 열기
5. 작업 시작 전 `git pull`
6. 작업 종료 후 `git add`, `git commit`, `git push`

## 권장 로컬 경로

```text
C:\Users\<user>\Documents\Codex\codex-growth-os
```

## Obsidian 사용법

- Vault로 열 폴더: 이 저장소 루트
- 시작 문서: `Home.md`
- CMDS 기준 문서: `MOC - CMDS Flow.md`
- 새 노트 기본 위치: `00_inbox`
- 첨부파일 기본 위치: `etc/_assets`
- 템플릿 위치: `etc/_templates`
- 현재 업무 기록 시작점: `01_projects/current-work/MOC - 현재 업무.md`
- 프로젝트 관리 시작점: `01_projects/MOC - 프로젝트.md`

## Obsidian Properties

CMDS 단계는 노트 상단 프로퍼티로 관리합니다.

```yaml
종류: 노트
단계: 연결
영역: 현재업무
상태: 초안
tags:
  - CMDS/연결
```

권장 값:

- `단계`: `connect`, `merge`, `develop`, `share`, `system`
- `종류`: `note`, `moc`, `project`, `template`, `codex-task`
- `상태`: `draft`, `active`, `organizing`, `ready`, `archived`
- `영역`: `current-work`, `projects`, `pg-settlement`, `portfolio-career`, `data-analysis`, `ai-service`, `automation`, `codex-skills`

## 폴더 구조

```text
00_inbox
01_projects
  current-work
  pg-settlement
02_portfolio-career
03_data-analysis
04_ai-service
05_automation-ideas
90_references
98_outputs-index
99_archive
etc
  _assets
  _templates
```

## Google Drive 연결

Drive에는 `Codex Growth OS` 폴더를 만들고 무거운 산출물을 보관합니다.

Drive 파일 링크는 `98_outputs-index/drive-index.md`에 기록합니다.

## GitHub 연결

원격 저장소 확인:

```bash
git remote -v
```

작업 흐름:

```bash
git pull
git add .
git commit -m "작업 내용"
git push
```

## 주의

- `.env`와 API 키는 Git에 올리지 않습니다.
- 큰 파일은 Git에 넣지 않고 Drive에 보관합니다.
- 충돌이 나면 임의로 덮어쓰지 말고 변경 내용을 비교한 뒤 정리합니다.
