# AI Learning Roadmap

> 理论学习计划唯一真源：持续记录“准备学什么、已经学了什么、接下来学什么”，形成可长期回看的 AI 理论学习主线。

最后更新：2026-08-30

---

## 1. 信息论与 MDL

- **状态**：🟡 学习中
- **已接触**：
  - 信息论与机器学习之间的关系
  - 正则化、模型复杂度与 MDL 的联系
  - Kolmogorov Complexity 的基本思想
- **接下来**：
  - 信息量为什么是 `-log p`
  - 熵 (Entropy) 与交叉熵 (Cross-Entropy)
  - KL Divergence
  - 最大似然与负对数似然 (NLL)
  - 从信息论重新理解 Cross-Entropy Loss
  - MDL 的两部分编码：模型 + 数据
  - MDL、贝叶斯方法与正则化之间的关系
- **阶段目标**：
  能够解释“为什么更短的描述可能意味着更好的泛化”，并明确这一说法成立的条件和边界。

---

## 2. Machine Learning Theory

- **状态**：🟡 已接触部分概念，尚未系统学习
- **已接触**：
  - Loss、梯度下降、学习率
  - 反向传播的基本思想
  - 正则化、泛化问题
- **接下来**：
  - 经验风险与真实风险
  - 训练误差与测试误差
  - 假设空间与模型容量
  - Bias–Variance 权衡
  - Overfitting / Underfitting
  - 数据泄漏与可靠实验设计
  - 泛化为什么可能发生（泛化界、PAC / VC 理论基本思想）
- **阶段目标**：
  不仅会训练模型，还能判断一个机器学习结论为什么可信，以及证据允许我们声称什么。

---

## 3. Deep Learning Theory

- **状态**：⚪ 尚未系统开始
- **接下来**：
  - 神经元、层与参数
  - 为什么纯线性网络没有深度意义
  - Activation Function
  - Representation
  - Forward / Backpropagation
  - Optimization / Initialization / Normalization
  - Residual Connection
  - Attention 与 Transformer
  - Scaling 与现代大模型训练的基本原理
- **阶段目标**：
  从“会调用神经网络”逐步走到能够解释现代深度学习系统为什么这样设计。

---

## 当前优先级

1. 熵 → 交叉熵 → KL Divergence → 最大似然
2. 完成 MDL 主线
3. 建立机器学习泛化理论框架
4. 从“为什么需要非线性”正式进入深度学习理论

---

## 维护原则

1. **唯一真源**：路线变动与阶段状态在此处统一更新。
2. **计划书保持精炼**：维护方向与状态，长篇推导与笔记下沉至专题目录。
3. **知识沉淀分层**：
   - 第一层：`ROADMAP.md` 记录方向与进度。
   - 第二层：专题目录记录通用知识理解与推导。
   - 第三层：代码与实验记录保存在私密仓库 `python-ml-study`。
