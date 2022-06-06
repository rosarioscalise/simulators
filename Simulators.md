I'll cover these 3 questions:
1. Why care about simulators?
2. Why differentiable simulators?
3. What are system-level considerations that are relevant to robotics that have yet to be fully realized?

 Hopefully you walkaway with a better idea of which simulator you should use.

## Why care about simulators?
1. Rapid prototyping and development of:
	1. robot systems/morphologies
	2. algorithms for controlling robots
	3. (potentially co-designing)
2. Generating large datasets that are required for modern machine learning techniques that have led to breakthroughs in areas like signal processing, machine translation, CV, and NLP.
3. 


## There are different modes for using a simulator.
For certain goals, the fact that many simulators struggle to model real physical characteristics accurately has been ignored for at least half a decade, but likely longer. We need to start focusing on using simulators for the right reasons.

- accurately model the dynamics of the robot
- accurately model the dynamics of an environment (sometimes as a part of the total controllable system)
- identifying parameters that describe the dynamics of the robot
	- masses
	- friction coefficients
	- etc.
- See EMOs talk and table

#### Different simulators make different assumptions.

As we discussed last week, CLM problem solving methods are the most common:
(theses are acceptable when we have this specific assumption.)



#### Which simulator is good for each of these modes?

### Summary Table of simulators


## Why differentiable simultors?




