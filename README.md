# Computational Intelligence — Search, Evolutionary Algorithms, and Game-Playing

A collection of academic projects and laboratory exercises exploring computational-intelligence techniques, including heuristic search, local search, evolutionary strategies, genetic algorithms, and game-playing agents.

The repository is organized by exercise rather than as one standalone application. The most substantial themes visible in the current contents are **set-covering optimization** and **decision-making for the Quarto board game**.

## Projects and topics

| Directory | Topic | What it explores |
|---|---|---|
| `Lab1/` | Search for the set-covering problem | Breadth-first search, depth-first search, greedy best-first search, and A*; compares solution weight and number of selected nodes |
| `Lab1_Hill_Climping/` | Local search | Hill-climbing variants, including first-improvement and steepest-step neighborhood search |
| `GA_SetCovering_Problem/` | Genetic algorithms | Mutation, one-cut crossover, elitism, random and tournament parent selection, and offspring/operator parameter experiments |
| `lab2_setCovering+ea/` | Evolutionary strategies | (1+1), (1+λ), (1,λ), and (μ+λ) strategies for set-covering optimization |
| `Lab3_NIM_Game/` | Game exercise | NIM-game implementation and related exercise files |
| `quarto/` | Game-playing agents | Quarto players with heuristic scoring and a Minimax-based approach |
| `Computational_Intelligence_Report_S295805_v2.0.pdf` | Project report | A detailed report associated with the course work |

Individual folders may contain their own README files, code, dependency files, and experiment notes. Consult those folder-level documents for the details of each exercise.

## Getting started

The exercises are separate projects and may have different dependencies. Start by opening the README and dependency configuration in the directory you want to run. Some folders include a `pyproject.toml` and `poetry.lock`; use the environment configuration belonging to that specific exercise rather than assuming one environment works for the whole repository.

For example, to explore the genetic-algorithm project, begin in `GA_SetCovering_Problem/`; for the Quarto agents, begin in `quarto/`.

This repository is an academic collection, not a single installable Python package. A unified root-level installation or test command is not currently documented.

## What this work demonstrates

- Search strategy design and comparison for combinatorial problems
- Local optimization and neighborhood exploration
- Evolutionary computation, selection strategies, mutation, crossover, and elitism
- Hyperparameter experimentation and interpretation of stochastic results
- Heuristic evaluation and game-playing decision logic

## Notes and limitations

- Results recorded in exercise-level READMEs are historical project results; they have not been independently rerun or benchmarked as part of this repository overview.
- Stochastic algorithms can produce different outcomes across runs. Fair comparisons should document random seeds, problem instances, parameter settings, and repeated-run statistics.
- The repository contains multiple course exercises and reports. Before redistributing or presenting the material, ensure that any course-provided code, third-party game framework, and report contents are shared in accordance with their applicable licenses and academic rules.
- For a portfolio presentation, treat this as a supporting collection of classical computational-intelligence work rather than the primary showcase for current LLM/GenAI engineering.

