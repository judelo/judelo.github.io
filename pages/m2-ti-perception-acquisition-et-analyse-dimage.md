---
layout: page
title: "M2 MM – Perception, acquisition et analyse d’images (PERCEP)"
header-img: "img/backBlue.png"
---

### Cours Perception, acquisition et analyse d’images

* Acquisition d’images : [Transparents](http://w3.mi.parisdescartes.fr/~jdelon/enseignement/cours_image_m2/cours_perception_acquisition.pdf)
* Images et Radiométrie :  [Transparents](http://w3.mi.parisdescartes.fr/~jdelon/enseignement/cours_image_m2/COURS_radiometrie_master.pdf)  et [poly](http://w3.mi.parisdescartes.fr/~jdelon/enseignement/cours_image_m2/radiometrie.pdf).
* Couleur et transfert de couleur : [Transparents](http://w3.mi.parisdescartes.fr/~jdelon/enseignement/cours_image_m2/COURS_couleur_master.pdf)

### TP  en ligne sous Python 3 

* [Image et radiométrie](https://nbviewer.jupyter.org/github/judelo/notebooks/blob/master/python/TP_Radiometrie.ipynb)
* [Couleur et perception](https://nbviewer.jupyter.org/github/judelo/notebooks/blob/master/python/TP_color.ipynb) 
* [Transfert de couleur](https://nbviewer.jupyter.org/github/judelo/notebooks/blob/master/python/TP_color_transfer.ipynb)

### TP  en ligne sous Matlab / Scilab

* [Images et radiomètrie](http://w3.mi.parisdescartes.fr/~jdelon/enseignement/tp_image/org/TP_radiometrie.html)
* [Couleur et perception](http://w3.mi.parisdescartes.fr/~jdelon/enseignement/tp_image/org/TP_perception.html)
* [Transfert de couleur](http://w3.mi.parisdescartes.fr/~jdelon/enseignement/tp_image/org/TP_color_transfer.html)

### Validation du cours et projets 

**Projets**

Chaque projet consiste en l’étude approfondie d’un article de la littérature. A la fin du projet, chaque étudiant doit rendre ses codes complets et commentés, un rapport sur le projet, et présenter son travail lors d’une soutenance orale. Le rapport, rédigé en LaTeX, devra contenir :

* Une introduction expliquant et illustrant le problème.
* Une explication détaillée des algorithmes et codes et leur interprétation.
* Plusieurs exemples d’application.
* Attributions des sujets :
    * Xavier Florez de la Colina, Zie Ouattara : projet 9
    * Diala Hawat, Mariem Abaach et Mehdi Boussaa : projet 3
    * Valentin Dumas,  Adrien Monjean : projet 5
    * Naima Bessaoud : projet 6
    * Polina Arsenteva, Camille Petri : projet 2
    * Gninwoyo Eric Hermann Coulibaly : projet 7 ou 8

**Sujets**

1. [Texture Synthesis Using Convolutional Neural Networks](https://papers.nips.cc/paper/5633-texture-synthesis-using-convolutional-neural-networks.pdf) (code [ICI](https://github.com/leongatys/DeepTextures))   (**)
2. [Image Style Transfer Using Convolutional Neural Networks](https://zpascal.net/cvpr2016/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf)  (code [ICI](https://github.com/leongatys/PytorchNeuralStyleTransfer)).  (**)
3. [A Wasserstein-type distance in the space of Gaussian Mixture Models](https://hal.archives-ouvertes.fr/hal-02178204) (code [ICI](https://github.com/judelo/gmmot)) (**)
4. [Synthesizing and Mixing Stationary Gaussian Texture Models](https://hal.archives-ouvertes.fr/hal-00816342/) (**) (code [ICI](https://github.com/gpeyre/2013-SIIMS-gaussian-textures))
5. [Simulated exposure fusion](http://www.ipol.im/pub/pre/279/preprint.pdf) (**) (code et demo en ligne [ICI](https://www.ipol.im/pub/pre/279/))
6. [Image segmentation by Mean-shift](https://www.ipol.im/pub/art/2019/255/article_lr.pdf) (*) (code [ICI](https://www.ipol.im/pub/art/2019/255/))
7. [An algorithm for Gaussian texture inpainting](http://www.ipol.im/pub/art/2017/198/) (*)
8. Patch-based image inpainting, en se basant sur le TP [suivant](http://w3.mi.parisdescartes.fr/~jdelon/enseignement/tp_image/org/TP_inpainting.html) (*)
9. [Study of the Principal Component Analysis Method for the Correction of Images Degraded by Turbulence](https://www.ipol.im/pub/art/2018/47/) (*)

Les projets 1 et 2 demandent d’être à l’aise avec le fait de manipuler des réseaux de neurones. On pourra utiliser un outil en ligne pour expérimenter. Les projets 3,4 et 7 sont plus théoriques que les autres, mais une partie pratique sera également demandée.

Voir également :  [rédiger votre rapport de projet en LaTeX](latex.md)