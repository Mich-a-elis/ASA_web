---
title: Le contrôle dans tous ses états


event: ASA conference
event_url: https://example.org

subtitle: La théorie du contôle

# Summary for listings and search engines
summary: En mathématiques et en ingénierie, la théorie du contrôle a comme objet l'étude du comportement de systèmes dynamiques paramétrés en fonction des trajectoires de leurs paramètres. La conduite d'une voiture est un système dynamique contrôlé. Le contrôle est l'angle du volant, les pressions exercée sur le frein et sur l'accélérateur, et l'état est la position de la voiture sur la route. le jeu de tennis est un système dynamique contrôlé. Le contrôle est ma position sur le court ainsi que la position et le mouvement de ma raquette, et l'état est la position de la balle. Le pilotage d'une torpille est aussi un système dynamique contrôlé. Le contrôle est la position de ses aillettes, et l'état la position de la torpille.

# Link this post with a project
projects: []


# Date published
date: "2022-01-22T00:00:00Z"

# Date updated
lastmod: "2022-01-22T00:00:00Z"


# Date published

abstract: En mathématiques et en ingénierie, la théorie du contrôle a comme objet l'étude du comportement de systèmes dynamiques paramétrés en fonction des trajectoires de leurs paramètres. La conduite d'une voiture est un système dynamique contrôlé. Le contrôle est l'angle du volant, les pressions exercée sur le frein et sur l'accélérateur, et l'état est la position de la voiture sur la route. le jeu de tennis est un système dynamique contrôlé. Le contrôle est ma position sur le court ainsi que la position et le mouvement de ma raquette, et l'état est la position de la balle. Le pilotage d'une torpille est aussi un système dynamique contrôlé. Le contrôle est la position de ses aillettes, et l'état la position de la torpille.


# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: true

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ""
  placement: 2
  preview_only: false

authors:
- Baparou DAHNANE

---


<br>

**Date**: 2022/01/22

<br>
<br>


**Qu’est-ce que la théorie du contrôle ?** La théorie du contrôle analyse les propriétés des systèmes commandés, c’est-à-dire des systèmes dynamiques sur lesquels on peut agir au moyen d’une commande (ou contrôle). Le but est alors d’amener le système d’un état initial donné à un certain état final, en respectant éventuellement certains critères. Les systèmes abordés sont multiples : systèmes différentiels, systèmes discrets, systèmes avec bruit, avec retard... Leurs origines sont très diverses : mécanique, électricité, électronique, biologie, chimie, économie... L’objectif peut être de stabiliser le système pour le rendre insensible à certaines perturbations (stabilisation), ou encore de déterminer des solutions optimales pour un certain critère d’optimisation (contrôle optimal). Dans les industries modernes où la notion de rendement est prépondérante, le rôle de l’automaticien est de concevoir, de réaliser et d’optimiser, tout au moins d’améliorer les méthodes existantes. Ainsi les domaines d’application sont multiples : aérospatiale, automobile, robotique, aéronautique, internet et les communications en général, mais aussi le secteur médical, chimique, génie des
procédés, etc. Du point de vue mathématique, un système de contrôle est un système dynamique dépendant d’un paramètre dynamique appelé le contrôle. Pour le modéliser, on peut avoir recours à des équations différentielles, intégrales, fonctionnelles, aux différences finies, aux dérivées partielles, stochastiques, etc. Pour cette raison la théorie du contrôle est à l’interconnexion de nombreux domaines mathématiques. Les contrôles sont des fonctions ou des paramètres, habituellement soumis à des contraintes. 

<br>

**Contrôlabilité.** Un système de contrôle est dit contrôlable si on peut l’amener (en temps fini) d’un état initial arbitraire vers un état final prescrit. Pour les systèmes de contrôle linéaires en dimension finie, il existe une caractérisation très simple de la contrôlabilité, due à Kalman. Pour les systèmes non linéaires, le problème mathématique de contrôlabilité est beaucoup plus difficile.

<br>

