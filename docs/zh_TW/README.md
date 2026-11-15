![BrowserMirrorAgents](../../assets/banner.png)

# BrowserMirrorAgents

**將 OpenCode 和 Codex 連接到基於瀏覽器的 AI 代理。**

BrowserMirrorAgents 是一個自託管的整合層，將 AI 編碼工具連接到基於瀏覽器的 AI 服務。

透過現有的瀏覽器工作階段，將您喜愛的 AI 編碼環境與 Bitrix24、Qwen 和 DeepSeek 一起使用——無需為每個供應商購買單獨的 API 金鑰。

[🌐 官方網站](https://agent.p5g.ru/)

---

## 🚀 支援的整合

### AI 編碼工具

| 整合 | 狀態 |
|---|---|
| OpenCode | 支援 |
| Codex | 支援 |

### 基於瀏覽器的 AI 供應商

| 供應商 | 支援 |
|---|---|
| Bitrix24 | 支援 |
| Qwen | 支援 |
| DeepSeek | 支援 |
| Google AI | 支援 |

---

## ✨ 為什麼選擇 BrowserMirrorAgents？

- **無需單獨的 API 金鑰** — 使用瀏覽器工作階段，而不是購買單獨的 API 存取權限。
- **多個 AI 供應商** — 連接到不同的基於瀏覽器的 AI 服務。
- **OpenCode 整合** — 在您的 OpenCode 工作流程中使用基於瀏覽器的 AI 代理。
- **Codex 整合** — 將 Codex 連接到支援的瀏覽器 AI 服務。
- **自託管** — 在您自己的伺服器上執行應用程式。
- **Docker 部署** — 使用 Docker Compose 簡單安裝。
- **一次性付款** — 無經常性訂閱。

## 🔌 工作原理

BrowserMirrorAgents 充當 AI 編碼工具和基於瀏覽器的 AI 服務之間的整合層。

1. 在您的伺服器上部署 BrowserMirrorAgents。
2. 連接您的基於瀏覽器的 AI 工作階段。
3. 設定 OpenCode 或 Codex。
4. 開始與支援的 AI 供應商合作。

您的實際存取、使用限制和可用性取決於對應的 AI 供應商和您的瀏覽器工作階段。

---

## 🐳 安裝

使用 Docker 部署 BrowserMirrorAgents。

將 `YOUR_LICENSE_KEY` 替換為購買後收到的個人授權金鑰。

`docker run -d --name browsermirroragents --restart unless-stopped -p 8000:8000 -e LICENSE_KEY=YOUR_LICENSE_KEY soft.p5g.ru/browsermirroragents:latest`

容器執行後，開啟：

**[http://localhost:8000](http://localhost:8000)**

就這樣！BrowserMirrorAgents 已準備好使用。

---

## 💳 價格

### $18.88 — 一次性付款

- 一次性授權購買
- 無每月訂閱
- 無經常性付款
- 自託管部署

[取得您的授權](https://agent.p5g.ru/)

## 🌍 多語言支援

BrowserMirrorAgents 支援 21 種語言：
- [English](../../README.md)
- [Español](../es/README.md)
- [Deutsch](../de/README.md)
- [Français](../fr/README.md)
- [Italiano](../it/README.md)
- [简体中文](../zh_CN/README.md)
- [繁體中文](README.md)
- [Português (Brasil)](../pt_BR/README.md)
- [日本語](../ja/README.md)
- [한국어](../ko/README.md)
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

## 🤖 AI 驅動的介面監控

**不用擔心介面變更。我們為您監控。**

AI 驅動的監控在我們這邊運行，追蹤支援的 AI 服務及其瀏覽器介面的變更。

當介面元素或選擇器變更時，我們的系統會偵測更新並幾乎立即發布更新的選擇器和相容性調整。

- **持續監控** — 定期監控支援的介面。
- **AI 驅動的偵測** — 自動識別變更。
- **快速更新** — 快速發布更新的選擇器和介面調整。
- **較少維護** — 無需手動追蹤介面變更或不斷自行更新選擇器。

**我們監控介面。您專注於工作。**

## 💬 社群與支援

此儲存庫是報告問題、討論問題和分享與 BrowserMirrorAgents 相關解決方案的中心位置。

歡迎您：

- **回報錯誤** — 如果遇到意外行為或錯誤，請建立 issue。
- **請求功能** — 建議改進和新的整合。
- **討論解決方案** — 與其他使用者分享想法、解決方法和解決方案。
- **提問** — 討論設定、相容性和使用方式。
- **追蹤更新** — 關注有關修復、改進和相容性變更的討論。

在建立新 issue 之前，請檢查現有 issue 以避免重複。

**發現問題？開啟 issue，讓我們一起解決！**

---

## ❓ 常見問題

### 我需要單獨的 API 金鑰嗎？

不需要。BrowserMirrorAgents 設計為透過現有的瀏覽器工作階段運作，因此您無需為每個支援的供應商購買單獨的 API 金鑰。

### 支援哪些 AI 編碼工具？

OpenCode 和 Codex。

### 支援哪些 AI 供應商？

Bitrix24、Qwen、DeepSeek、Google AI。

### 我可以在自己的伺服器上託管嗎？

可以。BrowserMirrorAgents 以 Docker 映像形式發布，可以使用 Docker Compose 進行部署。

### 有月費嗎？

沒有。BrowserMirrorAgents 可透過一次性授權購買取得。

### AI 服務是無限的嗎？

使用情況取決於每個 AI 供應商的可用性、政策和限制以及您的瀏覽器工作階段。

您也可以連接多個瀏覽器帳戶並在工作階段之間切換，但需遵守各供應商的服務條款。

---

## 🔗 連結

- **網站：** https://agent.p5g.ru/
- **授權：** 可在官方網站取得。
- **支援：** 聯絡資訊可在官方網站取得。

---

## ⚖️ 免責聲明

BrowserMirrorAgents 是一個獨立的軟體產品，與 OpenAI、OpenCode、Bitrix24、Alibaba Cloud、DeepSeek 或其各自的所有者無關聯、背書或正式關聯。

所有第三方產品名稱和商標屬於其各自的所有者。

使用第三方 AI 服務須遵守其各自的服務條款、政策和使用限制。

---

**BrowserMirrorAgents**

*一個整合層。多個基於瀏覽器的 AI 代理。*
