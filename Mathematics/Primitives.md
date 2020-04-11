# Primitives

## Composing with primitives

#### Sum

$ \boxed{\int\left[u(x)+v(x)\right]dx = \int[u(x)]dx + \int[v(x)]dx} $

#### Multiplying by a constant

$ \forall k \in \R $
$ \boxed{\int[k \times u(x)]dx = k \times \int[u(x)]dx} $

#### Quotient

$ \boxed{\int\left[\frac{\frac{d}{dx}u(x)}{u(x)}\right]dx = ln|u(x)|} $

#### Exponential

$ \boxed{\int\left[\frac{d}{dx}u(x) \times e^{u(x)}\right]dx = e^{u(x)}} $

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

#### Trigonometric

$ \forall (x,\phi, C) \in \R^3, \forall \omega \in \R^* $
$ \boxed{\int [cos(\omega \times x + \phi)]dx = \frac{1}{\omega} \times sin(\omega \times x + \phi)} $
$ \boxed{\int [sin(\omega \times x + \phi)]dx = \frac{-1}{\omega} \times cos(\omega \times x + \phi)} $
$ \boxed{\int [tan(x)]dx = -ln|cos(x)|} $
