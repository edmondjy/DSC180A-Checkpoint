# DSC180A-Checkpoint
This is a temporary repository until I can get access to the main one by Dr Chi. I created this so that I could submit the assignment on time.

# Improving Relationship Exercises: Exponential and Gamma Distributions

## Project Overview

This project is part of my DSC 180 Capstone Quarter 1 Project at UC San Diego. The goal is to improve an existing Jupyter notebook called *Relationship Exercises*, which introduces students to the relationship between Exponential and Gamma probability distributions.

The original notebook focuses on generating random variables, comparing probability distributions, and investigating the memoryless property through Python simulations.

My goal is to improve the notebook by making the exercises more interactive, providing clearer instructions, introducing real-world examples, and encouraging students to interpret their results rather than only complete calculations.

## Project Objectives

The main objectives of this project are to:

- Improve the clarity and organization of the existing exercises.
- Introduce additional visualizations to demonstrate statistical relationships.
- Add real-world scenarios to connect mathematical concepts to practical applications.
- Encourage students to predict and explain simulation results.
- Make the notebook reproducible so others can run the exercises and obtain comparable results.

## Proposed Notebook Improvements

I developed three additional exercises that build on the original notebook.

Q1.3 - Real-World Applications | Demonstrate how Exponential and Gamma distributions model customer waiting times. 
Q1.4 - Interactive Parameter Exploration | Allow students to observe how changing λ and r affects distribution shapes. 
Q2.4 - Visualizing the Memoryless Property | Use graphs to compare conditional probabilities for Exponential and Gamma distributions. 

I also identified improvements to existing exercises, including clarifying instructions, correcting inconsistent variable names, and improving visualization requirements.

## Data

This project uses simulated data rather than an external dataset.

The data consist of randomly generated samples from Exponential and Gamma probability distributions using Python.

These simulations allow students to compare theoretical results with simulated observations and explore how changing distribution parameters affects waiting times.

No external dataset is required for the newly proposed exercises.

The original notebook may reference additional course-provided files or grading utilities. These must be included separately if required to execute the original assignment in full.

## Software Dependencies

The project uses Python and Jupyter Notebook.

The main Python libraries are:

- NumPy
- SciPy
- Matplotlib
- ipywidgets 
- JupyterLab

These dependencies should be listed in a `requirements.txt` file.


### Reproduce the results

The exercises generate random samples using NumPy and compare simulated results with theoretical statistical relationships.

For example, the expected value of a Gamma distribution with shape r and rate λ is:

\[
E[X] = \frac{r}{\lambda}
\]

Simulation results should be approximately equal to theoretical values. Small differences may occur because the samples are randomly generated.

Where random seeds are specified, the same software environment and seed can be used to reproduce the same simulation results.






