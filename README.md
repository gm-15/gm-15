# Welcome to GunWoo's GitHub! 👋

> 업무의 조건을 이해하고, 정합성, 운영 안정성, 확장성까지 고려해 설계하는 백엔드 엔지니어입니다.

## About Me 🧑‍💻

- 상명대학교 소프트웨어학과 4학년, 2027.02 졸업 예정
- Java, Spring Boot 기반 백엔드를 중심으로 데이터 정합성과 운영 안정성을 고민
- 문제 발생 시 증상에 머무르지 않고 메트릭과 테스트를 통해 원인을 좁혀 검증
- 기능의 정상 동작뿐 아니라 실제 결과와 운영 환경까지 확인

## Projects 🗂️

| 프로젝트 | 기간 | 역할 | Key Engineering | Repository |
|---|---|---|---|---|
| 🛒 **Clmakase**<br>대규모 트래픽 대응 클라우드 플랫폼 | 26.02 ~ 26.02 | 팀장<br>백엔드, 인프라 | 150K VU 부하 테스트, EKS에서 Aurora까지 병목 추적<br>피크 56,300 hits/s, P99 ≤180ms | [GitHub](https://github.com/gm-15/Clmakase) |
| 🥬 **냉장GOAT**<br>식자재 발주 의사결정 백엔드 | 25.10 ~ ing | 캡스톤<br>백엔드 리드 | 500-thread 환경에서 락 4종 비교 및 재고 정합성 검증<br>KAMIS 6년 데이터 기반 발주 판단 기준 설계 | [GitHub](https://github.com/gm-15/naengjang-goat_backend) |
| 📰 **INSK**<br>AI 뉴스 센싱 및 부서 추천 플랫폼 | 25.07 ~ 26.06 | 팀장<br>백엔드, 인프라 | 추천 silent failure 원인 추적, Retry/Fallback/재처리 구현<br>Redis 캐시 적용 후 3,950ms → 21.5ms | [GitHub](https://github.com/gm-15/INSK) |
| 🅿️ **ParkingMate**<br>P2P 주차 공유 백엔드 | 25.12 ~ 26.03 | 단독 개발<br>백엔드 중심 | Transactional Outbox와 다층 락으로 예약 정합성 강화<br>Spatial Index 적용 후 EXPLAIN rows 9,880 → 378 | [GitHub](https://github.com/gm-15/ParkingMate) |

## Engineering Focus 🔍

### Reliability
- 외부 API와 비동기 처리 실패를 Retry, Fallback, 재처리 경로로 분리
- 정상 응답 뒤에 숨은 silent failure까지 결과값을 직접 측정해 추적
- 장애 발생 위치와 실제 병목 위치를 분리해 확인

### Data Integrity
- 동시성 충돌 환경을 직접 구성하고 락 전략별 정합성을 비교
- Transactional Outbox로 핵심 트랜잭션과 후속 작업의 실패를 분리
- 업무에서 사용하는 판단 기준을 데이터와 시스템 로직으로 구체화

### Scalability
- 150K VU 부하 테스트를 통해 애플리케이션, 노드, DB connection pool까지 병목 범위를 축소
- 캐시, 병렬 처리, Spatial Index 등 병목에 맞는 방법을 적용하고 전후 결과 측정
- 스케일아웃 시 애플리케이션뿐 아니라 DB와 외부 의존성의 한계까지 함께 검토

## Experiences 🏃

- **CJ OliveNetworks Cloud Wave 7기** | 400h, 캡스톤 팀장, 최종 2등
- **SK mySUNI 써니C 4기** | AI 뉴스 센싱 프로젝트
- **LangChain 기반 생성형 AI 서비스 개발 과정** | 80h
- **SK mySUNI AI Dream Camp** | AI, 데이터 분석 기초
- **상명대학교 실리콘밸리 단기 해외연수** | 글로벌 IT 기업 6곳 방문

## Awards & Certifications 🎖️

- **정보처리기사** | 2026.06
- **AWS Certified Solutions Architect – Associate** | 2026.03
- **컴퓨터활용능력 1급** | 2024.05
- **AWS와 함께하는 소중한 상명해커톤 최우수상** | 팀장, 2024.08
- **Departmental Top Honor Scholarship**

## Links 🔗

- 📓 [Portfolio](https://enshrined-streetcar-972.notion.site/Park-GunWoo-36a402afeda5809395eed9b5f899a946)
- ✍️ [Tech Blog](https://velog.io/@gm-15)
- 💼 [LinkedIn](https://www.linkedin.com/in/%EA%B1%B4%EC%9A%B0-%EB%B0%95-52a23434a/)
- 📧 **gunwoo363@gmail.com**
