<h1 align="center">Han's GitHub</h1>

<p align="center">
  웹 애플리케이션과 자동화를 통해 실제 운영 문제를 해결합니다.
</p>

<p align="center">
  I build production-ready web applications, mini apps, and workflow automation systems focused on<br/>
  mobile-first UX, structured data flow, auth/RLS, practical AI integration, monetization, and operational efficiency.
</p>

<p align="center">
  <a href="https://han-portfolio-six.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-111111?style=for-the-badge&logo=vercel&logoColor=white" />
  </a>
  <a href="https://findmymoney.vercel.app/">
    <img src="https://img.shields.io/badge/Benefit_Finder-2563EB?style=for-the-badge&logo=moneygram&logoColor=white" />
  </a>
  <a href="https://updown-brief.vercel.app/">
    <img src="https://img.shields.io/badge/UpDown_Brief-0F172A?style=for-the-badge&logo=chartdotjs&logoColor=white" />
  </a>
  <a href="https://gymkidzone.vercel.app/">
    <img src="https://img.shields.io/badge/Gymkidzone-111111?style=for-the-badge&logo=googlemaps&logoColor=white" />
  </a>
  <a href="https://momecheck.vercel.app/">
    <img src="https://img.shields.io/badge/MomeCheck-0F172A?style=for-the-badge&logo=googlefit&logoColor=white" />
  </a>
  <a href="https://velog.io/@creyon0215">
    <img src="https://img.shields.io/badge/Velog-20C997?style=for-the-badge&logo=velog&logoColor=white" />
  </a>
  <a href="mailto:ljhan0215@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

---

## About Me

- **Next.js · React · TypeScript** 기반으로 서비스를 기획하고 개발합니다.
- **모바일 퍼스트 UX**, **인증/권한 구조**, **실수 방지형 입력 플로우**, **운영 가능한 데이터 구조 설계**에 강점이 있습니다.
- 단순히 화면을 구현하는 데서 끝나지 않고, **실제 사용자 환경에서 오래 운영될 수 있는 구조**를 중요하게 생각합니다.
- 기획, 화면 설계, 데이터 흐름, 예외 처리, 운영 관점까지 한 흐름으로 연결해서 보는 편입니다.
- 최근에는 웹앱을 **앱인토스(Apps in Toss) 미니앱 환경**으로 확장하며, 광고·인앱 결제·포인트 보상·프리미엄 권한 같은 수익화 구조까지 함께 실험하고 있습니다.

### AI & Automation

- AI를 단순 기능 추가가 아니라 **입력 보조, 파싱 자동화, 추천 고도화, 실수 방지 UX 개선**에 활용해왔습니다.
- **자연어 입력 → 구조화 데이터 변환 → 미리보기/검증 → 안전 반영** 같은 실제 서비스형 플로우 설계에 관심이 많습니다.
- 반복 작업은 가능한 한 자동화하여, **운영 비용을 줄이고 재사용 가능한 워크플로우**로 만드는 것을 중요하게 생각합니다.

### Apps in Toss / Mini App Experience

- **앱인토스(Apps in Toss)** 환경에서 실행되는 미니앱을 설계하고 배포한 경험이 있습니다.
- 일반 웹앱과 달리 제한된 모바일 WebView 환경, SDK 연동, 샌드박스 테스트, AIT 번들 배포, 콘솔 검수 흐름까지 고려해 개발했습니다.
- 인앱 광고, 보상형 광고, 인앱 결제, 상품 지급 처리, 서버 검증 흐름처럼 **실제 수익화와 운영에 필요한 기능**을 서비스 구조 안에 연결했습니다.
- 단순 기능 구현보다, 검수 기준·사용자 흐름·수익화 정책·서버 상태 동기화까지 함께 맞추는 데 집중했습니다.

> “기능을 만드는 개발자”보다  
> “실제 운영 가능한 구조를 설계하는 개발자”를 지향합니다.

---

## Main Projects

### 1) UpDown Brief

뉴스와 경제 지표를 바탕으로  
**시장과 생활에 어떤 영향을 줄지 빠르게 해석해주는 모바일 중심 경제 브리핑 서비스**입니다.

앱인토스 미니앱 환경에 맞춰 배포했으며, 뉴스 해석, 포인트 보상, 프리미엄 콘텐츠, 인앱 결제, 광고 수익화를 함께 설계했습니다.

**What I focused on**
- 경제 뉴스의 시장 영향도를 점수화하고 사용자가 이해하기 쉬운 형태로 재구성
- 환율·금리 데일리 리포트, 뉴스 임팩트, 직접 해석 기능 등 정보 소비 흐름 설계
- 포인트 보상, 출석, 광고 리워드, 프리미엄 멤버십을 연결한 수익화 구조 설계
- 앱인토스 SDK 기반 인앱 결제, 상품 지급 처리, 보상형 광고, 배너 광고 연동
- Vercel API와 Supabase 기반 사용자 상태, 포인트, 분석권, 프리미엄 기간 관리

