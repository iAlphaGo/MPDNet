# MPDNet:  Multi-Prior Guided Diffusion Network for Underwater Image Enhancement

San Zhang, Qianwen Ding, Manli Zhou, Yuhang Ma, Shiliang Zhou,shuying Li

## Abstract
This repository contains the implementation code of MPDNet. MPDNet proposes a completely new underwater image enhancement framework. By jointly guiding the diffusion model with physical, color and frequency priors, it effectively addresses the color distortion, detail blurring and noise interference problems existing in underwater images.

## This codebase was tested with the following environment configurations. It may work with other versions.

- PyTorch  1.11.0
- Python  3.8(ubuntu20.04)
- CUDA  11.3

## Preparing datasets
1. EUVP U60:[data](https://li-chongyi.github.io/proj_benchmark.html)
2. UIEB:[data](https://github.com/JJsnowx/EUVP_Dataset/tree/main/EUVP%20Dataset)
3. SUIM:[data](https://github.com/trentqq/SUIM-E)
4. U45:[data](https://github.com/IPNUISTlegal/underwater-test-dataset-U45-/tree/master/upload/U45)

## Training / Testing
To make use of the [main.py](https://github.com/iAlphaGo/MPDNet/blob/main/main.py)

## Contact
Should you have any question, please contact <dingqianwen@stu.xupt.edu.cn>
