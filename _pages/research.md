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
The correlation established between different modalities can be also leveraged for other clinical and research purposes such as anomaly detection and PET attenuation correction.

> ## *<sup>18</sup>F-FDG PET Anomaly Detection for Parkinson’s Disease (PD) Diagnosis*
> - We propose a Metabolism-aware Anomaly Detection (MetaAD) framework, which leverages a cyclic cross-modality image translation workflow to identify abnormal metabolism cues of PD in <sup>18</sup>F-FDG PET scans.
> ### *Relevant Publications:*
> - <a href="" target="_blank">MetaAD: Metabolism-Aware Anomaly Detection for Parkinson’s Disease in 3D <sup>18</sup>F-FDG PET</a> [MICCAI'24 Early Accept & Oral & Best Paper Award Nomination]
> ![](/images/metaAD.png)

<!-- > ## *<sup>18</sup>F-FDG PET to <sup>11</sup>C-CFT PET synthesis for Parkinson’s Disease (PD) Diagnosis*
> - We propose a framework that synthesizes <sup>11</sup>C-CFT PET images from real <sup>18</sup>F-FDG PET scans for automatic PD diagnosis, which was based on the correlation between dopaminergic deficiency in the striatum and increased glucose metabolism in PD patients.
> ![](/images/PET_synthesis.png) -->

> ## *Whole-body MR-to-CT Synthesis for PET Attenuation Correction*
> - We propose a whole-body MR-to-CT synthesis framework that integrates structural guidance, spatial alignment, and semantic authenticity to enhance synthetic CT image quality, thus facilitating PET attenuation correction.
> ![](/images/whole_body_MR_to_CT.png)


# Medical Image Super-Resolution

3D medical images like MRI are typically acquired using 2D scanning protocols, resulting in high in-plane resolution yet compromised through-plane resolution.
Super-resolution can reduce the inter-slice spacing of 2D scanned volumes, thereby facilitating downstream visualization and computer-aided diagnosis. 

> ## *MR Image Super-resolution for Arbitrary Inter-Slice Spacing Reduction*
> - We proposed Hierarchical Feature Conditional Diffusion (HiFi-Diff) for arbitrary reduction of MR inter-slice spacing, which generates any desired in-between MR slice from hierarchical features of adjacent MR slices.
> ### *Relevant Publications:*
> - <a href="https://link.springer.com/chapter/10.1007/978-3-031-45673-2_3" target="_blank">Arbitrary Reduction of MRI Inter-slice Spacing Using Hierarchical Feature Conditional Diffusion</a> [MLMI'23]
> ![](/images/MRI_SR.png)
