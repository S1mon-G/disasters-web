# Plan d'action éco-conception
---

**<u>US sélectionnées</u>:**

- **US04** : Réduction du nombre de requêtes HTTP
- **US05** : Suppression de fonctionnalités non essentielles
- **US06** : Contrôler les animations
---

**<u>Etat avant modifications</u>:**

- Score Lighthouse performance: 45
- Score Lighthouse accessibilité: 79
- Nombre de requêtes réseau: 1468

**<u>Modifications prévues</u>:**

- **US04**
  - Appels API : identification des requêtes répétées ou fusionnables, fusion ou mise en cache en fonction.
  - Lazy loading: différer les requêtes non critiques

- **US05**
  - Three JS: suppression de la fonctionnalité innutile.

- **US06**
  - Mise en place d'un contrôle de l'animation d'accueil par l'utilisateur
  - Suppression de l'animation du titre

---

**<u>Priorisation</u>:** 
- Three JS: suppression de l'animation (gain immédiat, impact direct sur les performances)
- Appels API : fusion ou mise en cache des requêtes répétées.
- Lazy loading: différer les requêtes non critiques
- Mise en place d'un contrôle de l'animation d'accueil
- Suppression de l'animation du titre

---

**<u>Résultats attendus</u>:**

- Score Lighthouse performance > 90
- Score Lighthouse accessibilité > 90
- Réduction des requêtes mesurable via GreenIT

