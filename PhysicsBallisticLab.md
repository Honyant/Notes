# Ballistics Lab

## Introduction

In this lab, we will fire a projectile into a bob/catcher on a pendulum. Once the projectile hits the bob, an inelastic collision occurs, and the combined mass goes on to rise to a maximum angle. The projectile is fired at a constant velocity, and the angle of the bob is measured over multiple trials. We will measure the average angle and calculate the uncertainty of our measurement. With this information, we can determine the initial velocity of the projectile and the uncertainty in our initial velocity.

## Procedure

1. Measure the mass of the ball with a scale, the mass of the pendulum bob with a scale, and the length of the pendulum with a ruler. Estimate the uncertainties in each of these measurements based on the limited precision of the instrument.
2. Fire the projectile at a constant velocity with the contraption, and measure the maximum angle the bob reaches and stops at with a digital protractor. (Do this 10 times.)
3. Derive and calculate the velocity of the projectile prior to the collision based on the mass of the ball, the mass of the bob, the length of the pendulum, and the average angle of the bob.
4. Calculate the uncertainty in the velocity of the projectile by propagating the error from the other variables using the error propagation formula.

## Data Collection
| Item | Measurement | Uncertainty |
| ---- | ----------- | ----------- |
| Mass of the ball ($m$) | 69.45 g | 0.05 g |
| Mass of the bob ($M$) | 231.59 g | 0.05 g |
| Length of the pendulum ($l$) | 30.7 cm | 0.1 cm |

| Trial # | Angle (deg) |
| -------- | ----- |
| 1 | $47.0 \degree$ |
| 2 | $46.7 \degree$ |
| 3 | $46.5 \degree$ |
| 4 | $46.0 \degree$ |
| 5 | $47.3 \degree$ |
| 6 | $47.1 \degree$ |
| 7 | $47.1 \degree$ |
| 8 | $46.5 \degree$ |
| 9 | $47.4 \degree$ |
| 10| $45.6 \degree$ |

## Data Analysis

We can calculate the average angle of the bob by averaging the angles of each trial, and the standard deviation of the angles with the formula:
$$\sigma_\theta = \sqrt{\frac{1}{N-1} \sum_{i=1}^{N} (\theta_i - \bar{\theta})^2}$$

$\bar \theta = 46.72\degree$
$\sigma_\theta=0.6\degree$

We can calculate the height h that the pendulum bob reaches by using the formula:
$$h=l-lcos(\theta)=l(1-\cos(\theta))$$
This is because the pendulum is a perfect circle, and the height difference from the bottom is equal to the length of the pendulum times the cosine of the angle.

From the conservation of energy:
$$\frac{1}{2}(M+m)v_f^2=(M+m)gh$$
$$v_f=\sqrt{2gl(1-\cos(\theta))}$$

From the conservation of momentum:
$$\frac{1}{2}mv_i=\frac{1}{2}(M+m)v_f$$

We finally get the initial velocity of the projectile:
$$v_i=\frac{(m+M)}{m} \sqrt{2 g l (1-\cos{\theta})}$$

With the above equation, we can calculate the initial velocity of the projectile along with the uncertainty in the initial velocity:
$$\boxed{5.96\plusmn0.03 \frac{m}{s}}$$

## Conclusion

In this lab, we have determined the initial velocity of the projectile and the uncertainty of $5.96\plusmn0.03 \frac{m}{s}$ in the initial velocity by using the data collected in the lab.

Some sources of error in this lab include:
**Systematic Error:** Air resistance slowing the projectile and the bob slow the projectile in this experiment.
**Systematic Error:** The ridges at the end to catch the projectile can also slow the bob down.
