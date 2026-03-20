# 👋 Hello, i am Han(이중한)

실제 운영 환경에서 발생하는 문제를 **웹 애플리케이션으로 해결하는 개발자**입니다.

I build production-ready web applications that solve real operational problems.

Next.js · React · TypeScript 기반으로  
**모바일 퍼스트 UX, 인증/권한 설계, 데이터 흐름 구조화, LLM 기반 입력 파이프라인 설계**를 강점으로 합니다.

I focus on:
- Mobile-first UX
- Authentication & role-based access
- Clear data flow design
- Preventing user mistakes through preview & validation

> “기능을 만드는 개발자”가 아니라  
> “운영이 가능한 구조를 설계하는 개발자”를 지향합니다.

---

## 🔥 Main Project

### ☕ Cafe Ledger (PWA) — 실제 사용 중인 내부 운영 툴

가족이 운영하는 카페에서 **실제로 사용 중인** 예치금/미수금/예약 관리 PWA입니다.

A production PWA used in a real café.

#### 핵심 설계 포인트

- 📱 모바일 퍼스트 UX (스마트폰 기준 설계)
- 👥 직원 초대 및 역할 기반 접근 제어 (Supabase RLS)
- 📊 예약 → 장부 자동 반영
- 🧾 부서(거래처) 단위 정산 구조 + 히스토리 관리
- 🤖 AI Helper (LLM 기반)
자연어 입력 → 예약 의도 파싱 → 미리보기 → 확인 → 안전하게 반영  
(OpenAI API 기반 입력 파이프라인)
- 🗄 Supabase(PostgreSQL) 기반 백엔드 구조 및 RLS 정책 직접 설계

특히, **사용자인 어머니가 헷갈리지 않도록**  
입력 단계를 단순화하고, 실수 방지 구조에 집중했습니다.

🔗 Live: https://nescafe-admin-pwa.vercel.app/

---

## ✍️ Writing (회고 기록: Retrospective)

Cafe Ledger를 개발하면서 겪은  
운영 이슈, RLS 정책 충돌, 예외처리 설계 등을 정리하고 있습니다.

About architecture decisions and real-world constraints.

🔗 Series:  
https://velog.io/@creyon0215/series/CafeLedger
  ---

  ## 🥗 나만의 영양코치 — AI
  Nutrition Coach (Cross-Platform)

  GPT-4o Vision + Supabase Edge
  Functions 기반의 AI 영양 관리
  앱입니다.
  iOS / Android / Web(PWA) 단일
  코드베이스로 동시 지원합니다.

  A cross-platform AI nutrition
  tracking app — iOS, Android, and
  Web from one codebase.

  #### 핵심 설계 포인트

  - 📸 AI 음식 인식 — 사진 촬영 시
  GPT-4o Vision이
  음식·중량·칼로리·매크로 자동 분석
  - ✍️  텍스트 AI 로깅 — 자연어 입력
  → GPT-4o-mini가 구조화된 영양
  데이터로 파싱
  - 🧮 개인 목표 계산 엔진 —
  BMR(Mifflin-St Jeor /
  Katch-McArdle) · TDEE · 목표별
  매크로 자동 설정
  - 🤖 AI 영양 코치 채팅 — 오늘 식단
   + 프로필을 컨텍스트로 주입한
  개인화 코칭
  - 📊 주간 통계 & 12주 체중 예측
  모델
  - 🔐 보안 설계 — OpenAI 키를 Edge
  Function 서버 시크릿으로 격리,
  클라이언트 미노출
    사용자당 AI 호출 10회 제한
  (`api_usage` 테이블 + HTTP 429)
  - 🌐 플랫폼 분기 번들링 —
  `FoodCamera.native.tsx` /
  `FoodCamera.tsx` 분리로
    `expo-camera`를 웹 번들에서
  완전히 제외

  🔗 Live (DEMO):
  [https://nutrition-coach-han.vercel.app/)

  ---

## ⚽ FcSquadMeter — Deployed

NEXON Open API 기반 계정/매치 데이터 비교 웹앱입니다.

A deployed web app built on NEXON Open API.

- 데이터 정규화 및 가공
- 비교 중심 UI 설계
- 통계 정보의 가독성 개선

🔗 https://fcsquadmeter.vercel.app/

---

## 🚀 Portfolio

현재 작업 및 프로젝트를 정리한 포트폴리오입니다.

include:
- Cafe Ledger 아키텍처 상세 분석
- AI 입력 파이프라인 설계 과정
- 권한 모델 및 RLS 구조
- 실제 운영 기반 문제 해결 사례

🔗 https://han-portfolio-six.vercel.app/

---

## 🧩 Other Project

### ✈ Holidays (Team Project, 2023 / Legacy)

라이프스타일·커머스 성격의 PWA 팀 프로젝트입니다.

My Ownership:
- Login/Auth 시스템 전체 설계 및 구현
- Payment 시스템 설계 및 연동
- 메인/로그인/매거진/결제 유도 플로우 개발
- PWA 설정 단독 진행
- Google Play 배포 → 심사(인증) 대기 단계까지 진행

현재 서비스는 만료되었으며,  
포트폴리오에서 GIF/이미지 기반으로 핵심 플로우를 정리했습니다.

---

## 🧠 Tech Stack

### Main
- Next.js
- React
- TypeScript

### Supporting
- Supabase (PostgreSQL / Auth / RLS)
- React Query
- Zustand
- Tailwind CSS
- OpenAI API (LLM)
- PWA
- Vercel

---

## 📬 Contact

- Email: ljhan0215@gmail.com
- GitHub: lbj23han
- Velog: https://velog.io/@creyon0215

---

> “매일 조금씩, 꾸준히 앞으로.”
