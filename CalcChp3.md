
# 2nd derivative test


# Limits at infinity

n is the largest exponent

$$\lim_{x \to \infty} \frac{a_1 x^n+ a_2 x^{n-1}+\cdots}{b_1 x^n+b_2x^{n-1}+ \cdots}
$$
$$=\lim_{x \to \infty} \frac{a_1+a_2 x^{-1} + \cdots}{b_1 + b_2 x^{-1} \cdots}$$

$$=\frac{a_1}{b_1}$$

# Antiderivatives

The function $f(x)=6x$ has infinitely many antiderivatives.
$F(x)=3x^2+C$
$F$ is the antiderivative of $f$

# Fundamental theorem of Calculus
Derivative of the anti-derivative of a function is the original function


**FTC pt.2**
If $f$ in cont. on $[a,b]$, them $\int_{a}^{b} f(x) dx = F(b)-F(a)$ where $F$ is any antiderivative of $f$.

Proof:
let $g(x)=\int_a^x f(t) dt$
Then $g'(x)=f(x)$
Then $g(x)$ is an antiderivative of $f(x)$

$F(x)=g(x)+C$
$\int_{a}^{b} f(t) dt = \int_a^b f(t) dt - \int_a^a f(t) dt$
$=g(b)-g(a)$
$=(F(b)-C)-(F(a)-C)$
$=F(b)-F(a)$

#### New Notation

$\int_{-2}^1 x^2+x dx= (\frac{x^3}{3}+\frac{x^2}{2}) \bigg |_{-2}^1$
$=(\frac{1}{3}+\frac{1}{2})-(-\frac{8}{3}+\frac{4}{2})=\frac{3}{2}$

### Trapezoidal Integration

$\int_a^b f(x) dx \approx \Delta x_1 \frac{f(x_0)+f(x_1)}{2}+\Delta x_2 \frac{f(x_1)+f(x_2)}{2}+\cdots+\Delta x_n \frac{f(x_{n-1})+f(x_n)}{2}$

**Trapezoidal rule:** If $\Delta x$ are constant, then 
$\int_a^b f(x) dx=\frac{\Delta x}{2} (f(x_0)+2f(x_1)+2f(x_2)+...+2f(x_{n-1})+f(x_n))$

### U Substitution

$du=\frac{du}{dx}\cdot dx$