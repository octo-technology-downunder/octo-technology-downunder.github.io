---
title: Test driven development on legacy code
sub-header: From legacy code to clean code
duration_days: 3
duration_hours: 21
time_shares:
  - label: Presentation
    value: 20
  - label: Use cases
    value: 70
  - label: Sharing experiences
    value: 10
type: Workshop
category: craftsmanship
layout: training
---

## Description

Le code legacy est une métaphore pour parler de ce code existant dans nos applications, difficile à maintenir, souvent de mauvaise qualité et non testé automatiquement. Ce module forme les développeurs aux pratiques permettant de maintenir et de faire évoluer du code legacy sans risque, et ainsi trouver les trajectoires de retour à une haute qualité.

## OBJECTIFS PÉDAGOGIQUES

Savoir appréhender des problèmes de qualité du code et appliquer les techniques de refactoring de code
Identifier les points d’entrée pour faire évoluer du code legacy en minimisant les risques
Appliquer les techniques pour mettre en place des tests automatisés autour de code legacy
Evaluer les risques pour choisir une stratégie adaptée de réduction de la dette technique
PUBLIC CIBLE

* Chef de projet en développement
* Développeur
* Testeur ayant une fibre développement
* Architecte
* Technical Leader

## PRÉ-REQUIS

Compétences en programmation et génie logiciel.
Une expérience dans le développement piloté par les tests (TDD) et la programmation orientée objet est un plus.
Avoir suivi la formation "Qualité des développements avec Test Driven Development" (TDD01) serait un plus.
MÉTHODE PÉDAGOGIQUE

Formation principalement composée d’exercices pratiques qui fourniront aux participants des outils qu’ils pourront mettre en pratique immédiatement dans leurs projets actuels.
Echanges sur les contextes des participants et retours d’expérience du formateur, complétés d’apports théoriques.

## PROFILS DES INTERVENANTS

Toutes nos formations sont animées par des consultants-formateurs expérimentés et reconnus par leurs pairs.

## MODALITÉS D’ÉVALUATION

L’évaluation des acquis se fait tout au long de la session au travers des ateliers et des mise en pratiques. Une évaluation à chaud est réalisée systématiquement en fin de session.

## PROGRAMME :

### Jour 1

#### CONNEXION
En binômes, racontez une situation où intervention sur le code a produit un retour de bâton
Tour de table
Présentation des participants
Exposé des situations
#### ANTI PATTERN : LEGACY CODE
Du code que nous avons reçu en héritage, qui a une valeur pour l’entreprise, et qu’il faut modifier
Les quatre raisons de modifier un code legacy
Couvrir les tests avec un harnais de tests unitaires
Améliorer le délai de feedback du code sur le développeur
Difficultés du TDD sur du code legacy
Le dilemme du code legacy
Exercice pratique : "Racontez une session de travail durant laquelle vous avez renoncé à écrire un test sur du code existant."
#### STRATÉGIE DE MODIFICATION D’UN CODE LEGACY
Identifier un point de changement
Trouver les points de test
Casser les dépendances
Ecrire des tests
Effectuer le changement et refactorer
Types de raccords : préprocesseur, faux collaborateurs
#### CLÔTURE DU JOUR 1
### Jour 2

#### PATTERN : TEST DE CARACTÉRISATION
Problème : le code est non testé, la documentation est absente ou obsolète
Solution: écrire des tests qui caractérisent le système tel qu’il est
Démarche :
Appeler un morceau de code depuis un harnais de test
Ecrire une assertion dont vous savez qu’elle échouera
En échouant le test indique quel est le comportement du code
Modifier le test de façon à ce qu’il attende le comportement que produit le code
Répéter
Heuristique générale
Test de caractérisation sur un bug
Exercice pratique : "Installer la base de code TriviaGame – examiner les classes – écrire des tests de caractérisation."
Débrief toutes les 25 minutes
#### PATTERN : DIAGRAMME D’EFFET
Problème : on souhaite étudier l’impact que pourrait avoir un changement sur le code
Solution : tracer les effets de chaque variable sur les méthodes impactées
Exercice pratique : "Sur le code de Trivia Game, rechercher les effets d’un changement en traçant un diagramme d’effet."
#### CLÔTURE DU JOUR 2

### Jour 3
#### PATTERN : EXTRACT INTERFACE
Problème : une classe collabore avec une classe posant une dépendance extérieure
Solution : extraire une interface de la classe posant la dépendance
Autres patterns de rupture de dépendances extérieures
Exercice pratique : "Sur un code sélectionné dans vos projets, effectuer des tests de caractérisations, puis du refactoring, en utilisant la stratégie vue précédemment."
Débrief toutes les 25 minutes
#### BILAN ET CLÔTURE DE LA SESSION
