# 🛠️ 기술 스택

!!! note ""
    서비스 인프라와 운영에 관련된 기술을 먼저, 개발 언어와 프레임워크를 그 다음에 정리했습니다.
    모두 실무 프로젝트에서 사용한 기술입니다.

## 인프라 · 운영

| 분야 | 기술 | 사용한 프로젝트 |
|---|---|---|
| 퍼블릭 클라우드 | AWS (EC2, Aurora, ElastiCache, S3, GameLift, Lambda, SNS, SQS, CloudWatch) | 트랜스포머 멀티 쇼크, Dubium, Relic Keepers |
| IaC | AWS CloudFormation | Dubium |
| CI/CD · 구성 관리 | Jenkins, Ansible, AWX | 트랜스포머 멀티 쇼크, Dubium, Relic Keepers |
| 컨테이너 | Docker | Dubium |
| 모니터링 · 관측성 | Prometheus, Grafana, OpenTelemetry, Sentry, CloudWatch | 트랜스포머 멀티 쇼크, Dubium |
| 로그 · 분석 | Fluentd, S3, OpenSearch, BI 로그 설계, Looker Studio | 트랜스포머 멀티 쇼크, Dubium, Relic Keepers, 리니지 레드 나이츠 |
| 데이터베이스 · 캐시 | MySQL (Aurora), MS-SQL, Couchbase, Redis (ElastiCache), Valkey | 전 프로젝트 (DB 설계, 저장 프로시저, 쿼리 튜닝) |
| 웹 계층 | nginx | 마블 퓨처 파이트 |
| 플랫폼 연동 | Steam, GamePot, 퍼블리셔·사내 SDK | 로그인, 결제, 푸시 |
| 운영 도구 | Blazor, MudBlazor, MFC, Flask | 백오피스, 모니터링 툴, 운영 웹툴 |

## 서버 개발

| 분야 | 기술 |
|---|---|
| 언어 | **C#**, C++, Java, Python, Go |
| 네트워크 · 서버 프레임워크 | MagicOnion, SpanNetty, Netty, SignalR, LiteNetLib, ProudNet, RakNet, Boost, protobuf, MemoryPack |
| 웹 · 백엔드 | Spring Boot, Jetty, Flask, Jinja2, Echo, Gin, EF Core, Dapper, AutoMapper |
| 테스트 | NUnit |

## 기타

| 분야 | 기술 |
|---|---|
| AI 개발 도구 | Claude Code, GitHub Copilot, ChatGPT, Codex, Amazon Q |
| 앱 개발 | Dart, Flutter |
| 게임 엔진 (클라이언트 협업) | Unity, Unreal Engine 4/5 |
| 협업 · 형상 관리 | Jira, Confluence, Redmine, Git, Plastic SCM, SVN |
