Anthony Wang
Mr. Irons
11/19/2021
# AP Physics C – Moment of Inertia Lab
## Purpose 
With translational motion, the equation, $F=ma$, is sufficient to describe the motion of an object if we have a force, $F$, the mass of an object, $m$, and the acceleration of an object, $a$. When considering rotational motion, we find the rotational analogue of $F=ma$, $\tau=I\alpha$, where $\tau$, $I$, and $\alpha$ are the torque, the moment of inertia, and the angular acceleration of an object, respectively. The purpose of this lab is to determine the moment of inertia of a disk of mass $m$ and radius of $R$ experimentally, by measuring and controlling $\alpha$ and $\tau$ using different weights.


## List of Materials
- Pulley setup + disk
- Weights
- String
- Rotation sensor
- Computer with Logger Pro installed


## Procedure
1. Attach string to the pulley at the top
2. Attach weight to the string
3. Let the weight fall, and log the velocity as it falls
4. Find the average acceleration from the velocity using Logger Pro
5. Repeat steps 2-4 with different weights

## Data Collection
| Item | Measurement |
| ---- | ----------- |
| Mass of the disk | 0.1069 kg |
| Radius of the disk | 0.045 m |
| Radius of the pulley attached to the disk | 0.024 m |

| Weight (kg) | Measured Angular Acceleration (rad/s^2) |
| -------- | ----- |
| 0.05 | 84.6 |
| 0.10 | 135.2 |
| 0.15 | 178.2 |
| 0.20 | 206.2 |
| 0.25 | 229.1 |

## Data analysis
Given the two equations,
$T=mg-ma$
$\tau=RT$

We can solve for $\tau$ in terms of our measured angular acceleration, $\alpha$, the radius of the disk, $R$, and the mass of the weight, $m$.
$\tau=Rm(g-a)$
$\tau=Rm(g-\alpha R)$

We analyze the data to get:

| Weight (kg) | Torque (Nm) |
| ----------- | ----------- |
| 0.05 | 0.00933552 |
| 0.10 | 0.01575648 |
| 0.15 | 0.01991952 |
| 0.20 | 0.02333376 |
| 0.25 | 0.0258696 |

![picture 1](https://i.imgur.com/q4LvbxS.png)  
Because $\tau=I\alpha$, when we plot $\tau$ vs $\alpha$, we can use the best fit line to calculate I, and we get a result of $I=0.0001131 Nm/rad/s^2$

We derive the theoretical value of the moment of inertia of the disk: $I=\frac{1}{2}mR^2=0.5*0.1068*0.045^2 = 0.000108135 Nm/rad/s^2$

Using the error formula, we get a percent error of $4.59\%$

## Conclusion
In this lab, we fulfilled our purpose of experimentally determining the moment of inertia $I$, for a disk around its axis of symmetry. Our measured moment of inertia was $I=0.0001131 Nm/rad/s^2$, and our theoretical value was $I=0.000108135 Nm/rad/s^2$. We used the error formula to calculate the percent error, which was $4.59\%$.

A source of systematic error is the mass in the pulleys, and the error in our result could have been reduced by compensating for their masses in the theoretical calculation. This would likely decrease the error because the theoretical moment of inertia would increase if we accounted for the mass of the pulley.

Another source of systematic error is the friction between the pulleys and the shafts they rotates on, which could be reduced with increased lubrication.

