# Optimization_model
COMPANY:CODECH IT SOLUTIONS

INTERN ID:CT04DZ1769

DOMAIN:DATA SCIENCE

DURATION:4 WEEKS

MENTOR:NEELA SANTOSH

PROJECT DESCRIPTION:SOLVE A BUSINESS PROBLEM USING OPTIMIZATION TECHNIQUES (E.G., LINEAR PROGRAMMING) AND PYTHON LIBRARIES LIKE PULP

Project Overview
This project demonstrates how to solve a real-world business problem using Linear Programming (LP) techniques with the PuLP library in Python. Optimization models are widely used in industries such as manufacturing, logistics, transportation, and finance to maximize profits, minimize costs, or achieve a balance between resources and constraints.

The notebook in this repository walks through the entire process — from problem formulation to implementation, solving, and generating insights. This work was completed as part of my internship task for CODTECH, where the objective was to demonstrate optimization modeling in a clear, well-documented way.

Objective
The main goal of this project is to develop a profit maximization model for a small manufacturing business. The business produces two products, and each product requires a certain amount of limited resources (such as labor hours and raw materials). By using optimization techniques, we determine the optimal production quantities of each product to maximize total profit, while staying within resource limits.

Tools and Technologies
Python — Primary programming language

PuLP — Python library for linear optimization

Jupyter Notebook — For coding, documentation, and visualization

GitHub — Version control and project hosting

Project Structure
bash
Copy
Edit
├── Business_Optimization_PuLP.ipynb   # Main Jupyter Notebook
├── README.md                          # Project documentation
Problem Formulation
We define:

Decision Variables → Number of units to produce for each product.

Objective Function → Maximize total profit = (Profit per unit of Product A × Units of A) + (Profit per unit of Product B × Units of B).

Constraints → Limitations on labor hours and raw material availability.

Example:

Product A requires 2 hours of labor and 3 units of raw material.

Product B requires 4 hours of labor and 2 units of raw material.

Available resources: 100 labor hours and 90 units of raw material.

Profit per unit: $40 for Product A, $30 for Product B.

Implementation Steps
Import PuLP and create a linear programming problem.

Define decision variables for products.

Add the objective function (maximize profit).

Add constraints for labor and materials.

Solve the problem using PuLP’s solver.

Display results including the optimal production quantities and maximum profit.

Results & Insights
The optimization model provides:

Exact number of units for each product to produce.

Maximum achievable profit within the given constraints.

Resource usage for the optimal solution.

This approach allows business managers to make data-driven decisions instead of relying solely on intuition.

Learnings
Through this project, I learned:

How to structure a business problem into an optimization model.

The importance of constraints in real-world problems.

How to use PuLP effectively for solving linear programming problems.

Future Enhancements
Add more products and resource types.

Include integer constraints for discrete production planning.

Implement sensitivity analysis to see how changes in resource availability affect the solution.

