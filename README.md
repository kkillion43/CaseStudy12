# Case Study 12 - Simulation Study of a Branching Process

___DataScience@SMU___<br>
___Data Scientist: Kyle Killion and Joseph Stoffa___

# Abstract:
This project aims to explore The Monte Carlo method, simulation, and random number generation with built-in probability distribution generators. With these tools, we can then begin to generate inference off the open-ended theories that might not be able to go "coast-to-coast" in solving.

ref: Gaston Sanchez, https://rpubs.com/gaston/dendrograms

# Introduction

The probability distributions that are utilized in this study are the Poisson distribution, Chi-Squared Distribution, and Exponential Distribution. The Exponential Distribution, a very popular continuous distribution, is often utilized to model the time elapsed between events. One of the key points about this distribution is that it is memoryless. This is meaning that having different starting points cannot be used to determine equal life expectancies. The Poisson distribution depicts the probabilities of an event happening on any given time interval. These events happening within the given time have to be independent from each other in order to fall within the Poisson assumption. The Chi Square distribution is leveraged in way of overlaying a theoretically distribution over an observed distribution. This can be comparable to seeing how big your kids are to the theoretically distribution of kids at that age. So, as we go through our Monte Carlo Simulations, we can then begin to explore how these computer threads behave. Code antics and preferred techniques are trudged through along the way such as recursion and vectorization.  In section 4 we answer question 6 from the text and provide a alternative visualizations followed by a brief discussion of the their implementation.



