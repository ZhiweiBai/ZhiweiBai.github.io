# FAI Seminar 讲座信息

## 讲座标题

**中文：** 理解 Adam 动力学：退化方向中的加速与二次方向中的损失尖峰

**English:** Understanding Adam Dynamics: Acceleration in Degenerate Directions and Loss Spikes in Quadratic Directions

## 讲座摘要

Adam is one of the most widely used adaptive optimizers in deep learning, yet a unified understanding of why it accelerates optimization in some settings and becomes unstable in others is still missing. This talk presents two ICML 2026 works that study these phenomena through the geometry of the loss landscape.

The first work studies Adam dynamics on highly degenerate polynomials. In this highly degenerate landscape, gradient descent and Momentum exhibit power-law convergence, while Adam achieves faster linear convergence. The key mechanism is a decoupling between Adam's second-moment estimator and the instantaneous squared gradient. This decoupling compensates for the vanishing curvature in degenerate directions, allowing the effective curvature to be lifted to and stabilized at a constant scale, which leads to linear convergence. The second work studies loss spikes in quadratic directions. We show that the delayed response of the adaptive preconditioner can drive the preconditioned effective curvature toward or beyond the stability boundary; pronounced spikes arise when unstable directions are sufficiently activated. The parameter \(\beta_2\) controls the response time and the severity of this instability, while gradient-directional curvature provides a useful predictor of spikes. We support the proposed mechanisms with experiments on simplified models, neural networks, and Transformers.


## 讲者信息

**白志威（Zhiwei Bai）**

白志威，上海交通大学应用数学方向 2022 级博士生，指导老师为张耀宇教授和许志钦教授。主要从事 Deep Learning Theory 研究，尤其关注通过“现象驱动”的方法理解深度学习模型实际训练中的复杂性。他致力于追问“什么是真正的理解”，并尝试从第一性原理的角度理解深度神经网络的训练动力学，包括过参数下的泛化与自适应优化。研究范围涵盖神经网络的损失景观、凝聚现象、隐式正则化、Adam 动力学以及大语言模型的推理偏好。

## 相关论文

1. **Zhiwei Bai**, Jiajie Zhao, Zhangchen Zhou, Zhi-Qin John Xu, and Yaoyu Zhang. “Towards Understanding Adam Convergence on Highly Degenerate Polynomials.” *International Conference on Machine Learning (ICML)*, 2026 (**Spotlight**). [arXiv:2603.09581](https://arxiv.org/abs/2603.09581)

2. **Zhiwei Bai**, Zhangchen Zhou, Jiajie Zhao, Xiaolong Li, Zhiyu Li, Feiyu Xiong, Hongkang Yang, Yaoyu Zhang, and Zhi-Qin John Xu. “Adaptive Preconditioners Trigger Loss Spikes in Adam.” *International Conference on Machine Learning (ICML)*, 2026. [arXiv:2506.04805](https://arxiv.org/abs/2506.04805)

## 讲者照片

![9350f6ba3e60d7c6f70825d4d0416e88](https://cdn.jsdelivr.net/gh/ZhiweiBai/images_for_typora@main/9350f6ba3e60d7c6f70825d4d0416e88.png)