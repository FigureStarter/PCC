# Prototype-Centroid Collaboration for Budget-Aware Few-Shot Sample Selection
### Overview

![](resources/framework.png)

### Introduction

In practical few-shot learning (FSL) scenarios, it is often necessary to manually annotate a balanced subset of samples with an equal number per class from a large pool of unlabeled data before training the model. However, most existing approaches implicitly assume access to fully labeled datasets, while traditional active learning methods are not inherently designed to operate under the strict $N$-way $K$-shot settings, thus limiting their effectiveness in this context. To bridge this gap, we introduce a new task formulation termed Unsupervised  $N$-way $K$-shot Sample Selection, which explicitly models the sample selection process under FSL constraints, enabling principled evaluation and method development in this context. A key challenge of this task lies in its budget-aware nature, where effective selection must be achieved with limited annotation resources. Furthermore, we propose a novel sample selection framework based on a Prototype-Centroid Collaborative (PCC) strategy, which facilitates efficient and class-balanced sample acquisition under constrained annotation budgets. Extensive experiments demonstrate that our method not only operates effectively under low-budget conditions but also outperforms conventional baselines when full supervision is available.



