---
title: "Treatment Effect Estimation for User Interest Exploration on Recommender Systems"
collection: publications
category: conferences
permalink: /publication/SIGIR'24
excerpt: 'An uplift model-based framework that optimizes category exposure in recommendations through causal treatment effect estimation, effectively discovering hidden user interests while maximizing engagement.'
date: 2024-07-11
venue: "SIGIR 2024 (The 47th International ACM SIGIR Conference on Research and Development in Information Retrieval)"
paperurl: 'https://arxiv.org/abs/2405.08582'
citation: "Chen, J., Wenjie, W., Gao, C., Wu, P., Wei, J., & Hua, Q. (2024, July). Treatment Effect Estimation for User Interest Exploration on Recommender Systems. In Proceedings of the 47th International ACM SIGIR Conference on Research and Development in Information Retrieval (pp. 1861-1871)."
---

## Abstract

Recommender systems learn personalized user preferences from user feedback such as clicks. However, user feedback is typically biased towards partially observed interests, leaving many hidden interests unexplored. Existing approaches often mitigate bias or increase diversity but fail to strategically consider the potential rewards of recommending different item categories. We address this gap with **UpliftRec**, a novel framework that transforms top-N recommendation into a treatment optimization problem.

## Key Contributions

**Causal Treatment Effect Estimation:**  
UpliftRec estimates treatment effects—specifically, the click-through rate (CTR) under different category exposure ratios—using observational user feedback. This causal inference approach enables more informed decision-making about content allocation.

**Hidden Interest Discovery:**  
By calculating group-level treatment effects, UpliftRec effectively discovers users' hidden interests that yield high CTR rewards. The framework leverages **inverse propensity weighting** to alleviate confounder bias, ensuring more accurate estimations.

**Optimal Global Scheduling:**  
UpliftRec employs a dynamic programming method to compute the optimal treatment strategy for overall CTR maximization. This global scheduling approach allocates top-N recommendations across categories more effectively than existing methods.

**Robust Empirical Validation:**  
We implement UpliftRec on various backend models and conduct extensive experiments across three real-world datasets. The results consistently demonstrate UpliftRec's effectiveness in exploring users' hidden interests while achieving superior recommendation accuracy.

## Keywords

Recommender Systems, User Interest Exploration, Treatment Effect Estimation, Causal Inference, Multivariate Continuous Treatments, Uplift Modeling
