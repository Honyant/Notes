# Maxima and minima

$f(c)$ is the **absolute global min** value of f if $f(c)\leq f(x)$ for all $x \in D_f$

$f(c)$ is the **absolute global max** value of f if $f(c)\geq f(x)$ for all $x \in D_f$

$f(c)$ is the **absolute local min** value of f if $f(c)\leq f(x)$ for all $x \in (c \pm \varepsilon)$

$f(c)$ is the **absolute local max** value of f if $f(c)\geq f(x)$ for all $x \in (c \pm \varepsilon)$

## Consequence of definitions

- Endpoints might be global max or min but can never be local max or min

Extreme value, extrema (indicate if they are max or min)

## Extreme value theorem

If f is continuous on a closed interval $[a,b]$, then f attains an absolute max and absolute min value on $[a,b]$.

If g has a local max or min at c and $f'(c)$ exists, then $f'(c)=0$.

A critical number of f is a number c in the domain of f such that

- $f'(c)=0$
- or $f'(c)$ DNE

If f has a local max or min at c, then c is a critical number.

## Candidates Test

To find absolute max/min values of a continuous function f on a closed interval $[a,b]$:

1. Find all critical values for f on $(a,b)$
2. Find f of those critical numbers
3. Find f of the endpoints
4. Compare y vals

There is NO absolute max, if looks like theres a hole at where the max should be

### Example

Find the abs max/min of $f(x)=x +\frac{1}{x}$ on $[0.2,4]$
f is continuous on $[0.2,4]$
**Critical values:**

$f'(x)=1-x^{-2}$
$f'(x)$ undefined at $x=0$ but thats not in domain
$f'(x)=0$ when $1=x^{-2} \implies x^2=1 \implies x=\pm 1$, but only 1 is in the interval

$f(1)=1+\frac{1}{1}=2$
$f(0.2)=0.2+\frac{1}{0.2}=5.2$
$f(4)=4+\frac{1}{4}=4.25$
$f(0.2)=5.2$ is the abs max val
$f(1)=2$ is the abs min val

## Some theorems

Rolle's theorem
On a continuous and differentiable interval $[a,b]$ where $f(a)=f(b)$ then $\exists x \in (a,b)$ such that $f'(x)=0$

Mean Value theorem

On a continuous and differentiable interval $[a,b]$ then $\exists x \in (a,b)$ such that $f'(x)=\frac{f(a)-f(b)}{a-b}$
Basically, instantaneous rate of change=avg rate of change