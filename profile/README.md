<p align="center">
  <a href="https://monithub.org">
    <img src="https://monithub.org/assets/monithub-icon.svg" width="96" alt="Monithub logo" />
  </a>
</p>

<h1 align="center">Monithub</h1>

<p align="center">
  LLM, 애플리케이션, 인프라 운영을 위한 AI observability platform
</p>

<p align="center">
  <a href="https://monithub.org">Website</a>
  ·
  <a href="https://monithub.org/pricing.html">Pricing</a>
  ·
  <a href="mailto:supprtmonithub@gmail.com">Contact</a>
</p>

## 문제를 찾는 시간은 줄이고, 운영 판단은 빠르게

Monithub(모닛허브)는 LLM, 애플리케이션, 인프라의 상태를 통합 모니터링하고 이상 징후를 빠르게 탐지하며, trace 기반으로 근본 원인을 추적하는 AI 운영 관측 플랫폼입니다.

운영 데이터는 여러 시스템에 흩어져 있습니다. 장애나 성능 저하가 발생하면 팀은 대시보드, metric, log, trace, AI 요청 흐름을 오가며 원인을 찾아야 합니다. Monithub는 이런 신호를 하나의 판단 흐름으로 연결해 운영자가 더 빠르게 상황을 이해하고 대응하도록 돕습니다.

## 제품

### Monithub Platform

Monithub Platform은 metric, trace, log 관측을 자연스럽게 이어 문제를 찾는 시간을 줄이는 통합 운영 화면입니다.

- 전체 시스템 상태를 한눈에 파악
- 느린 요청의 trace 흐름 추적
- 장애 로그를 빠르게 좁혀 확인
- 주요 metric 변화와 이상 징후 확인
- 팀 기준에 맞춘 패널 편집과 시각화 구성

### Monithub Gateway / SDK

Monithub Gateway / SDK는 AI 모델 호출과 내부 서비스 요청을 관측 가능한 운영 단위로 바꾸는 observability-first AI proxy gateway입니다.

- AI proxy 요청 수, 오류율, 지연 시간, 토큰 사용량 모니터링
- OpenTelemetry 기반 trace, log, metric 수집
- `traceparent`, `X-Request-Id` 전파
- provider별 usage, latency, provider request id, finish reason 정규화
- public endpoint와 private/local endpoint를 같은 서비스 레지스트리로 관리

Monithub Gateway는 일반적인 인증/인가 중심 API Gateway가 아니라, AI와 애플리케이션 요청 흐름을 관측 가능한 데이터 플레인으로 만드는 데 초점을 둡니다.

### Monithub Sentinel

Monithub Sentinel은 운영 데이터의 변화 패턴, 임계값 이탈, 비정상 흐름을 먼저 포착해 중요한 이상 징후와 대응 우선순위를 빠르게 판단하도록 돕습니다.

- 이상 탐지
- 대시보드 생성
- 데이터 분석
- Monithub AI Model 연동
- 로컬 LLM 지원

## 아키텍처

Monithub는 Gateway, Platform, Sentinel이 각자의 역할을 맡고 하나의 운영 흐름으로 연결되도록 설계합니다.

1. **Monithub Gateway / SDK**: AI 서비스와 애플리케이션 요청 흐름을 수집하고 trace 가능한 형태로 정리합니다.
2. **Monithub Platform**: 운영 상태, metric, log, trace를 한 화면에서 읽고 공유하게 만듭니다.
3. **Monithub Sentinel**: 놓치기 쉬운 이상 신호를 먼저 보여주고 원인 분석을 돕습니다.
4. **Action**: 팀이 더 빠르게 대응하고 더 안정적으로 서비스를 운영하도록 연결합니다.

## 운영 원칙

- **Trace-first UX**: 데이터 나열보다 문제를 읽는 흐름을 우선해 원인 파악 속도를 높입니다.
- **Detection as a layer**: 운영 화면 위에 이상 탐지와 분석 경험을 자연스럽게 더합니다.
- **Gateway observability**: 복잡한 AI 요청 구간도 trace와 metadata 중심으로 안정적으로 운영하게 만듭니다.
- **Modern but practical**: 기술 선택은 화려함보다 실제 운영 효율과 확장성을 기준으로 결정합니다.

## 도입 옵션

