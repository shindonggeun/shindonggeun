# 안녕하세요! 수영 국가대표를 꿈꿨던 소년에서 지금은 개발자가 된 신동근입니다.

Java/Spring Boot 기반 **백엔드 개발자**입니다. 현재 미래로시스템에서 **삼성전자 메모리 반도체 분석 시스템(A-DMS)** 의 MSA 아키텍처 설계와 서버 개발·운영을 맡고 있습니다.
기능을 만드는 데서 끝내지 않고, 데이터가 들어와서 저장되고 배포되어 운영되기까지 **서비스 전체 흐름을 책임지는 개발자**를 목표로 합니다.

### 💡 관심 분야
- **인증 / 인가**: Spring Security, JWT, OAuth 2.0(OIDC) 기반의 SSO 연동, Access/Refresh 이중 토큰, 계층적 인가처럼 보안성과 사용자 편의성을 함께 챙기는 계정·권한 체계
- **데이터 파이프라인**: 여러 소스에서 들어오는 데이터를 빠짐없이 수집하고, 다시 실행해도 안전하게(멱등) 적재하고, 분석·통계까지 잇는 흐름 설계
- **메시징 / 이벤트 기반 아키텍처**: RabbitMQ, Kafka로 서비스 간 결합을 낮추고 메시지 유실·중복·재처리를 다루는 구조
- **인프라 / DevOps**: CI/CD 자동화, 컨테이너 배포, 폐쇄망 운영, 모니터링
- **AI 기반 개발**: Claude Code·Codex 같은 AI 코딩 에이전트를 실무에 활용합니다. 서브 에이전트를 병렬로 돌리는 개발 오케스트레이터와 업무 자동화 스킬을 직접 만들어 쓰고, 사이드 프로젝트는 100% 바이브코딩으로 설계부터 운영까지 진행하고 있습니다

### 🏠 Home Lab
라즈베리파이5 4대와 미니PC 2대, **총 6대로 온프레미스 홈서버**를 직접 구축해 운영하고 있습니다.
- 호스트마다 역할(인그레스·스토리지, dev/prod 애플리케이션, DB, 모니터링, 빌드·메시징)을 나누고 IaC로 관리
- Nginx · Certbot · DDNS, Jenkins, Kafka, MySQL · PostgreSQL · Redis, MinIO, Vault, Prometheus · Grafana, Elasticsearch · Filebeat, Ollama(로컬 LLM)
- 개인·팀 프로젝트(Trading Desk, Hondigagae, BossPickSeoul 등)의 dev/prod 환경을 이 위에서 직접 운영합니다

### 🤝 일하는 방식
- 팀원이 어려움에 부딪혔을 때 가장 먼저 떠올리고, 편하게 도움을 청할 수 있는 동료가 되려고 합니다.
- 사용자 관점에서 더 빠르고 효율적으로 서비스를 제공하는 방법을 고민합니다.
- 새로운 기술을 배우는 것을 좋아하고, 배운 것은 블로그와 문서로 정리해 팀과 나눕니다.

## 🚀 Tech Stack
- **Language**: Java, JavaScript, TypeScript, Python
- **BackEnd**: Spring Boot, Spring Security, Spring Data JPA, QueryDSL, MyBatis, Spring Cloud(Gateway, Eureka, Config, OpenFeign), Spring Integration, Spring Batch, Spring AI, Quartz Scheduler, MapStruct, Flyway, FastAPI, SQLAlchemy
- **FrontEnd**: React, Vue.js
- **DataBase**: Oracle, MySQL, PostgreSQL, MariaDB, MS-SQL, MongoDB, Redis
- **Messaging**: RabbitMQ, Kafka
- **Infra / DevOps**: Linux(Ubuntu), Docker, Docker Compose, GitLab CI/CD, GitLab Runner, Jenkins, GitHub Actions, Nginx, Nexus, MinIO, HashiCorp Vault, AWS EC2, AWS Lightsail, Firebase
- **Monitoring**: Prometheus, Grafana, Spring Boot Actuator, Elasticsearch, Filebeat
- **AI Tools**: Claude Code, Codex, Cursor, Ollama
- **BigData**: Hadoop, Spark
- **Etc**: Git, GitHub, GitLab, Slack, Discord, Notion

