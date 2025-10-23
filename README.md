# UniVE-DABS
Contains project covered during my Master's Degree.

**Branches**  
**MDMM**  
**Background**: This document addresses an optimization problem for scheduling employees within a company to maximize net productivity. Given the total number of employees and current work distribution (on-site vs. remote), the company aims to optimize their operational setup in light of various constraints.  
**Purpose**: The goal is to determine the optimal number of employees working on-site and remotely, and to decide on the number of offices required to accommodate the on-site workforce, while maximizing the company's net productivity.  
**Methodology**: The problem is modeled using linear programming with the ‘pulp’ library in Python. Key variables include the productivity of on-site and remote employees, office rent, and carbon tax costs. Constraints ensure that employees with specific needs work remotely, a minimum number of employees are on-site, and office capacities are not exceeded.  
**Results**: The model calculates the number of employees working on-site and remotely, the number of offices needed, and evaluates the total productivity, costs, and profit based on the optimal solution.  
**Conclusion**: The solution provides a balance between maximizing productivity and managing operational costs. The company can adjust its work distribution and office space to achieve the best financial outcome while adhering to all constraints.
