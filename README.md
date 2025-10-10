# 🧬 Genetic Algorithms Collection

A curated set of small projects and Jupyter notebooks exploring **Genetic Algorithms** (GAs) for solving optimization problems.

## 📚 Projects

| Notebook                                                            | Description                                                                       |
| ------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
| [01 - Evolving a String](notebooks/01_evolving_a_string.ipynb)      | Evolves a random string into a target word or sentence using basic GA principles. |
| [02 - Knapsack Problem](notebooks/02_knapsack_problem.ipynb)        | Solves the classic Knapsack Problem with comparison to the brute force approach.  |
| [03 - Travelling Salesman Problem (TSP)](notebooks/03_tsp_ga.ipynb) | Find near-optimal routes between cities.                                          |

## 🧠 What are Genetic Algorithms?

Genetic Algorithms (GAs) are bio-inspired optimization techniques that mimic the process of natural selection.  
They iteratively improve a population of potential solutions using:

- 🧩 Selection — choose the fittest individuals for reproduction
- 🔀 Crossover — combine genes (solutions) from parents to produce new offspring
- 🎲 Mutation — introduce random changes to maintain genetic diversity
- 🏅 Fitness Evaluation — score how well each solution solves the problem
  > 💡 GAs are ideal for problems where brute-force or analytical methods are computationally infeasible (e.g., NP-hard problems).

## 🚀 Getting Started

1. Clone this repo

```bash
git clone git@github.com:goncalooliveirasilva/genetic-algorithms.git
cd genetic-algorithms
```

2. Create and activate Conda environment (optional)

```bash
conda env create -f environment.yml
conda activate ga-env
```

3. Launch Jupyter

```bash
jupyter lab
```

## ⚖️ License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
