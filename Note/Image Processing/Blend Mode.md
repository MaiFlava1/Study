# Blend Mode
### Type and Formulas
---
- Multiply
	- Darker
	- Formula :  $R = \frac{A \times B}{255}$
- Screen
	- Bright
	- Formula :  $R = 255 - \frac{(255 - A) \times (255 - B)}{255}$
- Overlay
	- Multiply and Screen
	- Formula :  $$R =\begin{cases}
\frac{2 \times A \times B}{255}, & A < 128 \\
255 - \frac{2 \times (255 - A) \times (255 - B)}{255}, & A \geq 128
\end{cases}$$
- Color Dodge
	- Formula :  $R = \min\left(255, \frac{A}{(255 - B)} \times 255\right)$