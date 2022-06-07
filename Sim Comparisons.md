| simulator   | year | application | integrator                 | state   | contact   | solver        | language | gradients         |
| ----------- | ---- | ----------- | -------------------------- | ------- | --------- | ------------- | -------- | ----------------- |
| MuJoCo(DM)  | 2015 | robotics    | implicit Euler/RK4         | minimal | soft      | Newton/PGS/CG | C        | finite-difference |
| Drake       | 2019 | robotics    | implicit Euler/RADAU5      | minimal | soft/hard | LCP/Newton    | C++      | gradient-bundle   |
| ODE         | 2001 | graphics    | implicit Euler             | maximal | soft/hard | LCP           | C++      |                   |
| Bullet      | 2006 | graphics    | implicit Euler             | minimal | soft/hard | MLCP          | C/C++    | sub-gradient      |
| DART        | 2012 | robotics    | implicit Euler/variational | minimal | hard      | LCP           | C++      | sub-gradient      |
| ^ nimble    | 2021 | "           | "                          | "       | "         |               |          |                   |
| Brax        | 2021 | graphics    | explicit Euler             | maximal | soft      | N/A           | Python   | sub-gradient      |
| RaiSim      | -    | robotics    | implicit Eutler            | minimal | hard      | bisection     | C++      | -                 |
| Dojo        | 2022 | robotics    | variational                | maximal | hard      | NCP           | julia    | smooth gradient   |
| IsaacSim    | 2021 | robotics    | -                          | -       | -         | -             | C++      | -                 |
| Meta Option | -    | -           | -                          | -       | -         | -             | -        | -                 |

### Notes:

## Less Feature Complete
[ADD: Analytically Differentiable Dynamics for Multi-Body Systems with  Frictional Contact](https://arxiv.org/pdf/2007.00987.pdf)
[A Differentiable Physics Engine for Deep Learning in Robotics](https://arxiv.org/pdf/1611.01652.pdf)


## Sources
[Simulation Tools for Model-Based Robotics: Comparison of Bullet, Havok, MuJoCo, ODE and PhysX - Ezra, Tassa, Todorov](https://homes.cs.washington.edu/~todorov/papers/ErezICRA15.pdf)
[SimBenchmark | Physics engine benchmark for robotics applications: RaiSim vs. Bullet vs. ODE vs. MuJoCo vs. DartSim](https://leggedrobotics.github.io/SimBenchmark/#models)
[Dojo: A Differentiable Simulator for Robotics - Taylor et. al](https://sites.google.com/view/dojo-sim)
