# Mild Cognitive Impairment Classification Using Deep Learning on MRI Images

## Overview

This project presents a novel deep learning approach for the enhanced multiclass classification of Mild Cognitive Impairment (MCI), an intermediate stage between normal cognitive aging and Alzheimer's disease. The study leverages the strengths of precise hippocampal segmentation and multi-model feature extraction to improve diagnostic accuracy.

## Project Highlights

- **Dataset**: The Alzheimer's Disease Neuroimaging Initiative (ADNI) dataset was utilized for this study, focusing on MRI brain images.
- **Segmentation**: A hippocampus autoencoder was employed to accurately isolate the hippocampus, a brain region particularly susceptible to MCI-related changes.
- **Feature Extraction**: Image features were extracted using multiple deep learning architectures, including hippocampus CNN, InceptionV3, and MobileNet.
- **Classification**: Various deep learning (DL) and machine learning (ML) classifiers were evaluated, with the highest accuracy of 95.6% achieved using hippocampus CNN-extracted features coupled with either a CNN or random forest model.
- **Four-Class Categorization**: The project provides a nuanced diagnostic approach by categorizing images into four cognitive states—Cognitively Normal (CN), Early MCI (EMCI), Late MCI (LMCI), and MCI.

## Key Contributions

1. **MRI Direct Classification**: The project categorizes brain images from MRI scans into four distinct cognitive states using a range of deep learning models, including CNN, ResNet, VGG16, InceptionV3, and MobileNet.
2. **Hippocampal Segmentation**: Accurate segmentation of hippocampal regions within MRI images was performed using a hippocampus autoencoder, followed by pre-processing and classification of the segmented images.
3. **Feature Extraction**: Advanced feature extraction techniques were applied to the segmented images using hippocampus CNN, MobileNet, and InceptionV3 architectures. These features were then classified using various machine learning and deep learning techniques.
4. **Performance Evaluation**: The performance of the classification models was rigorously evaluated using metrics such as Area Under the Curve - Receiver Operating Characteristic (AUC-ROC), accuracy, F1-score, precision, and recall.

## Project Structure

- **data/**: Contains the ADNI dataset used for training and testing the models.
- **models/**: Includes the deep learning architectures (e.g., CNN, ResNet, VGG16, InceptionV3, MobileNet) and machine learning classifiers used for the project.
- **notebooks/**: Jupyter notebooks detailing the data preprocessing, model training, and evaluation processes.
- **results/**: Stores the outputs, including model performance metrics and visualizations.
- **scripts/**: Python scripts for data loading, model training, and evaluation.

## Architecture Diagram
![image](https://github.com/user-attachments/assets/850e0da6-8056-449d-861f-433e1bf62c33)
![image](https://github.com/user-attachments/assets/15ffc1c6-db5c-4484-825b-686a93fbd7a6)



