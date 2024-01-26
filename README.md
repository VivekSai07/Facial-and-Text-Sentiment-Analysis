# SentimentBlend: Unified Facial and Text Emotion Analysis

## Overview
This project harnesses the capabilities of machine learning, employing the Support Vector Machine (SVM) algorithm, to accurately predict facial emotions. The facial emotion predictor has been meticulously trained on a dataset consisting of manually prepared images for various emotions, each standardized to a resolution of 200x200 pixels. The dataset includes 68 facial landmarks, extracted using the dlib library, and corresponding class labels. The emotions covered include anger, happiness, sadness, contempt, fear, neutrality, surprise, and disgust.

## Features
- Emotion Classification: Accurate identification of emotions in facial expressions.
- SVM Algorithm: Utilizes the Support Vector Machine algorithm for robust prediction.
- Dataset Preparation: Images manually collected, standardized, and annotated with 68 facial landmarks.
- Versatile Applications: Potential uses in psychology research, marketing, and virtual reality experiences.

## Dataset Preparation
**Collection of Images**
The dataset used in this project has been meticulously prepared by collecting images that express different emotions. Each image is standardized to a resolution of 200x200 pixels to ensure consistency and optimal model training.

**Facial Landmark Extraction**
To enhance the understanding of facial features, the dlib library is employed to extract 68 facial landmarks from each image. These landmarks provide key points on the face, aiding the model in capturing nuanced expressions.

**Annotation in Excel Sheet**
The extracted facial landmarks are organized in an Excel sheet along with their corresponding class labels representing different emotions. This annotation process ensures a structured and labeled dataset for training and testing the facial emotion predictor.

**Class Labels**
The emotions covered in the dataset include anger, happiness, sadness, contempt, fear, neutrality, surprise, and disgust. Each image is associated with the appropriate class label, facilitating supervised learning for emotion classification.

**Standardization**
All images and corresponding annotations are standardized to maintain a consistent format, enabling seamless integration into the machine-learning pipeline. This standardized dataset forms the foundation for training the Support Vector Machine (SVM) model for accurate emotion prediction.

## Contributions
If you're interested in contributing to this project, feel free to fork the repository, create a new branch, and submit a pull request. Your contributions are highly appreciated!
