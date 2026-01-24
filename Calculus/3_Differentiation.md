# **3_Differentiation**

Created: January 24, 2026
Written by: Nash Muñoz
Latest update: January 24, 2026
Updated by: 

---
> **(NOTE) Definition of a Derivative**
> A function $f$ is differentiable at $a$ if $f'(a)$ exists. It is differentiable on an open interval $(a,b)$ \[ or $(a,\infty)$ or ($-\infty,a$) or $(-\infty, \infty)$  \] if it is differentiable at every number in the interval.

*using the Leibniz notation*
### ***Derivatives of Polynomials and Exponential Functions***

**Constant Function**
$$
\frac{d}{dx}(c)=0
$$
**The Power Rule**
If $n$ is any real number, then
$$
\frac{d}{dx}(x^n)=nx^{n-1}
$$
**The Constant Multiple Rule**
If $c$ is a constant and $f$ is a a differentiable function, then
$$
\frac{d}{dx}[cf(x)]=c\frac{d}{dx}f(x)
$$
**The Sum Rule**
If $f$ and $g$ are both differentiable, then
$$
\frac{d}{dx}[f(x)+g(x)]=\frac{d}{dx}f(x)+\frac{d}{dx}g(x)
$$

**The Difference Rule**
If $f$ and $g$ are both differentiable, then
$$
\frac{d}{dx}[f(x)-g(x)]=\frac{d}{dx}f(x)-\frac{d}{dx}g(x)
$$

**Derivative of a Natural Exponential Function**
$$
\frac{d}{dx}(e^x)=e^x
$$
---
### ***The Product and Quotient Rules***

**The Product Rule**
If $f$ and $g$ are both differentials, then
$$
\frac{d}{dx}[f(x)g(x)]=f(x)\frac{d}{dx}[g(x)]+g(x)\frac{d}{dx}[f(x)]
$$
**The Quotient Rule**
If $f$ and $g$ are both differentiable, then
$$
\frac{d}{dx} \left[ \frac{f(x)}{g(x)} \right] = 
\frac{g(x)\frac{d}{dx}[f(x)]-f(x)\frac{d}{dx}[g(x)]}{[g(x)]^2}
$$
---
### ***Derivatives of Trigonometric Functions***

$$
\frac{d}{dx}{(\sin{x})}=\cos{x} \hspace{2cm} \frac{d}{dx}{(\csc{x})}=-\csc{x}\cot{x}
$$
$$
\frac{d}{dx}{(\cos{x})}=-\sin{x} \hspace{2cm} \frac{d}{dx}{(\sec{x})}=\sec{x}\tan{x}
$$
$$
\frac{d}{dx}{(\tan{x})}=\sec^2{x} \hspace{2cm} \frac{d}{dx}{(\cot{x})}=-\csc^2{x}
$$

### ***The Chain Rule***
If $f$ and $g$ are both differentiable and $F=f \circ g$ is the composite functino defined by $F(x)=f(g(x))$, then $F$ is differentiable and $F'$ is given by the product
$$
F'(x)=f'(g(x))g'(x)
$$
In Leibniz notation, if $y=f(u)$ and $u=g(x)$ are both differentiable functions, then
$$
\frac{dy}{dx}=\frac{dy}{du} \frac{du}{dx}
$$

***Power Rule combined with the Chain Rule***
If $n$ is any real number and $u=g(x)$ is differentiable, then
$$
\frac{d}{dx}(u^n)=nu^{n-1}\frac{du}{dx}
$$
Alternatively,
$$
\frac{d}{dx}[g(x)]^n=n[g(x)]^{n-1} \cdot g'(x)
$$

---
### ***Implicit Differentiation***
Most of the functions that we've come across can be described by expressing one variable explicitly in terms of another, example:
$$
y=x \sin{x}
$$
Some functions, however, are defined implicitly by a relation between $x$ and $y$ such as:
$$
x^2+y^2=25
$$
or
$$
x^3+y^3=6xy
$$

**Implicit Differentiation.** Differentiating both sides of the equation with respect to $x$ and then solving the resulting equation for $y'$

Example: $x^2+y^2=25$
$$
\begin{align}
\frac{d}{dx}(x^2+y^2) &= \frac{d}{dx}(25) \\
\frac{d}{dx}(x^2)+\frac{d}{dx}(y^2) &= 0
\end{align}
$$
Remember that $y$ is a function of $x$ and using the Chain Rule, we have
$$
\frac{d}{dx}(y^2)=2y\frac{dy}{dx}
$$
Thus,
$$
2x+2y\frac{dy}{dx}=0
$$
Now we solve this equation for $dy/dx$:
$$
\frac{dy}{dx}=-\frac{x}{y}
$$

---
### ***Derivatives of Logarithmic Functions***

$$
\frac{d}{dx}(log_ax)=\frac{1}{x\ln{a}}
$$
$$
\frac{d}{dx}(\ln{x})=\frac{1}{x}
$$
$$
\frac{d}{dx}(\ln{u})=\frac{1}{u}\frac{du}{dx} \hspace{1cm} or \hspace{1cm}
\frac{d}{dx}[\ln{g(x)}] = \frac{g'(x)}{g(x)}
$$
