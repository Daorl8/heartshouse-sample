# STRUCTURE · heartshouse-sample (v0.1 · 편지 봉투)

```
heartshouse-sample/
├─ index.html                 단일 파일 (CSS·JS 인라인 · 봉투 아이콘 SVG symbol #env)
├─ wrangler.toml              name = heartshouse-sample → heartshouse-sample.lgt3232.workers.dev (Worker 이름도 같게)
├─ .assetsignore              img/ · _old/ · 문서 · index_*.html · _deploy 배포 제외
├─ hh-pretendard.woff2        한글 · 본문 (Pretendard 400–800, 쓰는 글자만)
├─ hh-outfit.woff2            영문 라벨 (Outfit 700–800, 라틴)
├─ hh-logo.webp / hh-logo-w.webp   로고 검정(헤더 · 히어로) · 흰(푸터) — 하트는 둘 다 파랑
├─ hh-hero.webp               히어로 (봉투 프레임 안)
├─ hh-writing / drawing       LETTER
├─ hh-pancake / parfait / brulee / kiwi / toast / plate   COFFEE & DESSERT
├─ hh-entry / door / stair / table / shelf / corner       THE HOUSE
├─ hh-sign                    VISIT (골목 COFFEE 의자)
├─ favicon.png · og-heartshouse.jpg
├─ img/                       다올 제공 원본 98장 (배포 제외 · 얼굴 사진 포함)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더 → 히어로 → `#letter`(띠색) → `#menu` → `#house`(띠색) → `#visit` → 푸터(먹) + 모바일 `.quick`(2칸).

## 규칙
- 굵은 선(5px) · 모서리 4px = 로고 선. 파랑 #1A6892은 라벨 · 포커스 · 호버만.
- 모바일 히어로: 봉투 사진 먼저(4:3) · 히어로 로고 숨김(헤더에 있음).

## 그리드
모든 그리드 칸 `minmax(0, …)`(LESSONS §27).

## 폰트 재생성
문구 바꾸면 빠진 글자 검사(LESSONS §26). Outfit은 영문 라벨에만(한글 넣지 말 것).
