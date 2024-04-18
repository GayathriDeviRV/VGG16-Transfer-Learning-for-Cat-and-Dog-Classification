# VGG16-Transfer-Learning-for-Cat-and-Dog-Classification
Cat vs. Dog image classification using VGG16 transfer learning

This project aims to classify images of cats and dogs using transfer learning with the VGG16 pre-trained model.

## Dataset
The dataset used for this project can be found on Kaggle: [Cat and Dog Dataset](https://www.kaggle.com/datasets/tongpython/cat-and-dog).

## Requirements
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Pandas
- scikit-learn

## Usage
1. **Dataset Preparation**: Download the dataset from the provided link and place it in the desired directory. Ensure that the dataset is structured with separate folders for cats and dogs.

2. **Setting Up**: Open the Jupyter Notebook (`catvsdog.ipynb`) in Google Colab or any Python environment with the required libraries installed.

3. **Training the Model**: Follow the instructions in the notebook to train the model using the VGG16 pre-trained model with transfer learning.

4. **Evaluation**: After training, the notebook evaluates the model's performance on the test dataset and generates a confusion matrix to visualize the results.

## Results
After training for 10 epochs, the model achieved a test accuracy of approximately 95.41%.
