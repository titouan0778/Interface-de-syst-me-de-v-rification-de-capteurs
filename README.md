# Interface de système de vérification de capteurs

## Description

Ce projet est une interface web permettant de gérer des capteurs.

L'interface a été réalisée en HTML et CSS et reprend le principe du projet de vérification de capteurs.

Elle permet d'afficher les capteurs enregistrés et propose différentes actions pour les gérer.

## Fonctionnalités

L'interface permet de :

* Ajouter un capteur
* Modifier un capteur
* Supprimer un capteur
* Afficher la liste des capteurs enregistrés

Lorsqu'aucun capteur n'est enregistré, un message est affiché :

Aucun capteur enregistré pour le moment

## Interface

La page principale contient :

* Un titre `Système de vérification` de capteurs
* Une section permettant d'afficher les capteurs enregistrés
* Un bouton `Ajouter un capteur`
* Un bouton `Modifier un capteur`
* Un bouton `Supprimer un capteur`

Les éléments sont organisés à l'aide de HTML et mis en forme avec CSS.

## Structure du projet


Interface-de-syst-me-de-v-rification-de-capteurs/

* capteur.html    # Page principale de l'interface
* capteur.css     # Mise en forme de l'interface
* LICENSE         # Licence du projet
* README.md       # Documentation du projet

## Technologies utilisées

* HTML
* CSS

## Fonctionnement

### Affichage des capteurs

Les capteurs enregistrés sont affichés dans une liste sur la page.

Si aucun capteur n'est présent, le message suivant est affiché :

`Aucun capteur enregistré pour le moment`

### Ajouter un capteur

Le bouton `Ajouter un capteur` permet de lancer l'action permettant d'ajouter un nouveau capteur.

### Modifier un capteur

Le bouton `Modifier un capteur` permet de modifier les informations d'un capteur existant.

### Supprimer un capteur

Le bouton `Supprimer un capteur` permet de supprimer un capteur de la liste.

## Mise en forme

Le fichier `capteur.css` permet notamment de :

* Centrer l'interface sur la page
* Définir une largeur de 800 pixels pour le bloc principal
* Ajouter une bordure autour de l'interface
* Arrondir les coins du bloc
* Organiser les boutons
* Ajouter des espaces entre les différents éléments

## Utilisation

Pour utiliser l'interface, il suffit d'ouvrir le fichier :

`capteur.html`

dans un navigateur web.

Aucune installation particulière n'est nécessaire pour afficher la page HTML et son style CSS.

## Objectif

Ce projet a pour objectif de créer une interface web simple pour gérer des capteurs.

Il permet notamment de mettre en pratique :

* La structure d'une page HTML
* Les éléments HTML comme les titres, listes et boutons
* Les identifiants (`id`)
* La mise en forme avec CSS
* Le positionnement des éléments
* La création d'une interface simple et organisée

## Améliorations possibles 

* Ajouter un fichier JavaScript pour rendre l'interface dynamique
* Lier le fichier JavaScript avec le code C++ (disponible à l'adresse `https://github.com/titouan0778/Systeme-de-verification-de-capteurs` sous forme d'interface console pour le moment)

## Licence

Ce projet est sous licence MIT.

Voir le fichier LICENSE pour plus d'informations.

## Auteur

FOUCHE Titouan
