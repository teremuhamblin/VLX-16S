# 📘 CHANGELOG — VLX‑16S

Format basé sur *Keep a Changelog*.  
Versions suivant *Semantic Versioning*.

---

## [5.0.0] — 2026-XX-XX
### Added
- Nouveau moteur de simulation haute-fidélité (cycle 4T complet)
- Gestion avancée AFR, knock, lambda, ignition maps
- Interface Python 2.0 (dashboard tactique)
- Système de plugins ECU
- Mode “Stealth” (réduction thermique & bruit moteur)

### Improved
- Optimisation du cœur ECU (+40% performance)
- Refonte architecture C++ (Core / IO / Maps)

### Fixed
- Correction des valeurs d’avance à haut régime

---

## [4.0.0] — 2026-XX-XX
### Added
- Support moteur Diesel 2.2L (profil VT4)
- CAN-bus virtuel + messages ECU standardisés
- Mode “Dégradé+” avec sécurité thermique
- Générateur de logs tactiques

### Improved
- Stabilisation injection en charge élevée
- Amélioration du modèle thermique

---

## [3.0.0] — 2025-XX-XX
### Added
- Interface Python (FastAPI) v1.0
- Visualisation RPM / Load / Temp en temps réel
- Système de configuration YAML

### Improved
- Courbes d’injection plus réalistes
- Gestion capteurs plus stable

---

## [2.0.0] — 2025-XX-XX
### Added
- Modes ECU : Civil / Tactique / Dégradé
- Profil moteur 1.6L essence
- Tests unitaires GoogleTest

### Improved
- Refactoring du modèle moteur
- Documentation technique initiale

---

## [1.0.0] — 2025-XX-XX
### Added
- Version initiale du simulateur ECU
- Modèle moteur minimal (RPM, charge, température)
- Injection & allumage basiques
- README + logo + structure du projet
