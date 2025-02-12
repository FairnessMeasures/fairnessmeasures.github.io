<!--
# About the Program
-->

<ul>
    <li> [view on Github](https://github.com/FairnessMeasures/fairness-measures-code) </li>
</ul>


This project quantifies the fairness distribution of rankings in a dataset using simple statistical functions,
e.g. Mean Average, as well as more advanced such as group fairness rankings. Fairness is measured for example if there is an equal distribution of protected and non-protected attributes in a dataset.
Given a dataset with already definded protected attributes (e.g. sex, race, age) as an input, the output is the score of a function measuring the respective statistical key figure
(e.g. Mean Value, Kendall's Tau) with respect to the protected elements. More details are available in the respective functions, please refer to the code comments.


## Getting Started
1. Packages accept datasets that already have a calculated score indicating a ranking.
2. to use a dataset, each feature should be represented in a column with the first entry as the column name.
Protected attributes require the prefix ``protected``. The column to be examined requires the prefix ``target``.
For example, if you need to measure fairness rankings of a dataset with the columns ``sex`` and ``credit_score``,
please rename the first columns e.g. to ``protected_sex`` and ``target_credit_Score``

### Prerequisites

* python version 3.5+
* dataset to examine in csv format with features as described [above](##Getting Started)

<!--maybe put python version checker for unix and windows terminal?
@mega: included now in Main.py
-->

### Installing

* clone repository
* put into python path

```
command line code for both steps
```

And repeat

```
until finished
```

## Running first example
* go to src/
* call main.py to perform t-test on small example dataset
```
python3 main.py
```
* call main.py with your dataset file to perform t-test on your data
```
python3 main.py /PATH/TO/YOUR/CSV/FILE
```

## Running the tests

* unittests for the system
* go to test/
* call ```python3 runner.py```


## Contributing

* write how people can participate in the project. Codes of Conduct?

## Versioning

* Do we have any special versioning tools? I guess it's just git, right?

## Authors

* **Meike Zehlike** - *Initiator* - [MilkaLichtblau](https://github.com/MilkaLichtblau)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the GPL License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* cite Zliobaite paper here as inspiration
* Hat tip to anyone who's code was used
* more inspiration
* etc


<!--
# How to Install

# How to run

# License
make sure access rights are correct
-->