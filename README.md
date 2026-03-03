# 👋 Hello, i am Han(이중한)

실사용 환경에서 발생하는 문제를 **운영 가능한 웹앱으로 해결하는 프론트엔드 개발자**입니다.

I build web applications that solve real operational problems.

Next.js · React · TypeScript 기반으로  
**모바일 퍼스트 UX**, **인증/권한 설계**, **데이터 흐름 구조화**를 강점으로 합니다.

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
- 🤖 AI Helper (진행 중)  
  자연어 입력 → 미리보기 → 확인 → 안전하게 반영

특히, **실사용자인 어머니가 헷갈리지 않도록**  
입력 단계를 단순화하고, 실수 방지 구조에 집중했습니다.

🔗 Live: https://nescafe-admin-pwa.vercel.app/

---

## ✍️ Writing (설계 회고 기록)

Cafe Ledger를 개발하면서 겪은  
운영 이슈, RLS 정책 충돌, 예외처리 설계 등을 정리하고 있습니다.

About architecture decisions and real-world constraints.

🔗 Series:  
https://velog.io/@creyon0215/series/CafeLedger

주요 내용:
- 외부 공휴일 데이터 분리 관리
- Supabase RLS 정책 설계 및 충돌 해결
- 멀티 매장(shop) 구조 설계
- 취소/수정/미수 처리 등 예외 케이스 모델링
- 고연령 사용자 UX 설계

---

## ⚽ FcSquadMeter — Deployed

NEXON Open API 기반 계정/매치 데이터 비교 웹앱입니다.

A deployed web app built on NEXON Open API.

- 데이터 정규화 및 가공
- 비교 중심 UI 설계
- 통계 정보의 가독성 개선

🔗 https://fcsquadmeter.vercel.app/

---

## 🚀 Portfolio (배포 예정)

현재 포트폴리오 사이트를 정리 중입니다.

Will include:
- Cafe Ledger 아키텍처 상세 분석
- AI 입력 파이프라인 설계 과정
- 권한 모델 및 RLS 구조
- 실제 운영 기반 문제 해결 사례

🔗 Coming Soon

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
- Supabase (Auth + RLS)
- React Query
- Zustand
- Tailwind CSS
- Vercel

---

## 📬 Contact

- Email: ljhan0215@gmail.com
- GitHub: lbj23han
- Velog: https://velog.io/@creyon0215

---

> “매일 조금씩, 꾸준히 앞으로.”
