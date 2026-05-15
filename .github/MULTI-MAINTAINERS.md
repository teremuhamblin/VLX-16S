# Multi‑Maintainers — VLX‑16S ECU Project

Ce document définit l’équipe de maintenance du projet **VLX‑16S**, leurs rôles, responsabilités et domaines d’intervention.  
Il garantit une gouvernance claire, stable et professionnelle du projet.

---

## 👑 Mainteneur Principal

### **@Teremu**
Rôle global :
- Direction technique du projet  
- Validation finale des Pull Requests  
- Gestion des versions et releases  
- Supervision de l’architecture ECU  
- Sécurité, vulnérabilités, conformité  
- Cohérence globale (code, docs, assets, CI/CD)

---

## 🧩 Mainteneurs par Domaine

### 🔧 1. Core ECU & Architecture
Responsable : **@Teremu**  
Responsabilités :
- Modules Sensors / Actuators  
- CAN Bus  
- Diagnostics  
- Mapping moteur VLX‑16S  
- Gestion des configurations moteur  

---

### 📚 2. Documentation & Standards
Responsable : **@Teremu**  
Responsabilités :
- Documentation technique (Docs/)  
- Guides développeurs  
- Normes de contribution  
- Chartes graphiques  
- Maintenance des fichiers `.md` globaux  

---

### 🛡️ 3. Sécurité & Analyse des Menaces
Responsable : **@Teremu**  
Responsabilités :
- Analyse des vulnérabilités  
- Gestion des rapports privés  
- Correctifs de sécurité  
- Mise à jour de SECURITY.md  
- Mise à jour de SECURITY‑THREATS.md  

---

### ⚙️ 4. CI/CD & Automatisation
Responsable : **@Teremu**  
Responsabilités :
- GitHub Actions  
- Tests automatisés  
- Analyse statique  
- Qualité du code  
- Pipelines de build  

---

### 🧪 5. Tests & Validation
Responsable : **@Teremu**  
Responsabilités :
- Tests unitaires  
- Tests d’intégration  
- Tests ECU spécifiques  
- Validation des PR techniques  

---

## 🔄 Processus d’Ajout ou de Retrait d’un Mainteneur

1. Proposition via Pull Request  
2. Discussion et validation par le mainteneur principal  
3. Mise à jour de :
   - MULTI-MAINTAINERS.md  
   - CODEOWNERS.md  
4. Notification dans le CHANGELOG  

---

## 📌 Règles Générales

- Respect du Code de Conduite  
- Communication claire et professionnelle  
- Documentation obligatoire pour toute modification majeure  
- Tests requis pour toute nouvelle fonctionnalité  
- Transparence sur les décisions techniques  

---

## 🏁 Conclusion

L’équipe de maintenance garantit la stabilité, la sécurité et l’évolution du projet **VLX‑16S**.  
Toute modification de ce fichier doit être approuvée par le mainteneur principal.
