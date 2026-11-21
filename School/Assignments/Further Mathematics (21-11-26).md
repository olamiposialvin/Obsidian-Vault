---
Subject: Further Mathematics
Date: 2026-11-21
Purpose: Assignment
---
The following table gives the corresponding values of two variables $h$ and $t$.

$$
\begin{array}{|c|c|}
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
\begin{array}{c}
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
\begin{array}{|c|c|c|c|c|c|}
\hline
\log h & 0.3 & \overset{\smash{\raise{1em}{x_1}}}{0.5} & 0.6 & \overset{\smash{\raise{1em}{x_2}}}{0.7} & 0.8
\\ \hline
\log t & 0.8 & \overset{\smash{\lower{3em}{y_1}}}{1.5} & 2.0 & \overset{\smash{\lower{3em}{y_2}}}{2.4} & 2.7
\\ \hline
\end{array}
$$

im too lazy to make a graph so im not doing it graphically, instead im using slope formula

$$
\text{Slope} \ n = \frac{y_2 - y_1}{x_2 - x_1}
$$
$$
n = \frac{2.4 - 1.5}{0.7 - 0.5}
$$
$$
n = \frac{0.9}{0.2}
$$
$$
\boxed{n = \frac{9}{2} = 4.5}
$$
$$
\log t = \frac{9}{2} \log h + \log k
$$
$$
1.5 = \frac{9}{2} \times 0.5 + \log k
$$
$$
\frac{3}{2} = \frac{9}{4} + \log k
$$
$$
\frac{3}{2} - \frac{9}{4} = \log k
$$
$$
10^{\frac{6 - 9}{4}} = \cancel{10}^{\cancel{\log} k}
$$
$$
10^{\frac{-3}{4}} = k
$$
$$
\boxed{k \approx 0.18}
$$
$$
$$

