# The-Bootstrap-and-the-Normal-Curve

This is part of the exercise that I have done on a course Data Science (Data-8), a UCBerkely university course program. 

In this exercise, we will explore a dataset that includes the safety inspection scores for restauraunts in the city of Austin, Texas. We will be interested in determining the average restaurant score (out of 100) for the city from a random sample of the scores. We'll compare one method for computing a confidence interval for that quantity: the bootstrap resampling method. 

In statistics, bootstrapping is any test or metric that relies on random sampling with replacement. Bootstrapping allows assigning measures of accuracy (defined in terms of bias, variance, confidence intervals, prediction error or some other such measure) to sample estimates. This technique allows estimation of the sampling distribution of almost any statistic using random sampling methods. Generally, it falls in the broader class of resampling methods (Wikipedia).

Bootstraping follows simple steps for generating another samples that resembles the population observation. 

1. Treat the original sample as if it were the population.
2. Draw from the sample, at random with replacement, the same number of times as the original sample size.

Note: resampling the same number of times (n) as the original (first sample size) is important. This is because the variability of an estimated sample depends on the size of the sample itself.  

In this exercise I have used datascience library to complete the bootstraping.
