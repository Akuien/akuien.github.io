---
title: "Adaptive AI Task Partitioning and Offloading in Heterogeneous EdgeCloud Networks"
collection: publications
category: manuscripts
permalink: /publication/master-thesis
excerpt: 'This master’s thesis presents REAP, a runtime energy-aware framework for dynamically partitioning and offloading deep neural network inference across heterogeneous edge, fog, and cloud devices. The framework profiles computation and network conditions, evaluates possible model split points, and periodically adapts the execution strategy based on latency, communication overhead, and energy consumption. Evaluated on a physical three-node testbed using VGG-16, AlexNet, and MobileNetV2, REAP reduced total energy consumption by up to 35.82% and end-to-end latency by up to 22.92% compared with static partitioning.'
#date: 2015-10-01
#venue: 'Journal 1'
#slidesurl: 'https://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://akuien.github.io/files/FULLTEXT01.pdf'
citation: 'A. A. Deng and E. Butkus, “Adaptive AI task partitioning and offloading in heterogeneous edge-cloud networks: REAP—Runtime Energy-Aware Adaptive Partitioning and Offloading Framework,” M.Sc. thesis, Dept. Comput. Syst. Sci., Stockholm Univ., Stockholm, Sweden, 2026.'
---

In recent years, the use of AI on resource-constrained IoT devices has grown significantly. However, most existing solutions for partitioning and offloading AI inference tasks across edge-cloud networks rely on static methods that are fixed before deployment and do not adapt to changes during runtime. Additionally, many of these solutions are evaluated in simulated environments rather than on real hardware. This thesis addresses this gap by designing and implementing an adaptive partitioning and offloading
framework that dynamically determines where to split a neural network’s layers across a three-node heterogeneous network. The framework was built in Python and tested on a physical testbed consisting of a Raspberry Pi 5 edge device, a laptop fog, and a high-performance GPU desktop PC as the cloud. Three CNN models were used for evaluation: VGG-16, AlexNet and MobileNetV2. The framework profiles the model at startup, measures the network link conditions between nodes, and periodically re-evaluates
the partition to react to changes in the environment. Results show that compared to a static partitioning baseline, the framework achieved energy reductions of 35.82% for VGG-16, 35.70% for AlexNet and 27.09% for MobileNetV2. End-to-end latency was also reduced by 6.34%, 22.92% and 14.20%, respectively. These results show that adaptive partitioning can reduce energy consumption on resource-constrained devices while maintaining acceptable latency in a real heterogeneous edge-cloud network.
