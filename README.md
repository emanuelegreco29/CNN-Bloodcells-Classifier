# CNN for bloodcells Classification Problem

This project aims to develop a robust model for multi-class classification of blood cell images while optimizing accuracy and computational efficiency.

## Project Scope
In this project, we addressed the challenge of classifying 96x96 RGB blood cell images. Our goal was to create a model capable of generalizing well on unseen and potentially augmented datasets, all while keeping an eye on computational efficiency and storage requirements. The entire project has been tested on the **CodaBench** platform, while the notebooks have been run on **Google Colab**.

## Experiments
| **Model**               | **Augmentation** | **Validation Accuracy** | **Test Accuracy**   |
|-------------------------|------------------|-------------------------|---------------------|
| Custom VGG16            | No               | 98.41%                  | 98.58%              |
| Custom VGG16            | Yes              | 22.41%                  | 22.83%              |
| MobileNetV3             | No               | 92.64%                  | 91.05%              |
| MobileNetV3             | Yes              | 74.16%                  | 74.41%              |
| ResNet50V2              | No               | 88.71%                  | 90.13%              |
| ResNet50V2              | Yes              | 41.56%                  | 43.65%              |
| InceptionV3             | No               | 18.14%                  | 17.47%              |
| InceptionV3             | Yes              | 14.30%                  | 14.72%              |
| EfficientNetV2M         | No               | 97.83%                  | 97.66%              |
| EfficientNetV2M         | Yes              | 98.66%                  | 98.41%              |

A thorough and extensive explaination of all the steps and phases of our project can be found in the [report](https://github.com/emanuelegreco29/CNN-Bloodcells-Classifier/blob/1cc240759318436964ded39c08f09dc145fcc303/Johnny%20Deep%20(Learning)%20-%20HW1%20Report.pdf).

## Team
- **Andrea Giangrande**
- **Marta Giliberto**
- **Emanuele Greco**
