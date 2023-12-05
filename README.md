# DehazeNeRF

Official repository for DehazeNeRF: Multiple Image Haze Removal and 3D Shape Reconstruction
using Neural Radiance Fields\
Wei-Ting Chen, Wang Yifan, Sy-Yen Kuo, Gordon Wetzstein\
3DV 2024

[Project Page](https://ccnguyen.github.io/diffusion-in-the-dark/) | [Paper](https://arxiv.org/pdf/2303.11364.pdf)

[![arXiv](https://img.shields.io/badge/arXiv-2303.04291-b31b1b.svg)](https://arxiv.org/pdf/2303.11364.pdf)

## Updates
- 10/15/23: ✨ DehazeNeRF was accepted into 3DV!


## Setup
You can use the following to set up a Conda environment.\

```

```
Download our pretrained model [HERE](). Put the pretrained model in a `runs` folder.

We put the datasets into a folder outside of the repo to create the following file structure
```python

```

### Synthetic Dataset in DehazeNeRF downloaded from [here]()
File structure should be as follows:
```python

```

### Real Capture Dataset in DehazeNeRF downloaded from [here]()
File structure should be as follows:
```python

```


## Usage
```

```



To test:
```
```


## Reference
If you find this work useful, please consider citing us!
```python
@inproceedings{chen2024dehazenerf,
  title={Dehazenerf: Multiple image haze removal and 3d shape reconstruction using neural radiance fields},
  author={Chen, Wei-Ting and Yifan, Wang and Kuo, Sy-Yen and Wetzstein, Gordon},
  journal={3DV},
  year={2024}
}
```


## Acknowledgements
We thank the authors of [NeuS](https://lingjie0206.github.io/papers/NeuS/) from which our repo is based off of.
