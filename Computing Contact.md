
There are two styles of contact. One which reasons about Penetration/Collision/Friction and another which uses a LPM where the rigid bodies are attached via a spring-mass system.

## Hard Contact
*which can be further divided into two classes:*

![[Pasted image 20220607110707.png|600]]
***LCP** (pyramidal approx. of friction cone) vs **NCP** (true friction cone)*

### LCP
*Linear Complementarity Problem*

There are different solvers used to solve this, common ones include (iterative or direct):
- PGS
- ISOR
- Danitz

#### Issues
-  iterative methods can lead to the body rotating -> can lead to asymmetric result depending on starting position

This is often non-differentiable. *Nimble* makes this differentiable for DART.

### NCP

*Dojo* solves this exactly, without approximating the friction cone using a fancy interior-point method.

![[cone.gif]]

![[Pasted image 20220607132129.png|600]]

### Soft Contact (Spring-Mass Model)

Note: is there a damping coeff?

### Issues:
- experiences unphysical interpenetration
- forces at a distance (i.e., while not in contact)
- need to tune the contact model parameters