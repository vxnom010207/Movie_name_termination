# Movie Title Erasure Simulation

## Overview of the project
This project is a Python-based simulation that analyzes the statistical probability and iteration count required to "erase" a movie title string. By randomly selecting a character present in the string and removing all instances of that character, the script calculates how many steps it takes to reduce the string to an empty state. It performs this simulation over 100 trials using a curated list of popular movie titles and visualizes the results.

## Features
* **Randomized Dataset Selection:** Selects from a diverse list of over 100 popular movie titles for every trial.
* **Stochastic Reduction Logic:** Implements a "unique character" removal algorithm where a random character is chosen from the remaining unique characters to clear the string.
* **Data Visualization:** Generates a line graph plotting the number of iterations required for each of the 100 trials.
* **Console Logging:** Provides real-time feedback in the terminal, showing the selected movie name and the total iterations for that specific run.

## Technologies/tools used
* **Programming Language:** Python 3
* **Numerical Computing:** NumPy (`numpy`)
* **Data Visualization:** Matplotlib (`matplotlib.pyplot`)
* **Standard Libraries:** `random`, `string`

## Steps to install & run the project

1.  **Prerequisites:** Ensure you have Python installed on your machine.
2.  **Clone/Download:** Save the script file (e.g., `main.py`) to your local directory.
3.  **Install Dependencies:** Open your terminal or command prompt and install the required external libraries:
    ```bash
    pip install numpy matplotlib
    ```
4.  **Run the Application:** Execute the script using Python:
    ```bash
    python main.py
    ```

## Instructions for testing
To verify the application is working correctly:
1.  Run the script.
2.  **Console Verification:** Check the terminal output. You should see a list of movie titles printed, followed by "Iterations to empty name: X" for 100 distinct entries.
3.  **Visual Verification:** A window should pop up displaying a line graph.
    * **X-Axis:** Should range from 0 to 100 (representing the trial number).
    * **Y-Axis:** Should represent the number of iterations (steps) taken to clear the name.
4.  **Logic Check:** Ensure the graph lines correlate with the console output (e.g., if the console says a movie took 15 iterations, the corresponding point on the graph should be at Y=15).

## Screenshots
<img width="638" height="545" alt="image" src="https://github.com/user-attachments/assets/d4e14f74-8a8d-486e-91b3-cc4cb386d295" />
