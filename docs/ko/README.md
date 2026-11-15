![BrowserMirrorAgents](../../assets/banner.png)

# BrowserMirrorAgents

**OpenCode와 Codex를 브라우저 기반 AI 에이전트에 연결하세요.**

BrowserMirrorAgents는 AI 코딩 도구를 브라우저 기반 AI 서비스에 연결하는 자체 호스팅 통합 레이어입니다.

기존 브라우저 세션을 통해 Bitrix24, Qwen 및 DeepSeek과 함께 선호하는 AI 코딩 환경을 사용하세요. 각 제공업체마다 별도의 API 키를 구매할 필요가 없습니다.

[🌐 공식 웹사이트](https://agent.p5g.ru/)

---

## 🚀 지원되는 통합

### AI 코딩 도구

| 통합 | 상태 |
|---|---|
| OpenCode | 지원됨 |
| Codex | 지원됨 |

### 브라우저 기반 AI 제공업체

| 제공업체 | 지원 |
|---|---|
| Bitrix24 | 지원됨 |
| Qwen | 지원됨 |
| DeepSeek | 지원됨 |
| Google AI | 지원됨 |

---

## ✨ 왜 BrowserMirrorAgents인가?

- **별도 API 키 불필요** — 개별 API 액세스를 구매하는 대신 브라우저 세션 사용.
- **여러 AI 제공업체** — 다양한 브라우저 기반 AI 서비스에 연결.
- **OpenCode 통합** — OpenCode 워크플로우에서 브라우저 기반 AI 에이전트 사용.
- **Codex 통합** — Codex를 지원되는 브라우저 AI 서비스에 연결.
- **자체 호스팅** — 자체 서버에서 애플리케이션 실행.
- **Docker 배포** — Docker Compose를 사용한 간단한 설치.
- **일회성 결제** — 반복 구독 없음.

## 🔌 작동 방식

BrowserMirrorAgents는 AI 코딩 도구와 브라우저 기반 AI 서비스 간의 통합 레이어로 작동합니다.

1. 서버에 BrowserMirrorAgents를 배포합니다.
2. 브라우저 기반 AI 세션을 연결합니다.
3. OpenCode 또는 Codex를 구성합니다.
4. 지원되는 AI 제공업체로 작업을 시작합니다.

실제 액세스, 사용 제한 및 가용성은 해당 AI 제공업체와 브라우저 세션에 따라 다릅니다.

---

## 🐳 설치

Docker를 사용하여 BrowserMirrorAgents를 배포합니다.

`YOUR_LICENSE_KEY`를 구매 후 받은 개인 라이선스 키로 교체합니다.

`docker run -d --name browsermirroragents --restart unless-stopped -p 8000:8000 -e LICENSE_KEY=YOUR_LICENSE_KEY soft.p5g.ru/browsermirroragents:latest`

컨테이너가 실행되면 다음을 엽니다:

**[http://localhost:8000](http://localhost:8000)**

끝입니다! BrowserMirrorAgents 사용 준비가 완료되었습니다.

---

## 💳 가격

### $18.88 — 일회성 결제

- 일회성 라이선스 구매
- 월간 구독 없음
- 반복 결제 없음
- 자체 호스팅 배포

[라이선스 받기](https://agent.p5g.ru/)

## 🌍 다국어 지원

BrowserMirrorAgents는 21개 언어를 지원합니다:
- [English](../../README.md)
- [Español](../es/README.md)
- [Deutsch](../de/README.md)
- [Français](../fr/README.md)
- [Italiano](../it/README.md)
- [简体中文](../zh_CN/README.md)
- [繁體中文](../zh_TW/README.md)
- [Português (Brasil)](../pt_BR/README.md)
- [日本語](../ja/README.md)
- [한국어](README.md)
- [العربية](../ar/README.md)
- [हिन्दी](../hi/README.md)
- [Türkçe](../tr/README.md)
- [Bahasa Indonesia](../id/README.md)
- [Polski](../pl/README.md)
- [Tiếng Việt](../vi/README.md)
- [ไทย](../th/README.md)
- [Nederlands](../nl/README.md)
- [Svenska](../sv/README.md)
- [Norsk](../no/README.md)
- [Русский](../ru/README.md)

## 🤖 AI 기반 인터페이스 모니터링

**인터페이스 변경을 걱정하지 마세요. 우리가 모니터링합니다.**

AI 기반 모니터링은 당사 측에서 실행되며 지원되는 AI 서비스와 브라우저 인터페이스의 변경 사항을 추적합니다.

인터페이스 요소나 선택기가 변경되면 시스템이 업데이트를 감지하고 거의 즉시 업데이트된 선택기와 호환성 조정을 게시합니다.

- **연속 모니터링** — 지원되는 인터페이스는 정기적으로 모니터링됩니다.
- **AI 기반 감지** — 변경 사항이 자동으로 식별됩니다.
- **빠른 업데이트** — 업데이트된 선택기와 인터페이스 조정이 신속하게 게시됩니다.
- **유지보수 감소** — 인터페이스 변경을 수동으로 추적하거나 선택자를 지속적으로 직접 업데이트할 필요가 없습니다.

**우리는 인터페이스를 모니터링합니다. 당신은 업무에 집중하세요.**

## 💬 커뮤니티 및 지원

이 저장소는 BrowserMirrorAgents와 관련된 문제 보고, 문제 논의 및 솔루션 공유를 위한 중앙 장소입니다.

다음에 환영합니다:

- **버그 보고** — 예상치 못한 동작이나 오류가 발생하면 issue를 생성하세요.
- **기능 요청** — 개선 사항과 새로운 통합을 제안하세요.
- **솔루션 논의** — 다른 사용자와 아이디어, 해결 방법 및 솔루션을 공유하세요.
- **질문하기** — 구성, 호환성 및 사용법에 대해 논의하세요.
- **업데이트 추적** — 수정, 개선 및 호환성 변경에 대한 토론을 따르세요.

새로운 issue를 생성하기 전에 중복을 피하기 위해 기존 issue를 확인하세요.

**문제를 발견하셨나요? issue를 열고 함께 해결합시다!**

---

## ❓ FAQ

### 별도 API 키가 필요합니까?

아니요. BrowserMirrorAgents는 기존 브라우저 세션을 통해 작동하도록 설계되었으므로 지원되는 각 제공업체마다 별도 API 키를 구매할 필요가 없습니다.

### 어떤 AI 코딩 도구가 지원됩니까?

OpenCode와 Codex.

### 어떤 AI 제공업체가 지원됩니까?

Bitrix24, Qwen, DeepSeek, Google AI.

### 자체 서버에서 호스팅할 수 있습니까?

예. BrowserMirrorAgents는 Docker 이미지로 배포되며 Docker Compose를 사용하여 배포할 수 있습니다.

### 월간 요금이 있습니까?

아니요. BrowserMirrorAgents는 일회성 라이선스 구매로 이용 가능합니다.

### AI 서비스가 무제한입니까?

사용량은 각 AI 제공업체의 가용성, 정책 및 제한 사항과 브라우저 세션에 따라 다릅니다.

또한 각 제공업체의 서비스 약관에 따라 여러 브라우저 계정을 연결하고 세션 간에 전환할 수 있습니다.

---

## 🔗 링크

- **웹사이트:** https://agent.p5g.ru/
- **라이선스:** 공식 웹사이트에서 이용 가능.
- **지원:** 연락처 정보는 공식 웹사이트에서 이용 가능.

---

## ⚖️ 면책 조항

BrowserMirrorAgents는 독립적인 소프트웨어 제품이며 OpenAI, OpenCode, Bitrix24, Alibaba Cloud, DeepSeek 또는 해당 소유자와 제휴, 승인 또는 공식적으로 연관되어 있지 않습니다.

모든 제3자 제품 이름 및 상표는 해당 소유자의 재산입니다.

제3자 AI 서비스의 사용은 해당 서비스 약관, 정책 및 사용 제한의 적용을 받습니다.

---

**BrowserMirrorAgents**

*하나의 통합 레이어. 여러 브라우저 기반 AI 에이전트.*
