---
title: Variables et affectations
date: 2020-03-14T15:40:24.000+06:00
image: images/2020-three-quarters-1.png
author:
- Admin
categories:
- Working days
tags:
- work
- day
description: This is meta description

---
Dès que l’on possède des _types de données_, on a besoin des _variables_ pour stocker les données. En réalité, Python n’offre pas la notion de variable, mais plutôt celle de _référence d’objet_. Tant que l’objet n’est pas modifiable (comme les entiers, les flottants, etc.), il n’y a pas de différence notable. Dans le présent calepin, nous discutons les grandes lignes atour de l’utilisation des variables sous Python.

Il faut remarquer que les variables en chaînes de caractères sont toujours définies avec des guillemets. Avec des guillemets simples, on a des chaines de types char alors qu’avec des guillemets doubles, on obtient des chaînes de type string. Noter aussi que même si une variable est définie avec des nombres, lorsque ces nombres sont indiqués avec des guillemets, python traite cette variable comme une chaine de caractères. Néanmoins, il existe des fonctions pour convertir une variable d’un type à un autre lorsque cette conversion est autorisée. Voir les exemples suivants.