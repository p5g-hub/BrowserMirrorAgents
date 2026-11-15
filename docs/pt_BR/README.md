![BrowserMirrorAgents](../../assets/banner.png)

# BrowserMirrorAgents

**Conecte OpenCode e Codex a agentes de IA baseados em navegador.**

BrowserMirrorAgents é uma camada de integração auto-hospedada que conecta ferramentas de codificação com IA a serviços de IA baseados em navegador.

Use seu ambiente de codificação com IA favorito com Bitrix24, Qwen e DeepSeek através de sessões de navegador existentes — sem precisar comprar chaves de API separadas para cada provedor.

[🌐 Site Oficial](https://agent.p5g.ru/)

---

## 🚀 Integrações Suportadas

### Ferramentas de Codificação com IA

| Integração | Status |
|---|---|
| OpenCode | Suportado |
| Codex | Suportado |

### Provedores de IA Baseados em Navegador

| Provedor | Suporte |
|---|---|
| Bitrix24 | Suportado |
| Qwen | Suportado |
| DeepSeek | Suportado |
| Google AI | Suportado |

---

## ✨ Por que BrowserMirrorAgents?

- **Sem chaves de API separadas** — use sessões de navegador em vez de comprar acesso individual à API.
- **Múltiplos provedores de IA** — conecte-se a diferentes serviços de IA baseados em navegador.
- **Integração com OpenCode** — use agentes de IA baseados em navegador no seu fluxo de trabalho OpenCode.
- **Integração com Codex** — conecte Codex aos serviços de IA de navegador suportados.
- **Auto-hospedado** — execute o aplicativo em seu próprio servidor.
- **Implantação Docker** — instalação simples usando Docker Compose.
- **Pagamento único** — sem assinatura recorrente.

## 🔌 Como Funciona

BrowserMirrorAgents atua como uma camada de integração entre ferramentas de codificação com IA e serviços de IA baseados em navegador.

1. Implante BrowserMirrorAgents em seu servidor.
2. Conecte suas sessões de IA baseadas em navegador.
3. Configure OpenCode ou Codex.
4. Comece a trabalhar com provedores de IA suportados.

Seu acesso real, limites de uso e disponibilidade dependem do provedor de IA correspondente e da sua sessão de navegador.

---

## 🐳 Instalação

Implante BrowserMirrorAgents usando Docker.

Substitua `YOUR_LICENSE_KEY` pela sua chave de licença pessoal recebida após a compra.

`docker run -d --name browsermirroragents --restart unless-stopped -p 8000:8000 -e LICENSE_KEY=YOUR_LICENSE_KEY soft.p5g.ru/browsermirroragents:latest`

Quando o container estiver em execução, abra:

**[http://localhost:8000](http://localhost:8000)**

É isso! BrowserMirrorAgents está pronto para usar.

---

## 💳 Preços

### $18.88 — Pagamento único

- Compra de licença única
- Sem assinaturas mensais
- Sem pagamentos recorrentes
- Implantação auto-hospedada

[Obtenha Sua Licença](https://agent.p5g.ru/)

## 🌍 Suporte Multilíngue

BrowserMirrorAgents suporta 21 idiomas:
- [English](../../README.md)
- [Español](../es/README.md)
- [Deutsch](../de/README.md)
- [Français](../fr/README.md)
- [Italiano](../it/README.md)
- [简体中文](../zh_CN/README.md)
- [繁體中文](../zh_TW/README.md)
- [Português (Brasil)](README.md)
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

## 🤖 Monitoramento de Interface Impulsionado por IA

**Não se preocupe com mudanças na interface. Nós as monitoramos para você.**

O monitoramento impulsionado por IA é executado do nosso lado, rastreando mudanças nos serviços de IA suportados e suas interfaces de navegador.

Quando elementos da interface ou seletores mudam, nosso sistema detecta as atualizações e publica seletores atualizados e ajustes de compatibilidade quase imediatamente.

- **Monitoramento contínuo** — interfaces suportadas são monitoradas regularmente.
- **Detecção impulsionada por IA** — mudanças são identificadas automaticamente.
- **Atualizações rápidas** — seletores atualizados e ajustes de interface são publicados prontamente.
- **Menos manutenção** — não há necessidade de rastrear manualmente mudanças na interface ou atualizar constantemente os seletores você mesmo.

**Nós monitoramos as interfaces. Você se concentra no seu trabalho.**

## 💬 Comunidade e Suporte

Este repositório é o local central para relatar problemas, discutir problemas e compartilhar soluções relacionadas ao BrowserMirrorAgents.

Você é bem-vindo para:

- **Relatar bugs** — crie um issue se encontrar comportamento inesperado ou erros.
- **Solicitar recursos** — sugira melhorias e novas integrações.
- **Discutir soluções** — compartilhe ideias, soluções alternativas e soluções com outros usuários.
- **Fazer perguntas** — discuta configuração, compatibilidade e uso.
- **Acompanhar atualizações** — acompanhe discussões sobre correções, melhorias e mudanças de compatibilidade.

Antes de criar um novo issue, verifique os issues existentes para evitar duplicatas.

**Encontrou um problema? Abra um issue e vamos resolvê-lo juntos!**

---

## ❓ FAQ

### Preciso de chaves de API separadas?

Não. BrowserMirrorAgents foi projetado para funcionar através de sessões de navegador existentes, então você não precisa comprar chaves de API separadas para cada provedor suportado.

### Quais ferramentas de codificação com IA são suportadas?

OpenCode e Codex.

### Quais provedores de IA são suportados?

Bitrix24, Qwen, DeepSeek, Google AI.

### Posso hospedá-lo em meu próprio servidor?

Sim. BrowserMirrorAgents é distribuído como uma imagem Docker e pode ser implantado usando Docker Compose.

### Há taxas mensais?

Não. BrowserMirrorAgents está disponível com uma compra de licença única.

### Os serviços de IA são ilimitados?

O uso depende da disponibilidade, políticas e limites de cada provedor de IA e das suas sessões de navegador.

Você também pode conectar várias contas de navegador e alternar entre sessões, sujeito aos termos de serviço dos respectivos provedores.

---

## 🔗 Links

- **Site:** https://agent.p5g.ru/
- **Licença:** Disponível no site oficial.
- **Suporte:** Informações de contato estão disponíveis no site oficial.

---

## ⚖️ Aviso Legal

BrowserMirrorAgents é um produto de software independente e não é afiliado, endossado ou oficialmente associado à OpenAI, OpenCode, Bitrix24, Alibaba Cloud, DeepSeek ou seus respectivos proprietários.

Todos os nomes de produtos de terceiros e marcas registradas pertencem aos seus respectivos proprietários.

O uso de serviços de IA de terceiros está sujeito aos seus respectivos termos de serviço, políticas e limitações de uso.

---

**BrowserMirrorAgents**

*Uma camada de integração. Múltiplos agentes de IA baseados em navegador.*
