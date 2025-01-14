---
title: "A Latent Adversarial Cauchy-Schwarz Autoencoder for Medical Image Segmentation"
collection: publications
category: conferences
permalink: /publication/conference2
excerpt: ''
date: 2023-02-03
venue: 'IEEE International Conference On Bioinformatics And Biomedicine'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10385981/'
citation: 'Zhang J, Gao J, Chen Z, et al. A Latent Adversarial Cauchy-Schwarz Autoencoder for Medical Image Segmentation[C]//2023 IEEE International Conference on Bioinformatics and Biomedicine (BIBM). IEEE, 2023: 3962-3967.'
---

Medical image segmentation plays a vital role in clinical diagnosis. However, previous methods cannot handle intrinsic ambiguities in extracting deep semantics of medical images. Moreover, they neglect fruitful semantic information in segmentation maps. To address the challenges, a latent adversarial Cauchy-Schwarz autoencoder is proposed, which defines image segmentation as a cross-modal translation task from medical images to segmentation maps. Specifically, a probabilistic graph model is defined to fit the conditional distribution of the image translation between modalities, which leverages the Cauchy-Schwarz divergence to alleviate approximation errors caused by ambiguities in extracting deep semantics. Then, a novel numerical solution is derived to optimize the probabilistic graph model, which explores semantics in segmentation maps to facilitate the segmentation. Afterwards, a dual-flow architecture is proposed with an adversarial encoding-decoding paradigm to implement the numerical solution. Finally, extensive experiments in two medical scenarios illustrate that the proposed method achieves the state-of-the-art performance compared with nine baseline methods.
