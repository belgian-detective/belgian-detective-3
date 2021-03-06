# BDetective
BDetective est un jeu de société en ligne dans lequel les joueurs doivent découvrir l'identité de l'assassin le plus vite possible. Pour ce faire, ils disposent de certains indices, et lorsque c'est leur tour de jouer, ils peuvent émettre des hypothèses qui peuvent être infirmées ou non par d'autres joueurs, leur fournissant ainsi des indices supplémentaires.

## Technologies
BDetective utilise les technologies suivantes:
- TypeScript
- React (avec Vite)
- [PixiJS](https://pixijs.com/) et [ReactPixi](https://reactpixi.org/) (plus précisément la branche alpha compatible React 18 [@saitonakamura/react-pixi](https://www.npmjs.com/package/@saitonakamura/react-pixi)) pour la visualisation du plateau
- [XState](https://xstate.js.org/) pour le moteur du jeu
- [Zod](https://zod.dev/) pour la validation dynamique des données
- [Semantic UI React](https://github.com/Semantic-Org/Semantic-UI-React) pour l'interface

## Plan de développement
BDetective se veut facile à utiliser et disponible entièrement en ligne et sans création de compte ou de connexion à des services tiers, mais ces fonctionnalités seront disponibles pour une expérience encore plus confortable.
L'ensemble du projet BDetective est ambitieux, il est donc impératif d'établir des priorités sur les diverses fonctionnalités du projet pour permettre une efficacité et rapidité de développement optimale.

Ceci est le plan de développement actuel, il est susceptible d'évoluer dans le temps:
1.  Fournir un jeu rudimentaire mais fonctionnel
    - [ ] Moteur du jeu avec XState (inclus beaucoup de tests) [EN COURS]
    - [ ] Interface rudimentaire
    - [ ] Visualisation du plateau
    - [ ] Synchronisation côté serveur
2.  Ajouter options de personnalisation
    - [ ] Importer des plateaux personnalisés (personnages, pièces, ...)
    - [ ] Paramétrer les règles du jeu
    - [ ] Créer un compte / connexion avec Discord pour sauvegarder les préférences
    - [ ] Sauvegarder des "tables de jeu" incluant joueurs, plateau, configuration, ...

En parallèle, le projet BDetective Board Editor (bientôt sur GitHub) permettra de créer le plateau du jeu, et lors de l'étape 2 du plan de développement, permettra au grand public de créer des plateaux personnalisables.