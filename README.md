# Nüwa.RNA Foundation Model

[English](README.md) | [中文](README_zh.md)

---

## Model Description

**Nüwa.RNA** is a large-scale generalist foundation model developed by the Cheng Yuan and Guo Xin team at **Shanghai Academy of Artificial Intelligence for Science (SAIS)**. It establishes a **unified representation of RNA sequence, structure, and function**.

The model is available in **multiple sizes, scaling up to 30 billion parameters**, and is trained on a massive corpus of diverse RNA types using a novel **multi-level masked self-supervised learning framework**. This approach synergizes synchronized single-token masking with span-based masking strategies and explicitly incorporates secondary structure information within an optimized architecture. This multi-modal training regime enables the emergence of advanced cognitive capabilities regarding RNA structural features and chemical modifications.

Nüwa.RNA achieves **state-of-the-art performance across 43 evaluation metrics** spanning sequence generation, structure prediction, and functional inference, **ranking first in comprehensive benchmarks**. Notably, Nüwa.RNA attains optimal results in **42 of these 43 metrics**, surpassing leading models such as RNA-FM, RNAGenesis, and AIDO.RNA.

Beyond in silico benchmarking, Nüwa.RNA's practical utility has been validated through a **"Lab-in-the-loop" system** for nucleic acid drug design. In experimental validation targeting five distinct targets across aptamer and siRNA modalities, Nüwa.RNA **reduced wet-laboratory validation costs by over 90%**.

## Model Architecture

Nüwa.RNA is built upon a modernized **encoder-only Transformer** architecture with:
- **Rotary Positional Embeddings (RoPE)** for better relative positioning between nucleotides
- **GeGLU activation functions** for improved training stability
- **Hybrid attention** combining sliding window and global attention mechanisms
- Specialized heads for **masked language modeling** and **structural constraint prediction**

**Nüwa.RNA-1.6B Configuration:**

| Hyperparameter | Value |
|----------------|-------|
| num-layers | 32 |
| hidden-size | 2,048 |
| ffn-hidden-size | 5,440 |
| num-attn-heads | 32 |
| vocab-size | 16 |

## Model Access

🔗 **NovaInspire Platform**: [https://aistudio.ai4s.com.cn/galaxy-model/model/167](https://aistudio.ai4s.com.cn/galaxy-model/model/167)

---

## License

Please refer to the model portal for licensing information.

## Citation

If you use Nüwa.RNA in your research, please cite our technical report.
