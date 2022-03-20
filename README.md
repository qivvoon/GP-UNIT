# GP-UNIT - Official PyTorch Implementation

<img src="https://raw.githubusercontent.com/williamyang1991/GP-UNIT/main/doc_images/results.jpg" width="96%" height="96%">

This repository provides the official PyTorch implementation for the following paper:

**Unsupervised Image-to-Image Translation with Generative Prior**<br>
[Shuai Yang](https://williamyang1991.github.io/), [Liming Jiang](https://liming-jiang.com/), [Ziwei Liu](https://liuziwei7.github.io/) and [Chen Change Loy](https://www.mmlab-ntu.com/person/ccloy/)<br>
In CVPR 2022.<br>
[**Project Page**](https://www.mmlab-ntu.com/project/gpunit/) | [**Paper**]() (coming soon)
> **Abstract:** *Unsupervised image-to-image translation aims to learn the translation between two visual domains without paired data. Despite the recent progress in image translation models, it remains challenging to build mappings between complex domains with drastic visual discrepancies. In this work, we present a novel framework, Generative Prior-guided UNsupervised Image-to-image Translation (GP-UNIT), to improve the overall quality and applicability of the translation algorithm. Our key insight is to leverage the generative prior from pre-trained class-conditional GANs (e.g., BigGAN) to learn rich content correspondences across various domains. We propose a novel coarse-to-fine scheme: we first distill the generative prior to capture a robust coarse-level content representation that can link objects at an abstract semantic level, based on which fine-level content features are adaptively learned for more accurate multi-level content correspondences. Extensive experiments demonstrate the superiority of our versatile framework over state-of-the-art methods in robust, high-quality and diversified translations, even for challenging and distant domains.*

<img src="https://raw.githubusercontent.com/williamyang1991/williamyang1991.github.io/master/images/project/CVPR2022.jpg" width="96%" height="96%">

## Updates

- [03/2022] This website is created.

## Code

- We are cleaning our code. Coming soon. 

## Results

#### Male-to-Female: close domains

![male2female](./doc_images/5.gif)

#### Dog-to-Cat: related domains 

![cat2dog](./doc_images/3.gif)

#### Dog-to-Human and Bird-to-Dog: distant domains  

![dog2human](./doc_images/4.gif)

![bird2dog](./doc_images/2.gif)

#### Bird-to-Car: extremely distant domains for stress testing

![bird2car](./doc_images/1.gif)

## Citation

If you find this work useful for your research, please consider citing our paper:

```bibtex
@inproceedings{yang2022Unsupervised,
  title={Unsupervised Image-to-Image Translation with Generative Prior},
  author={Yang, Shuai and Jiang, Liming and Liu, Ziwei and Loy, Chen Change},
  booktitle={CVPR},
  year={2022}
}
```

## Acknowledgments

The code is developed based on [StarGAN v2](https://github.com/clovaai/stargan-v2) and [Imaginaire](https://github.com/nvlabs/imaginaire).
