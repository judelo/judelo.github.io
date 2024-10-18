---
layout: page
title: "Projet Benchopt de débruitage d’images"
header-img: "img/backBlue.png"
---

#### Contexte :

Le débruitage d’images est l'une des tâches les plus centrales en restauration d'image. Il consiste à estimer une image inconnue $x$ à partir d'une observation bruitée $y=x+\epsilon$, où $\epsilon$ est la réalisation d'un bruit (qu'on supposera de loi connue ici). 

Plusieurs méthodes ont été développées pour cette tâche depuis 30 ans, et il est important de les comparer  selon des critères variés, tant en termes de qualité des résultats obtenus que de coût et complexité de calcul.

Benchopt est une librairie Python conçue pour faciliter l’évaluation et la comparaison d’algorithmes dans des benchmarks reproductibles. L’objectif de ce projet est d’utiliser Benchopt pour mettre en place un premier benchmark reproductible pour quelques méthodes emblématiques de débruitage d’images.

#### Objectif du projet :

Vous devrez :
- Mettre en place un benchmark reproductible sur [Benchopt](https://benchopt.github.io/) en utilisant les méthodes de débruitage suivantes :
  1. **TV-L2** : voir le cours et le [TP](http://nbviewer.org/github/storimaging/Notebooks/blob/main/Restoration/Variational_approaches_for_image_restoration.ipynb) 
  2. **NLmeans** : [Article IPOL](https://www.ipol.im/pub/art/2011/bcm_nlm/) et [TP](http://nbviewer.org/github/storimaging/Notebooks/blob/main/Restoration/Non_Local_Means_for_denoising.ipynb)
  3. **FFDNet** : [Lien vers l'article](https://www.ipol.im/pub/art/2019/231/) et [TP](http://nbviewer.org/github/storimaging/Notebooks/blob/main/Restoration/Networks_for_image_denoising.ipynb)
  4. **DRUNet** : [Lien vers le code sur Github](https://github.com/cszn/DPIR)

- On utilisera les **métriques de qualité** suivantes :
  - **PSNR** (Peak Signal-to-Noise Ratio)
  - **SSIM** (Structural Similarity Index)
  
- Ainsi que des **métriques de performance computationnelle** :
  - **Temps d’exécution**.
  - **Utilisation de la mémoire**.
  - **Puissance de calcul en teraflops** nécessaire pour exécuter chaque méthode.
  - **Coût d’entraînement** pour les méthodes basées sur des réseaux de neurones (FFDNet, DRUNet).

#### Etapes du projet :

1. **Familiarisation avec Benchopt** :
   - Comprendre comment structurer un benchmark reproductible.

2. **Intégration des méthodes de débruitage** :
   - Adapter les implémentations des méthodes ci-dessus pour les intégrer au benchmark.
   
3. **Mise en place du benchmark** :
   - Choisir une base d'images de test
   - Configurer Benchopt pour exécuter les méthodes choisies sur cet ensemble d'images bruitées.
   - Définir les métriques de comparaison (PSNR, SSIM, etc.).

4. **Analyse des résultats** :
   - Analyser les compromis entre qualité de débruitage et efficacité computationnelle (notamment pour les méthodes utilisant des réseaux de neurones).