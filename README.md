# isic2018_task3
* This repo was run on colab notebook.
* Build a custom dataset and custom model to classify 7 classes of skin lesion images from [ISIC challenge 2018 task3 dataset](https://challenge.isic-archive.com/data/#2018)
* Try to use multiple backbones and evaluate their performace.

## ResNet101:
* Model size: 548MB
* Training phase was in 25 epochs, validate accuracy reached its peak at 0.8238 in 15th epoch.
* Prediction for test dataset hit 0.7533 accurate while its macro f1 score was 0.5725.
