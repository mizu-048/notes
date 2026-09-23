---
{"dg-publish":true,"permalink":"/notes/z-semester-1/mathematics/calculus/trigonometry/"}
---

Deriving trigonometric functions:
$\dfrac{d}{dx}f(x)=\underset{ \Delta x \to 0 }{\lim} \dfrac{f(x+\Delta x)-f(x)}{\Delta x}$

$\dfrac{d}{dx}f(x)=\dfrac{f(x)-f(a)}{x-a}$
>[!question]- how is $\dfrac{d}{dx}\sin x=\cos x$ 
> - $\dfrac{d}{dx}\sin x=\underset{ \Delta x \to 0 }{\lim} \dfrac{\sin(x+\Delta x)-\sin(x)}{\Delta x}$
> - $\dfrac{d}{dx}\sin x=\underset{ \Delta x \to 0 }{\lim}\dfrac{\sin(x)\cos(\Delta x)+\sin (\Delta x) \cos (x)-\sin(x)}{\Delta x}$
> -  $\dfrac{d}{dx}\sin x=\underset{ \Delta x \to 0 }{\lim}\dfrac{[\sin(x)\times(\cos(\Delta x)-1)]}{\Delta x}+ \dfrac{\sin (\Delta x) \cos (x)}{\Delta x}$
> -  $\dfrac{d}{dx}\sin x=\sin(x)\underset{ \Delta x \to 0 }{\lim}\dfrac{[(\cos(\Delta x)-1)]}{\Delta x}+ \cos (x)\underset{ \Delta x \to 0 }{\lim}\dfrac{\sin (\Delta x) }{\Delta x}$
> -  applying limit and L hopital rule or that sin limit thing watever
> -  $\dfrac{d}{dx}\sin x=\sin(x)(0)+ \cos (x)(1)$
> -   $\dfrac{d}{dx}\sin x=\cos (x)$


>[!question]- Explain how $\dfrac{d}{dx}\sin^{-1}(x)=\dfrac{1}{\sqrt{ 1-x^{2} }}$  by definition
> - $y=\sin^{-1}(x);\qquad \sin(y)=x$ 
> -  $\dfrac{d}{dx}\sin(y)=\dfrac{d}{dx}(x)$
> -  $\cos(y)\times \dfrac{dy}{dx} = 1;\qquad \dfrac{dy}{dx}  =\dfrac{1}{\cos(y)}$ 
> -  $\dfrac{dy}{dx} =\dfrac{1}{\sqrt{ (\cos y)^{2} }}=\dfrac{1}{\sqrt{ 1-\sin ^{2}y }}    \because \sin ^{2}x+\cos ^{2}x=1$ 
> -  $\dfrac{dy}{dx} \dfrac{1}{\sqrt{ 1-x }}\qquad     \because y=\sin^{-1}(x)$

