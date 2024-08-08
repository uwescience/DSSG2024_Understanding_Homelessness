---
layout: page
title: Method 2
---


## RDS-II (Volz-Heckathorn Estimator)

The RDS-II (Volz-Heckathorn) estimator is used to approximate population proportions in Respondent-Driven Sampling (RDS) studies. The estimator is based on the idea that the probability of selection is proportional to the degree of each respondent, which reflects their number of contacts within the target population.

### Formula

The RDS-II estimator for the population proportion \(\hat{\mu}_{VH}\) is given by:

\[
\hat{\mu}_{VH} = \frac{\sum_{i} \frac{S_i}{d_i} z_i}{\sum_{i} \frac{S_i}{d_i}}
\]

where:
- \(\hat{\mu}_{VH}\) is the estimated population proportion.
- \(S_i\) is the sample size for respondent \(i\).
- \(d_i\) is the degree (number of contacts) of respondent \(i\).
- \(z_i\) is the value of the variable of interest for respondent \(i\).

### Explanation

- **Degree Proportionality:** The estimation assumes that the probability of selection is proportional to the respondent's degree (\(d_i\)). This means that respondents with more contacts are more likely to be selected.
- **Weights:** The term \(\frac{S_i}{d_i}\) acts as a weight, adjusting for the fact that respondents with higher degrees (more contacts) are given more influence in the estimation process. This corrects for biases introduced by the network-based sampling.
- **Numerator:** The numerator \(\sum_{i} \frac{S_i}{d_i} z_i\) aggregates the weighted values of the variable of interest (\(z_i\)). This ensures that respondents with more contacts contribute more to the estimate.
- **Denominator:** The denominator \(\sum_{i} \frac{S_i}{d_i}\) normalizes the weights to produce the final proportion estimate. It ensures that the weights are properly scaled to give a proportionate estimate of the population.

This estimator helps in providing more accurate estimates of population proportions by accounting for the network-based sampling design and variations in respondent degrees.
