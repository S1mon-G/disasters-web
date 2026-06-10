# Plan d'action éco-conception
---

**<u>US sélectionnées</u>:**

- **US04** : Réduction du nombre de requêtes HTTP
- **US05** : Suppression de fonctionnalités non essentielles
- **US06** : Contrôler les animations
- **US07** : Supprimer le code mort
---

**<u>Etat avant modifications</u>:**

- Score Lighthouse performance: 45
- Score Lighthouse accessibilité: 79
- Nombre de requêtes réseau: 1468
- Classes CSS non utilisées: +50
- Dépendances non utilisées: ~7

**<u>Modifications prévues</u>:**

- **US04**
  - Appels API : identification des requêtes répétées ou fusionnables, fusion ou mise en cache en fonction.
  - Lazy loading: différer les requêtes non critiques

- **US05**
  - Three JS: suppression de la fonctionnalité innutile.

- **US06**
  - Mise en place d'un contrôle de l'animation d'accueil par l'utilisateur
  - Suppression de l'animation du titre

- **US07**
  - Supression du CSS mort
  - Supression des dépendances pas utilisées
---

**<u>Priorisation</u>:** 
- CSS: suppression des lignes de code non utilisées
- Package.json: suppression des dépendances jamais utilisées
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
- Réduction du poinds du CSS <10kB (DevTools)
- Réduction du bundle JS

**<u>Réalisations</u>:**
- [X] CSS: suppression des lignes de code non utilisées
- [ ] Package.json: suppression des dépendances jamais utilisées
- [ ] Three JS: suppression de l'animation (gain immédiat, impact direct sur les performances)
- [ ] Appels API : fusion ou mise en cache des requêtes répétées.
- [ ] Lazy loading: différer les requêtes non critiques
- [ ] Mise en place d'un contrôle de l'animation d'accueil
- [ ] Suppression de l'animation du titre
