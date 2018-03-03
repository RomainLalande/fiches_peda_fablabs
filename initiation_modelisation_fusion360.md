# Initiation modélisation 3D - Fusion 360
## Objectifs
A travers la modélisation d'une table, les objectifs de cette séquence sont :
 - Connaître les étapes de la modélisation paramétrique (sketch, body, opérations, rendus )
 - Savoir réaliser des formes simples à l'aide de Fusion 360
 - Savoir explorer et trouver les fonctions utiles de Fusion 360 pour parvenir à un résultat souhaité en autonomie
 - Connaître le principe de fonctionnement des rendus

## Modalités d'organisation
**Taille du groupe :** 2 à 4 personnes par animateur

**Durée :** 3h

**Public :** Personnes souhaitant découvrir la modélisation 3D pour la premeière fois.

**Matériel nécessaire :**
 - Nécessaire de convivialité (café, grignottes),
 - Un ordinateur disposant de Fusion 360 par participants)
 - Un vidéo-projecteur

## Fusion 360
Fusion 360 est un logicel de modélisation 3D paramétrique développé par Autodesk. Il est gratuit pour des usages personnels ou éducatifs, mais payant pour des usages professionnels.

**Inconvénients :**
 - Uniquement windows 64 bit / MAC,
 - Logiciel non libre,
 - Gratuit pour le moment mais aucune garantie sur la durée,
 - Nécessite la création d'un compte.

**Avantages :** 
 - Bonne ergonomie pour découvrir les principes de base de la modélisation paramétrique
 - Bonne communauté d'utilisateurs (nombreuses réponses aux questions sur internet)
 - Adapté à la fabrication numérique (dispose d'une focntion dédié au fraisage)


## Pré-requis
**Participants :** 
 - être très à l'aise avec l'utilisation d'un ordinateur
 - Créer un compte autodesk sur autodek.com
 
**Animateurs :** Avoir réalisé le modèle, savoir utiliser les fonctions de base de Fusion 360.

## Préparation 
**Avant la séquence :** 
 - D'avoir réalisé le modèle avant, 
 - D'installer fusion 360 sur les postes
 - Avoir créé un compte Autodesk commun pour les participants

## 15 mn - Accueil café
 - Accueil des participants
 - Tour des prénoms et des attentes des participants

## 15 mn - Connexion
 - Chacun se connecte à son compte (un compte générique dispo si pas encore fait)
 - Chacun enregistre son projet avec son prénom.

## 10 mn - Prise en main

Expliquer le principe de comment on va fonctionner : 
 - La séquence commencera par une heure "d'informations déscendantes"
 - Elle se poursuivra par deux heures d'explorations libres avec le support des animateurs

**Tour du propriétaire : **  [Martin]
 - on survole les différents ateliers (Model, patch, ...).
 - Pour chaque fonction on a un atelier différent
 - Nous allons voir l'atelier model et render
 - Mais on pourrait aussi simuler des contraintes et paramétrer le code pour fraisage
 - Expliquer la chaine de modélisation autour de la création d'une pyramide (empilement de trois rectangles extrudés): le principe on part du 2D pour aller vers la 3D
 - Expliquer le principe du navigateur (barre de navigation)


**Démonstration 1 (les participants sont spectateurs) :** [Martin] 
 - les sketch géométriques (cercle, rectangle)
 - Le choix du plan
 - L'outil "dimension"
 - extrusion des formes géométriques
 - déplacment des formes à la main
 - déplacement de la vue caméra
 - Le résultat final de la table qu'on va réaliser.

**Consigne 1 (les participants répondent à la consigne):** [Martin] 
 - "Créez une table avec les fonctions présentées et respectant les dimensions données"
 - Dessiner le schéma de la table au tableau : 
  - quatre pieds carrés : 100 cm de haut, 10x10cm
  - un plateau rectangulaire : 5cm d'épaisseur, 
  - Table rectangulaire de 150cm x 90cm . Pieds de 100 de haut.  

**Démonstration 2 (les participants sont spectateurs) :**[Romain]
 - Montrer le déplacement point to point
 - Montrer le déplacement point to point avec copie
 - La ligne de vie du projet (modifier l'extrusion pour le quatre pieds - edite feature)

**Consigne 2 (les participants répondent à la consigne):**[Romain]
 - "Reproduire les quatre pieds par déplacement copie, puis modifier la taille des quatre en un coup"


**Démonstration 3 (les participants sont spectateurs) :**[Romain + Martin] 
 - Romain - Donner les limites de la méthode précédente : 
  - le sketch du pied est toujours à son emplacement d'origine, 
  - on doit doit bouger chaque pied un par un, 
  - impossible avec des pieds ronds car pas de point to point possible -> Cette méthode ne fonctionne pas toujours
 - Martin - Présentation d'une méthode simple pour des pieds ronds. Démonstration des contraintes de distance avec les cotes d'éloignement des pieds par rapport au bord, pour qu'à la modification du plateau chaque pied reste bien placé proportionnellement
 	- La méthode 1 : ajouter une contrainte pied par pied à 15 cm des bords
    - La méthode 2 : faire un rectangle en traits de construction avec Offset et en créant les ronds à ses angles.
 
**Consigne 3 (les participants répondent à la consigne):**
 - "Créer une table avec des pieds ronds en utilisant les contraintes pour mettre automatiquemnt les pieds à 15 cm du bord.

**Démonstration 4 (les participants sont spectateurs) :**[Martin] Montrer : 
 - Survoler les option de la section "modify" pour rendre notre modèle plus joli

**Consigne 4 (les participants répondent à la consigne):** [Martin]
 - "Amusez-vous à rendre votre table la plus belle possible" 

**Démonstration 5 (les participants sont spectateurs) :**

Il s'agit de montrer une troisième méthode de création possible pour parvenir à ce résultat et de prouver que l'on peut faire de mille façons, à chacun de chosir sa stratégie en fonction de l'objet souhaité et de la manière dont on aime réfléchir.
 - Faire une boite
 - Dessiner les pieds avcec des lignes (dans le sketch)
 - Extruder vers l'intérieur (avec cut)


# PAUSE 



# Temps créatif :
On donne une consigne large et simple pour que chacun imagine sa propre stratégie de modéliation sur une forme simple : 
 - Imaginez votre pot à crayon qui doit tenir sur une table et pouvoir recevoir des crayons

Invitez ceux qui le souhaitent à réaliser l'objet de leur choix.

Si certains ont besoin d'être plus guidés, on leur donne des cotes précises autour de la création d'un dé.

Durant ce temps libre, refocaliser l'attention du groupe à travers trois moments de démonstration d'une dizaine de minutes autour : 
 - [Romain] Fonction "Combine > cut" : creuser un tiroir dans la table
 - [Martin] Fonction "Revolve + shell" : on crée une bouteille vide sur la table
 - [Martin] Montrer les rendus bois et les exports en stl et dxf

