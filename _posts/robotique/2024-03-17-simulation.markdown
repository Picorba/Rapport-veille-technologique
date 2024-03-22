---
layout: post
title:  "Simulation"
date:   2024-03-17 18:34:50 +0100
categories: Robotics
---
<link rel="stylesheet" href="https://picorba.github.io/Rapport-veille-technologique/assets/css/theme_dark.css">

# L'Intérêt de la Simulation en Robotique 

<div class="text">
La simulation permet de tester les algorithmes de contrôle, les trajectoires et les interactions robot-environnement dans des environnements virtuels, offrant ainsi une plateforme sûre et flexible pour l'expérimentation. De plus, elle facilite la formation des opérateurs et des utilisateurs des robots, améliorant ainsi leur efficacité et leur sécurité.

De plus, on prévoit une expansion des "Digital Twins" dans l'industrie à l'avenir. Les "Digital Twins" sont des répliques numériques des systèmes qui permettront aux industriels de mieux comprendre et optimiser leurs processus. Ils faciliteront le développement de nouvelles fonctionnalités et l'identification de leur utilité, tout en réduisant les temps d'arrêt des systèmes. Cependant, le principal obstacle à cette technologie réside dans la montée en puissance des récentes cyberattaques. <br>

Source : https://blog.3ds.com/fr/brands/delmia/quels-sont-les-avantages-de-la-simulation-robotique/
</div>

<img src="https://picorba.github.io/Rapport-veille-technologique/assets/images/digital_twin.png" alt="Evolution du marché des digitals twins"><br>
Source : https://www.ptc.com/fr/industry-insights/digital-twin
<br>

# Outils principaux : 

<div class="text">

La robotique est un domaine très complexe et complet qui mêle matériel, logiciel et intermédiaire. Je n'ai pas la prétention de tout énumérer ici, mais j'aimerais mentionner certains logiciels notables utilisés en robotique.
</div>

## 1. ROS/Gazebo :

<div class="text">
ROS est un SDK (Software Development Kit) développé par Open Robotics et largement utilisé en robotique pour le contrôle des robots, que ce soit en simulation ou en réalité. Il est soutenu par une très grande communauté, ce qui facilite son utilisation. Open Robotics propose également un logiciel de simulation 3D d'environnement appelé Gazebo (qui est en train de changer de nom pour les versions récentes), permettant de simuler des environnements complexes et d'entraîner ainsi les robots dans le cadre du Reinforcement Learning.
</div>

## 2. Unity/ML-Agents 

<div class="text">
Certes, Unity est à la base un moteur de jeu vidéo multiplateforme, mais il permet également la simulation réaliste d'environnements complexes et l'utilisation de modules tels que [Unity Robotics](https://unity.com/solutions/automotive-transportation-manufacturing/robotics). L'avantage de Unity est qu'il est assez facile à prendre en main, ce qui permet aux étudiants ou aux professionnels du domaine de l'informatique de passer facilement au monde de la robotique à travers un outil familier. ML-Agent est un package Unity qui permet d'entraîner assez facilement des agents par renforcement, et ce module est applicable au monde de la robotique."
</div>

## 3.Autres :

 <div class="text">
Si vous êtes intéressés pour faire un projet, voici aussi d'autres logiciels de simulation qui sont utilisables pour simuler et entraîner des robots (certains avec ROS). Malheureusement, je ne connais pas les avantages et inconvénients de chacun, donc à vous de trouver celui qui conviendra à votre projet :

- Blender
- V-REP (CoppeliaSim maintenant)
- Unreal Engine

Voici un [article](https://www.linkedin.com/advice/0/how-can-you-use-unity-blender-v-rep-ros-skills-ros) pour lier ROS avec Unity, Blender et V-REP.

</div>