![header](https://capsule-render.vercel.app/api?section=header&type=waving&color=6691FF)

<p align="center">
  <img width="318" height="125" alt="image" src="https://github.com/user-attachments/assets/e414058e-c97c-4e6e-90e7-ed3650a22a52" />
</p>
<p align="center">
  <b>LANEIGE 제품 데이터 히스토리 저장·분석 및 인사이트 제공 AI AGENT</b>
</p>

<br><br>

## I. 팀원 소개 (Team Members) 👥  
| 고희주(BE, FE) | 김소정(Crawling, FE) | 박유진(AI, FE) |
|:---:|:---:|:---:|
| <img src="https://github.com/HeejuKo.png" width="100"> | <img src="https://github.com/jxeong.png" width="100"> | <img src="https://github.com/dolmaroyujinpark.png" width="100"> ||  
| [@HeejuKo](https://github.com/HeejuKo) | [@jxeong](https://github.com/jxeong) | [@dolmaroyujinpark](https://github.com/dolmaroyujinpark) |

<br><br>

## II. 🌀 프로젝트 소개 (About Project) 🧐

**LAENIGE Insight Pocket**   LANEIGE 제품 데이터 히스토리 저장·분석 및 인사이트 제공 AI AGENT

1. **📈 랭킹 히스토리 자동 추적**
   - Amazon 카테고리별 실시간 랭킹 스냅샷 자동 수집
   - 제품별 순위 변동 기록 및 히스토리 누적
   - 주간 / 월간 / 연간 단위 순위 추이 시각화
   - 급상승·급하락 제품 자동 탐지

2. **📊 성과 대시보드 분석**
   - 베스트 셀러 랭킹 및 상세 성과 비교 가능
   - 판매 추이 시각화 차트 제공

3. **🥰 리뷰 감정 분석 및 키워드 인사이트**
   - 긍정/부정 감성 비율 자동 분석
   - 평점 분포 및 평판 지수 산출
   - 리뷰 키워드 기반 Aspect 분석 (ex. 보습력, 향 등)
  
4. **🤖 AI 분석**
   - 매일 중요 지표를 분석하여 '오늘의 인사이트' 제공
   - 선택한 데이터 기반 ChatGPT 연동 대화형 분석 및 분석 결과를 자연어 리포트 형태로 생성

5. **🛒 인사이트 카드 장바구니** :
   - 필요한 인사이트 카드를 선택해서 저장하여 여러 분석 결과를 하나의 Pocket에 수집
   - 카드별 시트 자동 분리 Excel 다운로드

<br><br>


## III. 📚 기술 스택 (Tech Stack) 📚  

<p align="center" style="display: flex; justify-content: center; gap: 10px; flex-wrap: wrap;">
    <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=TypeScript&logoColor=white" alt="TypeScript">
    <img src="https://img.shields.io/badge/React-61dbfb?style=for-the-badge&logo=React&logoColor=white" alt="React">
    <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=OpenJDK&logoColor=white" alt="Java">
    <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=Spring&logoColor=white" alt="Spring Boot">
    <img src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white" alt="Oracle">
<br>
    <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python">
    <img src="https://img.shields.io/badge/-selenium-%43B02A?style=for-the-badge&logo=selenium&logoColor=white" alt="Selenium">
    <img src="https://img.shields.io/badge/langchain-%231C3C3C.svg?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain">
    <img src="https://img.shields.io/badge/chatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white" alt="GPT">
    <img src="https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi" alt="Fast API">
    <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white" alt="Docker">
    <img src="https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS">
</p>

- 🌐 **TypeScript** & **React**: 사용자 친화적인 프론트엔드 인터페이스 개발
- 💻 **Java** & **Spring Boot**: 강력한 백엔드 서비스 구축
- 🗄️ **Oracle DB**: 스냅샷 기반 데이터 히스토리 관리
- 🕷️ **Selenium**: Amazon 데이터 자동 크롤링 시스템 구축
- ⚡ **FastAPI**: AI 분석 전용 API 서버
- 🤖 **LangChain** & **GPT API**: AI Agent Layer 구현
- 🐳 **Docker**: 백엔드, AI 서버 컨테이너화
- ☁️ **AWS**: 클라우드 배포 및 관리
- 🚀 **CI/CD**: Docker와 GitHub Actions를 활용한 자동 빌드 및 배포
- 🔄 **Git Workflow**: main 브랜치를 기준으로 기능 단위 브랜치 생성 → 이슈 번호 기반 브랜치 네이밍 → PR → 자동 빌드 → 테스트 통과 후 배포


<br><br>


## IV. 프로젝트 구조 (Project Structure) 🗂️
- **WebCrawling**: Amazon 데이터 자동 수집 및 가공
- **FE**: 사용자 인터페이스 및 데이터 시각화 
- **BE**: API 서버 및 데이터 관리
- **AI**: 대화형 분석 및 리포트 기반 인사이트 생성

<br><br>

## V. ERD 및 시스템 구조도 (ERD and Architecture) 📊  
### ERD
<img width="800" alt="LANEIGE Insight Pocket" src="https://github.com/user-attachments/assets/d7fd7c84-c455-4183-a8a2-8c859b9e2307" /><br>
### 시스템 구조도
<img width="800" alt="System Architect" src="https://github.com/user-attachments/assets/4f0f0a2b-c920-4213-b3c0-43a9749fb523" />

<br><br>

## VI. 시작 가이드 (Getting Started) 🚀  
1. **레포지토리 복제 (Clone the Repository)**  
   - Frontend:  
     `git clone https://github.com/2026-AMORE-InsightPocket/FE.git`  
   - Backend:  
     `git clone https://github.com/2026-AMORE-InsightPocket/BE.git`  

2. **프로젝트 디렉토리로 이동 (Navigate to the Project Directory)**  
   `cd <repository-name>`

3. **의존성 설치 (Install Dependencies)**  
   - Frontend:  
     `yarn install`
   - Backend:  
     `./gradlew build -x test`

5. **빌드 및 실행 (Build and Run)**  
   - Frontend:  
     `yarn run dev`  
   - Backend:  
     `./gradlew bootRun`

<br><br>


## VII.⭐ README 소개 (About this README) ⭐  
이 README는 **Insight Pocket** 프로젝트의 기술 스택, 구조, 시작 가이드를 간결하고 명확하게 설명합니다.

<br>

![footer](https://capsule-render.vercel.app/api?section=footer&type=waving&color=6691FF)

