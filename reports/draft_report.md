
# Sugarscape model in the midst of an epidemic
###### by Ally Bell and Mahima Beltur

## Abstract
Sugarscape is a model that, in a simple way, represents reward-seeking and resource accumulating behaviours in societies. In this project we will explore how the behaviours of our agents are modified with the introduction of an epidemic disease begins to affect the population. The disease will spread to closeby agents and greatly increase the probability of the agent dying, unless they receive significant "aid" by surrounding agents. The amount of aid is measured by the number of neighboring agents. We plan on modelling the contagious disease in a similar manner to the forest fire model. We will explore how different rates of contagion will influence the agents of different ranges of vision when they are programed to move away from disease, but closer to a bigger source of sugar. It will be interesting to note which desire wins out more: life or wealth?

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

## Areas of Concern

* As we go through, we keep finding many interesting features we could experiment with such as: 
  * limiting their sugar harvesting behaviours based on health status (we could also make these progressive)
* We need to be cognizant of how we're bringing two types of models together which answer very different questions: sugarscape is about finding resources where an epidemic disease model is about transmission
* We need to decide on concrete metrics by which to measure the agent behaviours. As one example, we could have a parameter that was continuous and resprestned some strategry - disease, inclination to wander etc. 
* It is possible that the model could spontaniously show two different strategies- which would be an interesting find!
* There is not an obvious anwer with the model we are doing. In sugarscape, as the system evoled we got more vision and less metabolism. This answer feels somewhat obvious, whereas that's not the case of our model.

## Next Steps
### Mahima
I will spend some time studying the implementation of epidemic models and planning out ways that we might be able to apply these concepts to the sugarscape model. I will also brainstorm some metrics we can focus on measuring after we have a working model.

### Ally
I'm going to work on writing a first implementation of this model and get it to Mahima 11/21.


1) A meaningful title (not "Draft Report"), and the full names of the authors.

2) An abstract that identifies the topics you are investigating and the tools you are using.

3) An annotated bibliography of papers that relate to your topic and/or tools.  Explain what the papers are about, what experiments they report, and what their primary conclusions are.

4) A description of the experiment from these papers that you are replicating and the extensions or variations of those experiments you are working on.

5) Results from the replication and possibly preliminary results from the extension. Or if you don't have results, sketch what the results from these experiments might look like, possibly using a cartoon of a graphical result.

6) Interpret the results; for example, "If the power spectrum on a log-log scale is approximately linear, we will estimate its slope.  If that slope is near 1, we will conclude that the time series generated by the model resembles pink noise."

7) Identify causes for concern.  Review the criteria for what makes a good project and identify any areas where your project might be problematic.

8) Outline next steps.  For each team member, what do you plan to work on immediately?  For the team, what do you think you can get done in the next week?  Consider using GitHub Projects to make a kanban board to track tasks.

