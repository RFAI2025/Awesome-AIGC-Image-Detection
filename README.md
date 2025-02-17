# Awesome-AIGC-Image-Detection [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)  
![](1739449670179.jpg)

Photographs are a means for people to document their daily experiences and are often seen as reliable sources of information. However, there is increasing concern that advancements in artificial intelligence (AI) technology could lead to the creation of fake images, potentially causing confusion and eroding trust in the authenticity of photos. The rapid advancement of AI-Generated Content (AIGC) has greatly impacted our daily lives, making the detection of such content a critical challenge for AI safety today. This is a collection list of research on AIGC image detection, intended to support progress in related areas.  

## Contents
- Datasets
- Papers
- Tools
- Others

## Datasets
|  Year   | Dataset  |  Number of Real  |  Number of Fake  |  Source of Real Image  |  Generation Method of Fake Image  |
|  ----  | ----  |  ----  | ----  |  ----  | ----  |
| 2023  | [GenImage](https://genimage-dataset.github.io/) | 1,331,167  |  1,350,000 | ImagNet | SDMs, Midjourney, BigGAN |
| 2023  | [Fake2M](https://github.com/Inf-imagine/Sentry) | -  |  2,300,000 | CC3M | SD-V1.5, IF, StyleGAN3 |
| 2024  | WildFake | 2,557,278  | 1,013,446 | ImagNet, Laion, Wukong, COO...  | BigGAN, StyleGAN, StarGAN, Midjourney, DALLE... |

## Papers
<details open>
  <summary>2025</summary>

  - [**KDD '25**] Improving Synthetic Image Detection Towards Generalization: An Image Transformation Perspective [[Paper](https://arxiv.org/pdf/2408.06741)][[Code](https://github.com/Ouxiang-Li/SAFE)]
  - [**arxiv**] TextureCrop: Enhancing Synthetic Image Detection through Texture-based Cropping [[Paper](https://arxiv.org/pdf/2407.15500)]
</details>

<details open>
  <summary>2024</summary>
  
  - [**CVPR '24**] Forgery-aware Adaptive Transformer for Generalizable Synthetic [[Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Liu_Forgery-aware_Adaptive_Transformer_for_Generalizable_Synthetic_Image_Detection_CVPR_2024_paper.pdf)][[Code](https://github.com/Michel-liu/FatFormer?tab=readme-ov-file)]
  - [**ECCV '24**] Zero-Shot Detection of AI-Generated Images [[Paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/02665.pdf)][[Code](https://github.com/grip-unina/ZED/)]
  - [**ECCV '24**] Leveraging Representations from Intermediate Encoder-blocks for Synthetic Image Detection [[Paper](https://arxiv.org/pdf/2402.19091)][[Code](https://github.com/mever-team/rine/tree/main?tab=readme-ov-file)]
  - [**ECCV '24**] Contrasting Deepfakes Diffusion via Contrastive Learning and Global-Local Similarities [[Paper](https://arxiv.org/pdf/2407.20337)][[Code](https://github.com/aimagelab/CoDE)]
  - [**CVPRW' 24**] Raising the Bar of AI-generated Image Detection with CLIP [[Paper](https://openaccess.thecvf.com/content/CVPR2024W/WMF/papers/Cozzolino_Raising_the_Bar_of_AI-generated_Image_Detection_with_CLIP_CVPRW_2024_paper.pdf)][[Code](https://github.com/grip-unina/ClipBased-SyntheticImageDetection/)]
  - [**arxiv**] Mixture of Low-rank Experts for Transferable AI-Generated Image Detection [[Paper](https://arxiv.org/pdf/2404.04883)][[Code](https://github.com/zhliuworks/CLIPMoLE)]
  - [**arxiv**] Guided and Fused: Efficient Frozen CLIP-ViT with Feature Guidance and Multi-Stage Feature Fusion for Generalizable Deepfake Detection [[Paper](https://arxiv.org/pdf/2408.13697)]
</details>

<details open>
  <summary>2023</summary>

  - [**CVPR '23**] Towards Universal Fake Image Detectors that Generalize Across Generative Models [[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Ojha_Towards_Universal_Fake_Image_Detectors_That_Generalize_Across_Generative_Models_CVPR_2023_paper.pdf)][[Code](https://github.com/WisconsinAIVision/UniversalFakeDetect)]
  - [**CVPR '23**] Learning on Gradients: Generalized Artifacts Representation for GAN-Generated Images Detection [[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Tan_Learning_on_Gradients_Generalized_Artifacts_Representation_for_GAN-Generated_Images_Detection_CVPR_2023_paper.pdf)][[Code](https://github.com/chuangchuangtan/LGrad)]
  - [**ICCV '23**] DIRE for Diffusion-Generated Image Detection [[Paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Wang_DIRE_for_Diffusion-Generated_Image_Detection_ICCV_2023_paper.pdf)][[Code](https://github.com/ZhendongWang6/DIRE)]
  - [**NeurIPS' 23**] Seeing is not always believing: Benchmarking Human and Model Perception of AI-Generated Images [[Paper](https://arxiv.org/pdf/2304.13023)][[Code](https://github.com/Inf-imagine/Sentry)]
  - [**ICCVW '2023**] Online Detection of AI-Generated Images [[Paper](https://openaccess.thecvf.com/content/ICCV2023W/DFAD/papers/Epstein_Online_Detection_of_AI-Generated_Images__ICCVW_2023_paper.pdf)]
  - [**arxiv**] PatchCraft: Exploring Texture Patch for Efficient AI-generated Image Detection [[Paper](https://arxiv.org/pdf/2311.12397v3)]
</details>
