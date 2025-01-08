# Performing-Facial-Recognition-with-Deep-Learning

## Objective
This project focuses on creating a facial recognition tool using a Convolutional Neural Network (CNN) and a dataset from Kaggle. The aim is to develop a baseline model for recognizing faces and enhancing existing features for healthcare applications.

## Context
The project is inspired by Face2Gene, an AI-based healthcare app designed to assist doctors in diagnosing genetic disorders. The app converts patient images into mathematical facial descriptors for comparison with syndrome-specific classifiers, aiding in syndrome prioritization and annotation. This project aims to build a foundational facial recognition model to further improve the app's features.

## Dataset
- **Source**: [Kaggle - ORL Database of Faces](https://www.kaggle.com/datasets/kasikrit/att-database-of-faces)
- **Details**:
  - 400 images of 40 subjects.
  - Varying conditions: lighting, facial expressions, glasses, etc.
  - Image size: 92x112 pixels, 256 grayscale levels.

## Steps Undertaken
1. **Data Preparation**:
   - Imported relevant packages and dependencies.
   - Uploaded and visualized sample images from the dataset.
   - Split data into training and testing sets.
   - Preprocessed images for input into the CNN model.

2. **Model Building**:
   - Designed a CNN model architecture tailored for face recognition.
   - Trained the model using the preprocessed data.

3. **Evaluation**:
   - Assessed the model's performance on the test dataset.
   - Iteratively adjusted the model to achieve approximately 90% accuracy.

## Results
- Achieved a baseline accuracy of ~90%.
- Demonstrated robust recognition of faces under varying conditions.

## Tools & Technologies
- **Framework**: TensorFlow/Keras (or equivalent deep learning framework).
- **Platform**: Google Colab for code execution and training.
- **Programming Language**: Python.

## How to Use
1. Clone this repository.
2. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/kasikrit/att-database-of-faces).
3. Follow the provided Jupyter Notebook for step-by-step implementation.

## Future Work
- Experiment with advanced architectures like ResNet or MobileNet for improved accuracy.
- Explore transfer learning for faster convergence.
- Extend the model for multi-class facial recognition scenarios.

## Acknowledgements
- Dataset: ORL Database of Faces ([Kaggle](https://www.kaggle.com/datasets/kasikrit/att-database-of-faces)).
- Inspiration: Face2Gene healthcare app.

---

## Keywords
- #DeepLearning
- #FacialRecognition
- #Kaggle
- #GoogleColab
- #Python
- #AI
- #HealthcareAI
- #ComputerVision

