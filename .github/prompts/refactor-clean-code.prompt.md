---
mode: "agent"
description: 'Améliorer l application avec les principes Clean Code en appliquant directement les modifications'
---

#  Objectif
Analyser et **refactoriser directement le code** afin qu'il respecte les principes du **Clean Code**, en améliorant la lisibilité, la simplicité, la cohérence et la testabilité sans modifier le comportement fonctionnel.

#  Contexte
Code existant nécessitant amélioration avec :
- Violations des principes Clean Code (nommage, responsabilités, etc.)
- Dette technique accumulée impactant la maintenabilité
- Code complexe, dupliqué ou peu lisible
- Besoin d'amélioration progressive sans régression fonctionnelle
- Standards modernes du langage non appliqués

#  Problèmes identifiés
- **Nommage peu clair** : Variables, fonctions et classes mal nommées
- **Responsabilités multiples** : Classes/méthodes violant le principe SRP
- **Complexité cyclique élevée** : Logique imbriquée difficile à comprendre
- **Code dupliqué** : Violation du principe DRY
- **Manque d'explicité** : Code nécessitant trop de commentaires
- **Effets de bord non isolés** : Fonctions impures difficiles à tester

#  Objectif du refactoring
- **Appliquer Clean Code** : Nommage clair, responsabilité unique, simplicité
- **Réduire la complexité** : Décomposer les blocs complexes
- **Éliminer la duplication** : Factoriser le code redondant
- **Améliorer la testabilité** : Isoler les effets de bord
- **Maintenir la cohérence** : Standards et conventions uniformes

#  Contraintes techniques
- **Préserver le comportement** : Aucune régression fonctionnelle
- **Maintenir l'API** : Compatibilité des interfaces publiques
- **Modifications directes** : Appliquer sur les fichiers existants
- **Progressivité** : Une refactorisation à la fois
- **Standards modernes** : Aligner sur les bonnes pratiques du langage

#  Attentes de sortie
1. **Analyse initiale** :
   - Identification des code smells et violations Clean Code
   - Priorisation des modifications par impact/facilité

2. **Refactorisations appliquées** :
   - Modification directe des fichiers étape par étape
   - Documentation du principe Clean Code appliqué
   - Validation du comportement préservé

3. **Résumé des améliorations** :
   - Liste des modifications effectuées
   - Métriques d'amélioration (si mesurables)
   - Recommandations pour la suite

#  Style et bonnes pratiques
- **KISS** : Keep It Simple, Stupid - simplicité avant tout
- **DRY** : Don't Repeat Yourself - éliminer la duplication
- **SOLID** : Principes de conception orientée objet
- **Clean Code** : Robert C. Martin - nommage, fonctions, classes

#  Format de réponse attendu
1. ** Étape N : [Titre de la modification]**
   - **Problème identifié** : Code smell détecté
   - **Principe appliqué** : Référence Clean Code
   - **Modification** : Application directe sur le fichier
   - **Bénéfice** : Amélioration apportée

2. ** Résumé global** :
   - Modifications appliquées avec références
   - Métriques d'amélioration
   - Recommandations futures
