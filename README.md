# Distance-metric-learning
Implement the learning algorithm from the paper "Distance metric learning, with application to clustering with side-information [Eric P. Xing]".

*Detailed derivertion about some formulas in the paper.

*The objective function we want to achieve is as follows. (3-5)

min{A} sum{S}((xi-xj)'A(xi-xj))

s.t. sum{D}sqrt((xi-xj)'A(xi-xj))

![alt text](https://github.com/JasonYee/Distance-metric-learning/blob/master/figure_1.png)
