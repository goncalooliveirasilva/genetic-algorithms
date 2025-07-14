# Genetic Algorithms

A growing collection of small projects and notebooks using **Genetic Algorithms (GAs)** to solve various problems.

## Projects
| Notebook | Description |
| -------- | ----------- |
| [evolving_a_string](notebooks/evolving_a_string.ipynb) | Evolves a random string into a target word or sentence using basic GA principles. |
| [knapsack_problem](notebooks/knapsack_problem.ipynb) | Solves the classic Knapsack Problem with comparison to the brute force approach. |


## What are Genetic Algorithms?

Genetic Algorithms are optimization techniques inspired by **natural selection**. They evolve a population of cadidate solutions through:

- **Selection** - choosing the best individuals for reprodution
- **Crossover** - combining parts of parents to create offspring
- **Mutation** - introducing random changes to maintain diversity
- **Fitness Evaluation** - scoring how well each solution performs

They are particularly useful for problems where brute-force or exact methods are **computationally impractical**.

## Running the notebooks
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
## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
