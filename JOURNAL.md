# Carnet de bord — AquaHome Sentinel (Projet 6)

* **Établissement :** ESATIC · ING 1 · ECUE Fonction électronique (2026-2027)
* **Équipe :** Agoh Elvira, Bary Souleymane, Diomande Lassina, Atta Brindou, Kpai Sirus

---

## Semaine 1 — 25 novembre 2026
* **Objectif de la séance :** Cadrage du projet, répartition des rôles et rédaction de la fiche besoin.
* **Travail réalisé :**
  * Analyse du cahier des charges et définition des 5 scénarios d'usage (S1 à S5).
  * Rédaction et correction de la fiche besoin avec 8 exigences mesurables (`docs/AquaHome_Sentinel_Fiche_Besoin_Corrigee.pdf`).
  * Mise en place de l'architecture du dépôt GitHub (`docs`, `firmware`, `dashboard`, `tests`).
* **Décisions techniques prises :**
  * Périmètre fixé sur le socle minimal : 3 branches instrumentées, détection/localisation par règles simples (sans IA), coupure pompe < 2 s, alerte < 10 s.
  * Utilisation de 3 débitmètres (YF-S201) et 1 capteur de niveau (HC-SR04) sans capteur de pression.
  * Séparation physique stricte prévue entre la maquette hydraulique et le boîtier électronique.
* **Prochaines étapes :**
  * Faire valider la fiche besoin par l'encadrant (Revue Semaine 1 du 2 décembre 2026).
  * Réaliser les schémas d'architecture (hydraulique et câblage électrique) et finaliser la liste d'achat (BOM).
