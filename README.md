# Supplemental Machine Learning Module for Tensorflow

In this Github repository, I aim to provide additional abstractions and functionality to the Tensorflow library. I was largely inspired to create this library because I wanted to make is easier to implement transformers and use distributed learning techniques with Tensorflow models. This library isn't rigorously debugged, and definitely isn't ready yet for widespread use, but it serves as the first stepping stone to make some of these techniques more accessible. In the development of these modules, I try to follow the papers where these techniques were introduced, and cite the paper I used in the submodule.

Currently, the following functionality is available:
- Training and evaluation of co-trained ensembles
- Abstraction for ensembles of Tensorflow models
- Transformers and their many layer
