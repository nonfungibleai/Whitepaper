# ATC Whitepaper

ATC(Apt Trust Currency) — 아파트 신탁화폐 개념을 설명하는 웹 백서입니다.

## 구성

- `index.html` — 통합 백서 (01 소유구조 · 02 정산절차 · 03 부동산공개념화폐 · 저자 소개)
- `archive/` — 이전 시안들
  - `v1-ledger.html` — 등기부/문서 스타일 단일 인포그래픽
  - `v2-cardnews.html` — 스와이프 카드뉴스 형태
  - `v3-schematic.html` — 블루프린트 구조도 (01)
  - `v3b-settlement.html` — 정산절차 워터폴 (02)

## 배포

정적 HTML로만 구성되어 있어 Vercel/Netlify/GitHub Pages 어디든 별도 빌드 없이 바로 배포 가능합니다.

### Vercel로 배포하기
1. 이 저장소를 Vercel에 Import
2. Framework Preset: **Other** (정적 파일)
3. Build Command 없음 / Output Directory: `./`
4. Deploy
