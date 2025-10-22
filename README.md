# CV Web – page HTML statique

Un CV en ligne simple, lisible et responsive, publié avec GitHub Pages.  
Projet réalisé dans le cadre du BTS SIO option SISR.

---

## Objectifs du projet

- Publier un site statique avec GitHub Pages.  
- Structurer un document HTML sémantique (balises header, main, section, footer).  
- Mettre en page responsive (Bootstrap 5).  
- Appliquer des bases d’UX, d’accessibilité et de SEO.  
- Améliorer les performances (optimisation des ressources et chargement différé).  
- Utiliser les validateurs (W3C, Outiref, PageSpeed) et corriger les problèmes détectés.

---

## Confidentialité

Aucune donnée personnelle sensible n’est publiée :  
- Pas de numéro de téléphone  
- Pas d’adresse postale  
- Pas d’e-mail personnel  

Contact via :  
- Profil GitHub : [https://github.com/Trbarry](https://github.com/Trbarry)  
- Profil LinkedIn : [https://www.linkedin.com/in/tristan-barry-43b91b330](https://www.linkedin.com/in/tristan-barry-43b91b330)

---

## Liens du projet

- Dépôt GitHub : [https://github.com/Trbarry/page_cv](https://github.com/Trbarry/page_cv)  
- Site en ligne : [https://trbarry.github.io/page_cv/](https://trbarry.github.io/page_cv/)

---

## Stack technique

- HTML5  
- CSS3 / Bootstrap 5.3.3  
- Bootstrap Icons (polices vectorielles légères)  
- Responsive mobile-first  
- Publication via GitHub Pages

---

## Validation et performances

| Test | Résultat | Outil |
|------|-----------|-------|
| **W3C Validator** | 0 erreur, 0 warning | [validator.w3.org](https://validator.w3.org/) |
| **Outiref** | H1 unique, structure claire et hiérarchisée | [outiref.com](https://www.outiref.com/) |
| **PageSpeed (mobile)** | Performance : 84 / 100 | [pagespeed.web.dev](https://pagespeed.web.dev/) |
| **PageSpeed (desktop)** | Performance : 76 / 100 | |
| **Accessibilité** | 95 / 100 | Lighthouse |
| **Bonnes pratiques** | 100 / 100 | Lighthouse |
| **SEO** | 100 / 100 | Lighthouse |

---

## Auto-évaluation

### Version initiale (V1)
- Meta description trop courte.  
- Liens GitHub/LinkedIn collés visuellement.  
- Aucun preload ou defer pour le CSS/JS.  
- Absence de gestion du `font-display: swap`.  

### Version finale
- Meta description enrichie à 220 caractères.  
- Séparation visuelle entre les liens de contact.  
- Préchargement (`preconnect`, `preload`) ajouté pour le CSS.  
- Scripts chargés avec `defer` pour de meilleures performances.  
- Amélioration de l’accessibilité (contraste, structure Hn, focus clavier).  
- Ajout des données structurées JSON-LD pour le SEO.  

---

## Évaluation simulée

| Critère | Note /4 | Commentaire |
|----------|----------|-------------|
| Contenu du CV | 3.5 | Clair, concis et pertinent |
| HTML sémantique | 4 | Structure complète et hiérarchisée |
| Responsive | 4 | Parfaitement lisible sur mobile et desktop |
| UX & Accessibilité | 3.5 | Navigation fluide, contraste bon |
| SEO | 4 | Balises optimisées et structurées |
| Performance | 3.5 | Légère marge d’amélioration sur images |
| Validation & corrections | 4 | Toutes les erreurs corrigées |
| Publication Pages | 4 | Déploiement stable et opérationnel |
| Auto-évaluation | 3.5 | Analyse claire entre V1 et finale |
| Confidentialité | 4 | Conforme aux consignes |
| Qualité du dépôt | 4 | README structuré et clair |

**Note finale estimée : 18,4 / 20**

---

## Ressources utilisées

- [W3C Validator](https://validator.w3.org/)  
- [Outiref](https://www.outiref.fr/)  
- [PageSpeed Insights](https://pagespeed.web.dev/?hl=fr)  
- [GTmetrix](https://gtmetrix.com/)  
- Documentation Bootstrap 5.3.3  

---

## Crédits

Projet réalisé par **Tristan Barry**  
BTS SIO – Option SISR – Année 2025  