## 🏢 Work
### 미래로시스템 · DM팀 백엔드/서버 개발 (2024.09 ~ 재직중)
> 삼성전자 DS부문 메모리 반도체 분석 시스템 **A-DMS** (2025.01 ~ )
> `Java 21` `Spring Boot 3` `Spring Cloud` `Spring Security` `Spring Integration` `Quartz` `Oracle` `Redis` `RabbitMQ` `GitLab CI` `Docker`
- Spring Cloud 기반 멀티 모듈 MSA 설계·구축, 삼성전자 DS SSO(OIDC) 연동과 계층적 인증/인가(JWT 이중 토큰)
- 고객사 APM DB 의뢰 데이터 증분 수집 파이프라인(Quartz · Redis 워터마크) 초기 설계·개발
- TEM 이미지 자동/수동 수집·변환 서비스 초기 설계·개발 (Spring Integration 파일 트리거, FTP + RabbitMQ 이벤트 전환, 비동기 업로드 · SSE 진행률)
- SPAS 계측 데이터 파이프라인(동적 CSV 파싱 · 멱등 적재) 및 레거시 → A-DMS 전환(Phase 2) 설계 주담당
- RabbitMQ 멀티테넌트(vhost 격리 · DLQ 재시도) 메시징, GitLab CI/CD 설계와 폐쇄망 배포
- 운영 패치 자동화: master MR 파이프라인 → 패치 분할 압축 · 그룹웨어 대용량 메일 · Slack 알림
- Claude Code 스킬 기반 개발·업무 자동화 (서브 에이전트 병렬 개발 오케스트레이터, 운영 패치 · MR · VOC 관리)

### 현대IT&E · 운영사업부문 그린푸드IT팀 선임 (2022.08 ~ 2022.12)
> 유통·외식 ERP 시스템 **H-WIS** 운영 및 개발
> `Java` `Spring` `Oracle` `Xplatform`
- 엑셀 업로드 → 검증 → DB 반영 흐름으로 영업회계 수불장 월 마감 업무를 자동화해 반복 수작업 제거
- Xplatform 기반 월 마감 업무 화면 개발
- 다수 테이블 조회·집계 Oracle SQL 개선, 현업 데이터 추출 요청 대응 및 ERP 운영

### 한국인식산업 · 연구소 개발팀 인턴 (2021.06 ~ 2021.08)
> 안면인식 솔루션 테스트 및 영상처리 프로그램 개발
> `Python` `OpenCV` `TensorFlow` `Keras`
- 안면인식 솔루션 테스트 프로그램과 OpenCV 기반 영상 전처리 기능 개발
- 사진·영상을 이용한 위조 인증을 구분하는 Liveness Detection 기능 개발·검증 참여
- 실시간 영상에서 마스크 착용 여부를 판별하고 결과를 화면에 표시하는 프로그램 개발

### 훈훈소프트 · 웹 개발팀 인턴 (2019.09 ~ 2020.01)
> 인플루언서 이커머스 서비스 **셀럽스토어** 개발 및 운영
> `Node.js` `Express.js` `Vue.js` `MySQL`
- 쇼핑몰과 백오피스의 프론트엔드(Vue.js)·백엔드(Express.js) 기능 개발 및 운영 유지보수
- Google Spreadsheet API를 연동해 페이징으로만 보던 사업자 매출을 스프레드시트로 한눈에 확인하도록 개선

