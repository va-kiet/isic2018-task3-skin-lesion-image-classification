# Skin lesion images classification
* This repo was run on colab notebook.
* Build a custom dataset and custom model to classify 7 classes of skin lesion images from [ISIC challenge 2018 task3 dataset](https://challenge.isic-archive.com/data/#2018)
* Try to use multiple backbones and evaluate their performace.
* Training phase was in 25 epochs

## ResNet101:
* Model size: 171MB
* Validate accuracy reached its peak at 0.8238 in 15th epoch.
* Prediction for test dataset hit 0.7533 accurate while its macro f1 score was 0.5725.

## VGG19:
* Model size: 548MB
* Validate accuracy reached its peak at 0.7461 in 8th epoch.
* Prediction for test dataset hit 0.6832 accurate while its macro f1 score was 0.4038.
