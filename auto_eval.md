## 🧾 Auto-évaluation — Projet « CV Web – page HTML statique »

**Nom :** T****n B****y
**Formation :** BTS SIO option SISR — 1ʳᵉ année
**Date :** octobre 2025
**URL du site GitHub Pages :** [https://trbarry.github.io/page_cv/](https://trbarry.github.io/page_cv/)
**Dépôt GitHub :** [github.com/Trbarry/page_cv](https://github.com/Trbarry/page_cv)

---

### 1. Synthèse générale

Le projet consiste en la réalisation d’un **CV web statique**, conforme aux bonnes pratiques de **sémantique HTML, d’accessibilité, de performance et de SEO**, publié via **GitHub Pages**.
J’ai pris comme objectif de livrer une page **sobre, responsive, professionnelle**, avec une cohérence visuelle (thème sombre violet) et une structure claire (sections Profil, Projets, Formations, etc.).

---

### 2. Résultats des validateurs et améliorations

| Outil                            | Résultat V1                                               | Actions correctives                                                              | Résultat final  |
| -------------------------------- | --------------------------------------------------------- | -------------------------------------------------------------------------------- | --------------- |
| **W3C Validator**                | 3 erreurs mineures (balises non fermées, alt manquant)    | Correction du balisage, suppression des attributs non conformes                  | ✅ Aucune erreur |
| **Outiref**                      | Meta description trop courte, hiérarchie H mal équilibrée | Ajout d’une meta description longue et précise, hiérarchie H1 > H2 > H3 vérifiée | ✅ Score optimal |
| **PageSpeed Insights (Desktop)** | 94/100 – Police non optimisée                             | Ajout du `font-display: swap` dans la @font-face Bootstrap Icons                 | ✅ 98/100        |
| **PageSpeed Insights (Mobile)**  | 88/100 – Légères optimisations possibles                  | Allègement CSS et defer des scripts                                              | ✅ 93/100        |
| **Accessibilité (Lighthouse)**   | 88/100 – Couleurs à ajuster                               | Palette uniformisée (#8b5cf6) + contrastes renforcés                             | ✅ 96/100        |

---

### 3. Évaluation par critère

| N°      | Critère                     | Score (0–4) | Coef    | Score pondéré | Justification                                                                                                         |
| ------- | --------------------------- | ----------- | ------- | ------------- | --------------------------------------------------------------------------------------------------------------------- |
| **C1**  | Contenu du CV               | **4**       | 10      | 40            | Informations claires, bien structurées, aucune faute. Contenu professionnel et concis.                                |
| **C2**  | HTML sémantique             | **4**       | 10      | 40            | Hiérarchie H1→H2→H3 respectée, balises `<header>`, `<main>`, `<section>`, `<footer>`, `<nav>` utilisées correctement. |
| **C3**  | Responsive & mise en page   | **4**       | 15      | 60            | Structure Bootstrap, flexbox responsive sans scroll horizontal. Rendu stable sur mobile et desktop.                   |
| **C4**  | UX & Accessibilité          | **4**       | 15      | 60            | Contrastes suffisants, focus visibles, navigation clavier fonctionnelle, textes lisibles.                             |
| **C5**  | SEO minimum                 | **4**       | 10      | 40            | Title/meta précis, balises canoniques et description >200 caractères, liens explicites.                               |
| **C6**  | Performance                 | **4**       | 10      | 40            | CSS minimal, scripts en `defer`, polices optimisées, CDN rapide (JSDelivr).                                           |
| **C7**  | Validation & corrections    | **4**       | 10      | 40            | W3C validé, Outiref propre, PageSpeed >90, journal de corrections documenté.                                          |
| **C8**  | Publication GitHub Pages    | **4**       | 5       | 20            | Site public, opérationnel, testé sur mobile et desktop.                                                               |
| **C9**  | Auto-évaluation documentée  | **4**       | 5       | 20            | Tableau complet, analyse avant/après, justification détaillée.                                                        |
| **C10** | Confidentialité & consignes | **4**       | 5       | 20            | Aucune donnée personnelle, contact via GitHub uniquement.                                                             |
| **C11** | Qualité du dépôt            | **4**       | 5       | 20            | Arborescence propre, README clair, commits explicites.                                                                |
|         | **Total**                   |             | **100** | **360**       | —                                                                                                                     |

**Note finale : (360 / 400) × 20 = 18 / 20**

---

### 4. Observations globales

**Points forts :**

* Très bonne cohérence visuelle et responsive.
* Sémantique HTML exemplaire et SEO complet.
* Excellente maîtrise des outils (Bootstrap, CDN, Lighthouse, W3C).
* Confidentialité et professionnalisme respectés.

**Axes d’amélioration :**

* Ajouter éventuellement une page secondaire (ex. : portfolio détaillé ou version imprimable enrichie).
* Intégrer un badge PageSpeed/Outiref dynamique pour démontrer les performances.
* Améliorer encore le contraste des boutons “ghost” en violet clair sur écrans AMOLED.

---

### 5. Liste de contrôle finale ✅

* [x] Dépôt GitHub Pages public fonctionnel
* [x] Aucune erreur W3C
* [x] PageSpeed Desktop > 95, Mobile > 90
* [x] Meta description et title optimisés
* [x] Contraste conforme WCAG AA
* [x] Auto-évaluation documentée (présente)
* [x] Aucune donnée personnelle exposée
* [x] Contact via GitHub et LinkedIn uniquement

---

### 6. Conclusion

Ce projet m’a permis de consolider mes bases en **HTML sémantique, accessibilité et performance web**, tout en adoptant une **démarche itérative d’amélioration continue** (analyse V1 → corrections → version finale).
Le site final est propre, validé, rapide et professionnel, conforme aux standards demandés par le BTS SIO.
