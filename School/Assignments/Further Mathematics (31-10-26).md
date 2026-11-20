---
Subject: Further Mathematics
Date: 2026-10-31
Purpose: Assignment
---

# Instructions (Project)

1. Students are to form groups of $\textbf{five } \mathbf{(5)}$ members.
2. Each group is expected to work collaboratively to solve all the assigned questions.
3. Every member must participate actively in the research, calculations, discussion and preparation of the project.
4. Each group must prepare a well-organised written solution to all the questions.
5. Each group shall nominate ONE member to represent the group and present its solutions physically in the classroom upon resumption.
6. The nominated presenter must demonstrate a clear understanding of the methods used and be able to explain the steps involved in solving the questions.
7. Other group members may be asked questions during the presentation.
8. All calculations, diagrams and mathematical explanations must be clearly presented.

<div style="break-after: page;"></div>

# Questions

## 1. Area of a Triangle using Coordinates

The vertices of a triangle are $A(2, 3)$, $B(6, 7)$ and $C(8, 2)$.

1. Calculate the lengths of $AB$, $BC$ and $AC$ using the distance formula.
	$$
	\text{
	Distance Formula: $\sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2}$
	\\ Given points $A(x_1, y_1)$ and $B(x_2, y_2)$}
	$$
	<span><br></span>
	$$
	\textbf{\LARGE Line $\boldsymbol{AB}$}
	$$
	$$
	\text{Given $A(x_1, y_1)$ and $B(x_2, y_2)$}
	\\
	x_1 = 2 \qquad	y_1 = 3
	\\
	x_2 = 6 \qquad	y_2 = 7
	$$
	$$
	AB = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2}
	$$
	$$
	AB = \sqrt{(6 - 2)^2 + (7 - 3)^2}
	$$
	$$
	AB = \sqrt{(4)^2 + (4)^2}
	$$
	$$
	AB = \sqrt{2 \cdot (4)^2}
	$$
	$$
	AB = \sqrt{2} \cdot \sqrt{(4)^2}
	$$
	$$
	AB = \sqrt{2} \cdot \sqrt{4^2}
	$$
	$$
	AB = \sqrt{2} \cdot 4
	$$
	$$
	\boxed{ AB = 4 \sqrt{2} \text{ units} }
	$$
	<span><br></span>
	$$
	\textbf{\LARGE Line $\boldsymbol{BC}$}
	$$
	$$
	\text{Given $B(x_1, y_1)$ and $C(x_2, y_2)$}
	\\
	x_1 = 6 \qquad	y_1 = 7
	\\
	x_2 = 8 \qquad	y_2 = 2
	$$
	$$
	BC = \sqrt{(8 - 6)^2 + (2 - 7)^2}
	$$
	$$
	BC = \sqrt{(2)^2 + (-5)^2}
	\\[4pt] \text{\footnotesize Note that $(-x)^2 = x^2$, but $-(x)^2 \ne x^2$}
	$$
	$$
	BC = \sqrt{4 + 25}
	$$
	$$
	\boxed{BC = \sqrt{29} \text{ units}}
	$$
	<span><br></span>
	$$
	\textbf{\LARGE Line $\boldsymbol{AC}$}
	$$
	$$
	\text{Given $A(x_1, y_1)$ and $C(x_2, y_2)$}
	\\
	x_1 = 2 \qquad	y_1 = 3
	\\
	x_2 = 8 \qquad	y_2 = 2
	$$
	$$
	AC = \sqrt{(8 - 2)^2 + (2 - 3)^2}
	$$
	$$
	AC = \sqrt{(6)^2 + (-1)^2}
	$$
	$$
	AC = \sqrt{36 + 1}
	$$
	$$
	\boxed{AC = \sqrt{37} \text{ units}}
	$$
	<span><br></span>
	$$
	\text{From the calculations}
	\\ \boxed{
	    |AB| = 4\sqrt{2} \text{ units}
	\\  |BC| = \sqrt{29} \text{ units}
	\\  |AC| = \sqrt{37} \text{ units}
	}
	$$
	<span><br></span>
