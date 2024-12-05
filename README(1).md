# 3D_Brain_Tumor_Segmentation_UNET3D
Segmentation of brain tumor from the 3D brain MRI data using UNET_3D.
## Overview
UNET_3D algorithm is used to segment the brain tumor from the 3D MRI data provided by Medical Image Computing and Computer Assisted Interventions (MICCAI) [BraTS data](https://www.kaggle.com/awsaf49/brats20-dataset-training-validation)
## Dependencies
The entire code is written in google Colab as it provides free GPU and the entire code is compiled in cloud with out any pressure on the computer.
## Usage
Download the repository using the download option or
```bash
git clone https://github.com/SanthoshChintu/3D_Brain_Tumor_Segmentation_UNET3D
```
Download the training data from
```bash
https://www.kaggle.com/awsaf49/brats20-dataset-training-validation
```
Now upload the entire folder to the google drive.

Open the UNET_3D.ipynb file with Colab (install Colab extension for your drive if you are using it for the first time).

Set EPOCHS and BATCH_SIZE to the desired values based on the size of dataset.

Set Continue_training to the highest value file in training_checkpoints to load the pre-trained models or set to 0 if there no pre-trained model.
## Output
The output for the input is shown below:
<p align="center">
  <img width="400" height="600" src="https://github.com/SanthoshChintu/3D_Brain_Tumor_Segmentation_UNET3D/blob/main/outputs/img1.jpg">
  <img width="400" height="600" src="https://github.com/SanthoshChintu/3D_Brain_Tumor_Segmentation_UNET3D/blob/main/outputs/img.jpg">
</p>
This project is still under progress and need more training.
