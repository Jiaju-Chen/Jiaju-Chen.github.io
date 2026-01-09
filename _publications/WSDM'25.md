---
title: "DLCRec: A Novel Approach for Managing Diversity in LLM-Based Recommender Systems"
collection: publications
category: conferences
permalink: /publication/WSDM'25
excerpt: 'A fine-grained controllable recommendation framework that enables precise diversity management in LLM-based systems through task decomposition and robust data augmentation techniques.'
date: 2025-03-10
venue: "WSDM 2025 (The 18th ACM International Conference on Web Search and Data Mining)"
paperurl: 'https://arxiv.org/abs/2408.12470'
citation: "Chen, Jiaju, et al. \"Dlcrec: A novel approach for managing diversity in llm-based recommender systems.\" Proceedings of the Eighteenth ACM International Conference on Web Search and Data Mining. 2025."
---

### Abstract

The integration of Large Language Models (LLMs) into recommender systems has led to substantial performance improvements. However, this often comes at the cost of diminished recommendation diversity, which can negatively impact user satisfaction. To address this challenge, we propose DLCRec, a novel framework designed to enable fine-grained control over diversity in LLM-based recommendations.

### Key Contributions

Fine-Grained Task Decomposition:  
Unlike traditional methods that rely on simplistic mechanisms, DLCRec breaks down the recommendation process into three sequential sub-tasks: genre prediction, genre filling, and item prediction. This approach ensures more precise control over recommendation diversity according to user-defined preferences.

Robust Data Augmentation:  
To overcome challenges posed by scarce and unevenly distributed diversity-related user behavior data, we introduce two innovative data augmentation techniques. These methods enhance the model's robustness to noisy and out-of-distribution data, improving its adaptability across varying diversity levels.

Superior Performance:  
Our extensive empirical evaluation demonstrates that DLCRec not only provides precise diversity control but also outperforms state-of-the-art baselines across multiple recommendation scenarios, achieving better accuracy-diversity trade-offs.

### Keywords

Controllable Recommendation, Large Language Models, Diversity Management, Task Decomposition, Data Augmentation
