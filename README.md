# Fi Chart Project

<div align="center">
  <img src="https://via.placeholder.com/200x200?text=Fi+Chart" alt="Fi Chart Logo" width="200" height="200">
  <h3>개인 금융 관리를 위한 통합 데이터 수집, 분석 및 시각화 시스템</h3>
</div>

## 프로젝트 개요

Fi Chart Project는 투자자들이 여러 금융 자산(주식, 채권, 암호화폐 등)을 효과적으로 관리하고 분석할 수 있는 통합 솔루션입니다. 다양한 거래소와 금융 기관의 데이터를 수집하고 분석하여 개인 자산 관리를 위한 인사이트를 제공합니다.

## 구성 프로젝트

Fi Chart Project는 다음과 같은 핵심 프로젝트로 구성됩니다:

- [**go_fi_chart**](https://github.com/kimjooyoon/go_fi_chart) - 전통 금융 자산 데이터 처리 백엔드
  - 주식, 채권, ETF 등의 데이터 수집 및 처리
  - 포트폴리오 분석 및 최적화 알고리즘
  - 금융 데이터 API 서비스

- [**cryptolytica**](https://github.com/kimjooyoon/cryptolytica) - 암호화폐 데이터 수집 및 분석
  - 다양한 암호화폐 거래소 데이터 통합
  - 실시간 시장 데이터 분석
  - 온체인 데이터 분석 및 DeFi 프로토콜 통합

- [**flutter_fi_chart**](https://github.com/kimjooyoon/flutter_fi_chart) - 금융 데이터 시각화 및 사용자 인터페이스
  - 크로스 플랫폼 모바일/웹 애플리케이션
  - 대화형 차트 및 포트폴리오 대시보드
  - 개인화된 금융 인사이트 및 알림

## 지원 거래소 및 금융 기관

### 전통 금융
- 한국 증권사 (삼성증권, 미래에셋증권 등)
- 해외 브로커 (Interactive Brokers, TD Ameritrade 등)
- 글로벌 데이터 제공업체 (Yahoo Finance, Alpha Vantage 등)

### 암호화폐
- 글로벌 거래소 (바이낸스, 비트겟, 코인베이스 등)
- 국내 거래소 (업비트, 빗썸 등)
- DeFi 프로토콜 (유니스왑, 에이브 등)

## 아키텍처

프로젝트 아키텍처에 대한 자세한 내용은 [architecture](./architecture) 디렉토리에서 확인할 수 있습니다.

```
┌───────────────────┐      ┌───────────────────┐
│                   │      │                   │
│    go_fi_chart    │◄────►│   cryptolytica    │
│  (전통 금융 자산)   │      │    (암호화폐)      │
│                   │      │                   │
└─────────┬─────────┘      └────────┬──────────┘
          │                          │
          │         ┌────────────────┘
          │         │
          ▼         ▼
┌───────────────────────────┐
│                           │
│      flutter_fi_chart     │
│   (통합 사용자 인터페이스)   │
│                           │
└───────────────────────────┘
```

## 로드맵

프로젝트의 현재 진행 상황과 향후 계획은 [roadmap](./roadmap) 디렉토리에서 확인할 수 있습니다.

## 기여하기

Fi Chart Project는 오픈소스 프로젝트로, 다양한 기여를 환영합니다. 기여 방법과 가이드라인은 [CONTRIBUTING.md](./CONTRIBUTING.md)를 참조해주세요.

## 라이센스

이 프로젝트는 Apache License 2.0 라이센스 하에 배포됩니다.