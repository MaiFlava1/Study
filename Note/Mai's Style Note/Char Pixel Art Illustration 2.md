# Char Pixel Art Illustration 2

### Default Style Description
---
- Non pixel art
	- Rough draw sketches
	- Draw shape sketches
	- Rough color sketches
- Pixel art
	- Get rough color sketches to pixel sketches
	- Fill color with that effected by main color shadow and environmental color
		- Color equation
			- Outline color : Pick darkest color of neighbor diffuse pixel, then divide value with 4
			- Ambient Oculusion color : Pick darkest color of neighbor pixel, then divide value with 2
	- Stack light with layers
	- Give post effects