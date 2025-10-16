# 🎯 Objectif
Décris en une phrase ce que tu veux accomplir.  
> Exemple : "Refactorer la structure du projet pour séparer les couches métier, infrastructure et présentation."

# 🏗️ Contexte
Décris brièvement l’état actuel du code ou de l’architecture.  
> Exemple :  
> - Application monolithique Node.js avec Express  
> - Couches métier et data entremêlées  
> - Difficulté à tester ou à faire évoluer  

# 🔍 Problèmes identifiés
Liste les points de douleur que tu veux corriger.  
> Exemple :  
> - Couplage fort entre modules  
> - Manque de modularité / testabilité  
> - Duplications dans la logique métier  
> - Difficulté à intégrer de nouveaux services

# 💡 Objectif du refactoring
Explique les objectifs techniques et organisationnels.  
> Exemple :  
> - Extraire des services indépendants  
> - Améliorer la maintenabilité  
> - Faciliter les tests unitaires  
> - Préparer une future migration vers le cloud  

# ⚙️ Contraintes techniques
Spécifie les technologies, frameworks, ou limitations.  
> Exemple :  
> - TypeScript  
> - API REST  
> - Aucune dépendance externe nouvelle  

# 📐 Attentes de sortie
Décris ce que tu veux que Copilot te génère.  
> Exemple :  
> - Une nouvelle arborescence de fichiers  
> - Des exemples de structure de code refactoré  
> - Des suggestions de séparation de modules  
> - Des noms de composants cohérents  

# 🧠 Style et bonnes pratiques
> - Suivre les principes **SOLID**  
> - Respecter le **12-Factor App**  
> - Favoriser l’injection de dépendances  
> - Respecter les conventions de nommage existantes  

# 🚀 Format de réponse attendu
Indique comment tu veux que Copilot te réponde.  
> Exemple :  
> - Sous forme de plan (arborescence + explication)  
> - Avec des exemples de code commenté  
> - En listant les étapes de migration progressive  

---

💬 **Astuce PromptOps :**
Tu peux stocker ce template dans un fichier `/prompts/refactoring-architecture.md` et l’appeler dans Copilot Chat avec :
