# AI Learning Roadmap

> 目标：持续记录“准备学什么、已经学了什么、接下来学什么”，形成一条可以长期回看的 AI 理论学习主线。

最后更新：2026-08-30

## 当前状态

### 1. 信息论与 MDL

状态：🟡 学习中

已经接触：

* 信息论与机器学习之间的关系
* 正则化、模型复杂度与 MDL 的联系
* Kolmogorov Complexity 的基本思想

接下来：

* 信息量为什么是 `-log p`
* 熵 Entropy
* 交叉熵 Cross-Entropy
* KL Divergence
* 最大似然与负对数似然
* 从信息论重新理解 Cross-Entropy Loss
* MDL 的两部分编码：模型 + 数据
* MDL、贝叶斯方法与正则化之间的关系

目标：
能够解释“为什么更短的描述可能意味着更好的泛化”，并明确这一说法成立的条件和边界。

---

### 2. Machine Learning Theory

状态：🟡 已接触部分概念，尚未系统学习

已经接触：

* Loss
* 梯度下降
* 学习率
* 反向传播的基本思想
* 正则化
* 泛化问题

接下来：

* 经验风险与真实风险
* 训练误差与测试误差
* 假设空间
* 模型容量
* Bias–Variance
* Overfitting / Underfitting
* Regularization
* 数据泄漏与可靠实验
* 泛化为什么可能发生
* 泛化界、PAC / VC 等理论的基本思想

目标：
不仅会训练模型，还能判断一个机器学习结论为什么可信，以及证据允许我们声称什么。

---

### 3. Deep Learning Theory

状态：⚪ 尚未系统开始

接下来：

* 神经元、层与参数
* 为什么纯线性网络没有深度意义
* Activation Function
* Representation
* Forward Propagation
* Backpropagation
* Optimization
* Initialization
* Normalization
* Residual Connection
* Attention
* Transformer
* Scaling 与现代大模型训练的基本原理

目标：
从“会调用神经网络”逐步走到能够解释现代深度学习系统为什么这样设计。

---

## 当前优先级

近期顺序：

1. 熵 → 交叉熵 → KL Divergence → 最大似然
2. 完成 MDL 主线
3. 建立机器学习泛化理论框架
4. 从“为什么需要非线性”正式进入深度学习理论

原则：

* 不为了覆盖知识点而学习。
* 新知识必须尽量连接到已有问题。
* 区分“API / 约定，需要先知道”和“可以从原理推出的结论”。
* 每完成一个主题，记录：

  * 我现在能解释什么？
  * 哪些结论有证据？
  * 哪些地方仍然不确定？
  * 下一步最自然的问题是什么？
