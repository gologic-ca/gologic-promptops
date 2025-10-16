---
mode: "agent"
description: 'Générer un pipeline CI adapté au projet et à l outil d orchestration choisi'
---

#  Objectif
Générer un pipeline **Continuous Integration (CI)** adapté au contexte d'un projet (application, serverless, Infrastructure-as-Code) en demandant d'abord l'outil d'orchestration pour adapter la syntaxe et les bonnes pratiques.

#  Contexte
Projet nécessitant un pipeline CI avec :
- Code source sans pipeline automatisé ou pipeline obsolète
- Besoin d'automatisation des étapes build, test, publish
- Multiples outils d'orchestration possibles (GitHub Actions, GitLab CI, etc.)
- Stack technologique variée selon le type de projet
- Exigences de sécurité et d'observabilité modernes

#  Problèmes identifiés
- **Pas d'outil d'orchestration défini** : Syntaxe YAML différente selon la plateforme
- **Pipeline manquant ou obsolète** : Pas d'automatisation des builds/tests
- **Sécurité insuffisante** : Pas de scan de vulnérabilités ou gestion des secrets
- **Manque d'observabilité** : Pas de métriques DORA ou traçabilité
- **Configuration manuelle** : Étapes de déploiement non reproductibles

#  Objectif du refactoring
- **Identifier l'orchestrateur** : Demander l'outil CI/CD avant génération
- **Pipeline adapté** : Syntaxe et bonnes pratiques spécifiques à la plateforme
- **Sécurité intégrée** : Scans, gestion des secrets, conformité
- **Observabilité** : Métriques, logs, artefacts, alertes

#  Contraintes techniques
- **Demander l'orchestrateur** : GitHub Actions, GitLab CI, Azure DevOps, Jenkins, etc.
- **Agnostique technologie** : Adaptable à tout langage/framework
- **Sécurité obligatoire** : Pas de secrets en clair, scans intégrés
- **Reproductibilité** : Pipeline exécutable en local et en CI

#  Attentes de sortie
1. **Configuration initiale** :
   - Question sur l'outil d'orchestration CI/CD
   - Détection du type de projet et stack technologique

2. **Pipeline YAML complet** :
   - Fichier adapté à l'orchestrateur choisi
   - Étapes Build  Test  Publish structurées
   - Gestion des secrets et variables d'environnement

3. **Bonnes pratiques intégrées** :
   - Scans de sécurité (Trivy, Snyk)
   - Tests automatisés avec couverture
   - Artefacts versionnés et signés

#  Style et bonnes pratiques
- **KISS** : Keep It Simple, Stupid - pipeline minimal viable
- **DRY** : Don't Repeat Yourself - éviter la duplication
- **Security by design** : sécurité intégrée dès le départ
- **DORA metrics** : Lead Time, Deployment Frequency, MTTR, Change Fail Rate

#  Format de réponse attendu
1. **Question initiale** : Quel outil d'orchestration CI/CD utilisez-vous ?
2. **Pipeline généré** :
   - Fichier YAML complet avec commentaires
   - Explication étape par étape (build/test/publish)
3. **Recommandations** :
   - Améliorations sécurité et performance
   - Métriques et observabilité
