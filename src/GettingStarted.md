# Presstify Framework

## A Propos de PresstiFy

**PresstiFy** est un framework d'entreprise développé par la société [Milkcreation](https://milkcreation.fr/). 
Il permet de réaliser simplement des sites internet et des applications web dans un environnement **Wordpress**.

**Framework PHP** résolument moderne, il appuie son développement sur des concepts initités par les poids lourds du 
marché que sont [Symfony](https://symfony.com/) et [Lavarel](https://laravel.com/), ainsi que d'autres librairies 
modernes toutes aussi réputées comme [La Ligue des Packages Extraordinaires](https://thephpleague.com/).

Ce choix technologique permet de garantir une meilleure compatibilité de vos projets web, dans un environnement 
respectant les standards du développement PHP conduit par [PHP-Fig](https://www.php-fig.org/psr/).
 
**Presstify** ne s'arrête pas là, il propose d'autres approches singulières et innovantes; offrant ainsi aux 
développeurs une productivité augmentée et aux utilisateurs finaux une expérience web encore plus riche.

## Démarrer avec PresstiFy

### Installation

#### Prérequis

* PHP >= 7.2.0
* MySQL >= 5.6.0
* Extensions PHP requise :
    * php-curl
    * php-intl
    * php-mbstring
    * php-xml
* Extensions PHP recommandée :
    * php-gd
    * php-imagick
    * php-soap (modules de paiement e-commerce)

#### Lancer l'installation

##### Wordpress classic (recommandée)

L'installation "*Wordpress Classic*" permet de conserver une arborescence de projet similaire à une installation 
standard de **Wordpress** décrite sur le [site officiel](https://fr.wordpress.org/txt-install/).

###### via composer 

```bash
$ composer create-project --repository-url https://composer.tigreblanc.fr/presstify presstify/wordpress-classic htdocs
```
###### Configuration

Dans le cadre d'une installation "*Wordpress Classic*", les fichiers de configuration sont stockés dans le sous-dossier 
*config* de votre thème courant. 
Vous trouverez prochainement des informations sur la mise en oeuvre de la configuration des composants de Presstify sur
le [site officiel](https://presstify.com/docs). 

D'ici là vous pouvez toujours vous reporter à la documentation embarquée dans les modules de PresstiFy.