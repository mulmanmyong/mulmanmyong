## 김지헌 (Kim Ji Heon) | Software Engineer

전자공학을 전공하고, 임베디드 시스템에서 웹 서비스로 개발 경험을 넓혀왔습니다.  
Java와 Spring Boot 기반의 백엔드 개발을 중심으로 인증, 데이터 조회, 배포 환경을 구현했습니다.  
최근에는 삼성전자 기업연계 프로젝트에서 데이터 구조 분석부터 API와 지도 화면 개발까지 맡았습니다.

<!--[Portfolio](https://canva.link/kz6tfj9fw8ruvin) | [Blog](BLOG_URL)-->

### Projects

#### NAIS | Network AI Insight System
2026.04.06 – 2026.05.21 (약 7주) / 삼성전자 기업연계 프로젝트

통신 품질 데이터와 AI 예측 결과를 지도에서 조회하고 비교하는 분석 시스템

**역할: 데이터 구조 분석 / 조회 API 및 지도 화면 개발**

- 주행 경로 주변의 통신 품질과 예측 결과를 확인하는 기능을 맡아 데이터 구조 분석부터 API, 지도 화면까지 개발
- 데이터별 구조와 조회 목적을 검토하고, 필요한 정보를 함께 조회할 수 있도록 저장 및 처리 방식 구성
- Python 기반 조회 API와 지도 화면을 연결해 실제 측정 데이터와 AI 예측 결과를 비교하는 기능 구현
- 조회 범위와 화면에 표시하는 데이터의 처리 방식을 조정해 API 응답 및 지도 렌더링 성능 개선

기업연계 프로젝트로 코드와 상세 자료 비공개

#### Finkids | 학급 금융 경제 교육 플랫폼
2026.02.19 – 2026.03.30 (약 6주) / SSAFY 특화 프로젝트 우수상

교실에서 직업 활동과 금융 거래를 경험하며 경제를 배우는 교육 서비스

**역할: 팀장 / 인증 및 학생관리 기능 개발 / 배포 환경 구성**

- 교사와 학생의 접근 권한을 구분하는 JWT 인증 구현. Refresh Token을 HttpOnly 쿠키와 Redis로 관리하고 로그인 상태 복구 기능 개발
- 학생 생성, 수정, 비활성화, 비밀번호 초기화를 위한 API와 React 관리 화면 개발
- Jenkins 멀티브랜치 파이프라인으로 MR 검증과 브랜치별 배포 구성. 개발·QA·운영 환경의 설정을 분리하고 개발 및 운영 DB 및 계정 분리
- 기능의 필요성과 일정을 검토해 팀의 구현 범위 조율. 팀원들과 세 차례 QA를 진행하며 회차별 발견 오류 약 20건 → 10건 → 3건으로 감소

#### Presento | AI 기반 발표 질의응답 보조 로봇
2026.01.06 – 2026.02.09 (5주) / SSAFY 공통 프로젝트 우수상

발표 현장에서 질문자를 찾고, 질문을 들은 뒤 AI의 답변을 음성으로 전달하는 서비스

**역할: 임베디드 개발 / 로봇 시스템 통합**

- 웹과 AI 담당자들이 주고받는 정보를 확인하고, MQTT 제어 명령과 상태 메시지를 로봇 코드에 반영
- Jetson과 Raspberry Pi 간 TCP 통신 및 모터 제어 구현. 질문자 탐색부터 질문 청취와 답변 출력까지 동작 순서 관리
- 로봇 회전 후 질문자 위치를 다시 탐지하는 보정 과정을 적용해 회전 오차에 대응
- MediaMTX와 GStreamer를 활용해 로봇 카메라 영상을 웹에서 확인할 수 있도록 스트리밍 연결

### Skills

#### 주요 사용 기술

| 분야 | 기술 |
| --- | --- |
| Backend | Java, Spring Boot |
| Database | MySQL, Redis |
| Infra | Linux, Docker, Jenkins, Nginx |

#### 프로젝트 활용 경험

| 분야 | 기술 |
| --- | --- |
| Data & API | Python, FastAPI, PostgreSQL, PostGIS, DuckDB |
| Frontend | JavaScript, TypeScript, React, Vue |
| Embedded & Robotics | C, C++, ROS, ROS2, MQTT |
| Streaming | MediaMTX, GStreamer |

### Education

| 기간 | 교육 |
| --- | --- |
| 2025.07.08 – 2026.06.30 | 삼성 청년 SW·AI 아카데미 14기 Java 트랙 수료 |
| 2019.03.04 – 2025.08.22 | 경북대학교 전자공학부 전공 / 컴퓨터학부 부전공 |

### Awards

| 수상일 | 수상 |
| --- | --- |
| 2026.03.30 | SSAFY 특화 프로젝트 우수상 — Finkids |
| 2026.02.09 | SSAFY 공통 프로젝트 우수상 — Presento |
| 2024.10.29 | HL FMA 자율주행 경진대회 장려상 |

### Certifications & Language

| 자격명 | 취득일 / 응시일 | 발급기관 |
| --- | --- | --- |
| SQL 개발자(SQLD) | 2026.09.11 | 한국데이터산업진흥원 |
| 정보처리기사 | 2025.09.12 | 한국산업인력공단 |
| OPIc IM2 | 2025.02.21 | ACTFL |

<!--
### Learning

[CS Study](https://github.com/mulmanmyong/Computer-Science-Study) | [Algorithm](https://github.com/mulmanmyong/algo)
-->