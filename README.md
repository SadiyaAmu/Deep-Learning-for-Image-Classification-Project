# Deep-Learning-for-Image-Classification-Project
# CSC 578 Intel Image Classification Competition (Fall 2023)

## Overview
This repository contains my work for the CSC 578 Intel Image Classification Competition, conducted in Fall 2023. It includes various Convolutional Neural Network (CNN) models constructed and iteratively refined for optimal performance in image classification tasks.

## Author
- **Name:** Sadiya Amreen
- **Kaggle Username:** SADIYA AMREEN123

## Best Model
- **Kaggle Score:** Private: 0.97754, Public: 1.01072
- **Model:** Model 12
- **Key Specifications:**
  - Filters: 16, 32, 64 (layer-wise)
  - Padding: Added
  - Strides: Added
  - Additional Layer: 1
  - Batch Normalization: Added
  - Optimizer: Adam (best performance among Adam, Adamax, Adagrad, Adadelta)

## Approach
The approach involved systematic hyperparameter tuning, focusing on aspects such as number and size of filters, padding, strides, additional layers, regularizers (L1, L2, L1L2), dropout, batch normalization, and data augmentation.

## Models and Experiments
- **Initial Models:** Exploration of basic CNN architectures with varying layers and hyperparameters.
- **Model Refinement:** Detailed experiments leading to the final Model 12, including testing different regularizers, optimizers, and architecture adjustments.
- **Optimizer Experiments:** Comparative analysis of Adamax, Adagrad, and Adadelta.
- **Regularization Techniques:** Investigation into L1, L2, and L1L2 regularizations.

## Final Conclusion
Model 12 emerged as the best model, striking a balance between model complexity and generalization capabilities. It demonstrated the highest validation accuracy among all experimented architectures.

## Reflections
This project presented a significant learning curve and required extensive effort beyond regular class hours. It offered deep insights into CNN architectures and image classification, enhancing my practical skills in machine learning and data science.

## Repository Structure
- `models/`: Contains the different CNN models developed during the competition.
- `experiments/`: Detailed logs and analysis of various experiments conducted.
- `results/`: Final results and comparative analysis of different models.

## Installation and Usage
Instructions for setting up the environment, installing dependencies, and running the models are provided in separate documentation.

## License
This project is open source and available under the [MIT License](LICENSE).

## Acknowledgements
I would like to thank the course instructors and my peers for their guidance and support throughout this project.
