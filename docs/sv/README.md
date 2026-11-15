![BrowserMirrorAgents](../../assets/banner.png)

# BrowserMirrorAgents

**Anslut OpenCode och Codex till webbläsarbaserade AI-agenter.**

BrowserMirrorAgents är ett självhostat integrationslager som ansluter AI-kodningsverktyg till webbläsarbaserade AI-tjänster.

Använd din favorit-AI-kodningsmiljö med Bitrix24, Qwen och DeepSeek genom befintliga webbläsarsessioner — utan att köpa separata API-nycklar för varje leverantör.

[🌐 Officiell Webbplats](https://agent.p5g.ru/)

---

## 🚀 Stödda Integrationer

### AI-kodningsverktyg

| Integration | Status |
|---|---|
| OpenCode | Stöds |
| Codex | Stöds |

### Webbläsarbaserade AI-leverantörer

| Leverantör | Support |
|---|---|
| Bitrix24 | Stöds |
| Qwen | Stöds |
| DeepSeek | Stöds |
| Google AI | Stöds |

---

## ✨ Varför BrowserMirrorAgents?

- **Inga separata API-nycklar** — använd webbläsarsessioner istället för att köpa individuell API-åtkomst.
- **Flera AI-leverantörer** — anslut till olika webbläsarbaserade AI-tjänster.
- **OpenCode-integration** — använd webbläsarbaserade AI-agenter i din OpenCode-arbetsflöde.
- **Codex-integration** — anslut Codex till stödda webbläsar-AI-tjänster.
- **Självhostat** — kör applikationen på din egen server.
- **Docker-distribution** — enkel installation med Docker Compose.
- **Engångsbetalning** — ingen återkommande prenumeration.

## 🔌 Hur Det Fungerar

BrowserMirrorAgents fungerar som ett integrationslager mellan AI-kodningsverktyg och webbläsarbaserade AI-tjänster.

1. Distribuera BrowserMirrorAgents på din server.
2. Anslut dina webbläsarbaserade AI-sessioner.
3. Konfigurera OpenCode eller Codex.
4. Börja arbeta med stödda AI-leverantörer.

Din faktiska åtkomst, användningsgränser och tillgänglighet beror på motsvarande AI-leverantör och din webbläsarsession.

---

## 🐳 Installation

Distribuera BrowserMirrorAgents med Docker.

Ersätt `YOUR_LICENSE_KEY` med din personliga licensnyckel som du fick efter köpet.

`docker run -d --name browsermirroragents --restart unless-stopped -p 8000:8000 -e LICENSE_KEY=YOUR_LICENSE_KEY soft.p5g.ru/browsermirroragents:latest`

När containern körs, öppna:

**[http://localhost:8000](http://localhost:8000)**

Det var det! BrowserMirrorAgents är redo att användas.

---

## 💳 Prissättning

### $18.88 — Engångsbetalning

- Engångslicensköp
- Inga månatliga prenumerationer
- Inga återkommande betalningar
- Självhostad distribution

[Få Din Licens](https://agent.p5g.ru/)

## 🌍 Flerspråkigt Stöd

BrowserMirrorAgents stöder 21 språk:
- [English](../../README.md)
- [Español](../es/README.md)
- [Deutsch](../de/README.md)
- [Français](../fr/README.md)
- [Italiano](../it/README.md)
- [简体中文](../zh_CN/README.md)
- [繁體中文](../zh_TW/README.md)
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
- [Svenska](README.md)
- [Norsk](../no/README.md)
- [Русский](../ru/README.md)

## 🤖 AI-driven Gränssnittsövervakning

**Oroa dig inte för gränssnittsförändringar. Vi övervakar dem åt dig.**

AI-driven övervakning körs på vår sida och spårar förändringar i stödda AI-tjänster och deras webbläsargränssnitt.

När gränssnittselement eller selektorer ändras, upptäcker vårt system uppdateringarna och publicerar uppdaterade selektorer och kompatibilitetsjusteringar nästan omedelbart.

- **Kontinuerlig övervakning** — stödda gränssnitt övervakas regelbundet.
- **AI-driven detektering** — förändringar identifieras automatiskt.
- **Snabba uppdateringar** — uppdaterade selektorer och gränssnittsjusteringar publiceras snabbt.
- **Mindre underhåll** — inget behov av att manuellt spåra gränssnittsförändringar eller ständigt uppdatera selektorer själv.

**Vi övervakar gränssnitten. Du fokuserar på ditt arbete.**

## 💬 Community & Support

Detta repository är den centrala platsen för att rapportera problem, diskutera problem och dela lösningar relaterade till BrowserMirrorAgents.

Du är välkommen att:

- **Rapportera buggar** — skapa en issue om du stöter på oväntat beteende eller fel.
- **Begära funktioner** — föreslå förbättringar och nya integrationer.
- **Diskutera lösningar** — dela idéer, lösningar och workarounds med andra användare.
- **Ställa frågor** — diskutera konfiguration, kompatibilitet och användning.
- **Följa uppdateringar** — följ diskussioner om fixar, förbättringar och kompatibilitetsförändringar.

Innan du skapar en ny issue, kontrollera befintliga issues för att undvika duplicering.

**Hittat ett problem? Öppna en issue och låt oss lösa det tillsammans!**

---

## ❓ FAQ

### Behöver jag separata API-nycklar?

Nej. BrowserMirrorAgents är designat för att fungera genom befintliga webbläsarsessioner, så du behöver inte köpa separata API-nycklar för varje stödd leverantör.

### Vilka AI-kodningsverktyg stöds?

OpenCode och Codex.

### Vilka AI-leverantörer stöds?

Bitrix24, Qwen, DeepSeek, Google AI.

### Kan jag hosta det på min egen server?

Ja. BrowserMirrorAgents distribueras som en Docker-image och kan distribueras med Docker Compose.

### Finns det månadsavgifter?

Nej. BrowserMirrorAgents är tillgängligt med engångslicensköp.

### Är AI-tjänster obegränsade?

Användningen beror på tillgängligheten, policyerna och gränserna för varje AI-leverantör och dina webbläsarsessioner.

Du kan också ansluta flera webbläsarkonton och växla mellan sessioner, enligt respektive leverantörers tjänstevillkor.

---

## 🔗 Länkar

- **Webbplats:** https://agent.p5g.ru/
- **Licens:** Tillgänglig på den officiella webbplatsen.
- **Support:** Kontaktinformation finns på den officiella webbplatsen.

---

## ⚖️ Ansvarsfriskrivning

BrowserMirrorAgents är en oberoende mjukvaruprodukt och är inte ansluten till, godkänd av eller officiellt associerad med OpenAI, OpenCode, Bitrix24, Alibaba Cloud, DeepSeek eller deras respektive ägare.

Alla tredjeparts produktnamn och varumärken tillhör sina respektive ägare.

Användning av tredjeparts AI-tjänster omfattas av deras respektive tjänstevillkor, policyer och användningsbegränsningar.

---

**BrowserMirrorAgents**

*Ett integrationslager. Flera webbläsarbaserade AI-agenter.*
