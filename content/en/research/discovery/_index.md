---
title: ML-guided exploration and discovery
type : 
---
## ML-guided exploration and discovery

Data-driven exploration and discovery in science and engineering are challenging when dynamics are complex and data are limited. I develop methods that use probabilistic machine learning models to guide exploration based on uncertainty quantification. 

- Searching for simple/interpretable solutions in black-box optimization [1].
  - Simultaneously optimize objective and solution simplicity, by drawing connections between multi-objective Bayesian optimization and regularized acquisition functions.
  - Simple solutions provide interprebilty to the outcome and reduce cost of deployment and maintenance.
  
<p align="center">
<img src="/media/sebo.png" width="450">
</p>

- Learning to control robotic system with safety constraints [2].
  - Developed probabilistic safety certificates for control barrier functions based on uncertainty quantification.
<p align="center">
<img src="/media/probf.png" width="450">
</p>


#### Related Publications

[1] **Sparse Bayesian Optimization**. [Paper](https://arxiv.org/abs/2203.01900)\
<ins>Sulin Liu</ins>* (equal contr.), Qing Feng*, David Eriksson*, Benjamin Letham, Eytan Bakshy. *Under submission*, 2022. 

[2] **ProBF : Probabilistic Safety Certificates with Barrier Functions**. [Paper](https://arxiv.org/abs/2112.12210) | [Code](https://github.com/athindran/ProBF)\
Athindran Ramesh Kumar*, <ins>Sulin Liu</ins>* (equal contr., random order), Jaime F. Fisac, Ryan P. Adams, Peter J. Ramadge.
*Preprint*, 2021.\
short version at *NeurIPS Safe and Robust Control of Uncertain Systems Workshop*, 2021. 
