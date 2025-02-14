# Char Pixel Art Illustration 2

### Default Style Description
---
- Non pixel art
	- Rough draw sketches
	- Draw shape sketches
	- Rough color sketches
- Pixel art
	- Get rough color sketches to pixel sketches
	- Fill color
		- Shadowed diffuse color : recommend -10 value by diffuse color
			- Considering that eye adjust exposure. (Adaptive Exposure in HDR)
			- Effected by diffuse color and environmental color.
		- Outline color : Pick darkest color of neighbor pixel, then divide value with 4
		- Ambient Oculusion color : Pick darkest color of neighbor pixel, then divide value with 2
	- Stack light with layers
	- Give post effects
		- Soft Light : Screen, Overlay, Soft Light
		- Strong Light: Glow Dodge, Linear Dodge, Hard Light
		- Diffuse Reflection : Color Dodge, Screen, Overlay