**Tech**  
React · TypeScript · Vite · Apps in Toss · Supabase · Vercel Serverless Functions · OpenAI API

🔗 https://updown-brief.vercel.app/

---

### 2) Public Policy Finder

개인 조건에 맞는 정부 지원 정책을 탐색하고 우선순위화하여  
**받을 수 있는데 놓치고 있는 혜택을 발견하도록 돕는 서비스**입니다.

앱인토스 미니앱으로도 확장하며, 정책 탐색형 서비스에서 광고가 사용자 경험을 방해하지 않도록 배치와 노출 타이밍을 조정했습니다.

**What I focused on**
- 개인 조건 기반 정책 필터링 구조 설계
- 단순 나열이 아닌 **신청 가능성 × 혜택 크기** 중심 우선순위화
- 현실적인 가구 형태와 조건을 반영한 추천 방식
- 추천 이유를 설명할 수 있는 구조 설계
- 앱인토스 배너 광고 연동 및 정책 상세/리스트 흐름에 맞는 광고 배치

**Tech**  
Next.js · React · TypeScript · Public Data · Apps in Toss · Toss Ads

🔗 https://findmymoney.vercel.app/

---

### 3) Cafe Ledger (PWA)

가족이 운영하는 업체에서 **실제로 사용 중인 내부 운영 툴**입니다.  
예치금, 미수금, 예약, 거래처 정산을 모바일에서 쉽게 처리할 수 있도록 만들었습니다.

**What I focused on**
- 모바일 퍼스트 운영 UX
- 예약 → 장부 자동 반영 흐름 설계
- 직원 초대 및 역할 기반 접근 제어
- Supabase RLS 기반 권한 구조 설계
- 실사용자 관점의 단순한 입력 흐름과 실수 방지 UX

**AI Integration**
- 자연어 입력을 예약/장부 데이터로 해석하는 AI Helper 설계
- 자연어 입력 → 의도 파싱 → 미리보기 → 사용자 확인 → 안전 반영 구조 적용

**Tech**  
Next.js · React · TypeScript · Supabase · PostgreSQL · RLS · OpenAI API · PWA

🔗 https://nescafe-admin-pwa.vercel.app/

---

### 4) 헬린이맵 + 몸매체크

운동 입문자를 위한 **운동시설 탐색 서비스**와  
유입/관심 환기를 위한 **바디 목표 계산 도구**를 함께 설계한 프로젝트입니다.

#### 헬린이맵 (Gymkidzone)

리뷰, 가격, 시설 특성을 기반으로  
**초보자 친화적인 운동시설을 더 쉽게 찾도록 돕는 지도 기반 서비스**입니다.

**What I focused on**
- 지도 viewport 기반 데이터 조회 구조
- 시설 상세 lazy fetch 설계
- 리뷰/가격 기반 배지 및 점수화 구조
- “헬린이 친화 / 가성비 / 내향인 친화” 같은 탐색 기준 설계

🔗 https://헬린이맵.com

#### 몸매체크 (MomeCheck)

목표 몸 상태까지의 변화를 가볍게 계산해보는 **모바일 중심 웹 서비스**입니다.  
복잡한 입력 없이 빠르게 결과를 보여주고, 운동 관심 유저의 흥미를 유도하는 데 집중했습니다.

앱인토스 미니앱에서는 결과 화면에 전면형 광고를 연결하여, 사용자의 핵심 플로우를 방해하지 않는 위치에서 수익화를 실험했습니다.

**What I focused on**
- 빠른 진입과 낮은 입력 피로도
- 결과 중심 플로우 설계
- 모바일 퍼스트 UI
- 헬린이맵과 연결 가능한 유입/바이럴 도구 관점의 설계
- 앱인토스 전면형 광고 연동 및 결과 화면 중심 노출 설계

🔗 https://momecheck.vercel.app/

---

### 5) 꽃놀이맵 (Kkot Map)

봄철 나들이 사용자를 위한 **꽃구경 장소 탐색형 지도 서비스**입니다.  
지도 기반 탐색, 장소 리스트, 상세 정보, 커뮤니티 흐름을 모바일에서 빠르게 사용할 수 있도록 구성했습니다.

앱인토스 미니앱으로 배포하며, 지도형 서비스에서 광고가 사용자 경험을 방해하지 않도록 배치와 노출 타이밍을 조정했습니다.

**What I focused on**
- 지도 탐색과 리스트 탐색을 함께 고려한 모바일 UX
- 장소 상세 패널과 커뮤니티 흐름을 연결한 탐색 구조
- 지도 하단, 리스트 중간, 커뮤니티 영역 등 맥락에 맞는 광고 배치
- 앱인토스 AIT 빌드 및 미니앱 환경 대응
- 광고 노출이 핵심 행동을 가리지 않도록 lazy loading과 배치 전략 적용

**Tech**  
Next.js · React · TypeScript · Map UI · Apps in Toss · Toss Ads

---

## Mini App Monetization

