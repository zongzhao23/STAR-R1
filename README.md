# STAR-R1: Spacial TrAnsformation Reasoning by Reinforcing Multimodal LLMs

Multimodal Large Language Models (MLLMs) have demonstrated remarkable capabilities across diverse tasks, yet they lag significantly behind humans in spatial reasoning. We investigate this gap through Transformation-Driven Visual Reasoning (TVR), a challenging task requiring identification of object transformations across images under varying viewpoints. While traditional Supervised Fine-Tuning (SFT) fails to generate coherent reasoning paths in cross-view settings, sparse-reward Reinforcement Learning (RL) suffers from inefficient exploration and slow convergence. To address these limitations, we propose STAR-R1, a novel framework that integrates a single-stage RL paradigm with a fine-grained reward mechanism tailored for TVR. Specifically, STAR-R1 rewards partial correctness while penalizing excessive enumeration and passive inaction, enabling efficient exploration and precise reasoning. Comprehensive evaluations demonstrate that STAR-R1 achieves state-of-the-art performance across all 11 metrics, outperforming SFT by 23\% in cross-view scenarios. Further analysis reveals STAR-R1’s anthropomorphic behavior and highlights its unique ability to compare all objects for improving spatial reasoning. Our work provides critical insights in advancing the research of MLLMs and reasoning models.

## TODO List

**Due to multiple upcoming deadlines, we will finalize and release the code in June!**

- [ ] Release Training and Evaluation Codes
- [ ] Release Training and Evaluation Datasets
- [ ] Release Training and Evaluation Scripts
- [ ] Release Model Weights of STAR-R1

![fig2](https://github.com/user-attachments/assets/90f52c4a-b17c-480c-adc4-0608e8228abe)

![fig3](https://github.com/user-attachments/assets/cfb6930b-d841-4917-9cd6-58dfa8e66c4c)

![fig5](https://github.com/user-attachments/assets/87854fa7-de46-4f4f-bf66-9f062e6a0a71)

![fig6](https://github.com/user-attachments/assets/8bae0484-d75c-463e-869f-6ad93bb954dc)
