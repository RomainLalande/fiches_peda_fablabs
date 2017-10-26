# Arduino - initiation ados
**Fiche placée sous licence CC by SA**

**Contributeurs -** Grégoire Simonnet, Julien Rat, Romain Lalande

**Test de la séquence :** FunLab - FabLab de Tours

[TOC]
## Objectifs de la séquence
- Connaître focntionnement de base d’un arduino et de ses composants principaux
- Savoir être autonome dans l'apprentissage de l’Arduino
- Avoir la capacité et l’envie de poursuivre en auto-apprentissage accompagné l’arduino aus ein du FabLab.

![photo_atelier](http://wiki.funlab.fr/images/thumb/c/c1/Ados_arduino_3.jpg/800px-Ados_arduino_3.jpg)

## Pré-requis
- **Participants :** avoir de 10 à 16 ans, savoir et prendre du plaisir à utiliser internet et un ordinateur.
- **Animateurs :** savoir utiliser les fonctions et composants de base d’un arduino. Le mieux est d'être deux pour un groupe de huit, dont une personne qui peut ne rien y connaître mais être ressource pour accompagner les binomes.


## Matériel
Pour huit participants : 
- Un lieu permettant d'avoir de l'espace, comme un grand ilot central de tables qui permette de circuler autour, un espace pour bricoler, découper et un espace pour tenir tous debout ! 
- 4 ordinateurs
- 4 « starter kit » arduino
- 1 vidéo- projecteur
- Cartons et matériaux de récupération
- Matériel de petit bricolage : ciseaux, cutter, colle chaude, petits boulons,...

## Préparation de la séquence
![Installation](https://pbs.twimg.com/media/DLjO6UWUIAEwslf.jpg)

1. **Installer Arduino IDE sur les ordinateurs** - Prévoir un ordinateur pour deux participants) [lien de téléchargement](https://www.arduino.cc/en/Main/Software#) 
2. **Téleverser Firmata sur chaque Arduino** - Cela vous  permettra de faire fonctionner l’arduino via le logiciel Snap4Arduino. *Prévoir un Arduino pour deux participants : Lancez arduino IDE, connectez l’arduino à l'ordinateur, sélectionnez le fichier exemple Firmata (Fichier>Exemples>Firmata>StandardFirmata) puis téléversez le dans l’arduino.* 
**/!\ En cas de problème de téléversement** - Vérifiez que vous êtes sur le bon port série (Outils>Port Série>...) et que vous avez bien sélectionné la bonne carte Arduino (Outils>Type de carte>...).
3. **Installer Snap4Arduino** - Téléchargez le logiciel [sur le site officiel](http://snap4arduino.rocks/), installez-le puis lancez-le. Testez la connection à votre Arduino, dans la patie contenant les blocs Arduinos (bouton "connexion"). /!\ **Ne vous trompez pas de port série**, sinon il est possible qu'il faille relancer le logiciel...



## Déroulé
### Lancement de la séquence
**15mn** - debout en cercle
 - **Présentation(s) :** l’intervenant.e.s se présente.nt (prénom, rôle, compétences techniques)
 - **Photo-langage :** une animation pour symboliser l’arrivée dans le groupe, permettre à chacun de ++partager l’état d’esprit dans lequel il arrive++ et de se présenter par un biais détourné. 
 **Exemple :** Disposez des images sur la table (un jeu de dixit par exemple) et demander aux participants d’en choisir une qui correspond à son état d’esprit du moment (peut être demandé pendant que les participants attendent le démmarage). Lorsque tout le monde a sa carte, s’installer debout en cercle et demander à chacun de donner son prénom et pourquoi il a choisis cette carte.
 [Découvrir d'autres formats d'ouverture](http://osons.cc/wakka.php?wiki=PageAnimation&facette=checkboxListeUsageAnim=8)
 - **Déroulé de l’atelier :** proposer au groupe le déroulé imaginé pour la séquence, et les objectifs poursuivis. S’assurer que cela ne crée pas d’objection franche ou de frustration, adapter à la marge le programme pour lever ces objections si elles existent.
 - **Point logistique :** expliquer les règles minimales de sécurité, de condition d’usage des locaux et du matériel, indiquer les toilettes.
 - **Définir vos règles :** demander au groupe les règles nécessaires pour que la session se passe bien, en particulier dans les relations entre les personnes. Valider collectivement ces quelques règles simples.
![Dixit utilisé pour le photolanguage](http://wiki.funlab.fr/images/thumb/4/41/20171024_123208.jpg/800px-20171024_123208.jpg)

### Déballage et bases théoriques

**20 mn** - debout autour des tables et des ordinateurs

**Découverte du matériel :** Déballez l'arduino et les différents capteurs sur la table. Demander aux participants s'ils connaissent la focntion des éléments déballés et en expliquer la fonction si nécessaire.
Ce moment doit servir à expliciter le fonctionnement de base de l'arduino : des capteurs en entrée, et des sorties qui réagissent en fonction de conditions données dans le code. Donner un exemple simple du type "si le capteur à ultrason me détecte à moins de 50cm, alors le buzzer sonne".
![deballage](http://wiki.funlab.fr/images/thumb/d/de/Atelier_ados_deballe.jpg/337px-Atelier_ados_deballe.jpg)

**Exemples de projets arduino** (montrer le fonctionnement en conditions réelles à travers deux exemples de projets simples) : 
 - Exemple 1 – Robotique | [le Mirobot](https://www.youtube.com/watch?v=8NscDzlTb9U) 
 - Exemple 2 – Domotique | [le vélo espace](http://wiki.funlab.fr/index.php/V%C3%A9lo_Espace)

**Les bases de l'électronique**
En partant de la question "sauriez-vous expliquer comment allumer une LED ? Que se passe t-il lorsque la LED s'allume ?" : 
- Laissez les participants répondre
- Laissez les participants expérimenterleur réponse avec le matériel à disposition
- Effectuer un rappel théorique pour valider la réponse : le sens du courant, l'utilité de la résistance, le risque couru par la LED en cas d'erreur. (l'objectif n'est pas d'aborder trop techniquement le sujet, mais une simple compréhension du principe)



### Découverte de l'Arduino

**5mn** - En binome sur l'ordinateur*

**/!\ Les solutions proposées avec les impressions d'écranci-dessous sont des exemples, mais il existe plein d'autres manières de parvenir au résultat, laissez chacun trouver sa méthode !***

**Lancez Lancement Snap4Arduino :** chacun lance le logiciel sur son ordinateur, en cas de problème pour trouver le bon port série, montrez leur comment trouver le bon port en s'aidant de l'IDE Arduino.

**Mission 1 - Allumez une LED en direct**
Montrez leur comment brancher la LED à Arduino "en direct" via la breadboard afin qu'ils comprennent les sorties 5V et GND. 

**Mission 2 - Allumez une LED grâce à Arduino**
Montre-leur comment passer par l'arduino pour allumer la LED en remplaçant l'entrée 5V direct par une des PIN digital de l'Arduino. L'objectif est qu'ils saisissent la fonction de l'Arduino et la manière dont envoyer un signal VRAI ou FAUX. 
Laissez-les faire clignoter la LED manuellement en switchant entre VRAI et FAUX. 

![Led On/off](http://wiki.funlab.fr/images/4/4a/1.png)

### Expérimentation à son rythme
**60mn** - En binome sur son poste

Il s'agit de plusieurs étapes à réaliser pour prendre en main l'Arduino, le logiciel et pour intégrer la logique de programmation. Faites avancer les binomes à leur rythme étape après étape. L'objectif est ici de ne pas s'ennuyer et d'être stimulé par un certain nombre de petits défis.

Quelques recommandations : 
 - **Favoriser l'expérimentation** Laisser les binomes chercher  leur manière et trouver des biais détournés. L'important est qu'ils trouvent eux-même la solution.
 - **Etre attentifs aux blocage** pour ne pas créer trop de frustration (débloquer les binomes à temps)
 - **Etre vigilant aux relation au sein des binômes**. Il est important que chacun puisse contribuer à trouver la solution. N'hésitez pas à reformer des binomes de niveau en cours de route si nécessaire.

**Mission 3 - Faire clignoter la LED à interval régulier**

![Led clignote](http://wiki.funlab.fr/images/f/fb/2.png)

**Mission 4 - Faire sonner un Buzzer**

![buzzer](http://wiki.funlab.fr/images/1/10/3.png)

**Mission 5 - Faire varier les sons du buzzer**

![buzzer_cligno](http://wiki.funlab.fr/images/0/09/4.png)

**Mission 6 - Faire bouger un servomoteur à l'aide de touches du clavier**

![servo](http://wiki.funlab.fr/images/8/82/5.png)

**Mission 7 - Faire évoluer l'angle du servomoteur à l'aide d'une variable**

![servo_variable](http://wiki.funlab.fr/images/f/f1/6.png)

**Mission 8 - Paramétrer des limites d'angles / remise à zero du servomoteur**
Vous pouvez également demander ici de faire clignoter une LED/ bipper un buzzer lorsque la limite d'angle est dépassée.

![servo_buzzer](http://wiki.funlab.fr/images/9/9e/7.png)




### PAUSE

**20mn** - Autour du baby foot !

Une pause.
Pour se reposer.
Prendre son gouter.
Savourer de délicieux bonbons <3

### Le grand défi
**60mn à 120mn** - En mouvement

Pour finir la session, lancez un défi au groupe, qu'il réaliseront à deux, trois... ou huit participants. L'idée est de mettre en oeuvre leurs connaissances en Arduino très concrêtement, en passant par la phase de conception et de fabricationd 'un objet fonctionnel.

Commencez par leur donner des idées : 
- [Une pince simple en carton](https://www.hummingbirdkit.com/teaching/sketches/scissor-linkages)
- [Une grue imprimée en 3D](https://www.youtube.com/watch?v=KUmNDbAEv_c)

**Lancez leur ensuite le défi : fabriquez un prototype de bras ou de pince articulée !**

Laissez leur à disposition des cartons,ciseaux, colle, ficelle, moteur... et laissez les chercher. Votre rôle ici sera surtout de réfreiner les envies démesurées pour les décomposer en étapes réalisables dans le temps imparti. Ne brisez pas leurs rêve, mais aidez-les à en définir la plus petite étape atteignable ! 


Exemple de ce que cela peut donner : 
![carton_decoupe](http://wiki.funlab.fr/images/thumb/e/ea/Ados_arduino2.jpg/800px-Ados_arduino2.jpg)
![pince_realisation](http://wiki.funlab.fr/images/thumb/6/6b/Arduino_ados1.jpg/800px-Arduino_ados1.jpg)


## DEBRIEF 
Finissez par refaire un point collectif de débrief, par exemple au moment où les parents reviennent : **chacun présente ce qu'il a fait et découvert**. 

Faites un tour de clôtûre où chacun puisse **exprimer ce qu'il a apprécié ou moins apprécié**. Différents formats de clôture se retrouvent sur le web, il peut s'agir de demander à chacun d'exprimer une pépite (un point positif) et un rateau (un point négatif) ce qui a l'avantage de faire facilement ressortir des pistes d'améioration.

## Et ensuite ?
Avant de vous quitter, vous pouvez commencer à donner des idées par la suite, qui permettra aux participants de se projeter en autonomie au sein du FabLa : 
- Leur montrer le "vrai" code arduino pour qu'ils s'aperçoivent que ce n'est finalement pas si compliqu
- Leur donner l'idée d'une prochaine étape arduino qui fasse appel aussi à de la fabrication numérique. Sur la lancée des bras articulés, il y a par exemple le [Arm-robot](http://fablabo.net/wiki/Arm-robot) , plutôt bien documenté.  

