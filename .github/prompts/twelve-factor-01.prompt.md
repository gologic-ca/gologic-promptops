# 🎯 Objectif
Transformer mon application pour respecter le **Principe #1 - Codebase** des Twelve-Factor Apps : "Une seule base de code suivie par gestion de version, plusieurs déploiements".

📖 **Référence :** https://www.12factor.net/codebase

# 🏗️ Contexte
Application avec architecture actuelle :
- Code source dans un ou plusieurs repositories
- Configuration mélangée avec le code applicatif
- Potentiels duplications entre environnements
- Gestion de version non standardisée
- Processus de déploiement manuel ou incohérent

# 🔍 Problèmes identifiés
- **Multiples bases de code** : Code dupliqué entre environnements ou projets
- **Configuration dans le code** : Valeurs spécifiques aux environnements intégrées au code
- **Inconsistance des déploiements** : Différents artefacts selon l'environnement
- **Traçabilité insuffisante** : Difficile de savoir quelle version est déployée où
- **Gestion de version fragmentée** : Pas de source unique de vérité

# 💡 Objectif du refactoring
- **Repository unique** : Consolider tout le code dans un seul repository
- **Séparation code/configuration** : Externaliser toute configuration spécifique aux environnements
- **Artefact unique** : Même build déployé dans tous les environnements

# ⚙️ Contraintes techniques
- **Un seul repository** : Consolidation obligatoire si multiples repos
- **Configuration externalisée** : Aucune valeur spécifique à l'environnement dans le code
- **Build reproductible** : Même processus de construction partout

# 📐 Attentes de sortie
1. **Structure de repository** :
   - Consolidation en repository unique si nécessaire
   - Structure de dossiers claire et cohérente
   - Fichiers de configuration externalisés

2. **Gestion de la configuration** :
   - Séparation complète entre code et configuration
   - Templates de configuration par environnement
   - Variables d'environnement documentées
   - Mécanisme d'injection de configuration

3. **Processus de build** :
   - Script de build reproductible
   - Artefact unique pour tous les environnements
   - Versioning sémantique automatisé

4. **Stratégie de déploiement** :
   - Workflow Git standardisé
   - Mapping versions ↔ environnements
   - Automation du déploiement

# 🧠 Style et bonnes pratiques
- Respecter **strictement** le principe Codebase des 12-Factor Apps
- **KISS** : Keep It Simple, Stupid - solution minimale viable
- **DRY** : Don't Repeat Yourself - éviter la duplication
- **YAGNI** : You Aren't Gonna Need It - pas de sur-ingénierie

# 🚀 Format de réponse attendu
1. **Audit du codebase** : Analyse simple de la conformité actuelle
2. **Refactoring minimal** :
   - Consolidation repository si nécessaire
   - Externalisation de la configuration
   - Setup build reproductible

---

💬 **Objectif final :** Application respectant 100% le principe Codebase avec repository unique, configuration externalisée et déploiements reproductibles.