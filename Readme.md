# Workshop Laravel

![Logo Laravel](laravel-logo-big.png)

## Introduction
### Qu'est-ce que Laravel ?

Laravel est un CMS en PHP qui permet de créer un site en suivant un modèle MVC et qui est basé sur Symphony. Sa grosse différence avec WordPress est que Laravel fonctionne de manière beaucoup moins visuelle pour le développeur, ayant une configuration et un développement plus orienté Back-End.
Laravel a une gestion de base de donnée ainsi que de page html propre à elle, que nous verrons plus loin.
Car avant de commencer, installons Composer.

### Composer ? Kézako ? Et quelle nécessité ?

![Logo Composer](Logo-composer-transparent.png)

En effet, pour Installer et utiliser Laravel et ses différentes fonctionnalités, il faut tout d'abord utiliser Composer. Et ce dernier est à PHP ce que NPM est à Node.JS. C'est un gestionnaire de dépendances qui permet d'installer, comme sa fonction l'indique, des dépendaces et donc des packages de fonctionnalités que l'on peut comparer aux modules Node.JS.

Pour l'installer, suivez le guide: https://getcomposer.org/download/

A présent que Composer est installé, passons à la suite.

### Installation de Laravel

Maintenant que Composer est intallé, nous allons nous rendre dans le dossier www contenant nos projets habituels afin de créer notre projet.

!!Attention!! Vérifiez à posséder la version la plus récente de PHP.

ouvrez votre terminal et tapez :
```
composer global require "laravel/installer"
```

Quand celà est fait, tapez : 
```
laravel new nom-de-projet
```

Composer va alors initialiser un nouveau projet contenant Laravel.
Vous voulez voir ce que vous avez créé ? Allez sur votre Localhost et ouvrez le dossier contenant le projet (ou ajoutez le sur wamp si vous êtes sur windows, xamp sur mac).
Vous arriverez sur un index ressemblant à ça : 

![index](folder-content.png)