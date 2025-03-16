# Enzymology Homework: Michaelis-Menten Kinetics and Competitive Inhibition Analysis

## Overview
This project is a Python-based analysis of enzyme kinetics using the Michaelis-Menten model and competitive inhibition. The goal is to estimate key kinetic parameters such as \( V_{max} \) (maximum reaction rate), \( K_m \) (Michaelis constant), and \( K_i \) (inhibition constant) from experimental data. The project also includes visualization of the results using a Lineweaver-Burk plot, which helps distinguish between inhibited and uninhibited enzyme reactions.

## Key Features
- **Data Loading and Preprocessing**: The project loads enzyme kinetics data from a text file (`data63.txt`) and separates it into two datasets: one without an inhibitor and one with an inhibitor.
- **Michaelis-Menten Model**: The Michaelis-Menten equation is used to model the enzyme kinetics in the absence of an inhibitor. The parameters \( V_{max} \) and \( K_m \) are estimated using non-linear curve fitting.
- **Competitive Inhibition Model**: The project extends the Michaelis-Menten model to include competitive inhibition, where the inhibitor competes with the substrate for the enzyme's active site. The parameters \( V_{max} \), \( K_m \), and \( K_i \) are estimated for the inhibited reaction.
- **Lineweaver-Burk Plot**: A double reciprocal plot (Lineweaver-Burk plot) is generated to visualize the data and distinguish between inhibited and uninhibited reactions. Linear regression lines are fitted to the data for both conditions.
- **Parameter Estimation**: The project estimates key kinetic parameters for both uninhibited and inhibited reactions, providing insights into the enzyme's behavior and the effect of the inhibitor.
