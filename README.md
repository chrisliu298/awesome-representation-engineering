# Awesome Representation Engineering

[![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/chrisliu298/awesome-representation-engineering)

This repository tracks the latest research on representation engineering (RepE), which was originally introduced by [Zou et al. (2023)](https://arxiv.org/abs/2310.01405). The goal is to offer a comprehensive list of papers, datasets, and resources relevant to the topic.

> [!NOTE]
> If you believe your paper on LLM unlearning is not included, or if you find a mistake, typo, or information that is not up to date, please open an issue, and I will address it as soon as possible.
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

| Paper                                                                                                                        | Author(s)    | Year-Month | Venue | Code                                                                            |
| ---------------------------------------------------------------------------------------------------------------------------- | ------------ | ---------- | ----- | ------------------------------------------------------------------------------- |
| [Towards General Conceptual Model Editing via Adversarial Representation Engineering](https://arxiv.org/abs/2404.13752)      | Zhang et al. | 2024-04    | -     | [GitHub](https://github.com/Zhang-Yihao/Adversarial-Representation-Engineering) |
| [Towards Uncovering How Large Language Model Works: An Explainability Perspective](https://arxiv.org/abs/2402.10688)         | Zhao et al.  | 2024-02    | -     | -                                                                               |
| [Tradeoffs Between Alignment and Helpfulness in Language Models](https://arxiv.org/abs/2401.16332)                           | Wolf et al.  | 2024-01    | -     | -                                                                               |
| [Open the Pandora's Box of LLMs: Jailbreaking LLMs through Representation Engineering](https://arxiv.org/abs/2401.06824)     | Li et al.    | 2024-01    | -     | -                                                                               |
| [Aligning Large Language Models with Human Preferences through Representation Engineering](https://arxiv.org/abs/2312.15997) | Liu et al.   | 2023-12    | -     | -                                                                               |
| [Representation Engineering: A Top-Down Approach to AI Transparency](https://arxiv.org/abs/2310.01405)                       | Zou et al.   | 2023-10    | -     | [GitHub](https://github.com/andyzoujm/representation-engineering)               |

### Steering vectors

| Paper                                                                                                                                       | Author(s)           | Year-Month | Venue | Code                                                                  |
| ------------------------------------------------------------------------------------------------------------------------------------------- | ------------------- | ---------- | ----- | --------------------------------------------------------------------- |
| [Activation Steering for Robust Type Prediction in CodeLLMs](https://arxiv.org/abs/2404.01903)                                              | Lucchetti and Guha  | 2024-04    | -     | -                                                                     |
| [Extending Activation Steering to Broad Skills and Multiple Behaviours](https://arxiv.org/abs/2403.05767)                                   | van der Weij et al. | 2024-03    | -     | [GitHub](https://github.com/TeunvdWeij/extending-activation-addition) |
| [Towards Tracing Trustworthiness Dynamics: Revisiting Pre-training Period of Large Language Models](https://arxiv.org/abs/2402.19465)       | Qian et al.         | 2024-02    | -     | [GitHub](https://github.com/ChnQ/TracingLLM)                          |
| [MiMiC: Minimally Modified Counterfactuals in the Representation Space](https://arxiv.org/abs/2402.09631)                                   | Singh et al.        | 2024-02    | -     | -                                                                     |
| [Investigating Bias Representations in Llama 2 Chat via Activation Steering](https://arxiv.org/abs/2402.00402)                              | Lu and Rimsky       | 2024-02    | -     | -                                                                     |
| [InferAligner: Inference-Time Alignment for Harmlessness through Cross-Model Guidance](https://arxiv.org/abs/2401.11206)                    | Wang et al.         | 2024-01    | -     | [GitHub](https://github.com/Jihuai-wpy/InferAligner)                  |
| [Steering Llama 2 via Contrastive Activation Addition](https://arxiv.org/abs/2312.06681)                                                    | Rimsky et al.       | 2024-12    | -     | [GitHub](https://github.com/nrimsky/CAA)                              |
| [Improving Activation Steering in Language Models with Mean-Centring](https://arxiv.org/abs/2312.03813)                                     | Jorgensen et al.    | 2023-12    | -     | -                                                                     |
| [Backdoor Activation Attack: Attack Large Language Models using Activation Steering for Safety-Alignment](https://arxiv.org/abs/2311.09433) | Wang and Shu        | 2023-11    | -     | [GitHub](https://github.com/wang2226/Backdoor-Activation-Attack)      |
| [The Linear Representation Hypothesis and the Geometry of Large Language Models](https://arxiv.org/abs/2311.03658)                          | Park et al.         | 2023-11    | -     | [GitHub](https://github.com/KihoPark/linear_rep_geometry)             |
| [Activation Addition: Steering Language Models Without Optimization](https://arxiv.org/abs/2308.10248)                                      | Turner              | 2023-08    | -     | [GitHub](https://github.com/montemac/activation_additions)            |
| [Extracting Latent Steering Vectors from Pretrained Language Models](https://arxiv.org/abs/2205.05124)                                      | Subramani et al.    | 2022-05    | -     | [GitHub](https://github.com/nishantsubramani/steering_vectors)        |

### Concept activation vectors

| Paper                                                                                                             | Author(s)          | Year-Month | Venue     | Code |
| ----------------------------------------------------------------------------------------------------------------- | ------------------ | ---------- | --------- | ---- |
| [Uncovering Safety Risks in Open-source LLMs through Concept Activation Vector](https://arxiv.org/abs/2404.12038) | Xu et al.          | 2024-04    | -         | -    |
| [Explaining Explainability: Understanding Concept Activation Vectors](https://arxiv.org/abs/2404.03713)           | Nicolson et al.    | 2024-04    | -         | -    |
| [Demystifying Embedding Spaces using Large Language Models](https://arxiv.org/abs/2310.04475)                     | Tennenholtz et al. | 2023-10    | ICLR 2024 | -    |

### Other relevant papers

| Paper                                                                                                                                               | Author(s)         | Year-Month | Venue | Code                                                     |
| --------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------- | ---------- | ----- | -------------------------------------------------------- |
| [The Geometry of Truth: Emergent Linear Structure in Large Language Model Representations of True/False Datasets](https://arxiv.org/abs/2310.06824) | Marks and Tegmark | 2023-10    | -     | [GitHub](https://github.com/saprmarks/geometry-of-truth) |

## Blog Posts

- [Representation Engineering Mistral-7B an Acid Trip](https://vgel.me/posts/representation-engineering/)
- [Representation Engineering for Control Vector](https://mlops.substack.com/p/representation-engineering-for-control)

Other relevant posts:

- [Refusal in LLMs is mediated by a single direction](https://www.alignmentforum.org/posts/jGuXSZgv6qfdhMCuJ/refusal-in-llms-is-mediated-by-a-single-direction)
- [Simple probes can catch sleeper agents](https://www.anthropic.com/research/probes-catch-sleeper-agents)
