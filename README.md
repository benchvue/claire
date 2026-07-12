# Claire Kwon — Official Website

뮤지컬 배우 **클레어 권(Claire Kwon)**의 개인 웹사이트입니다.

## 🎭 Live Site

**https://benchvue.github.io/claire/index.html**

## 주요 기능

- **Claire on Tour (클레어 순회 공연 일정)** — 2026–2027 북미 투어 32개 도시 일정
  - 전체 투어 경로 지도 (탭하면 확대)
  - 좌우 화살표 / 스와이프로 넘기는 공연 카드 캐러셀 (모바일 1장 · 태블릿 2장 · PC 3장)
  - 각 도시의 대표 사진이 위키피디아에서 자동으로 로드되어 카드 배경에 표시
  - 오늘 날짜 기준 다음 공연에 `Next` 배지 자동 표시, 지난 공연은 흑백 처리
  - 카드를 탭하면 공연장 이름 표시
- **Photocards** — 앞/뒤로 뒤집히는 포토카드 18장 (탭하여 플립)
- **On Stage** — 무대 영상 6편 (첫 프레임 썸네일 + 재생 아이콘, 탭하면 전체 화면 재생)
- 모바일 우선 반응형 디자인

## 폴더 구조

```
claire/
├── index.html          # 사이트 전체 (HTML + CSS + JS 단일 파일)
├── README.md
├── images/
│   ├── map-1.png       # 투어 전체 일정 지도
│   ├── front_1.webp …  # 포토카드 앞면 (1–18)
│   └── back_1.webp …   # 포토카드 뒷면 (1–18)
└── videos/
    └── video_1.mp4 …   # 무대 영상 (1–6)
```

## 콘텐츠 업데이트 방법

- **공연 일정 수정**: `index.html`의 `PERFORMANCES` 배열을 편집 (일정 추가 시 캐러셀·카운터·Next 배지 자동 반영)
- **포토카드 교체**: `images/` 폴더에 `front_번호` / `back_번호` 파일 업로드 — 확장자는 webp/jpg/png 모두 지원, 대소문자 자동 인식
- **영상 교체**: `videos/video_번호.mp4` 업로드 — 권장 사양 1280×720 이상, H.264 MP4

## 권장 이미지 사양

| 용도 | 비율 | 권장 크기 |
|---|---|---|
| 포토카드 | 2:3 세로형 | 800 × 1200 px |
| 영상 | 16:9 가로형 | 1280 × 720 이상 |

---

© 2026 Claire Kwon · All Rights Reserved
