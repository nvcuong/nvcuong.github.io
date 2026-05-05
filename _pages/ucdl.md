---
layout: archive
title: "Project IV: Uncertainty Calibration for Deep Learning Models"
permalink: /ucdl/
author_profile: true
---

{% include base_path %}

## Description

Deep learning provides a suite of machine learning models that are based on artificial neural networks, which are the primary type of models used in modern artificial intelligence. 
These models usually consist of several layers, each of which involves a linear combination of previous outputs and a non-linear activation operator. 
Empirical observations have found that the more layers in the network (i.e., the deeper the model), the poorer its uncertainty estimates are. 
This may affect the performance of the model when its uncertainty estimates are used for decision making.

To mitigate this problem, there are several approaches that have been considered by the machine learning community. 
Examples of these approaches include the use of Bayesian methods, model ensemble, and uncertainty calibration. 
Among them, uncertainty calibration is a very simple approach that applies a post-processing step to the trained models to correct their uncertainty estimates via a validation data set. 
Despite its simplicity, this approach has been very effective in calibrating the uncertainty of deep learning models.

In this project, students will investigate the effects of different calibration approaches to the uncertainty estimates as well as the performance of deep learning models. 
They will have opportunities to work with real-world large scale data sets and state-of-the-art machine learning models using either Python or R.

## Mode of operation and evidence of learning

The project will involve learning through reading and discussion, and programming in R or Python. 
Students will demonstrate their understanding by implementing different uncertainty calibration methods and testing them on real and simulated data. 
Students will need to clearly communicate the material and their results in both written and oral formats.


## Prerequisites

- Machine Learning and Neural Networks III.
- You must also be comfortable with programming in R or Python.

## References

- Guo et al. *On calibration of modern neural networks*. ICML, 2017.
- Kumar et al. *Verified uncertainty calibration*. NeurIPS, 2019.
- Wang et al. *Rethinking calibration of deep neural networks: Do not be afraid of overconfidence*. NeurIPS, 2021.
