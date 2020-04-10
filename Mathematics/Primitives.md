# Primitives

## Common functions' primitives

#### Constant

$ \forall (\lambda,C) \in \R^2 $
$ \boxed{\int(\lambda)dx = \lambda \times x + C} $

#### Polynoms

$ \forall  (x,C) \in \R^2, \forall n \in \N^* $
$ \boxed{\int(x^n)dx = \frac{x^{(n+1)}}{n+1} + C} $

This gives in particular :

* $ \boxed{\int(x)dx}
\\ = \int(x^1)dx
\\ = \frac{x^{(1+1)}}{1+1} + C
\\ \boxed{= \frac{x^2}{2} + C} $
* $ \boxed{\int(x^2)dx}
\\ = \frac{x^{(2+1)}}{2+1} + C
\\ \boxed{= \frac{x^3}{3} + C} $

#### Inverse

$ \forall x \in \R^* , \forall C \in \R, \forall n \in \N, n \ge 2 $
$ \boxed{\int\left(\frac{1}{x}\right)dx = ln |x| + C} $
$ \boxed{\int\left(\frac{1}{x^n}\right)dx = \frac{-1}{(n-1)\times x^{(n-1)}} + C} $

#### Square root

$ \forall x \in \R_+^* , \forall C \in \R $
$ \boxed{\int\left(\frac{1}{\sqrt{x}}\right)dx = 2 \times \sqrt{x} + C} $

#### Exponential

$ \forall (x,\lambda,C) \in \R^3, \forall a \in \R_+^* $
$ \boxed{\int \left[a^{(\lambda \times x)}\right]dx = \frac{1}{\lambda \times ln(a)} \times a^{(\lambda \times x)} + C} $

This gives in particular :

* $ \boxed{\int \left[ e^{(\lambda \times x)} \right]dx}
\\ = \frac{1}{\lambda \times ln(e)} \times e^{(\lambda \times x)} + C
\\ \boxed{= \frac{1}{\lambda} \times e^{(\lambda \times x)} + C} $

#### Logarithm

$ \forall x \in \R_+^* , C \in \R $
$ \boxed{\int [ln(x)]dx = x \times ln(x) - x + C} $

