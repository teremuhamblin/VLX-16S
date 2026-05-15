# Security Threats
>VLX-16S ECU Project

Ce document recense les menaces potentielles liées au projet **VLX‑16S**, notamment celles touchant les systèmes ECU, le CAN Bus et les environnements embarqués.

---

## 1. Menaces critiques

### 🔥 1.1. Injection CAN Bus
- Envoi de trames malveillantes  
- Altération des valeurs capteurs  
- Override des actuateurs  
Impact : perte de contrôle moteur, comportement imprévisible.

### 🧨 1.2. Manipulation du mapping ECU
- Modification des tables d’allumage  
- Altération AFR  
- Override des limites de sécurité  
Impact : casse moteur, surchauffe, comportement dangereux.

### 🕳️ 1.3. Escalade de privilèges
- Accès non autorisé au simulateur  
- Exécution de code arbitraire  
Impact : compromission totale du système.

---

## 2. Menaces modérées

### ⚠️ 2.1. Corruption mémoire
- Overflow dans les modules sensors/actuators  
- Mauvaise gestion des buffers  
Impact : crash du simulateur, données incohérentes.

### ⚠️ 2.2. Attaques par déni de service
- Saturation du bus  
- Boucles infinies dans les modules  
Impact : blocage du simulateur ECU.

### ⚠️ 2.3. Exposition de données sensibles
- Fichiers de configuration moteur  
- Clés internes  
Impact : fuite d’informations critiques.

---

## 3. Menaces mineures

### 🛑 3.1. Mauvaise configuration
- Paramètres moteur incohérents  
- Valeurs par défaut dangereuses  
Impact : comportement imprévisible.

### 🛑 3.2. Documentation incomplète
- Mauvaise compréhension du système  
Impact : erreurs de manipulation.

---

## 4. Mesures de mitigation

### ✔️ 4.1. Validation stricte des entrées
- Filtrage des trames CAN  
- Vérification des valeurs capteurs  

### ✔️ 4.2. Tests de sécurité
- Tests unitaires  
- Tests d’intégrité du mapping  
- Analyse statique  

### ✔️ 4.3. Gestion des accès
- Aucun accès public aux fichiers sensibles  
- Isolation des modules critiques  

### ✔️ 4.4. Processus de patch
1. Analyse  
2. Reproduction  
3. Correctif  
4. Tests  
5. Release patch  
6. Mise à jour du CHANGELOG  

---

## 5. Signalement
Toute menace doit être reportée **en privé** selon la procédure définie dans `SECURITY.md`.

---

Ce document évolue avec le projet et doit être mis à jour à chaque nouvelle version majeure.
