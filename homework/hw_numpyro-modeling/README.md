# Modeling w/ NumPyro

1. Use `NumPyro` to define a model containing a single random variable that follows a [Gamma](https://en.wikipedia.org/wiki/Gamma_distribution) [distribution](https://num.pyro.ai/en/stable/distributions.html#gamma) with shape parameters $\alpha=5$, $\beta=0.1$.  First draw samples directly from the distribution and plot the histogram and/or KDE.

2. Using the samples you've drawn, compute the mean and variance of the random variable. Modify the shape parameters individually to see how each of them affect the mean and variance of the distribution.

3. The Gamma distribution doesn't have support for negative values, making it a useful prior distribution for parameters that must be positive. Use `NumPyro` to conduct an MCMC sampling of our linear regression model with outliers from class, but replace the half-normal priors for standard deviation parameters with sensible gamma distributions (i.e., not dramatically different in scale from the half-normal distributions previously used). Does the change in prior distribution meaningfully change the posterior distributions?

## 564 students
Repeat the Gaia linear regression analysis from the 564 portion of last week's homework, this time using `NumPyro`.

1. How do your results compare?
2. How about the efficiency of sampling?
3. Use the posterior predictive framework in `NumPyro` to simulate a new Gaia catalog from your model and posterior estimate.  How does it compare to the observed data?  How might we improve our model?