---
{"dg-publish":true,"permalink":"/notes/z-semester-1/mathematics/calculus/convergences-and-divergence/"}
---

![MORE SUMMARY.jpg|500](/img/user/Notes/zSemester%201/Mathematics/Calculus/attachments/MORE%20SUMMARY.jpg)

![another summary.png|500](/img/user/Notes/zSemester%201/Mathematics/Calculus/attachments/another%20summary.png)

![strategy for convergence test.png|500](/img/user/Notes/zSemester%201/Mathematics/Calculus/attachments/strategy%20for%20convergence%20test.png)

![convergence test summaries.png|500](/img/user/Notes/zSemester%201/Mathematics/Calculus/attachments/convergence%20test%20summaries.png)

# Sequence

- a function and its domain is all integers $n \in N$
	- $f:N\to R$
	- $\{a_{n}\}=\{1+\dfrac{1}{n}\}$
	- $a_{n}= f(n)$
- Convergent: if as $\underset{ n \to \infty }{\lim} a_{n} =1$ e.g. $f(n)=1+\dfrac{1}{n}$
- Divergent: if as $\underset{ n \to \infty }{\lim} a_{n} =D.N.E$ or oscillates or whateverbaljd aowd jaw



- $\underset{ n \to \infty }{\lim} r^{n}=0;\qquad|r|<1\qquad$ it will  be ==convergent==
	- $e.g. \ a_{n}=\{(-\dfrac{2}{3})^{n}\}^{\infty}_{n=1}$
- $\underset{ n \to \infty }{\lim} r^{n}=\infty;\qquad|r|> 1\qquad$ it will  be ==divergent==
	- $e.g. \ a_{n}=\{(-\dfrac{3}{2})^{n}\}^{\infty}_{n=1}$
- some convergent functions
	- $a_{n}=\{1\}^{\infty}_{n=1}$
	- $a_{n}=\{1^{n}\}^{\infty}_{n=1}$
	- $a_{n}=\{\}^{\infty}_{n=1}$
	- $a_{n}=\{\}^{\infty}_{n=1}$
- some divergent functions
	- $a_{n}=\{-1\}^{\infty}_{n=1}$, it oscillates between 1 and -1 so its divergent
- 
# Series
- An infinte series is of the form:  $\substack{{_{\infty}} \\ {\sum} \\{_{n=1}}} a_{n}=a_{1}+a_{2}+a_{3}\dots +a_{n}$
## Partial Sum
- an example sequence is $a_{n}=\dfrac{1}{n(n+1)}$
- $S_{1}=a_{1}=\dfrac{1}{2}$  
- $S_{2}=a_{1}+a_{2}=\dfrac{1}{2}+\dfrac{1}{2\times3}=\dfrac{2}{3 }$  
- $S_{3}=a_{1}+a_{2}+a_{3}=\dfrac{2}{3}+\dfrac{1}{12}$ 
- 
- $S_{n}= \ ?$
- partial fraction  = $\dfrac{A}{n}+\dfrac{B}{n+1}$ solving the partial fraction we get
- $=\dfrac{1}{n}-\dfrac{1}{n+1 }$
- now trying $S_{n}$
- $S_{n}=a_{1}+a_{2}+a_{3}\dots+a_{n}$  



##  Alternating Series:


# Practice
- [alternating, ratio and root](https://web.ma.utexas.edu/users/m408s/CurrentWeb/LM11-7-4.php)
- [idk](https://web.ma.utexas.edu/users/m408s/CurrentWeb/LM11-7-3.php)
- [bprp ratio and root](https://www.youtube.com/watch?v=SMPllC79KHY)
# TIPS

> [!NOTE]- images
> 
> ![cheatsheet_convergence_tests.png|700|500](/img/user/Notes/zSemester%201/Mathematics/Calculus/attachments/cheatsheet_convergence_tests.png)
> 
> ![convergence_test_order_tip.png|800|500](/img/user/Notes/zSemester%201/Mathematics/Calculus/attachments/convergence_test_order_tip.png)

- for things to the power of $n$ use root test
- for things involving factorials, use ratio test
- ==IMP== $(1+\dfrac{a}{n})^{bn}=e^{ab}$
	- solve $\substack{{_{\infty}} \\ {\sum} \\{_{n=1}}} \dfrac{n!}{n^{n}}$; sol in bprp ratio/root test video at 18:30
- 