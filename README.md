# Probability Project: Random Assignment Problem

## Index
1. [Overview](#overview)
2. [Key Information](#key-information)
3. [Project Files](#project-files)
4. [Computational Limitations](#computational-limitations)
5. [Conclusion](#conclusion)

## Overview
This project is developed as part of the "Probability for Data Science" course within the MSc in Data Science program. It focuses on solving the Random Assignment Problem using the Metropolis-Hastings algorithm.

## Key Information
- **Goal**: Apply the Metropolis-Hastings algorithm to effectively address the Random Assignment Problem.
- **Documentation**: All supplementary explanations, including variable descriptions, are available in the PDF file [here](Project_P_DS_Random_assignment.pdf).

## Project Files
- **Problem Contextualization**: Detailed in [problem_contextualization.ipynb](problem_contextualization.ipynb), this file analyzes the impact of the variables $\beta$ and $N$ on the project outcomes. For further details on these variables, refer to the associated PDF document.
- **Simulations and Results**: The core simulations are contained in [simulations_random_assignment.ipynb](simulations_random_assignment.ipynb). This notebook varies the parameters $\beta$, $N$, $M$, $n$ to explore different scenarios. Each variable's role and significance are discussed extensively in the provided PDF.

## Computational Limitations
Due to the intense computational demand of the Metropolis-Hastings algorithm, especially for larger values of $n$ (e.g., $n = 20$ requiring up to $10,000,000$ steps), the simulations were limited to smaller scales:
- **Tested Values**: $n = \{5, 10, 15, 20\}$
- **Steps Performed**: $N = 100,000$

**Note**: At $n = 20$, the limited number of steps does not achieve the asymptotic limit, impacting the precision of the results.

## Conclusion
This project underscores the computational challenges inherent in applying complex algorithms like Metropolis-Hastings at scale, and provides insights into the probabilistic modeling techniques used in data science.