# TP_re-experimentation
Subject: Alfred - Majordome de Batman

# Use Case
Use case : Chaque cas d'utilisation renvoie à une fonctionnalités que doit 
proposer le système. Toutes ces indications sont déstinées au seul acteur du système : Alfred le Majordome.
les cas d'utilisation définis dans ce modèle sont :
	- Régler le chauffage
	- Garder une bonne qualité de l'air
	- Savoir si sa voiture est chargée
	- Connaître le ratio production/consommation
	- Connaître la quantité d'eau chaude
	- Installer une nouvelle source de production électrique

![Alt text](Screen/UseCase.PNG?raw=true "Use case")

# Block Definition Diagram
6 blocks différents :
	- Analyse
	- Traitement
	- Module électronique 
	- Alfred
	- Capteurs
	- Affichage
D'après ce diagramme, le module electronique est composé d'un block d'analyse et de traitement destiné au traitement et à l'analyse des données
récoltées par les capteurs. Alfred est composé de ce module électronique, de capteurs et d'un écran. Les capteurs récupérent les données 
qui seront affichées sur l'écran

![Alt text](Screen/BDD.PNG?raw=true "Use case")
