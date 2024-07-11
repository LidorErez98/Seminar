# Mapping Photovoltaic Systems using U-Net

## Overview
This repository contains the research work on mapping solar photovoltaic (PV) systems in off-grid Bedouin settlements in the Negev using the U-Net deep learning architecture.

## Abstract
The study aims to automate the detection and mapping of PV systems using high-resolution satellite images from 2017 and 2020. The U-Net model was trained and evaluated, achieving the following metrics on the testing set:

* Precision: 0.337
* Recall: 0.201
* Intersection over Union (IoU): 0.144

## Key Components
1. Data Collection and Preprocessing
   
   a. High-resolution satellite images were collected and manually digitized.

   b. Images were segmented into 256x256 patches and labeled for training and testing.

2. U-Net Model Implementation
   
   a. The U-Net architecture was used for semantic segmentation of PV systems.

   b. Training involved a custom loss function combining focal and dice loss to address class imbalance.

3. Model Training and Evaluation
   
   a. The model was trained on the processed dataset and evaluated on separate test data.

   b. Results indicated challenges due to the imbalanced dataset and complex imagery.

4. Results and Discussion
   
   a. The model achieved reasonable training and validation losses but struggled with precision and recall.

   b. Proposed improvements include data augmentation, advanced loss functions, model architecture modifications, and optimizer adjustments.

## Implications
This research provides a framework for automating PV system mapping, essential for renewable energy policy and infrastructure development in off-grid communities.

## Conclusion
While the current model has limitations, the study lays the groundwork for future improvements and applications in similar challenging environments.

## Files in Repository

code/: contains the u-net architecture, training and evaluation scripts.

seminar/: contains the seminar work.
