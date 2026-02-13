# nba-roster-optimization-model
Develop a constrained optimization framework to construct an optimal NBA roster under salary cap and structural constraints using advanced performance metrics.

# Tools & Techniques
1. Microsoft Excel Solver
2. Linear Programming
3. Integer Programming (Binary Decision Variables)
4. Monte Carlo Simulation
5. Constraint Modeling

# Model Design
Objective Function: 
Maximize team performance score defined as:
0.5 × Win Shares (WS) + 0.5 × Box Plus-Minus (BPM)

Decision Variables:
Binary variable (0 or 1) indicating whether a player is selected.

Constraints Included:
1. Total salary ≤ budget cap
2. Fixed roster size
3. Positional requirements
4. Forced inclusion constraints (e.g., Luka and Kyrie selected together)
5. Optional stacking / pairing constraints

# Optimization Approach
1. Implemented Integer Programming via binary selection variables
2. Used Solver to maximize objective function under constraints
3. Conducted sensitivity testing
4. Ran Monte Carlo simulations to test roster performance variability

# Key Insights
1. Combining WS and BPM created balanced valuation between impact and efficiency.
2. Constraint stacking significantly affects feasible solution space.
3. Budget allocation efficiency improves when marginal impact per dollar is considered.

# Project Outcome
Built a structured decision-support tool for roster construction under financial and structural constraints, demonstrating applied optimization techniques in sports analytics.