## ⚙️ Education & Activities
* 💻 토스 Learner's High 서버 2기 [비바리퍼블리카] (2025.12.16 ~ 2026.01.15)
* 💻 토스 Learner's High 서버 1기 [비바리퍼블리카] (2024.12.16 ~ 2025.01.16)
* 💻 삼성 청년 SW 아카데미 10기 수료 [삼성전자, 멀티캠퍼스] (2023.07.05 ~ 2024.06.28)
* 💻 신한은행 해커톤 with SSAFY 해커톤 과정 수료 [삼성전자, 신한은행, 멀티캠퍼스] (2023.09.01 ~ 2023.09.17)
* 💻 MSA 기반 Full Stack 개발자 양성과정 수료 [한국소프트웨어산업협회 (KOSA)] (2022.02.17 ~ 2022.07.15)
* 💻 연세대학교 미래캠퍼스 디지털통신연구실 학부연구생 (2020.08 ~ 2021.06)
* 🎓 연세대학교 미래캠퍼스 컴퓨터정보통신공학부 정보통신공학과 졸업 (2020.03 ~ 2022.02, 4학기 수강)
* 💻 JAVA 프로그래밍 IT 실무 특강 과정 수료 [렉토피아] (2018.12.26 ~ 2019.01.15)
* 💻 C언어 & 기초자료구조 IT 전문과정 수료 [렉토피아] (2018.06.26 ~ 2018.07.23)
* 🎓 명지전문대 정보통신공학과 졸업 (2015.03 ~ 2020.02, 6학기 수강)

## 📜 Certificates
* 📄 2021.06 정보처리기사 [한국산업인력공단]

## ✋ Public Project History
* [100% 바이브코딩(Claude Code · Codex)으로 만든, LLM 멀티 에이전트 토론 실시간 중계 + 시장 수급 대시보드 1인 트레이딩 데스크, Trading Desk](https://github.com/shindonggeun/trading-desk)
* [관광 데이터를 기반으로 반려견 맞춤 여행을 설계하고 여행 의사결정을 돕는 AI 기반 스마트 관광 서비스 (2026 관광데이터 활용 공모전), Hondigagae](https://github.com/8llow8llowMe/hondigagae) → https://www.hondigagae.com
* [서울시 상권 공공데이터 기반 상권 분석 서비스, BossPickSeoul](https://github.com/8llow8llowMe/bosspickseoul) → https://dev.bosspickseoul.com
* [여행 미션 기반 보드게임형 관광 서비스 (공모전 본선 진출), TripMarble](https://github.com/8llow8llowMe/tripmarble)
* [서울시 상권 분석 서비스 플랫폼 (SSAFY 자율 프로젝트 우수상), NowDoBoss](https://github.com/8llow8llowMe/NowDoBoss)
* [빅데이터 기반 일본어 회화 학습 서비스 플랫폼 (SSAFY 특화 프로젝트 우수상), Talkydoki](https://github.com/shindonggeun/Talkydoki)
* [여러 명이 동시에 실시간으로 여행 계획을 작성하는 웹 서비스, PlanCard](https://github.com/shindonggeun/PlanCard)
* [신한은행 X SSAFY 해커톤 프로젝트 → 동아리/학생회 공금 관리 모바일 서비스, SSoC](https://github.com/SSoc-Student-SOCiety/SSoc)

## 👑 Awards
* 🏅 2024.05.24 삼성 청년 SW 아카데미 2학기 자율 프로젝트 우수상 (2등)
* 🏅 2024.04.05 삼성 청년 SW 아카데미 2학기 특화 프로젝트 우수상 (2등)
* 🏅 2022.07.15 한국소프트웨어산업협회 MSA 기반 Full Stack 개발자 양성과정 최종 프로젝트 발표회 대상

## 📝 Blog
* 기술 블로그: https://dongker.tistory.com/

## 🤖 Algorithm
[![Solved.ac 프로필](http://mazassumnida.wtf/api/v2/generate_badge?boj=tlsehdrms124)](https://solved.ac/tlsehdrms124)
