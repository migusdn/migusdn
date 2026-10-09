<h1 align="center">박현우 · Backend Developer</h1>

<p align="center">
  <strong>Realtime Systems · External API Integration · Data Automation</strong>
</p>

<p align="center">
  외부 API, 파일, 실시간 스트림에서 들어오는 복잡한 입력을<br />
  안정적인 백엔드 구조와 운영 가능한 흐름으로 연결합니다.
</p>

<p align="center">
  <strong>Contact</strong>
  ·
  <a href="mailto:contact@hyunwo.com">contact@hyunwo.com</a>
</p>

---

## What I build

- **Realtime systems** — WebSocket으로 유입되는 데이터를 내부 이벤트와 상태 모델로 변환하고 SSE·REST로 전달합니다.
- **External API integrations** — 인증, 토큰 캐시, rate limit, retry, 오류 변환을 경계 계층에서 관리합니다.
- **Data automation** — 반복적인 파일·브라우저·OCR 작업을 검증 가능한 데이터 파이프라인으로 바꿉니다.

## Featured work

### [KIS MCP Server](https://github.com/migusdn/KIS_MCP_Server) <sup>OPEN SOURCE</sup>

한국투자증권 REST API를 AI 도구가 안전하게 탐색하고 호출할 수 있도록 만든 MCP 서버입니다.

- 166개 API를 개별 도구로 나열하지 않고 `list → spec → call` 카탈로그 구조로 설계
- `stdio`, `SSE`, `Streamable HTTP` transport 지원
- 실전·모의 계좌 분기, token cache 무효화, 주문 API safety gate 구현
- Python 3.13 · FastMCP · httpx · unittest

### Realtime Order & Market Data Backend <sup>PRIVATE SOURCE</sup>

실시간 금융 데이터 수집부터 전략 평가, 주문 상태, 운영 화면과 장애 복구까지 연결한 개인 운영 시스템입니다.

- KIS REST/WebSocket → 내부 이벤트 → 브라우저 SSE 스트림 구성
- 신호·주문·체결·청산 상태를 PostgreSQL과 대시보드에 반영
- rate limit, retry, token, 주문 lifecycle을 독립적인 운영 경계로 관리
- Java 17 · Spring Boot · PostgreSQL · React · Python · OCI

> 소스 저장소는 비공개입니다. 계좌, 토큰, 실제 주문 데이터 등 민감정보를 제외한 구조와 구현 범위만 공개합니다.

### AI-assisted Workflow Automation <sup>PRIVATE WORK</sup>

반복적인 내부 업무를 데이터 기반 흐름으로 정리하고, 로컬 도구로 자동화한 경험이 있습니다.

- LLM structured output을 활용해 비정형 입력에서 특징을 추출하고 정규화
- 일반적인 입력은 규칙 기반 fast path로 처리하고, 모호한 경우에만 AI fallback 적용
- schema validation과 결과 versioning으로 AI 출력의 일관성과 재현성 보완

> AI 적용 방식 외에 프로젝트명, 업무 도메인, 실제 데이터, 세부 기능, 운영 구조와 소스는 공개하지 않습니다.

### [Wote](https://github.com/migusdn/Wote) <sup>TEAM PRODUCT</sup>

청소년의 소비 고민을 투표와 커뮤니티로 풀어낸 Apple Developer Academy 팀 프로젝트입니다.

- Spring Boot 기반 OAuth2 인증과 JPA·QueryDSL 데이터 계층 구현
- Quartz scheduler와 push notification server 구성
- 백엔드 개발자로 참여한 Apple Developer Academy 팀 프로젝트

## Core stack

| Area | Tools |
|---|---|
| Backend | Java, Spring Boot, Spring Security, Python, FastMCP, Node.js |
| Data | PostgreSQL, MariaDB, Oracle Database, SQLite, JPA, QueryDSL |
| Realtime & Integration | WebSocket, SSE, REST API, OAuth 2.0, JWT, OpenFeign |
| Infrastructure | OCI, Docker, Nginx, GitHub Actions, Gitea Actions |
| Automation | Selenium, OCR, Excel/Data Pipeline, OpenAI API |

## 주요 오픈소스

- **[KIS MCP Server](https://github.com/migusdn/KIS_MCP_Server)** — MCP 클라이언트를 위한 카탈로그 기반 한국투자증권 API 게이트웨이
- **[Process Memory Analyzer](https://github.com/migusdn/process-memory-analyzer)** — Swift 6과 Mach VM API로 구현한 권한 기반 macOS 프로세스 메모리 분석 도구
