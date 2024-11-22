---
title: "Treatment Effect Estimation for User Interest Exploration on Recommender Systems"
collection: publications
category: conferences
permalink: https://dl.acm.org/doi/10.1145/3626772.3657736
excerpt: 'Recommender Systems, User Interest Exploration, Treatment Effect
Estimation, Multivariate Continuous Treatments'
date: 2024-07-11
venue: 'GitHub Journal of Bugs'
paperurl: 'https://arxiv.org/abs/2405.08582'
citation: '@inproceedings{10.1145/3626772.3657736,
author = {Chen, Jiaju and Wenjie, Wang and Gao, Chongming and Wu, Peng and Wei, Jianxiong and Hua, Qingsong},
title = {Treatment Effect Estimation for User Interest Exploration on Recommender Systems},
year = {2024},
isbn = {9798400704314},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3626772.3657736},
doi = {10.1145/3626772.3657736},
abstract = {Recommender systems learn personalized user preferences from user feedback like clicks. However, user feedback is usually biased towards partially observed interests, leaving many users' hidden interests unexplored. Existing approaches typically mitigate the bias, increase recommendation diversity, or use bandit algorithms to balance exploration-exploitation trade-offs. Nevertheless, they fail to consider the potential rewards of recommending different categories of items and lack the global scheduling of allocating top-N recommendations to categories, leading to suboptimal exploration. In this work, we propose an Uplift model-based Recommender (UpliftRec) framework, which regards top-N recommendation as a treatment optimization problem. UpliftRec estimates the treatment effects, i.e., the click-through rate (CTR) under different category exposure ratios, by using observational user feedback. UpliftRec calculates group-level treatment effects to discover users' hidden interests with high CTR rewards and leverages inverse propensity weighting to alleviate confounder bias. Thereafter, UpliftRec adopts a dynamic programming method to calculate the optimal treatment for overall CTR maximization. We implement UpliftRec on different backend models and conduct extensive experiments on three datasets. The empirical results validate the effectiveness of UpliftRec in discovering users' hidden interests while achieving superior recommendation accuracy.},
booktitle = {Proceedings of the 47th International ACM SIGIR Conference on Research and Development in Information Retrieval},
pages = {1861–1871},
numpages = {11},
keywords = {multivariate continuous treatments, recommender systems, treatment effect estimation, user interest exploration},
location = {Washington DC, USA},
series = {SIGIR '24}
}'
---

Recommender systems learn personalized user preferences from user feedback like clicks. However, user feedback is usually biased towards partially observed interests, leaving many users' hidden interests unexplored. Existing approaches typically mitigate the bias, increase recommendation diversity, or use bandit algorithms to balance exploration-exploitation trade-offs. Nevertheless, they fail to consider the potential rewards of recommending different categories of items and lack the global scheduling of allocating top-N recommendations to categories, leading to suboptimal exploration. In this work, we propose an Uplift model-based Recommender (UpliftRec) framework, which regards top-N recommendation as a treatment optimization problem. UpliftRec estimates the treatment effects, i.e., the click-through rate (CTR) under different category exposure ratios, by using observational user feedback. UpliftRec calculates group-level treatment effects to discover users' hidden interests with high CTR rewards and leverages inverse propensity weighting to alleviate confounder bias. Thereafter, UpliftRec adopts a dynamic programming method to calculate the optimal treatment for overall CTR maximization. We implement UpliftRec on different backend models and conduct extensive experiments on three datasets. The empirical results validate the effectiveness of UpliftRec in discovering users' hidden interests while achieving superior recommendation accuracy.
