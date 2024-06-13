# Awesome Representation Engineering

<p align="center">
<a href=""> <img src="https://awesome.re/badge-flat.svg" alt="Awesome"></a>
<a href=""> <img src="https://img.shields.io/github/stars/chrisliu298/awesome-representation-engineering?style=flat-square&logo=github" alt="GitHub stars"></a>
<a href=""> <img src="https://img.shields.io/github/forks/chrisliu298/awesome-representation-engineering?style=flat-square&logo=github" alt="GitHub forks"></a>
<a href=""> <img src="https://img.shields.io/github/issues/chrisliu298/awesome-representation-engineering?style=flat-square&logo=github" alt="GitHub issues"></a>
<a href=""> <img src="https://img.shields.io/github/last-commit/chrisliu298/awesome-representation-engineering?style=flat-square&logo=github" alt="GitHub Last commit"></a>
</p>

This repository tracks the latest research on representation engineering (RepE), which was originally introduced by [Zou et al. (2023)](https://arxiv.org/abs/2310.01405). The goal is to offer a comprehensive list of papers and resources relevant to the topic. Work that falls under the umbrella of representation engineering are also included.

> [!NOTE]
> If you believe your paper on representation engineering (or related topics) is not included, or if you find a mistake, typo, or information that is not up to date, please open an issue, and I will address it as soon as possible.
>
> If you want to add a new paper, feel free to either open an issue or create a pull request.

Also:

> [!IMPORTANT]
> *Note that representation engineering is a relatively new framework, so the categorization below reflects my subjective understanding of the techniques. The first table includes work that explicitly uses the term "representation engineering." Other closely related work is grouped in the later tables.*
>
> If you disagree with the categorization or have suggestions for improvement, please let me know by opening an issue.

## Table of Contents

- [Table of Contents](#table-of-contents)
- [Papers](#papers)
  - [Representation engineering](#representation-engineering)
  - [Steering vectors](#steering-vectors)
  - [Concept activation vectors](#concept-activation-vectors)
  - [Other relevant papers](#other-relevant-papers)
- [Blog Posts](#blog-posts)

## Papers

### Representation engineering

- [Legend: Leveraging Representation Engineering to Annotate Safety Margin for Preference Datasets](https://arxiv.org/abs/2406.08124)
  - Author(s): Duanyu Feng, Bowen Qin, Chen Huang, Youcheng Huang, Zheng Zhang, Wenqiang Lei
  - Date: 2024-06
  - Venue: -
  - Code: [GitHub](https://github.com/colfeng/Legend)
- [PaCE: Parsimonious Concept Engineering for Large Language Models](https://arxiv.org/abs/2406.04331)
  - Author(s): Jinqi Luo, Tianjiao Ding, Kwan Ho Ryan Chan, Darshan Thaker, Aditya Chattopadhyay, Chris Callison-Burch, René Vidal
  - Date: 2024-06
  - Venue: -
  - Code: [GitHub](https://github.com/peterljq/Parsimonious-Concept-Engineering)
- [Improving Alignment and Robustness with Circuit Breakers](https://arxiv.org/abs/2406.04313)
  - Author(s): Andy Zou, Long Phan, Justin Wang, Derek Duenas, Maxwell Lin, Maksym Andriushchenko, Rowan Wang, Zico Kolter, Matt Fredrikson, Dan Hendrycks
  - Date: 2024-06
  - Venue: -
  - Code: [GitHub](https://github.com/blackswan-ai/circuit-breakers)
- [ConTrans: Weak-to-Strong Alignment Engineering via Concept Transplantation](https://arxiv.org/abs/2405.13578)
  - Author(s): Weilong Dong, Xinwei Wu, Renren Jin, Shaoyang Xu, Deyi Xiong
  - Date: 2024-05
  - Venue: -
  - Code: -
- [Towards General Conceptual Model Editing via Adversarial Representation Engineering](https://arxiv.org/abs/2404.13752)
  - Author(s): Yihao Zhang, Zeming Wei, Jun Sun, Meng Sun
  - Date: 2024-04
  - Venue: -
  - Code: [GitHub](https://github.com/Zhang-Yihao/Adversarial-Representation-Engineering)
- [Towards Uncovering How Large Language Model Works: An Explainability Perspective](https://arxiv.org/abs/2402.10688)
  - Author(s): Haiyan Zhao, Fan Yang, Bo Shen, Himabindu Lakkaraju, Mengnan Du
  - Date: 2024-02
  - Venue: -
  - Code: -
- [Tradeoffs Between Alignment and Helpfulness in Language Models](https://arxiv.org/abs/2401.16332)
  - Author(s): Yotam Wolf, Noam Wies, Dorin Shteyman, Binyamin Rothberg, Yoav Levine, Amnon Shashua
  - Date: 2024-01
  - Venue: -
  - Code: -
- [Open the Pandora's Box of LLMs: Jailbreaking LLMs through Representation Engineering](https://arxiv.org/abs/2401.06824)
  - Author(s): Tianlong Li, Shihan Dou, Wenhao Liu, Muling Wu, Changze Lv, Xiaoqing Zheng, Xuanjing Huang
  - Date: 2024-01
  - Venue: -
  - Code: -
- [Aligning Large Language Models with Human Preferences through Representation Engineering](https://arxiv.org/abs/2312.15997)
  - Author(s): Wenhao Liu, Xiaohua Wang, Muling Wu, Tianlong Li, Changze Lv, Zixuan Ling, Jianhao Zhu, Cenyuan Zhang, Xiaoqing Zheng, Xuanjing Huang
  - Date: 2023-12
  - Venue: -
  - Code: -
- [Representation Engineering: A Top-Down Approach to AI Transparency](https://arxiv.org/abs/2310.01405)
  - Author(s): Andy Zou, Long Phan, Sarah Chen, James Campbell, Phillip Guo, Richard Ren, Alexander Pan, Xuwang Yin, Mantas Mazeika, Ann-Kathrin Dombrowski, Shashwat Goel, Nathaniel Li, Michael J. Byun, Zifan Wang, Alex Mallen, Steven Basart, Sanmi Koyejo, Dawn Song, Matt Fredrikson, J. Zico Kolter, Dan Hendrycks
  - Date: 2023-10
  - Venue: -
  - Code: [GitHub](https://github.com/andyzoujm/representation-engineering)

### Steering vectors

- [Activation Steering for Robust Type Prediction in CodeLLMs](https://arxiv.org/abs/2404.01903)
  - Author(s): Francesca Lucchetti, Arjun Guha
  - Date: 2024-04
  - Venue: -
  - Code: -
- [Extending Activation Steering to Broad Skills and Multiple Behaviours](https://arxiv.org/abs/2403.05767)
  - Author(s): Teun van der Weij, Massimo Poesio, Nandi Schoots
  - Date: 2024-03
  - Venue: -
  - Code: [GitHub](https://github.com/TeunvdWeij/extending-activation-addition)
- [Towards Tracing Trustworthiness Dynamics: Revisiting Pre-training Period of Large Language Models](https://arxiv.org/abs/2402.19465)
  - Author(s): Chen Qian, Jie Zhang, Wei Yao, Dongrui Liu, Zhenfei Yin, Yu Qiao, Yong Liu, Jing Shao
  - Date: 2024-02
  - Venue: -
  - Code: [GitHub](https://github.com/ChnQ/TracingLLM)
- [MiMiC: Minimally Modified Counterfactuals in the Representation Space](https://arxiv.org/abs/2402.09631)
  - Author(s): Shashwat Singh, Shauli Ravfogel, Jonathan Herzig, Roee Aharoni, Ryan Cotterell, Ponnurangam Kumaraguru
  - Date: 2024-02
  - Venue: -
  - Code: -
- [Investigating Bias Representations in Llama 2 Chat via Activation Steering](https://arxiv.org/abs/2402.00402)
  - Author(s): Dawn Lu, Nina Rimsky
  - Date: 2024-02
  - Venue: -
  - Code: -
- [InferAligner: Inference-Time Alignment for Harmlessness through Cross-Model Guidance](https://arxiv.org/abs/2401.11206)
  - Author(s): Pengyu Wang, Dong Zhang, Linyang Li, Chenkun Tan, Xinghao Wang, Ke Ren, Botian Jiang, Xipeng Qiu
  - Date: 2024-01
  - Venue: -
  - Code: [GitHub](https://github.com/Jihuai-wpy/InferAligner)
- [Steering Llama 2 via Contrastive Activation Addition](https://arxiv.org/abs/2312.06681)
  - Author(s): Nina Rimsky, Nick Gabrieli, Julian Schulz, Meg Tong, Evan Hubinger, Alexander Matt Turner
  - Date: 2024-12
  - Venue: -
  - Code: [GitHub](https://github.com/nrimsky/CAA)
- [Improving Activation Steering in Language Models with Mean-Centring](https://arxiv.org/abs/2312.03813)
  - Author(s): Ole Jorgensen, Dylan Cope, Nandi Schoots, Murray Shanahan
  - Date: 2023-12
  - Venue: -
  - Code: -
- [Backdoor Activation Attack: Attack Large Language Models using Activation Steering for Safety-Alignment](https://arxiv.org/abs/2311.09433)
  - Author(s): Haoran Wang, Kai Shu
  - Date: 2023-11
  - Venue: -
  - Code: [GitHub](https://github.com/wang2226/Backdoor-Activation-Attack)
- [The Linear Representation Hypothesis and the Geometry of Large Language Models](https://arxiv.org/abs/2311.03658)
  - Author(s): Kiho Park, Yo Joong Choe, Victor Veitch
  - Date: 2023-11
  - Venue: -
  - Code: [GitHub](https://github.com/KihoPark/linear_rep_geometry)
- [Activation Addition: Steering Language Models Without Optimization](https://arxiv.org/abs/2308.10248)
  - Author(s): Alexander Matt Turner, Lisa Thiergart, David Udell, Gavin Leech, Ulisse Mini, Monte MacDiarmid
  - Date: 2023-08
  - Venue: -
  - Code: [GitHub](https://github.com/montemac/activation_additions)
- [Extracting Latent Steering Vectors from Pretrained Language Models](https://arxiv.org/abs/2205.05124)
  - Author(s): Nishant Subramani, Nivedita Suresh, Matthew E. Peters
  - Date: 2022-05
  - Venue: -
  - Code: [GitHub](https://github.com/nishantsubramani/steering_vectors)

### Concept activation vectors

- [Uncovering Safety Risks in Open-source LLMs through Concept Activation Vector](https://arxiv.org/abs/2404.12038)
  - Author(s): Zhihao Xu, Ruixuan Huang, Xiting Wang, Fangzhao Wu, Jing Yao, Xing Xie
  - Date: 2024-04
  - Venue: -
  - Code: -
- [Explaining Explainability: Understanding Concept Activation Vectors](https://arxiv.org/abs/2404.03713)
  - Author(s): Angus Nicolson, Lisa Schut, J. Alison Noble, Yarin Gal
  - Date: 2024-04
  - Venue: -
  - Code: -
- [Demystifying Embedding Spaces using Large Language Models](https://arxiv.org/abs/2310.04475)
  - Author(s): Guy Tennenholtz, Yinlam Chow, Chih-Wei Hsu, Jihwan Jeong, Lior Shani, Azamat Tulepbergenov, Deepak Ramachandran, Martin Mladenov, Craig Boutilier
  - Date: 2023-10
  - Venue: ICLR 2024
  - Code: -

### Other relevant papers

- [The Geometry of Truth: Emergent Linear Structure in Large Language Model Representations of True/False Datasets](https://arxiv.org/abs/2310.06824)
  - Author(s): Samuel Marks, Max Tegmark
  - Date: 2023-10
  - Venue: -
  - Code: [GitHub](https://github.com/saprmarks/geometry-of-truth)

## Blog Posts

- [Representation Engineering Mistral-7B an Acid Trip](https://vgel.me/posts/representation-engineering/)
- [Representation Engineering for Control Vector](https://mlops.substack.com/p/representation-engineering-for-control)

Other relevant posts:

- [Refusal in LLMs is mediated by a single direction](https://www.alignmentforum.org/posts/jGuXSZgv6qfdhMCuJ/refusal-in-llms-is-mediated-by-a-single-direction)
- [Simple probes can catch sleeper agents](https://www.anthropic.com/research/probes-catch-sleeper-agents)
