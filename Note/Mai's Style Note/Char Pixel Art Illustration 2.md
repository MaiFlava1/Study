# Char Pixel Art Illustration 2

### Processing
---
- Non pixel art
	- Rough draw sketches
	- Draw shape sketches
	- Rough color sketches
- Pixel art
	- Set canvas size that people consider as pixel art.
	- Get rough color sketches to pixel sketches
	- Shade
		- Shadowed diffuse color : recommend -10 value by diffuse color
			- Considering that eye adjust exposure. (Adaptive Exposure in HDR)
			- Effected by diffuse color and environmental color.
		- Outline color : Pick darkest color of neighbor pixel, then divide value with 4
			- Draw outline when enough far from back.
		- Ambient Oculusion color : Pick darkest color of neighbor pixel, then divide value with 2
	- Stack light with layers
		- Use Overlay blend mode for dark outline color doesn't affected by bright light colors
	- Give post effects