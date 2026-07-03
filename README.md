# 메리츠화재 TM 교육시스템(LMS) 구축 프로젝트 — 중간보고

메리츠화재 TM 교육시스템(LMS) 구축 프로젝트의 **중간보고서 HTML 슬라이드**를 정적 사이트로 정리한 저장소입니다.

## 라이브 사이트

- **URL:** https://parkh37t.github.io/meritz-lms/
- 진입 파일: 루트 [`index.html`](./index.html)

> GitHub Pages는 `main` 브랜치에 푸시될 때 GitHub Actions 워크플로
> ([`.github/workflows/pages.yml`](.github/workflows/pages.yml))가 자동으로 활성화·배포합니다.

## 구성

| 경로 | 설명 |
| --- | --- |
| `index.html` | 정적 사이트 진입 파일 (중간보고 슬라이드 덱, 자체 완결형 HTML) |
| `메리츠화재 TM LMS 중간보고-handoff/preview.html` | 전달받은 원본 핸드오프 소스 (보존용) |
| `.github/workflows/pages.yml` | GitHub Pages 자동 배포 워크플로 |
| `.nojekyll` | Jekyll 처리 비활성화 |

## 슬라이드 구성 (20장)

커버 + 다음 19개 섹션으로 구성되어 있습니다.

1. 보고 목적 및 범위
2. Executive Summary
3. 프로젝트 개요
4. 전체 추진 일정 및 현재 위치
5. 종합 진행 현황
6. 영역별 진행 현황 — 기획
7. 영역별 진행 현황 — 디자인
8. 영역별 진행 현황 — 퍼블리싱
9. 영역별 진행 현황 — 개발
10. 산출물 작성 및 관리 현황
11. 요구사항 관리 현황
12. 요구사항 추적 현황
13. 변경관리 현황
14. 현업 피드백 반영 및 개발 전달 현황
15. 주요 이슈 및 리스크
16. 리스크별 대응 계획
17. 향후 추진 계획
18. 고객사 협조 요청사항
19. 결론 및 마무리

## 로컬에서 보기

별도 빌드가 필요 없는 정적 HTML입니다. 저장소를 클론한 뒤 `index.html`을
브라우저로 열거나, 간단한 정적 서버로 확인할 수 있습니다.

```bash
python3 -m http.server 8000
# http://localhost:8000 접속
```
