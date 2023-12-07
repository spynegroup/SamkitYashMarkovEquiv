# An Investigation into the Markov Equivalence Class Problem in Bayesian Networks

### B.Tech Project 
### Mentor : Dr Saptarshi Pyne

## **Objective**
When predicting the underlying model of a given dataset, the ‘Markov equivalence class problem in Bayesian networks’ can lead to extremely misleading models.
In this project, we aim to review the literature and demonstrate the problem with a benchmark dataset. This project will be our first step to overcoming the problem.

## **The Markov equivalence class problem in Bayesian networks**
- The Bayesian network ‘structure learning’ algorithms usually find a DAG with the maximal likelihood score given a dataset.
- If two DAGs belong to the same Markov equivalence class, then they are statistically indistinguishable. Therefore, they will have the same likelihood score.
- If there is a tie between Markov equivalent DAGs, the existing algorithms break the ties by randomly selecting one of them. The result could be extremely misleading.  

## **Which DAGs are Markov equivalent?**
Andersson et al. proved that two DAGs are Markov equivalent if and only if they
- have the same underlying undirected structure (known as the ‘skeleton’) and
- the same ‘immorality’ sub-structures 
