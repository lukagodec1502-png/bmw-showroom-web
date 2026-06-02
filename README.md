# 🏁 BMW Motorsport Showroom - Galerie Interactive

Ce dépôt contient le code source d'un site web interactif dédié à l'histoire et à l'évolution de la gamme BMW Motorsport. Ce projet personnel a été réalisé pour mettre en pratique des concepts avancés d'intégration web et de dynamisme côté client via JavaScript, dans le cadre de mon apprentissage en BUT Informatique.

## 🎯 Description du Projet
L'objectif de ce projet était de créer une expérience utilisateur fluide et moderne sous forme de "Showroom" automobile. Le site présente plusieurs modèles emblématiques (de la 3.0 CSL historique à la récente M4 CSL)[cite: 12]. Il met l'accent sur l'interactivité avec des animations au défilement et des carrousels de présentation créés de A à Z sans aucune bibliothèque externe.

## 🛠️ Technologies Utilisées
* **Langages :** HTML5, CSS3, JavaScript (Vanilla)
* **Design :** CSS Flexbox, Animations `@keyframes`, Typographie Google Fonts (Montserrat)[cite: 11, 12]

## 🚀 Fonctionnalités Techniques Remarquables
* **Carrousels Dynamiques en JS :** Développement d'un système de sliders pour catégoriser les véhicules (Série M3, M5, Z, etc.)[cite: 12]. L'algorithme gère la boucle infinie des images (réinitialisation de l'index s'il dépasse les limites) et le nettoyage du DOM pour l'affichage conditionnel des classes `active`[cite: 12].
* **Scroll Reveal (Apparition au défilement) :** Utilisation de l'API moderne `IntersectionObserver` en JavaScript[cite: 12]. Ce script écoute le défilement de l'utilisateur et déclenche dynamiquement des animations CSS fluides (`transform: translateY(0)` et `opacity: 1`) lorsque les éléments entrent dans le champ de vision[cite: 11, 12].
* **Design "Dark Mode" Premium :** Création d'une interface élégante avec des tons sombres (`#131313`), une bannière d'en-tête (Hero Header) en image de fond fixe (`background-attachment: fixed`), et des boutons d'appel à l'action (CTA) interactifs[cite: 11].

## 🎓 Compétences BUT Validées (Preuves Portfolio)
Ce projet constitue une excellente trace technique et valide les compétences suivantes :

* **Compétence 1 - Réaliser (Développer des interfaces interactives) :** Structuration du document, mise en page esthétique avec CSS, et manipulation du DOM (Document Object Model) via JavaScript pour rendre le site vivant[cite: 11, 12].
* **Compétence 2 - Optimiser (Appréhender et construire des algorithmes) :** Implémentation d'une logique algorithmique robuste ("méthode bulletproof") pour la gestion des événements de clics sur les carrousels, garantissant qu'il n'y ait aucune erreur de dépassement d'indexation de tableau (Array)[cite: 12].

## 💻 Installation et Exécution
Le site est statique et exécuté directement par le navigateur.

1. Clonez ce dépôt sur votre machine locale :
```bash
   git clone [https://github.com/lukagodec1502-png/bmw-showroom.git](https://github.com/lukagodec1502-png/bmw-showroom.git)
