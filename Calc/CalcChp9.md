# Differential Equations
A differential equation is an equation

The order of a differential equation is the highest derivative in the equation.

$y'''=x+y$ is a third order differential equation because the highest derivative is $y'''$.

$\frac{d^2 y}{dx^2} + 2\frac{dy}{dx} + y = 5$ is a second order differential equation because the highest derivative is $y''$.


**Solving a differential equation** means to find all functions which satisfy the differential equation called the general solution.

Ex: with $\frac{dy}{dx}=3e^{5x}$, we have the general solution $y=\frac{3e^{5x}}{5} + C$. 

To find a particular solution to a differential equation requires knowing one or more facts called initial conditions.

$y(0)=3$ or $y'(1)=5$
This is called solving an initial value problem.

$\frac{dy}{dx}=3e^{5x}$ and $y(0)=1 \to$ $y=\frac{3e^{5x}}{5}+\frac{2}{5}$

**Another Example**

$\frac{dy}{dt}=y^2$ and $y(0)=1$
$\frac{dy}{y^2}=dt$

$\int y^2 dy=\int dt$
$-y^{-1}=t+C$
$y=\frac{1}{t+C}$

## Euler's Method
formula:$