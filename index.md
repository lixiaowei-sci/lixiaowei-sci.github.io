# 量子信息科学与人工智能基础知识库

欢迎来到我的个人主页。这里主要整理两条学习与写作主线：

- [量子信息科学](#量子信息科学)：从量子力学形式理论出发，逐步进入量子光学、量子计算、量子精密测量、量子信息理论与量子热力学。
- [人工智能基础](#人工智能基础)：从数学基础出发，逐步整理数据清洗、数据挖掘、深度学习与强化学习。

---

## 快速导航

### 量子信息科学

- [量子力学形式理论](./notes/量子力学形式理论.pdf)
- [量子光学](./notes/qis/quantum-optics.md)
- [量子计算](./notes/qis/quantum-computation.md)
- [量子精密测量](./notes/qis/quantum-precision-measurement.md)
- [量子信息理论](./notes/qis/quantum-information-theory.md)
- [量子热力学](./notes/qis/quantum-thermodynamics.md)

### 人工智能基础

- [数学基础](./notes/ai/math-foundations.md)
- [数据清洗](./notes/ai/data-cleaning.md)
- [数据挖掘](./notes/ai/data-mining.md)
- [深度学习](./notes/ai/deep-learning.md)
- [强化学习](./notes/ai/reinforcement-learning.md)

---

# 量子信息科学

量子信息科学的核心目标，是用量子力学的状态、测量、演化与复合系统结构来理解信息的表示、传输、处理与限制。这里的笔记按照“形式理论 → 物理平台 → 信息处理 → 测量与热力学”的顺序展开。

## 1. 量子力学形式理论

入口：[量子力学形式理论](./notes/qis/quantum-mechanics-formalism.md)

这一部分主要整理量子力学的公理化框架与数学语言，为后续量子信息、量子计算和量子测量打基础。

| 主题 | 链接 | 状态 |
|---|---|---|
| 状态空间与态叠加 | [状态空间](./notes/qis/quantum-mechanics-formalism.md#状态空间) | 更新中 |
| 抽象向量空间 | [向量空间](./notes/qis/quantum-mechanics-formalism.md#抽象向量空间) | 更新中 |
| 对偶空间与内积 | [对偶空间和内积](./notes/qis/quantum-mechanics-formalism.md#对偶空间和内积) | 更新中 |
| 线性算符 | [线性算符](./notes/qis/quantum-mechanics-formalism.md#线性算符) | 更新中 |
| 伴随算符与厄米算符 | [伴随算符与厄米算符](./notes/qis/quantum-mechanics-formalism.md#伴随算符与厄米算符) | 更新中 |
| 本征值、本征态与谱分解 | [谱分解](./notes/qis/quantum-mechanics-formalism.md#本征值本征态与谱分解) | 更新中 |
| 量子态与密度算符 | [密度算符](./notes/qis/density-operator.md) | 更新中 |
| 复合系统与纠缠 | [复合系统](./notes/qis/composite-systems-and-entanglement.md) | 更新中 |
| 量子动力学 | [薛定谔方程与冯诺依曼方程](./notes/qis/quantum-dynamics.md) | 更新中 |
| 开放量子系统 | [主方程与退相干](./notes/qis/open-quantum-systems.md) | 更新中 |
| 量子测量 | [投影测量与 POVM](./notes/qis/quantum-measurement.md) | 更新中 |
| 干涉条纹与探测强度 | [路径信息与干涉消失](./notes/qis/quantum-measurement.md#路径信息与干涉消失) | 更新中 |

推荐阅读顺序：

1. [状态空间](./notes/qis/quantum-mechanics-formalism.md#状态空间)
2. [内积、归一化与标准正交基](./notes/qis/quantum-mechanics-formalism.md#对偶空间和内积)
3. [线性算符与外积表示](./notes/qis/quantum-mechanics-formalism.md#线性算符)
4. [厄米算符与可观测量](./notes/qis/quantum-mechanics-formalism.md#伴随算符与厄米算符)
5. [谱分解与测量结果](./notes/qis/quantum-mechanics-formalism.md#本征值本征态与谱分解)
6. [密度算符](./notes/qis/density-operator.md)
7. [复合系统与纠缠](./notes/qis/composite-systems-and-entanglement.md)
8. [量子测量](./notes/qis/quantum-measurement.md)

---

## 2. 量子光学

入口：[量子光学](./notes/qis/quantum-optics.md)

量子光学研究光场的量子化、光与物质相互作用以及光学平台中的量子态制备、操控和测量。

| 主题 | 链接 | 状态 |
|---|---|---|
| 光场量子化 | [单模与多模光场](./notes/qis/quantum-optics.md#光场量子化) | 计划中 |
| Fock 态、相干态与压缩态 | [典型光场量子态](./notes/qis/quantum-optics.md#典型光场量子态) | 计划中 |
| 光与二能级系统相互作用 | [Jaynes--Cummings 模型](./notes/qis/jaynes-cummings-model.md) | 计划中 |
| 光子计数与探测 | [光学测量](./notes/qis/optical-measurement.md) | 计划中 |
| 腔量子电动力学 | [Cavity QED](./notes/qis/cavity-qed.md) | 计划中 |
| 连续变量量子信息 | [连续变量量子信息](./notes/qis/continuous-variable-quantum-information.md) | 计划中 |

---

## 3. 量子计算

入口：[量子计算](./notes/qis/quantum-computation.md)

这一部分整理量子比特、量子门、量子线路、量子算法、噪声模型和量子纠错等主题。

| 主题 | 链接 | 状态 |
|---|---|---|
| 量子比特与 Bloch 球 | [单量子比特](./notes/qis/qubit-and-bloch-sphere.md) | 计划中 |
| 单比特门与多比特门 | [量子门](./notes/qis/quantum-gates.md) | 计划中 |
| 量子线路模型 | [量子线路](./notes/qis/quantum-circuits.md) | 计划中 |
| Deutsch--Jozsa、Grover 与 Shor 算法 | [基础量子算法](./notes/qis/basic-quantum-algorithms.md) | 计划中 |
| 量子傅里叶变换 | [QFT](./notes/qis/quantum-fourier-transform.md) | 计划中 |
| 噪声、量子通道与 Kraus 表示 | [量子通道](./notes/qis/quantum-channels.md) | 计划中 |
| 量子纠错 | [量子纠错](./notes/qis/quantum-error-correction.md) | 计划中 |
| 变分量子算法 | [VQA](./notes/qis/variational-quantum-algorithms.md) | 计划中 |

---

## 4. 量子精密测量

入口：[量子精密测量](./notes/qis/quantum-precision-measurement.md)

量子精密测量关注如何利用量子态、量子相干性和纠缠来提升参数估计精度。

| 主题 | 链接 | 状态 |
|---|---|---|
| 经典参数估计 | [估计理论基础](./notes/qis/estimation-theory.md) | 计划中 |
| Fisher 信息 | [经典 Fisher 信息](./notes/qis/classical-fisher-information.md) | 计划中 |
| 量子 Fisher 信息 | [量子 Fisher 信息](./notes/qis/quantum-fisher-information.md) | 计划中 |
| Cramér--Rao 界 | [量子 Cramér--Rao 界](./notes/qis/quantum-cramer-rao-bound.md) | 计划中 |
| Ramsey 干涉 | [Ramsey 测量](./notes/qis/ramsey-interferometry.md) | 计划中 |
| 压缩态与精密测量 | [压缩与测量增强](./notes/qis/squeezing-and-metrology.md) | 计划中 |
| 多参数量子估计 | [多参数估计](./notes/qis/multiparameter-quantum-estimation.md) | 计划中 |

---

## 5. 量子信息理论

入口：[量子信息理论](./notes/qis/quantum-information-theory.md)

量子信息理论研究量子态、信道、熵、纠缠和通信任务中的基本限制。

| 主题 | 链接 | 状态 |
|---|---|---|
| Shannon 熵与经典信息 | [经典信息论基础](./notes/qis/classical-information-theory.md) | 计划中 |
| von Neumann 熵 | [量子熵](./notes/qis/von-neumann-entropy.md) | 计划中 |
| 相对熵与互信息 | [相对熵与互信息](./notes/qis/relative-entropy-and-mutual-information.md) | 计划中 |
| 量子信道容量 | [量子信道容量](./notes/qis/quantum-channel-capacity.md) | 计划中 |
| 纠缠度量 | [纠缠度量](./notes/qis/entanglement-measures.md) | 计划中 |
| 量子隐形传态 | [量子隐形传态](./notes/qis/quantum-teleportation.md) | 计划中 |
| 量子密钥分发 | [QKD](./notes/qis/quantum-key-distribution.md) | 计划中 |

---

## 6. 量子热力学

入口：[量子热力学](./notes/qis/quantum-thermodynamics.md)

量子热力学关注能量、熵、功、热、测量和信息之间的关系，尤其适合连接开放系统、量子测量和信息理论。

| 主题 | 链接 | 状态 |
|---|---|---|
| 密度算符与热态 | [Gibbs 态](./notes/qis/gibbs-state.md) | 计划中 |
| 开放系统与热浴 | [热浴与主方程](./notes/qis/thermal-bath-and-master-equation.md) | 计划中 |
| 量子功与热 | [量子功和热](./notes/qis/quantum-work-and-heat.md) | 计划中 |
| 涨落定理 | [量子涨落关系](./notes/qis/quantum-fluctuation-theorems.md) | 计划中 |
| Maxwell 妖与信息热力学 | [信息与热力学](./notes/qis/information-thermodynamics.md) | 计划中 |
| 量子热机 | [量子热机](./notes/qis/quantum-heat-engines.md) | 计划中 |

---

# 人工智能基础

人工智能基础部分围绕“数学工具 → 数据处理 → 模型学习 → 序贯决策”的顺序组织。目标不是只记录 API 用法，而是把基本概念、算法推导、实践细节和常见误区系统整理出来。

## 1. 数学基础

入口：[数学基础](./notes/ai/math-foundations.md)

| 主题 | 链接 | 状态 |
|---|---|---|
| 线性代数 | [向量、矩阵与特征分解](./notes/ai/linear-algebra.md) | 计划中 |
| 概率论 | [概率分布与条件概率](./notes/ai/probability.md) | 计划中 |
| 数理统计 | [估计、假设检验与置信区间](./notes/ai/statistics.md) | 计划中 |
| 优化方法 | [梯度下降与凸优化](./notes/ai/optimization.md) | 计划中 |
| 信息论 | [熵、交叉熵与 KL 散度](./notes/ai/information-theory.md) | 计划中 |
| 矩阵分解 | [SVD、PCA 与低秩近似](./notes/ai/matrix-factorization.md) | 计划中 |

---

## 2. 数据清洗与数据挖掘

入口：[数据清洗与数据挖掘](./notes/ai/data-cleaning-and-mining.md)

| 主题 | 链接 | 状态 |
|---|---|---|
| 数据质量评估 | [缺失值、异常值与重复数据](./notes/ai/data-quality.md) | 计划中 |
| 数据预处理 | [标准化、归一化与编码](./notes/ai/data-preprocessing.md) | 计划中 |
| 特征工程 | [特征构造与特征选择](./notes/ai/feature-engineering.md) | 计划中 |
| 探索性数据分析 | [EDA](./notes/ai/exploratory-data-analysis.md) | 计划中 |
| 聚类分析 | [K-means、层次聚类与 DBSCAN](./notes/ai/clustering.md) | 计划中 |
| 降维方法 | [PCA、t-SNE 与 UMAP](./notes/ai/dimensionality-reduction.md) | 计划中 |
| 关联规则 | [Apriori 与频繁项集](./notes/ai/association-rules.md) | 计划中 |

---

## 3. 深度学习

入口：[深度学习](./notes/ai/deep-learning.md)

| 主题 | 链接 | 状态 |
|---|---|---|
| 神经网络基础 | [多层感知机与反向传播](./notes/ai/neural-networks.md) | 计划中 |
| 损失函数与优化器 | [Loss 与 Optimizer](./notes/ai/loss-functions-and-optimizers.md) | 计划中 |
| 卷积神经网络 | [CNN](./notes/ai/convolutional-neural-networks.md) | 计划中 |
| 循环神经网络 | [RNN、LSTM 与 GRU](./notes/ai/recurrent-neural-networks.md) | 计划中 |
| Transformer | [Attention 与 Transformer](./notes/ai/transformer.md) | 计划中 |
| 表示学习 | [Embedding 与自监督学习](./notes/ai/representation-learning.md) | 计划中 |
| 生成模型 | [VAE、GAN 与扩散模型](./notes/ai/generative-models.md) | 计划中 |
| 模型评估 | [泛化、过拟合与验证集](./notes/ai/model-evaluation.md) | 计划中 |

---

## 4. 强化学习

入口：[强化学习](./notes/ai/reinforcement-learning.md)

| 主题 | 链接 | 状态 |
|---|---|---|
| Markov 决策过程 | [MDP](./notes/ai/markov-decision-process.md) | 计划中 |
| 动态规划 | [Value Iteration 与 Policy Iteration](./notes/ai/dynamic-programming.md) | 计划中 |
| Monte Carlo 方法 | [MC 控制](./notes/ai/monte-carlo-methods.md) | 计划中 |
| 时序差分学习 | [TD Learning](./notes/ai/temporal-difference-learning.md) | 计划中 |
| Q-learning | [Q-learning 与 SARSA](./notes/ai/q-learning-and-sarsa.md) | 计划中 |
| 策略梯度 | [Policy Gradient](./notes/ai/policy-gradient.md) | 计划中 |
| Actor--Critic | [Actor--Critic 方法](./notes/ai/actor-critic.md) | 计划中 |
| 深度强化学习 | [DQN、PPO 与 SAC](./notes/ai/deep-reinforcement-learning.md) | 计划中 |

---

# 最近更新

- [量子测量：投影测量与 POVM](./notes/qis/quantum-measurement.md)
- [路径信息、退相干与干涉条纹消失](./notes/qis/quantum-measurement.md#路径信息与干涉消失)
- [量子力学形式理论：状态空间、算符与谱分解](./notes/qis/quantum-mechanics-formalism.md)

---

# 推荐页面结构

如果使用静态网页系统，可以参考下面的目录组织方式：

```text
.
├── index.md
├── notes/
│   ├── qis/
│   │   ├── quantum-mechanics-formalism.md
│   │   ├── density-operator.md
│   │   ├── composite-systems-and-entanglement.md
│   │   ├── quantum-dynamics.md
│   │   ├── open-quantum-systems.md
│   │   ├── quantum-measurement.md
│   │   ├── quantum-optics.md
│   │   ├── quantum-computation.md
│   │   ├── quantum-precision-measurement.md
│   │   ├── quantum-information-theory.md
│   │   └── quantum-thermodynamics.md
│   └── ai/
│       ├── math-foundations.md
│       ├── data-cleaning-and-mining.md
│       ├── deep-learning.md
│       └── reinforcement-learning.md
└── assets/
    ├── figures/
    └── pdfs/
```

---

# 关于本站

本站主要用于整理学习笔记、讲义草稿、推导过程和代码实验。内容会持续更新，优先保证推导清楚、符号一致和结构完整。  
如果你对某个主题感兴趣，可以从上方目录进入对应页面。

---

# 联系方式

- GitHub：[lixiaowei-sci](https://github.com/lixiaowei-sci)
- Email：[lixiaowei@cdut.edu.cn](mailto:lixiaowei@cdut.edu.cn)
- ORCID：[0000-0002-6418-2689](https://orcid.org/0000-0002-6418-2689)

