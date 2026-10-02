# 👋 안녕하세요, 문제를 정의하는 개발자 권유정입니다.

> **"기획이 코드가 되고 배포되기까지, 전체 사이클을 이해하고 직접 손대는 풀스택 개발자입니다."**  
> AI를 디버깅과 탐색의 도구로 적극 활용해 문제 해결 시간을 단축하고, 확보된 시간으로 **클라이언트가 멈추지 않는 방어 로직**과 **직관적인 UX**를 설계하는 데 집중합니다.

---

### 🛠 Tech Stack

**Languages & Frameworks**  
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Database & Infrastructure**  
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

### 🚀 Key Projects & Troubleshooting

#### 📌 LINKET | URL 정보 수집 & AI 요약 서비스
> **프론트엔드/앱 웹뷰 성능 최적화 및 Shell Script 기반 CI/CD 구축**

* **안드로이드 WebView 스크롤 렌더링 최적화**
  * Vue SPA를 안드로이드 WebView에 탑재 시 발생하던 스크롤 병목 현상 분석
  * iOS WKWebView 대비 높은 Chromium repaint 비용 대응: 안드로이드 한정 Blur/Shadow 비활성화, rAF 기반 스크롤 동기화, `ResizeObserver` 연쇄 재측정 방지 적용
* **비동기 백그라운드 파이프라인 설계**
  * URL 저장 시 Gemini AI 요약 처리를 백그라운드로 이전하여 '저장 즉시 응답' 구현
* **Shell Script CI/CD 배포 자동화**
  * `front_dist_push.sh` 및 `deploy_server.sh` 작성
  * 명령어 한 줄로 로컬 빌드, static 파일 업로드, FastAPI DB 마이그레이션 및 프로세스 재실행 파이프라인 구축

#### 📌 DEALLO | 가격 비교 & 알림 서비스
> **유저 중심 UX 설계 및 외부 API 장애 우회(Fail-over) 구현**

* **1-Click 가격 알림 설정 UX**
  * 사용자가 직접 숫자를 계산해 입력하는 번거로움을 최소화하기 위해 최저가, 5%/3% 할인가를 자동 계산하여 '딸깍' 한 번으로 등록하는 인터랙션 설계
* **대체 데이터(Fail-over) 우회 경로 설계**
  * 외부 API에서 메인 상품 정보(AF) 조회가 실패하더라도 서비스가 차단되지 않도록 대체 데이터(DS)로 자동 우회하는 장애 방어 로직 구현

#### 📌 MSAP | 금융 앱 유지보수 & 방어적 프로그래밍
> **AI 기반 30분 디버깅 및 데이터 무결성 방어벽 구축**

* **서버-클라이언트 API 명세 위반 즉시 진단**
  * AI에게 구체적 오류 동작 및 로그를 공유해 원인 범위를 축소, Integer 필드에 빈 문자열(`""`)이 전달되던 서버측 응답 오류를 30분 만에 규명
* **방어적 프로그래밍(Defensive Programming) 확립**
  * 파싱 에러 대응을 넘어, 네트워크 타임아웃 및 백업 데이터 주입 등 데이터 포맷 예외 처리 전반을 강화하여 **1년간 앱 크래시 0건** 달성

---

### 💡 Core Values

* **올라운더(All-rounder)의 시야**: 프론트/앱부터 백엔드, DB, Nginx 배포까지 서비스 전체 흐름을 이해하고 문제 발생 시 장애 원인을 즉시 추적합니다.
* **디버깅 도구로서의 AI**: AI에게 모호한 질문 대신 동작과 상황을 명확히 제시하여 문제 해결 탐색 시간을 수분 내로 줄입니다.
* **사용자 중심 & 방어적 설계**: 사용자의 대기 시간을 줄이는 비동기 처리와, 외부 API/서버의 예외 상황에서도 멈추지 않는 단단한 서비스를 지향합니다.

---

### 📫 Contact & Portfolio

* **Web Portfolio**: [portfolio-zeta-dun-66.vercel.app](https://portfolio-zeta-dun-66.vercel.app/)
* **Email**: `yujung@example.com` *(실제 이메일로 변경해 주세요)*
