## Problem statement
When processing strings or analyzing text entropy, it is often useful to understand how "resilient" a string is to random deletion processes. The problem is to determine the variance in the number of steps required to completely erase a string when the deletion method involves removing all instances of a randomly selected existing character. This simulation seeks to visualize the randomness and distribution of these steps across a dataset of varying string lengths and character compositions (movie titles).

## Scope of the project
* **Data Source:** The scope is limited to a hardcoded list of approximately 150 popular feature films.
* **Simulation Boundaries:** The simulation runs for exactly 100 iterations (trials).
* **Functionality:** The project focuses on the logic of character set reduction and the visualization of the resulting iteration counts. It does not analyze the correlation between string length and iterations, merely the raw result per trial.

## Target users
* **Python Beginners/Students:** Users learning about loops, list manipulation, and basic plotting.
* **Data Enthusiasts:** Individuals interested in basic stochastic simulations and probability.
* **Educators:** Teachers looking for simple examples of how `while` loops and random choices interact in Python.

## High-level features
* **Dataset Management:** Utilization of a pre-defined string array containing movie titles.
* **Iterative Simulation:** A core loop that performs 100 distinct experiments.
* **Character Reduction Engine:** Logic that identifies unique characters in a string and performs a global replace/remove operation based on a random choice.
* **Result Plotting:** A graphical interface that maps the experimental results (Trial Index vs. Iteration Count) for immediate visual analysis.
