# CycleGAN

This repository contains an implementation of the CycleGAN architecture based on the original paper: [Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks](https://arxiv.org/abs/1703.10593). The model is trained on the **horse2zebra** dataset.

## Dataset
The model is trained on the `horse2zebra` dataset, which is part of the [CycleGAN dataset collection](https://people.eecs.berkeley.edu/~taesung_park/CycleGAN/datasets/).

## Features
- Implements the CycleGAN architecture using PyTorch.
- Trains the model for 60 epochs on the horse2zebra dataset.
- Achieves results comparable to those in the original paper for this dataset.

## References
- [CycleGAN with PyTorch - Towards Data Science](https://towardsdatascience.com/cycle-gan-with-pytorch-ebe5db947a99)
- [Official PyTorch Implementation of CycleGAN and Pix2Pix](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix)
- [Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks (Paper)](https://arxiv.org/abs/1703.10593)