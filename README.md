# Nvwa.RNA Foundation Model

[English](#english) | [中文](#中文)

---

## English

### Model Description

**Nvwa.RNA** is a large-scale generalist foundation model developed by the Cheng Yuan and Guo Xin team at **Shanghai Academy of Artificial Intelligence for Science (SAIS)**. It establishes a **unified representation of RNA sequence, structure, and function**.

The model is available in **multiple sizes, scaling up to 30 billion parameters**, and is trained on a massive corpus of diverse RNA types using a novel **multi-level masked self-supervised learning framework**. This approach synergizes synchronized single-token masking with span-based masking strategies and explicitly incorporates secondary structure information within an optimized architecture. This multi-modal training regime enables the emergence of advanced cognitive capabilities regarding RNA structural features and chemical modifications.

Nvwa.RNA achieves **state-of-the-art performance across 43 evaluation metrics** spanning sequence generation, structure prediction, and functional inference, **ranking first in comprehensive benchmarks**. Notably, Nvwa.RNA attains optimal results in **42 of these 43 metrics**, surpassing leading models such as RNA-FM, RNAGenesis, and AIDO.RNA.

Beyond in silico benchmarking, Nvwa.RNA's practical utility has been validated through a **"Lab-in-the-loop" system** for nucleic acid drug design. In experimental validation targeting five distinct targets across aptamer and siRNA modalities, Nvwa.RNA **reduced wet-laboratory validation costs by over 90%**.

### Model Architecture

Nvwa.RNA is built upon a modernized **encoder-only Transformer** architecture with:
- **Rotary Positional Embeddings (RoPE)** for better relative positioning between nucleotides
- **GeGLU activation functions** for improved training stability
- **Hybrid attention** combining sliding window and global attention mechanisms
- Specialized heads for **masked language modeling** and **structural constraint prediction**

**Nvwa.RNA-1.6B Configuration:**

| Hyperparameter | Value |
|----------------|-------|
| num-layers | 32 |
| hidden-size | 2,048 |
| ffn-hidden-size | 5,440 |
| num-attn-heads | 32 |
| vocab-size | 16 |

### Model Access

🔗 **NovaInspire Platform**: [https://aistudio.ai4s.com.cn/galaxy-model/model/167](https://aistudio.ai4s.com.cn/galaxy-model/model/167)

---

## 中文

### 模型描述

**Nvwa.RNA** 是由**上海科学智能研究院**程远和郭昕团队研发的大规模通用基础模型，建立了 **RNA 序列、结构和功能的统一表示**。

该模型提供**多种规模，最高可达 300 亿参数**，在海量多样化 RNA 类型语料库上进行训练，采用了新颖的**多层次掩码自监督学习框架**。该方法将同步的单 token 掩码与基于片段的掩码策略相结合，并在优化的架构中显式整合二级结构信息。这种多模态训练方式使模型能够涌现出关于 RNA 结构特征和化学修饰的高级认知能力。

Nvwa.RNA 在涵盖序列生成、结构预测和功能推断的 **43 项评估指标中取得了最先进的性能**，在综合基准测试中**排名第一**。值得注意的是，Nvwa.RNA 在其中 **42 项指标中达到最优**，超越了 RNA-FM、RNAGenesis 和 AIDO.RNA 等领先模型。

除了计算机模拟基准测试外，Nvwa.RNA 还通过**"Lab-in-the-loop"（干湿闭环）系统**验证了其在核酸药物设计中的实用价值。在针对适配体和 siRNA 两种药物形式、涵盖五个不同靶点的实验验证中，Nvwa.RNA **将湿实验室验证成本降低了 90% 以上**。

### 模型架构

Nvwa.RNA 基于现代化的**纯编码器 Transformer** 架构构建，具有以下特点：
- **旋转位置编码 (RoPE)**：更好地捕捉核苷酸之间的相对位置关系
- **GeGLU 激活函数**：提升训练稳定性
- **混合注意力机制**：结合滑动窗口注意力和全局注意力
- 专用的**掩码语言建模**和**结构约束预测**头

**Nvwa.RNA-1.6B 配置：**

| 超参数 | 值 |
|--------|-----|
| num-layers | 32 |
| hidden-size | 2,048 |
| ffn-hidden-size | 5,440 |
| num-attn-heads | 32 |
| vocab-size | 16 |

### 模型调用入口

🔗 **星河启智平台 (NovaInspire)**: [https://aistudio.ai4s.com.cn/galaxy-model/model/167](https://aistudio.ai4s.com.cn/galaxy-model/model/167)

---

## License

Please refer to the model portal for licensing information.

## Citation

If you use Nvwa.RNA in your research, please cite our technical report.
