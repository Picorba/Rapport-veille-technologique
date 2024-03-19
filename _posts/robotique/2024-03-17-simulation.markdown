---
layout: post
title:  "Simulation"
date:   2024-03-17 18:34:50 +0100
categories: Robotics
---
<link rel="stylesheet" href="https://picorba.github.io/Rapport-veille-technologique/assets/css/theme_dark.css">

# L'Intérêt de la Simulation en Robotique

La simulation en robotique présente plusieurs avantages significatifs :

## 1. Réduction des Coûts

- Les prototypes physiques peuvent être coûteux à concevoir, à fabriquer et à tester.
- La simulation permet de réduire ces coûts en évitant la nécessité de construire des prototypes physiques pour tester les algorithmes et les comportements des robots.

## 2. Sécurité

- Les robots peuvent être dangereux lorsqu'ils sont en phase de développement, surtout s'ils manipulent des charges lourdes ou interagissent avec des environnements complexes.
- La simulation offre un environnement sûr pour tester le comportement des robots sans risquer des dommages matériels ou des blessures.

## 3. Accélération du Développement

- Les itérations de conception peuvent être effectuées beaucoup plus rapidement en simulation qu'en construisant et en testant des prototypes physiques.
- Les erreurs peuvent être identifiées et corrigées plus rapidement, accélérant ainsi le processus de développement.

## 4. Flexibilité

- Les simulations offrent une grande flexibilité pour tester différents scénarios et conditions environnementales.
- Les paramètres peuvent être facilement ajustés pour évaluer le comportement du robot dans différentes situations.

## 5. Analyse Approfondie

- Les simulations permettent une analyse approfondie du comportement du robot, notamment en enregistrant des données détaillées sur ses mouvements, ses interactions et ses performances.
- Ces données peuvent être utilisées pour optimiser les algorithmes de contrôle et les stratégies de planification.

# Outils principaux :

La robotique est un domaine très complexe et complet qui mélange hard/middle et software. Je n'ai pas la prétention de tous lister içi mais j'aimerai mentionner ici certains software notable utilisé en robotique.

## 1. ROS/Gazebo :
ROS est un SDK (Software Development Kit) de Open Robotics très utilisé en robotique permettant le contrôle de robot aussi bien en simulation qu'en réalité. Il est soutenu par une très grande communauté ce qui permet de trouver. Open Robotics propose aussi un logiciel de simulation 3D d'environement Gazebo (Qui est en train de changer de nom pour les versions récentes) et qui permet de simuler des environnement complexes et d'ainsi entrainer son robot dans le cadre du Reinforcement Learning.
## 2. Unity/ML-Agents
Certes Unity est à la base un moteur de jeu vidéo multiplateforme, mais il permet aussi la simulation réaliste d'environnement complexe et des modules tel que [Unity Robotics](https://unity.com/solutions/automotive-transportation-manufacturing/robotics). L'avantage de Unity est qu'il est assez facile de prendre en main et permet à des étudiants ou travalleurs venant du milieu de l'informatique de passer facilement au monde de la robotique au travers d'un outil connu. ML-Agent est un package Unity qui permet d'entrainer assez facilement des agents par renforcement et ce module est applicable au monde de la robotique.


Sources :
https://www.linkedin.com/advice/0/how-can-you-use-unity-blender-v-rep-ros-skills-ros