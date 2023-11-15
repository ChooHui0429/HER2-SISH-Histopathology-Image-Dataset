# A Comparative Analysis of HER2-SISH Histopathology Image Classification Using Deep Neural Networks
This work is prepared to be published in IEEE Transactions on Medical Imaging.

## Introduction
This research discovers the application of deep learning techniques for the classification of HER2-SISH (silver-enhanced in situ hybridization) pathological images, with the primary objective of determining their HER2/Chr17 amplification status. Current decisions on the status are made by the pathologist by manually counting the signals inside the nuclei to get the HER2/Chr17 ratio. Our approach involved the deployment of seven pre-trained models, comprising four convolutional neural networks (CNNs), specifically DenseNet, MobileNet, Inception, and ResNet, in addition to three transformer models, namely the Vision Transformer, Data-Efficient Image Transformers, and Mobile Vision Transformer. The process involved the creation of multiple dataset versions, followed by an attentive refining process, making use of a private dataset sourced from a collaborating hospital. A range of preprocessing techniques were applied to ensure the integrity of the dataset, reliability, and precision. Here, we presented a comprehensive comparative assessment of the proposed methodologies including the effectiveness of the Trans- formers/CNNs approach in handling uncertainty within the HER2-SISH dataset. MobileNet v2 is yielding an impressive 98.04% accuracy, surpassing the single model approach and establishing itself as the best model for HER2-SISH classification tasks. This research has a significant leap forward in assisting pathologists in the important decision of gene amplification status in HER2-SISH breast cancer pathological images.

## Dataset
All datasets utilized in this research will be made publicly available on the repository, organized into three distinct parts :
1. Original
2. Final Dataset
3. Real test case

### Original
The folder labeled **Original** will contain all the original Region of Interest (ROIs) full-size images without any data preprocessing. This includes images from both the Final Dataset and Real Test Case. The intention is to provide open access to the public, allowing them to apply their own ideas and methods to potentially achieve more advanced results in the future.

### Final Dataset
The folder named **Final Dataset** will house the ultimate version of the dataset used in our research. This dataset has undergone preprocessing according to the methods outlined in the published journal.

### Real test case 
The **Real test case** folder contains the dataset used to evaluate the generalization ability of our best model from each pre-trained model after completing the entire training process. Notably, the ROIs in this dataset are derived from real-life cases, featuring image patterns entirely different from those in the training dataset.

## Collaborative Lab
1. <a href="https://viprlab.github.io/" target="_blank">Visual Processing (ViPr) Lab, Multimedia University (MMU)</a>
2. Artificial Intelligence For Digital Pathology (AI4DP) Lab, Multimedia University (MMU)
3. Department of Pathology, University Malaya Medical Center (UMMC)
