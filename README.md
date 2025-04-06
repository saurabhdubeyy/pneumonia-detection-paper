# Pneumonia Detection using CNN through Chest X-Ray

This repository contains a research paper on pneumonia detection using Convolutional Neural Networks (CNNs) with chest X-ray images. The paper explores the use of the ResNet-18 architecture with transfer learning for this medical imaging task.

## Abstract

Pneumonia remains a significant global health challenge, requiring accurate and timely diagnosis to reduce its high morbidity and mortality rates. This study investigates the use of pre-trained ResNet-18 architecture with transfer learning to improve pneumonia detection in chest X-ray (CXR) images. A deep learning pipeline was developed, fine-tuned using ImageNet pre-trained weights, and modified to classify binary outcomes (normal vs. pneumonia). The model was trained on a labeled dataset of 5,856 CXR images over 10 epochs using cross-entropy loss and the Adam optimizer, achieving a validation accuracy of 95.16% and a test accuracy of 81.09%. These findings underscore the effectiveness of ResNet-18 in identifying pneumonia but reveal discrepancies between validation and test performance, highlighting the need for further optimization through advanced augmentation techniques and hybrid architectures to enhance generalization for clinical applications.

## Paper Structure

- Introduction
- Literature Review
- Methodology
- Results
- Discussion
- Conclusion
- References

## Technical Details

The paper is formatted in LaTeX using the IEEE conference template (IEEEtran) with a two-column layout. The research explores pneumonia detection through chest X-rays using the ResNet-18 architecture with transfer learning. 