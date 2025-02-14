# Blend Mode
### Type and Formulas
---
- Multiply
	- Darker.
	- Formula :  $$R = \frac{A \times B}{255}$$
- Screen
	- Bright.
	- Formula :  $$R = 255 - \frac{(255 - A) \times (255 - B)}{255}$$
- Overlay
	- Mix of Multiply and Screen
	- Use Multiply if dark, Use Screen if bright.
	- Formula :  $$R =\begin{cases}
\frac{2 \times A \times B}{255}, & A < 128 \\
255 - \frac{2 \times (255 - A) \times (255 - B)}{255}, & A \geq 128
\end{cases}$$
- Hard Light
	- Similar with overlay
	- Formula : $$R =
\begin{cases}
Multiply(A, 2B), & B < 128 \\
Screen(A, 2(B - 128)), & B \geq 128
\end{cases}$$
- Color Dodge
	- Make brighter
	- More brighter if already bright.
	- Formula :  $$R = \min\left(255, \frac{A}{(255 - B)} \times 255\right)$$
- Soft Light
	- Mix of Screen, Overlay, Soft Light
	- Formula : $$
R = \frac{(255 - (255 - A) \times (255 - B))}{255}
$$
- Strong Light
	- Mix of Multiply and Screen
	- Formula : $$
R =
\begin{cases}
Multiply(A, 2B), & B < 128 \\
Screen(A, 2(B - 128)), & B \geq 128
\end{cases}
$$
- Diffuse Reflection
	- Mix
	- Formula : $$
R = Overlay(A, Screen(A, ColorDodge(A, B)))
$$
