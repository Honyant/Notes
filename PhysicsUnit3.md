# Unit 3

## Rotational Motion
For the rotation of a rigid body, if we have two points  $r_1$ and $r_2$ on the body, then the angular velocity of both points is the same, $\omega=\frac{v_1}{r_1} = \frac{v_2}{r_2}$.

### Angular Displacement
Always in radians, $\Delta\theta = \frac{\Delta s}{r}$

### Angular Velocity
$\omega = \frac{d \theta}{d t} = \frac{v_t}{r}$

**Vector** Right Hand Rule: Curl fingers with rotation, then thumb is pointing in the direction of the vector.

### Angular Acceleration
$\alpha = \frac{d \omega}{d t} = \frac{a_t}{r}$
$\star a=\sqrt{a_c^2+a_t^2}$

### Torque

![picture 1](https://i.imgur.com/0sUdWr7.png)  

$\tau =r T_\perp=r_\perp F=rF\sin\theta$
Cross product:
$\vec \tau =\vec r \times \vec F$

Angular Acceleration $\alpha = \frac{a_t}{r}$
$\tau=m r^2 \alpha$

$\sum \tau=(\sum_i m_i r_i^2) \alpha_i$
so, moment of inertia $I=\sum_i m_i r_i^2$ is conserved.

#### Newton's 2nd Law for rotation: 
$rF_t=\tau_{net}=I\alpha$


#### Atwoods machine with two masses and pulley with mass 
T1 T2

(T1-T2)=0.5 mp  a
m1g-t1=m1a
t2-m2g=m2a

g(m1-m2)=a(0.5mp+m1+m2)
$a=(g(m1-m2))/(0.5mp+m1+m2)$
in latex:
$a=\frac{g(m_1-m_2)}{0.5m_p+m_1+m_2}$

#### Stalling double radius pulley
What angle do you pull this at to get the pulley to stall?
![picture 2](https://i.imgur.com/vTZHiRY.png)  


torque: $f r_2 = t r_1$
$f = \frac{t r_1}{r_2}$
force_x: $T \cos(\theta) - f = 0$
$cos(\theta) = \frac{r_1}{r_2}$
$\theta = \cos^{-1}(\frac{r_1}{r_2})$

## Rolling without slipping
$\Delta x_{cm}= R \Delta \theta$
$v_{cm}= R \omega$
$a_{cm}= R \alpha$

## Moment of Inertia

$I_tot=\sum_i m_i r_i^2$
$I=\int r^2 \mathrm dm$

$$\int_{-\frac{l}{2}}^{\frac{l}{2}} x^2 \frac{m}{l} \mathrm dx$$

$$ \frac{m}{l} \frac{1}{3} x^3 \bigg |_{-\frac{l}{2}}^{\frac{l}{2}}$$

$$ ml^2 \frac{1}{3} 2 \frac{1}{8}$$
$$ ml^2 \frac{1}{12} $$

#### Rod with nonuniform density

Find moment of inertia of thin around extended from x=0 to x=l with linear density $\lambda=\gamma \frac{x^3}{l^3}$ about axis perp to rod through x=0. Find answer in terms of M and L.

$M=\int_0^L \gamma \frac{x^3}{L^3} \mathrm dx$
$M=\frac{\gamma}{L^3} \frac{L^4}{4}=4\frac{M}{L}$

$\int_0^L x^2 \gamma \frac{x^3}{L^3} \mathrm dx$
$\frac{\gamma}{L^3} \frac{L^6}{6}$
$\frac{4\frac{M}{L} L^3}{6}$
$=\frac{2ML^2}{3}$

#### Uniform disk M, R around center of mass
$dA=2\pi r dr$

$dm=\sigma dA$
$\sigma=\frac{M}{\pi R^2}$
$dm=\frac{M}{\pi R^2} 2 \pi r dr=\frac{2 M r}{R^2} dr$

$\int_0^R r^2 \frac{2 M r}{R^2} \mathrm dr$
$\frac{2 M}{R^2} \int_0^R r^3 \mathrm dr$
$\frac{2 M}{R^2} \frac{R^4}{4}$
$\frac{M R^2}{2}$

#### Hollow sphere with thickness
$d=r sin\theta$
$dm=\rho DV$
$\rho=\frac{M}{\frac{4}{3}\pi (R_2^2-R_1^2)}$
$dV=dr \cdot rd\theta \cdot rsin\theta d\phi$

$\iiint r^2 sin^2(\theta) \rho r^2 sin(\theta) \mathrm d\phi \mathrm dr \mathrm d\theta$

$$\rho \int_{0}^{\pi} \int_{R_1}^{R_2} \int_0^{2\pi} r^4 sin^3(\theta) \mathrm d\phi \mathrm dr \mathrm d\theta$$


$$\rho \int_{0}^{\pi} \int_{R_1}^{R_2} 2\pi r^4 sin^3(\theta)  \mathrm dr \mathrm d\theta$$
$$2 \pi \rho \int_{0}^{\pi}  sin^3(\theta) \frac{R_2^5-r_1^5}{5}\mathrm d\theta$$
$$2 \pi \rho  \frac{R_2^5-r_1^5}{5} \int_{0}^{\pi}  sin^3(\theta) $$

$$2\rho \frac{R_2^5-r_1^5}{5} \int_{0}^{\pi}  sin^3(\theta) $$

$$ 2\frac{4}{3} \pi \rho \frac{R_2^5-r_1^5}{5} $$

$$ \frac{4}{3} \pi \frac{M}{\frac{4}{3}\pi (R_2^2-R_1^2)} \frac{R_2^5-r_1^5}{5} $$

$$\boxed{I=\frac{2}{5} M \frac{R_2^5-r_1^5}{R_2^2-R_1^2}}$$

Solid Sphere $(R_1=0, R_2=R)$:
$$\boxed{I=\frac{2}{5} M R^2}$$

Spherical Shell $(R_1=R_2=R)$:

$$\lim_{R_1\to R_2} \frac{R_2^5-R_1^5}{R_1^2-R_1^2}$$
$$\lim _{R_1\to R_2} \frac{-5R_1^4}{-3R_1^2}=\frac{5}{3}R_2^2$$

$$\boxed{I=\frac{2}{3} M R^2}$$