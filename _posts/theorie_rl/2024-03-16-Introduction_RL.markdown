---
layout: post
title:  "Introduction à l'apprentissage par renforcement profond"
date:   2024-03-16 16:34:45 +0100
categories: deep_rl
---
<link rel="stylesheet" href="https://picorba.github.io/Rapport-veille-technologique/assets/css/theme_dark.css">
<div class="texte">
Voici l'article sur l'introduction au reinforcement learning (RL) et au Deep Reinforcement Learning (DRL).<br>
Cet article est destiné à poser les bases théoriques nécéssaires à la compréhension et l'utilisation de ces méthode d'apprentissage. Si vous êtes déjà familier avec ce type d'apprentissage vous pouvez directement passer à l'article suivant.<br>

<img src="https://picorba.github.io/Rapport-veille-technologique/assets/images/schema_rl.jpg" alt="Schema sur le fonctionnement du RL"><br>
https://medium.com/ai%C2%B3-theory-practice-business/reinforcement-learning-part-1-a-brief-introduction-a53a849771cf

<br>
L'apprentissage par renforcement est une méthode d'apprentissage en IA qui consiste à voir l'IA comme un agent qui va prendre des décisions (action) qui vont affecter son environnement qui lui transmettra à l'agent son nouvel état ainsi qu'une récompense (positive ou négative). L'agent décide de prendre une action selon une politique.

<img src="https://picorba.github.io/Rapport-veille-technologique/assets/images/cartole.png" alt="CartPole de gym"><br>

Cette image est une capture d'écran de l'environnement CartPole basique dans le RL car facilement utilisable avec python et gym. A chaque étape le robot décide de se déplacer à droite ou à gauche selon sa policy, et en fonction le bras tombe plus ou moins et sa nouvelle position est donné en observation à l'agent. Un exemple de récompense basique serait de donner à l'agent une récompense positive à chaque step ou il reste en vie. Nous allons voir dans l'article suivant un exemple d'algorithmes de Rl/DRL avec la Q Table et Deep Q table.

</div>