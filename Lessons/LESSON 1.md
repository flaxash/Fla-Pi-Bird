#leçon 1

##Introduction

Dans cette leçon, les étudiants vont importer les graphiques requis pour le jeu. Les prérequis pour cette leçon sont de connaître scratch et de savoir comment sélectionner du code, créer des variables, et de comprendre comment fonctionnent les messages à tous. Si ce n'est pas le cas, alors vous devriez ajouter d'autres leçons pour découvrir ces notions.

##Objectifs d'apprentissage

L'objectif de cette leçon est d'importer les graphiques dans le jeu et de comprendre que les sprites dans Scratch peuvent avoir différents costumes pour changer d'apparence.

##Acquis en fin de leçon

Tous les étudiants sont capables d'importer des graphiques dans Scratch et sont prêts à coder le jeu

##Résumé de la leçon
The leçon will begin with a small discussion on copyright and plagiarism to ensure students understand the importance of crediting original sources when using it for their own purposes. Students will then begin to code a game in Scratch. The code illustrated in this leçon will allow students to successfully get sprites moving on the screen in the direction they need them to in order to fulfil the game.
La leçon commence avec une discussion sur le copyright et le plagiat pour s'assurer que les étudiants comprennent bien l'importance de référencer ses sources lorsqu'on les utilise pour ses propres créations. Les étudiants vont alors commencer à coder le jeu dans Scratch. Le code illustré dans cette leçon va permettre aux étudiants de faire bouger les sprites à l'écran dans la direction souhaitée.

##Début
Placer le mot Copyright sur le tableau pour provoquer une discussion à propos du copyright et de ses implications. On pourra alors expliquer que cloner des jeux est devenu une pratique courante due aux lois complexes protégeant les logiciels. Voir dans l'appstore le nombre de copies des jeux qui marchent. Nous allons également cloner un jeu célèbre, mais les étudiants doivent être conscients des lois autour du copyright et des conséquences de plagier le travail d'un autre et le faire passer pour le sien. Le jeu original Flappy Bird a été ecris par Dong Nguyen et les crédits doivent lui revenir pour avoir fourni l'inspiration et la motivation de créer un clone de son jeu pour apprendre aux élèves la programmation.

##Développement principal
*Les étudiants commencent par ouvrir Scratch et suppriumer le chat en faisant un click-droit dessus et en sélectionnant 'supprimer'.

*Ils vont alors choisir un nouveau sprite et importer les costumes pour l'oiseau Fla-pi. Les voici :


* voici comment importer les graphiques :
![Imprt Graphic](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Screenshots/Import%20Graphic%20Screen%20Shot.fw.png?raw=true)  
  
![Flap-Pi Bird Costume 1](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Graphics/Flappy.fw.png?raw=true)  
  
![Fla-Pi Bird Costume 2](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Graphics/Flappy2.fw.png?raw=true)  

* Les étudiants vont alors importer 3 costumes différents pour l'objet stage de la même manière :  

![Game Intro Screen](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Graphics/Intro.png?raw=true)  
![Ready Screen](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Graphics/Ready.fw.png?raw=true)  
![Game Background](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Graphics/Background.png?raw=true)  

 
* Ensuite, les graphiques pour les tuyaux doivent être importés, il y en a 9. Soyez sûr que les étudiants ont bien importé tous ces costumes pour le tuyau.

![Pipe 1](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Graphics/Pipes/Pipe1.png?raw=true) Pipe 1  
![Pipe 2](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Graphics/Pipes/Pipe2.png?raw=true) Pipe 2  
![Pipe 3](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Graphics/Pipes/Pipe3.png?raw=true) Pipe 3  
![Pipe 4](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Graphics/Pipes/Pipe4.png?raw=true) Pipe 4  
![Pipe 5](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Graphics/Pipes/Pipe5.png?raw=true) Pipe 5  
![Pipe 6](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Graphics/Pipes/Pipe6.png?raw=true) Pipe 6  
![Pipe 7](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Graphics/Pipes/Pipe7.png?raw=true) Pipe 7  
![Pipe 8](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Graphics/Pipes/Pipe8.png?raw=true) Pipe 8  
![Pipe 9](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Graphics/Pipes/Pipe9.png?raw=true) Pipe 9  

* Enfin, le graphique du 'Game Over' va être importé à son tour
![Game Over](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Graphics/GameOver.fw.png?raw=true)  

* Ok, maintenant que les graphiques sont en place, nous allons ajouter le code aux éléments afin qu'ils soient visibles au bon moment dans le jeu. A ce stade, l'oiseau et les tuyaux ne demandent pas de code, nous allons d'abord nous occuper du sprite 'Game Over', sélectionnez-le tout d'abord :
![Game over code](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Code%20Blocks%20by%20leçon/1%20Graphics/Game%20Over%20Code.JPG?raw=true)  

Le code ci-dessus cache l'objet 'Game Over' quand le jeu commence. CE graphique sera utilisé plus tard et est affiché lorsque le jeu est fini.

*Le code pour l'objet 'stage' (fond) doit maintenant être ajouté. Ici, le code remplace l'écran du fond lorsque le jeu démarre. Le jeu attend alors que la barre d'espacement soit pressée pour commencer, 1 seconde plus tard, et envoyer un message appelé start. Ensuite le fond est remplacé par le visuel servant de décor au jeu. Cela conclue cette leçon.
![Stage code](https://github.com/AllenHeard/Fla-Pi-Bird/blob/master/Code%20Blocks%20by%20leçon/1%20Graphics/Stage%20Code.JPG?raw=true)  
* Students should save the file as Graphics.sb 
* Les étudiants devraient suvegarder leur travail maintenant

##Synthèse en plénière
  Les étudiants devraient être conscient de l'importance de la responsabilité éthique lorsqu'ils écrivent des logiciels pour éviter des conséquences possibles.
 
