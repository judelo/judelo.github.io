---
layout: page
title: "Projet transfert de style par OT"
header-img: "img/backBlue.png"
---


#### Contexte :

Le transfert de style est une technique de traitement d'images qui consiste à appliquer les caractéristiques de style d'une image (par exemple, une peinture) à une autre image, tout en conservant son contenu original. Le papier  [Gaussian Optimal Transport for Image Style Transfer](https://arxiv.org/pdf/1905.12828.pdf) de Mroueh propose une approche utilisant le transport optimal (OT) entre des mesures gaussiennes dans un espace latent pour réaliser ce transfert de style. Dans cette méthode, les styles peuvent être mélangés et interpolés via des barycentres de Wasserstein. L’objectif de ce projet est d'étudier et de réimplémenter cette méthode en utilisant des architectures préentraînées disponibles, ainsi que d'expérimenterez certaines variantes.

#### Objectifs du Projet :

1. **Étudier le papier** : [Gaussian Optimal Transport for Image Style Transfer](https://arxiv.org/pdf/1905.12828.pdf) et comprendre les concepts théoriques fondamentaux (transport optimal, mesures gaussiennes, barycentres de Wasserstein).
   
2. **Réimplémenter (en pytorch) la méthode** décrite dans le papier avec un code lisible et simple, on pourra utiliser les architectures d'encodeur/décodeur préentraînées disponibles ici : [Universal Style Transfer](https://github.com/Yijunmaverick/UniversalStyleTransfer?tab=readme-ov-file).

3. **Expérimenter** diverses variantes et extensions de la méthode, notamment :
   - Remplacer le transport optimal entre gaussiennes par un transport entre mélanges de gaussiennes, en vous basant sur le code associé au papier [OT-GMM](https://arxiv.org/abs/1907.05254).
   - Tester d’autres architectures pour les parties encodeur/décodeur, en utilisant des modèles déjà préentraînés, pour observer l'impact sur les résultats du transfert de style.

4. **Analyser les résultats** obtenus avec différentes méthodes et discuter des avantages et inconvénients des différentes approches utilisées.


