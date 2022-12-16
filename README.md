# Optimizing a Hydropower Station for Profitiabilty 

This project aims at creating an optimised operations plan for hydropower stations that take into account many different factors to maximize profitibility. 

## Original Problem

The code in the GitHub file called "original_problem" creates a base line model for a hydroelectric power station aimed at generating the most amount of profit with no optimisation. 

The variables that are being used are:
- p_t = flow of water through the turbine
- q_t = flow of water directed to the spillway
- a_t = amount of water inputted into the resivoir by the watershed and weather 
- V_t = the volume of water in the resevoir.

# Augmented Problem

The code in the GitHub file called "augmented_problem" expandes on the base model by optimising for profit by taking into account all the contraints of the hydrodam, and the inputs of the watershed and electricity profitability. This model also added different parameters, like solar power, pumping water back up, and creating an insentive in the cost function to favor more water in the resevoir. 
