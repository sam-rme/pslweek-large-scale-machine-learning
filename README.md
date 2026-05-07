# PSL Week — Large-Scale Machine Learning (LSML 26)

Practical notebooks from the PSL Spring 2026 intensive course **C2MINES-11 — Large-Scale Machine Learning** held at Mines Paris (March 2–6, 2026), co-organized by Gabriel Victorino Cardoso and Fabien Moutarde.

Each morning was a lecture, each afternoon a hands-on notebook. This repo contains my solutions.

## Notebooks

| # | Notebook | Topic |
|---|---|---|
| 1 | [1_sklearn_at_scale_Samy-RAHMANE.ipynb](1_sklearn_at_scale_Samy-RAHMANE.ipynb) | Scikit-learn at scale: complexity of trees & random forests, parallelization, incremental PCA |
| 2 | [2_generative_models-2.ipynb](2_generative_models-2.ipynb) | Deep unsupervised learning: autoencoders & diffusion models |
| 3a | [3a_tabular_RL-2-2.ipynb](3a_tabular_RL-2-2.ipynb) | Tabular reinforcement learning |
| 3b | [3b_deep_RL-2.ipynb](3b_deep_RL-2.ipynb) | Deep reinforcement learning |
| 4 | [4_RL_preference_learning-3.ipynb](4_RL_preference_learning-3.ipynb) | LLM post-training & preference learning (RLHF / DPO) |
| 5 | [5_deep_double_descent.ipynb](5_deep_double_descent.ipynb) | Stochastic optimization & double descent in neural networks |

## Setup

Python 3.9+ with the usual scientific stack:

```bash
pip install numpy scipy matplotlib pandas scikit-learn joblib memory_profiler torch torchvision jupyterlab
```

For the RL and LLM notebooks a GPU is recommended — Google Colab works well.
