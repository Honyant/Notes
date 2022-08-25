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
Solenoid is a good example: circular coil of wire.
Inductance of a Inductor: $L=\frac{N \Phi}{I}$

induced back emf: $\varepsilon_{loop}=-L\frac{d I}{d t}$

Energy stored in an inductor.
just like a capacitor, the battery needs to do work to get current to go through an inductor.


$P=IV=IL \frac{dI}{dt}$
$U=\int dU= \int IL \frac{dI}{dt}=\frac{LI^2}{2}$

$\int_{a}^{a+w} (\frac{\mu_0 I}{2\pi r} h * dr) = \frac{I h \mu_{0} \left(- \log{\left(a \right)} + \log{\left(a + w \right)}\right)}{2 \pi}$

## Inductor circuits

When current is changing, L behaves like a battery w/ $\varepsilon = - L \frac{d I}{d t}$

- current cannot change instantaneously because $\varepsilon$ would equal $\infty$
at steady state, the inductor behaves like a wire
at non-steady state, determine $\frac{d I}{d t}$ from $\varepsilon$

## LR circuit

Switch is at A for a long time.
$I=\frac{\varepsilon_0}{R}$
now switch to B at $t=0$
find $I(t)$
Switch to B at $t=0$

loop rule: $-IR-L\frac{dI}{dt}=0$

$-IR=L \frac{dI}{dt}$

$\frac{dI}{dt}<0$

$\int -R dt=\int \frac{dI}{I}$

$-\frac{Rt}{L}=\ln(\frac{I(t)}{\frac{\varepsilon_0}{R}})$

$I(t)=\frac{\varepsilon_0}{R} e^{-\frac{Rt}{L}}$

### Turning it on

$\varepsilon_0=IR-L\frac{dI}{dt}$
$L\frac{dI}{dt}=IR-\varepsilon_0$
$\frac{L dI}{IR-\varepsilon_0}=dt$
$\int_0^t \frac{dI}{dt}=\int_0^t \frac{dI}{I}$

$I(t)=\frac{\varepsilon_0}{R} (1-e^{-\frac{Rt}{L}})$

## CL circuit

$\frac{Q}{C}=L\frac{dI}{dt}$
$I=-\frac{dQ}{dt}$

$-Q\frac{1}{LC}=\frac{d^2 Q}{dt ^2}$

$w_0=\sqrt{\frac{1}{LC}}$


# DC vs AC

AC, you can change the voltage up and down.
You can't do this for DC.

Primary input coil. $N_p$ turns

Secondary output coil. $Ns$ turns

![picture 1](https://i.imgur.com/3HQFKV9.png)  

# Primary:
$V_p=V_{op} \cos(\omega t)$
$I_p=I_{op} \sin(\omega t)$

# Secondary:
$V_s=V_{os} \cos(\omega t)$
$I_s=I_{os} \sin(\omega t)$

**Self Inductance:** $L=\frac{\phi_0}{I}$
**Mutual Inductance:** $M_{12}=\frac{\Phi_{12}}{I_2}=M_{21}=M$

Primary:
$V_p-L_p\frac{d I_p}{dt}+M\frac{d I_s}{dt}=0$
$V_{op}=\omega (L_p I_{op})-M I_{os}$

Secondary:
$V_s-L_s\frac{d I_s}{dt}+M\frac{d I_p}{dt}=0$
$V_{os}=\omega (L_s I_{os})-M I_{op}$

Assume no power loss:

$P_p=P_s \to I_p V_p=I_s V_s$

$\omega (L_p I_{op}^2 - M I_{os}I_{op})=\omega (L_s I_{os}^2 - M I_{op}I_{os})$

$L_p I_{op}^2=L_s I_{os}^2$

$N_p^2 I_{op}^2=N_s^2 I_{os}^2$


$\frac{V_s}{V_p}=\frac{N_s}{N_p}$

# Inductance of Solenoid
$L=\frac{N \Phi}{I}=\frac{NBA}{I}=\frac{\mu_0 N A * \frac{N}{l} I}{I}$

Given the 4 Maxwells equations:

$\oint \vec E \cdot d \vec a = \frac{Q}{e_0}$
$\oint \vec B \cdot d \vec a = 0$
$\oint \vec B \cdot d \vec l = \mu_0 I$
$\oint \vec E \cdot d \vec l = -\frac{d}{dt} \int \vec B \cdot d \vec a$

For Amperes' law:
Withing the capacitor, we add an additional term due to displacement current.

$\oint \vec B \cdot d \vec l = \mu_0 I+\mu_0 \varepsilon_0 \frac{d}{dt} \int \vec E \cdot d \vec a$

Maxwell's equations in differential form:
$\nabla \cdot E = \frac{\rho}{e_0}$
$\nabla \cdot B = 0$
$\nabla \times B = \mu_0 J + \mu_0 \varepsilon_0 \frac{\partial E}{\partial t}$
$\nabla \times E = -\frac{\partial B}{\partial t}$

We can control a plane of magnetic field vectors.

We vary E but $E_y=E_z=0,\frac{\partial E}{\partial y}=\frac{\partial E}{\partial x}=0,\frac{\partial B}{\partial y}=\frac{\partial B}{\partial x}=0$

$E_x (z,t)$
$\nabla \times E = (0, \frac{\partial E_x}{\partial z}, 0)$ 
$\frac{\partial E}{\partial t} = (\frac{\partial E_x}{\partial t},0,0)$
$(\nabla \times B)_X=-\frac{\partial B_y}{\partial z}$

