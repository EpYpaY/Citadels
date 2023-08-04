<h1 align="center">
  <img src="https://github.com/LysnakeIT/Citadelles/blob/main/Images/Logo_Citadelles.png" alt="Citadelles" width="200"></a>
</h1>

# Projet de développement : Citadelle

Bienvenue dans le README du projet de développement de Citadelle ! Dans ce document, vous trouverez des informations sur l'équipe, le sujet, l'architecture du projet et comment lancer le jeu.

## L'équipe

Nous sommes fiers de présenter notre Dream Team, composée des membres suivants :

- Alexis COMMEAT
- Lilian DAMIEN
- Léo CORVE
- Mathieu LE TORREC

## L'objectif

Notre objectif est de rendre le jeu de plateau Citadelle sous forme électronique. Pour atteindre cet objectif, nous avons développé le jeu Citadelle en Java. Nous disposons d'une version en mode console ainsi que d'une extension graphique.

## Architecture du projet

Voici la structure de notre projet, avec les différents dossiers :
```yaml
Code :
    - build :
        - class : Les fichiers compilés en .class 
        - doc : La JavaDoc du projet (à ouvrir avec un navigateur)
        - jar : L'exécutable du jeu (à lancer pour jouer)
    - data :
        - cartes : Images des différentes cartes du jeu (personnages, quartiers)
        - assets : Images utilisées pour la version graphique du jeu
    - src :
        - application : Contient les fichiers nécessaires au lancement du jeu, ainsi que les fichiers de configuration et de    déroulement du jeu 
        - contrôleur : Contient les fichiers de contrôle du jeu 
        - modèle : Contient les fichiers de modélisation du jeu
        - test : Contient les fichiers de test du jeu
        - vue : Contient les fichiers de vue du jeu (version graphique)

Images :
    Contient notre logo du jeu Citadelle, ainsi que les différents graphiques

Rendus :
    Contient l'ensemble des rendus du projets
  ```


## Lancement du jeu

1. Téléchargez le dossier depuis GitHub.
2. **Ensuite placez-vous dans le dossier : Code.**
3. En ligne de commande :
   - Exécutez la commande `java -jar ./build/jar/application/Application.jar`.
4. Sur Visual Studio Code :
   - Lancez l'exécution

Après la compilation, vous aurez le choix de jouer en mode console ou en mode graphique. Les instructions détaillées seront fournies dans le manuel utilisateur.

Nous espérons que vous apprécierez notre projet de développement de Citadelle !
