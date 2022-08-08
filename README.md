# ABE - Activation-Based Early-Stopping

This repository includes code accompagnying our paper **Improving Meta-Learning Generalization with Activation-Based Early-Stopping** [(see link)](https://arxiv.org/abs/2208.02377), accepted at [CoLLAs 2022](https://lifelong-ml.cc/) and to be published in the [Proceedings of Machine Learning Research](https://proceedings.mlr.press/) (PMLR). Here is also a short [YouTube video](https://www.youtube.com/watch?v=khSTklKePwU) explaining the paper.

Authors : Simon Guiroy, Christopher Pal, Gonçalo Mordido, Sarath Chandar.

In this repo you will find :
- `ABE_tensorflow.ipynb` : Jupyter notebook example for how to apply the method, implemented in Tensorflow
- `ABE_pytorch.ipynb` : Jupyter notebook example for how to apply the method, implemented in PyTorch
- `activation_based_early_stopping.py` : Simple implementation of the functions of ABE, namely for computing the aggregated moments and obtain the neural activation trajectory (Equation 3), and computing the objective value (Equation 4) which is maximized to identify the critical layer, critical moment, and critical time. The implementation is in PyTorch (for GPU support) but it can easily be implemented in Tensoflow (see notebook), or in Numpy, and even in pure python.
