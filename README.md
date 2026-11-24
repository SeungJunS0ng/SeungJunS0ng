<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,45:0891b2,100:34d399&height=200&text=Welcome%20to%20Seungjun%27s%20GitHub&animation=fadeIn&fontColor=F8FAFC&fontSize=45" width="100%" />

  <br>

  # Seungjun Song

  ### Backend & Mobile Developer

  Spring Boot 기반 백엔드, Android·iOS 모바일 앱, 실시간 데이터 파이프라인을 설계하고 운영하는 개발자입니다.

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
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat&logo=googlecloud&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

### Mobile & Client

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=flat&logo=jetpackcompose&logoColor=white)
![Room](https://img.shields.io/badge/Room-3DDC84?style=flat&logo=android&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat&logo=swift&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-007AFF?style=flat&logo=swift&logoColor=white)

### Tools

![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ%20IDEA-000000?style=flat&logo=intellijidea&logoColor=white)
![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?style=flat&logo=androidstudio&logoColor=white)
![Xcode](https://img.shields.io/badge/Xcode-147EFB?style=flat&logo=xcode&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)

---

## Featured Projects

### 마중 · Majung

> 차로 누군가를 데리러 갈 때, 차량 내비게이션의 위치·도착 예정 시간을 기다리는 사람의 휴대폰에 실시간으로 공유하고 탑승 준비 상태와 만날 장소를 주고받는 서비스입니다.

- Pleos NaviHelper로 목적지·경유지·도착 예정 시간을 읽고 차량 앱에 반영
- 픽업 초대·요청·대기열과 위치 공유 권한 구현, SSE·Web Push로 탑승자 웹·iOS 실시간 상태 갱신
- SwiftUI · ActivityKit 기반 iOS 앱(잠금화면 Live Activity·외부 지도 연동) 구현 및 병렬 UI 테스트 CI 구성
- SDK 타임아웃과 앱 재실행 시 픽업 복구 처리, GCP Blue/Green 무중단 배포와 DB 백업·복원 검증

**Tech**  
`Kotlin`, `Android Automotive OS`, `Pleos Connect`, `Swift`, `SwiftUI`, `ActivityKit`, `Spring Boot`, `PostgreSQL`, `SSE`, `Web Push`, `GCP`, `GitHub Actions`

[Project Repository](https://github.com/majung-team/majung)  
[iOS Repository](https://github.com/majung-team/majung-ios)  
[Web Service](https://majung.cloud/account)  
[Project Wiki](https://github.com/majung-team/majung/wiki)

---

### FleaFlea · 플리플리

> 지인끼리 플리마켓을 열어 물건을 거래하고, 거래한 물건 기록을 도감처럼 함께 관리하는 서비스입니다.

- 마켓·도감 변경에 Redisson 분산 락과 DB 잠금을 적용하고 동시 요청 검증
- 상품 댓글·대댓글 API와 마켓 참여자·작성자 권한 구현
- GCP와 GitHub Actions로 Blue/Green 무중단 배포 및 DB 백업·복원 자동화 구성

**Tech**  
`Java`, `Spring Boot`, `PostgreSQL`, `Redis`, `Redisson`, `Docker`, `GCP`, `GitHub Actions`, `k6`

[Backend Repository](https://github.com/hyundai-autoever-team3/fleaflea-backend)  
[Web Service](https://fleaflea.app)  
[Project Wiki](https://github.com/hyundai-autoever-team3/fleaflea-backend/wiki)

---

### Industrial Equipment Monitoring & MCP AI Automation Dashboard

> 공장 설비의 센서 상태를 대시보드에서 실시간으로 확인하고, 자연어 채팅만으로 장비 조회부터 대시보드 위젯 편집까지 자동화한 관제 시스템입니다.

- SECS/GEM 장비의 센서 데이터를 MQTT로 수집하고, 새 장비·센서가 연결되면 자동 등록되도록 구현
- Redis로 최신 설비 상태를 캐싱하고 WebSocket(STOMP)으로 대시보드 화면을 실시간 갱신
- MCP Server를 연동해 자연어 명령으로 장비·센서 조회 및 위젯 생성·수정·삭제 자동화
- Spring Boot 기반 장비·센서·대시보드·위젯 도메인 API 및 AWS EC2·Docker 운영 환경 구성
- GitHub Actions 기반 테스트·빌드, EC2 자동 배포, 서비스 재시작 및 헬스체크 자동화

**Tech**  
`Java`, `Spring Boot`, `Spring Security`, `JWT`, `JPA`, `PostgreSQL`, `Redis`, `MQTT`, `Kafka`, `RabbitMQ`, `WebSocket`, `Docker`, `AWS EC2`, `GitHub Actions`, `MCP`

[Backend Repository](https://github.com/SeungJunS0ng/DashBoard/tree/develop)  
[Full Stack Repository](https://github.com/jaewoongyoo/2026_Capstone_Team1)  
[Project Wiki](https://github.com/jaewoongyoo/2026_Capstone_Team1/wiki/%EC%BA%A1%EC%8A%A4%ED%86%A4-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EC%B5%9C%EC%A2%85-%EC%9C%84%ED%82%A4-%EC%A0%95%EB%A6%AC)

---

### Battery Insight - SOH Android

> 스마트폰으로 배터리의 전압·전류·온도·잔량 데이터를 수집해 서버로 전송하고, AI가 분석한 배터리 수명(SOH) 결과를 실시간으로 확인하는 Android 진단 앱입니다.

- Jetpack Compose로 로그인, 배터리 등록·선택, 실시간 진단 대시보드, SOH 결과 및 커뮤니티 화면 구현
- BatteryManager API로 전압·전류·온도·잔량(SOC)을 수집하고 ViewModel·Repository 계층으로 상태 관리
- Foreground Service·WorkManager·BootReceiver로 앱이 백그라운드에 있어도 끊기지 않게 진단 유지
- AWS IoT MQTT 실시간 전송과 네트워크 장애 시 HTTP fallback 전송 흐름 구성
- Room DB로 진단 세션·로그를 로컬 저장하고 스키마 마이그레이션 이슈 해결

**Tech**  
`Kotlin`, `Jetpack Compose`, `Android`, `Room`, `Ktor Client`, `MQTT`, `WorkManager`, `Foreground Service`, `REST API`

[Repository](https://github.com/jaewoongyoo/2026-HSU-CSE_Graduation_Project-BMS)  
[Project Wiki](https://github.com/jaewoongyoo/2026-HSU-CSE_Graduation_Project-BMS/wiki/%EC%95%88%EB%93%9C%EB%A1%9C%EC%9D%B4%EB%93%9C-%EC%A3%BC%EC%9A%94-%EB%82%B4%EC%9A%A9)

---

## Focus On

- 실시간 데이터 수집, 저장, 캐싱, 브로드캐스트 흐름 설계
- Spring Boot 기반 REST API와 인증/권한 처리
- Android·iOS 앱의 백그라운드 작업, 로컬 저장소, 서버 연동
- 운영 환경에서 발생하는 배포, 네트워크, 프로세스 문제 디버깅
- Swagger, Wiki, README를 통한 문서화와 협업 가능한 개발 흐름
