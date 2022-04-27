# network_biosignatures
Network analysis on biosignature study methods

This project examines the connectivity between different kinds of biosignature measurements by extracting/interpreting information from the scientific literature. The result network analysis will support a decision tree, which is a graph that guides the decision making process for future robotic biosignature studies using AI.

Planning future scientific missions that search for life in space (planets and moons in the solar system and beyond) requires increasing amount of automous decision making using AI. In this case the AI being created is an extension of human intelligence and a powerful tool.

How do we teach robots to make decisions on 1) what measurements to take, 2) what observations to make, and 3) what to do the next in order to get closer to the goal given existing observations, when these machines must be away and make decisions on their own? What data should we use to guide them to make such decisions?

I propose that the scientific literature is probably the best place for such raw data. It is a body of knowledge that we humans utilize ourselves to organize and certify information through the peer-review process. This project have following goals:

1) Search the scientific litrature for high quality biosignature studies. A scoring system should be developed to determine what is considered "high quality".

2) Extract from such studies the primary scientific methods used to reach the conclusions. Having a weighting system to rank the methods -- which one is more important and how independent they are from each other to reach the conclusion.

3) Conduct a network analysis on the dataset collected to 1) understand the connectivity between different node of measurements, rank their relative importance, and 2) produce a decision tree that would allow accessment for the next set of measurements to do that would maximize the observational outcome for positive biosignature identification.

