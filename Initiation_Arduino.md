#Arduino - initiation ados
[TOC]

##Objectifs de la séquence
- Connaître focntionnement de base d’un arduino et de ses composants principaux
- Savoir être autonome dans l'apprentissage de l’Arduino
- Avoir la capacité et l’envie de poursuivre en auto-apprentissage accompagné l’arduino aus ein du FabLab.

![photo_atelier](http://wiki.funlab.fr/images/thumb/c/c1/Ados_arduino_3.jpg/800px-Ados_arduino_3.jpg)

##Pré-requis
- **Participants :** avoir de 10 à 16 ans, savoir et prendre du plaisir à utiliser internet et un ordinateur.
- **Animateurs :** savoir utiliser les fonctions et composants de base d’un arduino


##Matériel
Pour huit participants : 
- 4 ordinateurs
- 4 « starter kit » arduino
- 1 vidéo- projecteur
- Cartons et matériaux de récupération
- Matériel de petit bricolage : ciseaux, cutter, colle chaude, petits boulons,...

##Préparation de la séquence
![Installation](https://pbs.twimg.com/media/DLjO6UWUIAEwslf.jpg)

1. **Installer Arduino IDE sur les ordinateurs** - Prévoir un ordinateur pour deux participants) [lien de téléchargement](https://www.arduino.cc/en/Main/Software#) 

2. **Téleverser Firmata sur chaque Arduino** - Cela vous  permettra de faire fonctionner l’arduino via le logiciel Snap4Arduino. *Prévoir un Arduino pour deux participants : Lancez arduino IDE, connectez l’arduino à l'ordinateur, sélectionnez le fichier exemple Firmata (Fichier>Exemples>Firmata>StandardFirmata) puis téléversez le dans l’arduino.* 
*
**/!\ En cas de problème de téléversement** - Vérifiez que vous êtes sur le bon port série (Outils>Port Série>...) et que vous avez bien sélectionné la bonne carte Arduino () soit pas bon type de carte(Outils>Type de carte>...).
*
3. **Installer Snap4Arduino** - Téléchargez le logiciel [sur le site officiel](http://snap4arduino.rocks/), installez-le puis lancez-le. Testez la connection à votre, dans la patie contenant les blocs Arduinos. *
/!\ **Ne vous trompez pas de port série**, sinon il est possible qu'il faille relancer le logiciel...
*


##Déroulé
###Lancement de la séquence
*
**15mn** - debout en cercle*
 - **Présentation(s) :** l’intervenant.e.s se présente.nt (prénom, rôle, compétences techniques)
 - **Photo-langage :** une animation pour symboliser l’arrivée dans le groupe, permettre à chacun de partager l’état d’esprit dans lequel il arrive et de se présenter par un biais détourné. Disposer des images sur la table (un jeu de dixit par exemple) et demander aux participants d’en choisir une qui correspond à son état d’esprit du moment (peut être demandé pendant que les participants attendent le démmarage). Lorsque tout le monde a sa carte, s’installer debout en cercle et demander à chacun de donner son prénom et pourquoi il a choisis cette carte.
 - **Déroulé de l’atelier :** proposer au groupe le déroulé imaginé pour la séquence, et les objectifs poursuivis. S’assurer que cela ne crée pas d’objection franche ou de frustration, adapter à la marge le programme pour lever ces objections si elles existent.
 - **Point logistique :** expliquer les règles minimales de sécurité, de condition d’usage des locaux et du matériel, indiquer les toilettes.
 - **Définir vos règles :** demander au groupe les règles nécessaires pour que la session se passe bien, en particulier dans les relations entre les personnes. Valider collectivement ces quelques règles simples.

![Dixit utilisé pour le photolanguage](http://wiki.funlab.fr/images/thumb/4/41/20171024_123208.jpg/800px-20171024_123208.jpg)

### Déballage et bases théoriques
On déballe l’arduino + on montre une variété de capteurs composants sur la table
On explique le fonctionnement de base : capteurs /code/interraction e, montrant et en touchant
On montre deux exemples simples : 
Exemple 1 – Mirobot - https://www.youtube.com/watch?v=8NscDzlTb9U 
Exemple 2 – domotique (lumière minuterie, détecteur de présence,…) - Vélo Espace - http://wiki.funlab.fr/index.php/V%C3%A9lo_Espace  //
On révise les bases de l’électronique / électricité : 
On pose la question : sauriez-vous expliquer le montage pour allumer une LED, et expliquer le principe ?
On échange à partir des réponses, en dessinant sur un paperboard
Le sens du courant
Le fonctionnement d’un circuit simple LED / Résistancxe (on ne rentre pas dans les calculs, simplement comprendre le fonctionnement grossier)
On ajoute la notion de signal envoyé par arduino (5V ou autre,...)


Lancement SNAP
Chacun connecte arduino, lance snap
! possible problème si pas choisis le bon COM. Peut être intéressant de le vérifier avec l’IDE Arduino

Impr ecran sont des exemples, plein d'autres solutions

Etape 1 
Allumer LED EN DIRECT (5V / GND)
Tous sur même port => on montre

Photo

Ensuite sur sortie digital (comprendre l’intérêt de l’arduino : il va maintenant falloir lui dire d’envoyer une impulsion.

IMPR ECRAN 
Jouer avec TRUE / FALSE
![Led On/off](http://wiki.funlab.fr/images/4/4a/1.png)

###Expérimentatio à son rythme
Etape 2
Clignoter LED
=> ils cherchent

IMPR ECRAN

![Led clignote](http://wiki.funlab.fr/images/f/fb/2.png)

Etape 3 
Buzzer
=> on montre un son

![buzzer](http://wiki.funlab.fr/images/1/10/3.png)

Etape 4
Buzzer
On demande de faire varier les sons

![buzzer_cligno](http://wiki.funlab.fr/images/0/09/4.png)

Etape 5
Servomoteur mettre à un angle
Plusieurs touches utilisées

![servo](http://wiki.funlab.fr/images/8/82/5.png)


Etape 6
Servomoteur faire varier à l’aide d’une variable
Deux touches
![servo_variable](http://wiki.funlab.fr/images/f/f1/6.png)

Etape 7
Servomoteur faire varier à l’aide d’une variable / remise à zero ou blocage quand limite dépassée
+ buzzer si limite dépassée

![servo_buzzer](http://wiki.funlab.fr/images/9/9e/7.png)



###PAUSE

###Défis pince
Votre défis, fabriquer une pince !

Montrer deux exemples de pinces : 
Carton pince simple : https://www.hummingbirdkit.com/teaching/sketches/scissor-linkages 
Grue - https://www.youtube.com/watch?v=KUmNDbAEv_c 
Pour lancer ensuite sur projet http://fablabo.net/wiki/Arm-robot 

Faire un premier début de proto en carton
Exemple : 
![carton_decoupe](http://wiki.funlab.fr/images/thumb/e/ea/Ados_arduino2.jpg/800px-Ados_arduino2.jpg)
![pince_realisation](http://wiki.funlab.fr/images/thumb/6/6b/Arduino_ados1.jpg/800px-Arduino_ados1.jpg)



DEBRIEF 
Chacun montre ce qu’il a fait
On montre le « vrai code arduino avec ….
Tour de cloture
