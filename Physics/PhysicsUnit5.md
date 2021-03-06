- [Circuits](#circuits)
  - [Ohm's Law](#ohms-law)
  - [Drift Velocity](#drift-velocity)
  - [Things in parallel and in series:](#things-in-parallel-and-in-series)
    - [Resistors](#resistors)
      - [In series](#in-series)
      - [In parallel $R_{eq}=\frac{1}{\sum \frac{1}{R_i}}$](#in-parallel-r_eqfrac1sum-frac1r_i)
    - [Capacitors](#capacitors)
    - [Example of Resistor Circuit](#example-of-resistor-circuit)
    - [Another Example:](#another-example)
  - [Kirchhoff's Rules](#kirchhoffs-rules)
      - [Example:](#example)
      - [Example 2](#example-2)
  - [RC Circuit](#rc-circuit)
  - [Charging a Capacitor](#charging-a-capacitor)
  - [Discharging a Capacitor](#discharging-a-capacitor)

# Circuits

**current**- flow of charge
rate at which charge passes a point 
$I=\frac{dq}{dt}$
unit: ampere

**Conventional current** I is flow of positive charge.

**current density** $\vec J$, current per unit cross sectional area, $\frac{A}{m^2}$ vector of direction I
$I=\int \vec J \cdot d \vec a$

In most materials, $\vec J$ is proportional to $\vec E$.

$$\vec J=\sigma \vec E$$

$\sigma=$ conductivity

How do we establish current through a conductor?
We establish an e-field in the conductor.

How do we establish E-field through a conductor?
We establish a potential difference in the conductor.
with battery

How much current I do we set w/ specific $\Delta V$?
consider potential difference $\Delta V$ across conductor with length $L$, uniform cross sectional area $A$, uniform conductivity $\sigma$.

$J=\frac{I}{A}$
$\Delta V=-\int \vec E \cdot d \vec l=EL$

$\frac{I}{A}=\sigma \frac{\Delta V}{L}$

$\Delta V=(\frac{L}{\sigma A}) I=(\frac{\rho L}{ A}) I$

Resistivity: $\rho=\frac{1}{\sigma}$

Resistance: $\frac{\rho L}{A}$
$\frac{V}{A}=1 \Omega$

## Ohm's Law

not always true

$\Delta V = IR$

Always resistance $R=\frac{\Delta V}{I}$ Instantaneously
materials that have constant R obey Ohm's Law Ohmic.

Simple Circuit: Establish a constant $\Delta V$ with battery


## Drift Velocity

consider a conductor with charge carrier density $n =(\#/vo)$, cross sectional area $A$, drift speed $v_d$ 

find $I$

in time $dt$, a charge $dq$ passes point 
$I=\frac{dq}{dt}$


$dq=\frac{nAd_xe}{dt}$

$I=nev_dA$


$R=\frac{\rho L}{A}$

$\frac{d\omega}{dt}=\frac{dqV}{dt}$

$\boxed{P_{diss}=IV=I^2 R=\frac{V^2}{R}}$


**Steady State** - Current everywhere is constant in time

$I_A=I_B$



## Things in parallel and in series:

**Current** is constant in **series**.
**Voltage** is constant in **parallel**.

### Resistors

#### In series
 $R_{eq}=\sum R_i$

$\Delta V_{total}=\sum \Delta V_i$

In series: $\Delta V_{total}=IR_{eq}$

#### In parallel $R_{eq}=\frac{1}{\sum \frac{1}{R_i}}$


**Junction rule:** $I_{in}=I_{out}$

Voltage is constant in parallel.

$\frac{\Delta V}{R_{eq}}=\sum \frac{\Delta V_i}{R_i}$

$\therefore R_p=(\sum \frac{1}{R_i})^{-1}$

![picture 2](https://i.imgur.com/89YLQ3z.png)  
### Capacitors

**In series:** $C_{eq}=\frac{1}{\sum \frac{1}{C_i}}$
**In parallel:** $C_{eq}=\sum C_i$

### Example of Resistor Circuit
|  | V | I | R | P |
| --- | --- | --- | --- | --- |
| 4 | 2 | 2 | 2 | 8 |
| 6 | 2 | 2 | 3 | 12 |
| 2 | 2 | 2 | 1 | 4 |
| total | 12 | 2 | 6 | 24 |

too lazy to draw 2nd diagram

$R_{eq}=\frac{1}{\frac{1}{R_1}+\frac{1}{R_2}+\frac{1}{R_3}} = 2.20279$

### Another Example:
![picture 3](https://i.imgur.com/6XZovNY.png)  

It's helpful to redraw the circuit:

![picture 4](https://i.imgur.com/3QVKh7M.png)  

equiv resistance: $2 \Omega$

just simplify then work backwards

## Kirchhoff's Rules

**Junction Rule (current rule)**: charge does not build up at junction

current in = current out

$I_1=I_2+I_3$

**Loop rule (voltage rule)**: Going around any closed loop: $\sum \Delta V_i = 0$

#### Example:

![picture 1](https://i.imgur.com/94UFOMM.png)  

Finally got a diagram generator

$24V-6\Omega I_2-4\Omega I_1=0$
$12V-2\Omega I_3-6\Omega I_2=0$
$I_2=I_1+I_3$



#### Example 2
![picture 3](https://i.imgur.com/uozunLr.png)  

$I_1$ is highest, $I_3$ is lowest.

$I_1=I_2+I_3$
$18-8I_1-11I_2-12-7I_2-5I_1=0$
$36+7I_2-12+11I_2-5I_1=0$
$\downarrow$
$I_2=I_1+I_3$
$6-15I_1-18I_2=0$
$24+18I_2-5I_1=0$
$\downarrow$
$I_1=2.88A$
$I_2=-0.416A$
$I_3=3.3A$

## RC Circuit

![picture 3](https://i.imgur.com/DJpCs1T.png)  
Switch is without battery for a long time, then switch to A at t=0
What happens to Q_C,I_R,... as funciton of time?
$I(t)=\frac{\epsilon}{R}e^{-ta}$
$V(t)=\epsilon e^{-ta}$
$Q(t)=C \epsilon- e^{-ta}+smth$//asymptotically approaches $C \epsilon$ starts at $0$

**An uncharged capacity is the same as a wire.
A fully charged capacitor is the same as an open circuit.**

![picture 4](https://i.imgur.com/5QDMN9o.png)  

## Charging a Capacitor

Circuit with: Battery with emf $\varepsilon$, switch, resistor with resistance $R$, capacitor with capacitance $C$.
Find $Q(t)$
$\varepsilon-IR-\frac{Q}{C}=0$
$\varepsilon-R\frac{dQ}{dt}-\frac{Q}{C}=0$
$\frac{dQ}{dt}=(\varepsilon C-Q)\frac{1}{RC}$
$\int_{Q(0)}^{Q(t)} \frac{1}{\varepsilon C-Q} dQ =\int_0^t \frac{dt}{RC}$
$-\ln|\frac{\varepsilon C - Q(t)}{\varepsilon C - Q(0)}|=\frac{t}{RC}$
$\frac{\varepsilon C - Q(t)}{\varepsilon C}=e^{-\frac{t}{RC}}$
$$Q(t)=\varepsilon C (1- e^{-\frac{t}{RC}})$$

$$I(t)=\frac{dQ}{dt}=\frac{\varepsilon}{R}e^{-\frac{t}{RC}}$$

$$V(t)=\frac{Q(t)}{C}=\varepsilon (1- e^{-\frac{t}{RC}})$$

$\tau=RC$ 
$\tau=$ characteristic time scale for circuit
time to reach $1-\frac{1}{e}$

## Discharging a Capacitor

blah blah blah switch flips after capacitor is charged to max
$IR+\frac{Q}{C}=0$
$\frac{dQ}{dt}=-\frac{Q}{RC}$
$\int_{Q(0)}^{Q(t)}  \frac{dQ}{Q} =\int_0^t (-\frac{dt}{RC})$
$\ln|\frac{Q(t)}{Q(0)}|=-\frac{t}{RC}$
$Q(t)=e^{-\frac{t}{RC}}*Q(0)$
$Q(0)=\varepsilon C$
$\boxed{Q(t)=e^{-\frac{t}{RC}}\varepsilon C}$

$I=-\frac{dQ}{dt}$
$\boxed{I(t)=\frac{\varepsilon}{R} e^{-\frac{t}{RC}}}$

$\boxed{V(t)_C=\varepsilon e^{-\frac{t}{RC}}}$

![picture 1](https://i.imgur.com/3Whl4sg.png)  

