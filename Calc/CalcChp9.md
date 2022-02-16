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