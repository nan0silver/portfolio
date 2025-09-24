# 🧑‍💻 은나현 | Backend Developer

안녕하세요! 저는 **백엔드 개발자를 꿈꾸며 기술로 사람을 이해하고 문제를 해결하는 개발자**를 지향하고 있는 은나현입니다.

Java와 Python을 기반으로 백엔드 시스템과 모바일 앱을 개발해왔으며,  
사용자 중심의 AI 기반 시스템 개발부터 DevOps 환경 구성, 데이터 기반 대시보드 제작 등 다양한 영역에 도전해왔습니다.  
기술을 넘어 **문제의 본질을 이해하고, 비즈니스 흐름을 개선하는 개발자**로 성장하고자 합니다.
[개발 블로그](https://nan0silver.github.io/about/)

---

## 🎓 학력

- **숙명여자대학교 IT공학과 석사** (2022.09 ~ 2025.02)  
- **숙명여자대학교 IT공학과 학사** (2018.03 ~ 2022.08)

---

## 🛠 기술 스택

- **언어**: Java, Python, SQL  
- **프레임워크**: Spring, Flask, Jinja, Flutter
- **DevOps**: Docker, GitHub Actions  
- **데이터베이스**: Supabase, Firebase, MySQL  
- **기타**: Git, Postman, OpenCV, Figma  
- **관심 분야**: 백엔드 시스템 설계, 사용자 중심 서비스, 데이터 시각화, 자동화 인프라

---

## 💼 주요 프로젝트

### 🖥️ 1. 시각장애인 강의 영상 해설 시스템  
> AI 기반의 다이어그램 자동 해설 시스템 개발  
- Python + OpenCV + Flask 기반 서버 개발  
- 다이어그램 객체 탐지 및 관계 분석 → 자동 설명 문장 생성  
- 사용자 피드백 기반 개선 → 만족도 9.82점, 이해도 2.1점 상승  
- 국제 학술대회 SCOPUS 논문 2편 게재  
- 📂 [GitHub 링크](https://github.com/LectureVoice/LectureVoice-server)

> 백엔드
>> - Python: 주 백엔드 언어
>> - Flask: 경량 웹 서버 프레임워크, RESTful API 구현
>> - OpenCV (cv2): 이미지 처리, 다이어그램 분석, 윤곽선 감지
>> - PySceneDetect: 비디오에서 장면 전환 감지
>> - NumPy: 수치 계산 및 배열 처리
>
> API 서비스
>> - Naver Clova OCR API: 이미지에서 텍스트 추출
>> - Google Cloud Image Captioning API: 이미지 설명 생성
>> - Google Cloud Text-to-Speech API: 텍스트를 음성으로 변환
>
> 저장소
>> - Firebase Realtime Database: 사용자 데이터 및 해설 저장
>> - Firebase Authentication: 사용자 인증
> 프론트엔드
>> - Flutter & Dart: 크로스 플랫폼 모바일 애플리케이션 개발
>> - Firebase Storage: 이미지 및 비디오 저장
>

---

### 📞 2. 친구하자 (시니어 맞춤 실시간 통화 매칭 서비스)  
> 고령자의 사회적 고립 해소를 위한 실시간 매칭·통화 서비스
- Spring Boot(WebFlux) + Redis + MySQL 기반 **하이브리드 매칭 대기열** 설계  
- Redis Lua 스크립트로 원자적 연산 구현 → **중복 매칭률 0%**  
- API 최적화 + 캐싱 전략으로 응답 지연 **200ms → 15ms (93% 개선)**  
- GA4 + BigQuery 로그 분석 기반으로 **통화 시간 15%↑, 이탈률 감소** 성과 검증  
- GitHub Actions CI/CD + CodeRabbit AI 코드리뷰로 **품질·운영 안정성 확보**  
- 📂 [GitHub 링크](https://github.com/chingoo-haja)

> 백엔드  
>> - Java: 주 백엔드 언어  
>> - Spring Boot(WebFlux): 논블로킹 서버, REST API 구현  
>> - JPA: 데이터 영속성 관리  
>> - Redis: 대기열 관리 및 캐싱  
>> - MySQL: 관계형 데이터 저장
>
> 데이터/분석  
>> - GA4: 사용자 행동 데이터 수집  
>> - BigQuery: 지표 분석 및 성과 검증  
>
> DevOps  
>> - GitHub Actions: CI/CD 자동화  
>> - Docker: 컨테이너 기반 배포 환경  
>> - CodeRabbit: AI 기반 코드리뷰 도구
>
> 프론트엔드
>> - React 18, TypeScript
>> - Vit: 빠른 개발 서버 및 빌드
>> - TailwindCSS 3: 유틸리티 퍼스트 CSS 프레임워크
>> - shadcn/ui: 고품질 UI 컴포넌트 라이브러리


---

### 💄 3. 우르르 (뷰티 프로필 기반 AI 추천 + 공동구매 플랫폼)  
> 사용자 뷰티 프로필 기반 맞춤형 상품 추천 + 그룹 구매 서비스 개발  
- FastAPI 기반 Two-Tower 임베딩 모델 구축 (사용자 프로필 ↔ 상품 매칭)  
- KoSBERT 임베딩 + Faiss 벡터 검색 → 개인 맞춤형 추천 구현  
- OCR 기반 화장품 성분·알러지 정보 추출 → 안전한 상품 추천 강화  
- Redis + MySQL + Faiss 하이브리드 저장소 설계로 실시간 검색 성능 최적화  
- MVP 단계에서 5주 내 프로토타입 완성, AWS 월 9만원 이내 비용 최적화 설계  
- 📂 [GitHub 링크](https://github.com/UruruLab)

> 백엔드  
>> - Python: 주 백엔드 언어  
>> - FastAPI: RESTful API 서버  
>> - MySQL: 사용자·상품 DB 관리  
>> - Redis: 캐싱 및 세션 관리  

> AI/추천  
>> - KoSBERT: 한국어 임베딩 모델  
>> - Two-Tower 구조: 사용자 ↔ 상품 임베딩 매칭  
>> - Faiss: 벡터 검색 엔진  

> 데이터 처리  
>> - OCR API: 상품 성분 정보 추출  
>> - Pandas: 데이터 전처리  
>> - Scikit-learn: 추천 모델 학습  

> 배포/운영  
>> - Docker: 배포 환경 표준화  
>> - AWS: 저비용 클라우드 운영 환경  

---

### 📊 4. 비트코인 트렌드 대시보드  
> 실시간 데이터 기반 대시보드 + DevOps 환경 구성  
- Flask 기반 REST API 서버 설계  
- Docker & GitHub Actions를 활용한 CI/CD 자동화 구축  
- 코인 시세, 뉴스, 시각화 차트 제공 (실시간)  
- 📂 [GitHub 링크](https://github.com/nan0silver/doge_trend_monitoring)

> Backend
>> Java (HTTP 요청, JSON 파싱)
>
> Data Analysis
>> OpenAI LLM (gpt-4)
>
> Visualization
>> Chart.js
>
> Deployment
>> GitHub Pages, GitHub Actions

---

## 🏆 활동 및 수상

- 2025 라스베가스 CES 글로벌 네트워킹 지원  
- Python / 운영체제 조교 (2022~2024, 숙명여대 인공지능공학부)  
- 제3회 IPS 프로젝트 대회 멘토 (2023)  
- 숙명여대 알고리즘 대회 은상 수상 (2021)

---

## 📄 주요 논문 (SCOPUS)

- *DiagramVoice: Automatic Lecture Video Commentator for Visually Impaired Students*  
  → ICICT 2024 발표 / Oral / 1저자

- *Design of Automatic Online Lecture Video Commentator for Visually Impaired Students*  
  → ISBM 2023 발표 / Oral / 1저자

- *Speech-Recognizing KIOSK Mobile Application for the Visually Impaired*  
  → ICETC 2022 발표 / Poster / 1저자

---

## 📫 연락처

- Blog: [https://nan0silver.github.io/](https://nan0silver.github.io/about/)  
- GitHub: [https://github.com/nan0silver](https://github.com/nan0silver)  
- Email: silvernh1220@gmail.com

---

> 💬 “기술은 사람을 이해할 때 더 의미 있습니다.”  
> 사용자와 문제의 맥락을 이해하고, 기술로 실질적인 변화를 만드는 개발자가 되겠습니다.
