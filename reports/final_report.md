
# Sugarscape model in the midst of an epidemic
###### by Ally Bell and Mahima Beltur

## Abstract
The Sugarscape model is a simplified representation of resource seeking behaviours in societies. In this project we explore how the behaviours of our agents are modified with the introduction of an epidemic disease to the population. The disease will spread to close by agents and greatly increase the probability of the agent dying, unless they receive significant "aid" by surrounding agents. The amount of aid is measured by the number of neighboring agents. We plan on modelling the contagious disease in a similar manner to the forest fire model. We will explore how different rates of contagion will influence the agents of different ranges of vision when they are programed to move away from disease, but closer to a bigger source of sugar. It will be interesting to note which desire wins out more: life or wealth?

## Background

Sugarscape is an agent based model proposed in 1996 by Joshua Epstein and Robert Axtell where agents move around a 2-D grid harvesting and storing sugar. Across this grid, sugar is produced in different amounts, which agents need to survive.

Each agent starts the simulation with some amount of sugar, and some amount they need to consume for sustenance per step. They can see the amount of sugar in a radius of neighboring cells and and move towards it accordingly, although some agents can move and see further than others. These three factors give some agents advantages, leading to unequal wealth (sugar) distribution. 

For each time step, agents move in a random order. They look at the cells within the radius of vision they have, choose the unoccupied cell with the most sugar (in a tie, they pick the closest cell or choose randomly), move to the selected cell, and harvest sugar. At the end of this movement, they consume the amount of sugar they need. If they do not have enough sugar stored to fulfill this, they "die" and are removed from the grid.

![original model](./images/original_sugarscape.PNG )

In this replication of the original model, we can see the agents, denoted by red dots, move around the grid over three time steps: zero, two, and one-hundred, going from left to right. The amount of sugar in each cell is shown based on its color, the darker orange the cell, the more sugar present. We can see that over time, agents cluster around areas with the highest sugar concentration.



## Methodology



## Results

We ran this model with different sets of priorities between finding sugar and avoiding sick neighbors. Shown in the following figures, we can see the behavior of agents over three time steps with different ratios of the behavior they prioritized.

In our first simulation, agents only look at finding sugar, as in the original Sugarscape model. We see a very similar behavior, where agents cluster around areas of high sugar concentration.

![original model](./images/fw10_visual.PNG )

![original model](./images/10_deaths.PNG )

In the second simulation, agents only care about avoiding infected neighbors. In this 

![original model](./images/fw01_visual.PNG )

![original model](./images/01_deaths.PNG )

Next, agents weight these two needs evenly.

![original model](./images/fw11_visual.PNG )

![original model](./images/11_deaths.PNG )

In the fourth simulation, food is given a weight of 25% and avoiding infection 75%.

![original model](./images/fw13_visual.PNG )

![original model](./images/13_deaths.PNG )

Our final scenario weights finding sugar at 75% and avoiding infection at 25%.

![original model](./images/fw31_visual.PNG )

![original model](./images/31_deaths.PNG )

Comparing the results for each,

![original model](./images/wealth_distribution.PNG )

![original model](./images/Sick_agents.PNG )

![original model](./images/Agents_alive.PNG )

The number of agents sick seems to spike at the beginning in all scenarios, and then quickly drop and level out as the time steps progress. We think this is because agents start the simulation randomly spread out across the grid, and quickly move towards an equilibrium away form each other, or at least in clusters across the space, leading to smaller outbreaks. 

One interesting behavior seen here is in the agents who were only looking for food. These agents faced much higher rates of infection, but still followed a surprisingly similar infection curve to  the agents who looked to avoid sick neighbors. Despite higher levels of infection, these agents maintained a much larger population





## Bibliograpy

Downey, Allen. “Chapter 9 Agent Based Models.” *Think Complexity: Complexity Science and Computational Modeling*, O'Reilly, 2018. 

Frias-Martinez, Enrique, et al. “An Agent-Based Model of Epidemic Spread Using Human 	Mobility and Social Network Information.” *2011 IEEE Third International Conference on Privacy, Security, Risk and Trust and 2011 IEEE Third International Conference on Social Computing*, 2011, https://doi.org/10.1109/passat/socialcom.2011.142. 

Pan, Rong. “Rebellion on Sugarscape: Case Studies for Greed and Grievance Theory of Civil Conflicts Using Agent-Based Models.” *Social Computing, Behavioral-Cultural Modeling and Prediction*, 1 Aug. 2011, pp. 333–340., https://doi.org/10.1007/978-3-642-19656-0_46. 



