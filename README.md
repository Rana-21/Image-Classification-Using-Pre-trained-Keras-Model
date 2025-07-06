# Image-Classification-Using-Pre-trained-Keras-Model
  This project uses a model created with Teachable Machine to classify images and predict their categories with confidence scores.

## Project Description
This project uses a pre-trained Keras model to classify input images into different categories. It includes:

- Loading a saved Keras model (`keras_Model.h5`)
- Reading class labels from `labels.txt`
- Image preprocessing (resizing and normalization)
- Predicting the class of the input image and showing the confidence score

## Requirements
- Python 3.x
- TensorFlow (includes Keras)
- Pillow
- Numpy

Install dependencies using:

```bash
pip install tensorflow pillow numpy

