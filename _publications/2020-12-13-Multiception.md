---
title: "Depthwise Multiception Convolution for Reducing Network Parameters without Sacrificing Accuracy"
collection: publications
permalink: /publication/2020-12-13-Multiception
excerpt: 'We proposed a new convolutional method to improve the performance of depthwise separable convolution Code:https://github.com/guoqingbao/Multiception'
date: 2020-12-13
venue: 'The 16th International Conference on Control, Automation, Robotics and Vision'
paperurl: 'https://doi.org/10.1109/ICARCV50220.2020.9305369'
citation: '<b>Guoqing Bao</b>, Manuel B. Graeber, Xiuying Wang (2020). &quot;Depthwise Multiception Convolution for Reducing Network Parameters without Sacrificing Accuracy&quot; <i>International Conference on Control, Automation, Robotics and Vision</i> pp. 747-752, doi: 10.1109/ICARCV50220.2020.9305369'
---
Deep convolutional neural networks have been proven successful in multiple benchmark challenges in recent years. However, the performance improvements are heavily reliant on increasingly complex network architecture and a high number of parameters, which require ever increasing amounts of storage and memory capacity. Depthwise separable convolution (DSConv) can effectively reduce the number of required parameters through decoupling standard convolution into spatial and cross-channel convolution steps. However, the method causes a degradation of accuracy. To address this problem, we present depthwise multiception convolution, termed Multiception, which introduces layer-wise multiscale kernels to learn multiscale representations of all individual input channels simultaneously. We have carried out the experiment on four benchmark datasets, i.e. Cifar-10, Cifar-100, STL-10 and ImageNet32×32, using five popular CNN models, Multiception achieved accuracy promotion in all models and demonstrated higher accuracy performance compared to related works. Meanwhile, Multiception significantly reduces the number of parameters of standard convolution-based models by 32.48 % on average while still preserving accuracy.

[Access full paper here](https://doi.org/10.1109/ICARCV50220.2020.9305369)

Open-source Code in GitHub: [link](https://github.com/guoqingbao/Multiception)