2. Hence, calculate the area of triangle $ABC$ using the coordinate area formula.
	$$
	\text{Coordinate Area Formula: $
	\frac
	{\left| x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2) \right|}
	{2}
	$}
	\\[8pt] \text{Given $A(x_1, y_1)$, $B(x_2, y_2)$, and $C(x_3, y_3)$}
	$$
	<span><br></span>
	$$
	\textbf{\LARGE Triangle $\boldsymbol{ABC}$}
	$$
	$$
	\text{Given $A(x_1, y_1)$, $B(x_2, y_2)$, and $C(x_3, y_3)$}
	\\
	x_1 = 2 \qquad	y_1 = 3
	\\
	x_2 = 6 \qquad	y_2 = 7
	\\
	x_3 = 8 \qquad	y_3 = 2
	$$
	$$
	A_{ABC} = \frac{
	\left| x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2) \right|
	}{
	2
	}
	$$
	$$
	A_{ABC} = \frac{
	\left| 2(7 - 2) + 6(2 - 3) + 8(3 - 7) \right|
	}{
	2
	}
	$$
	$$
	A_{ABC} = \frac{
	\left| 2(5) + 6(-1) + 8(-4) \right|
	}{
	2
	}
	$$
	$$
	A_{ABC} = \frac{
	\left| 10 - 6 - 32 \right|
	}{
	2
	}
	$$
	$$
	A_{ABC} = \frac{
	\left| -28 \right|
	}{
	2
	}
	$$
	$$
	A_{ABC} = \frac{28}{2}
	$$
	$$
	\boxed{A_{ABC} = 14 \text{ units$^2$}}
	$$

<div style="break-after: page;"></div>

## 2. Area of a Triangle using the Determinant Method

Given the points $P(1, 2)$, $Q(5, 4)$ and $R(3, 8)$:

1. State the formula for calculating the area of a triangle when the coordinates of its three vertices are given.
	$$
	\text{Determinant Area Formula: } \frac{1}{2}
	\begin{vmatrix}
	x_1 & y_1 & 1
	\\
	x_2 & y_2 & 1
	\\
	x_3 & y_3 & 1
	\end{vmatrix}
	\\[8pt] \text{Given $A(x_1, y_1)$, $B(x_2, y_2)$, and $C(x_3, y_3)$}
	$$
	
