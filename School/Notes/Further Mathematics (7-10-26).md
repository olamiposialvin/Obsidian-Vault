---
Subject: Further Mathematics
Date: 2026-10-07
Purpose: Note
---

# Straight Lines
## Angle between Two Lines

<center><img src="Straight Lines - Illustration 1.1.svg" width=300px></center>

From the exterior angle theorem:
$$α_2 = α + α_1$$
Make $α$ the subject of the formula.
$$α = α_2 - α_1$$
Take the tangent of both sides.
$$\tan(α) = \tan(α_2 - α_1)$$
Using the tangent subtraction formula:
$$\tan(A - B) = \frac{\tan(A) - \tan(B)}{1 + \tan(A) \tan(B)}$$

$$\tan(α_2 - α_1) = \frac{\tan(α_2) - \tan(α_1)}{1 + \tan(α_2) \tan(α_1)}$$
Recall $m_x = \tan(α_x)$
$$\tan(α) = \frac{m_2 - m_1}{1 + m_2 m_1}$$

**Notes:**
1. Angle $α$ must be an acute angle ($α < 90^\circ$), if angle $α$ is obtuse ($α > 90^\circ$), then substitute it with $180^\circ - α$
2. If $\frac{m_2 - m_1}{1 + m_2 m_1}$ is negative, then $α$ is obtuse. To make it acute, remove the negative sign.

### Worked Example

Find the angle between lines $3x + 4y - 12 = 0$ and $5x - 2y + 8 = 0$ to the nearest degree.

Find $m$ in $y = mx + c$

**Equation 1:** $3x + 4y - 12 = 0$
	$4y = 12 - 3x$
	$y = \frac{12 - 3x}{4}$
	$y = \frac{12}{4} - \frac{3}{4}x$
	$m_1 = - \frac{3}{4}$

**Equation 2:** $5x - 2y + 8 = 0$
	$2y = 5x + 8$
	$y = \frac{5x + 8}{2}$
	$y = \frac{5}{2}x + \frac{8}{2}$
	$m_2 = \frac{5}{2}$

$$\tan(α) = \frac{m_2 - m_1}{1 + m_2 m_1}$$

$$\tan(α) = \frac{\frac{5}{2} - ( - \frac{3}{4} )}{1 + \frac{5}{2} ( - \frac{3}{4} )}$$

$$\tan(α) = \frac{\frac{5}{2} + \frac{3}{4} }{1 - \frac{5}{2} \cdot \frac{3}{4}}$$

$$\tan(α) = \frac{\frac{13}{4}}{1 - \frac{15}{8}}$$

$$\tan(α) = \frac{\frac{13}{4}}{- \frac{7}{8}}$$

$$\tan(α) = \frac{13}{4} \div - \frac{7}{8}$$

$$\tan(α) = \frac{13}{4} \cdot - \frac{8}{7}$$

$$\tan(α) = - \frac{26}{7}$$

$$\tan^{-1}( - \frac{26}{7} ) \approx -74.9315 ^\circ $$

$\tan^{-1}$ returns a negative value, meaning angle $α$ is obtuse, remove the negative sign to make it acute.

$$α \approx 74.9315 ^\circ $$

$$α = 75 ^\circ \text{ to the nearest degree.}$$