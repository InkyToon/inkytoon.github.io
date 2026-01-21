# Sobriété énergétique

## Introduction

Ce projet a été réalisé en BUT2 lors d'une SAE (Situation d'apprentissage évaluée) en groupe de 6 ayant pour but la sobriété énergétique de l'IUT. Nous avions alors de faux client qui nous éclairait sur leur volonté (température, qualité d'air) pour avoir un IUT auto-géré en terme de sobriété énergétique.

## Travail effectué

Pour ce faire, des ESP32 étaient à disposition de chaque équipe permettaant la récupération des données via des capteurs. Le chemin des données était le suivant :

-> Récupération des données via les différents capteurs avec le MicroControlleur\
-> Envoi des infos des capteurs à l'API hébergée par l'IUT\
-> Backend qui récupère les informations de l'API avec une stack docker PHP avec symfony puis renvoie les données propre au Frontend\
-> Frontend affiche les données via React + Vite

**Langages et programmation :**
- PHP
- Javascript
- HTML/CSS
- C

**Frameworks, bibliothèques et outils de développement front/back :**
- Symfony
- React
- Vite
- ApiPlatform

**Bases de données et API / testing :**
- PHPUnit
- ESLint

**Outils, environnements et gestion de projet :**
- PHPStorm
- Docker
- VS Code
- Teams
- Miro
- Discord

**[Retour](../index.md)** 