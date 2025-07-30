INTRODUCTION

Magnetic Resonance Imaging (MRI) is a commonly used non-invasive technique 
for brain tumor diagnosis.

Proposes a brain tumor region detection method using multimodal information 
fusion and Convolutional Neural Networks (CNNs).

Different MRI modalities (T1ce, T2, Flair) provide complementary information about 
brain tissue characteristics and Combining multiple MRI modalities enhances the 
ability to differentiate tumor regions from healthy brain tissue.

Convolutional Neural Networks (CNNs) have demonstrated high accuracy in image 
recognition tasks.

 Extends 2D-CNNs to 3D-CNNs to extract tumor features across different MRI 
modalities.
 
 Using 3D-CNNs for brain tumor region detection enables the extraction of spatial 
and volumetric features from 3D MRI scans.

DATASET PREPARATION:BraTS 2020

The dataset used for this project is sourced from the Kaggle repository, intended for Machine Learning Model development.
The BraTS (Brain Tumor Segmentation) 2020 dataset is a widely used benchmark in the medical imaging community for brain tumor detection and segmentation. It provides pre-operative multimodal MRI scans of glioma patients, along with expert-labeled ground truth segmentations.

METHODOLOGY


1. Data Preprocessing
2. Custom Data Generator
3. 3D U-Net Model Architecture
4. Loss Function & Optimization
5. Training & Validation
6. Model Evaluation
7. Comparison Between two models
8. Desktop user interface was created using pyQt. 


