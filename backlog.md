# Backlog du projet "Optimisation Sante+"

## USER STORIES

---

### Story 1 : Chargement initial plus rapide

**En tant que** nouvel utilisateur web,  
**je veux** que l’écran d’accueil charge en moins de 1,5 s  
**afin de** ne pas décrocher lors d’un pic de réseau lent.

- 🎯 Objectif : temps de chargement < 1500 ms
- 🧱 BP associée : réduire taille des ressources / lazy-loading
- 🛠️ KPI : LCP sur web (Lighthouse)
- 📅 Tag roadmap : M2

---

### Story 2 : Réduction poids images

**En tant que** utilisateur récurrent,  
**je veux** que les visuels du dashboard soient plus légers  
**afin de** économiser de la data sur mon forfait.

- 🎯 Objectif : 80% des images converties en WebP
- 🧱 BP associée : compression d’images / formats modernes
- 🛠️ KPI : poids total dossier `/assets` < 2 Mo
- 📅 Tag roadmap : M3

---

### Story 3 : Accessibilité améliorée

**En tant que** utilisateur malvoyant,  
**je veux** que les contrastes texte/fond soient conformes AA  
**afin de** pouvoir utiliser l’app sans difficulté visuelle.

- 🎯 Objectif : conformité AA WCAG
- 🧱 BP associée : respect contrastes (RGESN 6.3)
- 🛠️ KPI : score accessibilité Lighthouse > 90
- 📅 Tag roadmap : M4

...

---

### Story 4: Réduction du nombre de requêtes HTTP

**En tant que** utilisateur sur un réseau lent ,  
**je veux** que les pages se chargent rapidement
**afin de** ne pas attendre longtemps pour pouvoir utiliser l'application sans frustration.

- 🎯 Objectif : augmentation des performances
- 🧱 BP associée : limiter le nombre de requêtes HTTP (RGESN: 6.1 et 4.9)
- 🛠️ KPI : score performance Lighthouse > 90
- 📅 Tag roadmap : M1

---

### Story 5: Suppression de fonctionnalités non essentielles

**En tant que** développeur ,  
**je veux** retirer les fonctionnalités non essentielles
**afin de** répondre réellement au besoin de l'utilisateur

- 🎯 Objectif : augmentation des performances et meilleur accessibilité
- 🧱 BP associée : eliminer les fonctionnalités non essentielles (RGESN: 1.2 et 2.7)
- 🛠️ KPI : score performance Lighthouse > 90
- 📅 Tag roadmap : M2

---

### Story 6: Contrôler les animations

**En tant que** utilisateur ,  
**je veux** controler les animations de la page
**afin de** naviguer de manière plus agréable sans distraction

- 🎯 Objectif : rendre la page plus accessibile
- 🧱 BP associée : éviter les animations JavaScript/CSS (RGESN: NA - RWEB 003)
- 🛠️ KPI : score accessibilité Lighthouse > 90
- 📅 Tag roadmap : M4

