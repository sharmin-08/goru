# Trapezoidal Rule For Numerical Integration
## 1. Overview
In this project, we used the **Trapezoidal Rule** to approximate the integral of  
`f(x) = e^(-x^2)` from 0 to 1.  
It also compares the result with a high-precision value using the built-in `erf()` function from `<cmath>`.

---
## 2. Objectives
- Apply numerical integration using the trapezoidal rule.  
- Verify the result against a high-precision library value.  
- Analyze how the number of subintervals (`n`) affects accuracy.

---
## 4. Method / Formula
The trapezoidal rule formula:

I ≈ (h / 2) * [ f(a) + f(b) + 2 * Σ f(a + i*h) ]

Where:  
- `a` = lower limit (0)  
- `b` = upper limit (1)  
- `h = (b - a) / n`  
- `n` = number of subintervals (user input)

---
