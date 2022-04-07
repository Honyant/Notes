# Inductance

emf- a voltage difference capable fof doing continous work (like a battery)

emd around a closed loop

$\varepsilon =  \oint \vec E \cdot d \vec l$

recall in Estatics
$\Delta V= 0$

Now we are in electrodynamics.

Magenetic Flux
$\Phi_B = \int _S \vec B \cdot d \vec a$

If we have uniform B and flat A

$\Phi_B = \vec B \cdot \vec A= |B| |A| \cos(\theta)$

units $T m^2$

Find the flux through 1 turn of solenoid

$B=\mu_0 n I$
$\Phi=\mu_0 n I \pi r^2$

## Faraday's Law

An induced ef is cause by changing magnetic flux
$\varepsilon_{loop}=-\frac{d \Phi_B}{d t}$

$\oint_{\partial A} \vec E \cdot d \vec l = - \frac{d }{d t} \int_S \vec B \cdot d \vec a$

Ex: A square wire loop 0.1 m by 0.1 m is perpendicular to b-field  that is increasing at a rate of 0.1 T/s

What is $|\varepsilon|$ in the loop

$\Phi_B = |B| |A|$
$\frac{d |Phi}{dt}=A \frac{d B}{dt}=0.01*0.1=10^{-3} V$

# Lenz's Law 
minus sign in Faraday's law

The induced emf induces a current that flows in the direction that creates an induced magnetic field that **opposes the change of flux**.

# 2 different E -field
Electrostatic field: can define volage
- $\Delta V = -\int_A^B \vec E \cdot d \vec l$
- $\oint \vec E \cdot d \vec l = 0$
- lines do not form closed loops
- conservative

Electromagnetic (dynamic) field: 
- Changing B flux
- $\oint \vec E \cdot d \vec l \neq 0$
- field lines form closed loops
- not conservative
- no unique $\Delta V$


### Motional emf - 2 ways

1. Imagine a wire loop moving into a region of uniform B-field.

$f_B= force per unit charge = vB$
$df\varepsilon = \oint \vec f_B \cdot d \vec l= vBL$

# Conducting bar falling down

differential equation for $v(t)$

terminal velocity


$ m \frac{dv}{dt} = mg - \frac{BLv}{R} LB$

$m \frac{dv}{dt} = mg - \frac{B^2 L^2 v}{R}$

terminal velocity=$\frac{mgR}{B^2 L^2}$

# Inductor

This stores energy in magnetic field.



Inductance of a Inductor: $L=\frac{N \Phi}{I}$

induced back emf: $\varepsilon_{loop}=-L\frac{d I}{d t}$

Energy stored in an inductor.
just like a capacitor, the battery needs to do work to get current to go through an inductor.


$P=IV=IL \frac{dI}{dt}$
$U=\int dU= \int IL \frac{dI}{dt}=\frac{LI^2}{2}$

$\int_{a}^{a+w} (\frac{\mu_0 I}{2\pi r} h * dr) = \frac{I h \mu_{0} \left(- \log{\left(a \right)} + \log{\left(a + w \right)}\right)}{2 \pi}$