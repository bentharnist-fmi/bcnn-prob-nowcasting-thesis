# Probabilistic Precipitation Nowcasting Using Bayesian Convolutional Neural Networks

### Abstract
---

Precipitation nowcasting refers to forecasting precipitation at timescales of minutes to a few hours. This is usually approached by using models which are fed with real-time weather radar reflectivity images correlated with observed precipitation. Reliably nowcasting precipitation probabilities at fine spatial scales is a societally important challenge. This is due to the danger and economic losses potentially incurred by heavy rainfall and particularly flash floods provoked by them. 

In this thesis a Convolutional Neural Network (CNN) previously used for nowcasting deterministic precipitation estimates is adapted into a Bayesian Neural Network (BNN) for producing an ensemble of possible prediction scenarios used to estimate precipitation probabilities. A BNN is based on the principle of placing probability distributions onto values of network parameters that are estimated using Bayesian inference. In this work these are modeled as Normal distributions, whose parameters are learned through backpropagation in a scheme called Stochastic Variational Inference (SVI). The prediction ensembles for a trained model can then be formed by Monte Carlo sampling each parameter from its distribution, thus inducing a predictive distribution on data.

The predictive skill of the developed model, abreviated BCNN, is evaluated against several established baseline models using a multitude of criteria covering various aspects of the precipitation nowcasts. On some aspects, BCNN is found to perform at a level close or equal to baseline models. However, it is found to be especially challenging to produce a well-calibrated and reliable probabilistic nowcast, owning likely to properties of the model and problems in the training procedure. Nevertheless, BCNN provided encouraging preliminary results, pointing out potential avenues of further study for probabilistic precipitation nowcasting using Bayesian Neural Networks. 

---
