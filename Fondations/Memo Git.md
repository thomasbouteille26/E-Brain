#WhyGit
Git permet de garder en mémoire :
-   chaque modification de chaque fichier ;
-   pourquoi elle a eu lieu ;
-   et par qui !
**Git est un gestionnaire de versions**. Vous l’utiliserez pour créer un dépôt local et gérer les versions de vos fichiers.
**GitHub est un service en ligne** qui va héberger votre dépôt. Dans ce cas, on parle de **dépôt distant** puisqu’il n’est pas stocké sur votre machine.

#WhatsDepotGit
Un **dépôt local** est un entrepôt virtuel de votre projet. Il vous permet d'enregistrer les versions de votre code et d'y accéder au besoin.O n réalise une version du code, que l'on va petit à petit améliorer. Ces versions sont stockées au fur et à mesure dans le dépôt local.
Le **dépôt distant** est un peu différent. Il permet de stocker les différentes versions de votre code afin de garder un **historique délocalisé**, c'est-à-dire un historique hébergé sur Internet.
Ainsi, les dépôts sont utiles si :
-   vous souhaitez conserver un historique de votre projet ;
-   vous travaillez à plusieurs ;
-   vous souhaitez collaborer à des projets open source ;
-   vous devez retrouver par qui a été faite chaque modification ;
-   vous voulez savoir pourquoi chaque modification a eu lieu.

#HowGithub
**L’onglet Pull requests** permet de faire des demandes de modifications réalisées sur le code.Pour informer les autres utilisateurs des modifications que vous avez appliquées à une branche d'un repository sur GitHub, et que vous voulez fusionner avec le code principal.

#CommandesGit
**Commandes basique**
git config --global user.name "Thomas Bouteille"
git config --global user.email  thomas.bouteille@example.fr
git config --list - Liste tous les paramètres de config initialisé
git init - - initialisé le depot git **COMMANDE A PASSER DANS LE REPERTOIRE A SUIVRE**


#AstucesGit
**Activer les couleurs pour une meilleure lisibilité**
git config --global color.diff auto
git config --global color.status auto
git config --global color.branch auto



