# CCPX4199-DotStim-Visualization
This project uses PsychoPy to create a random dot motion task and Matplotlib to visualize individual performance.

## Task Description
Participants will be presented with moving dots and asked to identify whether the predominant direction of motion is left or right using the arrow keys. The task includes five coherence levels (0.05, 0.1, 0.2, 0.4, and 0.8), representing different proportions of dots moving in the same direction. The experiment records response accuracy, reaction time, and fixation duration.

## Visualization
The script generates three graphs:
  1. **Scatterplot**: Shows the relationship between coherence and reaction time, with colors representing correct and incorrect responses.
  2. **Histogram**: Shows the distribution of reaction times.
  3. **Bar Chart**: Shows response accuracy (%) across different motion coherence levels.

## How to Run
Run the script in a Python environment with the required libraries installed (PsychoPy, Pandas, Matplotlib, and openpyxl). Use the left and right arrow keys to complete the task. Once the experiment is finished, three performance graphs will be displayed.
