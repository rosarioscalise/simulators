**TL;DR:** Maximal coordinates are easier for the developers/maintainers but only lead to slower evaluation. Minimal coordinates require more jumping through hoops but lead to faster evaluation and therefore are preferred from the user standpoint.

> RMS: Now I'm not sure about this...

- In maximal coordinates, we always need to solve all constraints explicitly. This is computationally expensive.

### Solving Equations of Motion for Articulated Rigid Bodies
*with constraints*

Maximal Coordinates -> Lagrange Multiplier Method -> $O(n^3)$
- because the mass matrix must be inverted

Minimal Coordinates -> Featherstone Algorithm -> $O(n)$

