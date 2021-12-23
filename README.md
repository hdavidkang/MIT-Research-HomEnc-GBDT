# Building Ensemble of Trees beyond interpolation threshold for high-performance privacy-preserving ML 


## 🚀 Motivation
- Privacy-preserving ensemble trees are out there, but how effective can they be, and what are the conditions?

## 🎓 Theoretical background
- It is still widely accepted in the machine learning community that 'overfitting' means decrease in test performance by default.
- However, as clearly evidenced in some of the recent breakthroughs in ML including [Zhang et. al (2017)](https://dl.acm.org/doi/abs/10.1145/3446776) and [Belkin, 2019](https://www.pnas.org/content/116/32/15849.short), interpolation and generalization can co-exist.

## 💻 Work in progress
- We believe larger class of functions can contain interpolating functions with smaller norm that give lower test risk.
- We construct a HomEnc-GBDT-Regressor and show that the test performance can be significantly high when we are in the regime beyond the interpolation threshold.
- So yes, there is the cost of deploying encryption, but if the ML model is smartly chosen, the benefit can be significant.
