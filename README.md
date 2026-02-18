## Healthcare-Operations-Optimization
Prescriptive analytics suite using Linear Programming (LPP) and Transportation modeling to minimize healthcare supply chain costs.
## Project Overview
This project develops a two-stage mathematical optimization framework to minimize operational and logistics costs within a healthcare provider network. By integrating Linear Programming (LPP) and Transportation Modeling, the system prescribes the most cost-effective allocation of medical resources and optimizes the distribution of supplies across a multi-nodal supply chain.
## Repository Structure
•	Healthcare_Logistics_Optimization.xlsx: The core analytical engine containing the LPP Solver Model, Transportation Matrix, and automated Sensitivity Reports.
•	Healthcare_Optimization_Report.docs: A comprehensive technical report detailing the mathematical formulations, constraints, and management insights.
## Analytical Methodology
1. Resource Allocation (Linear Programming)
Using the Simplex LP engine, I formulated a model to minimize total service costs while satisfying complex operational boundaries:
•	Objective Function: Minimize $Z = \sum (Cost_i \times Resource_i)$.
•	Constraints: Factored in facility capacity, strict labor hour availability, and budgetary ceilings.
•	Outcome: Identified the optimal resource mix that meets 100% of service demand at the lowest possible cost.
2. Logistics Optimization (Transportation Model)
A second-stage model was designed to optimize the movement of medical supplies from 3 supply hubs to 4 demand centers:
•	Balancing: Synchronized total supply availability with fluctuating regional demand.
•	Optimization: Applied Northwest Corner and Stepping-Stone logic via Excel Solver to find the global minimum for freight and handling costs.
## Management Insights & Sensitivity Analysis
The project goes beyond static answers by utilizing Sensitivity Reports to provide strategic "What-If" capabilities:
•	Shadow Price Analysis: Quantified the marginal value of increasing constraints (e.g., how much one additional hour of labor reduces total system cost).
•	Stability Assessment: Identified the "Allowable Increase/Decrease" for cost coefficients, ensuring the logistics plan remains robust against fuel price volatility.
## Implementation & User Guide
To use this optimization suite:
1.	Open Healthcare_Optimization.xlsx and ensure the Excel Solver Add-in is enabled.
2.	Input your specific cost coefficients in the 'LPP Solver Model' tab.
3.	Run Solver: The model will automatically recalculate the optimal resource mix and update the Transportation Matrix.
4.	Review Dashboard: Visual summaries provide an instant view of total costs vs. budget utilization.

