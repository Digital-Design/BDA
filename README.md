# BDA

## A Utiliser :
 * serveur apache (wamp, laragon, lamp etc..)

 * github

 * trello (à mettre en favori, il y a la liste des tâches à faire)

 * Doc php et doc Symfony (idem en favori)

 * la liste des liens utiles dispos sur le drive.

## Informations utiles
### Only windows :

 * installer cmder : http://cmder.net/ console de bien meilleure qualité que celle de windows.
 --------------

 * installer composer : https://getcomposer.org/download/ windows ou linux, whatever

 * installer npm : https://nodejs.org/en/download/ windows ou linux, idem.

 * installer une interface git (git gui ou git desktop mais il faut que ça marche)

### Comment ça marche ?

Vous cloner le repository dans un dossier, sur windows:

	* C:/{nom du serveur}/www/bda de préférence

	* /var/html/www/bda ou un truc comme ça sur linux

Si vous avez bien installer ce qui a été demandé au-dessus c'est bon.

Architecture du site :

	* web/ -> c'est l'équivalent d'un public/ c'est tout ce qui sera visible au grand public, donc en général, ça en contient que les fichiers .js, .css, ou les images

	* src/{nom_du_bundle} -> c'est la ou seront stockés les controlleurs, ainsi que les appels des objets en base de données

	* app/config -> c'est la qu'il y aura toutes la configuration du site, routes etc..

	* app/resources -> c'est la qu'on stockera nos vues, attention, c'est du twig.

	Des questions ? go me mp.

Symfony Standard Edition
========================

Welcome to the Symfony Standard Edition - a fully-functional Symfony
application that you can use as the skeleton for your new applications.

For details on how to download and get started with Symfony, see the
[Installation][1] chapter of the Symfony Documentation.

What's inside?
--------------

The Symfony Standard Edition is configured with the following defaults:

  * An AppBundle you can use to start coding;

  * Twig as the only configured template engine;

  * Doctrine ORM/DBAL;

  * Swiftmailer;

  * Annotations enabled for everything.

It comes pre-configured with the following bundles:

  * **FrameworkBundle** - The core Symfony framework bundle

  * [**SensioFrameworkExtraBundle**][6] - Adds several enhancements, including
    template and routing annotation capability

  * [**DoctrineBundle**][7] - Adds support for the Doctrine ORM

  * [**TwigBundle**][8] - Adds support for the Twig templating engine

  * [**SecurityBundle**][9] - Adds security by integrating Symfony's security
    component

  * [**SwiftmailerBundle**][10] - Adds support for Swiftmailer, a library for
    sending emails

  * [**MonologBundle**][11] - Adds support for Monolog, a logging library

  * **WebProfilerBundle** (in dev/test env) - Adds profiling functionality and
    the web debug toolbar

  * **SensioDistributionBundle** (in dev/test env) - Adds functionality for
    configuring and working with Symfony distributions

  * [**SensioGeneratorBundle**][13] (in dev/test env) - Adds code generation
    capabilities

  * **DebugBundle** (in dev/test env) - Adds Debug and VarDumper component
    integration

All libraries and bundles included in the Symfony Standard Edition are
released under the MIT or BSD license.

Enjoy!

[1]:  https://symfony.com/doc/3.0/book/installation.html
[6]:  https://symfony.com/doc/current/bundles/SensioFrameworkExtraBundle/index.html
[7]:  https://symfony.com/doc/3.0/book/doctrine.html
[8]:  https://symfony.com/doc/3.0/book/templating.html
[9]:  https://symfony.com/doc/3.0/book/security.html
[10]: https://symfony.com/doc/3.0/cookbook/email.html
[11]: https://symfony.com/doc/3.0/cookbook/logging/monolog.html
[13]: https://symfony.com/doc/3.0/bundles/SensioGeneratorBundle/index.html
