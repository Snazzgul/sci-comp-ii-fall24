# Week 2 HW

The purpose of this assignment is to get exercise some basic sampling skills, focusing on rejection and importance sampling.

Take the following probability density function:
```math
p(x) = 0.164\exp{\left(-\frac{(x-10)^4}{2\cdot 8^2}\right)}
```

1. Use _rejection sampling_ to draw 1000 samples from this distribution.  Show that the samples you've drawn are correctly distributed according to this probability density function.

2. Use _importance sampling_ to estimate the expectation value of $x$, and compare it to the mean of the samples you drew in part 1.

3. Calculate the expectation value of $x^2$.

## Grad students:

Revisit the importance sampling example from the Intro to Sampling notebook from class.  There we demonstrated the use of importance sampling to estimate the expectation value of some function of our random variable.  We could also use the weights we computed to probabilistically choose samples from the sampling distribution to keep, in an effort to "reweigh" the sampling distribution to correspond to the target distribution.  Try to implement this, and see if your resampled distribution's histogram matches the target distribution's probability density function.
