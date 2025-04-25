This repository contains the numerical experiments presented in the paper:

[1] Ricardo Ferreira and Cláudia Soares. “Optimal Bounds for Adversarial Constrained Online Convex Optimization.” (2025).

We compare our approaches with the algorithm presented in the paper:

[2] Sinha, Abhishek and Vaze, Rahul, "Optimal Algorithms for Online Convex Optimization with Adversarial Constraints", Advances in Neural Information Processing Systems, 2024.

We present two problems: Online Linear Regression and Online Support Vector Machine. We uploaded two individual notebooks, one for each of the experiments. The notebook "OLR-Experiment.ipynb" allows to generate the synthetic dataset used and run the experiments for the Online Linear Regression problem. The notebook "Wine-Data-Experiment.ipynb" permits to run the experiments for the Online Support Vector Machine problem, however you need to download the public dataset:

[3] Cortez, Paulo, et al. "Modeling wine preferences by data mining from physicochemical properties." Decision support systems 47.4 (2009): 547-553.

You also need to place it in the same directory as the "Wine-Data-Experiment.ipynb" notebook and pre-process the data as described in [1].
