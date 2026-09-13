# Composant QR code

Une carte QR code simple et élégante réalisée dans le cadre d'un défi [Frontend Mentor](https://www.frontendmentor.io/).

L'objectif de ce projet était de reproduire une interface claire et centrée, tout en conservant une expérience agréable sur les petits comme sur les grands écrans.

## Aperçu

La page présente :

- un QR code permettant d'accéder à Frontend Mentor ;
- un titre qui invite à développer ses compétences front-end ;
- un court texte explicatif ;
- une mise en page responsive adaptée aux écrans de 360 px à 1440 px.

## Technologies utilisées

- HTML5 sémantique ;
- CSS3 ;
- Flexbox ;
- unités relatives et fonction `clamp()` pour une typographie fluide ;
- police [Outfit](https://fonts.google.com/specimen/Outfit) proposée par Google Fonts.

## Structure du projet

```text
DEFIS_2/
├── index.html
├── style.css
├── README.md
└── images/
	├── favicon-32x32.png
	└── image-qr-code.png
```

## Mise en page

Le fond bleu clair met en valeur la carte blanche contenant le QR code. La carte possède des angles arrondis, un espacement régulier et un texte centré pour rester fidèle au design du défi.

Les tailles de texte évoluent progressivement avec la largeur de l'écran grâce à `clamp()`. Elles restent ainsi lisibles sur mobile et équilibrées sur ordinateur, sans agrandir excessivement le contenu sur les très grands écrans.

## Utilisation

1. Ouvrir le dossier du projet dans Visual Studio Code.
2. Ouvrir le fichier `index.html` dans un navigateur.
3. Pour une meilleure expérience de développement, lancer la page avec une extension comme **Live Server**.

## Ce que j'ai appris

Pendant la réalisation de ce projet, j'ai appris à utiliser `:root` en CSS pour centraliser des variables réutilisables, notamment les tailles de texte. Cela permet de mieux organiser le code et de modifier plus facilement les valeurs principales du projet.

J'ai également utilisé la fonction `clamp()` afin de créer une typographie fluide. Les textes peuvent ainsi rétrécir ou s'agrandir progressivement en fonction de la taille de l'écran, tout en respectant une taille minimale et une taille maximale.

## Ressources utiles

Pour comprendre les différentes notions utilisées dans ce projet, je me suis appuyé sur les ressources suivantes :

- [MDN Web Docs en français](https://developer.mozilla.org/fr/) ;
- [W3Schools](https://www.w3schools.com/).

## Collaboration avec l'IA

J'ai utilisé l'IA de Google pour m'expliquer certains éléments que je ne comprenais pas complètement pendant mes recherches sur Internet, notamment l'utilisation de `:root` et des variables CSS.

## Auteur

Projet réalisé par **Mr. BILLY Jarod**, apprenti développeur autodidacte.

Défi proposé par [Frontend Mentor](https://www.frontendmentor.io/).
