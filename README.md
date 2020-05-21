# ContacttracingModel
A branching process model for assessing the effectiveness of contact tracing

This is a model that was adapted from a model for smallpox vaccination. I added a few features to it, such as the possibility of asymptomatic infection (implemented as probability of not being diagnosed), and contact reduction (implemented as a factor reducing the mean number of non-household contacts). I did not have time to change variable names, which still refer to vaccination. I will try to provide a more explicit description of the code soon. 

The model consists of 2 Mathematica notebooks. I have uploaded now the notebook that calculates basic and effective reproduction numbers, exponential growth rates, and doubling times. The second notebook, which I will upload soon, is the dynamic part, which allows for simulation of the branching process. 

In the version of 6-5-2020 I added a weighting function to account for the fraction of onward transmission of an infected contact person that is prevented by tracing and isolating the contact person. 
