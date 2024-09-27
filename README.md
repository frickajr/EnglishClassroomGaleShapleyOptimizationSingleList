# Modified Gale-Shapley Algorithm for Educational Game Pairing

This project implements a modified version of the Gale-Shapley stable matching algorithm, tailored for forming student pairs in educational settings. The algorithm uses similarity measures, particularly Jaccard similarity coefficients derived from student proficiency and academic performance, to form pairs better aligned in compatibility. Resources and extra documentation for the manuscript "Implementation of Stable Pairing Algorithms for Optimizing Educational Games: A Computational and Pedagogical Perspective," published in IEEE Latin America Transactions. 

## Overview

The main goal of this project is to enhance student collaboration and competition in digital educational games by forming pairs of highly compatible students. The modified Gale-Shapley algorithm works with a single list of participants and uses Jaccard similarity as a compatibility metric. This is particularly useful in educational settings where balanced competition and collaboration can improve learning outcomes.

## Features

- **Modified Gale-Shapley Algorithm**: The algorithm is adapted to work with a single list of participants. It matches participants based on compatibility scores calculated using the Jaccard similarity coefficient.
- **Compatibility Calculation**: Compatibility is calculated using Jaccard similarity, derived from students' proficiency and academic performance tests.
- **Random Pairing for Control**: Besides the modified Gale-Shapley algorithm, random pairings are generated for control experiments.

## Requirements

- Python 3.x
- NumPy for random control pairing
- Additional packages (if any) for handling data and implementing the algorithm (such as Pandas for data management)

