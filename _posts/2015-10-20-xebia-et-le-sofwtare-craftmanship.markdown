---
layout: post
title:  'Xebia et le "Software Craftsmanship"'
date:   2015-10-20 11:30:00
isStaticPost: false
---
Chez Xebia, les développeurs sont des acteurs du mouvement “Software Craftsmanship”. Cette vague vise à faire progresser la qualité des développement logiciels par la diffusion, l’apprentissage et la mise en oeuvre de bonnes pratiques au sein desquelles les tests tiennent une place centrale. Les tests unitaires assurent que la logique métier ou technique de l’application est bonne : ils sont réalisés par **JUnit, Mockito** et **Robolectric**. Les tests fonctionnels, quant à eux, valident de bout en bout le bon fonctionnement de l’application sur les parcours critique : l’utilisation d’**Espresso** et de **Spoon** font parties des bonnes pratiques.

La principale action réalisée par les Xebians est de mettre en place une stratégie de tests dès le début du projet et de la maintenir tout au long de la vie du produit. Afin de s’assurer du maintien de cette stratégie, les outils de métriques, telle que la couverture de tests, sont mis en place afin de suivre l’évolution de la maturité du projet. L’outil de référence **SonarQube** pour la qualité code ainsi que l’outil de couverture de tests **Jacoco** sont disponibles pour Android. 

Au sens de méthodologie agile, les livrables sont accessibles à tout moment, ce qui implique un processus de déploiement continu. La machine d’intégration automatise l’exécution des tests unitaires et fonctionnels, tout en assurant la mise à disposition des applications pour les beta testeurs. La combinaison de **Jenkins** et de **Fabric** est un exemple de machine d’intégration continue.

![Le processus de déploiement continu](https://lh3.googleusercontent.com/C_cI3FmsbEuRhMJrd7VR8G27wyO460CYzNDmTmMAsQ=s0 "Le processus de déploiement continu")
***Le processus de déploiement continu***

Pour plus d’informations sur les tests, découvrez notre livre blanc “[TechTrends Mobile](http://www.xebia.fr/livresblancs.html)”.

ABOUT XEBIA

Xebia est un cabinet de conseil parisien regroupant des passionnés et des experts de technologies Big Data, Cloud, Web, d’architectures Java et de mobilité dans des environnements agiles. Nous croyons qu’il est possible de développer des applications à la fois innovantes, performantes et de très bonne qualité. C’est au sein de Xebia Studio que nous mettons en œuvre cette philosophie. Xebia fait aujourd’hui autorité dans le domaine mobile et souhaite continuer sur cette lancée avec l’avènement des objets connectés. Pour ce faire, les xebians partagent leurs connaissances au quotidien via notre blog technique ([blog.xebia.fr](http://blog.xebia.fr/)), twitter (@XebiaFr) et participent/animent des conférences et des Tech Events.
