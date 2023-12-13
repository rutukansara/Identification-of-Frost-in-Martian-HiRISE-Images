# Identification of Frost in Martian HiRISE Images
## Usage

### Requirements

- Python
- Jupyter Notebook
- Keras
- TensorFlow
- PIL (Pillow)
- OpenCV
- Matplotlib

### Data Augmentation and Preprocessing

To perform data augmentation and preprocessing for the CNN and EfficientNetB0 model:

1. Open `dataAugmentation.ipynb` for data augmentation.
2. Open `dataPreprocessing_CNN_EfficientNetB0.ipynb` for data preprocessing and CNN model + EfficientNetB0 (A pre-trained model for Transfer Learning).

### Transfer Learning

To train and evaluate the transfer learning models:

1. Open `transfer learning.ipynb` for transfer learning using ResNet50, and VGG16.

## Results

The project achieves promising results in Martian frost detection, as shown in the classification report and confusion matrix.

## Acknowledgments

- NASA Jet Propulsion Laboratory (JPL) for providing the Martian terrain dataset.
- The project is a part of the final assessment for the DSCI 552 course on Machine Learning for Data Science at the University of Southern California (USC).
- You can find the dataset (data.zip file) in https://dataverse.jpl.nasa.gov/dataset.xhtml?persistentId=doi:10.48577/jpl.QJ9PYA
  
Feel free to contribute or provide feedback!
