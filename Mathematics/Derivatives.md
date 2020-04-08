# Derivatives

## Composing with Derivatives

#### Sum

$ \boxed{\frac{d}{dx}(f(x)+g(x)) = \frac{d}{dx}f(x) + \frac{d}{dx}g(x)} $

#### Product

$ \boxed{\frac{d}{dx}(f(x) \times g(x)) = f(x) \times \frac{d}{dx}g(x) + \frac{d}{dx}f(x) \times g(x)} $

#### Multiplying by a real number

$ \forall k \in \R $
$ \boxed{\frac{d}{dx}(k \times f(x))}
\\ = k \times \frac{d}{dx}f(x) + \frac{d}{dx}(k) \times f(x)
\\ = k \times \frac{d}{dx}f(x) + 0 \times f(x)
\\ \boxed{= k \times \frac{d}{dx}f(x)} $

#### Difference

$ \boxed{\frac{d}{dx}(f(x)-g(x))}
\\ = \frac{d}{dx}(f(x)+[-1 \times g(x)])
\\ = \frac{d}{dx}f(x) + \frac{d}{dx}[-1 \times g(x)]
\\ = \frac{d}{dx}f(x) + [-1 \times \frac{d}{dx}g(x)]
\\ \boxed{ = \frac{d}{dx}f(x) - \frac{d}{dx}g(x)} $

#### Inverse

$ \boxed{\frac{d}{dx}(\frac{1}{f(x)}) = \frac{-\frac{d}{dx}f(x)}{f(x)^2}} $

## Common functions' derivatives

#### Constant

$ \forall C \in \R $
$ \boxed{\frac{d}{dx}(C) = 0} $

#### Polynom

$ \forall x \in \R, \forall n \in \N $
$ \boxed{\frac{d}{dx}(x^n) = n \times x^{(n-1)}} $

This gives in particular :

* $ \boxed{\frac{d}{dx}(x)} = \frac{d}{dx}(x^1) = 1 \times x^{(1-1)} = 1 \times 1 = \boxed{1}$
* $ \boxed{\frac{d}{dx}(x^2)} = 2 \times x^{(2-1)} = \boxed{2 \times x} $

#### Multiplicative inverse

By using the polynom derivative :

$ \forall x \in \R^* , \forall k \in \N $
$ \boxed{\frac{d}{dx}(\frac{1}{x^k})} = \frac{d}{dx}(x^{-k}) = -k \times x^{(-k-1)} = \boxed{\frac{-k}{x^{(k+1)}}} $

This gives in particular :

* $ \boxed{\frac{d}{dx}(\frac{1}{x})} = \frac{d}{dx}(\frac{1}{x^1}) = \frac{-1}{x^{(1+1)}} = \boxed{\frac{-1}{x^2}} $
* $ \boxed{\frac{d}{dx}(\frac{1}{x^2})} = \frac{-2}{x^{(2+1)}} = \boxed{\frac{-2}{x^3}} $

#### N-root

By using the polynom derivative :

$ \forall x \in \R_+, \forall n \in \N $
$ \boxed{\frac{d}{dx}(^{n}\sqrt{x})} = \frac{d}{dx}(x^{\frac{1}{n}}) = \frac{1}{n} \times x^{(\frac{1}{n}-1)} = \frac{1}{n} \times x^{\frac{1}{n}\times(1-n)} = \frac{1}{n} \times (^{n}\sqrt{x})^{(1-n)} = \frac{1}{n \times(^{n}\sqrt{x})^{(n-1)}} = \boxed{\frac{1}{n \times ^{n}\sqrt{x^{(n-1)}}}} $

This gives in particular :

* $ \boxed{\frac{d}{dx}(\sqrt{x})} = \frac{d}{dx}(^{2}\sqrt{x}) = \frac{1}{2 \times \sqrt{x^{(2-1)}}} = \boxed{\frac{1}{2 \times \sqrt{x}}} $
* $ \boxed{\frac{d}{dx}(^{3}\sqrt{x})} = \frac{1}{3 \times \sqrt{x^{(3-1)}}} = \boxed{\frac{1}{3 \times ^{3}\sqrt{x^2}}} $

#### Exponential

$ \forall (x,\alpha) \in \R^2 $
$ \boxed{\frac{d}{dx}(\alpha^x) = \alpha^x \times ln(\alpha)} $

This gives in particular :

* $ \boxed{\frac{d}{dx}(e^x)} = e^x \times ln(e) = e^x \times 1 = \boxed{e^x} $

#### Logarithm

$ \forall x \in \R^* $
$ \boxed{\frac{d}{dx}(ln|x|) = \frac{1}{x}} $

This gives in particular :

* $ \boxed{\frac{d}{dx}(log_n|x|)} = \frac{d}{dx}(\frac{1}{ln(n)} \times ln|x|) = \boxed{\frac{1}{x \times ln(n)}}, \forall n \in \  ]0,1[ \cup ]1,+\infty[ $

#### Trigonometric

$ \forall x \in \R $
$ \boxed{\frac{d}{dx}(cos(x)) = -sin(x)} $ *(+ 1/4<sup>th</sup> on the trigonometric circle)*
$ \boxed{\frac{d}{dx}(sin(x)) = cos(x)} $ *(+ 1/4<sup>th</sup> on the trigonometric circle)*
