# 06-325 Numerical Methods and Machine Learning for Chemical Engineering - Fall 2025 mini-course

This is the repository for **06-325 – Numerical Methods and Machine Learning for Chemical Engineering**. 

It contains the notebooks, datasets, slide decks, and images used throughout the course. 

For announcements, detailed policies, and the official syllabus, visit the course site at [victor-alves.com/06325-Numerical-Methods-and-ML-for-ChemE](https://victor-alves.com/06325-Numerical-Methods-and-ML-for-ChemE).

## Weekly lecture roadmap
| Week   | Class # | Topic |
|--------|---------|-------|
| Week 1 | 1       | **Course Introduction & Python Foundations**<br>- Course roadmap<br>- Introduction to Python, Jupyter IDE and SciPy<br>- NumPy arrays<br>- Functions and control flows<br>- Plotting with Matplotlib<br>- Linear functions and systems of equations |
| Week 1 | 2       | **Nonlinear Functions & Root Finding**<br>- Bisection (`scipy.optimize.bisect`)<br>- Newton-Raphson (`scipy.optimize.newton`)<br>- Systems of nonlinear equations |
| Week 2 | —       | **No Class** – University Closed (Labor Day) |
| Week 2 | 3       | **Optimization**<br>- Newton’s method<br>- `scipy.optimize.minimize`<br>- Curve fitting / interpolation<br>- Derivative-free optimization |
| Week 3 | 4       | **Differential Equations**<br>- Euler's method (motivation and derivation)<br>- `scipy.solve_ivp` basics<br>- Events<br>- Forcing functions |
| Week 3 | 5       | **Differential Equations II**<br>- ODE systems<br>|
| Week 4 | 6       | **ML I – Concepts and Introduction**<br>- Model validation<br>- Feature engineering<br>- Train / validation / test split<br>- Linear Regression<br>- Decision Trees  |
| Week 4 | 7       | **ML II – Regression**<br>- Neural Networks  |
| Week 5 | 8       | **ML II – Regression**<br>- Gaussian Processes<br>- Extrapolation discussion |
| Week 5 | 9       | **ML III – Classification** |
| Week 6 | 10      | **Review and advanced topics I** |
| Week 6 | 11      | **Review and advanced topics II** |
| Week 7 | —       | **Final Group Project Presentations** |
| Week 7 | —       | **Final Group Project Presentations** |

## Homework (HW)
- **HW1** – Python basics and linear systems, with a mass balance example. Additionally, an example of The Ergun equation for root-finding.  
- **HW2** – Nonlinear equation solving and curve fitting, from the Colebrook friction factor to multi-variable systems and kinetic parameter estimation.  
- **HW3** – Ordinary differential equations with chemical kinetics, reaction networks, bioreactor modeling, and a predator-prey model. Stability/phase-plane analysis.  
- **HW4** – Machine-learning models in scikit-learn: decision trees, neural networks, and Gaussian processes using process data.

Each notebook includes collaboration and AI-use declarations and export (.*pdf) instructions.

## Team Project
- **Project guide** – Expectations, deliverables, grading rubric, and recommended workflow.  
- **Alkylation optimization** – Classic nonlinear programming benchmark for refinery operations.  
- **Concrete strength ML modeling** – Predict compressive strength from mix design via regression.  
- **Evaporator optimization** – Optimize operating conditions of a forced-circulation evaporator.  
- **Steam methane reforming (SMR) ML model** – Learn ML (surrogate) modeling of a large-scale SMR–membrane reactor process flowsheet.

## Repository layout
- **Lectures/** – Jupyter notebooks aligned with the weekly roadmap above.  
- **Assignments/** – Homework notebooks with problem statements.  
- **Projects/** – Team project options and datasets.  
- **Datasets/** – CSV/TXT files referenced across lectures, assignments, and projects.  
- **Slides/** and **images/** – Slide decks and figures that support in-class discussions.
