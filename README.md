# Modified Gale-Shapley Algorithm for Educational Game Pairing

This project implements a modified version of the Gale-Shapley stable matching algorithm, tailored for forming student pairs in educational settings. The algorithm uses similarity measures, particularly Jaccard similarity coefficients, derived from student proficiency and academic performance, to form pairs that are better aligned in terms of compatibility. This README file will guide you through understanding, setting up, and running the code for this project.

## Overview

The main goal of this project is to enhance student collaboration and competition in digital educational games by forming pairs of students with high compatibility. The modified Gale-Shapley algorithm works with a single list of participants and uses Jaccard similarity as a compatibility metric. This is particularly useful in educational settings where balanced competition and collaboration can lead to improved learning outcomes.

## Features

- **Modified Gale-Shapley Algorithm**: The algorithm is adapted to work with a single list of participants. It matches participants based on compatibility scores, calculated using the Jaccard similarity coefficient.
- **Compatibility Calculation**: Compatibility is calculated using Jaccard similarity, derived from students' proficiency and academic performance tests.
- **Random Pairing for Control**: In addition to the modified Gale-Shapley algorithm, random pairings are generated for control experiments.

## Requirements

- Python 3.x
- NumPy for random control pairing
- Additional packages (if any) for handling data and implementing the algorithm (such as Pandas for data management)

