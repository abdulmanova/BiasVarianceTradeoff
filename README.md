# BiasVarianceTradeoff
<p>Mean square error of each machine learning model could be decomposed
into a sum of squared bias, variance and noise (also called irreducible error).
Bias is an error which refers to generalizing a true function. Solving a real life
problem, a true function might never be approached, therefore, we simplify a
model so it would catch a general trend. Low bias suggests a more complicated
target function and high bias refers to less complex one. Variance defines how
flexible a model is if different datasets were applied. We expect a model to
produce proper results despite various training datasets. If variance is high, then
large changes will be observed given different datasets and if variance is low, it
implies that a function is generalized enough. Bias and variance is a tradeoff, as
a rule, the more flexible the model becomes the variance increases and the bias
decreases.</p>
<p>When assessing performance of a model, we would want to achieve low
bias and low variance. With high bias and low variance the problem of
underfitting occurs since a model did not catch a required pattern; with low bias
and high variance overfitting happens because a model becomes too complex
and sensitive to noisy data. Concluding all above, being aware of variance and
bias of a model is a credible way to estimate whether a model over- or underfits.</p>
