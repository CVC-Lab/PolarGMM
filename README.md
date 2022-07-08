# PolarGMM Datasets

This repository contains the 6 datasets used in our PolarGMM work ([arXiv](https://arxiv.org/abs/2206.12959)). This [download link](https://drive.google.com/drive/folders/1ORgyWZfCH86blWRNCuRSRO7w1CrqMHc5?usp=sharing) will be active only temporarily.

Directory names corresponds to those in the paper:
- `70s`: 70S, EMD-0406
- `70s-t2`: 70S-T, EMD-0406 with random planar translation
- `beta-g`: Bgal
- `beta-g-t2`: Bgal-T
- `t20`: T20, EMD-5623
- `t20-t2`: T20-T, EMD-5623

Each directory contains `2 * 10000 + 2` files.
- `*.mrc`: actual dataset images
- `*.png`: preview images
- `*_metadata.json`: transformations (orientation, planar rotation, planar translation) from original model to images and other internal metadata for our script
- `*.cfg`: list of paths for our script

Please contact either of the authors for any comments or questions. If you find this work useful, please consider citing.

```
@misc{https://doi.org/10.48550/arxiv.2206.12959,
  doi = {10.48550/ARXIV.2206.12959},
  url = {https://arxiv.org/abs/2206.12959},
  author = {Chockchowwat, Supawit and Bajaj, Chandrajit L.},
  keywords = {Computer Vision and Pattern Recognition (cs.CV), Computational Engineering, Finance, and Science (cs.CE), Machine Learning (cs.LG), FOS: Computer and information sciences, FOS: Computer and information sciences},
  title = {Probabilistic PolarGMM: Unsupervised Cluster Learning of Very Noisy Projection Images of Unknown Pose},
  publisher = {arXiv},
  year = {2022},
  copyright = {arXiv.org perpetual, non-exclusive license}
}
```
