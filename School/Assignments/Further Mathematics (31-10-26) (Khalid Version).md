## Question 1: Triangle with A(2, 3), B(6, 7), C(8, 2)

**Method:** Find the three sides, use **Heron's formula**, then check with the coordinate area formula.

### Plan
1. Find each side using $d^2 = \Delta x^2 + \Delta y^2$.
2. Put the sides into Heron's formula.
3. Check the area using the coordinate area formula.

### Coordinates

| Label | Point | x | y |
|:--:|:--:|:--:|:--:|
| P₁ | A | 2 | 3 |
| P₂ | B | 6 | 7 |
| P₃ | C | 8 | 2 |

### Working

**Step 1: Side lengths** (name each side after the vertex opposite it)

| Side | Δx | Δy | d² = Δx² + Δy² | d |
|:--:|:--:|:--:|:--:|:--:|
| c = AB | 6 − 2 = 4 | 7 − 3 = 4 | 16 + 16 = 32 | √32 = 4√2 ≈ 5.6569 |
| a = BC | 8 − 6 = 2 | 2 − 7 = −5 | 4 + 25 = 29 | √29 ≈ 5.3852 |
| b = CA | 8 − 2 = 6 | 2 − 3 = −1 | 36 + 1 = 37 | √37 ≈ 6.0828 |

*(Squaring removes the minus sign, so (−5)² = 25.)*

**Step 2: Heron's formula**

$$
s = \frac{a+b+c}{2}, \qquad \text{Area} = \sqrt{s(s-a)(s-b)(s-c)}
$$

$$
\begin{aligned}
s &= \frac{5.3852 + 6.0828 + 5.6569}{2} = \frac{17.1249}{2} \approx 8.5625 \\[4pt]
s-a &\approx 3.1773 \\
s-b &\approx 2.4797 \\
s-c &\approx 2.9056 \\[4pt]
\text{Area} &\approx \sqrt{8.5625 \times 3.1773 \times 2.4797 \times 2.9056} \\
&\approx \sqrt{196.02} \\
&\approx 14.00
\end{aligned}
$$

The sides are surds, so rounding gives a tiny error. Here is the **exact** version, with no rounding.

Write $16 \times \text{Area}^2 = (a+b+c)(a+b-c)\cdot(c+a-b)(c-a+b)$ and pair the brackets (difference of two squares):

$$
\begin{aligned}
(a+b+c)(a+b-c) &= (a+b)^2 - c^2 = 2ab + (a^2+b^2-c^2) \\
(c+a-b)(c-a+b) &= c^2 - (a-b)^2 = 2ab - (a^2+b^2-c^2)
\end{aligned}
$$

Multiplying the two results gives $4a^2b^2 - (a^2+b^2-c^2)^2$. Use $a^2 = 29,\ b^2 = 37,\ c^2 = 32$:

$$
\begin{aligned}
a^2 + b^2 - c^2 &= 29 + 37 - 32 = 34 \\
16\,\text{Area}^2 &= 4(29)(37) - 34^2 = 4292 - 1156 = 3136 \\
\text{Area}^2 &= \frac{3136}{16} = 196 \\
\text{Area} &= 14
\end{aligned}
$$

**Step 3: Check with the coordinate area formula**

$$
\frac{1}{2}\Big|\,x_1(y_2-y_3) + x_2(y_3-y_1) + x_3(y_1-y_2)\,\Big|
= \frac{1}{2}\Big|\,2(5) + 6(-1) + 8(-4)\,\Big|
= \frac{1}{2}\,|-28| = 14
$$

### Answer

$$
\boxed{\text{Area of } \triangle ABC = 14 \text{ square units}}
$$

**Why it works:** Heron's formula needs only the three side lengths, and the coordinate formula needs only the vertices. Both describe the same triangle, so they must agree.

---

## Question 2: Triangle with P(1, 2), Q(5, 4), R(3, 8)

**Method:** Determinant area formula, expanding the 3×3 determinant **down a column** (column 3).

### Plan
1. Set up the determinant with the coordinates and a column of 1s.
2. Expand down column 3 using the sign pattern for that column.
3. Halve the result.

### Coordinates

| Label | Point | x | y |
|:--:|:--:|:--:|:--:|
| P₁ | P | 1 | 2 |
| P₂ | Q | 5 | 4 |
| P₃ | R | 3 | 8 |

### Working

**Formula:**

$$
\text{Area} = \frac{1}{2}\left|\,D\,\right|, \qquad
D = \begin{vmatrix} 1 & 2 & 1 \\ 5 & 4 & 1 \\ 3 & 8 & 1 \end{vmatrix}
$$

**Rule for expanding down a column:** For each entry in the column:
- cover its row and column,
- take the 2×2 determinant of what is left (the *minor*),
- multiply by the entry and by its sign.

The sign pattern is a checkerboard. Column 3 reads **+, −, +** from top to bottom.

$$
\begin{pmatrix} + & - & + \\ - & + & - \\ + & - & + \end{pmatrix}
$$

**Expansion down column 3:**

