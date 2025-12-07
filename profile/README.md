# 🤖 FusionCrew

<div align="center">

### **AI 점원형 음성 대화 키오스크 시스템**

음성 인식과 AI를 활용한 차세대 무인 키오스크 솔루션

[![Frontend](https://img.shields.io/badge/Frontend-React%2019-61DAFB?style=for-the-badge&logo=react)](https://github.com/FusionCrew/Frontend)
[![Backend](https://img.shields.io/badge/Backend-Spring%20Boot%203-6DB33F?style=for-the-badge&logo=springboot)](https://github.com/FusionCrew/Backend)
[![AI](https://img.shields.io/badge/AI-FastAPI-009688?style=for-the-badge&logo=fastapi)](https://github.com/FusionCrew/AI)

</div>

---

## 🎯 프로젝트 소개

**AI 점원형 음성 대화 키오스크 시스템**은 기존 터치 기반 키오스크의 한계를 극복하고, 음성 대화를 통해 누구나 쉽게 사용할 수 있는 차세대 키오스크 솔루션입니다.

### ✨ 주요 기능
- 🎤 **음성 인식 주문** - 자연스러운 대화로 메뉴 주문
- 🤖 **AI 추천** - 사용자 맞춤형 메뉴 추천
- 👁️ **얼굴/포즈 감지** - MediaPipe 기반 사용자 인식
- 🔊 **음성 응답** - TTS를 통한 친근한 안내

---

## 🛠️ 기술 스택

| 분야 | 기술 |
|------|------|
| **Frontend** | React 19, TypeScript, Vite, TailwindCSS |
| **Backend** | Java 21, Spring Boot 3.2, Gradle |
| **AI Server** | Python 3.11, FastAPI, OpenAI API |
| **AI/ML** | MediaPipe (Face/Pose Detection), Speech Recognition |

---

## 📂 리포지토리

| 리포지토리 | 설명 | 링크 |
|------------|------|------|
| **Frontend** | React 기반 키오스크 UI | [바로가기](https://github.com/FusionCrew/Frontend) |
| **Backend** | Spring Boot API 서버 | [바로가기](https://github.com/FusionCrew/Backend) |
| **AI** | FastAPI AI 추론 서버 | [바로가기](https://github.com/FusionCrew/AI) |

---

## 👥 팀원 소개 및 업무 분담

### 이대연 (팀장) `2020114025`
> 소프트웨어공학과 4학년

| 담당 업무 |
|----------|
| 프로젝트 전체 구조 기획 리딩 |
| Node.js 서버 Express 기반 서버 구축 |
| LLM-STT-TTS 연동 및 음성 대화 프로필 구현 |
| AI 캐릭터 UI 설계 |
| Whisper-GPT를 활용한 음성 분석 처리 구성 |
| 데이터 흐름 설계 및 관리 / Cloud 엔지니어링 |
| 데이터 학습 |

---

### 김지나 `2022192006`
> 산업디자인학과 3학년

| 담당 업무 |
|----------|
| UX/UI 개발 총 수요 프로토타입 설계 |
| 기초 UI디자인 형성 및 동작 기반 시각 디자인 |
| 언어적·음성적 행동 분석 기반 UX 고도화 |
| 인터렉션 모션디자인 개발 및 조형감 개발 |

---

### 유현곤 `2022158002`
> 컴퓨터공학과 3학년

| 담당 업무 |
|----------|
| 콘텐츠 모션 개발 운영 |
| STT 입력 처리 및 음성 피드백 로직 개발 |
| LLM기반 대화 흐름 및 MediaPipe Pose 연동 |
| 음성 기반 사용자 판단 및 DB 연동 |
| FastAPI 딥러닝 서버 구축 |

---

### 이다하 `2023158022`
> 소프트웨어공학과 3학년

| 담당 업무 |
|----------|
| 프로젝트 프로토타입 제작 |
| 음성 행동 인식 용도 분석 |
| 영상·버튼 키 입력 기반 이벤트 분기 공동 개발 |

---

### 김나영 `2022150004`
> 컴퓨터공학과 3학년

| 담당 업무 |
|----------|
| 프로젝트 문서 정리 |
| Node.js Express 관련 API 개발 |
| POS 연동 프런트 외부 키오스크 구축 |
| 상호음성 인식 기반 주문 처리 기능 개발 |

---

## 📊 발표 자료

<details>
<summary><b>📌 1차 발표</b></summary>
<br>

- 📄 [1차 발표 PPT (PDF)](../presentations/1차발표_15팀.pdf)

</details>

<details>
<summary><b>📌 2차 발표</b></summary>
<br>

> 🚧 준비 중...

</details>

<details>
<summary><b>📌 3차 발표</b></summary>
<br>

> 🚧 준비 중...

</details>

<details>
<summary><b>📌 4차 발표 (최종)</b></summary>
<br>

> 🚧 준비 중...

</details>

---

## 📅 프로젝트 일정

```
2025년                              2026년 1학기
 11월        12월         1월         2월         3월         4월         5월         6월
  │           │           │           │           │           │           │           │
  ▼           ▼           ▼           ▼           ▼           ▼           ▼           ▼
┌─────────────────┐
│ 디자인 기획 및  │
│ UI/UX 디자인    │
└─────────────────┘
            ┌─────────────────────────┐
            │ 프론트엔드 구현          │
            ├─────────────────────────┤
            │ 행동 분류 데이터 학습    │
            ├─────────────────────────┤
            │ 백엔드 API 설계 및 구현  │
            └─────────────────────────┘
                        ┌─────────────────────────┐
                        │ LLM + STT + TTS         │
                        │ MediaPipe Pose 연동     │
                        └─────────────────────────┘
                                    ┌─────────┐
                                    │기능 다듬기│
                                    └─────────┘
                                              ┌─────────┐
                                              │ 2차 발표 │
                                              └─────────┘
                                                        ┌─────────┐
                                                        │기능 마무리│
                                                        └─────────┘
                                                                  ┌─────────┐
                                                                  │ 3차 발표 │
                                                                  └─────────┘
                                                                            ┌─────────────────┐
                                                                            │ 개발 보완 및    │
                                                                            │ 전시회 준비     │
                                                                            └─────────────────┘
```

| 기간 | 주요 내용 |
|------|----------|
| **2025.11** | 디자인 기획 및 UI/UX 디자인 |
| **2025.12** | 프론트엔드 구현, 행동 분류 데이터 학습, 백엔드 API 설계 및 구현 |
| **2026.01** | LLM + STT + TTS, MediaPipe Pose 연동 |
| **2026.02** | 기능 다듬기 |
| **2026.03** | 2차 발표 |
| **2026.04** | 기능 마무리 |
| **2026.05** | 3차 발표 |
| **2026.06** | 개발 보완 및 전시회 준비 |

---

<div align="center">

**FusionCrew** © 2025~2026

*한국공학대학교 졸업작품 프로젝트*

</div>