**Origine du contrôle optimal.** Une fois le problème de contrôlabilité résolu, on peut de plus vouloir passer de l’état initial à l’état final en minimisant un certain critère ; on parle alors d’un problème de contrôle optimal. En mathématiques, la théorie du contrôle optimal s’inscrit dans la continuité du calcul des variations. Elle est apparue après la seconde guerre mondiale, répondant à des besoins pratiques de guidage, notamment dans le domaine de l’aéronautique et de la dynamique du vol. Historiquement, la théorie du contrôle optimal est très liée à la mécanique classique, en particulier aux principes variationnels de la mécanique (principe de Fermat, de Huygens, équations d’Euler-Lagrange). Le point clé de cette théorie est le principe du maximum de Pontryagin, formulé par L. S. Pontryagin en 1956, qui donne une condition nécessaire d’optimalité et permet ainsi de calculer les trajectoires optimales. Les points forts de la théorie ont été la découverte de la méthode de programmation dynamique, l’introduction de l’analyse fonctionnelle dans la théorie des systèmes optimaux, la découverte des liens entre les solutions d’un problème de contrôle optimal et des résultats de la théorie de stabilité de Lyapunov. Plus tard sont apparues les fondations de la théorie du contrôle stochastique et du filtrage de systèmes dynamiques, la théorie des jeux, le contrôle d’équations aux dérivées partielles. Notons que l’allure des trajectoires optimales dépend fortement du critère d’optimisation. Par exemple pour réaliser un créneau et garer sa voiture, il est bien évident que la trajectoire suivie diffère si on réalise l’opération en temps minimal (ce qui présente un risque) ou bien en minimisant la quantité d’essence dépensée. Le plus court chemin entre deux points n’est donc pas forcément la ligne droite. En 1638, Galilée étudie le problème suivant : déterminer la courbe sur laquelle une bille roule, sans vitesse initiale, d’un point A à un point B, avec un temps de parcours minimal, sous l’action de la pesanteur (toboggan optimal). C’est le fameux problème de la brachistochrone (du grec brakhistos, “le plus court”, et chronos, “temps”). Galilée pense (à tort) que la courbe cherchée est l’arc de cercle, mais il a déjà remarqué que la ligne droite n’est pas le plus court chemin en temps. En 1696, Jean Bernoulli pose ce problème comme un défi aux mathématiciens de son époque. Il trouve lui-même la solution, ainsi que son frère Jacques Bernoulli, Newton, Leibniz et le marquis de l’Hospital. La solution est un arc de cycloïde commençant par une tangente verticale. Ce résultat a motivé le développement de la théorie du calcul des variations, devenue, plus tard, la théorie du contrôle optimal (pour plus de détails sur l’histoire du problème de la brachistochrone). 

<br>

**Contrôle optimal moderne et applications.** On considère que la théorie moderne du contrôle optimal a commencé dans les années 50, avec la formulation du principe du maximum de Pontryagin, qui généralise les équations d’Euler-Lagrange du calcul des variations. Dès lors, la théorie a connu un essor spectaculaire, ainsi que de nombreuses applications. De nos jours, les systèmes automatisés font complètement partie de notre quotidien (nous en sommes souvent inconscients), ayant pour but d’améliorer notre qualité de vie et de faciliter certaines tâches : système de freinage ABS, assistance à la conduite, servomoteurs, thermostats, régulation hygrométrique, circuits frigorifiques, contrôle des flux routiers, ferroviaires, aériens, boursiers, fluviaux, barrages EDF, photographie numérique, filtrage et reconstruction d’images, lecteurs CD et DVD, réseaux informatiques, moteurs de recherche sur internet, circuits électriques, électroniques, télécommunications en général, contrôle des procédés chimiques, raffinage pétrolier, chaînes industrielles de montage, peacemakers et autres systèmes médicaux automatisés, opérations au laser, robotique, satellites, guidages aérospatiaux, bioréacteurs, distillation, ... La liste est infinie, les applications concernent tout système sur lequel on peut avoir une action, avec une notion de rendement optimal.