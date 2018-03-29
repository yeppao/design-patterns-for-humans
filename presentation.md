# Démarrage
Bonjour, il est evident que vous connaissez ou maitrisez déjà le sujet des designs patterns. Cependant, il est toujours interessant de revoir leur fonctionnement.

# Images
Les designs patterns, sont une solution répondant a un ou plusieurs problèmes rencontrés par des developpeurs.

> Cela vous permettra de passer de ça (Image 1) à ça (Image 2)

# Leurs groupes
> Il existe 3 groupes différents, Creation, Structure & Comportement

Nous allons les étudier en détail.

# Creation
> Résoud les problèmes liés a la création ou a la configuration d'objets

## Nous allons prendre comme exemple le **Builder**
Au Subway, lorsque vous commandez un sandwich, vous avez la possibilité de le personnaliser.

Le builder est donc le serveur qui compose votre sandwich avec les éléments que vous souhaitiez.

## Dans Symfony
FormBuilder, NodeBuilder, QueryBuilder

# Structure
> Résoud des problèmes liés a la structuration des classes
Les mots clés sont Adaptation, Maintenabilité

## Nous allons prendre comme exemple le **Decorator**
Dans un coffee-shop, la base, c'est le café. Le café sera la classe originelle permettant de composer d'autres recettes

## Dans Symfony
Le HttpCache

# Comportement
> Résoud les problèmes liés a l'interaction entre les classes

## Nous allons prendre comme exemple le **Mediator**
Votre opérateur mobile : vous souhaitez envoyer un message a une autre personne

## Dans Symfony
L'EventDispatcher

# The End ?
Amener les developpeurs a être curieux sur les design patterns utilisés dans Symfony, aller regarder le code des librairies qu’ils consomment, + challenger leur dev pour adopter les design patterns qui leur simplifieraient la vie
