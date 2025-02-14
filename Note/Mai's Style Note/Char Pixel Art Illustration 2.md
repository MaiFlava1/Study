# Char Pixel Art Illustration 2

### Default Style Description
---
- Non pixel art
	- Rough draw sketches
	- Draw shape sketches
	- Rough color sketches
- Pixel art
	- Get rough color sketches to pixel sketches
	- Shade : 
		- Shadowed diffuse color : recommend -10 value by diffuse color
			- Considering that eye adjust exposure. (Adaptive Exposure in HDR)
			- Effected by diffuse color and environmental color.
		- Outline color : Pick darkest color of neighbor pixel, then divide value with 4
		- Ambient Oculusion color : Pick darkest color of neighbor pixel, then divide value with 2
	- Stack light with layers
		- Use Overlay blend mode for dark outline color doesn't affected by bright light colors
		
- $$R =\begin{cases}
\frac{2 \times A \times B}{255}, & A < 128 \\
255 - \frac{2 \times (255 - A) \times (255 - B)}{255}, & A \geq 128
\end{cases}$$
	- Give post effects