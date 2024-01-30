# VCA

## Nous voulons créer une application qui permet à un partenaire d'identifier un membre du reseau, calculer ses remises, & renseigner ses transaction dans notre base de données.

Pour ce faire:
* nous voudrons une application android membre qui doit:
  * logguer/identifier un membre
  * qui affiche ses differents status
  * qui fournit un code barre/QR code qui pourra etre scanée par l'application partenaire

* nous voudrons une application android partenaire qui doit:
  * logguer/identifier un partenaire
  * scaner l'identifiant de l'application membre
  * interroger notre BDD sur les credits du membre
  * updater toutes transactions avec ce membre dans notre BDD
  
* Nous voudrons une base de données (& son API) disponible dans le cloud pour regir ses 2 applications
* Nous aurons besoin d'un DashBoard pour administrer l'ensemble du projet

* Nous aurons besoin d'un compte Github pour VCA, qui hebergera & possedera ce code advitam eternam
* Nous aurons besoin de creer une organisation VCA-[nom-du-projet] pour inviter les codeurs a contribuer a ce code
* Nous devrons definir une license open-source pour ce projet avec les decideurs VCA
* nous aurons besoins d'utilisateurs (ausi bien membres que partenaires) volontaires pour tester ces applications à outrance, remonter les bugs & demandes sur ce repository (ils devront créer un compte github)
* ... (à compléter)

## contraintes des devellopeurs
* Typescript obligatoire
* zod (shema)
* tout se passe sur github
* le repository (repertoire github) sera cloner sur le compte github VCA & appartiendra à VCA