Monithub는 팀의 운영 환경과 보안 요구사항에 맞춰 다양한 도입 방식을 제공합니다.

| Plan | Description |
| --- | --- |
| Free Trial | 2주간 SaaS 환경에서 Monithub의 핵심 모니터링 흐름을 체험합니다. |
| Self-hosted | 고객사 VPC 또는 온프레미스 환경 안에서 직접 운영합니다. |
| Hybrid-SaaS | 빠른 온보딩과 SaaS 기반 운영 효율을 가져가면서 필요한 데이터 경계를 유연하게 구성합니다. |

## 문의

제품 소개, 데모, PoC, 기술 상담, 투자 및 파트너십 문의를 환영합니다.

- Website: [monithub.org](https://monithub.org)
- General inquiry: [supprtmonithub@gmail.com](mailto:supprtmonithub@gmail.com)
- Partnership / investment: [ryankimjhga@gmail.com](mailto:ryankimjhga@gmail.com)

---

## Less Time Finding Problems, Faster Operational Decisions

Monithub is an AI observability platform that unifies monitoring across LLMs, applications, and infrastructure, detects anomalies early, and helps teams trace root causes through request and system traces.

Operational data is often scattered across multiple systems. When incidents or performance issues happen, teams have to move between dashboards, metrics, logs, traces, and AI request flows to understand what went wrong. Monithub connects those signals into one decision flow so operators can understand issues faster and respond with more confidence.

## Products

### Monithub Platform

Monithub Platform is an integrated operations workspace that connects metric, trace, and log observability to reduce the time spent finding problems.

- Understand overall system health at a glance
- Trace slow requests across services
- Filter and inspect incident logs quickly
- Detect important metric changes and anomaly signals
- Customize panels and visualizations for each team's workflow

### Monithub Gateway / SDK

Monithub Gateway / SDK is an observability-first AI proxy gateway that turns AI model calls and internal service requests into traceable, measurable operational units.

- Monitor AI proxy request volume, error rate, latency, and token usage
- Collect traces, logs, and metrics through OpenTelemetry
- Propagate `traceparent` and `X-Request-Id`
- Normalize provider usage, latency, request ids, and finish reasons
- Manage public and private/local endpoints through one service registry

Monithub Gateway is not a traditional auth-centered API gateway. It is designed as an observable data plane for AI and application request flows.

### Monithub Sentinel

Monithub Sentinel is an intelligent anomaly detection layer that surfaces metric changes, threshold violations, and abnormal flows before they become harder to diagnose.

- Anomaly detection
- Dashboard generation
- Data analysis
- Monithub AI Model integration
- Local LLM support

## Architecture

Monithub is designed as a connected operations flow where Gateway, Platform, and Sentinel each play a focused role.

1. **Monithub Gateway / SDK**: Collects AI and application request flows and turns them into traceable telemetry.
2. **Monithub Platform**: Brings operational state, metrics, logs, and traces into one shared operating view.
3. **Monithub Sentinel**: Detects subtle anomaly signals and supports root cause analysis.
4. **Action**: Helps teams respond faster and operate services more reliably.

## Principles

- **Trace-first UX**: Prioritize the flow of understanding a problem over simply listing data.
- **Detection as a layer**: Add anomaly detection and analysis naturally on top of the operations experience.
- **Gateway observability**: Make complex AI request paths easier to operate through traces and metadata.
- **Modern but practical**: Choose technology based on operational efficiency, scalability, and real-world usefulness.

## Deployment Options

Monithub supports multiple deployment models depending on each team's infrastructure, security requirements, and operating model.

| Plan | Description |
| --- | --- |
| Free Trial | Try Monithub's core monitoring flow in a SaaS environment for two weeks. |
| Self-hosted | Run Monithub inside your own VPC or on-premises environment. |
| Hybrid-SaaS | Combine fast onboarding and SaaS-based operational efficiency with flexible data boundaries. |

## Contact

For product introductions, demos, PoCs, technical discussions, investment, or partnership inquiries, feel free to contact us.

- Website: [monithub.org](https://monithub.org)
- General inquiry: [supprtmonithub@gmail.com](mailto:supprtmonithub@gmail.com)
- Partnership / investment: [ryankimjhga@gmail.com](mailto:ryankimjhga@gmail.com)
