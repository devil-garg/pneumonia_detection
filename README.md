# Pneumonia Detection using Deep Learning

This project implements and compares three deep learning models (ResNet, DenseNet, and VGG16) for the detection of pneumonia in chest X-ray images.

## Dataset

The project uses the Pneumonia dataset from [Kaggle](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia) , which contains chest X-ray images categorized into pneumonia and normal cases.

## Models

Three state-of-the-art convolutional neural network (CNN) architectures were implemented and trained:

1. ResNet
2. DenseNet
3. VGG16

Each model was trained for 25 epochs on the dataset.

## Results

After training, the best performance was achieved by the VGG16 model:

- Training Accuracy: 97%
- Validation Accuracy: 91%

## File Structure

```
.
├── data_set/
│   └── test/
├── .gitattributes
├── DenseNet_pneumonia_epoch_25.h5
├── DenseNet_pneumonia_epoch_25.ipynb
├── ResNet_epoch_25.ipynb
├── ResNet_pneumonia_epoch_25.h5
├── VGG16_epoch_25.ipynb
├── VGG16_pneumonia.h5
├── VGG16_pneumonia_epoch_25.h5
└── X ray pneumonia detection.ipynb
```

## Usage

To replicate the results or use the trained models:

1. Clone this repository
2. Install the required dependencies 
3. Run the Jupyter notebooks for each model to train and evaluate

## Future Work

- Fine-tune the models to improve validation accuracy
- Experiment with ensemble methods to combine the strengths of different models
- Collect and incorporate more diverse data to improve generalization

## colab link
https://colab.research.google.com/drive/1XQofKtEuddoC-001eigxMtMc5O5lLE84#scrollTo=75OhZ0ZndXpB



