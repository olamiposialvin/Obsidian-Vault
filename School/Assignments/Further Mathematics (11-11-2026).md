---
Subject: Further Mathematics
Date: 2026-11-11
Purpose: Assignment
---

$$
\textbf{\huge Preface}
\\[1.2em]
\text{
There is a simpler way to find the area with the Determinant Method
}
\\[1.6em]
\text{
1. Move the whole triangle such that a point $A(x_1, y_1)$ is at the origin
\\
2. Get the location of the new points after the movement
\\
for this example, they will be labeled as follows
}
\\[0.8em]
\begin{array}{r@{\;}c@{\;}l@{\hspace{4.8em}}c}
x_2 & \Longrightarrow & w_2 & w_2 = x_2 - x_1
\\
y_2 & \Longrightarrow & z_2 & z_2 = y_2 - y_1
\\[0.8em]
x_3 & \Longrightarrow & w_3 & w_3 = x_3 - x_1
\\
y_3 & \Longrightarrow & z_3 & z_3 = y_3 - y_1
\end{array}
\\[0.8em]
\text{3. Get the determinant of the matrix: $\begin{pmatrix} w_2 & z_2 \\ w_3 & z_3 \end{pmatrix}$
}
\\
\begin{vmatrix} w_2 & z_2 \\ w_3 & z_3 \end{vmatrix} = w_2 z_3 - z_2 w_3
\\[0.8em]
\text{4. Take the absolute value and halve it to get the actual area:}
\\[1.2em]
\boxed{\frac{1}{2} | w_2 z_3 - z_2 w_3 |}
$$

<div style="break-after: page;"></div>

# Section A: Area of Triangles using the Determinant Method

Calculate the area of each triangle using the determinant method.

1. $A(-2, 1)$, $B(3, 4)$, and $C(4, -2)$.
	$$
	\text{Given $A(x_1, y_1)$, $B(x_2, y_2)$, $C(x_3, y_3)$,
	\\
	$w_2 = x_2 - x_1$, $w_3 = x_3 - x_1$,
	\\
	$z_2 = y_2 - y_1$, and $z_3 = y_3 - y_1$}
	\\[1.2em]
	\begin{array}{cc}
	x_1 = -2 &	y_1 = 1
	\\
	x_2 = 3 &	y_2 = 4
	\\
	x_3 = 4 &	y_3 = -2
	\\[1.2em]
	w_2 = 3 - (-2) = 5 & z_2 = 4 - 1 = 3
	\\
	w_3 = 4 - (-2) = 6 & z_3 = -2 - 1 = -3
	\end{array}
	$$
	$$
	A_{ABC} = \frac{1}{2} | w_2 z_3 - z_2 w_3 |
	$$
	$$
	A_{ABC} = \frac{1}{2} | (5 \times -3) - (3 \times 6) |
	$$
	$$
	A_{ABC} = \frac{1}{2} | -15 - 18 |
	$$
	$$
	A_{ABC} = \frac{1}{2} | -33 |
	$$
	$$
	A_{ABC} = \frac{1}{2} \times 33 
	$$
	$$
	\boxed{A_{ABC} = 16.5 \, \text{square units}}
	$$
	<div style="break-after: page;"></div>
2. The vertices of a triangle are $A(1, 1)$, $B(5, 3)$, and $C(k , 7)$. If its area is $10 \, \text{square units}$, find the possible value(s) of $k$.
	$$
	\text{Given $A(x_1, y_1)$, $B(x_2, y_2)$, $C(x_3, y_3)$,
	\\
	$w_2 = x_2 - x_1$, $w_3 = x_3 - x_1$,
	\\
	$z_2 = y_2 - y_1$, and $z_3 = y_3 - y_1$}
	\\[1.2em]
	\begin{array}{cc}
	x_1 = 1 &	y_1 = 1
	\\
	x_2 = 5 &	y_2 = 3
	\\
	x_3 = k &	y_3 = 7
	\\[1.2em]
	w_2 = 5 - 1 = 4 & z_2 = 3 - 1 = 2
	\\
	w_3 = k - 1 & z_3 = 7 - 1 = 6
	\end{array}
	$$
	$$
	10 = \frac{1}{2} | (4 \times 6) - 2(k-1) |
	$$
	$$
	10 = \frac{1}{2} | 24 - 2k + 2 |
	$$
	$$
	20 = | 26 - 2k |
	$$
	$$
	20 = | 2(13 - k) |
	$$
	$$
	\text{If $|x| = a$, then $x = a$ or $x = -a$}
	$$
	$$
	\begin{array}{cc}
	\text{\textbf{Case 1:} $+$ve} & \text{\textbf{Case 2:} $-$ve}
	\\
	20 = 2(13 - k) & -20 = 2(13 - k)
	\\
	10 = 13 - k & -10 = 13 - k
	\\
	10 + k = 13 & -10 + k = 13
	\\
	k = 13 - 10 & k = 13 + 10
	\\
	\boxed{k = 3} & \boxed{k = 23}
	\end{array}
	$$
	<div style="break-after: page;"></div>
