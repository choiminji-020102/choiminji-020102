# 안녕하세요, 최민지입니다 👋

> AI가 코드를 대신 짜주는 시대에도, 결국 서비스를 사용하는 건 '사람'입니다.  
> 깊은 공감을 바탕으로 진짜 문제를 정의하고, 백엔드와 AI 기술을 결합해 사용자의 니즈를 직관적인 UX로 실현해 내는 개발자입니다.

📫 t3335150@gmail.com

<br>

## 🛠 Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

<br>

## 📌 Projects

### 📦 [월간지 구독관리 시스템](https://github.com/choiminji-020102/magazine-manager)
> 출판사의 엑셀·기억 속 발송 규칙을 관리 시스템으로 옮긴 실서비스 · **프리랜서 1인** · 2025.10 ~ 유지보수 중

- 월 약 3,000건 발송 명단을 **버튼 하나로 생성**, 발송 누락 0건
- 합포장·VIP·주문 유입 경로·변경 이력 등 색칠·메모로 관리하던 규칙을 시스템 기능으로 구현
- Cafe24 API(OAuth 2.0) 연동으로 주문 수집 ~ 배송 상태 변경 자동화 — 월 100건 수동 입력 제거
- 조용히 틀리던 장애 추적: 페이징 정렬 불안정(PK 2차 정렬로 쿼리 10곳 수정), 외부 API 실패의 건별 처리 전환

`FastAPI` `SQLAlchemy` `MySQL` `Alembic` `React` `TypeScript` `Tailwind`

<br>

### 📣 [다 맡케팅](https://github.com/choiminji-020102/Da-Matketing)
> 소상공인 SNS 게시물을 AI로 만들어 바로 올리는 마케팅 자동화 플랫폼 · **7인 팀** · 2025.07 ~ 09 · KT AIVLE 빅프로젝트 **대상**

- **담당: SNS 게시글 관리 축** (AI 에이전트 · 프론트엔드)
- LangGraph StateGraph 4노드(콘텐츠 분석 → 트렌드 분석 → 제목·본문 → 해시태그)로 역할 분리
- 단계별 모델·temperature 차등, 해시태그만 다시 만드는 **부분 실행 API** (LLM 호출 4회 → 2회)
- 업종·지역·날짜를 주입해 8개 범주로 트렌드를 받는 프롬프트, 플랫폼별 해시태그 규칙
- LLM 출력을 프롬프트에만 맡기지 않고 **코드로 후처리** (JSON 파싱 3단계 폴백, 해시태그 6단계 정규화)

`LangGraph` `LangChain` `FastAPI` `OpenAI` `React` `Redux`

<br>

### 🐄 [소담소담](https://github.com/choiminji-020102/Sodam-Sodam)
> 센서 없이 앱과 AI로 소규모 낙농가를 돕는 서비스 · **3인 팀, AI 파트 단독** · 2025.04 ~ 07 · 창업경진대회 **우수상**

- 낙농 전문 문서 기반 **RAG 챗봇 '소담이'** — 질문 의도를 4유형으로 라우팅하는 LangGraph 에이전트, 답변에 출처 표기
- 대화가 막히던 지점을 찾아 그래프 재설계: 노드 경계 재정의로 Over-blocking 해소, 이표번호 없이도 이어지는 5노드 서브그래프
- 럼피스킨병 진단 모델 학습(YOLOv8 분류), 유방염 위험도·착유량 예측(Random Forest)

`LangGraph` `ChromaDB` `OpenAI` `YOLOv8` `scikit-learn`

<br>

## 💼 Experience

| 기간 | 내용 |
|---|---|
| 2025.10 ~ | 도서출판 목자의지혜 · 프리랜서 풀스택 개발 |
| 2024.03 ~ 2024.08 | 삼성메디슨 AI Vision 그룹 인턴 |

## 🎓 Education

| 기간 | 내용 |
|---|---|
| 2025.03 ~ 2025.09 | KT AIVLE School 7기 AI 개발자 트랙 |

## 🏆 Awards

| 시기 | 내용 |
|---|---|
| 2025.09 | KT AIVLE School 7기 빅프로젝트 대상 |
| 2025.08 | 농림축산식품 공공데이터 활용 창업경진대회 우수상 |
