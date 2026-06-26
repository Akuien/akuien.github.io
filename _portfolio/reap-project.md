---
title: "REAP-Adaptive AI Task Partitioning and Offloading Framework"
excerpt: "An adaptive AI task partitioning and offloading framework for distributed DNN inference across Raspberry Pi, laptop, and GPU desktop nodes, optimizing energy consumption and latency in a heterogeneous end-edge-cloud environment. [GitHub repo](https://github.com/Akuien/DNN-partitioning-and-Oflloading-framework-REAP)<br/><img src='/images/static_baseline_500x300.png'>"

collection: portfolio
---

REAP is an energy-aware framework that dynamically partitions deep neural network inference across a Raspberry Pi, edge laptop, and GPU cloud node. It evaluates runtime latency, network conditions, and energy consumption to select efficient model split points and adapt them when conditions change. The framework supports VGG-16, AlexNet, and MobileNetV2 and was validated on a physical three-node edge–cloud testbed. I personally contributed in the design and development of the 3-tier partitioning and offloading algorithm.

Technologies: Python, PyTorch, Torchvision, ZeroMQ, NumPy, PyYAML, NVIDIA NVML, Intel RAPL, Linux, Raspberry Pi, GPU computing, and Tailscale.
