#Bootstrapping

Bootstrapping is a method that uses sampling with replacement to infer statistical results from a population (such as it's mean, median or variance) from results found on a collection of smaller, simulated random samples of that population.
Sampling with replacement occurs when we randomly select an element from a finite population and we "return it" to the population after recording its characteristics. In the case of bootstrapping, we sample with replacement to simulate our bootstrapped datasets.
Bootstrapping requires a considerable amount of computational power but it saves time and resources when studying a population.
Bootsrapping is often used to train machine learning models which are then cross-validated against unseen data of the population.

# Getting Started

The code demonstration explains how the bootstrap method works in the field of statistics. Bootstrapping is a simple alternative method for statistical inference based on re-sampling with replacement. Read more about it on [Wikipedia](https://en.wikipedia.org/wiki/Bootstrapping_(statistics)). 

## Installation
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install numpy and matplotlib.

```bash
pip install numpy
pip install matplotlib
```

Execute the notebook [Bootstrapping - Code Demonstration.ipynb](https://github.com/Lawrence-LUOoo/Bootstrapping-Code-Demonstration/blob/main/Bootstrapping%20-%20Code%20Demonstration.ipynb) cell-by-cell to understand how each part of bootstrapping works.

## Analysis steps
1. simulate population distribution
2. take a random sample from the population
3. bootstrap for 10,000 times
4. analysis and interpretation
5. plot the probability distribution and confidence interval

## Authors:
+ [Ruifeng Luo](https://github.com/Lawrence-LUOoo)
+ [Charudatta Manwatkar](https://github.com/CharudattaManwatkar)
+ [Siew Tsien (Hanna) Lee](https://link-url-here.org)
+ [Camilo Chaves Beltran](https://link-url-here.org)


