# 🥬 FreshiNotei — AI 식재료 관리 앱

> **AI로 식탁 위의 낭비를 삭제하다**
> 
> 영수증 한 장으로 시작하는 스마트 냉장고 관리 서비스

<br>

## 📌 프로젝트 개요

**프레시노티(FreshiNotei)** 는 1인 가구를 위한 AI 기반 식재료 관리 앱입니다.  
영수증 OCR로 식재료를 자동 등록하고, 부패 위험도와 사용 빈도를 계산해  
"오늘 가장 먼저 먹어야 할 식재료"를 알려주는 솔루션입니다.

| 항목 | 내용 |
|------|------|
| **프로젝트 유형** | 멋쟁이사자처럼 아이디어톤 참가작 |
| **팀명** | DELETE |
| **역할** | 기획 · 디자인 리드 |
| **작업 기간** | 2026.04 ~ 2026.05 (약 5주) |
| **팀 구성** | 기획·디자인 1명, 프론트엔드 1명, 백엔드·발표 1명 |
| **결과물** | 100초 피칭 영상, IR DECK, 프로토타입 |

<br>

## 🎯 문제 정의

```
1인 가구 35% 시대 — 한 사람당 매년 18만 원이
음식물 쓰레기로 사라지고 있습니다.
```

- 매주 의욕적으로 장을 보지만 야근·약속에 치이다 보면 야채칸이 묘지가 되는 자취생의 반복 사이클
- 기존 앱들은 **일일이 수동 입력**해야 하고, **단순 유통기한 알림**에 그침
- "잊혀진 식재료가 상하기 전에 먼저 깨워주는" 서비스의 부재

<br>

## 💡 핵심 기능

| 기능 | 설명 |
|------|------|
| 📷 **스마트 등록** | 영수증 한 장 촬영 → AI가 품목·유통기한 3초 자동 등록 |
| 🔔 **지능형 알림** | 부패 위험도 + 사용 빈도 계산 → 오늘 먹어야 할 식재료 추천 |
| 🍳 **AI 레시피 큐레이션** | 냉장고 재료 기반 맞춤 레시피 제안 |
| 📊 **소비 통계 리포트** | 낭비 감소 시각화, 소비 패턴 분석 |

<br>

## 📁 자산 구성

```
FreshiNotei-Design/
│
├── 📄 README.md
│
├── 🖼️ 일러스트 자산 (9개).zip
│   └── 페르소나, 야채칸 Before/After, 영수증, 
│       4분할 일상, 활기찬 마트 등
│
├── 📱 UI 화면 자산 (16개).zip
│   └── OCR 스캔, AI 분석, 인식 결과, 냉장고 메인, 
│       가짜 기존 앱 UI 대조 시안 등
│
├── 📊 인포그래픽 자산 (2개).zip
│   └── 1인 가구 35% 통계, 연 18만 원 임팩트
│
└── 🎨 타이포 로고 자산 (3개).zip
    └── 워드마크, 시그니처 심볼, 풀버전 조합
```

<br>

## 🎨 디자인 시스템 v2

**"따뜻함(공감) + 스마트함(신뢰)"** 를 동시에 전달하는 시스템

### Color Tokens

| 토큰 | HEX | 용도 |
|------|-----|------|
| `brand-primary` | `#5FA855` | Fresh Green — 브랜드 메인 |
| `brand-accent` | `#E89042` | Coral Orange — 강조, 임팩트 |
| `bg-base` | `#F8F4ED` | Warm Cream — 메인 배경 |
| `text-primary` | `#2D3134` | Charcoal — 본문 |
| `state-danger` | `#D9534F` | Red — 위험 상태(D-1) |

### Typography
- **Primary Font**: Pretendard (한글 + 영문)
- **Type Scale**: Display 36px / H1 24px / H2 18px / Body 16px / Caption 12px

### Component Rules
- 카드: 16px radius, 상태별 좌측 4px 보더
- 버튼: 12px radius, 48px 높이 (모바일 터치 타겟)
- 간격: 8px 그리드 시스템