2. Use the formula to calculate the area of triangle $PQR$.
	$$
	\text{Given $P(x_1, y_1)$, $Q(x_2, y_2)$, and $R(x_3, y_3)$}
	\\
	x_1 = 1 \qquad	y_1 = 2
	\\
	x_2 = 5 \qquad	y_2 = 4
	\\
	x_3 = 3 \qquad	y_3 = 8
	$$
	$$
	A_{PQR} = \frac{1}{2} \begin{vmatrix}
	x_1 & y_1 & 1
	\\
	x_2 & y_2 & 1
	\\
	x_3 & y_3 & 1
	\end{vmatrix}
	$$
	$$
	A_{PQR} = \frac{1}{2}\begin{vmatrix}
	1 & 2 & 1
	\\
	5 & 4 & 1
	\\
	3 & 8 & 1
	\end{vmatrix}
	$$
	$$
	\text{
	To find the determinant of a 3$\times$3 matrix:
	\\
	Go through every number on the top row, for each of them:
	\\
	Cross out its row and column
	\\
	Turn the remaining numbers into a 2$\times$2 matrix
	\\
	Multiply that number with the 2$\times$2 matrix's determinant
	\\
	Look at the following matrix:
	}
	\\[8pt]
	\begin{pmatrix}
	+ & - & +
	\\ - & + & -
	\\ + & - & +
	\end{pmatrix}
	\\[8pt]
	\text{
	It is made with a checkerboard pattern with the top left being +
	\\
	Multiply the number with $\pm1$ based on the sign in its position
	\\
	Add the three results together
	}
	\\[12pt]
	\text{\footnotesize The determinant of a 2$\times$2 matrix of the form $\small\begin{vmatrix}a & b \\ c & d	\end{vmatrix}$ is $ad - bc$}
	$$
	$$
	A_{PQR} = \frac{1}{2} \Biggl[
	+ 1 \begin{vmatrix} 4 & 1 \\ 8 & 1 \end{vmatrix}
	- 2 \begin{vmatrix} 5 & 1 \\ 3 & 1 \end{vmatrix}
	+ 1 \begin{vmatrix} 5 & 4 \\ 3 & 8 \end{vmatrix}
	\Biggr]
	$$
	$$
	A_{PQR} = \frac{1}{2} \Big[
	+ 1 (4 \cdot 1 - 1 \cdot 8)
	- 2 (5 \cdot 1 - 1 \cdot 3)
	+ 1 (5 \cdot 8 - 3 \cdot 4)
	\Big]
	$$
	$$
	A_{PQR} = \frac{1}{2} \Big[
	+ 1 (4 - 8)
	- 2 (5 - 3)
	+ 1 (40 - 12)
	\Big]
	$$
	$$
	A_{PQR} = \frac{1}{2} \Big[
	+ 1 (-4)
	- 2 (2)
	+ 1 (28)
	\Big]
	$$
	$$
	A_{PQR} = \frac{1}{2} \Big[
	- 4
	- 4
	+ 28
	\Big]
	$$
	$$
	A_{PQR} = \frac{1}{2} \times 20
	$$
	$$
	A_{PQR} = 10
	$$

<div style="break-after: page;"></div>

## 3. Collinearity of Three Points

Given the points $A(1, 2)$, $B(3, 6)$ and $C(5, 10)$:

1. Calculate the area of triangle $ABC$ using the coordinate area formula.
	$$
	\text{Given $A(x_1, y_1)$, $B(x_2, y_2)$, and $C(x_3, y_3)$}
	\\
	\begin{array}{cc}
	x_1 = 1 &	y_1 = 2
	\\
	x_2 = 3 &	y_2 = 6
	\\
	x_3 = 5 &	y_3 = 10
	\end{array}
	$$
	$$
	A_{ABC} = \frac{
	\left| x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2) \right|
	}{
	2
	}
	$$
	$$
	A_{ABC} = \frac{
	\left| 1(6 - 10) + 3(10 - 2) + 5(2 - 6) \right|
	}{
	2
	}
	$$
	$$
	A_{ABC} = \frac{
	\left| 1(-4) + 3(8) + 5(-4) \right|
	}{
	2
	}
	$$
	$$
	A_{ABC} = \frac{
	\left| -4 + 24 - 20 \right|
	}{
	2
	}
	$$
	$$
	A_{ABC} = \frac{
	\left| 0 \right|
	}{
	2
	}
	$$
	$$
	A_{ABC} = \frac{0}{2}
	$$
	$$
	A_{ABC} = 0
	$$
2. What conclusion can you draw about the three points? Give a reason for your answer.
	$$
	\text{
	The three points cannot form a triangle
	\\
	because they all lie on a single straight line
	\\
	i.e. they are \textbf{collinear}
	}
	$$

<div style="break-after: page;"></div>

## 4. Area of a Triangle with Unknown Coordinates (Incorrect Question)

The coordinates of three vertices of a triangle are $A(1, 2)$, $B(5, 2)$, and $C(k, 6)$. If the area of triangle $ABC$ is 12 square units:

