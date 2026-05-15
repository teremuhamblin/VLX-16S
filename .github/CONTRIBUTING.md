# Contributing — VLX-16S ECU Project

Merci de votre intérêt pour le projet **VLX‑16S**.  
Ce document explique comment contribuer proprement et efficacement.

---

## 1. Pré-requis
- Git installé
- Python 3.10+
- Connaissance basique des ECU / systèmes embarqués
- Respect du code de conduite

---

## 2. Workflow Git
1. Fork du projet  
2. Création d’une branche :  
   `git checkout -b feature/nom-fonction`
3. Commits propres et descriptifs  
4. Push de la branche  
5. Pull Request vers `main`

---

## 3. Style de code
- Python : PEP8  
- Documentation obligatoire dans chaque module  
- Tests unitaires pour toute nouvelle fonctionnalité  
- Pas de code mort ou non utilisé

---

## 4. Structure recommandée
- `A-src/` : cœur du simulateur ECU  
- `Python-interface/` : interface utilisateur  
- `Include/` : headers, constantes  
- `Tests/` : tests unitaires  
- `Docs/` : documentation technique  

---

## 5. Pull Requests
Chaque PR doit inclure :
- Description claire  
- Changements listés  
- Tests associés  
- Aucun warning critique  

---

## 6. Sécurité
Toute faille doit être reportée via `SECURITY.md`.

Merci de contribuer à un projet propre, stable et professionnel.
