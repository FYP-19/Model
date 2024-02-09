# Model Implementation


## Project Overview

In this project, we implemented transfer learning using five different base models to train our custom dataset. The goal was to leverage the pre-trained features of well-known models and adapt them to our specific domain. Subsequently, we applied a weighted averaging ensemble method to improve the overall model accuracy by combining the strengths of individual models.

## Transfer Learning Base Models

1. **MobileNetV2**

2. **ResNet50**

3. **DenseNet121**

4. **EfficientNetV2B0**

5. **NASNetMobile**

## Weighted Averaging Ensemble Model

After training the individual models, we implemented a weighted averaging ensemble model to combine their predictions effectively. The weights assigned to each model were fine-tuned based on their individual performance and contribution to the overall accuracy.


This ensemble approach allowed us to achieve a significant improvement in accuracy compared to individual models, showcasing the effectiveness of combining diverse transfer learning models for enhanced performance.

Feel free to explore the project code and experiment with different model combinations to tailor the solution to your specific requirements.

## How to Replicate

To replicate our results or further experiment with the models, follow these steps:

1. Clone the repository.
2. Download the necessary datasets and preprocess them.
3. Train the individual transfer learning models using the provided scripts.
4. Fine-tune the weights for the ensemble model.
5. Evaluate the ensemble model on your test dataset.


