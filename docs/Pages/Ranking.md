# Fair Ranking Algorithms
It is crucial that the decision-making algorithms are fair, that they do not systematically 
transmit or amplify the already existing biases in today's society. Researchers in the field of 
fairness algorithms have provided various possible ranking algorithms. We cite a few examples
here.

## FairSearch: An Open-source Library for Fairness Notions in Search 
This project constitutes the first [fair open source search API](https://github.com/fair-search) to provide fairness notions in ranked search results. It implements two algorithms from the fair ranking literature, namely FA\*IR (Zehlike et al., 2017) and DELTR (Zehlike et al.,
2018). Those are available as stand-alone libraries in Python and Java. Additionally the authors implement interfaces to Elasticsearch for both algorithms. The interfaces enable search engine developers who wish to ensure fair search
results of different styles to easily integrate DELTR and FA\*IR into their existing Elasticsearch environment.

## Fair Top-k Ranking Algorithm
Zehlike et al provided an algorithmic solution to the Fair Top-k Ranking problem over a
single binary type attribute. With respect to the group fairness criteria, they provided
a greedy algorithm which selects the best k candidates from a large pool while ensuring 
maximal utility.


## Designing Fair Ranking Schemes
Asudeh et al. have focused on designing fair scoring functions by assigning a weighted 
sum of numeric attribute values to each item.


## Fairness of Exposure in Rankings
Singh and Joachims have proposed a general framework of fairness constraints that employs 
probabilistic rankings and linear programming, allowing the computation of the utility-
maximising ranking.

## Ranking with Fairness Constraints
Celis et al. provided a linear time approximation algorithm of the ranking problem in ethical
data processing.


### References

The above described algorithms can be found in following literature:

Zehlike, Meike, Tom Sühr, Carlos Castillo, and Ivan Kitanovski. "[FairSearch: A Tool For Fairness in Ranked Search Results.](https://arxiv.org/pdf/1905.13134.pdf)" arXiv preprint arXiv:1905.13134 (2019).

Zehlike, Meike, Gina-Theresa Diehn and Carlos Castillo. "[Reducing disparate exposure in ranking: A learning to rank approach.](https://arxiv.org/pdf/1805.08716.pdf)" arXiv preprint arXiv:1805.08716 (2018).

Zehlike, Meike, Francesco Bonchi, Carlos Castillo, Sara Hajian, Mohamed Megahed, and Ricardo Baeza-Yates. "[Fa* ir: A fair top-k ranking algorithm.](https://dl.acm.org/citation.cfm?id=3132938)" Proceedings of the 2017 ACM on Conference on Information and Knowledge Management. doi:10.1145/3132847.3132938. 
<a href="Files/bib/Fair.bib">bibtex</a>

Asudeh, Abolfazl, H. V. Jagadish, Julia Stoyanovich, and Gautam Das. "[Designing Fair Ranking Schemes](https://arxiv.org/abs/1712.09752)."arXiv preprint arXiv:1712.09752 (2017). <a href="Files/bib/asudeh.bib">bibtex</a>

Singh, Ashudeep, and Thorsten Joachims. "[Fairness of Exposure in Rankings](https://arxiv.org/abs/1802.07281)." arXiv preprint arXiv:1802.07281 (2018).<a href="Files/bib/singh.bib">bibtex</a>

Celis, L. Elisa, Damian Straszak, and Nisheeth K. Vishnoi. "[Ranking with fairness constraints](https://arxiv.org/abs/1704.06840)." arXiv preprint arXiv:1704.06840 (2017).<a href="Files/bib/celis.bib">bibtex</a>




