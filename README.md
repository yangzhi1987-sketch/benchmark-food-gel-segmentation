# benchmark-food-gel-segmentation
Benchmarking Deep Learning Models for Confocal Micrograph Segmentation of Protein Networks
Overview

This repository contains the code, data organization, model configurations, and analysis workflows for our benchmark study on deep learning–based segmentation of confocal laser scanning microscopy (CLSM) images of protein gel networks. The goal of this work is to systematically compare multiple segmentation architectures for their ability to reproduce not only pixel-level masks, but also structurally meaningful descriptors relevant to food microstructure analysis.

In addition to conventional image segmentation metrics such as Dice, IoU, and RMSE, this benchmark evaluates the agreement between model-predicted masks and ground-truth masks in terms of extracted structural descriptors, including:

Protein area fraction

Fractal dimension

Lacunarity

Betti-0

Betti-1

Euler number

This framework is designed to support reproducible comparison of segmentation models for food micrographs and to help identify architectures that best preserve physically meaningful structural information.

Benchmark Scope

The benchmark includes representative encoder–decoder segmentation models commonly used in biomedical and scientific image analysis, such as:

U-Net

U-Net++

FPN

DeepLabV3+

LinkNet

MAnet

Backbones can be adapted depending on the study design (for example, ResNet34, EfficientNet-B0).

Project Objectives

The main objectives of this benchmark are to:

Compare segmentation performance across state-of-the-art deep learning architectures.

Evaluate whether strong pixel-level performance translates into reliable structural descriptor prediction.

Identify models that best preserve protein-network morphology in confocal micrographs.

Establish a reproducible workflow for segmentation benchmarking in food microstructure research.
