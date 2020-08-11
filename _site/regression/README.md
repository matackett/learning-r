# Regression tutorials

There are three `learnr` tutorials in this directory:

- `tutorial-intro-lm` introduces the `lm` function as applied to simple linear regression and basics of linear regression modeling. The `tidy` and `glance` functions from the `broom` package is also introduced here. Interpretation of coefficient estimates and statistical inference are briefly discussed.
- `tutorial-diag-pred-augment` introduces multiple linear regression, as well as the `augment` function from `broom`. Interpretation of coefficient estimates and statistical inference are briefy discussed, as well as interaction terms and corresponding interpretations. Finally, we use `augment` and `ggplot` to evaluate model diagnostics.
- `tutorial-logistic` introduces logistic regression as a way to create a model for binary outcomes. This tutorial also makes heavy use of the `broom` package.

The `beijing.csv` dataset is used for the linear model tutorials; the `pokemon.csv` dataset is used for the logistic regression tutorial.
