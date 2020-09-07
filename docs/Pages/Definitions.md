# Fairness Definitions in Machine Learning
What does it actually mean for an algorithm to be fair? Different researchers have
used different notions of algorithmic fairness. We provide here three different ways 
of classifying fairness.

## Group versus Individual Fairness
### Group Fairness
It is also refered to as statistical parity. It is a requirement that the protected
groups should be treated similarly to the advantaged group or the populations as a whole. 

### Individual Fairness
It is a requirement that individuals should be treated consistently. 

#### Comparison between Group & Individual Fairness
Group fairness does not consider the individual merits and may result in choosing the 
less qualified members of a group, whereas individual fairness assumes a similarity metric
of the individuals for the classification task at hand that is generally hard to find.

## User versus Content Biases
### User Bias
This appears when different users receive different content based on user attributes
that should be protected, such as gender, race, ethnicity, or religion.
### Content Bias
It refers to biases in the information received by any user. Take for example,
when some aspect is disproportionately represented in a query result or in news feeds.

## Direct versus Indirect Discrimination
### Direct Discrimination
This consists of rules or procedures that explicitly mention minority or disadvantaged
groups based on sensitive discriminatory attributes related to group membership. 
### Indirect Discrimination
This consists of rules or procedures that, while not explicitly mentioning discriminatory
attributes, intentionally or unintentionally could generate discriminatory decisions. 
It exists due to the correlation of the non-discriminatory items with the discriminatory ones.

### References

These definitions of fairness can be found in following literature:

Zehlike, Meike, et al. "[Fa* ir: A fair top-k ranking algorithm](https://dl.acm.org/citation.cfm?id=3132938)" Proceedings of the 2017 ACM on Conference on Information and Knowledge Management. doi:10.1145/3132847.3132938. 
<a href="Files/bib/Fair.bib">bibtex</a>

Pitoura, Evaggelia et al. "[On measuring Bias in Online Information](https://arxiv.org/abs/1704.05730)."	doi:10.1145/3186549.3186553 . <a href="Files/bib/pitoura.bib">bibtex</a>

Hajian, Sara et al. "[Algorithmic Bias: From Discrimination Discovery to Fairness-aware Data Mining](https://dl.acm.org/citation.cfm?id=2945386)." doi:10.1145/2939672.2945386 .<a href="Files/bib/hajian.bib">bibtex</a>

