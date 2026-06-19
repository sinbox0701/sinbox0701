### 박기웅 (Kiwoong Park) — Backend Engineer

분산 시스템을 단독 설계하고, 팀 품질을 **구조**로 만드는 백엔드 엔지니어.
**NestJS · TypeScript** 주력. 스택보다 문제의 본질(동시성 · 아키텍처 · 팀 품질)로 일합니다.

---

#### 🛠 무엇을 하나

- **분산 시스템 동시성 제어** — 동시 접속이 몰려도 환경이 중복 생성·멈춤 없이 돌도록 설계 (실습 환경 프로비저닝, 중복 발급 0건 · 장애 시 graceful degradation)
- **zero-to-one 아키텍처** — 성격이 다른 다수 도메인을 한 모놀리스에 수용, 개발 기간 30%+ 단축
- **팀 품질의 구조화** — 컨벤션 · 리뷰로 팀원 자발적 리팩토링 유도 (-56%)
- **AI 코딩 하네스** — "사람이든 AI든 누가 작업해도 같은 품질"이 나오도록 생성→검증→피드백 루프를 코드 수준에서 강제

---

#### 📦 대표 프로젝트

**[backend-template](https://github.com/sinbox0701/template)** — 도메인 비종속 NestJS 백엔드 스타터
> 4-레이어 아키텍처를 **CI가 기계적으로 강제**(dependency-cruiser) · 3-tier RBAC/ABAC 접근제어 · 마이그레이션 드리프트 가드 · `.claude/` **AI 협업 하네스**(SDD 파이프라인)
> 📖 읽기 가이드: [Backend Template Guide](https://dark-agenda-1b4.notion.site/Backend-Template-Guide-384222cff3e1801f9be5d39b7eb51ccb)

**[hhplus-shop](https://github.com/sinbox0701/hhplus-shop)** — Kotlin + Spring Boot 이커머스 백엔드
> 자원별 락 전략 분리(비관/낙관/Redisson 분산락) · Kafka 선착순 쿠폰 · Redis 실시간 랭킹 · k6 부하테스트

---

#### ⚙️ 기술 스택

- **Backend:** NestJS · TypeScript · Node.js · Kotlin/Spring Boot
- **Data:** PostgreSQL · MikroORM · Redis · MySQL · Kysely
- **Infra:** AWS(ECS) · Docker · GitHub Actions
- **Tooling:** Claude Code · AI 코드 통제 하네스 · k6 · OpenTelemetry

---

#### 📫 연락

📧 psh090953@gmail.com
