# Improper Integrals
Case 1: $F$ is continuous on $[a,b]$
> We can use FTC Part 2 if we can find antiderivative

Case 2: There are a finite number of removable or jump discontinuities
> We can use FTC Part 2 in the pieces.

Case 3: There is an infinite discontinuity between $a$ and $b$
> This is Type II improper integral

### Example: 

**Wrong:**
$\int_{-1}^{1} \frac{1}{x^2} dx$
$=(-\frac{1}{x})|_{-1}^{1}$
$-1-1=-2$

**Correct:**
$\int_{-1}^{1} \frac{1}{x^2} dx$
$=(-1)*(\frac{1}{x}|_{-1}^{0}+\frac{1}{x}|_{0}^{1})$
$\boxed{Diverges}$
skipped a few steps but basically each individual term diverges so the overall integral diverges

## Line integrals

Length of segment $\overline{P_1 P_2}= \sqrt{(\Delta x)^2 + (\Delta y)^2}$

$\Delta y \approx (\frac{dy}{dx}) \Delta x$

$dy=\sqrt{1+\frac{dx^2}{dy^2}} \cdot dx$
$dy=\sqrt{1+\left(\frac{dx}{dy}\right)^2} \cdot dx$



**Example:**
What is the length of the curve $f(x)=\frac{x^3}{2}$ between $x=-1$ and $x=5$?

$$\int_{-1}^{5} \sqrt{1+\left(\frac{3x^2}{2}\right)^2} dx$$

