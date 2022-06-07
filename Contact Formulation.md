
There are two styles of contact. One which reasons about Penetration/Collision/Friction and another which uses a LPM where the rigid bodies are attached via a spring-mass system.

## Hard Contact
*which can be further divided into two classes:*

![[Pasted image 20220607110707.png|600]]
***LCP** (pyramidal approx. of friction cone) vs **NCP** (true friction cone)*

### LCP
*Linear Complementarity Problem*

There are different solvers used to solve this, common ones include:
- PGS
- ISOR
- Danitz

This is often non-differentiable. Nimble makes this differentiable for DART.

### NCP


![[cone.gif]]


### Spring-Mass Model (soft contact)

