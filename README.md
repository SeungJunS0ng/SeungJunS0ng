# 송승준 · Seungjun Song

Java와 Spring Boot로 백엔드를 개발합니다. Kotlin으로 Android 앱도 만들고 있습니다.  
최근에는 **FleaFlea**와 **마중**을 개발하며 API 구현부터 서버 배포, 동시 요청 처리, 연결이 끊긴 뒤의 복구까지 다루고 있습니다.

[이메일](mailto:john091122@naver.com) · [GitHub](https://github.com/SeungJunS0ng)

## 최근 프로젝트

### 마중 · Majung
차량 내비게이션과 탑승자의 휴대전화를 연결하는 픽업 서비스입니다. 운전자는 차량 앱에서 초대와 요청을 관리하고, 탑승자는 웹에서 차량 위치·도착 예정 시간과 준비 상태를 확인합니다.

**차량 앱·SDK 연동과 서버 통합·검증·배포를 맡았습니다.**

- Pleos Connect의 NaviHelper로 목적지·경유지·도착 예정 시간을 읽고, 기존 최종 목적지를 유지하면서 픽업 장소를 반영했습니다.
- Spring Boot로 차량·계정 연결, 픽업 초대와 요청, 대기열, 위치 공유 권한을 처리했습니다. 웹은 SSE로 변경을 감지한 뒤 최신 상태를 조회합니다.
- SDK 응답이 멈추거나 앱이 다시 실행되는 상황에 대비해 타임아웃, 픽업 복구, 공유 재개 확인을 구현했습니다. 오래된 위치·도착 예정 시간을 현재 정보처럼 보여주지 않도록 처리했습니다.
- GCP에 HTTPS 서비스와 GitHub Actions 배포를 구성했습니다. Blue/Green 전환 시 로그인 세션을 DB로 공유하고, 백업·복원과 배포 실패 시 복구 절차를 검증했습니다.

Pleos 공식 에뮬레이터에서 개발·시험한 프로젝트이며, 실제 차량 검증과 앱마켓 출시는 아직 진행하지 않았습니다.

[프로젝트 소개](https://github.com/majung-team/majung) · [백엔드](https://github.com/majung-team/majung-backend) · [차량 앱](https://github.com/majung-team/majung-vehicle-app) · [웹](https://github.com/majung-team/majung-web)  
[서비스](https://majung.cloud/account) · [API 문서](https://majung.cloud/api/swagger-ui/index.html) · [사용 안내](https://github.com/majung-team/majung/wiki)

### FleaFlea · 플리플리
친구끼리 플리마켓을 열고 물건을 거래하는 서비스입니다.

**백엔드 기능 개발과 GCP 서버·배포 환경 구성을 맡았습니다.**

- 마켓·도감 변경에 Redisson 분산 락과 DB 잠금을 적용하고, 동시 요청과 Redis 장애 상황을 시험했습니다.
- WebSocket·STOMP 채팅과 Redis Pub/Sub을 연결해 서로 다른 앱 프로세스 사이에서도 채팅 이벤트를 전달하도록 구성했습니다.
- 상품 댓글·대댓글과 접근 권한을 구현하고, 부모 댓글 삭제와 답글 작성이 겹치는 상황을 검증했습니다.
- GCS 이미지 저장·서명 URL, 썸네일과 캐시 정책을 다루고, 상품 상세 응답에서 불필요한 이미지 조회를 줄였습니다.
- GitHub Actions, Artifact Registry, Nginx로 Blue/Green 배포를 구성했습니다. 운영·개발 환경을 분리하고 DB 백업·복원, 로그와 장애 알림을 정리했습니다.

`Java` · `Spring Boot` · `JPA / QueryDSL` · `PostgreSQL` · `Redis / Redisson` · `WebSocket / STOMP` · `GCP` · `Docker` · `GitHub Actions` · `k6`

[백엔드 저장소](https://github.com/hyundai-autoever-team3/fleaflea-backend) · [기술 Wiki](https://github.com/hyundai-autoever-team3/fleaflea-backend/wiki) · [서비스](https://fleaflea.app) · [API 문서](https://api.fleaflea.app/swagger-ui/index.html)

## 이전 프로젝트

| 프로젝트 | 작업 내용 | 링크 |
| --- | --- | --- |
| 산업 장비 모니터링 대시보드 | Spring Boot 장비·센서 API, MQTT 데이터 수신, Redis 최신 상태 저장, WebSocket 전송 및 MCP 기반 대시보드 조작 | [백엔드](https://github.com/SeungJunS0ng/DashBoard/tree/develop) · [팀 저장소](https://github.com/jaewoongyoo/2026_Capstone_Team1) |
| Battery Insight | Kotlin·Jetpack Compose Android 앱, 배터리 데이터 수집, MQTT 전송, 백그라운드 작업과 Room 로컬 저장 | [저장소](https://github.com/jaewoongyoo/2026-HSU-CSE_Graduation_Project-BMS) |
| MOTMAP | Spring Boot·카카오맵 기반 맛집 저장·검색, JWT 인증, 위치·주소 검색 및 거리순 정렬 | [저장소](https://github.com/SeungJunS0ng/MOTMAP) |

## 주로 사용하는 기술

| 영역 | 기술 |
| --- | --- |
| 백엔드 | Java, Spring Boot, Spring Security, Spring Data JPA, QueryDSL |
| 데이터·통신 | PostgreSQL, MySQL, Redis, WebSocket, SSE, MQTT |
| 차량·Android | Kotlin, Android Automotive OS, Pleos Connect, Jetpack Compose, Room |
| 배포·운영 | GCP, AWS EC2, Docker, GitHub Actions, Nginx, Caddy |
| 검증 | JUnit, Testcontainers, k6 |

문제가 생기면 재현 조건을 먼저 만들고, 수정한 뒤 같은 조건으로 다시 확인합니다. 배포나 장애 대응 과정에서 확인한 내용은 각 프로젝트의 PR과 Wiki에 기록하고 있습니다.
