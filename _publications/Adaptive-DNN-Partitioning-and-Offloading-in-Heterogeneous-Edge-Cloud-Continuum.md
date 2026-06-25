---
title: "Adaptive DNN Partitioning and Offloading in Heterogeneous Edge-Cloud Continuum"
collection: publications
category: conferences
permalink: /publication/Adaptive-DNN-Partitioning-and-Offloading-in-Heterogeneous-Edge-Cloud-Continuum
excerpt: 'This paper presents an adaptive framework for dynamically partitioning DNN inference across heterogeneous edge, fog, and cloud devices. Evaluated on a physical testbed using VGG16, AlexNet, and MobileNetV2, the framework reduced energy consumption by 27.09–35.82% and end-to-end latency by 6.34–22.92% compared with static partitioning. The work was based on our masters thesis and was submitted and accepted in the 21st International Conference on Availability, Reliability and Security (ARES 2026) Workshop on Security, Availability, and Fault-Tolerance in Edge AI Systems, held August 24 – 27, 2026 in Linköping, Sweden.'
date: 2026-05-10
#venue: 'Journal 1'
#slidesurl: 'https://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://akuien.github.io/files/Adaptive DNN Partitioning and Offloading in Heterogeneous Edge-Cloud Continuum.pdf'
#bibtexurl: 'https://academicpages.github.io/files/bibtex1.bib'
citation: 'Deng, A. A., Butkus, E., Lapkovskis, A., & Donta, P. K. (2026). Adaptive DNN Partitioning and Offloading in Heterogeneous Edge-Cloud Continuum. arXiv preprint arXiv:2605.09623.'
---
Abstract - In recent years, the use of artificial intelligence on resourceconstrained IoT devices has grown significantly. However, existing approaches to DNN partitioning and offloading across the edge-cloud continuum typically rely on static methods that ignore runtime dynamics. Furthermore, they are often evaluated in simulated environments rather than on real hardware. To address this gap, we propose a framework that dynamically splits neural network layers across the heterogeneous continuum. The framework profiles the model at startup, measures network link conditions between nodes, and periodically re-evaluates the partition to adapt to environmental changes. We created a physical testbed comprising a Raspberry Pi edge device, a laptop fog, and a highperformance desktop PC as the cloud. We evaluated the framework over three widely adopted convolutional neural networks: VGG16, AlexNet, and MobileNetV2. Our results show that the framework achieves reductions in energy and end-to-end latency of 27.09–35.82% and 6.34–22.92%, respectively, compared to a static partitioning baseline. These findings confirm the superiority of adaptive to static partitioning.
