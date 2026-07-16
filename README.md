# Codex Growth OS

Codex Growth OS는 서비스기획자에서 PM/PO로 성장하기 위한 개인 운영체계입니다.

이 저장소는 Obsidian Vault이자 Git 저장소로 사용합니다. Obsidian에서는 지식과 기획 맥락을 관리하고, Git에서는 문서와 자동화 산출물의 변경 이력을 관리합니다.

## 운영 축

- `01_pg-settlement-career`: PG, 정산, 대사, 결제 운영 지식과 커리어 자산
- `02_pm-po-portfolio`: PM/PO 성장, 포트폴리오, 면접 스토리
- `03_data-analysis-lab`: 데이터 분석, SQL, 지표 설계, 대시보드 실험
- `04_ai-service-builder`: 개인 AI 서비스 아이디어, MVP, 제품 기획
- `05_work-automation`: 업무 자동화, 문서/엑셀/Jira/Figma 자동화

## 기본 원칙

1. 생각과 초안은 Obsidian에 남긴다.
2. 정리된 문서와 자동화 파일은 Git으로 버전 관리한다.
3. PDF, 이미지, 엑셀, 발표자료 등 무거운 산출물은 Google Drive에 보관한다.
4. 중요한 결정은 `DECISIONS.md`에 남긴다.
5. 다음 작업은 `TODO.md`에 남긴다.

## 작업 흐름

```bash
git pull
# Obsidian 또는 Codex로 작업
git status
git add .
git commit -m "작업 내용"
git push
```

새 컴퓨터에서는 최초 1회만 clone합니다.

```bash
git clone <github-repo-url>
```

## Drive 연결 규칙

Google Drive에는 같은 이름의 `Codex Growth OS` 폴더를 두고, Git에 넣기 애매한 파일만 보관합니다.

- 캡처 이미지
- PDF
- Excel/CSV 원본
- 발표자료
- 외부 공유용 최종본

Drive에 올린 파일은 필요하면 `98_outputs-index/drive-index.md`에 링크와 설명을 남깁니다.
