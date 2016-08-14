Title: Sequences
Slug: sequences
Date: 2016-08-13

$\newcommand{\red}[1]{\color{red}{\text{#1}}}$


#### Sequences: definitions & theorems

(1) $\red{Basic limit definition}$: $\lim_{n \to \infty} a_n = L$, aka  $a_n \to L$ as $n \to \infty$
   A sequence has a limit if $a_n$ approaches limit $L$ as $n$ increases. If a limit exists, the sequence is convergent; else, divergent.

(2) $\red{Rigorous definition w/interval}$: A limit exists for a sequence if, as $\lim_{n \to \infty}$, for an interval $\varepsilon \pm L$, an $N$ exists for which all subsequent values of $a_n$ are within $|\varepsilon - L|$

(3) Theorem w/ $n$ as an integer: $\lim_{n \to \infty} f(x) = L$ and $f(n) = a_n$ when $n$ is an integer, $\lim_{n \to \infty} a_n = L$ [$\red{If you know a continuous function that goes through the points and it has a limit, then just use that limit}$]

(4) Fractions with $(\text{denominator})^n$:$lim_{n \to \infty} \frac{1}{n^r} = 0$ if $r > 0$ <- converges to 0

(5) Definition for $lim_{n \to \infty}$ diverges to $\infty$: for every positive number $M$, if $a_n > M$ there is an integer $N$ greater than $n$


For convergent sequences ($c$ is a constant): 

  * $lim_{n \to \infty}(a_n + b_n) = lim_{n \to \infty}(a_n) + lim_{n \to \infty}(b_n)$
  * $lim_{n \to \infty}(a_n - b_n) = lim_{n \to \infty}(a_n) - lim_{n \to \infty}(b_n)$
  * $lim_{n \to \infty} ca_n = c lim_{n \to \infty}a_n$, $lim_{n \to \infty} c = c$
  * $lim_{n \to \infty}(a_n b_n) = lim_{n \to \infty} a_n * lim_{n \to \infty} b_n$
  * $lim_{n \to \infty} \frac{a_n}{b_n} = \frac{lim_{n \to \infty} a_n}{lim_{n \to \infty} b_n}$ if $lim_{n \to \infty} b_n \neq 0$
  * $lim_{n \to \infty}a_n^p = [lim_{n \to \infty} a_n]^p$ if $p > 0$ and $a_n > 0$

[$\red{Limit of some-series-combined-using-some-operations is the same operations applied to the individual series' limits}$]

$\red{Squeeze Theorem adaptation}$: if $a_n \le b_n \le c_n$ for $n \ge n_0$ and $lim_{n \to \infty} a_n = lim_{n \to \infty} c_n = L$, then $lim_{n \to \infty} b_n = L$

(6) $\red{Absolute value theorem}$: if $lim_{n \to \infty} |a_n| = 0$, then $lim_{n \to \infty} a_n = 0$

(7) If we apply a continuous function to a convergent sequence, the result is convergent: if $lim_{n \to \infty} a_n = L$ and $f$ is continuous at $L$, then $f(a_n) = f(L)$ [$\red{Limit of some function of a series is: the function applied to the series' limit}$]

(8) for $a_n = \frac{n!}{n^n}$: $a_n = \frac{1}{n}(\frac{2*3*...*n}{n*n*...*n})$; numerator is $\le$ denominator, so $0 \lt a_n \le \frac{1}{n}$; $\frac{1}{n} \to 0$ as $n \to \infty$

(9) for $a_n = r^n$: $\{r^n\}$ is convergent if $-1 < r \le 1$ and divergent for all other values of $r$; $lim_{n \to \infty} r^n = 0$ if $-1 < r < 1$, $1$ if $r = 1$

(10) Definition for increasing/decreasing/monotonic:

  * increasing: $a < a_{n + 1}$ for all $n \ge 1$, aka $a_1 < a_2 < ... < a_n$ 
  * decreasing: $a > a_{n + 1}$ for all $n \ge 1$, aka $a_1 > a_2 > ... > a_n$ 
  * monotonic if increasing or decreasing

(11) Definition for bounded above/bounded below/bounded sequence:

  * bounded above: $M$ exists such that $a_n \le M$, for all $n \ge 1$
  * bounded below: $m$ exists such that $m \le a_n$, for all $n \ge 1$
  * bounded sequence: bounded above & below

(12) Monotonic sequence theorem: every bounded monotonic sequence is convergent.