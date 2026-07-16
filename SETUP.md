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

## GitHub 연결

원격 저장소를 만든 뒤 아래 명령을 실행합니다.

```bash
git remote add origin <github-repo-url>
git branch -M main
git push -u origin main
```

## Google Drive 연결

Drive에는 `Codex Growth OS` 폴더를 만들고 다음 하위 폴더를 둡니다.

```text
01_pg-settlement-career
02_pm-po-portfolio
03_data-analysis-lab
04_ai-service-builder
05_work-automation
90_references
98_outputs
99_archive
```

Drive 파일 링크는 `98_outputs-index/drive-index.md`에 기록합니다.

## Obsidian 사용법

- Vault로 열 폴더: 이 저장소 루트
- 새 노트 기본 위치: `00_inbox`
- 첨부파일 기본 위치: `_assets`
- 정리된 노트는 주제 폴더로 이동

## 주의

- `.env`와 API 키는 Git에 올리지 않습니다.
- 큰 파일은 Git에 넣지 않고 Drive에 보관합니다.
- 충돌이 나면 임의로 덮어쓰지 말고 변경 내용을 비교한 뒤 정리합니다.
