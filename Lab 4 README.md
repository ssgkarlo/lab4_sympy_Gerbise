# lab4_sympy_Gerbise

This activity demonstrates how Python, with the help of the sympy library, can be used to explore core concepts in Calculus such as symbolic manipulation, limits, derivatives, series expansion, and equation solving without doing any manual calculations.

Required Module

from sympy import *

  Imports all necessary symbolic math functions from SymPy.

1. Playing with Symbols

x = symbols('x')
x + x

  x + x represents symbolic addition: 1x + 1x = 2x

2. Exploring Limits

limit(sin(x)/x, x, 0)

Even though the expression becomes 0/0, the result is assumed to be finite value so it becomes 1.

3. Playing with Derivatives

solve(Eq(x**2 - 4, 0), x)

This solves the quadratic equation: x^2 - 4 = 0
