![BrowserMirrorAgents](../../assets/banner.png)

# BrowserMirrorAgents

**Connectez OpenCode et Codex aux agents IA basés sur le navigateur.**

BrowserMirrorAgents est une couche d'intégration auto-hébergée qui connecte les outils de codage IA aux services IA basés sur le navigateur.

Utilisez votre environnement de codage IA préféré avec Bitrix24, Qwen et DeepSeek via des sessions de navigateur existantes — sans acheter de clés API séparées pour chaque fournisseur.

[🌐 Site Web Officiel](https://agent.p5g.ru/)

---

## 🚀 Intégrations Prises en Charge

### Outils de Codage IA

| Intégration | Statut |
|---|---|
| OpenCode | Pris en charge |
| Codex | Pris en charge |

### Fournisseurs IA Basés sur le Navigateur

| Fournisseur | Support |
|---|---|
| Bitrix24 | Pris en charge |
| Qwen | Pris en charge |
| DeepSeek | Pris en charge |
| Google AI | Pris en charge |

---

## ✨ Pourquoi BrowserMirrorAgents ?

- **Pas de clés API séparées** — utilisez des sessions de navigateur au lieu d'acheter un accès API individuel.
- **Plusieurs fournisseurs IA** — connectez-vous à différents services IA basés sur le navigateur.
- **Intégration OpenCode** — utilisez des agents IA basés sur le navigateur dans votre flux de travail OpenCode.
- **Intégration Codex** — connectez Codex aux services IA de navigateur pris en charge.
- **Auto-hébergé** — exécutez l'application sur votre propre serveur.
- **Déploiement Docker** — installation simple avec Docker Compose.
- **Paiement unique** — pas d'abonnement récurrent.

## 🔌 Comment ça fonctionne

BrowserMirrorAgents agit comme une couche d'intégration entre les outils de codage IA et les services IA basés sur le navigateur.

1. Déployez BrowserMirrorAgents sur votre serveur.
2. Connectez vos sessions IA basées sur le navigateur.
3. Configurez OpenCode ou Codex.
4. Commencez à travailler avec les fournisseurs IA pris en charge.

Votre accès réel, vos limites d'utilisation et votre disponibilité dépendent du fournisseur IA correspondant et de votre session de navigateur.

---

## 🐳 Installation

Déployez BrowserMirrorAgents en utilisant Docker.

Remplacez `YOUR_LICENSE_KEY` par votre clé de licence personnelle reçue après l'achat.

`docker run -d --name browsermirroragents --restart unless-stopped -p 8000:8000 -e LICENSE_KEY=YOUR_LICENSE_KEY soft.p5g.ru/browsermirroragents:latest`

Une fois le conteneur en cours d'exécution, ouvrez :

**[http://localhost:8000](http://localhost:8000)**

C'est tout ! BrowserMirrorAgents est prêt à l'emploi.

---

## 💳 Tarification

### $18.88 — Paiement unique

- Achat de licence unique
- Pas d'abonnements mensuels
- Pas de paiements récurrents
- Déploiement auto-hébergé

[Obtenez Votre Licence](https://agent.p5g.ru/)

## 🌍 Support Multilingue

BrowserMirrorAgents prend en charge 21 langues :
- [English](../../README.md)
- [Español](../es/README.md)
- [Deutsch](../de/README.md)
- [Français](README.md)
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
- [Svenska](../sv/README.md)
- [Norsk](../no/README.md)
- [Русский](../ru/README.md)

## 🤖 Surveillance d'Interface Alimentée par l'IA

**Ne vous inquiétez pas des changements d'interface. Nous les surveillons pour vous.**

La surveillance alimentée par l'IA s'exécute de notre côté, suivant les changements dans les services IA pris en charge et leurs interfaces de navigateur.

Lorsque les éléments d'interface ou les sélecteurs changent, notre système détecte les mises à jour et publie des sélecteurs actualisés et des ajustements de compatibilité presque immédiatement.

- **Surveillance continue** — les interfaces prises en charge sont régulièrement surveillées.
- **Détection alimentée par l'IA** — les changements sont identifiés automatiquement.
- **Mises à jour rapides** — les sélecteurs actualisés et les ajustements d'interface sont publiés rapidement.
- **Moins de maintenance** — pas besoin de suivre manuellement les changements d'interface ou de mettre constamment à jour les sélecteurs vous-même.

**Nous surveillons les interfaces. Vous vous concentrez sur votre travail.**

## 💬 Communauté & Support

Ce dépôt est l'endroit central pour signaler des problèmes, discuter des problèmes et partager des solutions liées à BrowserMirrorAgents.

Vous êtes invité à :

- **Signaler des bugs** — créez un issue si vous rencontrez un comportement inattendu ou des erreurs.
- **Demander des fonctionnalités** — suggérez des améliorations et de nouvelles intégrations.
- **Discuter des solutions** — partagez des idées, des solutions de contournement et des solutions avec d'autres utilisateurs.
- **Poser des questions** — discutez de la configuration, de la compatibilité et de l'utilisation.
- **Suivre les mises à jour** — suivez les discussions sur les correctifs, les améliorations et les changements de compatibilité.

Avant de créer un nouvel issue, veuillez vérifier les issues existants pour éviter les doublons.

**Vous avez trouvé un problème ? Ouvrez un issue et résolvons-le ensemble !**

---

## ❓ FAQ

### Ai-je besoin de clés API séparées ?

Non. BrowserMirrorAgents est conçu pour fonctionner via des sessions de navigateur existantes, donc vous n'avez pas besoin d'acheter des clés API séparées pour chaque fournisseur pris en charge.

### Quels outils de codage IA sont pris en charge ?

OpenCode et Codex.

### Quels fournisseurs IA sont pris en charge ?

Bitrix24, Qwen, DeepSeek, Google AI.

### Puis-je l'héberger sur mon propre serveur ?

Oui. BrowserMirrorAgents est distribué en tant qu'image Docker et peut être déployé en utilisant Docker Compose.

### Y a-t-il des frais mensuels ?

Non. BrowserMirrorAgents est disponible avec un achat de licence unique.

### Les services IA sont-ils illimités ?

L'utilisation dépend de la disponibilité, des politiques et des limites de chaque fournisseur IA et de vos sessions de navigateur.

Vous pouvez également connecter plusieurs comptes de navigateur et basculer entre les sessions, sous réserve des conditions d'utilisation des fournisseurs respectifs.

---

## 🔗 Liens

- **Site web :** https://agent.p5g.ru/
- **Licence :** Disponible sur le site web officiel.
- **Support :** Les informations de contact sont disponibles sur le site web officiel.

---

## ⚖️ Avertissement

BrowserMirrorAgents est un produit logiciel indépendant et n'est pas affilié, approuvé ou officiellement associé à OpenAI, OpenCode, Bitrix24, Alibaba Cloud, DeepSeek ou leurs propriétaires respectifs.

Tous les noms de produits tiers et marques commerciales appartiennent à leurs propriétaires respectifs.

L'utilisation des services IA tiers est soumise à leurs conditions d'utilisation, politiques et limitations d'utilisation respectives.

---

**BrowserMirrorAgents**

*Une couche d'intégration. Plusieurs agents IA basés sur le navigateur.*
