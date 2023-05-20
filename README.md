#  Neural Architecture Search with early stopping

**Author:** Kovaleva Maria

The work is dedicated to the problem of neural architecture search. The main problem of neural architecture search optimization algorithms is the time, which they spend. We propose to solve this problem by early stopping. We consider early stopping criteria based on the change point detection algorithm CUSUM and add this early stopping to the popular hyperparameters optimization algorithm Hyperband [1]. Proposed method was tested at nas-bench nlp и cifar10 benchmarks. Our method found better architectures for the less time.

Also we considered classification task of model to be in the top 5% and regression task of prediction of the final loss function.

[1] Li, L. et al. (2018) Hyperband: A novel bandit-based approach to hyperparameter optimization, arXiv.org. Available at: https://arxiv.org/abs/1603.06560 (Accessed: 18 May 2023). 

[Draft with literature review and preliminary results](https://docs.google.com/document/d/1A0nhXXczofwsRUDMEmy6MImaiPf9JAJ5CazqGcetn5Q/edit?usp=sharing)

[Presentation](https://github.com/MarKovka20/Project_reseach/blob/main/presentation.pdf)




