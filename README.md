# MPDNet:  Multi-Prior Guided Diffusion Network for Underwater Image Enhancement

San Zhang, Qianwen Ding, Manli Zhou, Yuhang Ma, Shiliang Zhou,shuying Li

## Abstract
Underwater images typically suffer from severe color distortion, contrast attenuation, and detail loss due to wavelength-dependent light absorption and scattering, which significantly degrades the reliability of underwater vision systems. Although recent deep learning approaches, including diffusion models, have shown strong generative capability, they generally overlook the degradation characteristics embedded in the underwater frequency domain. This omission often leads to unstable color restoration and insufficient detail reconstruction. To address above limitations, we propose a Multi-Prior Guided Diffusion Network (MPDNet), a two‑stage spatial-frequency collaborative enhancement framework that integrates a Difference of Gaussians-based Decomposition (DGD) into a multi‑prior guided diffusion model. In the frequency domain, a DGD strategy is employed to separate the degraded image into multi-scale intrinsic modes, followed by Bayesian optimization to adaptively tune enhancement parameters for color correction, detail refinement, and noise suppression. In the spatial domain, we construct a conditional diffusion model guided by a prior tensor that fuses three complementary priors: multi‑scale DGD frequency priors, physics‑based scene radiance priors, and global color statistical priors. This collaborative design leverages the complementary strengths of frequency‑domain analysis and spatial‑domain generation. Extensive experiments on multiple underwater benchmarks demonstrate that our proposed MPDNet achieves superior PSNR and SSIM compared with state‑of‑the‑art approaches, while ablation studies further verify the critical role of the multi-prior guidance mechanism and the synergy between frequency-domain analysis and spatial-domain generation.

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
To make use of the [main.py](https://github.com/iAlphaGo/VMD_diff_sea/blob/main/main.py)

## Contact
Should you have any question, please contact <dingqianwen@stu.xupt.edu.cn>
