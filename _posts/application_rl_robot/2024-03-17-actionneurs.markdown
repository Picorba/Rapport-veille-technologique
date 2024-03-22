---
layout: post
title:  "DRL dans les Actionneurs"
date:   2024-03-17 18:34:50 +0100
categories: applicationss
---
<link rel="stylesheet" href="https://picorba.github.io/Rapport-veille-technologique/assets/css/theme_dark.css">
<div class="texte">
Dans cette partie nous allons voir comment une IA entrainée par DRL peut directement interagir avec les actionneurs pour controler un robot.Nous allons voir deux exemples un en simulation et un autre qui a pu être réellement déployer.
</div>

# Entrainement d'une IA par DRL pour jouer à TrackMania
 
 <div class="texte">
 Les vidéos de Yosh (liens dans la page Méthode) montre la création d'une IA qui joue à trackMania (un jeu de course sur ordinateur). La dernière est toute récente et explique le processus qu'il a mit en place pour entrainer une IA à conduire sur des tuyaux. Au travers de ces vidéos on remarque que tout d'abord il faut énormèment d'itération pour bien entrainer une IA alors que son IA n'a que choix possible : accélérer, freiner, tourner à droite ou à gauche (elle controle aussi en intensité). Cette série de vidéo est très bien pour comprendre des concepts fondamentaux liés à l'apprentissage par renforcement profond comme l'émérgence de comportement imprévu, par exemple sur une des vidéos l'IA pour aller plus vite avait appris que dans les virages à 90 degrés elle devait faire un petit saut ce qui à court terme faisait gagner du temps, mais à long terme en perdait. Il a fallu mettre en place à ce moment un nouveau paramètres en entrée.<br>

</div>

<iframe width="640" height="400" src="https://www.youtube.com/watch?v=kojH8a7BW04" frameborder="0" allowfullscreen></iframe>

 <div class="texte">
<br>
Source : [Yosh sur youtube](https://www.youtube.com/@yoshtm)


</div>

# Controle d'un ASV simple 

<div class="texte">
Ce papier de recherche est un peu moins intéréssant de par son support, mais ce qu'ils ont fait est impressionant. Beaucoup d'algorithmes que nous avons discuté jusqu'ici ne fonctionnait que en simulation, car une erreur dans la réalité peut vite coutait chère, il faut donc prendre beaucoup de précautions. Mais içi cette équipe de chercheurs à réussi à déployer un ASV (Autonomaus Surface Vessel, un bateau drone) simple et lui a appris à reproduire des trajectoires simples par du DRL. Il lui ont fait prendre en entrée le Yaw Pitch Roll du drone et il devait suivre une trajectoire précédemment calculée.<br>

 <img src="https://picorba.github.io/Rapport-veille-technologique/assets/images/asv.png" alt="ASV"><br>

Source : Deep Reinforcement Learning Based Tracking Control of an
Autonomous Surface Vessel in Natural Waters Wei Wang1,2,,
 Xiaojing Cao3,, Alejandro Gonzalez-Garcia2,4, Lianhao Yin1, Niklas Hagemann2,
Yuanyuan Qiao2,3, Carlo Ratti2, and Daniela Rus
</div>

[DRL pour les systèmes multi-agents](/Rapport-veille-technologique/applicationss/2024/03/17/multiagent.html)
