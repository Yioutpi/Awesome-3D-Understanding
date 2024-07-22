# Awesome-3D-Understanding

Table of Contents
- Awesome Papers
  - 3D Scene Understanding
  - Open-Vocabulary Indoor Scene Understanding
  - 3D Vision Grounding
  - 3D Multimodal LLMs
- Awesome Datasets
  - Basic Indoor Scenes
  - Basic Outdor Scenes
  - Language-assitant Tasks
  - Datasets of Multimodal Instruction Tuning

<!-- ## 3D Perception and Understanding -->
## Awesome Papers

### Open-Vocabulary Indoor Scene Understanding
|  Title  |   Venue  |   Date   |   Code   |   Demo   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![Star](https://img.shields.io/github/stars/Wang-pengfei/GGSD.svg?style=social&label=Star) <br> [**Open Vocabulary 3D Scene Understanding via Geometry Guided Self-Distillation**](https://arxiv.org/pdf/2407.13362) | ECCV | 2024-07-18 | [Github](https://github.com/Wang-pengfei/GGSD) | - |
| ![Star](https://img.shields.io/github/stars/lslrh/DMA.svg?style=social&label=Star) <br> [**Dense Multimodal Alignment for Open-Vocabulary 3D Scene Understanding**](https://arxiv.org/pdf/2407.09781) | ECCV | 2024-07-13 | [Github](https://github.com/lslrh/DMA) | - |


### 3D Scene Understanding
|  Title  |   Venue  |   Date   |   Code   |   Demo   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![Star](https://img.shields.io/github/stars/dk-liang/UniSeg3D?style=social&label=Star) <br> [**A Unified Framework for 3D Scene Understanding**](https://arxiv.org/pdf/2407.03263) | Arxiv | 2024-07-03 | [Github](https://github.com/dk-liang/UniSeg3D) | - |
| [**Self-supervised Pre-training with Masked Shape Prediction for 3D Scene Understanding**](https://arxiv.org/pdf/2407.03263) | CVPR | 2023 | - | - |


### 3D Vision Grounding
|  Title  |   Venue  |   Date   |   Code   |   Demo   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![Star](https://img.shields.io/github/stars/qzp2018/MCLN?style=social&label=Star) <br> [**Multi-branch Collaborative Learning Network for 3D Visual Grounding**](https://arxiv.org/abs/2407.05363) | ECCV | 2024-07-10 | [Github](https://github.com/qzp2018/MCLN) | - |


### 3D Multimodal LLMs
|  Title  |   Venue  |   Date   |   Code   |   Demo   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![Star](https://img.shields.io/github/stars/Ivan-Tang-3D/Any2Point?style=social&label=Star) <br> [**Any2Point: Empowering Any-modality Large Models for Efficient 3D Understanding**](https://arxiv.org/pdf/2404.07989) | ECCV | 2024-04-31 | [Github](https://github.com/Ivan-Tang-3D/Any2Point) | - |


### Object-level
- PointLLM: Empowering Large Language Models to Understand Point Clouds [[Paper]](https://arxiv.org/abs/2308.16911) [[Homepage]](https://runsenxu.com/projects/PointLLM/) [[Github]](https://github.com/OpenRobotLab/PointLLM)
- Point-Bind & Point-LLM: Aligning Point Cloud with Multi-modality for 3D Understanding, Generation, and Instruction Following [[Paper]](https://arxiv.org/abs/2309.00615) [[Demo]](http://imagebind-llm.opengvlab.com/) [[Github]](https://github.com/ZiyuGuo99/Point-Bind_Point-LLM)

### Scenes-level
- 3D-LLM: Injecting the 3D World into Large Language Models (NeurIPS2023 Spotlight) (10TB Object data)[[Paper]](https://arxiv.org/pdf/2307.12981.pdf) [[Homepage]](https://vis-www.cs.umass.edu/3dllm/) [[Github]](https://github.com/UMass-Foundation-Model/3D-LLM)
- LL3DA: Visual Interactive Instruction Tuning for Omni-3D Understanding, Reasoning, and Planning[[Paper]](https://arxiv.org/pdf/2311.18651v1.pdf) [[Homepage]](https://ll3da.github.io/) [[Github]](https://github.com/Open3DA/LL3DA)
- AN EMBODIED GENERALIST AGENT IN 3D WORLD[[Paper]](http://arxiv.org/abs/2311.12871) [[Homepage]](https://embodied-generalist.github.io/) [[Github]](https://github.com/embodied-generalist/embodied-generalist)
- M3DBench: Let’s Instruct Large Models with Multi-modal 3D Prompts[[Paper]](http://arxiv.org/abs/2312.10763) [[Homepage]](https://m3dbench.github.io/)
- EmbodiedScan: A Holistic Multi-Modal 3D Perception Suite Towards Embodied AI [[Paper]](http://arxiv.org/abs/2312.16170) [[Homepage]](https://tai-wang.github.io/embodiedscan/)
- ODIN: A Single Model for 2D and 3D Perception[[Paper]](http://arxiv.org/abs/2401.02416) [[Homepage]](https://odin-seg.github.io/)


## 3D With CLIP

- ULIP: Learning a Unified Representation of Language, Images, and Point Clouds for 3D Understanding [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Gao_ULIP_Learning_a_Unified_Representation_of_Language_Images_and_Point_CVPR_2023_paper.html) [[Github]](https://github.com/salesforce/ULIP)
- ULIP-2: Towards Scalable Multimodal Pre-training for 3D Understanding [[Paper]](https://arxiv.org/abs/2305.08275) [[Github]](https://github.com/salesforce/ULIP)
- OpenShape: Scaling Up 3D Shape Representation Towards Open-World Understanding [[Paper]](http://arxiv.org/abs/2305.10764) [[Github]](https://github.com/Colin97/OpenShape_code) [[Homepage]](https://colin97.github.io/OpenShape/)
- CLIP <sup>2</sup> : Contrastive Language-Image-Point Pretraining from Real-World Point Cloud Data [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Zeng_CLIP2_Contrastive_Language-Image-Point_Pretraining_From_Real-World_Point_Cloud_Data_CVPR_2023_paper.html) [[Github]]()
- CLIP Goes 3D: Leveraging Prompt Tuning for Language Grounded 3D Recognition [[Paper]](https://openaccess.thecvf.com/content/ICCV2023W/OpenSUN3D/html/Hegde_CLIP_Goes_3D_Leveraging_Prompt_Tuning_for_Language_Grounded_3D_ICCVW_2023_paper.html) [[Github]](https://github.com/deeptibhegde/CLIP-goes-3D)
- CLIP2Point: Transfer CLIP to Point Cloud Classification with Image-Depth Pre-Training [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/html/Huang_CLIP2Point_Transfer_CLIP_to_Point_Cloud_Classification_with_Image-Depth_Pre-Training_ICCV_2023_paper.html) [[Github]](https://github.com/tyhuang0428/CLIP2Point)
- Uni3D: Exploring Unified 3D Representation at Scale [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/html/Huang_CLIP2Point_Transfer_CLIP_to_Point_Cloud_Classification_with_Image-Depth_Pre-Training_ICCV_2023_paper.html) [[Github]](https://github.com/baaivision/Uni3D)
- MixCon3D: Synergizing Multi-View and Cross-Modal Contrastive Learning for Enhancing 3D Representation [[Paper]](http://arxiv.org/abs/2311.01734) [[Github]](https://github.com/baaivision/Uni3D)



## 3D-Dataset

### Object-level
- OmniObject3D (CVPR 2023 Award Candidate): real-scanned 3D objects(6K), 190 classes [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Wu_OmniObject3D_Large-Vocabulary_3D_Object_Dataset_for_Realistic_Perception_Reconstruction_and_CVPR_2023_paper.pdf) [[Homepage]](https://omniobject3d.github.io/)
- Objaverse-XL: 3D Objects(10M+) [[Paper]](https://arxiv.org/abs/2307.05663) [[Homepage]](https://objaverse.allenai.org/) [[Dataset]](https://colab.research.google.com/drive/15XpZMjrHXuky0IgBbXcsUtb_0g-XWYmN?usp=sharing)
- Cap3D: 3D-Text pairs(660K) [[Paper]](https://arxiv.org/pdf/2306.07279.pdf) [[Download]](https://huggingface.co/datasets/tiange/Cap3D)
- ULIP - Objaverse Triplets: 3D Point Clouds(800K)-Images(10M)-Language(100M) Triplets, [[Download]](https://console.cloud.google.com/storage/browser/sfr-ulip-code-release-research;tab=objects?prefix=&forceOnObjectsSortingFiltering=false&pageState=(%22StorageObjectListTable%22:(%22f%22:%22%255B%255D%22)))
- ULIP - ShapeNet Triplets: 3D Point Clouds(52.5K)-Images(3M)-Language(30M) Triplets,[[Download]](https://console.cloud.google.com/storage/browser/sfr-ulip-code-release-research;tab=objects?prefix=&forceOnObjectsSortingFiltering=false&pageState=(%22StorageObjectListTable%22:(%22f%22:%22%255B%255D%22)))

### Scene-level
- ScanRefer: 3D object localization in RGB-D scans using natural language
- SQA3D: 650 Scenes, 6.8K situations,  20.4k descriptions and 33.4k diverse reasoning questions for these situations[[Paper]](https://arxiv.org/pdf/2210.07474.pdf) [[Homepage]](https://sqa3d.github.io/)

## Survey
- Recent Advances in Multi-modal 3D Scene Understanding: A Comprehensive Survey and Evaluation [[Paper]](http://arxiv.org/abs/2310.15676)
- JM3D & JM3D-LLM: Elevating 3D Representation with Joint Multi-modal Cues [[Paper]](https://arxiv.org/abs/2310.09503)
