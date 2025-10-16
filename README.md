# 🚀 Gologic Copilot PromptOps

> **Collection de prompts d'ingénierie logicielle pour GitHub Copilot**  
> Accélérez vos pratiques DevOps, sécurité et architecture avec des agents IA spécialisés

## 📋 Vue d'ensemble

Ce dépôt contient une collection complète de **prompts d'agent GitHub Copilot** pour améliorer la qualité, la sécurité et la fiabilité de vos applications. Tous les prompts suivent le format standardisé [`PROMPT.md`](PROMPT.md) pour garantir cohérence et professionnalisme.

### 🎯 Objectifs du projet

- **Standardiser** les pratiques d'ingénierie logicielle via l'IA
- **Accélérer** l'adoption des bonnes pratiques (Clean Code, DevOps, SRE)
- **Sécuriser** le développement avec des revues automatisées
- **Simplifier** l'implémentation des architectures modernes

## 📚 Catalogue des prompts

### 🏗️ **Twelve-Factor Apps** (12 prompts)
Implémentez les principes des [Twelve-Factor Apps](https://12factor.net/fr/) pour des applications cloud-native robustes :

| # | Principe | Description | Prompt |
|---|----------|-------------|--------|
| 1 | **Codebase** | Une seule base de code suivie par gestion de version, plusieurs déploiements | [🔗](/.github/prompts/twelve-factor-01.prompt.md) |
| 2 | **Dependencies** | Déclarer et isoler explicitement toutes les dépendances | [🔗](/.github/prompts/twelve-factor-02.prompt.md) |
| 3 | **Config** | Stocker la configuration dans l'environnement, pas dans le code | [🔗](/.github/prompts/twelve-factor-03.prompt.md) |
| 4 | **Backing Services** | Traiter les services externes comme des ressources attachées | [🔗](/.github/prompts/twelve-factor-04.prompt.md) |
| 5 | **Build, Release, Run** | Séparer strictement les étapes de build, release et run | [🔗](/.github/prompts/twelve-factor-05.prompt.md) |
| 6 | **Processes** | Exécuter l'application comme un ou plusieurs processus sans état | [🔗](/.github/prompts/twelve-factor-06.prompt.md) |
| 7 | **Port Binding** | Exposer les services via des ports | [🔗](/.github/prompts/twelve-factor-07.prompt.md) |
| 8 | **Concurrency** | Mettre à l'échelle via le modèle de processus | [🔗](/.github/prompts/twelve-factor-08.prompt.md) |
| 9 | **Disposability** | Maximiser la robustesse avec des démarrages rapides et des arrêts gracieux | [🔗](/.github/prompts/twelve-factor-09.prompt.md) |
| 10 | **Dev/Prod Parity** | Garder les environnements aussi similaires que possible | [🔗](/.github/prompts/twelve-factor-10.prompt.md) |
| 11 | **Logs** | Traiter les logs comme des flux d'événements | [🔗](/.github/prompts/twelve-factor-11.prompt.md) |
| 12 | **Admin Processes** | Exécuter les tâches d'administration comme des processus ponctuels | [🔗](/.github/prompts/twelve-factor-12.prompt.md) |

### 🔧 **DevOps & Engineering**

| Prompt | Description | Cas d'usage |
|--------|-------------|-------------|
| [**CI Pipeline Builder**](/.github/prompts/ci-pipeline-builder.prompt.md) | Générer des pipelines CI adaptés à votre orchestrateur | GitHub Actions, GitLab CI, Azure DevOps, Jenkins |
| [**Clean Code Refactoring**](/.github/prompts/refactor-clean-code.prompt.md) | Améliorer le code avec les principes Clean Code | Refactoring, dette technique, maintenabilité |

### 🛡️ **Sécurité & Fiabilité**

| Prompt | Description | Spécialisation |
|--------|-------------|----------------|
| [**Security Code Review**](/.github/prompts/security-code-review.prompt.md) | Auditer la sécurité avec les principes OWASP | AppSec, vulnérabilités, SSDLC |
| [**SRE Guardian**](/.github/prompts/sre-guardian.prompt.md) | Améliorer la fiabilité avec les principes SRE | Observabilité, résilience, DORA metrics |

## 🚀 Comment utiliser

### 1. **Choisir le prompt adapté**
Identifiez le domaine d'amélioration (architecture, sécurité, CI/CD, etc.)

### 2. **Ouvrir dans GitHub Copilot**
```bash
# Copier le contenu du prompt dans GitHub Copilot Chat
# Ou utiliser directement via @workspace
```

### 3. **Décrire votre contexte**
- État actuel de votre application
- Technologies utilisées  
- Objectifs spécifiques

### 4. **Appliquer les recommandations**
L'agent analysera votre code et proposera des améliorations concrètes

## 📖 Format standardisé

Tous les prompts suivent le format [`PROMPT.md`](PROMPT.md) avec 8 sections structurées :

- 🎯 **Objectif** - But du prompt
- 🏗️ **Contexte** - Situation actuelle
- 🔍 **Problèmes identifiés** - Points de douleur
- 💡 **Objectif du refactoring** - Résultats attendus
- ⚙️ **Contraintes techniques** - Limitations et prérequis
- 📐 **Attentes de sortie** - Livrables concrets
- 🧠 **Style et bonnes pratiques** - Références méthodologiques
- 🚀 **Format de réponse attendu** - Structure des recommandations

## 🏢 À propos de Gologic

**Gologic** est spécialisé dans l'accompagnement des entreprises vers l'excellence technique et opérationnelle. Ces prompts démontrent notre approche **AI-First** pour :

- Accélérer l'adoption des bonnes pratiques
- Standardiser la qualité logicielle
- Réduire la dette technique
- Optimiser les performances et la sécurité

---

### 🤝 Contribution

Les contributions sont bienvenues ! Assurez-vous de suivre le format [`PROMPT.md`](PROMPT.md) pour maintenir la cohérence.

### 📄 Licence

Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE) pour plus de détails.