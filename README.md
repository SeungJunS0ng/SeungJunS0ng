<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,45:0891b2,100:34d399&height=200&text=Welcome%20to%20Seungjun%27s%20GitHub&animation=fadeIn&fontColor=F8FAFC&fontSize=45" width="100%" />

  <br>

  # Seungjun Song

  ### Backend & Android Developer

  Spring Boot 기반 백엔드, Android 앱, 실시간 데이터 파이프라인을 중심으로 공부하는 개발자입니다.

  <br/>

  [![GitHub](https://img.shields.io/badge/GitHub-SeungJunS0ng-181717?style=flat&logo=github&logoColor=white)](https://github.com/SeungJunS0ng)
  [![Email](https://img.shields.io/badge/Email-john091122%40naver.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:john091122@naver.com)
</div>

---

## 🛠 Tech Stack

### Backend

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat&logo=springsecurity&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring%20Data%20JPA-59666C?style=flat&logo=hibernate&logoColor=white)

### Data, Messaging & Infra

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat&logo=eclipsemosquitto&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![AWS EC2](https://img.shields.io/badge/AWS%20EC2-FF9900?style=flat&logo=amazonaws&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

### Android & Client

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=flat&logo=jetpackcompose&logoColor=white)
![Room](https://img.shields.io/badge/Room-3DDC84?style=flat&logo=android&logoColor=white)

### Tools

![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ%20IDEA-000000?style=flat&logo=intellijidea&logoColor=white)
![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?style=flat&logo=androidstudio&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)

---

## Featured Projects

### Industrial Equipment Monitoring & MCP AI Automation Dashboard

> SECS/GEM 기반 산업 장비 데이터를 MQTT, Spring Boot, Redis, WebSocket으로 연결한 실시간 통합 모니터링 시스템입니다.  
> MCP Server를 통해 자연어 명령으로 장비 조회, 센서 조회, 위젯 생성/수정/삭제를 자동화했습니다.

- Spring Boot 기반 장비, 센서, 대시보드, 위젯 도메인 API 구현
- MQTT metadata/telemetry payload 수신 및 장비/센서 자동 등록 흐름 구현
- Redis 최신 snapshot 캐싱 및 WebSocket(STOMP) 실시간 브로드캐스트 구현
- AWS EC2, Docker, PostgreSQL, Redis, MQTT Broker, RabbitMQ 운영 환경 구성
- GitHub Actions 기반 Gradle test/build, EC2 배포, systemd restart, health check 자동화

**Tech**  
`Java`, `Spring Boot`, `Spring Security`, `JWT`, `JPA`, `PostgreSQL`, `Redis`, `MQTT`, `Kafka`, `RabbitMQ`, `WebSocket`, `Docker`, `AWS EC2`, `GitHub Actions`, `MCP`

[Backend Repository](https://github.com/SeungJunS0ng/DashBoard/tree/develop)  
[Full Stack Repository](https://github.com/jaewoongyoo/2026_Capstone_Team1)  
[Project Wiki](https://github.com/jaewoongyoo/2026_Capstone_Team1/wiki/%EC%BA%A1%EC%8A%A4%ED%86%A4-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EC%B5%9C%EC%A2%85-%EC%9C%84%ED%82%A4-%EC%A0%95%EB%A6%AC)

---

### Battery Insight - SOH Android

> 스마트폰을 보조배터리 진단용 데이터 수집 게이트웨이처럼 활용해 전압, 전류, 온도, SOC를 수집하고 서버 및 AI 진단 결과와 연동하는 Android 기반 IoT 진단 앱입니다.

- Jetpack Compose 기반 로그인, 배터리 등록/선택, 실시간 진단 대시보드, SOH 결과 화면 구현
- ViewModel, Repository 계층 분리로 화면 상태와 API 호출 로직 관리
- BatteryManager API 기반 SOC, 전압, 전류, 온도, 충전 상태 수집
- Foreground Service, WorkManager, BootReceiver, BroadcastReceiver로 백그라운드 진단 안정성 보완
- AWS IoT MQTT telemetry 전송 및 HTTP fallback 흐름 구성
- Room DB 기반 로컬 세션/로그 저장 및 migration 문제 디버깅
- Community API 연동으로 게시글 조회, 필터, 상세, 삭제, SOH 히스토리 조회 구현

**Tech**  
`Kotlin`, `Jetpack Compose`, `Android`, `Room`, `Ktor Client`, `MQTT`, `WorkManager`, `Foreground Service`, `REST API`

[Repository](https://github.com/jaewoongyoo/2026-HSU-CSE_Graduation_Project-BMS)  
[Project Wiki](https://github.com/jaewoongyoo/2026-HSU-CSE_Graduation_Project-BMS/wiki/%EC%95%88%EB%93%9C%EB%A1%9C%EC%9D%B4%EB%93%9C-%EC%A3%BC%EC%9A%94-%EB%82%B4%EC%9A%A9)

---

### MOTMAP - Kakao Map 기반 맛집 지도 서비스 🍽️

> **Spring Boot 3.2**와 **카카오맵 API**를 연동하여 지도 기반의 맛집 저장, 실시간 거리 계산, 위치 탐색 및 리뷰를 제공하는 Full-Stack 웹 서비스입니다.

- **인증 & 권한**: Spring Security + JWT 기반 회원가입/로그인 및 작성자 소유권 기반 CRUD 접근 제어 구현
- **위치 & 지도 UX**: GPS 현재 위치 Pulse 마커, 등록 예정 드래프트 핀, 검색/필터 시 지도 영역 자동 맞춤(`fitBounds`) 구현
- **실시간 거리 계산**: Haversine 공식을 적용한 내 위치 기준 맛집 거리 배지(`350m`, `1.2km`) 및 거리순 정렬 기능 개발
- **주소 검색 & 지오코딩**: 카카오 지오코더 연동을 통한 도로명/건물명 직접 주소 검색 및 좌표 자동 매핑 구현
- **디자인 & 편의성**: Glassmorphism 및 다크/라이트 테마, 커스텀 토스트 알림, XSS 보안 방어 및 실시간 필드 유효성 검사 적용
- **안정적인 아키텍처**: MySQL 8 연동, Bean Validation, 전역 예외 처리(GlobalExceptionHandler) 및 Swagger UI 문서화

**Tech**  
`Java 17`, `Spring Boot 3.2`, `Spring Security`, `JWT`, `Spring Data JPA`, `MySQL 8`, `Swagger`, `Thymeleaf`, `JavaScript (ES6+)`, `Kakao Map API`

[Repository](https://github.com/SeungJunS0ng/MOTMAP)

---

## Focus On

- 실시간 데이터 수집, 저장, 캐싱, 브로드캐스트 흐름 설계
- Spring Boot 기반 REST API와 인증/권한 처리
- Android 앱의 백그라운드 작업, 로컬 저장소, 서버 연동
- 운영 환경에서 발생하는 배포, 네트워크, 프로세스 문제 디버깅
- Swagger, Wiki, README를 통한 문서화와 협업 가능한 개발 흐름
