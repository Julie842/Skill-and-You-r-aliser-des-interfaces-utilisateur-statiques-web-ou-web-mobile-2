# Skill-and-You-r-aliser-des-interfaces-utilisateur-statiques-web-ou-web-mobile-2

Atelier : mettre en forme les images sur les animaux sauvages

Ce projet est une page web statique simple et interactive réalisée en HTML5 et CSS3. Elle présente une galerie de quatre animaux sauvages accompagnés de descriptions qui se révèlent dynamiquement au survol de la souris.

Fonctionnalités

Mise en page en grille horizontale : Utilisation de display: inline-block et de la fonction CSS calc() pour aligner proprement les quatre fiches d'animaux dans un conteneur <figure>.

Effets interactifs au survol (:hover) :

Mise en avant de la carte survolée en faisant passer son opacité de 0.5 à 1.

Apparition d'une bordure colorée et d'une ombre portée (box-shadow).

Révélation fluide de la description textuelle de l'animal (initialement masquée via visibility: hidden).

Sémantique HTML : Utilisation des balises sémantiques <figure> et <figcaption> pour structurer la galerie.

Structure du projet

Pour que l'affichage des images fonctionne correctement, le projet doit respecter l'arborescence suivante :

projet-animaux/
│
├── index.html          # Page principale contenant le code HTML et le CSS intégré
├── README.md           # Documentation du projet
└── images/             # Dossier contenant les ressources graphiques
    ├── singe.jpg
    ├── girafe.jpg
    ├── éléphant.jpg
    └── lion.jpg
