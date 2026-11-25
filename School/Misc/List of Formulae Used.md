---
Subject: Multiple
Date: 2026-11-17
Purpose: Misc
---

# Further Mathematics

## Coordinate Geometry — Straight Lines

### Sectioning a Line by a Ratio

$\dfrac{m}{n} = \dfrac{x - x_1}{x_2 - x}$ [^1]

$x = \dfrac{mx_2 + nx_1}{m + n}$[^2]

$\dfrac{m}{n} = \dfrac{y - y_1}{y_2 - y}$ 

$y = \dfrac{my_2 + ny_1}{m + n}$

### Gradient of a Line Segment

$m = \dfrac{\Delta y}{\Delta x} = \dfrac{y_2 - y_1}{x_2 - x_1}$

### Angle of a Slope

$m = \tan \theta$[^3]

### Angle between Two Lines

$\alpha_2 = \alpha + \alpha_1 \qquad \text{Exterior Angle Theorem}$[^4]

$\tan(A - B) = \dfrac{\tan A - \tan B}{1 + \tan A \, \tan B}$ 

$\tan \alpha = \dfrac{\tan \alpha_2 - \tan \alpha_1}{1 + \tan \alpha_2 \, \tan \alpha_1} = \dfrac{m_2 - m_1}{1 + m_2 \, m_1}$[^5] 

### Parallelism and Perpendicularity

For two lines to be parallel, their gradients must be equal to each other, i.e. $m_1 = m_2$.

For two lines to be perpendicular, the product of their gradients must be equal to $-1$. i.e. Their gradients must be negative reciprocals of each other. i.e. $m_1 \, m_2 = -1$, $m_1 = - \frac{1}{m_2}$, or $m_2 = - \frac{1}{m_1}$.

### Equations of a Line

1. **Slope / Gradient Intercept** — $y = mx + c$
2. **One Point Form** — $m(x - x_1) = y - y_1$
3. **Two Point Form** — $\frac{y_2 - y_1}{x_2 - x_1} = \frac{y_2 - y}{x_2 - x} = \frac{y - y_1}{x - x_1}$[^6]
4. **Perpendicular Distance** — $Q = y \sin \alpha + x \cos \alpha$[^7]
5. **General Form** — $ax + by + c = 0$

## Coordinate Geometry — Points

### Distance between Two Points

$\Delta x = x_2 - x_1$
$\Delta y = y_2 - y_1$

$|AB| = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2}$

### Area of Three Points 

With Coordinates: $\frac{1}{2} | x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2) |$ 

With the Determinant: $\dfrac{1}{2} \left| \begin{vmatrix} x_1 & y_1 & 1 \\ x_2 & y_2 & 1 \\ x_3 & y_3 & 1\end{vmatrix} \right|$

With the Determinant 2: $\dfrac{1}{2} \left| x_1 \begin{vmatrix} y_2 & 1 \\ y_3 & 1 \end{vmatrix} - y_1 \begin{vmatrix} x_2 & 1 \\ x_3 & 1 \end{vmatrix} + \begin{vmatrix} x_2 & y_2 \\ x_3 & y_3 \end{vmatrix} \right|$[^8]

With the Determinant 3: $\dfrac{1}{2} | w_2 z_3 - z_2 w_3 |$[^9]

### Collinearity

Three points are collinear if:

1. The area of the "triangle" they make is equal to 0.
	i.e. $\frac{1}{2} | x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2) | = 0$  
2. If the gradients between any two of the three points are all equal
	i.e. $\frac{y_2 - y_1}{x_2 - x_1} = \frac{y_3 - y_2}{x_3 - x_2} = \frac{y_3 - y_1}{x_3 - x_1}$ 

### Height of a Triangle

$\text{height} = \dfrac{| x_1(y_2 - y_3) + x_2(y_3 - y_1) + x_3(y_1 - y_2) |}{\sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2}}$[^10]


## Trigonometric Identities

$\sin \theta = \cos (90 - \theta)$
$\cos \theta = \sin (90 - \theta)$
$\tan \theta = \frac{\sin \theta}{\cos \theta}$
$\tan \theta = \cot (90 - \theta)$
$\sin ^2 \theta + \cos ^2 \theta = 1$
$\csc ^2 \theta = 1 + \cot ^2 \theta$
$\sec ^2 \theta = 1 + \tan ^2 \theta$

## Misc.

If $|x| = a$ and $a \geq 0$, then $x = \pm a$.


# Mathematics

## Approximation and Estimation
### Error

$\text{Absolute Error} = | \text{Actual Value} - \text{Measured Value} |$

$\text{Relative Error} = \dfrac{\text{Absolute Error}}{\text{Actual Value}}$ [^11]

$\text{Relative Error}= \dfrac{| \text{Actual Value} - \text{Measured Value} |}{\text{Actual Value}}$

$\text{Percentage Error} = \text{Relative Error} \times 100\%$

$\text{Percentage Error} = \dfrac{\text{Absolute Error}}{\text{Actual Value}} \times 100\%$

