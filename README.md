# MATLAB Fall 2014 – Research Plan

> * Group Name: Rocco Ghielmini 
> * Group participants names: Rocco Ghielmini
> * Project Title: Diffusion of Vaccination Refusal and it's Consecuancens

## General Introduction

The refusal of vaccination has emerged as a trend in recent years due to the fear for it to be cause of auto immune diseases. Public health officers are concerned with this attitude increasing the risk of the return of diseases which were considered almost estinguished. An example is the recent outbreak of measles in Switzerland. Currently, campaigns are promoting vaccination to contrast this new trend. I model the risk of a large spread of a disease given the percentage of non vaccinated people and visualize it by means of a simualtion. The former should define a safe threshold on the percentage of vaccinated people for the disease not to take over. Furthermore, we simulate to which extent a campaign should intervene to restore such threshold. 

## The Model

Models: Agent based Epidemic modeling and Evolutionary Game theory 

Population: homogenously mixed populations or networks

Independent variables:
- percentage of non vaccinated people (look at current distribution)
- spread factor of the disease (dependent given the disease)
- persuasion factor of campaign ( hyperparamether )
- persuasion factor among individuals ( follows a model from the literature )
- incidence of severe complications ( dependent on disease)

Dependent variable:
- damage in terms of number of severe complications per unit of time

I assume the society under study is subject to risk of infection only because of the lack of vaccination.
I also assume the vaccination is free of charge.
Such a model is therefore applicable to welfare states where the cost of a vaccination can be assumed inexistent.



## Fundamental Questions

What can be considered a safe threshold on the ratio of non vaccinated people, given the disease and the society under study?
How much effort shall be invested in vaccination campaigns given the extent of the refusal trend?



## Expected Results


I expect a minor percentage of people refusing vaccination to be of no harm for the entire society.
On the other hand, I suspect that a sufficiently high percentage can lead to disastrous scenarios (the incidence of severe complications to be out of control) 


## References 

Bauch, Chris T., and Samit Bhattacharyya. "Evolutionary game theory and social learning can determine how vaccine scares unfold." PLoS computational biology 8.4 (2012): e1002452.

Bauch, Chris T., and David JD Earn. "Vaccination and the theory of games." Proceedings of the National Academy of Sciences of the United States of America 101.36 (2004): 13391-13394.

Fu, Feng, et al. "Imitation dynamics of vaccination behaviour on social networks." Proceedings of the Royal Society B: Biological Sciences 278.1702 (2011): 42-49.


## Research Methods

Agent based modeling (evolutionary game dynamics) and differential equations (SIR)

