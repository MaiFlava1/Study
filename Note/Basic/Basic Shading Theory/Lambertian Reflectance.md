# Lambertian reflectance
### What is Lambertian Reflectance
---
 Lambertian reflectance is light reflective equation in ideal situation.
### How to calculate
---
- I : Incoming lights RGB
- S : Amount of light that surface get
- IA : Angle between surface and Incoming lights

$$S = cos( IA ) * I$$
### Pre-Calculated data
---

| IA              | 0   | 10   | 20   | 30   | 40   | 50   | 60   | 70   | 80   | 90  |
| --------------- | --- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | --- |
| cos( IA )       | 1   | 0.98 | 0.94 | 0.87 | 0.77 | 0.64 | 0.50 | 0.34 | 0.17 | 0   |
| Differencial    |     | 0.02 |      |      |      |      |      |      |      |     |
| Cel shade range |     |      |      |      |      |      |      |      |      |     |


