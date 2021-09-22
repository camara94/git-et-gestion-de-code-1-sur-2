# Git et gestion de code partie 1 sur 2
## Les possibilité de git
Git permet 👍
* De versionner ses fichiers( code, images, documents, ...)
* De mettre en attente une version et de travailler sur une autre
* De pouvoir fusionner un même fichier sur lequel plusieurs personnes ont travaillé
* D'organiser son travail par version
* De publier en production son code source à partir d'une version donnée
* D'avoir une historique precise de son projet
* De pouvoir blamé quelqu'un !;-)
* .... 
## Les ressources
* [https://git-scm.com/](https://git-scm.com/): Site officiel de Git
* [http://github.com](http://github.com): Plateforme en ligne de Git
* [http://gitref.org](http://gitref.org): Pour ne jamais oublier les commandes
* [https://try.github.io](https://try.github.io): Pour s'entrainer

## Qu'est ce qu'un gestionnaire de version ?
* Enregistrer les évolutions d'un fichier
* Permet de revenir à une version précédente
* Fonctionne avec tout type de fichier(.txt, .java, .jpg, .exe, ...)
* Permet de retrouver un fichier supprimé
## Les trois états
* Un fichier modifier sous Git peut être sous 3 états:
    * **Validé,** le fichier est sauvegardé en base.
    * **Modifier,** le fichier est modifié, la modification n'est pas en base.
    * **Indexé,** le fichier est modifié, et est prêt à être envoyé en base.
  ![etats](images/trois-etats.png)

## Les trois états
* Ce qui nous donne trois sections principales d'un projets GIT
    1. **Validé** = Le répertoire **.git**
    2. **Modifier** = Le répertoire **courant de travail**
    3. **Indexé** = La zone virtuelle qui liste les fichiers qui seront dans le prochain instantané.

![etats](images/trois-etats.png)

## Initialisation d'un dossier 
Pour initialiser un dossier git, on tape <code>git init</code>
   