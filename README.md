# Sign Language Classifier 

This notebook contains a classifier for American Sign Language based on Convolutional Neural Network built using Tensorflow framework.
The dataset used here is obtained from Kaggle website from the Sign Language MNIST datset and can be obtained from given link: https://www.kaggle.com/datamunge/sign-language-mnist

The American Sign Language letter database of hand gestures represent a multi-class problem with 24 classes of letters (excluding J and Z which require motion).

Following steps are performed:
1. Load Dataset
2. Preprocessing and Data Augmentation (using ImageDataGenerator)
3. Model Building
4. Model Training and Evaluation
5. Visualizing Accuracy and Loss on Training and Validation Data
6. Prediction with custom uploaded image