1. Calculate the possible value(s) of $k$.
	$$
	\text{Given $A(x_1, y_1)$, $B(x_2, y_2)$, and $C(x_3, y_3)$}
	\\
	\begin{array}{cc}
	x_1 = 1 &	y_1 = 2
	\\
	x_2 = 5 &	y_2 = 2
	\\
	x_3 = k &	y_3 = 6
	\end{array}
	$$
	$$
	A_{ABC} = \frac{1}{2} \left|
	x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2)
	\right|
	$$
	$$
	12 = \frac{1}{2} \left|
	1(2 - 6) + 5(6 - 2) + k(2 - 2)
	\right|
	$$
	$$
	12 = \frac{1}{2} \left|
	1(-4) + 5(4) + k(0)
	\right|
	$$
	$$
	12 = \frac{1}{2} \left|
	-4 + 20 + 0k
	\right|
	$$
	$$
	12 = \frac{1}{2} \left|
	16 + \cancel{0k}
	\right|
	$$
	$$
	\text{\footnotesize Notice that $k$ is irrelevant in the inequation because its coefficient is 0}
	$$
	$$
	12 = \frac{1}{2} \left|
	16
	\right|
	$$
	$$
	12 = \frac{1}{2} \times 16
	$$
	$$
	12 \ne 8
	$$
	$$
	\therefore \text{There is no number $k$ such that $A_{ABC} = 12$ square inits}
	$$
2. Explain why there may be more than one possible value of $k$.
	$$\text{
	There are 0 values of $k$
	\\
	this is because no value can satisfy $A_{ABC} = 12$.
	}$$

<div style="break-after: page;"></div>

## 5. Application of Coordinate Geometry

The points $A(2, 1)$, $B(8, 1)$, and $C(5, 7)$ represent the vertices of a triangular piece of land.

1. Calculate the perpendicular height of the triangle from $C$ to $AB$.
	$$
	\text{Given $A(x_1, y_1)$, $B(x_2, y_2)$, and $C(x_3, y_3)$}
	\\
	\begin{array}{cc}
	x_1 = 2 &	y_1 = 1
	\\
	x_2 = 8 &	y_2 = 1
	\\
	x_3 = 5 &	y_3 = 7
	\end{array}
	$$
	$$
	A_{ABC} = \frac{1}{2} \text{base $\times$ height}
	$$
	$$
	\text{Using $AB$ as the base}
	$$
	$$
	A_{ABC} = \frac{1}{2} AB \times \text{height} 
	$$
	$$
	\text{height} = \frac{2 A_{ABC}}{AB}
	$$
	$$
	\text{height} = \frac{
	\left| x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2) \right|
	}{
	\sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2}
	}
	$$
	$$
	\text{height} = \frac{
	\left| 2(1 - 7) + 8(7 - 1) + \cancel{5(1 - 1)} \right|
	}{
	\sqrt{(8 - 2)^2 + \cancel{(1 - 1)^2}}
	}
	$$
	$$
	\text{height} = \frac{
	\left| 2(-6) + 8(6) \right|
	}{
	\mathrlap{\bcancel{\sqrt{\vphantom{(^{\bcancel{2}})}}}}\kern0.265em{\sqrt{(8-2)^{\bcancel{2}}}}
	}
	$$
	$$
	\text{height} = \frac{
	\left| -12 + 48 \right|
	}{
	(8 - 2)
	}
	$$
	$$
	\text{height} = \frac{
	\left| 36 \right|
	}{
	6
	}
	$$
	$$
	\text{height} = \frac{36}{6}
	$$
	$$
	\boxed{\text{height} = 6 \, \text{units}}
	$$
2. Calculate the area of the triangular piece of land.
	$$
	A_{ABC} = \frac{1}{2}\left| x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2) \right|
	$$
	$$
	A_{ABC} = \frac{1}{2} \left| 2(1 - 7) + 8(7 - 1) + \cancel{5(1 - 1)} \right|
	$$
	$$
	A_{ABC} = \frac{1}{2} \left| 2(-6) + 8(6) \right|
	$$
	$$
	A_{ABC} = \frac{1}{2} \left| -12 + 48 \right|
	$$
	$$
	A_{ABC} = \frac{1}{2} \left| 36 \right|
	$$
	$$
	A_{ABC} = \frac{1}{2} \times 36
	$$
	$$
	\boxed{A_{ABC} = 18 \, \text{units}^2}
	$$
