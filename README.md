# A Convolutional Neural Network for CIFAR-10

## Project Objective:

In this task, I am to build multi-class classification models using tensorflow.keras libraries on the CIFAR-10 dataset. The targated macro accuracy is at least 80%.

## Dataset

CIFAR-10 dataset, which consists of 60,000 32x32 colour images in 10 classes, with 6,000 images per class. There are 50,000 training images and 10,000 test images.

## Models for performance comparison
- Model 1. Build a linear model
- Model 2. Build a deeper model using three hidden layers with number of neurons in (512, 256, 512) and the rectified linear unit as the activation function
- Model 3. Build a deep model having 9 layers: (2 convoluted filter 2D + 1 Maxpooling) x 3, using l2 regularization and dropout

Note: In the model 3, heavy regularizations are applied to avoid over-fitting. Data augmentation is then applied to further improve model performance.

## Hyper-parameters
- Learning_rate = 0.001 #default learning rate
- Epochs = 20
- Batch_size = 32 #default batch size

## Results

Accuracy of my best model: 81.43% 

## Further improvements
- Experimenting with other deep model architectures (e.g. VGG-16)
- Please note that in this project, I did not finetune hyper-parameters. Rather, the hyper-parameters are fixed in advance as a way to make the task more challenging for me. Thus, parameters fine-tuning will be highly likely to improve my model's performance.

