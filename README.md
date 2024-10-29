# Dog Breed Identification

This project leverages transfer learning to identify dog breeds from dog images. Using TensorFlow and Keras, MobileNet V2 is trained on a diverse dataset of dog breeds.
</br>

![labarador](https://github.com/user-attachments/assets/00fd8ccb-399b-41ce-8590-31deb35b8899)


## Features
- Classifies images into various dog breeds.
- A total of 120 unique dog breeds.
- Utilizes a user-friendly interface via Streamlit (coming soon).


## Dataset
The model is trained on a comprehensive dataset from Kaggle containing images of multiple dog breeds.
- (https://www.kaggle.com/c/dog-breed-identification)
</br>

## Model Training
The model employs transfer learning with MobileNet V2, which includes:

- Data Augmentation: To enhance model robustness by creating variations of the training images.
- Early Stopping: To prevent overfitting by stopping training when the validation loss stops improving.
- Performance Metrics: Accuracy and loss are tracked during training, with visualizations provided.
</br>

## Installation
To set up the project, clone the repository and install the required libraries:
- Pandas
- Numpy
- MatplotLib
- TensorFlow
- Keras


```bash
git clone https://github.com/sreejith2005/Dog-Breed-Identification.git
cd Dog-Breed-Identification
pip install -r requirements.txt