3. A triangle has vertices $A(2, 1)$, $B(6, 5)$, and $C(8, 1)$. Calculate its area and hence determine the length of its base $AC$ and the perpendicular height from $B$ to $AC$.
	$$
	\text{Given $A(x_1, y_1)$, $B(x_2, y_2)$, $C(x_3, y_3)$,
	\\
	$w_2 = x_2 - x_1$, $w_3 = x_3 - x_1$,
	\\
	$z_2 = y_2 - y_1$, and $z_3 = y_3 - y_1$}
	\\[1.2em]
	\begin{array}{cc}
	x_1 = 2 &	y_1 = 1
	\\
	x_2 = 6 &	y_2 = 5
	\\
	x_3 = 8 &	y_3 = 1
	\\[1.2em]
	w_2 = 6 - 2 = 4 & z_2 = 5 - 1 = 4
	\\
	w_3 = 8 - 2 = 6 & z_3 = 1 - 1 = 0
	\end{array}
	$$
	$$
	A_{ABC} = \frac{1}{2} \left| \cancel{4 \times 0} - 4 \times 6 \right|
	$$
	$$
	A_{ABC} = \frac{1}{2} \left| - 24 \right|
	$$
	$$
	A_{ABC} = \frac{1}{2} \times 24
	$$
	$$
	\boxed{A_{ABC} = 12 \, \text{square units}}
	$$
	$$
	AC = \sqrt{(x_3 - x_1)^2 + (y_3 - y_1)^2}
	$$
	$$
	AC = \sqrt{(8 - 2)^2 + \cancel{(1 - 1)^2}}
	$$
	$$
	AC = \mathrlap{\bcancel{\sqrt{\vphantom{(^{\bcancel{2}})}}}}\kern0.265em{\sqrt{(8-2)^{\bcancel{2}}}}
	$$
	$$
	AC = 8 - 2
	$$
	$$
	\boxed{AC = 6 \, \text{units}}
	$$
	$$
	A_{ABC} = \frac{1}{2} \text{base} \times \text{height}
	$$
	$$
	A_{ABC} = \frac{1}{2} AC \times \text{height}
	$$
	$$
	\text{height} = \frac{2A_{ABC}}{AC}
	$$
	$$
	\text{height} = \frac{2(12)}{6}
	$$
	$$
	\text{height} = \frac{24}{6}
	$$
	$$
	\boxed{\text{height} = 4 \, \text{units}}
	$$

<div style="break-after: page;"></div>

# Section B: Collinearity of Points

4. Determine whether the points $A(1, 2)$, $B(3, 6)$, and $C(5, 10)$ are collinear using the determinant method.
	$$
	\text{For three points to be collinear
	\\
	the area of the triangle they make
	\\
	must be equal to 0}
	$$
	$$
	\text{Given $A(x_1, y_1)$, $B(x_2, y_2)$, $C(x_3, y_3)$,
	\\
	$w_2 = x_2 - x_1$, $w_3 = x_3 - x_1$,
	\\
	$z_2 = y_2 - y_1$, $z_3 = y_3 - y_1$,
	\\
	and $A_{ABC} = 0$}
	\\[1.2em]
	\begin{array}{cc}
	x_1 = 1 &	y_1 = 2
	\\
	x_2 = 3 &	y_2 = 6
	\\
	x_3 = 5 &	y_3 = 10
	\\[1.2em]
	w_2 = 3 - 1 = 2 & z_2 = 6 - 2 = 4
	\\
	w_3 = 5 - 1 = 4 & z_3 = 10 - 2 = 8
	\end{array}
	$$
	$$
	0 = \frac{1}{2} | 2 \times 8 - 4 \times 4 |
	$$
	$$
	0 = \frac{1}{2} | 16 - 16 |
	$$
	$$
	0 = \frac{1}{2} | 0 |
	$$
	$$
	0 = \frac{1}{2} \times 0
	$$
	$$
	\boxed{0 = 0}
	$$
	$$
	\text{Since the area is equal to 0} \\ \therefore \text{The points $A(1, 2)$, $B(3, 6)$, and $C(5, 10)$ are collinear.}
	$$
	<div style="break-after: page;"></div>
