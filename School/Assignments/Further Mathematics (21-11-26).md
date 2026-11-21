---
Subject: Further Mathematics
Date: 2026-11-21
Purpose: Assignment
---
The following table gives the corresponding values of two variables $h$ and $t$.

$$
\begin{array}{|c||*{5}{c|}}
\hline
h & 2 & 3 & 4 & 5 & 6
\\ \hline
t & 6.4 & 32.4 & 102.4 & 250 & 518.4
\\ \hline
\end{array}
$$

If the relation between $h$ and $t$ is of the form $t = kh^n$ where $k$ and $n$ are constants.

1. Graphically determine the values of $k$ and $n$.
2. Use the graph to estimate to 1 decimal place the value of $t$ when $h = 4.5$.

# Solution

$$
t = kh^n
$$
$$
\text{Take the logarithm (base 10) of both sides}
$$
$$
\log t = \log kh^n
$$
$$
\log t = \log k + \log h^n
$$
$$
\log t = \log k + n \log h
$$
$$
\log t = n \log h + \log k
$$
$$
\text{Compare with the equation $y = mx + c$}
$$
$$
\begin{array}{*{6}{c}}
y & = & m & x & + & c
\\
\Bigg\updownarrow & & \Bigg\updownarrow & \Bigg\updownarrow & & \Bigg\updownarrow
\\
\log t & = & n & \log h & + & \log k
\end{array}
$$


$$
\begin{aligned}
\text{$y$ intercept} &= \log k
\\
\text{Gradient} &= \log n
\\
\text{Plot} &= \log t \ \text{against} \ \log h
\end{aligned}
$$
$$
\begin{array}{|c||*{5}{c|}}
\hline
\log h & 0.301 & 0.477 & 0.602 & 0.699 & 0.778
\\ \hline
\log t & 0.806 & 1.511 & 2.010 & 2.398 & 2.715
\\ \hline
\end{array}
$$

im too lazy to make a graph so im not doing it graphically, instead im using slope formula

$$
\text{Using}
\\
\begin{array}{cc}
x_1 = 0.477 & x_2 = 0.778
\\
y_1 = 1.511 & y_2 = 2.715
\end{array}
$$
$$
n = \frac{2.715 - 1.511}{0.778 - 0.477}
$$
$$
n = \frac{1.204}{0.301}
$$
$$
\boxed{n = 4}
$$
$$
\log t = 4 \log h + \log k
$$
$$
\text{Using}
\\
\begin{aligned}
\log h &= 0.477
\\
\log t &= 1.511
\end{aligned}
$$
$$
1.511 = 4 \times 0.477 + \log k
$$
$$
1.511 = 1.908 + \log k
$$
$$
1.511 - 1.908 = \log k
$$
$$
-0.397 = \log k
$$
$$
10^{-0.397} = \cancel{10}^{\cancel{\log} k}
$$
$$
0.401 = k
$$
$$
\boxed{k = 0.401}
$$
$$
\therefore \log t = 4 \log h + \log 0.401
$$
$$
\log t =\log 0.401 h^4
$$
$$
\boxed{t = 0.401 h^4}
$$
$$
\text{Given $h = 4.5$}
$$

$$
t = 0.401 \times 410.0625
$$
$$
t = 164.4350625
$$
$$
\boxed{t \approx 164.4}
$$
$$
\therefore \text{When $h = 4.5$, $t \approx 164.4 $}
$$