$\text{Percentage Error} = \dfrac{| \text{Actual Value} - \text{Measured Value} |}{\text{Actual Value}} \times 100\%$

### Limits of Accuracy

$\text{Limit of Accuracy / Maximum Error} = \pm \dfrac{\text{Unit}}{2}$[^12]

$\text{Lower Bound} = \text{Actual Value} - \text{Limit of Accuracy}$

$\text{Upper Bound} = \text{Actual Value} + \text{Limit of Accuracy}$

## Algebraic Identities

$(x + y)^2 = x^2 + 2xy + y^2$
$(x - y)^2 = x^2 - 2xy + y^2$
$(x + y)(x - y) = x^2 - y^2 \qquad \text{(Difference of two squares)}$

$\dfrac{x}{y}$ is undefined when $y = 0$, and when $y \ne 0$ is equal to 0 when $x = 0$.

$\dfrac{a}{b} + \dfrac{c}{d} = \dfrac{ad + bc}{bd}$

$\dfrac{a}{b} - \dfrac{c}{d} = \dfrac{ad - bc}{bd}$

# Physics

## Electrical Energy and Power

$W = QV = IVt = Pt = I^2 Rt = \frac{V^2 t}{R}$
$Q = It$
$V = IR$
$I = V \div R$
$P = \frac{W}{t} = IV = I^2R = \frac{V^2}{R}$


$\begin{array}{r@{\;}c@{\;}l@{\quad}l} W & \hcline{2em} & \text{Electrical Energy} & \text{(Joules, J)} \\ Q & \hcline{2em} & \text{Electrical Charge} & \text{(Columbs, C)} \\ V & \hcline{2em} & \text{Potential Difference} & \text{(Volts, V)} \\ I & \hcline{2em} & \text{Electric Current} & \text{(Amperes, A)} \\ R & \hcline{2em} & \text{Electrical Resistance} & \text{(Ohms, \( \Omega \))} \\ P & \hcline{2em} & \text{Electrical Power} & \text{(Watt, W)} \\ t & \hcline{2em} & \text{Time} & \text{(Seconds, s)} \end{array}$ 

### Buying and Selling Electrical Energy

$1kWh = 3.6MJ = 3 \, 600 \, 000 J$ 
$\text{Cost} = Pct$
$\begin{array}{r@{\;}c@{\;}l@{\quad}l} P & \hcline{2em} & \text{Electrical Power} & \textbf{(Kilowatts, kW)} \\ c & \hcline{2em} & \text{Unit Cost of Electrical Energy} & \text{(Kobo per Kilowatt Hour, kobo / kWh)} \\ t & \hcline{2em} & \text{Time} & \text{(Hours, h)} \end{array}$ 
## Vector Quantities

### Resultant of Vector Addition

1. **Same Direction** — $R = F_1 + F_2$[^13]
2. **Opposite Directions** — $R = | F_1 - F_2 |$
3. **Perpendicular Directions** — $R = \sqrt{F_1^2 + F_2^2}$
4. **Multiple Vectors** — It's a clusterfuck and I'm not bothered to note it down.

$\tan \alpha = \frac{y}{x}$[^14]

### Resolution of Vectors into Components

$x = F\cos \theta$[^15]
$y = F\sin \theta$

## Motion

$v = u + at$
$s = ut + \frac{1}{2} at^2$
$v^2 = u^2 + 2as$
$s = \frac{1}{2} t(u + v)$

$\begin{array}{r@{\;}c@{\;}l@{\quad}l} v & \hcline{2em} & \text{Final Velocity} & \text{(Metres per second, m/s)} \\ u & \hcline{2em} & \text{Initial Velocity} & \text{(Metres per second, m/s)} \\ a & \hcline{2em} & \text{Acceleration} & \text{(Metres per square second, m/s\(^2\))} \\ t & \hcline{2em} & \text{Time} & \text{(Seconds, s)} \\ s & \hcline{2em} & \text{Distance} & \text{(Metres, m)} \end{array}$

## Projectile in Motion

### Horizontal Launch

$R = x = ut$
$h = y = \frac{1}{2}gt^2$
$H = ut + \frac{1}{2}gt^2$

$\begin{array}{r@{\;}c@{\;}l@{\quad}l} R & \hcline{2em} & \text{Range} & \text{(Metres, m)} \\ h & \hcline{2em} & \text{Height} & \text{(Metres, m)} \\ H & \hcline{2em} & \text{Total Distance} & \text{(Metres, m)} \\ u & \hcline{2em} & \text{Initial Velocity} & \text{(Metres per second, m/s)} \\ g & \hcline{2em} & \text{Gravity} & \text{(Metres per square second, m/s\(^2\))} \\ t & \hcline{2em} & \text{Time} & \text{(Seconds, s)} \end{array}$
### Vertical Launch

$h = \dfrac{u^2 \sin ^2 \theta}{2g}$

$t = \dfrac{u \sin \theta}{g}$

$T = \dfrac{2u \sin \theta}{g}$

$R = \dfrac{u \sin (2 \theta)}{g}$

$R_M = \dfrac{u}{g}$

