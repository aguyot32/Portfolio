# Portfolio Personnel - Antoine GUYOT

Bienvenue sur le dépôt de mon portfolio ! Ce site vitrine a été conçu et développé de A à Z pour présenter mes compétences, mes projets (académiques et personnels) ainsi que mon parcours en tant que futur professionnel du développement informatique.

**[Voir le portfolio en ligne](https://aguyot32.alwaysdata.net/portfolio/)**

---

## Fonctionnalités

Ce projet a été l'occasion de mettre en place des solutions techniques modernes et optimisées, sans utiliser de bibliothèques externes lourdes :

* **Mode Sombre / Clair :** Thème personnalisable par l'utilisateur avec sauvegarde automatique dans le `localStorage` du navigateur. Le site se souvient de vos préférences d'une page à l'autre.
* **Système Multilingue (FR / EN) :** Changement de langue instantané. Le mécanisme est géré **en CSS**, ce qui permet une traduction immédiate sans aucun rechargement de page ni script complexe. Le choix est également mémorisé via `localStorage`.
* **Design Responsive :** Utilisation intensive de CSS Grid et Flexbox pour garantir un bon affichage sur ordinateur, tablette et smartphone.
* **UI/UX Moderne :** Effets de *Glassmorphism* (flou en arrière-plan), formes géométriques flottantes animées, et micro-interactions sur les boutons et les cartes de projets.
* **Presse-papier natif :** Bouton permettant de copier mon pseudo Discord en un clic, utilisant l'API `navigator.clipboard` avec un système de secours (fallback) pour les environnements non-HTTPS.
* **Formulaire de contact fonctionnel :** Intégration de l'API *Formspree* pour la réception directe des messages sans nécessiter de backend lourd.

---

## Stack Technique

* **Langages :** HTML5, CSS3, Vanilla JavaScript
* **Architecture :** Site statique multipage
* **Hébergement :** alwaysdata

---

## Structure du projet

```text
portfolio/
├── index.html
├── contact.html
└── mentions-legales.html