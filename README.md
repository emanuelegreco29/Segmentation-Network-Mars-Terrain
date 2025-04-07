# Mars Terrain Segmentation Network 🚀🛰️

This project focuses on semantic segmentation of 64x128 grayscale images of Mars terrain. Our goal is to classify every pixel into one of five terrain categories—all while training our networks entirely from scratch (no pretrained models allowed)!

## Overview
In this project, we tackle the challenge of pixel-wise segmentation on Mars terrain images. Each image is segmented into distinct terrain types, providing valuable insights into the Martian surface. The task is challenging due to significant class imbalance and the strict requirement to build models from scratch.

### Project Highlights
- **Semantic Segmentation:** Classify every pixel of Mars terrain images into five different classes.
- **Scratch-Built Models:** All models are developed and trained from scratch—pretrained architectures are not used.
- **Innovative Architectures:** We experimented with various UNet variants (including dual UNet structures) and even explored approaches like DeepLabV3+ with ResNet.
- **Advanced Loss Functions:** Our experiments include the use of Sparse Categorical Crossentropy, Dice Loss, Jaccard Loss, and combined loss strategies to tackle class imbalance.
- **Data Augmentation:** Implemented creative augmentation techniques to enhance model generalization and robustness. 🎨

## Further Details
This README provides a high-level overview of the project. For further details about our experimental setup, analysis, and results, consult the full [report](https://github.com/emanuelegreco29/Segmentation-Network-Mars-Terrain/blob/5a3e1a873acb988dbd1540fa0949233b68220216/Johnny%20Deep%20(Learning)%20-%20HW2%20Report.pdf). It includes comprehensive insights into every aspect of the project from data preprocessing to final model evaluation.

## Final Grade
**5.5/5.5**

## Team
- **Andrea Giangrande**
- **Marta Giliberto**
- **Emanuele Greco**
