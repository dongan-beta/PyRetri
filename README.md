# PyRetri

## Introduction

PyRetri is an open source deep learning-based image retrieval toolbox based on PyTorch.

### Major features

- **Modular Design**

  We decompose the deep learning-based image retrieval into several stages and one can easily construct a image retrieval pipeline by combining different modules.

- **Flexible Loading**

  The toolbox is able to adapt to load several types of model parameters, including parameters with the same keys and shape, parameters with different keys, and parameters with the same keys but different shapes.

- **Support of  Multiple Methods**

  The toolbox directly supports popluar methods designed fot deep learning-based image retrieval.

- **Combinations Search Tool**

  We provide the pipeline combinations search scripts to help users to find possible combinations of approaches with various hyper-parameters. 

### Supported Methods

- **Pre-processing**
  - DirectReszie, PadResize, ShorterResize
  - CenterCrop, TenCrop
  - TwoFlip
  - ToTensor, ToCaffeTensor
  - Normalize
- **Feature Representation**
  - GAP
  - GMP
  - [R-MAC](https://arxiv.org/pdf/1511.05879.pdf)
  - [SPoC](https://arxiv.org/pdf/1510.07493.pdf)
  - [CroW](https://arxiv.org/pdf/1512.04065.pdf)
  - [SCDA](http://www.weixiushen.com/publication/tip17SCDA.pdf)
  - [GeM](https://pdfs.semanticscholar.org/a2ca/e0ed91d8a3298b3209fc7ea0a4248b914386.pdf)
  - [PWA](https://arxiv.org/abs/1705.01247)
  - [PCB](http://openaccess.thecvf.com/content_ECCV_2018/papers/Yifan_Sun_Beyond_Part_Models_ECCV_2018_paper.pdf)
- **Post-processing**
  - [SVD](https://link.springer.com/chapter/10.1007%2F978-3-662-39778-7_10)
  - [PCA](http://pzs.dstu.dp.ua/DataMining/pca/bibl/Principal%20components%20analysis.pdf)
  - [DBA](https://www.robots.ox.ac.uk/~vgg/publications/2012/Arandjelovic12/arandjelovic12.pdf)
  - [QE](https://www.robots.ox.ac.uk/~vgg/publications/papers/chum07b.pdf)
  - [K-reciprocal](https://arxiv.org/pdf/1701.08398.pdf)

## License

This project is released under the [Apache 2.0 license](https://github.com/hby96/pyretri/blob/master/LICENSE).

## Installation

Please refer to INSTALL.md for installation and dataset preparation.

## Get Started

Please see GETTING_STARTED.md for the basic usage of PyRetri.

## Model Zoo

Results and models are available in MODEL_ZOO.md.

## Citation

If you use this toolbox in your research, please cite this project.

```shell

```
