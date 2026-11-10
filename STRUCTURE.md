# STRUCTURE · heartshouse-sample (v0.2 · 편지지)

```
heartshouse-sample/
├─ index.html                 단일 파일 (CSS·JS 인라인 · 봉투 아이콘 SVG symbol #env)
├─ wrangler.toml              name = heartshouse-sample → heartshouse-sample.lgt3232.workers.dev (Worker 이름도 같게)
├─ .assetsignore              img/ · _old/ · 문서 · index_*.html · _deploy 배포 제외
├─ hh-myeongjo.woff2         제목 · 라벨 (나눔명조 Regular 400, 쓰는 글자만)
├─ hh-pretendard.woff2        본문 (Pretendard 400–700, 쓰는 글자만)
├─ hh-logo.webp / hh-logo-w.webp   로고 검정(헤더 · 히어로) · 흰(푸터) — 하트는 둘 다 파랑
├─ hh-hero.webp               히어로 (봉투 프레임 안)
├─ hh-writing / drawing       LETTER
├─ hh-pancake / parfait / brulee / kiwi / toast / plate   COFFEE & DESSERT
├─ hh-entry / door / stair / table / shelf / corner       THE HOUSE
├─ hh-sign                    VISIT (골목 COFFEE 의자)
├─ favicon.png · og-heartshouse.jpg
├─ _old/                      v0.1(굵은 선 · Outfit) 롤백용 (배포 제외)
├─ img/                       다올 제공 원본 98장 (배포 제외 · 얼굴 사진 포함)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더 → 히어로(흰) → `#letter`(아이보리) → `#menu`(흰) → `#house`(짙은 원목) → `#visit`(아이보리) → 푸터(짙은 원목) + 모바일 `.quick`(2칸).

## 규칙
- 선 1px · 모서리 2px(v0.2). 굵은 선은 로고 안에만. 파랑 #1A6892은 섹션 아이콘 · 포커스만.
- 모바일 히어로: 봉투 사진 먼저(4:3) · 히어로 로고 숨김(헤더에 있음).

## 그리드
모든 그리드 칸 `minmax(0, …)`(LESSONS §27).

## 폰트 재생성
문구 바꾸면 빠진 글자 검사(LESSONS §26). 두 서브셋 모두 다시.
