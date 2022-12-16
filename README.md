# Optimizing a Hydropower Station for Profitiabilty 

This project aims at creating an optimised operations plan for hydropower stations that take into account many different factors to maximize profitibility. 

## Original Problem

The code in the GitHub file called "original_problem" creates a base line (vanilla) model for a hydroelectric power station aimed at generating the most amount of profit with no optimisation. This means that the same average amount of water is let through the turbine everyday, irespective of weather and electricity price conditions. 

The variables that are being used are:
- p_t = flow of water through the turbine
- q_t = flow of water directed to the spillway
- a_t = amount of water inputted into the resivoir by the watershed and weather 
- V_t = the volume of water in the resevoir.
- θ_t = average daily price of electricity per kWh

# Augmented Problem

The code in the GitHub file called "augmented_problem" expandes on the base model by optimising for profit by taking into account all the parameters, and adding a new one like solar panels for an extra electricity source. This means that the changing weather, electricity price fluctuations, dam ramp up and ramp down constraints, are all taken into account.  

The new variable that was added:
- w_t = amount of water pumped back up into the resivoir 

