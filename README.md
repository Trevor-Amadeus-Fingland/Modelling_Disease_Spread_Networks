# Modelling_Disease_Spread_Networks
Master's project for modelling the spread of disease on a network.

**Link to Master's project paper:** https://www.overleaf.com/read/pdpjvpfjwjkk

**SUMMARY OF PROJECT:**
The file included in this repo ,Containment code, is the code I implemented for my master's project.
We model the spread of disease on a scale-free network under different initial conditions and perform
local stability analysis for the solutions. 

**DESCRIPTION:**
The question we wanted to ask was how disease spreads over networks. Networks in this case are graphs
consisting of nodes and edges. These models are ideal for larger scale systems such as the spread of disease 
over cities or airports. My main contribution to this argument was assuming that we cannot say with certainty 
where a new disease can begin. To account for this, we consider initial distributions where there is a probability
,rather than a certanity, of where the disease will start. In addition, we model the probability of containment.
This was something we defined in our work to be the probability that the disease fails to spread over time
