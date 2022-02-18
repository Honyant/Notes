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


### Capacitors

**In series:** $C_{eq}=\frac{1}{\sum \frac{1}{C_i}}$
**In parallel:** $C_{eq}=\sum C_i$

![picture 2](https://i.imgur.com/89YLQ3z.png)  


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

# Example:

Don't feel like drawing a shitty diagram on my trackpad.

$24V-6\Omega I_2-4\Omega I_1=0$
$12V-2\Omega I_3-6\Omega I_2=0$
$I_2=I_1+I_3$