# Work and Energy

**Energy** - ability to do work
$1\mathrm J=1 \frac{\mathrm {kg} \space \mathrm m^2}{\mathrm s^2}$
$W=\vec F \cdot \vec d=|\vec F| |\vec d| \cos(\theta)$

law of cosines $\implies$
$|A|^2+|B|^2-2|A||B| \cos \theta = |B-A|^2$
$\implies A \cdot B= A_x B_x+A_yB_y$

Find components and then you don't need to find $\theta$

W for constant force
$W=F \Delta x \cos \theta$

**Frictional work is always negative**

Example: a particle moves along a straight path with a displacement  $\vec s  =(4,-3)$ while the force $\vec F=(2,5)$ acts on it.

1. Work done by F
$2*4+5*(-3)=8-15=-7 \mathrm J$
2. Angle between them
$-7=|F||S| \cos \theta$

$$\left(\cos^{-1}\left(\frac{-7}{(\sqrt{4+25}*\sqrt{16+9})}\right)\right) = 105.06848815949222 \space \mathrm{degrees}$$

## Work definition(general): variable form, every path)

Path integral over a vector field
$$W=\int \vec F\cdot \mathrm d \vec s$$

1 dimensional
$W=\int F_x \mathrm dx$

Ex:

$\int_2^6 (3x-2 )dx $
$\frac{3}{2} x^2 -2x \bigg|_2^6$
$3/2*36-12-3/2*4+4=\textcolor{red}{40 \mathrm J}$

$\int_0^x  -kx \space \mathrm dx$
$=-\frac{kx^2}{2}$

y=0
yx + 2 dy =2y 

2

$y=x^2$
$dy= 2x dx$

$\int y dx+ \int 2x dy =\int x^2 dx+\int 2x 2x dx= \int_0^1 5x^2 dx=\frac{5}{3} J$

## Newton's second law for work


Work by net force $W_{net}= \int F_{net} \mathrm dx = \int (ma) \mathrm dx$

$$m \int \frac{\mathrm d^2 x}{ \mathrm dt^2} \frac{\mathrm d}{ \mathrm dt} \mathrm dt$$

$$ \frac{\mathrm d^2 x}{ \mathrm dt^2} \frac{\mathrm d}{ \mathrm dt}=\frac{\mathrm d}{ \mathrm dt}[\frac{1}{2}( \frac{\mathrm dx}{ \mathrm dt})^2]$$

$$=\frac{m}{2} \int_0^t ( \frac{\mathrm dx}{ \mathrm dt})^2 dt$$

$$=\frac{1}{2} mv^2-\frac{1}{2} mv_0^2$$

**Kinetic energy:**
$K=\frac{1}{2}mv^2$

**Work-Energy Theorem:**
$W_{net}= \Delta K$

Example:
A 70kg bse runner slides into 2nd base moving 4 m/s $\mu_k=0.7$. Stops at base.

- How much energy is lost to friction?
$1/2*70*4^2 = 560$
- How far does he slide?
$F=mg \mu_k$
$560=Fd=d/mg \mu_k=560/70/9.81/0.7 = 1.164991990680064$

**Conservative Forces:** define special class of force, F, such that.

$F=-\nabla U$
$\nabla \times \nabla U \equiv 0$

1. F depends only on position, $\vec r$.
2. Work done by F between points a&b is same for all paths between a&b.

**Def:**
Associated with every cons. force is a positive energy function, $U(\vec r)$ (of only position).
chose reference position $\vec r_0$ where $R(\vec r_0)=0$
$$U(\vec r) \equiv -W (\vec r_0 \to  \vec r)=-\int_{\vec r_0}^{\vec r} \vec F \cdot \mathrm d \vec r$$


$$W(\vec r_1 \to \vec r_2)=-\Delta U$$

W-K theorem: If all forces are cons.
$W_{net}=\Delta K=-\Delta U \to \Delta K+ \Delta U=0$
$\Delta(K+U)=0$


![picture 1](https://i.imgur.com/c0afRjh.png)  
$K+U=30$ everywhere if all forces are conservative
$E=K+U$

Conservative force|non-cons.
-----|-----
gravity|friction
spring|people
electrostatic|

$W_g=-mgh$
$\Delta U_g=-mgh$

$\textcolor{red}{\sqrt{(1/2kx^2+mgh)2/m}}$

$1/2kx^2=mg(h_2-h_1)$
$\textcolor{red}{\sqrt{mg(h_2-h_1)*2/k}}$

$mgh=dgm \mu$
$\mu =\frac{h}{d}$

$F_x= -\frac{\mathrm dU}{ \mathrm dx}$

$U=\frac{8-x^3}{x^4}=8x^{-4}-x^{-1}$
$ F=-\frac{\mathrm d U}{ \mathrm dt}=-32x^{-5}+x^{-2}$
$0=-32x^{-5}+x^{-2}$
$x=\sqrt[3]{32}$

### Momentum

$\vec p= m \vec v$
$\vec p_{tot}= \sum \vec p_n$
$ \frac{\mathrm d \vec p}{ \mathrm dt}= m \frac{\mathrm d \vec v}{ \mathrm dt}$

#### Impulse momentum theorem

$$\vec J = \int \vec F_{net} \mathrm dt=\Delta \vec p$$

momentum is conserved if no net ext. force
