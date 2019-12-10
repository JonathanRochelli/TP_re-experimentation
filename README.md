# TP_re-experimentation
Subject: Alfred - Majordome de Batman

Fichier contenant les user stories nous guidant pour la réalisation des diagrammes : [User Stories](https://github.com/JonathanRochelli/TP_re-experimentation/blob/master/UserStories_MENDEZ_GRILLOT_MASTERICE.xlsx)

# Requirements Diagram
Requirements Diagram : Ce diagramme présente les différentes exigences du système. La principale exigence du système est de gérer la maison. Cette exigence est, ensuite, découpée en plusieurs sous-parties, chacune chargées d'un domaine (eau, éléctricité,...)
Quelques exemples d'exigences sont :
* Gérer l'eau chaude
* Gérer la consommation électrique
* Gérer la température de la pièce

![Alt text](experimentation/RequirementDiagram.PNG?raw=true "Use case")

# Use Case
Use case : Chaque cas d'utilisation renvoie à une fonctionnalités que doit 
proposer le système. Toutes ces indications sont déstinées à l'utilisateur. Il peut récupérer toutes les informations liées à la gestion de la maison.
les cas d'utilisation définis dans ce modèle sont :
* Régler le chauffage
* Garder une bonne qualité de l'air
* Savoir si sa voiture est chargée
* Connaître le ratio production/consommation
* Connaître la quantité d'eau chaude

![Alt text](experimentation/UseCase.PNG?raw=true "Use case")

# Block Definition Diagram
Block Definition Diagram : Ce diagramme représente les principaux composants utilent dans le système. 6 blocks différents présents dans le diagramme :
* Analyse
* Traitement
* Module électronique 
* Alfred
* Capteurs
* Affichage

D'après ce diagramme, le module electronique est composé d'un block d'analyse et de traitement destiné au traitement et à l'analyse des données
récoltées par les capteurs. Alfred est composé de ce module électronique, de capteurs et d'un écran. Les capteurs récupérent les données 
qui seront affichées sur l'écran

![Alt text](experimentation/BlockDefinitionDiagram.PNG?raw=true "BDD")

# Internal Block Diagram
Internal Block Diagram : Détail du block Alfred du Block Definition Diagram. Ce diagramme contient le en entrée (in) les 6 capteurs nécessaires à l'obtention des données.
Toutes les informations des capteurs vont dans le block analyse puis traitement. Ces deux phases permettent le traitement et la génération du graphique propre au type de données demandées.
Les informations traitées sont ensuite afffichées à l'écran (out).

![Alt text](experimentation/InternalBlockDiagram.PNG?raw=true "IBD")

# Sequence Diagram
Sequence Diagram : Diagramme de séquence de l'affichage du graphique de la consommation d'eau. Il représente le processus d'affichage du graphique de la consommation d'eau. Ce processus est initié par l'utilisateur. Ce diagramme fait intervenir 4 acteurs :
* L'utilisateur
* L'écran
* Alfred
* Les capteurs

![Alt text](experimentation/SequenceDiagram.PNG?raw=true "IBD")
