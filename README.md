<div align="center">

# 👋 안녕하세요, 개발자 홍민하입니다

**React · Node · Spring 풀스택 2년차, 지금은 LangGraph 기반 AI 에이전트를 만듭니다.**

로그 속의 단서를 추적해 문제의 뿌리를 해결하고,  
LLM · RAG · AI Agent로 실제로 동작하는 서비스를 만드는 개발자로 성장하고 있습니다.

[![Portfolio](https://img.shields.io/badge/Portfolio-portfolio--korit.vercel.app-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio-korit.vercel.app)
[![Email](https://img.shields.io/badge/Email-hlkm1667haha@naver.com-03C75A?style=for-the-badge&logo=naver&logoColor=white)](mailto:hlkm1667haha@naver.com)

</div>

---

## 🙋 About Me

- 🎓 컴퓨터공학 전공
- 💼 풀스택 웹 개발자 2년차 — 프론트엔드, 백엔드, 배포까지 서비스 전체 흐름을 구현
- 🏭 **MES 생산관리 시스템** 개발, **5개 제조사 납품 완료**
- 🦺 **SafeWith 현장 안전관리 SaaS** 개발 (RBAC, JWT 세션 관리)
- 🤖 LangGraph, RAG, Function Calling 기반 **AI 에이전트 개인 프로젝트 5개** 개발 및 배포
- 📚 현재 **[이스트캠프] AI 휴먼(멀티모달 · TTS/STT · 프롬프트 엔지니어링 · RAG)** 과정 수강 중 (2026.06 ~ 2026.11)

---

## 📈 Impact

| 성과 | 내용 |
| --- | --- |
| ⚡ 쿼리 응답 **95%↓** | 대용량 생산 이력 조회 5.2s → 0.28s (복합 인덱스, N+1 제거, 서버 페이징) |
| 🚀 대시보드 로딩 **77%↓** | 3.5s → 0.8s (`Promise.all` 병렬 호출) |
| 🔒 LOT 번호 중복 **0건** | DB 시퀀스 + UNIQUE 인덱스 + 재시도로 Race Condition 해결 |
| 🔑 강제 로그아웃 **0건** | Axios Interceptor 기반 401 감지 → Refresh Token 자동 재발급 |

---

## 🚀 Featured Projects

### 🤖 AI Agent Projects (개인 프로젝트)

| 프로젝트 | 설명 | 핵심 기술 | 링크 |
| --- | --- | --- | --- |
| 🔍 **PrSense** (피알센스) | PR이 열리면 diff를 분석해 인라인 리뷰 코멘트를 자동 작성하는 GitHub PR 리뷰 에이전트 | LangGraph · Chroma RAG · FastAPI · React · SSE | [Demo](https://prsenseapp-production.up.railway.app/) · [Repo](https://github.com/minhahamin/PrSense) |
| 🏢 **AI Agent Company** | 목표 한 줄로 CEO · Planner · Developer · Reviewer · Reporter 5개 에이전트가 협업해 보고서를 만드는 멀티에이전트 플랫폼 | LangGraph · FastAPI · Next.js · PostgreSQL | [Demo](https://ai-agent-company-production.up.railway.app/) · [Repo](https://github.com/minhahamin/ai-agent-company) |
| 💰 **PennyWise** (페니와이즈) | 카드 CSV · 영수증 사진을 LLM이 분류·분석해 예산 알림과 절약 팁을 제공하는 재무 에이전트 | LangGraph · FastAPI · Vision LLM · React · Recharts | [Demo](https://pennywise-production-9cf8.up.railway.app/) · [Repo](https://github.com/minhahamin/PennyWise) |
| 🏭 **ERPilot** (SmartERP) | 자연어로 ERP 데이터를 조회하고 사내 문서를 검색하는 AI Copilot이 결합된 B2B SaaS | NestJS · Prisma · PostgreSQL · Gemini Function Calling · RBAC | [Demo](https://smart-erp-fe-production.up.railway.app) · [Repo](https://github.com/minhahamin/SmartERP) |
| 🧭 **LearnPath** | 실제 웹 검색 결과에만 근거해 학습 로드맵을 만드는 ReAct 기반 큐레이터 (환각 URL 코드로 차단) | ReAct · Gemini · Tavily · FastAPI · React Query | [Demo](https://frontend-production-c5ba.up.railway.app) · [Repo](https://github.com/minhahamin/LearnPath) |

### 💼 Work Experience Projects

#### 🏭 MES 생산관리 시스템 — 5개 제조사 납품
> 기준정보 · 영업 · 생산 · 품질 · 자재를 통합 관리하는 제조 현장 MES

- **Stack**: Java · Spring · MyBatis · Oracle · JSP / React · Node.js · Nest.js · MariaDB
- 생산 계획 · 작업 지시 · 재고 · HACCP 온도일지 · KPI 불량률 · LOT 발급 · 권한 관리
- 대용량 쿼리 최적화(95%↓), API 병렬화(77%↓), LOT 동시성 이슈 해결

#### 🦺 SafeWith 현장 안전관리 시스템
> 현장 운영 · 안전 점검 · 근로자 · 협력사를 통합 관리하는 SaaS 플랫폼

- **Stack**: Next.js · React · Node.js · Express · PostgreSQL · REST API · JWT
- 위성 GIS 관제 대시보드, 보호구 지급 관리, 위험성 평가, RBAC 권한 관리
- Refresh Token 자동 재발급으로 점검 일지 작성 중 세션 단절 0건

---

## 🛠 Tech Stack

**Frontend**  
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Backend**  
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

**Database**  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)

**AI / Agent**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-FF6F00?style=flat-square)
![Function Calling](https://img.shields.io/badge/Function_Calling-4285F4?style=flat-square)

**Infra**  
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)

---

## 🐍 Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/minhahamin/minhahamin/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/minhahamin/minhahamin/output/github-snake.svg" />
  <img alt="GitHub contribution snake animation" src="https://raw.githubusercontent.com/minhahamin/minhahamin/output/github-snake.svg" />
</picture>

</div>

---

## 🤖 Currently Learning

LLM Application · Prompt Engineering · RAG Architecture · Vector Database · AI Agent (LangGraph) · Multimodal AI · TTS / STT

---

## 📚 Development Philosophy

> 좋은 개발자는 코드를 작성하는 사람이 아니라 문제를 해결하는 사람이라고 생각합니다.  
> 로그에서 단서를 찾고, 임시방편이 아닌 근본 원인을 해결해 사용자의 일상을 지킵니다.

---

## 📫 Contact

- 📧 Email: hlkm1667haha@naver.com
- 💼 Portfolio: https://portfolio-korit.vercel.app
