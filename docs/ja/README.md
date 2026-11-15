![BrowserMirrorAgents](../../assets/banner.png)

# BrowserMirrorAgents

**OpenCodeとCodexをブラウザベースのAIエージェントに接続します。**

BrowserMirrorAgentsは、AIコーディングツールをブラウザベースのAIサービスに接続するセルフホスト型統合レイヤーです。

既存のブラウザセッションを通じて、Bitrix24、Qwen、DeepSeekでお気に入りのAIコーディング環境を使用できます。各プロバイダーごとに個別のAPIキーを購入する必要はありません。

[🌐 公式ウェブサイト](https://agent.p5g.ru/)

---

## 🚀 サポートされている統合

### AIコーディングツール

| 統合 | ステータス |
|---|---|
| OpenCode | サポート済み |
| Codex | サポート済み |

### ブラウザベースのAIプロバイダー

| プロバイダー | サポート |
|---|---|
| Bitrix24 | サポート済み |
| Qwen | サポート済み |
| DeepSeek | サポート済み |
| Google AI | サポート済み |

---

## ✨ なぜBrowserMirrorAgents？

- **個別のAPIキー不要** — 個別のAPIアクセスを購入する代わりにブラウザセッションを使用。
- **複数のAIプロバイダー** — さまざまなブラウザベースのAIサービスに接続。
- **OpenCode統合** — OpenCodeワークフローでブラウザベースのAIエージェントを使用。
- **Codex統合** — CodexをサポートされているブラウザAIサービスに接続。
- **セルフホスト型** — アプリケーションを独自のサーバーで実行。
- **Dockerデプロイ** — Docker Composeを使用した簡単なインストール。
- **一回払い** — 定期的なサブスクリプションなし。

## 🔌 仕組み

BrowserMirrorAgentsは、AIコーディングツールとブラウザベースのAIサービスの間の統合レイヤーとして機能します。

1. サーバーにBrowserMirrorAgentsをデプロイします。
2. ブラウザベースのAIセッションを接続します。
3. OpenCodeまたはCodexを設定します。
4. サポートされているAIプロバイダーでの作業を開始します。

実際のアクセス、使用制限、可用性は、対応するAIプロバイダーとブラウザセッションによって異なります。

---

## 🐳 インストール

Dockerを使用してBrowserMirrorAgentsをデプロイします。

`YOUR_LICENSE_KEY`を購入後に受け取った個人ライセンスキーに置き換えます。

`docker run -d --name browsermirroragents --restart unless-stopped -p 8000:8000 -e LICENSE_KEY=YOUR_LICENSE_KEY soft.p5g.ru/browsermirroragents:latest`

コンテナが実行されたら、開きます：

**[http://localhost:8000](http://localhost:8000)**

これだけです！BrowserMirrorAgentsの使用準備ができました。

---

## 💳 価格

### $18.88 — 一回払い

- 一回限りのライセンス購入
- 月額サブスクリプションなし
- 定期的な支払いなし
- セルフホスト型デプロイ

[ライセンスを取得](https://agent.p5g.ru/)

## 🌍 多言語サポート

BrowserMirrorAgentsは21言語をサポートしています：
- [English](../../README.md)
- [Español](../es/README.md)
- [Deutsch](../de/README.md)
- [Français](../fr/README.md)
- [Italiano](../it/README.md)
- [简体中文](../zh_CN/README.md)
- [繁體中文](../zh_TW/README.md)
- [Português (Brasil)](../pt_BR/README.md)
- [日本語](README.md)
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

## 🤖 AI搭載インターフェース監視

**インターフェースの変更を心配しないでください。私たちが監視します。**

AI搭載の監視は当社側で実行され、サポートされているAIサービスとそのブラウザインターフェースの変更を追跡します。

インターフェース要素やセレクターが変更されると、システムが更新を検出し、更新されたセレクターと互換性調整をほぼ即座に公開します。

- **継続的な監視** — サポートされているインターフェースは定期的に監視されます。
- **AI搭載検出** — 変更は自動的に識別されます。
- **高速更新** — 更新されたセレクターとインターフェース調整は迅速に公開されます。
- **メンテナンス削減** — インターフェースの変更を手動で追跡したり、セレクターを常に自分で更新したりする必要はありません。

**私たちはインターフェースを監視します。あなたは仕事に集中してください。**

## 💬 コミュニティ＆サポート

このリポジトリは、BrowserMirrorAgentsに関連する問題の報告、問題の議論、ソリューションの共有のための中央場所です。

欢迎您：

- **バグを報告** — 予期しない動作やエラーが発生した場合はissueを作成してください。
- **機能をリクエスト** — 改善点や新しい統合を提案してください。
- **ソリューションを議論** — 他のユーザーとアイデア、回避策、ソリューションを共有してください。
- **質問する** — 設定、互換性、使用方法について議論してください。
- **更新を追跡** — 修正、改善、互換性の変更に関する議論に従ってください。

新しいissueを作成する前に、重複を避けるために既存のissueを確認してください。

**問題を見つけましたか？ issueを開いて、一緒に解決しましょう！**

---

## ❓ よくある質問

### 個別のAPIキーが必要ですか？

いいえ。BrowserMirrorAgentsは既存のブラウザセッションを通じて動作するように設計されているため、サポートされているプロバイダーごとに個別のAPIキーを購入する必要はありません。

### どのAIコーディングツールがサポートされていますか？

OpenCodeとCodex。

### どのAIプロバイダーがサポートされていますか？

Bitrix24、Qwen、DeepSeek、Google AI。

### 独自のサーバーでホストできますか？

はい。BrowserMirrorAgentsはDockerイメージとして配布され、Docker Composeを使用してデプロイできます。

### 月額料金がありますか？

いいえ。BrowserMirrorAgentsは一回限りのライセンス購入で利用できます。

### AIサービスは無制限ですか？

使用量は、各AIプロバイダーの可用性、ポリシー、制限、およびブラウザセッションによって異なります。

また、各プロバイダーの利用規約に従って、複数のブラウザアカウントを接続し、セッションを切り替えることができます。

---

## 🔗 リンク

- **ウェブサイト:** https://agent.p5g.ru/
- **ライセンス:** 公式ウェブサイトで利用可能。
- **サポート:** 連絡先情報は公式ウェブサイトで利用可能。

---

## ⚖️ 免責事項

BrowserMirrorAgentsは独立したソフトウェア製品であり、OpenAI、OpenCode、Bitrix24、Alibaba Cloud、DeepSeek、またはそれぞれの所有者と提携、承認、または公式に関連していません。

すべてのサードパーティ製品名および商標は、それぞれの所有者に帰属します。

サードパーティのAIサービスの使用は、それぞれの利用規約、ポリシー、使用制限の対象となります。

---

**BrowserMirrorAgents**

*1つの統合レイヤー。複数のブラウザベースのAIエージェント。*