앱인토스 미니앱을 통해 웹앱을 단순 배포하는 것을 넘어, 실제 운영 가능한 수익화 구조까지 실험하고 있습니다.

**Implemented**
- AIT 번들 빌드 및 앱인토스 샌드박스 테스트
- 인앱 결제 상품 목록 조회 및 구매 플로우
- `processProductGrant` 기반 상품 지급 완료 처리
- 분석권/프리미엄 멤버십 서버 상태 관리
- 배너 광고, 전면 광고, 보상형 광고 연동
- 광고 리워드 포인트 지급, 일일 제한, 쿨타임 처리
- Vercel Serverless Functions와 Supabase를 통한 서버 검증 흐름

**Why it matters**
- 미니앱은 일반 웹앱보다 검수, SDK, 결제, 광고 정책 제약이 강합니다.
- 이 환경에서 실제 출시 가능한 구조를 맞추며, 제품 개발과 운영 조건을 함께 다루는 경험을 쌓고 있습니다.

---

## Automation / Private Systems

### YouTube Content Automation Pipeline (Private)

콘텐츠 제작부터 업로드까지의 반복 작업을 줄이기 위해 만든 **영상 제작·업로드 자동화 파이프라인**입니다.

**What it does**
- 스크립트, 씬 프롬프트, 메타데이터, 설정 파일만 교체하면 새 영상 제작 가능
- 이미지 생성, TTS, BGM 구성, 썸네일 생성, 영상 렌더링, 업로드까지 일괄 실행
- 단계별 스킵 실행, 특정 씬 재생성, 오디오/자막 재합성 등 운영용 보정 플로우 지원
- YouTube 업로드를 위한 OAuth 기반 배포 흐름 포함

**Why it matters**
- 반복적인 제작 업무를 수작업이 아닌 **재사용 가능한 워크플로우**로 전환
- 콘텐츠 자체보다 **입력 구조화, 파이프라인 제어, 실패 복구, 운영 효율화**에 초점을 둠

**Tech**  
Python · FFmpeg · TTS · Prompt-based image generation · YouTube API · Workflow Automation

---

## Other Projects

### Apps in Toss Mini Apps

UpDown Brief, 꽃놀이맵, 혜택줍줍, 몸매체크 등 여러 서비스를 앱인토스 미니앱 형태로 확장하며  
광고, 인앱 결제, 보상 포인트, 프리미엄 권한 관리 같은 운영 기능을 실험하고 있습니다.

### Nutrition Coach

AI 음식 인식, 텍스트 로깅, 목표 매크로 계산, 코칭 기능을 포함한 영양 관리 앱

### FcSquadMeter

NEXON Open API 기반 계정/매치 데이터 비교 웹앱  
🔗 https://fcsquadmeter.vercel.app/

### Holidays

라이프스타일·커머스 성격의 팀 PWA 프로젝트  
인증, 결제, PWA 설정 중심으로 기여

---

## Writing

실제 서비스 개발 과정에서 겪은 문제와 해결 과정을 기록하고 있습니다.

- 운영 환경에서의 UX 개선
- Supabase RLS 정책 설계
- 예외 처리와 데이터 흐름 구조
- AI 입력 파이프라인 설계와 검증 흐름
- 앱인토스 미니앱 배포, 인앱 결제, 광고 수익화 연동 경험

🔗 https://velog.io/@creyon0215/series/CafeLedger

---

## Tech Stack

### Main

![Next.js](https://img.shields.io/badge/Next.js-111111?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-111111?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-111111?style=flat-square&logo=typescript&logoColor=3178C6)

### Supporting

![Supabase](https://img.shields.io/badge/Supabase-111111?style=flat-square&logo=supabase&logoColor=3ECF8E)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-111111?style=flat-square&logo=postgresql&logoColor=4169E1)
![React Query](https://img.shields.io/badge/React_Query-111111?style=flat-square&logo=reactquery&logoColor=FF4154)
![Zustand](https://img.shields.io/badge/Zustand-111111?style=flat-square)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-111111?style=flat-square&logo=tailwindcss&logoColor=06B6D4)
![OpenAI](https://img.shields.io/badge/OpenAI_API-111111?style=flat-square&logo=openai&logoColor=white)
![PWA](https://img.shields.io/badge/PWA-111111?style=flat-square)
![Vercel](https://img.shields.io/badge/Vercel-111111?style=flat-square&logo=vercel&logoColor=white)
![Apps in Toss](https://img.shields.io/badge/Apps_in_Toss-111111?style=flat-square)
![Toss Ads](https://img.shields.io/badge/Toss_Ads-111111?style=flat-square)
![Serverless](https://img.shields.io/badge/Serverless-111111?style=flat-square)

---

## Contact

- Email: **ljhan0215@gmail.com**
- GitHub: **lbj23han**
- Portfolio: **https://han-portfolio-six.vercel.app/**
- Velog: **https://velog.io/@creyon0215**

---

<p align="center">
  매일 조금씩, 꾸준히 앞으로.
</p>
