# High dynamic range (HDR)
### What is HDR
---
Increasing some range, in this case is light, specifically RGB.

### How to calculate
---
- RGB range : 0 ~ 255
- HDR RGB range : 0 ~ 255 ~ Infinite
- Consider as overpowered light.


$$
WhatWeCanSee = RGB = min(WhiteColorInRGB, hdrRGB)
$$

### Calculate with Lambertian reflectance
---
If light is strong enough, areas that would normally be dark will be illuminated. 

$$
RGB(170, 0, 0) = min(RGB(255, 255, 255), hdrRGB (1000, 0, 0)* rsin(10))
$$