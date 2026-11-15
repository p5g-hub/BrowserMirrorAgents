![BrowserMirrorAgents](assets/banner.png)

# BrowserMirrorAgents

**Connect OpenCode and Codex to browser-based AI agents.**

BrowserMirrorAgents is a self-hosted integration layer that connects AI coding tools to browser-based AI services.

Use your favorite AI coding environment with Bitrix24, Qwen and DeepSeek through existing browser sessions — without purchasing separate API keys for each provider.

[🌐 Official Website](https://agent.p5g.ru/)

---

## 🚀 Supported Integrations

### AI Coding Tools

| Integration | Status |
|---|---|
| OpenCode | Supported |
| Codex | Supported |

### Browser-based AI Providers

| Provider | Support |
|---|---|
| Bitrix24 | Supported |
| Qwen | Supported |
| DeepSeek | Supported |
| Google AI | Supported |

---

## ✨ Why BrowserMirrorAgents?

- **No separate API keys** — use browser sessions instead of purchasing individual API access.
- **Multiple AI providers** — connect to different browser-based AI services.
- **OpenCode integration** — use browser-based AI agents in your OpenCode workflow.
- **Codex integration** — connect Codex to supported browser AI services.
- **Self-hosted** — run the application on your own server.
- **Docker deployment** — simple installation using Docker Compose.
- **One-time payment** — no recurring subscription.

## 🔌 How It Works

BrowserMirrorAgents acts as an integration layer between AI coding tools and browser-based AI services.

1. Deploy BrowserMirrorAgents on your server.
2. Connect your browser-based AI sessions.
3. Configure OpenCode or Codex.
4. Start working with supported AI providers.

Your actual access, usage limits and availability depend on the corresponding AI provider and your browser session.

---

## 🐳 Installation

Deploy BrowserMirrorAgents using Docker.

Replace `YOUR_LICENSE_KEY` with your personal license key received after purchase.

`docker run -d --name browsermirroragents --restart unless-stopped -p 8000:8000 -e LICENSE_KEY=YOUR_LICENSE_KEY soft.p5g.ru/browsermirroragents:latest`

Once the container is running, open:

**[http://localhost:8000](http://localhost:8000)**

That's it! BrowserMirrorAgents is ready to use.

---

## 💳 Pricing

### $18.88 — One-time payment

- One-time license purchase
- No monthly subscriptions
- No recurring payments
- Self-hosted deployment

[Get Your License](https://agent.p5g.ru/)

## 🌍 Multilingual Support

BrowserMirrorAgents supports 21 languages:
- [English](README.md)
- [Español](docs/es/README.md)
- [Deutsch](docs/de/README.md)
- [Français](docs/fr/README.md)
- [Italiano](docs/it/README.md)
- [简体中文](docs/zh_CN/README.md)
- [繁體中文](docs/zh_TW/README.md)
- [Português (Brasil)](docs/pt_BR/README.md)
- [日本語](docs/ja/README.md)
- [한국어](docs/ko/README.md)
- [العربية](docs/ar/README.md)
- [हिन्दी](docs/hi/README.md)
- [Türkçe](docs/tr/README.md)
- [Bahasa Indonesia](docs/id/README.md)
- [Polski](docs/pl/README.md)
- [Tiếng Việt](docs/vi/README.md)
- [ไทย](docs/th/README.md)
- [Nederlands](docs/nl/README.md)
- [Svenska](docs/sv/README.md)
- [Norsk](docs/no/README.md)
- [Русский](docs/ru/README.md)

## 🤖 AI-Powered Interface Monitoring

**Don't worry about interface changes. We monitor them for you.**

AI-powered monitoring runs on our side, tracking changes in supported AI services and their browser interfaces.

When interface elements or selectors change, our system detects the updates and publishes refreshed selectors and compatibility adjustments almost immediately.

- **Continuous monitoring** — supported interfaces are regularly monitored.
- **AI-powered detection** — changes are identified automatically.
- **Fast updates** — refreshed selectors and interface adjustments are published promptly.
- **Less maintenance** — no need to manually track interface changes or constantly update selectors yourself.

**We monitor the interfaces. You focus on your work.**

## 💬 Community & Support

This repository is the central place for reporting issues, discussing problems, and sharing solutions related to BrowserMirrorAgents.

You are welcome to:

- **Report bugs** — create an issue if you encounter unexpected behavior or errors.
- **Request features** — suggest improvements and new integrations.
- **Discuss solutions** — share ideas, workarounds, and solutions with other users.
- **Ask questions** — discuss configuration, compatibility, and usage.
- **Track updates** — follow discussions about fixes, improvements, and compatibility changes.

Before creating a new issue, please check existing issues to avoid duplicates.

**Found a problem? Open an issue and let's solve it together!**

---

## ❓ FAQ

### Do I need separate API keys?

No. BrowserMirrorAgents is designed to work through existing browser sessions, so you don't need to purchase separate API keys for every supported provider.

### Which AI coding tools are supported?

OpenCode and Codex.

### Which AI providers are supported?

Bitrix24, Qwen, DeepSeek, Google AI.

### Can I host it on my own server?

Yes. BrowserMirrorAgents is distributed as a Docker image and can be deployed using Docker Compose.

### Are there monthly fees?

No. BrowserMirrorAgents is available with a one-time license purchase.

### Are AI services unlimited?

Usage depends on the availability, policies and limits of each AI provider and your browser sessions.

You can also connect multiple browser accounts and switch between sessions, subject to the respective providers' terms of service.

---

## 🔗 Links

- **Website:** https://agent.p5g.ru/
- **License:** Available on the official website.
- **Support:** Contact information is available on the official website.

---

## ⚖️ Disclaimer

BrowserMirrorAgents is an independent software product and is not affiliated with, endorsed by, or officially associated with OpenAI, OpenCode, Bitrix24, Alibaba Cloud, DeepSeek or their respective owners.

All third-party product names and trademarks belong to their respective owners.

Use of third-party AI services is subject to their respective terms of service, policies and usage limitations.

---

**BrowserMirrorAgents**

*One integration layer. Multiple browser-based AI agents.*
