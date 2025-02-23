# Ambient Occlusion (AO)
### What is Ambient Occlusion (AO)
---
Ambient Occulusion is rendering technique calculating how exposed to ambient lighting. 

### Why are we using AO
---
**Global Illumination** are works to all surfaces but at the corner or light keep bounce and decrease their light power, means getting darker. But this method is very **expensive** to render.

So estimate Ambient Light affected by Global Illumination, And then calculating how exposed with AO and check how dark is it.

$$
Global Illumination = Ambient Light * Ambient Occulusion * etc
$$