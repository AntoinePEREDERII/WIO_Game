# Projet "Rool on Coins" pour WIO Terminal

Bienvenue dans le passionnant univers de "Rool on Coins", un jeu captivant conçu pour la carte WIO Terminal. Dans ce projet, nous nous sommes lancés dans le développement d'un jeu ludique qui exploite l'accéléromètre de la WIO Terminal pour une expérience de jeu immersive.

# Table of Content
[Introdution](#introduction) |  [UI](#interface-utilisateur) | [Mécanique de jeu](#mécaniques-de-jeu) | [Stratégie et Défi](#stratégie-et-défi) | [Objectifs du Projet](#objectifs-du-projet) | [Contributeurs](#contributeurs)  

## Introduction

"Rool on Coins" met en scène une boule rouge de 14 pixels de diamètre, que vous allez contrôler en inclinant la carte pour ramasser des pièces jaunes éparpillées sur l'écran. L'objectif est de collecter autant de pièces que possible dans un délai de 30 secondes, tout en évitant de sortir de la zone de jeu. 

### Niveaux de Difficulté

Pour pimenter les choses, le jeu propose trois niveaux de difficulté :
- **Novice**: 5 pièces faciles d'accès.
- **Confirmé**: 5 pièces, certaines situées sur les bords et une dans un coin.
- **Expert**: Le même défi que le niveau "Confirmé", mais avec des pièces noires qui font perdre 10 secondes au chrono si vous les touchez.

## Interface Utilisateur

L'interface utilisateur du jeu est soignée et intuitive. En haut, un bandeau bleu de 40 pixels de large affiche le niveau actuel. Au milieu de ce bandeau, vous pouvez voir votre score en cours. Le chrono est situé à droite du bandeau bleu pour que vous gardiez un œil sur le temps restant pour collecter les pièces.

## Mécaniques de Jeu

Au début du jeu, un court délai est suivi d'un signal sonore pour vous permettre de vous préparer à l'inclinaison de la carte. Dès que le jeu commence, le chrono démarre et s'affiche à l'écran. Les pièces jaunes et noires sont disposées dans la zone de jeu, ce qui vous permet de visualiser le défi qui vous attend.

Pendant la phase active du jeu, les boutons ne sont pas accessibles, et vous devez vous concentrer sur le déplacement de la boule rouge. Lorsque la boule touche une pièce jaune, elle émet un bip joyeux et vous rapporte 10 points. Dans le niveau expert, si la boule touche une pièce noire, vous perdez 10 secondes de votre temps de jeu, accompagné d'un son grave.

## Stratégie et Défi

Une stratégie intéressante consiste à utiliser le troisième bouton (le plus à droite) pour ajouter 10 secondes au chrono une seule fois par partie de 30 secondes. Cependant, cela divise la valeur des pièces jaunes restantes par 2, ce qui signifie qu'elles ne valent plus que 5 points. De plus, il n'y a plus d'ajout du temps au score si vous parvenez à collecter toutes les pièces jaunes grâce à ce délai supplémentaire.

## Objectifs du Projet

Lors de la réalisation de ce projet, nous avons mis l'accent sur plusieurs aspects clés :

- Créer une expérience réaliste de déplacement de la boule virtuelle sur un écran statique.
- Mettre en œuvre une détection de collision de haute qualité.
- Assurer une fluidité d'affichage optimale.
- Produire un code de qualité, facile à modifier pour permettre des ajustements rapides (par exemple, la taille du bandeau, la couleur de fond, le nombre de pièces, etc.).

## Contributeurs
* [Antoine PEREDERII](https://github.com/AntoinePEREDERII)
* [Vianney JOURDY](https://codefirst.iut.uca.fr/u/vianney.jourdy)