$$
D = \underbrace{(+1)\begin{vmatrix} 5 & 4 \\ 3 & 8 \end{vmatrix}}_{\text{row 1}}
\;\underbrace{-\,(1)\begin{vmatrix} 1 & 2 \\ 3 & 8 \end{vmatrix}}_{\text{row 2}}
\;\underbrace{+\,(1)\begin{vmatrix} 1 & 2 \\ 5 & 4 \end{vmatrix}}_{\text{row 3}}
$$

Each 2×2 determinant is $ad - bc$:

$$
\begin{aligned}
\begin{vmatrix} 5 & 4 \\ 3 & 8 \end{vmatrix} &= 5(8) - 4(3) = 40 - 12 = 28 \\[4pt]
\begin{vmatrix} 1 & 2 \\ 3 & 8 \end{vmatrix} &= 1(8) - 2(3) = 8 - 6 = 2 \\[4pt]
\begin{vmatrix} 1 & 2 \\ 5 & 4 \end{vmatrix} &= 1(4) - 2(5) = 4 - 10 = -6
\end{aligned}
$$

$$
D = 28 - 2 + (-6) = 20
$$

$$
\text{Area} = \frac{1}{2} \times |20| = 10
$$

**Quick check (expand down column 1, signs + − +):**

$$
D = 1(4-8) - 5(2-8) + 3(2-4) = -4 + 30 - 6 = 20 \;\checkmark
$$

### Answer

$$
\boxed{\text{Area of } \triangle PQR = 10 \text{ square units}}
$$

**Why it works:** A determinant gives the same value whichever row or column you expand along, as long as you use the correct signs. So expanding down a column gives the same $D$ as expanding along the top row.

---

## Question 3: Points A(1, 2), B(3, 6), C(5, 10)

**Method:** Compare the **gradients** of AB and BC (no area formula).

### Plan
1. Find the gradient of AB.
2. Find the gradient of BC.
3. If they are equal, the points are collinear.

### Coordinates

| Label | Point | x | y |
|:--:|:--:|:--:|:--:|
| P₁ | A | 1 | 2 |
| P₂ | B | 3 | 6 |
| P₃ | C | 5 | 10 |

### Working

$$
m = \frac{y_2 - y_1}{x_2 - x_1} = \frac{\text{rise}}{\text{run}}
$$

$$
\begin{aligned}
m_{AB} &= \frac{6 - 2}{3 - 1} = \frac{4}{2} = 2 \\[6pt]
m_{BC} &= \frac{10 - 6}{5 - 3} = \frac{4}{2} = 2
\end{aligned}
$$

$$
m_{AB} = m_{BC} = 2
$$

### Answer

$$
\boxed{\text{A, B and C are collinear (they lie on one straight line)}}
$$

**Reason:** AB and BC have the same gradient, so they are parallel. They also share the point B, so they must be the same line. Since the three points lie on one line, no triangle can be formed (its area would be 0).

**Why it works:** A straight line has a single constant gradient. If the gradient from A to B equals the gradient from B to C, the path does not change direction at B.

---

## Question 5: Triangular land A(2, 1), B(8, 1), C(5, 7)

**Method:** Find the **perpendicular distance from C to line AB** and use that as the height. Then area = ½ × base × height, then cost.

### Plan
1. Find the equation of line AB.
2. Use the point-to-line distance formula to get the height from C.
3. Find the base AB.
4. Area = ½ × base × height.
5. Cost = area × ₦500.

### Coordinates

| Label | Point | x | y |
|:--:|:--:|:--:|:--:|
| P₁ | A | 2 | 1 |
| P₂ | B | 8 | 1 |
| P₃ | C | 5 | 7 |

### Working

**Step 1: Equation of line AB**

$$
m_{AB} = \frac{1 - 1}{8 - 2} = 0
$$

The gradient is 0, so AB is horizontal. Use point A with $y - y_1 = m(x - x_1)$:

$$
y - 1 = 0 \quad\Rightarrow\quad y = 1 \quad\Rightarrow\quad 0x + 1y - 1 = 0
$$

So $a = 0,\; b = 1,\; c = -1$.

**Step 2: Height (distance from C(5, 7) to the line)**

$$
d = \frac{|a x_0 + b y_0 + c|}{\sqrt{a^2 + b^2}}
= \frac{|0(5) + 1(7) - 1|}{\sqrt{0^2 + 1^2}}
= \frac{|6|}{1} = 6
$$

*(Sense check: the line is y = 1 and C is at y = 7, so the vertical gap is 7 − 1 = 6.)*

**Step 3: Base AB**

$$
AB = \sqrt{(8-2)^2 + (1-1)^2} = \sqrt{36} = 6
$$

**Step 4: Area**

$$
\text{Area} = \frac{1}{2} \times \text{base} \times \text{height} = \frac{1}{2} \times 6 \times 6 = 18
$$

**Step 5: Cost**

| Quantity | Value |
|:--|:--|
| Area | 18 square units |
| Rate | ₦500 per square unit |
| Total | 18 × ₦500 = ₦9,000 |

### Answer

$$
\boxed{\text{Height} = 6 \text{ units}} \qquad
\boxed{\text{Area} = 18 \text{ square units}} \qquad
\boxed{\text{Cost} = ₦9{,}000}
$$

**Why it works:** The height of a triangle is the perpendicular distance from the opposite vertex to the base line, and the point-to-line distance formula gives exactly that distance.