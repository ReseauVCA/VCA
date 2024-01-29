# VCA

# Nous voulons créer une application qui permet & un partenaire d'identifier un membre du reseau, calculer ses remises, & renseigner ses transaction dans notre base de données.

pour ce faire:
* nous voudrons une application android membre qui doit:
  * logguer/identifier un membre
  * qui affiche ses differents status
  * qui fournit un code barre/QR code qui pourra etre scanée par l'application partenaire

* nous voudrons une application android partenaire qui doit:
  * logguer/identifier un partenaire
  * scaner l'identifiant de l'application membre
  * interroger notre BDD sur les credits du membre
  * updater toutes transactions avec ce membre dans notre BDD
  
* nous voudrons une base de données (& son API) disponible dans le cloud pour regir ses 2 applications
 * nous aurons besoin d'un DashBoard pour administrer l'ensemble du projet

* Nous aurons besoin d'un compte Github pour VCA, qui hebergera & possedera ce code advitam eternam
* nous aurons besoin de creer une organisation VCA-[nom-du-projet] pour inviter les codeurs a contribuer a ce code

## contraintes des devellopeurs
* Typescript obligatoire
* zod (shema)
* tout se passe sur github