<br>

## 🎬 100초 피칭 영상 구조

Before/After 페어링 구조로 감정 곡선 설계

```
① 훅 (0:00~0:11)      금전 손실 상징 → 영수증
② BEFORE (0:11~0:33)   지원이의 좌절 사이클
③ 솔루션 (0:33~1:03)   OCR 3초 자동 등록 데모
④ AFTER (1:03~1:18)    변화한 지원이의 일상
⑤ 임팩트 (1:18~1:33)   기존 앱 대조 + 18만 원
⑥ 클로징 (1:33~1:40)   슬로건 + 브랜드
```

**핵심 시각 장치**
- 🧾 영수증 3중 변주: 손실 상징 → 사용자 도구 → 충분함의 상징
- 🥬 야채칸 Before/After: 검은 야채칸 ↔ 정돈된 야채칸
- 🔢 숫자 호응: "절반이 사라진다면?" → "35%" → "18만 원"

<br>

## 👤 페르소나 — 김지원

> 27세, 강남 IT 스타트업 마케터, 역삼동 1인 거주

- 월 식비 55만 원 (장보기 18 + 배달 22 + 외식 15)
- 2~3주마다 컬리 주문 → 야근·약속 → 야채칸 묘지 → 죄책감 → 재구매 사이클
- 노션 시도했지만 포기, 토스 가계부 보고 충격
- **"냉장고 정리하려고 앱까지 깔아야 하나? 싶었는데, 18만 원 버리고 있더라고요."**

<br>

## 🛠️ 사용 도구 및 스택

### Design
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white)
![Figma Make](https://img.shields.io/badge/Figma_Make-000000?style=flat&logo=figma&logoColor=white)

### AI Assets
![ChatGPT](https://img.shields.io/badge/ChatGPT_4o-74AA9C?style=flat&logo=openai&logoColor=white)
![Kling AI](https://img.shields.io/badge/Kling_AI-000000?style=flat)

### Collaboration
![Notion](https://img.shields.io/badge/Notion-000000?style=flat&logo=notion&logoColor=white)

### Video Production
![CapCut](https://img.shields.io/badge/CapCut-000000?style=flat)

<br>

## 🎓 배운 것

### 시각적 스토리텔링
- 100초 안에 감정 곡선을 설계하는 방법
- "톤이 다른 자산"으로 영상의 구간을 시각적으로 분리하는 기법
- 다큐멘터리 톤 + 일러스트 톤의 교차 활용

### 디자인 시스템 사고
- 시안 → 락(LOCK) → 시스템화의 단계적 진행
- 자산 간 시각적 일관성 유지를 위한 컬러·톤·스타일 규칙
- 프론트엔드 인계를 위한 토큰 기반 문서화

### 팀 협업
- 기획·디자인 리드로서 팀의 시각적 방향성 정립
- 명확한 자산 우선순위와 시간 예산 관리
- 심사 기준(문제정의 20% / 차별성 20% / 시장반응도 20% / 실현가능성 15%)에 맞춘 자산 배치

<br>

## 📎 관련 링크

- 🎬 [피칭 영상 보기]
  https://www.youtube.com/watch?v=EH6IoNMC-i4
- 📄 [IR DECK 보기]() *(추후 링크 추가)*
- 🌐 [프로토타입 데모]() *(추후 링크 추가)*

<br>

## 👥 팀 DELETE

| 역할 | 담당 |
|------|------|
| 기획 · 디자인 리드 | 신민종 |
| 프론트엔드 · 영상 | 이현석 |
| 백엔드 · 발표 | 이준호 |

<br>

## 📄 라이선스

이 프로젝트의 디자인 자산은 포트폴리오 목적으로 공개되어 있습니다.  
상업적 사용 및 무단 재배포를 금지합니다.

© 2026 FreshiNotei Team DELETE. All rights reserved.

---

<p align="center">
  <b>Made with 🥬 by Team DELETE</b>
</p>
