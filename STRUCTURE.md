# STRUCTURE · daysom-sample (v0.1 · 아이보리 · 그레이지 + 튤 · 빛 그림자 + 자간 넓은 세리프 · 연분홍 포인트 · 모서리 2px · 배포 예정 daysom-sample.lgt3232.workers.dev)

```
daysom-sample/
├─ index.html                 단일 파일 (CSS · JS 인라인)
├─ wrangler.toml              name = daysom-sample
├─ .assetsignore              img/ · _old/ · 문서 · index_*.html · _deploy 배포 제외
├─ ds-pretendard-v01.woff2    한글 · 본문 (Pretendard 300–600)
├─ ds-bellefair-v01.woff2     영문 (Bellefair 400, 영문 · 숫자만)
├─ ds-hero.webp               히어로 튤 사진(사장님 daysom beauty 글자 포함)
├─ ds-owner.webp              about 원장 사진 720×900
├─ ds-led.webp                LED 연장 사진
├─ ds-light.webp · ds-shadow.webp   섹션 사이 빛 · 그림자 띠 배경
├─ ds-w1~w6.webp              시술 사진
├─ favicon.png · og-ds.jpg
├─ img/                       다올 제공 원본 + _원문.md (배포 제외)
└─ CHANGELOG.md / STRUCTURE.md  (로컬 정본 · 업로드 안 함, R-38)
```

## 섹션 순서
헤더(sticky · daysom · 메뉴 5 · 카카오 채널 예약 / 900 미만 `.snav`) → 히어로 → 빛 띠 → `#about` → `#led`(그레이지) → `#curl` → 그림자 띠 → `#works` → `#price`(그레이지) → `#booking` → `#visit`(그레이지) → 푸터 + 모바일 `.quick`.

## 버튼 · 링크
- 카카오 채널 `https://pf.kakao.com/_BxkgXn`(메인): 헤더 · 히어로 · 예약 · 푸터 · 하단 바
- 전화 `tel:050714820861`: 히어로 · 예약 · 오시는 길 · 하단 바
- 네이버 플레이스(「네이버 예약」 버튼 · 푸터) · 네이버 지도 `map.naver.com/p/entry/place/1912242615` · 인스타 · 블로그
- 구글 지도 검색어 「경기 평택시 용죽5길 11」(배포 후 핀 확인 · R-35)

## 모션 (강제 재생)
- `.reveal` setInterval · 앵커 rAF(R-25). reduced-motion 분기 없음.

## 폰트 재생성
문구 바꾸면 빠진 글자 검사 + 파일 이름 버전 올리기(R-43).
