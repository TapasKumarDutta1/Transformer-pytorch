# Transformer-Based Architectures in Deep Learning

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

This repository provides implementations of various Transformer-based architectures for deep learning. Additionally, this README outlines the current status of the project and suggests future work to be done.

## Table of Contents

- [Introduction](#introduction)
- [Implemented Architectures](#implemented-architectures)
  - [Vision Transformer (ViT)](#vision-transformer-vit)
  - [Detection Transformer (DETR)](#detection-transformer-detr)
  - [Attention Is All You Need (Transformer Architecture)](#attention-is-all-you-need-transformer-architecture)
- [Citation](#Citation)

## Introduction

Transformers have revolutionized various fields in deep learning, including natural language processing and computer vision. These models are known for their parallelizable and scalable nature, making them highly effective for various tasks. This repository explores the implementation of Transformer-based architectures in deep learning, primarily focusing on Vision Transformers (ViT) and Detection Transformers (Detr).

## Implemented Architectures

### Vision Transformer (ViT)

The Vision Transformer (ViT) is a novel architecture that applies the Transformer model to computer vision tasks, such as image classification. In this repository, you can find an implementation of the ViT model.

### Detection Transformer (DETR)

The Detection Transformer (Detr) is a Transformer-based architecture designed for object detection tasks. It combines the power of Transformers with object detection, making it efficient and accurate. This repository includes an implementation of Detr, complete with pre-trained models and utilities for object detection tasks.

### Attention Is All You Need (Transformer Architecture)

"Attention Is All You Need" introduced a groundbreaking Transformer architecture pivotal in natural language processing (NLP). This repository houses an implementation of the Transformer model, enabling users to explore and utilize this transformative architecture in NLP tasks.


## Citation

```markdown
@article{dosovitskiy2020vit,
  title={An Image Is Worth 16x16 Words: Transformers for Image Recognition},
  author={Dosovitskiy, Alexey and Beyer, Lucas and Kolesnikov, Alexander and Weissenborn, Dirk and Zhai, Xiaohua and Unterthiner, Thomas and Dehghani, Mostafa and Minderer, Matthias and Heigold, Georg and Gelly, Sylvain and Uszkoreit, Jakob and Houlsby, Neil},
  journal={arXiv preprint arXiv:2010.11929},
  year={2020}
}

@misc{vaswani2023attention,
      title={Attention Is All You Need}, 
      author={Ashish Vaswani and Noam Shazeer and Niki Parmar and Jakob Uszkoreit and Llion Jones and Aidan N. Gomez and Lukasz Kaiser and Illia Polosukhin},
      year={2023},
      eprint={1706.03762},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}

@inproceedings{carion2020end,
  title={End-to-end object detection with transformers},
  author={Carion, Nicolas and Massa, Francisco and Synnaeve, Gabriel and Usunier, Nicolas and Kirillov, Alexander and Zagoruyko, Sergey},
  booktitle={European conference on computer vision},
  pages={213--229},
  year={2020},
  organization={Springer}
}


