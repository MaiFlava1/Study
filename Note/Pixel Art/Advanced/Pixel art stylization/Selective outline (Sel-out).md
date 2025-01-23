# Selective outline (Sel-out)
### What is Selective outline 
---
Sel-out is advanced pixel art technique. This method can **solve** problem that outer AA buffer become **unfittable with other backgrounds**.

### How to use
---
Draw outline and draw internal AA buffer, In this case, internal, contains **outlines** and **sprites**. In other words, Drawing internal AA but thinner is maybe correct. 

### Personal opinion
---
Using Internal AA buffer with only sprites is better when using sprite in magnify pixel situation. When Sel-out method encounter 