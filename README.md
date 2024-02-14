## Common Pool Resource Games with Network-Based Information Sets

Welcome to the GitHub page for the Common Pool Resource Games with Network-Based Information Sets paper. This page contains the code to replicate the plots in the paper. The graphical user interface that allows users to interact with and explore the results of the agent-based model can be found at https://github.com/bobbyleg/ABM_CPR_Model_Interface/tree/main.

# Abstract

To come to a complete comprehension of common pool resource dynamics, we must first understand the information flows that drive users' incentives. This paper advances an agent-based model with boundedly rational common pool resource agents and information flows based on Barabasi-Albert networks. In the model, heterogeneity in the number of connections creates bistable resource equilibria, leading to an abundant and a scarce outcome. This result is driven by highly-connected users' influence on others' perceived network states. Allocating greater environmental weight to highly-connected individuals aligns their environmental impact and visibility, diminishing the difference between the abundant and scarce resource outcomes. These outcomes unite at the full-information equilibrium when highly-connected users are distributed sufficient environmental weight. Policymakers can leverage these findings regarding information asymmetries and the substantial influence of hub users to develop more informed approaches to CPR management in contexts such as food security and climate regulation. 

# Running the code

The file that produces all the main plots is ground_up.ipynb. The sensitivity analysis is performed through the sensitivity_analysis_paper.ipynb file. 

# Code requirements

-	Numpy (1.24.3)
-	Matplotlib (3.7.2)
-	Pandas (2.0.3)
-	Networkx (3.1)
-	tqdm (4.65)
-	SALib (1.4.7), only for sensitivity analysis
-	diptest (0.7.0), only for sensitivity analysis

# License

This GUI is distributed under the Creative Commons Attribution 4.0 International license.
The DOI of the project is https://doi.org/10.5281/zenodo.10566363.

Feel free to explore the model, experiment with parameter settings, and gain insights into the dynamics of common pool resources!
