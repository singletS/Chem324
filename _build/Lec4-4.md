---
redirect_from:
  - "/lec4-4"
title: '4.4 Angular momentum in QM'
prev_page:
  url: /Lec4-3
  title: '4.3 Rotators.'
next_page:
  url: /HarmOsc_visualize
  title: '4.5 Visualziing Harmonic Oscillator Solutions'
comment: "***PROGRAMMATICALLY GENERATED, DO NOT EDIT. SEE ORIGINAL FILES IN /content***"
---
## Outline for Lecture 4.4:  

- Angular momentum plays a central role in both classical and quantum mechanics. In classical mechanics, all isolated systems conserve angular momentum (as well as energy and linear momentum); this fact reduces considerably the amount of work required in calculating trajectories of planets, rotation of rigid bodies, and many more. 
- Similarly, in quantum mechanics, angular momentum plays a central role in understanding the structure of atoms, as well as other quantum problems that involve rotational symmetry. Like other observable quantities, angular momentum is described in QM by an operator. This is in fact a vector operator, similar to momentum operator. However, contrary to the linear momentum operator, the three components of the angular momentum operator do not commute!
- In QM, there are several angular momentum operators: the total angular momentum (usually denoted by $J$), the orbital angular momentum (usually denoted by $L$ ) and the intrinsic, or spin angular momentum (denoted by $S$). This spin has no classical analogue! Confusingly, the term “angular momentum” can refer to either the total angular momentum, or to the orbital angular momentum.



## Angular momentum: classical

Consider a particle of mass m, momentum $\vec{p}$ and position vector $\vec{r}$ with respect to a fixed origin, $r = 0$. In classical mechanics, the particle’s orbital angular momentum is given by a vector$\vec{L}$ , defined by
$$
\vec{L} = \vec{r}  \times \vec{p}
$$
The vector product of two vectors results in a third vector which points in the direction perpendicular to planed of the two vectors. The thumb rule is adopted for indicating directon of 


$$
\vec{L}=L_x \vec{e_x}+L_y \vec{e_y} +L_z \vec{e_z}
$$


 The components of the vector are given as:
$$
L_x = yp_z-zp_y \\
L_y = zp_x-xp_z \\
L_z = xp_y-yp_x
$$
## Angular momentum: quantum



The classical definition of the orbital angular momentum,  can be carried directly to QM by reinterpreting $r$ and $p$ as the operators associated with the position and the linear momentum:
$$
\hat{L} = \hat{r}  \times \hat{p} = r\times (-i\hbar\nabla) \\
$$

The quantum Mechanical components are then:

$$
\hat{L_x} = -i\hbar \Big( y\frac{\partial }{\partial z}-z\frac{\partial}{\partial y} \Big) \\
\hat{L_y} = -i\hbar \Big( z\frac{\partial }{\partial x}-x\frac{\partial}{\partial z} \Big) \\
\hat{L_z} = -i\hbar \Big( x\frac{\partial }{\partial y}-y\frac{\partial}{\partial x} \Big) 
$$
