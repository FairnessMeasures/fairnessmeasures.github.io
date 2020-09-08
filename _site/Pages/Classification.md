# Fairness Classification Algorithms
There are circumstances in which the output is binary. Take for example, the output by bail decisions
would be either 'jail' or 'release'. This kind of algorithm falls into the category of classification.
You may find a classification algorithm implementing the following measures on our 
[GitHub repository](https://github.com/megantosh/fairness_measures_code/tree/master). To be consistent with 
convention, **positive outcome** is considered as the desired one for a certain candidate in a group, 
e.g. being granted a loan given a certain credit score (**target score**).


## Absolute Measures  

### Mean Difference
The difference between the target score mean values of the protected vs. unprotected groups.
_No difference = no discrimination_

### Normalized Difference
The mean difference for binary classification normalized by the rate of positive outcomes.
_At a given positive outcome rate, maximum possible discrimination is taken into account_

### Impact Ratio
The ratio of positive outcomes for the protected group over the non-protected group.

### Odds Ratio
The association between exposure and outcome

## Statistical Tests  

### Difference of Means _a.k.a. Welch-Test_
For a null hypothesis that the **means of the two groups** (protected and non-protected) are equal.
### Difference in proportions for two groups _a.k.a. Fisher's exact test_
For a null hypothesis that the **rates of positive outcomes** within the two groups are equal.

## References
Measures above can be found in the following paper: 
Žliobaitė, Indrė. "[Measuring discrimination in algorithmic decision making](https://link.springer.com/article/10.1007%2Fs10618-017-0506-1)" Data Mining and Knowledge Discovery 31, no. 4 (July 31, 2017): 1060-089. doi:10.1007/s10618-017-0506-1. 
 <i>[bibtex](https://citation-needed.springer.com/v2/references/10.1007/s10618-017-0506-1?format=bibtex&flavour=citation)</i>
