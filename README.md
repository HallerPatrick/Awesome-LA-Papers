# Awesome Linear Attention Papers
[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

A curated list of resources related to linear attention mechanisms.

This project is a work in progress. Contributions are welcome! 
## Table of Contents

1. [Introduction](#introduction)
2. [Papers](#papers)
   - [Architectures](#architectures)
   - [Theoretical Foundations](#theoretical-foundations)
   - [Applications](#applications)
3. [Libraries and Implementations](#libraries-and-implementations)
4. [Datasets](#datasets)
5. [Tutorials and Blog Posts](#tutorials-and-blog-posts)
6. [Contributing](#contributing)

# Introduction

Linear attention mechanisms have emerged as efficient alternatives to traditional attention methods, offering scalability and performance benefits, especially for long-sequence data. This repository aims to consolidate key papers, libraries, tutorials, and datasets pertinent to linear attention.

## Papers
### Architectures

- **Retentive Network: A Successor to Transformer for Large Language Models** (ArXiv, June 2023)  
  [Paper](https://arxiv.org/abs/2307.08621)

- **Gated Linear Attention Transformers with Hardware-Efficient Training** (ArXiv, November 2023)  
  [Paper](https://arxiv.org/abs/2312.06635)

- **You Only Cache Once: Decoder-Decoder Architectures for Language Models** (NeurIPS 2024)  
  [Paper](https://proceedings.neurips.cc/paper_files/paper/2024/file/0df38cd13520747e1e64e5b123a78ef8-Paper-Conference.pdf)

- **xLSTM: Extended Long Short-Term Memory** (NeurIPS 2024)  
  [Paper](https://proceedings.neurips.cc/paper_files/paper/2024/file/c2ce2f2701c10a2b2f2ea0bfa43cfaa3-Paper-Conference.pdf)

- **Rethinking Attention with Performers** (ArXiv, September 2020)  
  [Paper](https://arxiv.org/abs/2009.14794)

- **Luna: Linear Unified Nested Attention** (ArXiv, June 2021)  
  [Paper](https://arxiv.org/abs/2106.01540)

- **Train Short, Test Long: Attention with Linear Biases Enables Input Length Extrapolation** (ArXiv, August 2021)  
  [Paper](https://arxiv.org/abs/2108.12409)

- **HGRN - Hierarchically Gated Recurrent Neural Network for Sequence Modeling** (NeurIPS 2023)  
  [Paper](https://proceedings.neurips.cc/paper_files/paper/2023/file/694be3548697e9cc8999d45e8d16fe1e-Paper-Conference.pdf)

- **HGRN2: Gated Linear RNNs with State Expansion** (COLM 2024)  
  [Paper](https://arxiv.org/abs/2404.07904)

- **Mamba: Linear-Time Sequence Modeling with Selective State Spaces** (COLM 2024)  
  [Paper](https://arxiv.org/abs/2312.00752) [Code](https://github.com/state-spaces/mamba)

- **Transformers are SSMs: Generalized Models and Efficient Algorithms Through Structured State Space Duality** (ICML 2024)  
  [Paper](https://arxiv.org/abs/2405.21060)

- **The Devil in Linear Transformer** (EMNLP 2022)  
  [Paper](https://aclanthology.org/2022.emnlp-main.473.pdf) [Code](https://github.com/OpenNLPLab/Transnormer)

- **Linear Transformers with Learnable Kernel Functions are Better In-Context Models** (ACL 2024)  
  [Paper](https://aclanthology.org/2024.acl-long.518/)

- **The Hedgehog & the Porcupine: Expressive Linear Attentions with Softmax Mimicry**  
  [Paper](https://arxiv.org/abs/2402.04347)

- **Parallelizing Linear Transformers with the Delta Rule over Sequence Length** (NeurIPS 2024)  
  [Paper](https://proceedings.neurips.cc/paper_files/paper/2024/file/d13a3eae72366e61dfdc7eea82eeb685-Paper-Conference.pdf)

- **Resurrecting Recurrent Neural Networks for Long Sequences** (PMLR 2023)  
  [Paper](https://proceedings.mlr.press/v202/orvieto23a.html)

- **RWKV: Reinventing RNNs for the Transformer Era** (EMNLP 2023)  
  [Paper](https://aclanthology.org/2023.findings-emnlp.936/)

- **Griffin: Mixing Gated Linear Recurrences with Local Attention for Efficient Language Models** (ArXiv, February 2024)  
  [Paper](https://arxiv.org/abs/2402.19427)

- **MetaLA: Unified Optimal Linear Approximation to Softmax Attention Map** (NeurIPS 2024)  
  [Paper](https://proceedings.neurips.cc/paper_files/paper/2024/file/8329a45669017898bb0cc09d27f8d2bb-Paper-Conference.pdf)

- **Gated Delta Networks: Improving Mamba2 with Delta Rule** (ICLR 2025)  
  [Paper](https://arxiv.org/abs/2412.06464)

- **Titans: Learning to Memorize at Test Time** (ArXiv, December 2024)  
  [Paper](https://arxiv.org/abs/2501.00663)


### Theoretical Foundations

- **Linear Attention Is (Maybe) All You Need (to Understand Transformer Optimization)** (ICLR 2024)  
  [Paper](https://openreview.net/forum?id=0uI5415ry7)

- **Bridging the Divide: Reconsidering Softmax and Linear Attention** (NeurIPS 2024)  
  [Paper](https://arxiv.org/abs/2412.06590)

- **Scaling Laws for Linear Complexity Language Models** (EMNLP 2024)  
  [Paper](https://aclanthology.org/2024.emnlp-main.916)

- **Explaining Modern Gated-Linear RNNs via a Unified Implicit Attention Formulation** (ICLR 2025)  
  [Paper](https://arxiv.org/abs/2405.16504)


### Linearization

- **Transformers to SSMs: Distilling Quadratic Knowledge to Subquadratic Models** (NeurIPS 2024)  
  [Paper](https://proceedings.neurips.cc/paper_files/paper/2024/file/3848fef259495bfd04d60cdc5c1b4db7-Paper-Conference.pdf)

- **LoLCATs: On Low-Rank Linearizing of Large Language Models** (ICLR 2025)  
  [Paper](https://arxiv.org/abs/2410.10254)

- **Liger: Linearizing Large Language Models to Gated Recurrent Structures** (ArXiv, March 2025)  
  [Paper](https://arxiv.org/abs/2503.01496)

- **Llamba: Scaling Distilled Recurrent Models for Efficient Language Processing** (ICLR 2025)  
  [Paper](https://arxiv.org/abs/2502.14458)

- **The Mamba in the Llama: Distilling and Accelerating Hybrid Models** (NeurIPS 2024)  
  [Paper](https://arxiv.org/abs/2408.15237)


### Applications

- **FLatten Transformer: Vision Transformer Using Focused Linear Attention** (ArXiv, August 2023)  
  [Paper](https://arxiv.org/abs/2308.00442)

- **Thinking Slow, Fast: Scaling Inference Compute with Distilled Reasoners** (ICLR 2025)  
  [Paper](https://arxiv.org/abs/2502.20339)


## Libraries and Implementations

- **FLA**: A collection of Triton-based implementations of linear attention models.  
  [GitHub Repository](https://github.com/fla-org/flash-linear-attention/tree/main)

- **InLine**: Code accompanying the paper "Bridging the Divide: Reconsidering Softmax and Linear Attention."  
  [GitHub Repository](https://github.com/LeapLabTHU/InLine)


## Datasets

- **Long Range Arena (LRA)**: A benchmark for evaluating efficient transformers on tasks requiring long-context understanding.  
  [GitHub Repository](https://github.com/google-research/long-range-arena)
- **Zoology: Measuring and Improving Recall in Efficient Language Models (MQAR)**: A dataset for evaluating the recall of sequence models.  
  [GitHub Repository](https://github.com/HazyResearch/zoology)

## (TODO) Tutorials and Blog Posts

## Contributing

We welcome contributions! You can contribute by:

- Adding new papers, libraries, or tutorials.
- Reporting issues or suggesting improvements.
- Enhancing the documentation.

Please feel free to submit a pull request, open an issue, or contact me via [email](mailto:patrickhaller40@googlemail.com).
