# ContacttracingModel
A branching process model for assessing the effectiveness of contact tracing

This is a model that was adapted from a model for smallpox vaccination. I added a few features to it, such as the possibility of asymptomatic infection (implemented as probability of not being diagnosed), and contact reduction (implemented as a factor reducing the mean number of non-household contacts). I did not have time to change variable names, which still refer to vaccination. I will try to provide a more explicit description of the code soon. 

The model consists of 2 Mathematica notebooks. I have uploaded now the notebook that calculates basic and effective reproduction numbers, exponential growth rates, and doubling times. The second notebook, which I will upload soon, is the dynamic part, which allows for simulation of the branching process. 

In the version of 6-5-2020 I added a weighting function to account for the fraction of onward transmission of an infected contact person that is prevented by tracing and isolating the contact person. 

The notebooks rzero_corona_final.nb and rzero_corona_hypercube.nb were used to create the results of the paper "Impact of delays on effectiveness of contact tracing strategies for COVID-19: a modelling study", which will shortly be published in the Lancet Public Health.

On October 28, I added a version of the notebook called Containment_of_COVID-19. This was used to generate results and figures for a paper submitted to Frontiers in Physics. 
