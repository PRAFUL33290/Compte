## 🎮 MÉCANIQUE DE CRÉATION — DRAG CONTINU (ESSENTIEL)

### 🔹 Principe

L’utilisateur peut créer plusieurs éléments/scènes **en un seul geste continu**, sans avoir besoin de relâcher la souris ou le doigt.

---

### 🔹 Comportement attendu

* Au clic (ou touch) sur un élément :
  → activation du mode “placement”

* Si l’utilisateur glisse :
  → chaque zone/case traversée crée automatiquement un élément

* Le placement se fait **en temps réel pendant le déplacement**

* Le geste s’arrête uniquement quand :
  → l’utilisateur relâche la souris ou le doigt

---

### 🔹 Exemple concret

* L’enfant sélectionne “forêt”
* Il glisse sur 5 cases
  → 5 scènes “forêt” sont créées automatiquement

---

### 🔹 Règles UX obligatoires

* Afficher un aperçu (ghost preview) avant placement
* Feedback visuel immédiat (animation / surbrillance)
* Son léger à chaque création (gratifiant)
* Taille de zone suffisamment grande pour les doigts

---

### 🔹 Spécificité mobile (iPad / iPhone)

* Support complet du tactile :

  * touchstart → active le placement
  * touchmove → crée en continu
  * touchend → stop

* Tolérance de mouvement (éviter les placements involontaires)

* Désactiver le scroll pendant le placement

---

### 🔹 Sécurité anti-erreur (IMPORTANT)

* Ne pas créer plusieurs éléments sur la même case
* Ajouter un délai minimum (ex : 50–100ms) entre chaque création
* Possibilité d’annuler (bouton undo)

---

### 🔹 Mode enfant (3–6 ans)

* Simplifier :

  * un seul type d’élément à la fois
  * feedback sonore renforcé
  * animation ludique à chaque placement

---

### 🔹 Objectif UX

Créer une sensation :

* fluide
* magique
* instantanée

L’enfant doit avoir l’impression de “dessiner son histoire avec le doigt”

---
