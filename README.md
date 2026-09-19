# 김형범 — AI·디지털 활용 강사 랜딩 페이지

영화감독·미디어교육자 출신 AI·디지털 활용 강사 김형범의 소개 원페이지 랜딩 사이트.

## 구성

단일 스크롤 페이지 (8개 섹션):

1. **Nav** — sticky 상단 내비게이션
2. **Hero** — 풀블리드 강사 사진 + 그라데이션 스크림
3. **기능 카드** — 생성형 AI 활용 / 스마트폰 디지털 교육 / AI 콘텐츠 제작 / 업무 활용과 자동화
4. **강사 소개**
5. **대표 강의** (01–04)
6. **강의 사례** (카드 그리드)
7. **경력** (테이블)
8. **문의** (이메일 · 전화)

## 기술

- 프레임워크·빌드 없는 **단일 정적 HTML** (`index.html`)
- Modernist 디자인 시스템 토큰을 인라인 CSS로 재현 (radius 0, accent `#ec3013`)
- 폰트: **Archivo**(라틴) + **Pretendard**(한글) — Google Fonts / jsDelivr CDN
- 아이콘: Lucide (인라인 SVG)
- 반응형: 데스크톱(4열) → 태블릿(2열) → 모바일(1열)

## 로컬에서 보기

정적 파일이라 그냥 `index.html`을 브라우저로 열면 됩니다. 폰트/이미지 경로 때문에 로컬 서버로 보려면:

```bash
python -m http.server 8000
# 또는
npx serve
```

## 에셋

- `assets/hero.png` — 히어로 배경 강사 사진

## 배포 (GitHub Pages)

저장소 **Settings → Pages → Branch: `main` / `root`** 로 설정하면
`https://<username>.github.io/profile_2026.09/` 에서 바로 서비스됩니다.
