# Nvwa.RNA Foundation Model

[English](#english) | [中文](#中文)

---

## English

### Model Description

Nvwa.RNA is a large-scale foundation model for RNA function and structure prediction, developed by the Cheng Yuan and Guo Xin team at Shanghai Academy of Artificial Intelligence for Science (SAIS). The model has **1.6 billion parameters** and is trained on non-coding RNA (ncRNA) sequences at single-nucleotide resolution. Pre-trained with a masked language modeling (MLM) objective, Nvwa.RNA generates high-quality RNA sequence representations.

Nvwa.RNA achieves **state-of-the-art performance** across multiple tasks including:
- Structure prediction
- Gene regulation
- Cross-species molecular function
- RNA sequence design

Nvwa.RNA is an **encoder-only Transformer** pre-trained using a masked language model (MLM) objective.

### Model Architecture

| Hyperparameter | Value |
|----------------|-------|
| num-layers | 32 |
| hidden-size | 2,048 |
| ffn-hidden-size | 5,440 |
| num-attn-heads | 32 |
| vocab-size | 16 |

### Model Access

🔗 **Model Portal**: [https://aistudio.ai4s.com.cn/galaxy-model/model/167](https://aistudio.ai4s.com.cn/galaxy-model/model/167)

---

## 中文

### 模型描述

Nvwa.RNA 是由上海科学智能研究院程远和郭昕团队研发的一款面向 RNA 功能和结构预测的大规模基础模型。该模型拥有 **16 亿个参数**，以单核苷酸分辨率在非编码 RNA（ncRNA）序列上进行训练，并通过掩码语言建模目标进行预训练，能够生成高质量的 RNA 序列表示。

在以下多项任务中，Nvwa.RNA 均取得了**最先进的性能**：
- 结构预测
- 基因调控
- 跨物种分子功能
- RNA 序列设计

Nvwa.RNA 是一款**仅使用编码器的 Transformer**，并使用掩码语言模型 (MLM) 目标进行预训练。

### 模型架构

| 超参数 | 值 |
|--------|-----|
| num-layers | 32 |
| hidden-size | 2,048 |
| ffn-hidden-size | 5,440 |
| num-attn-heads | 32 |
| vocab-size | 16 |

### 模型调用入口

🔗 **模型入口**: [https://aistudio.ai4s.com.cn/galaxy-model/model/167](https://aistudio.ai4s.com.cn/galaxy-model/model/167)

---

## License

Please refer to the model portal for licensing information.

## Citation

If you use Nvwa.RNA in your research, please cite our technical report.

