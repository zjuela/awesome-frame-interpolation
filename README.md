# Progress on Frame Interpolation and Extrapolation

A curated list of recent frame-interpolation work and resources.

## Contributing
Please feel free to [pull requests](https://github.com/zjuela/awesome-frame-interpolation/pulls) to add papers.


## Table of Contents
- [Category](#category)
- [Papers](#papers)
  - [Frame Interpolation](#frame-interpolation)
  - [Frame Extrapolation](#frame-extrapolation)
- [Software](#software)
- [Blogs](#blogs)

## Category

| Methods | Optical-flow-based | Convolution-based | Synthesis-based | End-to-end | GAN |
|---------|:------------------:|:-----------------:|:---------------:|:----------:|:---:|
|   [PBFI](#frame-interpolation)  |:heavy_check_mark:|                  |                  |                  |                  |
|   [FIAC](#frame-interpolation)  |                  |:heavy_check_mark:|                  |:heavy_check_mark:|                  |
|  [FIASC](#frame-interpolation)  |                  |:heavy_check_mark:|                  |:heavy_check_mark:|                  |
|  [VETOF](#frame-interpolation)  |                  |:heavy_check_mark:|                  |:heavy_check_mark:|                  |
|   [DFN](#frame-extrapolation)   |                  |:heavy_check_mark:|                  |                  |                  |
|  [FSCCN](#frame-extrapolation)  |                  |:heavy_check_mark:|                  |                  |                  |
|   [ULPI](#frame-extrapolation)  |                  |                  |                  |                  |                  |
|  [DMGVP](#frame-extrapolation)  |:heavy_check_mark:|                  |                  |                  |:heavy_check_mark:|

## Papers

### Frame Interpolation
* Phase-Based Frame Interpolation for Video (PBFI)
  * Simone Meyer, Oliver Wang, Henning Zimmer, Max Grosse and Alexander Sorkine-Hornung, CVPR 2015.
  * [[Paper](http://www.ahornung.net/files/pub/2015-cvpr-phase-meyer.pdf)] [[Third-party code](https://github.com/owang/PhaseBasedInterpolation)]

* Video Frame Interpolation via Adaptive Convolution (FIAC)
  * Simon Niklaus, Long Mai and Feng Liu, CVPR 2017.
  * [[Paper](http://web.cecs.pdx.edu/~fliu/papers/cvpr2017-interp.pdf)] [[Web](http://web.cecs.pdx.edu/~fliu/project/adaconv/)]

* Video Frame Interpolation via Adaptive Separable Convolution (FIASC)
  * Simon Niklaus, Long Mai and Feng Liu, ICCV 2017.
  * [[Paper](http://web.cecs.pdx.edu/~fliu/papers/iccv2017-interp.pdf)] [[Code](https://github.com/sniklaus/pytorch-sepconv)] [[Web](http://web.cecs.pdx.edu/~fliu/project/sepconv/)]

* Video Enhancement with Task-Oriented Flow (VETOF)
  * Tianfan Xue, Baian Chen, Jiajun Wu, Donglai Wei and William T. Freeman, Arxiv 2017.
  * [[Paper](https://arxiv.org/pdf/1711.09078.pdf)]


### Frame Extrapolation
* Dynamic filter networks (DFN)
  * Bert De Brabandere, Xu Jia, Tinne Tuytelaars and Luc Van Gool, NIPS 2016.
  * [[Paper](https://papers.nips.cc/paper/6578-dynamic-filter-networks.pdf)] [[Code](https://github.com/dbbert/dfn)]

* Visual Dynamics: Probabilistic Future Frame Synthesis via Cross Convolutional Networks (FSCCN)
  * Tianfan Xue, Jiajun Wu, Katherine L Bouman and William T Freeman, NIPS 2016
  * [[Paper](http://visualdynamics.csail.mit.edu/visualDynamics16.pdf)] [[Code](https://github.com/tfxue/visual-dynamics)] [[Web](http://visualdynamics.csail.mit.edu/)]

* Unsupervised learning for physical interaction through video prediction (ULPI)
  * Chelsea Finn, Ian Goodfellow and Sergey Levine, NIPS 2016
  * [[Paper](https://arxiv.org/pdf/1605.07157.pdf)]

* Dual Motion GAN for Future-Flow Embedded Video Prediction (DMGVP)
  * Xiaodan Liang, Lisa Lee, Wei Dai and Eric P. Xing, ICCV 2017
  * [[Paper](https://arxiv.org/pdf/1708.00284.pdf)]



## Software

* [Butterflow](https://github.com/dthpham/butterflow)