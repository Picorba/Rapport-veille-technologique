---
layout: post
title:  "Introduction à l'apprentissage par renforcement profond"
date:   2024-03-16 16:34:45 +0100
categories: deep_rl
---
<link rel="stylesheet" href="https://picorba.github.io/Rapport-veille-technologique/assets/css/theme_dark.css">
<div class="texte">
Bienvenue à l'article d'introduction sur le reinforcement learning (RL) et le Deep Reinforcement Learning (DRL). Ce texte vise à établir les bases théoriques indispensables pour comprendre et utiliser ces méthodes d'apprentissage. Si vous êtes déjà familier avec ce type d'apprentissage, vous pouvez passer directement à l'article suivant.<br> <br>

<img src="https://picorba.github.io/Rapport-veille-technologique/assets/images/schema_rl.jpg" alt="Schema sur le fonctionnement du RL"><br> <br>
https://medium.com/ai%C2%B3-theory-practice-business/reinforcement-learning-part-1-a-brief-introduction-a53a849771cf

<br>
L'apprentissage par renforcement est une technique d'apprentissage en intelligence artificielle qui envisage l'IA comme un agent prenant des décisions (actions) influençant son environnement. L'environnement retourne à l'agent son nouvel état ainsi qu'une récompense, positive ou négative. L'agent choisit ses actions en suivant une politique.<br>

<img src="https://picorba.github.io/Rapport-veille-technologique/assets/images/cartole.png" alt="CartPole de gym"><br>
 <br>
L'image ci-dessus est une capture d'écran de l'environnement CartPole, une simulation couramment utilisée dans le domaine du Reinforcement Learning (RL) car elle est facilement accessible via Python et la bibliothèque gym. À chaque étape, le robot décide de se déplacer vers la droite ou vers la gauche en fonction de sa politique (policy). En fonction de cette décision, le bras du robot tombe plus ou moins, et sa nouvelle position est renvoyée à l'agent en tant qu'observation. Un exemple de récompense basique serait d'attribuer une récompense positive à l'agent à chaque étape où il reste en vie. Dans l'article suivant, nous explorerons un exemple d'algorithmes de RL/DRL avec la Q-Table et la Deep Q-Table.

</div>