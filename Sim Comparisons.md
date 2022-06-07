| simulator | year | application | integrator                 | state   | contact   | solver        | language | gradients         |
| --------- | ---- | ----------- | -------------------------- | ------- | --------- | ------------- | -------- | ----------------- |
| MuJoCo    | 2015 | robotics    | implicit Euler/RK4         | minimal | soft      | Newton/PGS/CG | C        | finite-difference |
| Drake     | 2019 | robotics    | implicit Euler/RADAU5      | minimal | soft/hard | LCP/Newton    | C++      | gradient-bundle   |
| Bullet    | 2006 | graphics    | implicit Euler             | minimal | soft/hard | LCP           | C/C++    | sub-gradient      |
| DART      | 2012 | robotics    | implicit Euler/variational | minimal | hard      | LCP           | C++      | sub-gradient      |
| Brax      | 2021 | graphics    | explicit Euler             | maximal | soft      | N/A           | Python   | sub-gradient      |
| RaiSim    | -    | robotics    | implicit Eutler            | minimal | hard      | bisection     | C++      | -                 |
| Dojo      | 2022 | robotics    | variational                | maximal | hard      | NCP           | julia    | smooth gradient   |
| IsaacSim  | 2021 | robotics    | -                          | -       | hard      | NCP           | C++      | -                 |


