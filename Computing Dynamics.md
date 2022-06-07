## Forward Dynamics
Given $\theta$, $\dot{\theta}$, $\tau$ -> Find $\ddot{\theta}$

Can be solved using:
1. Lagrangian Formulation
2. Newton-Euler (explicit or implicit)
3. (rare) Hamiltons Principle of Least Action

Implicit methods are iterative.


### Issues with semi-implicit Euler:
- high rates can prove a challenge for control tasks, such as model-predictive control applications where real-time re-planning is required
- or reinforcement- learning settings where vanishing or exploding gradients are exacerbated over long horizons with many time steps



## Inverse Dynamics
Given $\theta$, $\dot{\theta}$, $\ddot{\theta}$ -> Find $\tau$




### Continuous vs. Discrete Mechanics


Variational Integrator Approach automatically conserves momentum and energy.
![[Pasted image 20220607132018.png|600]]