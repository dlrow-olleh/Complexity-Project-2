
# Sugarscape model in the midst of an epidemic
###### by Ally Bell and Mahima Beltur

## Abstract
Sugarscape is a model that, in a simple way, represents reward-seeking and resource accumulating behaviours in societies. In this project we will explore how the behaviours of our agents are modified with the introduction of an epidemic disease begins to affect the population. The disease will spread to close by agents and greatly increase the probability of the agent dying, unless they receive significant "aid" by surrounding agents. The amount of aid is measured by the number of neighboring agents. We plan on modelling the contagious disease in a similar manner to the forest fire model. We will explore how different rates of contagion will influence the agents of different ranges of vision when they are programed to move away from disease, but closer to a bigger source of sugar. It will be interesting to note which desire wins out more: life or wealth?

## Background

Sugarscape is an agent based model proposed in 1996 by Joshua Epstein and Robert Axtell that 



## Annotated Bibliograpy

<!-- https://www.taylorfrancis.com/chapters/edit/10.4324/9781351034944-9/contagious-agents-sebastian-vehlken
 -->

#### An Agent-Based Model of Epidemic Spread Using Human Mobility and Social Network Information
https://ieeexplore.ieee.org/abstract/document/6113095

Frias-Martinez, Enrique; Williamson, Graham; Frias-Martinez, Vanessa, IEEE (October 2011).

This paper uses an agent based approach to evaluate the effects that govornment restrictions on the 2009 H1N1 outbreak in Mexico. To characterize agent's behavior, patterns of interactions and individual movement are collected from call records. This allows for accurate modeling of virus spreading, and allows an understanding of the effects of govornment restricti, ons that were put into place. The simulation produced shows that govornment mandates reduced by 10% the peak number of cases at a time, and postponed the peak - flattening the curve.

<!-- #### Rebellion on Sugarscape: Case Studies for Greed and Grievance Theory of Civil Conflicts using Agent-Based Models

https://arxiv.org/ftp/arxiv/papers/1908/1908.06883.pdf

Pan, Rong, Arizona State University (August 1, 2019). -->

## Experiment and Results

The experiment we will replicate involved adding a behaviour to the agents in sugarscape that acts as a- counter incentive to moving towards areas of highest sugar density. This counter-incentive will be an highly transmissible epidemic dease that the agents will be programmed to- or learn to- avoid. We expected our preliminary experimental results to look something like this:

![image](https://user-images.githubusercontent.com/42980963/142095021-285270c0-59ec-4542-87b9-8088455d1379.png)

So far, we have sucessfully implemented the existence of a disease, and its ability to spread between agents based on their proximity to each other. However, this behaviour immediately obvious in visuals of our results as we have not yet been able to have the agents be represented by the correct colours. 

The image on the left represents what we expect to see time 0 of running our model, with one ill agent in different population densities. At the end of the experiment it is evident that the agents that decided to stay in the areas of high sugar densities (also with the highest population density) have more cases amongst them than agents who stayed  or decided to move to areas of lower population density. By comparing the number of agents that gravitate towards certain behaviours such as:

* nomadic agents vs farming agents
* disregarding risk of disease in order to maximize resource possession vs disregarding material collection in order to avoid disease
It would be itneresting if we were able to find clusteres adhering to two opposite as successful survival mechanism.