3. If the land is to be covered with grass at a cost of ₦500 per square unit, calculate the total cost of covering the land.
	$$
	\begin{array}{ccc}
	1 \, \text{unit}^2 & = & \text{₦500}
	\\
	\llap{\scriptstyle \times 18} \Bigg\downarrow & & \Bigg\downarrow \rlap{\scriptstyle \times 18}
	\\
	18 \, \text{units}^2 & = & \text{₦}x
	\end{array}
	$$
	$$
	\text{₦}x = 18 \times \text{₦}500
	$$
	$$
	\boxed{\text{₦}x = \text{₦}9000}
	$$
	$$
	\therefore \text{The total cost of covering the land is \textbf{₦9,000}.}
	$$

<div style="break-after: page;"></div>

# Extra
## Modified Question 4

The coordinates of three vertices of a triangle are $A(1, 2)$, $B(5, 2)$, and $\mathbf{C(6, k)}$. If the area of triangle $ABC$ is 12 square units:

1. Calculate the possible value(s) of $k$.
	$$
	\text{Given $A(x_1, y_1)$, $B(x_2, y_2)$, and $C(x_3, y_3)$}
	\\
	\begin{array}{cc}
	x_1 = 1 &	y_1 = 2
	\\
	x_2 = 5 &	y_2 = 2
	\\
	x_3 = 6 &	y_3 = k
	\end{array}
	$$
	$$
	A_{ABC} = \frac{1}{2} \left|
	x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2)
	\right|
	$$
	$$
	12 = \frac{1}{2} \left|
	1(2 - k) + 5(k - 2) + 6(2 - 2)
	\right|
	$$
	$$
	12 = \frac{1}{2} \left|
	1(2 - k) + 5 \cdot (k - 2) \cdot (-1)^2 + \cancel{6(0)}
	\right|
	$$
	$$
	12 = \frac{1}{2} \left|
	1(2 - k) + (-1)(5) \cdot (-1)(k - 2)
	\right|
	$$
	$$
	12 = \frac{1}{2} \left|
	1(2 - k) + (-5) \cdot(-k + 2)
	\right|
	$$
	$$
	12 = \frac{1}{2} \left|
	1(2 - k) -5(2 - k)
	\right|
	$$
	$$
	12 = \frac{1}{2} \left|
	(1 - 5)(2 - k)
	\right|
	$$
	$$
	12 = \frac{1}{2} \left|
	-4(2 - k)
	\right|
	$$
	$$
	12 = \frac{1}{2} \left|
	-8 + 4k
	\right|
	$$
	$$
	24 = \left|
	-8 + 4k
	\right|
	$$
	$$
	24 = \left|
	4k - 8
	\right|
	$$
	$$
	\text{If $|x| = a$, then $x = a$ or $x = -a$}
	$$
	$$
	\begin{array}{cc}
	\text{\textbf{Case 1:} $+$ve} & \text{\textbf{Case 2:} $-$ve}
	\\
	24 = 4k - 8 & -24 = 4k - 8
	\\
	24 + 8 = 4k & -24 + 8 = 4k
	\\
	32 = 4k & -16 = 4k
	\\
	\frac{32}{4} = 4k & \frac{-16}{4} = k
	\\
	\boxed{k = 8} & \boxed{k = -4}
	\end{array}
	$$
2. Explain why there may be more than one possible value of $k$. <br>
	There are two (2) possible values of $k$ because the formula for the area of a triangle uses the **absolute value** to restrict the area into being positive, and the absolute value of **two values** can return the same value.