$\begin{array}{r@{\;}c@{\;}l@{\quad}l} h & \hcline{2em} & \text{Maximum Height Attained} & \text{(Metres, m)} \\ t & \hcline{2em} & \text{Time Taken to reach Max Height} & \text{(Seconds, s)} \\ T & \hcline{2em} & \text{Time in Flight} & \text{(Seconds, t)} \\ R & \hcline{2em} & \text{Horizontal Range} & \text{(Metres, m)} \\ R_M & \hcline{2em} & \text{Maximum Range} & \text{(Metres, m)} \\ u & \hcline{2em} & \text{Initial Velocity} & \text{(Metres per second, m/s)} \\ \theta & \hcline{2em} & \text{Angle made with the +ve \(x\)-axis} & \text{(Degrees, \(^\circ\))} \\ g & \hcline{2em} & \text{Gravity} & \text{(Metres per square second, m/s\(^2\))} \end{array}$

## Circular Motion / S.H.M.

$F_C = \dfrac{mv^2}{r} = m \omega ^2 r$

$F_F = -\dfrac{mv^2}{r}$

$s = \theta r$

$v = \omega r = \pm \omega \sqrt{A^2 -y^2}$

$y = A \sin \omega t \quad \text{or} \quad A \sin (\omega t + \theta)$

$a = \alpha r = \dfrac{v^2}{r} = \omega ^2 r = -\omega ^2 y$ 

$a_{\mathrm{max}} = \omega ^2 A$

$\omega = 2 \pi f$

$f = \dfrac{\omega}{2 \pi} = \dfrac{1}{T}$

$T = \dfrac{2 \pi}{\omega} = \dfrac{1}{f}$ 

$\mathrm{K.E_{max}} = \frac{1}{2} mv_{\mathrm{max}}^2$ 

$v_{\mathrm{max}} = \omega A$ 

$F \propto e$

$F = Ke$

### Simple Pendulum

$T = 2 \pi \sqrt{\dfrac{l}{g}}$

$f = \dfrac{\sqrt{\frac{g}{l}}}{2 \pi}$

### Spiral Spring

$T = 2 \pi \sqrt{\dfrac{M}{K}}$

$f = \dfrac{\sqrt{\frac{K}{M}}}{2 \pi}$

## Identities

$c^2 = a^2 + b^2 - 2ab\cos C$ [^16]
$a^2 = b^2 + c^2 - 2bc\cos A$
$b^2 = a^2 + c^2 - 2ac\cos B$

$\dfrac{a}{\sin A} = \dfrac{b}{\sin B} = \dfrac{c}{\sin C}$

# Footnotes

[^1]: $m$ and $n$ refer to the straight line $AB$ being divided by a point $P$ such that $AP : PB = m : n$. $m$ **does not** refer to the gradient of the line in this case.

[^2]: External division of a straight line uses the ratio $m : {-n}$.

[^3]: Given a straight line $y = mx + c$, $\theta$ is the angle the straight line makes with the positive x-axis.

[^4]: Given two lines, $\alpha$ is the angle between the two lines, $\alpha_1$ is the angle between the first line and the positive x-axis, and $\alpha_2$ is the angle between the second line and the positive x-axis.

[^5]: $\frac{m_2 - m_1}{1 + m_2 \, m_1}$ gives the tangent of the directed angle from the first line to the second line, which can be  negative. To get the acute angle $\alpha$, take the absolute value of the fraction. If the lines are perpendicular, then $\alpha = 90^\circ$ and the formula is undefined.

[^6]: The equality breaks apart with vertical lines because gradients do not exist on vertical lines. Three points with $x_1 = x_2 = x_3$ are collinear but the gradient test breaks due to division by 0.

[^7]: $Q$ is the perpendicular distance from the origin to the line. $\alpha$ is the angle between the perpendicular from the origin and the positive x-axis.

[^8]: The second determinant formula is the first determinant formula expanded.

[^9]: $w_2 = x_2 - x_1$, $z_2 = y_2 - y_1$, $w_3 = x_3 - x_1$, and $z_3 = y_3 - y_1$. i.e. $w_n$ is $x_n$ after $x_1$ is shifted  to the origin, and $z_n$ is $y_n$ after $y_1$ is shifted to the origin.

[^10]: Given triangle $ABC$ and its base is $AB$, therefore its perpendicular height is from $AB$ to $C$.

[^11]: Relative Error is undefined when Actual Value is equal to 0.

[^12]: Unit refers to the smallest place value the measurement is rounded to. e.g. A "unit" is 0.1 when rounding to 1 decimal place.

[^13]: Given resultant force/vector $R$ and forces/vectors $F_1$ and $F_2$.

[^14]: $\alpha$ refers to the direction of the resultant along the horizontal (x-axis). $x$ refers to the vector that is purely horizontal. $y$ refers to the vector that is purely vertical.

[^15]: $F$ is the vector, and $\theta$ is the angle the vector makes with the x-axis.

[^16]: Given 3 angles $A$, $B$, and $C$, and 3 sides $a$, $b$, and $c$.


