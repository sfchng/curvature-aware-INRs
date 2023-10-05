# Curvature-Aware Training for Coordinate Networks
### [Paper](https://arxiv.org/abs/2305.08552)
[![Open Demo in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1PYSs4UCOVHn2A5qze61WzgGTY9uuwMsT?authuser=2#scrollTo=Jozp8Gv2HWuy)<br>

[Shin-Fang Chng](https://sfchng.github.io)\*<sup>1</sup>,
[Hemanth Saratchandran]()\*<sup>1</sup>,
[Sameera Ramasinghe]()<sup>2</sup>,
[Lachlan MacDonald]()<sup>1</sup>,
[Simon Lucey]()<sup>1</sup>,
<sup>1</sup>Australian Institute for Machine Learning (AIML), University of Adelaide, <sup>2</sup>Amazon 
<sup>*</sup>denotes equal contribution


## Abstract
<img src="misc/gradient.png" width="800" height="250">

Coordinate networks are widely used in computer vision due to their ability to represent signals as compressed, continuous entities. However, training these networks with first-order optimizers can be slow, hindering their use in real-time applications. Recent works have opted for shallow voxel-based representations to achieve faster training, but this sacrifices memory efficiency. This work proposes a solution that leverages second-order optimization methods to significantly reduce training times for coordinate networks while maintaining their compressibility. Experiments demonstrate the effectiveness of this approach on various signal modalities, such as audio, images, videos, shape and neural radiance fields (NeRF).

## Code
We provide a [demo IPython notebook](https://colab.research.google.com/drive/1PYSs4UCOVHn2A5qze61WzgGTY9uuwMsT?authuser=2#scrollTo=Jozp8Gv2HWuy) as a simple reference for the core idea. 

## TODOs
- [x] provide demo
- [ ] python scripts for other modalities
- [ ] hessian analysis



