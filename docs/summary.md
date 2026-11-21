# 🧭 서비스 인프라 · 런칭 역량 요약

!!! info ""
    게임 서비스 인프라 설계와 신규 타이틀 오픈에 필요한 역량을 제 경험과 프로젝트에 연결해 정리했습니다. 프로젝트 이름을 누르면 상세 페이지로 이동합니다.

## 한눈에 보기

| 역량 | 관련 경험 | 프로젝트 |
|---|---|---|
| 대규모 온라인 서비스 인프라 설계·구축·운영 | 15년간 PC·모바일 온라인 게임 서비스의 서버 구조 설계와 라이브 운영. 글로벌 모바일 RPG의 대규모 트래픽 대응 구조 개선 | [마블 퓨처 파이트](projects/marvel-future-fight.md), [마계촌 온라인](projects/makaimura-online.md), [리니지 레드 나이츠](projects/lineage-red-knights.md) |
| 퍼블릭 클라우드(AWS) 기반 서비스 아키텍처 설계 | EC2, Aurora, ElastiCache, S3, GameLift, Lambda, SNS/SQS, CloudWatch을 이용해 3개 타이틀의 서비스 인프라 구축 | [트랜스포머 멀티 쇼크](projects/transformers-multi-shock.md), [Dubium](projects/dubium.md), [Relic Keepers](projects/relic-keepers.md) |
| 신규 서비스 오픈을 기술 책임자로 수행 | 팀장·파트장으로 프로토타입부터 서비스 오픈까지 서버 개발 일정과 우선순위를 관리하고 오픈을 준비 (일본 모바일, Steam 얼리 액세스, 모바일, 한국·중국 PC) | [트랜스포머 멀티 쇼크](projects/transformers-multi-shock.md), [Dubium](projects/dubium.md), [Relic Keepers](projects/relic-keepers.md), [마계촌 온라인](projects/makaimura-online.md) |
| 서버, 네트워크, DB, 스토리지 전반 이해 | 실시간 네트워크 엔진(ProudNet, LiteNetLib, SpanNetty, SignalR, MagicOnion) 설계와 전환, DB 설계·프로시저·쿼리 튜닝(MySQL, MS-SQL, Couchbase), 캐시(Redis, Valkey), S3 기반 로그 저장 | 전 프로젝트 |

## 장르별 서비스 아키텍처 경험

| 유형 | 특징 | 프로젝트 |
|---|---|---|
| MMO형 (상시 접속, 실시간) | 대규모 동시 접속 처리, 데이터 무결성과 트랜잭션, 실시간 지표 모니터링 | [마계촌 온라인](projects/makaimura-online.md), [L.O.E](projects/loe.md) |
| 세션·매치형 | 로비와 매치메이킹, 데디케이티드/실시간 인게임 서버 분리, GameLift 기반 세션 호스팅 | [Dubium](projects/dubium.md), [Relic Keepers](projects/relic-keepers.md) |
| 모바일 RPG (API형) | 요청/응답 기반 서버, 결제 검증, 대규모 트래픽 대응, 글로벌·일본 서비스 | [트랜스포머 멀티 쇼크](projects/transformers-multi-shock.md), [마블 퓨처 파이트](projects/marvel-future-fight.md), [리니지 레드 나이츠](projects/lineage-red-knights.md) |

## 런칭 준비와 서비스 오픈

- **일정과 리소스 관리**: 팀장·파트장으로 기능별 우선순위를 조정하고 개발 일정을 관리 (트랜스포머 멀티 쇼크, Dubium, Relic Keepers, 마계촌 온라인)
- **동시 접속 대비와 행사 대응**: Steam Next Fest 등 외부 행사에서 대규모 동시 접속에 대비한 서버 튜닝과 실시간 모니터링 (Dubium)
- **테스트 단계 운영**: CBT, FGT, 2차 CBT 기간의 이슈 대응과 서버 튜닝 (L.O.E, 마계촌 온라인, 리니지 레드 나이츠)
- **지역별 서비스 대응**: 한국·중국(마계촌 온라인), 글로벌(마블 퓨처 파이트), 일본(트랜스포머 멀티 쇼크, 리니지 레드 나이츠)
- **플랫폼 연동**: Steam, GamePot, 퍼블리셔 SDK 등 로그인·결제 시스템 연동과 검증
- **라이브 이후까지**: 오픈 후 라이브 운영과 서비스 종료까지 전 주기 경험

## 가용성, 확장성, 운영 효율

- **관측성**: Prometheus, Grafana, OpenTelemetry, Sentry 기반 모니터링 구축 / MFC 기반 실시간 지표(트래픽, 세션, 자원 사용량) 수집·시각화 툴과 알림 기능
- **로그와 데이터**: Fluentd → S3 로그 파이프라인, OpenSearch 로그 분석, BI 로그 설계와 Looker Studio 시각화
- **확장성과 최적화**: 대규모 트래픽을 고려한 서버 구조 개선, 병목 구간 분석과 성능 최적화, 쿼리 튜닝
- **장애 대응**: 라이브 이슈의 원인 분석과 구조 개선으로 재발 방지
- **품질**: 유닛 테스트로 코드 커버리지 80% 유지

## 표준화와 자동화

- **IaC**: AWS CloudFormation으로 서버 인프라 프로비저닝 템플릿 작성 (Dubium)
- **배포 자동화**: Jenkins, Ansible, AWX로 빌드·배포 파이프라인을 여러 타이틀에 반복 구축 (트랜스포머 멀티 쇼크, Dubium, Relic Keepers)
- **컨테이너**: Docker 기반 서버 환경 (Dubium)
- **운영 도구**: Blazor 백오피스를 3개 타이틀에서 반복 구축
- **AI 도구 활용**: Claude Code, GitHub Copilot, ChatGPT, Amazon Q를 개발 과정에 도입해 생산성 향상

## 유관부서 협업과 문서화

- Wiki를 구축해 유관 부서와의 협업 체계 정립 (트랜스포머 멀티 쇼크)
- 운영팀·QA팀이 직접 쓸 수 있는 알림, 로그 분석, 데이터 조회 도구 제공 (마계촌 온라인, 리니지 레드 나이츠)
- 외부 플랫폼·SDK 연동 과정의 이슈 분석과 대응 (Relic Keepers, 마블 퓨처 파이트)
