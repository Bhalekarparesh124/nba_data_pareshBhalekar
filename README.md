# README: NBA Data Analysis and Algorithms

## Description
This repository contains Python scripts and a Jupyter Notebook designed to perform specific analyses and computations, including:

1. Analyzing NBA data to extract insights such as:
   - The team with the maximum average salary.
   - The college contributing the maximum number of players.
   - The difference between the top 2 highest-paid players.

2. Implementing algorithmic solutions for problems like:
   - Finding the sum of all prime numbers between two numbers.
   - Identifying the 3rd smallest number in an array.

---

## Table of Contents
- [Prerequisites](#prerequisites)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [NBA Data Analysis](#nba-data-analysis)
- [Algorithmic Solutions](#algorithmic-solutions)
  - [Sum of Primes Between Two Numbers](#sum-of-primes-between-two-numbers)
  - [3rd Smallest Number in an Array](#3rd-smallest-number-in-an-array)
- [License](#license)

---

## Prerequisites
- Python 3.x
- Libraries: `pandas`, `numpy`, `matplotlib` (for data analysis and visualization)

---

## Setup and Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/nba-analysis-and-algorithms.git
   ```
2. Navigate to the project directory:
   ```bash
   cd nba-analysis-and-algorithms
   ```
3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage
### Running the Jupyter Notebook
1. Open the notebook in Jupyter:
   ```bash
   jupyter notebook nba_data.ipynb
   ```
2. Execute the cells sequentially to perform NBA data analysis.

### Running the Scripts
1. Run the `sum_of_primes.py` script:
   ```bash
   python sum_of_primes.py
   ```
2. Run the `third_smallest.py` script:
   ```bash
   python third_smallest.py
   ```

---

## NBA Data Analysis
### Questions Addressed:
1. **Get team name which has the maximum average salary**:
   - The script calculates the average salary for each team and identifies the team with the highest average.
2. **Which college has contributed the maximum number of players?**
   - The script aggregates player counts by college and determines the top contributor.
3. **What is the difference between the top 2 salaried players?**
   - The script sorts player salaries and computes the difference between the highest and second-highest salaries.

---

## Algorithmic Solutions
### Sum of Primes Between Two Numbers
The script computes the sum of all prime numbers between two given numbers \(a\) and \(b\) (exclusive).
#### Example Usage:
```python
from sum_of_primes import sum_of_primes

result = sum_of_primes(10, 30)
print(f"Sum of primes between 10 and 30: {result}")
```
#### Output:
```
Sum of primes between 10 and 30: 60
```

### 3rd Smallest Number in an Array
The script finds the 3rd smallest number in an array of integers.
#### Example Usage:
```python
from third_smallest import third_smallest

array = [7, 10, 4, 3, 20, 15]
result = third_smallest(array)
print(f"The 3rd smallest number is: {result}")
```
#### Output:
```
The 3rd smallest number is: 7
```

---

## License
This project is open-source and available under the [MIT License](LICENSE).
