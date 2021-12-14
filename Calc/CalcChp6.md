# Inverse of Function
A function is locally invertible/locally one-to-one if f is one to one in a neighborhood around b.

## Evaluate the inverse by inspection

Just look at the function $f^{-1}(c)$ and guess and check.

if $(x,y)$ is on $f$, then $(y,x)$ is on $f^{-1}$

$(a,b)=(a,f^{-1}(b))=(a,f(a))$, a point on $f$
$(b,a)=(f^{-1}(a),b)=(f(a),a)$, a point on $f^{-1}$

$f^{-1}(a)

If f is a 1-1 continuous function, then $f'(f^{-1}(a))\neq0$, then
$\boxed{\frac{d}{dx} f^{-1}(a) = \frac{1}{f'(f^{-1}(a))}}$


## Exponential Functions

Definition: $a^x=\lim_{r\to x} a^r$ where $r$ is rational

e is the number such that
$\lim_{h\to 0} \frac{e^h-1}{h}=1$


$\frac{d}{dx} a^x=a^x \ln(a)$

$\frac{d}{dx} \ln(x) = \frac{1}{x}$ only for x>0
$\frac{d}{dx} \ln(|x|) = \frac{1}{x}$

$\int \tan(x) dx = \int \frac{\sin(x)}{\cos(x)} dx$


## Logarithmic Differentiation

if you see something like
$\frac{d}{dx}f(x)^{g(x)}$

Acoording to ms. pool logarithmic differentiation is the only way to solve something of this form- when both the exponent and the base are non-constant.

Then you can rewrite it as

$\frac{d}{dx}e^{ln(f(x)^{g(x)})}=\frac{d}{dx}e^{g(x)ln(f(x))}=e^{g(x)ln(f(x))}*\frac{d}{dx}g(x)ln(f(x))$
$=f(x)^{g(x)}*(\frac{g(x)f'(x)}{f(x)}+g'(x)ln(f(x)))$
You dont need to memorize the formula, but you should understand the process.


