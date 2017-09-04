# CNNGeometric PyTorch implementation

![](http://www.di.ens.fr/willow/research/cnngeometric/images/teaser.png)

This is the implementation of the paper: 

I. Rocco, R. Arandjelović and J. Sivic. Convolutional neural network architecture for geometric matching. CVPR 2017 [[website](http://www.di.ens.fr/willow/research/cnngeometric/)][[arXiv](https://arxiv.org/abs/1703.05593)]

using PyTorch ([for MatConvNet implementation click here](https://github.com/ignacio-rocco/cnngeometric_matconvnet)).

If you use this code in your project, please cite use using:
````
@InProceedings{Rocco17,
  author       = "Rocco, I. and Arandjelovi\'c, R. and Sivic, J.",
  title        = "Convolutional neural network architecture for geometric matching",
  booktitle    = "Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition",
  year         = "2017",
}
````

### Dependencies ###
  - Python 3
  - pytorch, torchvision
  - numpy, skimage (included in conda)

### Getting started ###
  - demo.py demonstrates the results on the ProposalFlow dataset
  - train.py is the main training script. For some standard training options, see scripts folder
  - eval_pf.py evaluates on the ProposalFlow dataset