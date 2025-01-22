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
WhatWeCanSee = RGB = Min(WhiteColorInRGB, hdrRGB)
$$

### Calculate with Lambertian reflectance
---
$$
RGB(255, 0, 0) = Min(RGB(255, 255, 255), hdrRGB (1000, 0, 0)* cos(10))
$$