5. Find the value of $k$ if the points $A(1, 2)$, $B(3, 6)$, and $C(k, 10)$ are collinear.
	$$
	\text{Given $A(x_1, y_1)$, $B(x_2, y_2)$, and $C(x_3, y_3)$}
	\\[1.2em]
	\begin{array}{cc}
	x_1 = 1 &	y_1 = 2
	\\
	x_2 = 3 &	y_2 = 6
	\\
	x_3 = k &	y_3 = 10
	\end{array}
	$$
	$$
	m_{AB} = m_{AC}
	$$
	$$
	\frac{y_2 - y_1}{x_2 - x_1} = \frac{y_3 - y_1}{x_3 - x_1}
	$$
	$$
	\frac{6 - 2}{3 - 1} = \frac{10 - 2}{k - 1}
	$$
	$$
	\frac{4}{2} = \frac{8}{k - 1}
	$$
	$$
	2 = \frac{8}{k - 1}
	$$
	$$
	2(k - 1) = 8
	$$
	$$
	2k - 2 = 8
	$$
	$$
	2k = 10
	$$
	$$
	\boxed{k = 5}
	$$
	<div style="break-after: page;"></div>
6. Given that the points $P(1, 4)$, $Q(3, 8)$, and $R(5, 12)$ are collinear, calculate the gradient of the line passing through the three points.
	$$
	\text{Given $P(x_1, y_1)$, $Q(x_2, y_2)$, and $R(x_3, y_3)$}
	\\[1.2em]
	\begin{array}{cc}
	x_1 = 1 &	y_1 = 4
	\\
	x_2 = 3 &	y_2 = 8
	\\
	x_3 = 5 &	y_3 = 12
	\end{array}
	$$
	$$
	m = \frac{y_2 - y_1}{x_2 - x_1}
	$$
	$$
	m = \frac{8 - 4}{3 - 1}
	$$
	$$
	m = \frac{4}{2}
	$$
	$$
	\boxed{m=2}
	$$

<div style="break-after: page;"></div>

# Section C: Intersection of Straight Lines

7. Find the point of intersection of: $2x + y = 8$ and $x - y = 1$.
	$$
	\text{Add the two equations together}
	$$
	$$
	2x \cancel{+ y} + x \cancel{- y} = 8 + 1
	$$
	$$
	3x = 9
	$$
	$$
	\boxed{x = 3}
	$$
	$$
	x - y = 1
	$$
	$$
	3 - y = 1
	$$
	$$
	3 = 1 + y
	$$
	$$
	y = 3 - 1
	$$
	$$
	\boxed{y = 2}
	$$
	$$
	\therefore \text{The point of intersection is at $(3, 2)$}
	$$
	<div style="break-after: page;"></div>
8. Find the point of intersection of: $3x + 2y = 12$ and $x + y = 5$.
	$$
	\text{Multiply the 2nd equation by $-2$}
	$$
	$$
	-2(x + y) = -2(5)
	$$
	$$
	\boxed{-2x - 2y = -10} \hcline{2.5em} \text{Equation 3}
	$$
	$$
	\text{Add the first and third equation together}
	$$
	$$
	3x + 2y +(-2x - 2y) = 12 + (-10)
	$$
	$$
	3x \cancel{+ 2y} - 2x \cancel{- 2y} = 12 - 10
	$$
	$$
	\boxed{x = 2}
	$$
	$$
	x + y = 5
	$$
	$$
	2 + y = 5
	$$
	$$
	y = 5 - 2
	$$
	$$
	\boxed{y = 3}
	$$
	$$
	\therefore \text{The point of intersection is at $(2, 3)$}
	$$