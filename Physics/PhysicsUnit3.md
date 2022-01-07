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

$$ \frac{4}{3} \pi \frac{M}{\frac{4}{3}\pi (R_2^2-R_1^2)} \frac{R_2^5-R_1^5}{5} $$

$$\boxed{I=\frac{2}{5} M \frac{R_2^5-r_1^5}{R_2^2-R_1^2}}$$

Solid Sphere $(R_1=0, R_2=R)$:
$$\boxed{I=\frac{2}{5} M R^2}$$

Spherical Shell $(R_1=R_2=R)$:

$$\lim_{R_1\to R_2} \frac{R_2^5-R_1^5}{R_1^2-R_1^2}$$
$$\lim _{R_1\to R_2} \frac{-5R_1^4}{-3R_1^2}=\frac{5}{3}R_2^2$$

$$\boxed{I=\frac{2}{3} M R^2}$$

### Parallel Axis Theorem

Relates I about axis through COM to I about a parallel axis
![picture 5](https://i.imgur.com/n4AFmDS.png)  

**Derivation:**
P is $(a,b)$ away
$$I_{CM}=\int(x^2+y^2)dm$$

$$I_p=\int((x-a)^2+(y-b)^2) dm$$

$$I_p=\int(x^2-2ax+a^2+y^2-2by+b^2) dm$$

$$I_p=\int(x^2+y^2) dm-2a \int(x) dm-2b\int(y) dm + \int (a^2+b^2) dm$$

$$I_p=I_{CM}-0-0+d^2 \int dm$$

$$I_p=I_{CM}+md^2$$

#### Example
Rod from 0 to l of mass m, spherical bob at the far end radius l/6 mass m/2. axis at 0

1/3 ml^2+(2/5 m/2 (l/6)^2+m(7l/6)^2)
17/10 l^2m

### Rotational Kinetic Energy
$K_{rot}=\sum_i{\frac{1}{2}m_i{v_i}^2}$
$=\frac{1}{2}\sum_i{m_i r_i^2 \omega^2}$
$=\frac{1}{2}I \omega^2$

Treat rolling as pure rotation+pure translation
$K=\frac{1}{2}mv^2+\frac{1}{2}I\omega^2$

## Angular Momentum

$L=\vec{p} \times \vec{r}$

$L=mvr\sin\theta$
nutron star

vf=(v'cost-v) m/M, v'sint m/M




$w= m v_f \times l$
$w=m l (v_0-v' cos t)$ 

# Gravity
## Universal Law of Gravitation

$F_g=\frac{Gm_1m_2}{r^2}(-\hat{r})$

$G=6.67408*10^{-11} \frac{Nm^2}{kg^2}$

gravitational acceleration:
$\vec{g}=\frac{Gm}{r^2}(-\hat{r})$

## Kepler's Laws
Huge paradigm shift in the laws of physics:

### 1. Planets orbit in ellipses with the sun as one focus

ellipse:
$\frac{x^2}{a^2}+\frac{y^2}{b^2}=1$

$r(\theta)=\frac{a(1-e^2)}{1+e\cos\theta}$
$e=$eccentricity

### 2. Planets sweep out equal areas of the ellipse in equal time

consequence of conservation of angular momentum:

### 3. Period is proportional to a^1.5

$T^2=a^3$
yr  = au

GmM/r^2=mv^2/r

$v=\sqrt{\frac{Gm}{r}}$

## g for spherically symmetric mass distribution

generally, $\mathrm d\vec{g}=\frac{G\mathrm dm}{r^2}(-\hat{r})$


Thin, hollow shell of mass m, radius R



![picture 2](https://i.imgur.com/1yMmK7F.png)  



by law of cosines,
$R^2=s^2+r^2-2sr\cos\theta$
$s^2=R^2-r^2-2sr\cos\phi$
$+2rR\sin\phi=2s ds$

$dm=\rho da$
$\rho=\frac{m}{4\pi R^2}$

$R \sin\theta$ 
$R d\phi$
$da=2\pi R \sin\theta R d\phi$


![picture 3](https://i.imgur.com/BX58W1q.png)  

By symmetry, $g_y=g_z=0$


$g=g_x=\int d g_x$

$dg_x=\frac{GM2\pi R^2\sin\theta d\phi}{4\pi R^2S^2}*\cos\theta$
$=\frac{GM2\pi R^2}{4\pi R^2S^2}\frac{2s ds}{2rR}\frac{s^2+r^2-R^2}{2sR}$
$g=\frac{GM}{4r^2R}\int (1+\frac{r^2-R^2}{s^2}) ds$

$g_{out}=\int_{r-R}^{r+R} \cdots=$

$g_{in}=\int_{R-r}^{r+R} \cdots=$ 


$g_{out}=\frac{GM}{4r^2R}(s-\frac{r^2-R^2}{s})|_{r-R}^{r+R}=\frac{GM}{r^2}$

$g_{in}=\frac{GM}{4r^2R}(s-\frac{r^2-R^2}{s})|_{R-r}^{r+R}=0$

proof by wolfram alpha

https://en.wikipedia.org/wiki/Shell_theorem


Ex: find g for a sphere of density $\rho = \Omega r^2$, radius R

$\boxed{g(r>R)=\frac{GM}{r^2}}$ by inspection (each shell is $\frac{Gm_i}{r^2}$)

$\boxed{g(r<R)=\frac{GM_{enclosed}}{r^2}}$ by inspection bcs inside of shell is 0

$M=\int_{0}^{r} dm$

$dm=\rho 4\pi r^2 dr$

$M= \int_0^r \rho 4\pi r^2 dr=\int_0^r \Omega 4 \pi r^4 dr$


$g(r>R)=\frac{4\pi \Omega G R^5}{5r^2}$

$g(r<R)=\frac{4\pi \Omega G r^3}{5}$

$\boxed{U(r)=-\frac{GMm}{r}}$

## Ex: find U, K , E for obejct in circular orbit of radius r around mass m

u=-GMm/r
g=v^2/r

GM/r^2=v^2/r

ke=1/2mv^2=1/2 GMm/r
=-u/2

E=1/2 U

1/2mv^2=GMm/r

$v=\sqrt{\frac{2GM}{r}}$

"rock" -jeremy yu when asked about the most abundant element in the solar system.

$\frac{2}{\cos(c)}$