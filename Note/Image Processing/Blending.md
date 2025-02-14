# Blending
### Type and Formulas
---
- Multiply
	- Formula :  $R = \frac{A \times B}{255}$
- Screen
	- Formula :  $R = 255 - \frac{(255 - A) \times (255 - B)}{255}$
- Overlay
	- Formula :  $$R =\begin{cases}
\frac{2 \times A \times B}{255}, & A < 128 \\
255 - \frac{2 \times (255 - A) \times (255 - B)}{255}, & A \geq 128
\end{cases}$$
- Color Dodge
	- Formula :  $R = \min\left(255, \frac{A}{(255 - B)} \times 255\right)$
- 