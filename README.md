# FLPMP
This repository contains the data files used in the computational experiments for the scientific paper:

> **A bilevel approach to the facility location problem with customer preferences under a mill pricing policy**  
> Authors: Herminia I. Calvete, Carmen Galé, Aitor Hernández and José A. Iranzo  
> Journal: Mathematics  
> DOI: to be assigned

Each `FLPMP_*.txt` file has the following structure:

- **First line**: Two integers, `m` and `n`, where:
  - `m` represents the number of customers.
  - `n` represents the number of facilities.
- **Following line**: The word `costs`.
- **Next `m` lines**: A matrix of size `m x n` containing the travel cost from each customer to each faility.
- **Following line**: The word `budgets`.
- **Following line**: A vector of length `m` containing customer's budgtes.
- **Following Line**: The word `preferences`.
- **Next `m` Lines**: A matrix of size `m x n` containing the customer's preferences.
