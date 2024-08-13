---
#layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

# Controllable Lesion Image Synthesis

Scaling law is widely deemed as the cornerstone towards medical foundation models. However, the collection of sufficient training data, particularly those related to lesions, may remain an unattainable objective in clinical practice. 
We utilize generative models to disentangle the attributes of lesions across the domains of radiology and pathology, thereby creating extensive and diverse annotated lesion data in a controllable manner.
This not only facilitates the training of medical AI but also serves as a robustness assessment benchmark, and potentially acts as a medical education tool.

> ## *Chest X-ray Lung Nodule Synthesis for Lung Nodule Detection*
> - We proposed a lung nodule synthesis framework disentangles nodule attributes (i.e., shape, size, and texture) and synthesize nodules in a controllable manner. We leveraged the controllability of the framework to design a hard example mining strategy for data augmentation on lung nodule detection.
> ### *Relevant Publications:*
> - <a href="https://www.sciencedirect.com/science/article/abs/pii/S136184152200336X" target="_blank">Image Synthesis with Disentangled Attributes for Chest X-ray Nodule Augmentation and Detection</a> [MedIA'23]
> - <a href="https://link.springer.com/chapter/10.1007/978-3-030-88010-1_45" target="_blank">Nodule Synthesis and Selection for Augmenting Chest X-ray Nodule Detection</a> [PRCV'21]
> ![](/images/nodule_synthesis.png)

> ## *Cervical Cytological Image Synthesis for Cervical Lesion Screening*
> - We proposed CellGAN, a class-conditional GAN, to synthesize cervical cytological image patches of various cervical cell types, aimed at enhancing patch-level cervical cell classification. 
> - We incorporated CellGAN into a knowledge distillation framework for multi-class abnormal cervical cell detection, which facilitates the class-balance pre-training of a teacher network.
> ### *Relevant Publications:*
> - <a href="https://link.springer.com/chapter/10.1007/978-3-031-43987-2_47" target="_blank">CellGAN: Conditional Cervical Cell Synthesis for Augmenting Cytopathological Image Classification</a> [MICCAI'23 Early Accept]
> - <a href="https://www.sciencedirect.com/science/article/abs/pii/S0893608024003290" target="_blank">Distillation of Multi-class Cervical Lesion Cell Detection via Synthesis-aided Pre-training and Patch-level Feature Alignment</a> [Neural Networks'24]
> ![](/images/cell_synthesis.png)


# Cross-Modality Medical Image Synthesis 

Multi-modal medical imaging information is the cornerstone of precision medicine, yet a common challenge is the unavailability of some imaging modalities in clinical practice.
Cross-modality image synthesis can impute target modality images from source modality images, which serves as a beneficial tool in multi-modal studies. 
The correlation established between the two modalities can be also leveraged for applications such as anomaly detection.

> ## *PET Anomaly Detection for Parkinson’s Disease (PD) Diagnosis*
> - We propose a Metabolism-aware Anomaly Detection (MetaAD) framework, which leverages a cyclic cross-modality image translation workflow to identify abnormal metabolism cues of PD in <sup>18</sup>F-FDG PET scans.
> ### *Relevant Publications:*
> - <a href="" target="_blank">MetaAD: Metabolism-Aware Anomaly Detection for Parkinson’s Disease in 3D <sup>18</sup>F-FDG PET</a> [MICCAI'24 Early Accept]
> ![](/images/metaAD.png)


# Medical Image Super-Resolution

3D medical images like MRI are typically acquired using 2D scanning protocols, resulting in high in-plane resolution yet compromised through-plane resolution.
Super-resolution can reduce the inter-slice spacing of 2D scanned volumes, thereby facilitating downstream visualization and computer-aided diagnosis. 

> ## *MRI Super-resolution for Arbitrary Inter-slice Spacing Reduction*
> - We proposed Hierarchical Feature Conditional Diffusion (HiFi-Diff) for arbitrary reduction of MR inter-slice spacing, which generates any desired in-between MR slice from hierarchical features of adjacent MR slices.
> - We proposed Spatial Attention-based Implicit Neural Representation (SA-INR) network, which represents an MR image as a continuous implicit function of 3D coordinates and performs arbitrary inter-slice spacing by sampling feature representations at arbitrary locations in 3D space.
> ### *Relevant Publications:*
> - <a href="https://link.springer.com/chapter/10.1007/978-3-031-45673-2_3" target="_blank">Arbitrary Reduction of MRI Inter-slice Spacing Using Hierarchical Feature Conditional Diffusion</a> [MLMI'23]
> - <a href="https://www.sciencedirect.com/science/article/pii/S1361841524000835" target="_blank">Spatial Attention-based Implicit Neural Representation for Arbitrary Reduction of MRI Slice Spacing</a> [MedIA'24]
> ![](/images/MRI_SR.png)