>[!question]- Explain how $\dfrac{d}{dx}\sec^{-1}(x)=\dfrac{1}{x\sqrt{ 1-x^{2} }}$  by definition
> - $y=\sec^{-1}(x);\qquad \sec(y)=x$ 
> -  $\dfrac{d}{dx}\sec(y)=\dfrac{d}{dx}(x)$
> -  $\sec(y)\times \tan (y)\times \dfrac{dy}{dx} = 1;\qquad \dfrac{dy}{dx}  =\dfrac{1}{\sec(y)\times \tan (y)}$ 
> -  $\dfrac{dy}{dx} =\dfrac{1}{\sec(y) \times \sqrt{ (\tan (y)^{2} }}=\dfrac{1}{\sec(y) \times\sqrt{ 1-\sec ^{2}y }}    \because \sec ^{2}x=1+\tan ^{2}x$ 
> -  $\dfrac{dy}{dx} \dfrac{1}{x\sqrt{ 1-x }}\qquad     \because y=\sec^{-1}(x)$

Euler formula: 
- $re^{i\theta} = r(Cos\theta + iSin\theta)$
- $re^{-i\theta} = r(Cos\theta - iSin\theta)$
by adding and subtracting these two
$\cos \theta=\dfrac{e^{i \theta}+e^{-i \theta}}{2};\qquad \sin \theta=\dfrac{e^{i \theta}-e^{-i \theta}}{2}$
and
$\cosh \theta=\dfrac{e^{ \theta}+e^{- \theta}}{2};\qquad \sinh \theta=\dfrac{e^{ \theta}-e^{- \theta}}{2}$

>[!question]- derive $\sinh ^{-1}(x)=\ln(x+\sqrt{ x^{2}+1 })$ 
> - $y=\sinh^{-1}(x);\qquad \sinh(y)=x$
> - $\dfrac{e^{y}-e^{-y}}{2}=x;\qquad (e^{y}-\dfrac{1}{e^{y}})=2x$
> - $(e^{2y}-1)=2e^{y};\qquad e^{2y}-2xe^{y}-1=0$
> - now apply the quadratic formula
> - $e^{y}=\dfrac{-(-2x)\pm \sqrt{ (-2x)^{2} \ - 4(1)(1) }}{2(1)}$
> - $e^{y}=\dfrac{2x\pm \sqrt{ 4(x^{2} - 1) }}{2}=\dfrac{2x\pm 2\sqrt{ (x^{2} - 1) }}{2}$
> - $e^{y}=x\pm \sqrt{ (x^{2} - 1) }$
> - taking log on both sides
> - $y \ \ln(e)=\ln(x\pm \sqrt{ (x^{2} - 1) }$
> - $\sinh ^{-1}x=\ln(x\pm \sqrt{ (x^{2} - 1) }$


# derivative
definition of a derivative:
$$
f'(x)=\underset{ h \to 0 }{\lim} \dfrac{f(x+h)-f(x)}{h}
$$


# Definition of derivative 3.1-3.3

>[!question]- 3.1 Q#1 $\qquad5x^{2}-4;\qquad P(2,f(2))$; find slope and equation of tangent line
> - $\dfrac{d}{dx}f(x)=\underset{ h \to 0 }{\lim} \dfrac{f(x+\Delta x)-f(x)}{\Delta x}=\dfrac{[5(x+h)^{2}-4(x+h)]-(5x^{2}-4x)}{h}$
> - $\underset{ h \to 0 }{\lim}\dfrac{5x^{2}+5h^{2}+10hx-4x-4h-5x^{2}+4x}{h}=\underset{ h \to 0 }{\lim}\dfrac{h(5h+10x-4)}{h}=\underset{ h \to 0 }{\lim}(5h+10x-4)$
> - apply limit: $5(0)+10x-4$
> - $f'(x)=10x-4;\qquad f'(2)=20-4=16$
> - $f(2)=5(4)-4(2)=12$
> - now for equation of tangent line: $(y-y_{1})=m_{2}(x-x_{1})$
> - $y-12=16(x-2);\qquad y=16x-20$
>   
>     
> 
> 
> 


# continuity
[vid](https://www.youtube.com/watch?v=nRv1lPqrx3k)

- Conditions for continuity at $a$:
	- $f(a)$ is defined
	- $\underset{ x \to a }{\lim}f(x)$ exists
		- a thing to note is that $\underset{ x \to a }{\lim} f(x)$ only exists if $\underset{ x \to a^{+} }{\lim} f(x)=\underset{ x \to a^{-} }{\lim} f(x)$ 
	- $\underset{ x \to a }{\lim}f(x)=f(a)$
[vid](https://www.youtube.com/watch?v=EDOI2S171TI)

- to be continuous on an closed interval $[a,b]$ a function $f(x)$
	- $\underset{ x \to c }{\lim}f(x)=f(c)$
	- $\underset{ x \to a^{+} }{\lim}f(x)=f(a)$
	- $\underset{ x \to b^{-} }{\lim}f(x)=f(b)$