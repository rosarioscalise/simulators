## Why Differentiable?

- Gradients can be computed natively.
	- policy gradients for control tasks
	- dynamics jacobians for model-based control
	- physical property gradients for model fitting
	- other cool things



![[box.gif|300]] ![[geometry.gif|300]]


* Alternatives:
	* Finite differencing: evaluating the forward simulation multiple times with small perturbations to the relevant parameters to approximate the relevant gradients
	* Gradient-free: inefficient and approximate
	
### Why avoid finite-differencing?
1. the high computational burden of finite differencing when computing the gradient with respect to a large number of model/policy parameters
2. the instability of numerical gradients over long time horizons, especially if contacts change over the course of a rollout (roundoff errors)

### Current Approach
- Existing simulators simply add an analytical description of the LCP problem. Typically utilizing a library like pytorch that enables autograd.

### Examples of use cases
*from Filipe de A. Belbute-Peres ... Tenenbaum/Kolter*

- First, we show that it can infer the mass of an object by observing the dynamics of a scene. 
- Next, we demonstrate that embedding a differentiable physics engine within a deep autoencoder network can lead to high accuracy predictions and improved sample efficiency. 
- Finally, we use the differentiable physics engine together with gradient-based control methods to show that we can learn to perform physics-based tasks with low sample complexity when compared to model-free methods.



## Current Options

Dojo
Nimble
...
eventually Mujoco
IsaacSim


## Sources
[The frontier of simulation-based inference](https://arxiv.org/pdf/1911.01429.pdf)
[End-to-End Differentiable Physics for Learning and Control](https://proceedings.neurips.cc/paper/2018/file/842424a1d0595b76ec4fa03c46e8d755-Paper.pdf)
