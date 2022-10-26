# Classifier-free Diffusion Guidance

Diffusion models have recently emerged as an expressive and flexible family of generative models. [Classifier_Free_DDIM_Mnist.ipynb](Classifier_Free_DDPM_Mnist.ipynb) is simple implementation of a conditional diffusion model, which is capable to generate MNIST digits. The model use [the classifier-free guidance](https://arxiv.org/abs/2207.12598) without training other classifiers. Additionally, [DDIM](https://arxiv.org/abs/2010.02502) is adopted to accelerate generating samples in this work.

<div align=center><img src="https://github.com/tatakai1/classifier_free_ddim/blob/main/saved_models/demo.gif?raw=true" width="  "></div>
<p align="center">Generation process of DDIM</p>

