---
layout: post
title:  "Planification de trajectoire"
date:   2024-03-17 18:34:50 +0100
categories: applicationss
---
<link rel="stylesheet" href="https://picorba.github.io/Rapport-veille-technologique/assets/css/theme_dark.css">
<div class="texte">
Afin de déplacer un robot, il faut planifier sa trajectoire, mais celle ci peut rencontrer des obstacles ou alors nécéssiter une grande réflexion comme dans le cas d'un labyrhinte. La cartographie et la localisation simultanées (SLAM en anglais) est un problème courant en robotique qui consiste pour un robot à construire et améliorer en même temps une carte de son environnement. Je vais içi expliquer un algorithme que j'ai déjà pu impplémenter moi même lors de mon stage en laboratoire en IA.<br><br>
Le Projet était de controler un bras robotique en utilisant de du DRL pour la génération de trajectoire. Pour ce faire l'IA prenait en entrée l'état du robot et de la destination, ainsi que d'un objet à éviter (de taille  fixe) et devait générer des poids qui servaient à la génération de la trajectoire. Ensuite ces poids étaient utilisée par les Dynamical Movement Primitives pour générer la trajectoire de la main du robot et une récompense était attribué selon si le robot touchait ou non l'obstacle.<br><br>
Les Dynamical Movement Primitives (DMP) sont une méthode d'apprentissage de mouvements développée pour la robotique et la biomécanique. Elles permettent de générer des trajectoires de mouvement fluides et adaptatives en imitant les caractéristiques des mouvements observés dans la nature. Les DMP décomposent les mouvements en primitives dynamiques, qui sont des fonctions non linéaires paramétrées, et utilisent des systèmes dynamiques pour réguler leur exécution en temps réel. Cela les rend particulièrement utiles pour la génération de mouvements précis et naturels dans des environnements variables et pour l'apprentissage de tâches complexes de manipulation et de locomotion. Voici un schéma qui illustre l'intêret des poids dans cette méthodes.

 <img src="https://picorba.github.io/Rapport-veille-technologique/assets/images/dmp.png" alt="Graphique réussité des LLMs sur le benchmark SWE-bench"><br>

<br> <br>
Source : Survey of Deep Reinforcement Learning for Motion
Planning of Autonomous Vehicles Szilárd Aradi Feb 2022<br>
https://arxiv.org/pdf/2302.09120.pdf <br>
https://arxiv.org/ftp/arxiv/papers/2307/2307.07296.pdf <br>
https://www.reddit.com/r/reinforcementlearning/comments/inspcf/learning_about_slam_and_reinforcement_learning/
</div>