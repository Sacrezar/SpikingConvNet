# SpikingConvNet

Implementation of the paper *STDP-based spiking deep neural networks for object recognition*, for the MNIST classification task.
```
@article{KHERADPISHEH201856,
title = {STDP-based spiking deep convolutional neural networks for object recognition},
journal = {Neural Networks},
volume = {99},
pages = {56-67},
year = {2018},
issn = {0893-6080},
doi = {https://doi.org/10.1016/j.neunet.2017.12.005},
url = {https://www.sciencedirect.com/science/article/pii/S0893608017302903},
author = {Saeed Reza Kheradpisheh and Mohammad Ganjtabesh and Simon J. Thorpe and Timothée Masquelier},
keywords = {Spiking neural network, STDP, Deep learning, Object recognition, Temporal coding},
}
```

**This repository is a fork from [SpikingConvNet](https://github.com/ggoupy/SpikingConvNet)**

## Installation

- Download [MNIST Dataset](https://data.deepai.org/mnist.zip) and add it to MNIST folder after having uncompressed it. You should have files like `train-labels-idx1-ubyte`

- Create a virtual environment and install requirements:
```sh
# WINDOWS
py -m pip virtualenv .env
.env/Script/activate.ps1
pip install -r requirements.txt

# LINUX
virtualenv .env
source .env/bin/activate
pip install -r requirements.txt
```

- Launch `snn.py`

## References:

[1] Kheradpisheh, S.R., et al. STDP-based spiking deep neural networks for object recognition. arXiv:1611.01421v1 (Nov, 2016)
  
[2] Mozafari, M., Ganjtabesh, M., Nowzari-Dalini, A., & Masquelier, T. (2019). SpykeTorch: Efficient Simulation of Convolutional Spiking Neural Networks With at Most One Spike per Neuron. Frontiers in Neuroscience (https://doi.org/10.3389/fnins.2019.00625).
   
[3] https://github.com/npvoid/SDNN_python
