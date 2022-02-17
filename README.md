# UDA-pytorch
An unofficial PyTorch implementation of [Unsupervised Data Augmentation for Consistency Training](https://arxiv.org/abs/1904.12848) (UDA).
The official Tensorflow implementation is [here](https://github.com/google-research/uda).

This code is only available in UDA for image classifications.


## Results

|  | CIFAR-10-4K | SVHN-1K |
|:---:|:---:|:---:|
| Paper (WRN-28-2) | 95.68 ± 0.08 | 97.77 ± 0.07 |
| This code (WRN-28-2) | - | - |
| Acc. curve | - | - |

\* This code has not been tested, but only part of [my FixMatch code](https://github.com/kekmodel/FixMatch-pytorch) that has been tested several times has been modified.

## Requirements
- python 3.6+
- torch 1.4
- torchvision 0.5
- tensorboard
- numpy
- tqdm
- apex (optional)


## Citations
```
@article{xie2019unsupervised,
  title={Unsupervised Data Augmentation for Consistency Training},
  author={Xie, Qizhe and Dai, Zihang and Hovy, Eduard and Luong, Minh-Thang and Le, Quoc V},
  journal={arXiv preprint arXiv:1904.12848},
  year={2019}
}

@article{cubuk2019randaugment,
  title={RandAugment: Practical data augmentation with no separate search},
  author={Cubuk, Ekin D and Zoph, Barret and Shlens, Jonathon and Le, Quoc V},
  journal={arXiv preprint arXiv:1909.13719},
  year={2019}
}
```
