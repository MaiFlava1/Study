# Lambertian Reflectance
### What is Lambertian Reflectance
---
 Lambertian reflectance is light reflective equation in ideal situation of Diffuse reflection.
 
### How to calculate
---
- I : Incoming light RGB
- S : Amount of light that surface get
- IA : Angle between surface and Incoming light
- SNA : Angle between surface normal and Incoming light

$$S = rcos( SNA ) = rcos( 90 - IA ) = rsin( IA ) * I$$
### Pre-Calculated data
---

| IA           | 0    | 10   | 20   | 30   | 40   | 50   | 60   | 70   | 80   | 90  |
| ------------ | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | --- |
| rcos( SNA )  | 0    | 0.17 | 0.34 | 0.50 | 0.64 | 0.77 | 0.87 | 0.94 | 0.98 | 1   |
| rsin( IA )   | 0    | 0.17 | 0.34 | 0.50 | 0.64 | 0.77 | 0.87 | 0.94 | 0.98 | 1   |
| Differencial | 0.17 | 0.17 | 0.16 | 0.14 | 0.13 | 0.1  | 0.07 | 0.04 | 0.02 | 0   |

