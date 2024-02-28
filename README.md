# Auto-ML-Bayesian-Optimization
This repo implements different hyperparameter tuning with different techniques: Grid Search - Random Search - Bayesian Optimization.

Implementations:

1.Choosing a supervised learning algorithm with a large number of hyperparameters.

2.Selecting a data set and an objective function for evaluating the algorithm.

3.Implementing the Bayesian optimization algorithm.

4.Comparing the Bayesian optimization algorithm with random search.

5.Visualizing the space of tested hyperparameter values. Color indicates the value of the objective function on them.

6.Visualizing the value of the objective function depending on the step number.

## A. the chosen supervised learning algorithm: Gradient Boosting
~~~
GradientBoostingClassifier(n_estimators=int(hyp_params[0]), learning_rate=hyp_params[1],
    subsample = hyp_params[2], min_samples_split = hyp_params[3],
    min_weight_fraction_leaf = hyp_params[4], max_depth = int(hyp_params[5]),
    random_state=0).fit(X_train, y_train)
~~~
## B. Comparison results:

![image](https://github.com/ghfranj/Auto-ML-Bayesian-Optimization/assets/98123238/a9e0885e-434e-4817-b784-6ea4860fb6d2)


